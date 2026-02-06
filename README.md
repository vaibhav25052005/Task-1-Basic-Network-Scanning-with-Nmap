Basic Network Scanning with Nmap
Install Nmap
Ubuntu / Kali
sudo apt update
sudo apt install nmap -y

Verify installation
nmap --version

Scan your local machine
Find your IP
ip a

Basic scan
nmap <your-ip>


Example:

nmap 192.168.1.5

Service + version scan
nmap -sV 192.168.1.5

Save output
nmap -sV 192.168.1.5 -oN nmap_scan_results.txt
