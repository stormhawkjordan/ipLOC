# ipLOC - A simple, easy to use IP checker for Debian based distributions

ipLOC is a simple and lightweight IP status tool that can be run from one command: iploc  
 
## What does it do?

ipLOC:
- Checks if your VPN is connected
- Retrieves your public IP address
- Provides IP Geolocation (country, region, ISP, org)
- Identifies your active VPN client and protocol
- Warns you if your real IP is exposed

It is recommended to run iploc before starting a torrent or web browsing, so you dont leak your IP address. Bonus security if you bind your VPN to your torrent client!

## Requirements

This script is designed for **Debian** based Linux distributions, such as **Linux Mint** and **Ubuntu**

Make sure the following dependencies are installed:
- curl - Fetches your public IP address
- jq - Parses JSON from API response
- nmcli - Checks VPN status via NetworkManager

To install these, open a Terminal and run: 

```bash
sudo apt update
sudo apt install curl jq network-manager -y
```

## Installation

**1: Clone this repository**

```bash
git clone https://github.com/stormhawkjordan/iploc.git

cd iploc
```

**2: Make the script executable**
```bash
chmod +x iploc
```

**3 Move to /usr/local/bin to use the iploc command anywhere**

```bash
sudo cp iploc /usr/local/bin/iploc
```
## Usage

From inside the repo directory:
```bash
./iploc
```

**Globally (if moved to /usr/local/bin)**

```bash
iploc
```

## Credits
- Script by stormhawkjordan
- ASCII art via patorjk.com/software/taag
- IP Geolocation API by ip-api.com
- Readme generated with readme.so

## License
This script is released with the MIT License

You are free to use, modify and distribute it. Credit is appreciated!
