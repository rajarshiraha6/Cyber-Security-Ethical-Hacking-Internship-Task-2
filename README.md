 Cyber Security Internship – Task 2  
Network Security & Scanning -

 Objective -
Learn and perform reconnaissance, network scanning, vulnerability analysis, packet sniffing, and basic firewall configuration to understand network security and traffic behavior.



Steps Performed

 Reconnaissance -
- Passive Recon: `whois`, `nslookup`, Google Dorking, Shodan.io  
- Active Recon: `ping`, banner grabbing using `nc` and `telnet`  
- Output:  `recon.txt`, `alive_hosts.txt`



Port & Service Scanning (Nmap)
Commands used:

nmap -T4 -F <target-ip> -oN nmap_quick.txt
sudo nmap -sS -sV -O --script vuln <target-ip> -oN nmap_full.txt

