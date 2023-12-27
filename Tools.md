# Recon

## Passive: 

whois

nslookup

dig

[viewdns.info](https://viewdns.info)

[DNSdumpster](https://dnsdumpster.com)

[crt.sh](https://crt.sh)

[ICANN Lookup](https://lookup.icann.org)

[Web Archive](https://web.archive.org)

[Shodan](https://www.shodan.io)

| **Purpose** | **Commandline Example** |
| --------------|-------------------|
| Lookup WHOIS record | `whois example.com` | 
| Lookup DNS A records | `nslookup -type=A example.com` | 
| Lookup DNS MX records at DNS server | `nslookup -type=MX example.com 1.1.1.1` | 
| Lookup DNS TXT records | `nslookup -type=TXT example.com` |
| Lookup DNS A records | `dig example.com A` | 
| Lookup DNS MX records at DNS server | `dig @1.1.1.1 example.com MX` | 
| Lookup DNS TXT records | `dig example.com TXT` | 

## Active: 

ping

traceroute

telnet

| **Command** | **Example** |
| --------------|-------------------|
| ping | `ping -c 10 MACHINE_IP` on Linux or macOS | 
| ping | `ping -n 10 MACHINE_IP` on MS Windows | 
| traceroute | `traceroute MACHINE_IP` on Linux or macOS | 
| tracert | `tracert MACHINE_IP` on MS Windows |
| telnet | `telnet MACHINE_IP PORT_NUMBER` | 
| netcat as client | `nc MACHINE_IP PORT_NUMBER` | 
| netcat as server | `nc -lvnp PORT_NUMBER` | 

| **Operating System** | **Developer Tools Shortcut** |
| --------------|-------------------|
| Linux or MS Windows | `Ctrl+Shift+I` | 
| macOS | `Option + Command + I` | 

# Web 
