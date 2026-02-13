# local-network-port-scan
# Local Network Port Scanning using Nmap

## Objective
To identify active devices and open ports in the local network.

## Tools Used
- Kali Linux
- Nmap

## Network Range
192.168.29.0/24

## Commands Used

### Host Discovery
sudo nmap -sn 192.168.29.0/24

### TCP SYN Scan
sudo nmap -sS 192.168.29.0/24

### Service Version Detection
sudo nmap -sS -sV 192.168.29.1

## Files in this Repository
- host_discovery.txt
- syn_scan_results.txt
- service_version.txt
- scan.html

## Conclusion
Open ports increase attack surface. Unnecessary services should be disabled.
