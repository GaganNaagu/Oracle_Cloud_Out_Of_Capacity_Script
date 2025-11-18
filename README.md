# 🛠 Oracle_Cloud_Out_Of_Capacity_Script

A complete guide to deploy a Python bot that helps monitor and respond to Oracle Cloud "Out of Capacity" errors. This guide covers everything from bot setup to script execution across Windows and Linux.

---

## Downloading Script

```bash
bash <(curl -s https://raw.githubusercontent.com/GaganNaagu/Oracle_Cloud_Out_Of_Capacity_Script/refs/heads/main/download_script.sh)
```

---

## 🌐 Creating VCN and Subnet (Optional)

- **Destination CIDR Block**: `0.0.0.0/0`

---

## 🌐 Operating System Images

- [**Operating System Images Webpage**](https://docs.oracle.com/en-us/iaas/images/)

---

## 🤖 Bot Configuration

- Use [**Discord**](https://discord.com/developers/applications) to create your Discord bot and get the Bot token.

---

## Runing in Docker

```bash
docker run --name oci-script -d -v $(pwd):/app --restart unless-stopped --log-opt max-size=10k --log-opt max-file=1 GaganNaagu/oci-out-of-capacity-script
```

---

## See Logs

```bash
docker logs oci-script
```

---
