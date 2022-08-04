# IPSweep

A Script to Discover IP Address / Devices in a network

## Installation

```bash
git clone https://github.com/Basil-jiji/IPSweep.git
```

```bash
# To make it Executable
chmod +x ./ipsweep.sh

# To Run the Script
./ipsweep.sh
```

## Usage

Connect to the network that you want to scan

```bash
# To Sweep a range of IP Address from 192.168.230.0 to 192.168.230.255
./ipsweep 192.168.230
```

```bash
# To Run and store the IP Address into a file
./ipsweep 192.168.230 > ips.txt

# To view the stored IP Address
cat ips.txt
```
