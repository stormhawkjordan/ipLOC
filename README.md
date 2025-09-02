# 🌐 ipLOC VPN Checker

A lightweight and simple VPN/IP status checker script for Ubuntu based Linux distributions such as Linux Mint.  
**It Checks your VPN connection, shows your public IP, and provides detailed IP geolocation info.**

---

## 🛠 Features

- ✅ Check if your VPN is connected (via NetworkManager)
- 🌍 Display your **public IP address**
- 🧭 Fetch geolocation info: **country**, **region**, **city**, **ISP**, and **organization**
- 🔐 Detect VPN **client** and **protocol**
- 🎨 Cool ASCII banner with a retro touch cause why not

---

## 📦 Requirements

Make sure these tools are installed:

| Tool       | Purpose                         |
|------------|----------------------------------|
| `curl`     | Fetches your public IP address  |
| `jq`       | Parses JSON from API response   |
| `nmcli`    | Checks VPN status via NetworkManager |

Install them on Linux Mint / Ubuntu:

```bash
sudo apt update
sudo apt install curl jq network-manager -y

🚀 Installation
1. Clone this repository
