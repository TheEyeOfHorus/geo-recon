# Geo-recon
An OSINT tool built with python for performing IP Geo-location and Reputation look up.

# Setup
This tool is compactible with:
* Any Linux Operating System (Debian, Ubuntu, centOS)
* Termux

# Linux Setup
```bash
git clone https://github.com/radioactivetobi/geo-recon.git
cd geo-recon
chmod +x geo-recon.py
pip install -r requirements.txt
```
# Termux Setup
```bash
git clone https://github.com/radioactivetobi/geo-recon.git
cd geo-recon
chmod +x geo-recon.py
pip install -r requirements.txt
```
# Sample Syntax
```bash
root@kali:~/geo-recon# python geo-recon.py 138.121.128.19

░██████╗░███████╗░█████╗░  ██████╗░███████╗░█████╗░░█████╗░███╗░░██╗
██╔════╝░██╔════╝██╔══██╗  ██╔══██╗██╔════╝██╔══██╗██╔══██╗████╗░██║
██║░░██╗░█████╗░░██║░░██║  ██████╔╝█████╗░░██║░░╚═╝██║░░██║██╔██╗██║
██║░░╚██╗██╔══╝░░██║░░██║  ██╔══██╗██╔══╝░░██║░░██╗██║░░██║██║╚████║
╚██████╔╝███████╗╚█████╔╝  ██║░░██║███████╗╚█████╔╝╚█████╔╝██║░╚███║
░╚═════╝░╚══════╝░╚════╝░  ╚═╝░░╚═╝╚══════╝░╚════╝░░╚════╝░╚═╝░░╚══╝

                         By d3xt3r_182
 Github: https://github.com/radioactivetobi | Twitter: @d3xt3r_182
            Usage: python geo-recon.py <IPADDRESS> 
            


[*] Running Geo-location Check Against 138.121.128.19

Country: Brazil
Region: Piaui
City: Teresina
Organization: Itech Telecom
ISP: Itech Telecom

[*] Geo-IP Lookup Complete!!!


[*] Running Reputation Check Against 138.121.128.19

Domain: "redeitechtelecom.com.br"
Hostname: []
Usage Type: "Fixed Line ISP"
Confidence of Abuse: 100
Number Times of Reported: 982
Last Reported: "2020-08-21T16:43:12+00:00"
Whitelisted: false

The IP Address 138.121.128.19 Is Malicious and well known for SSH Bruteforce Attacks

[*] IP Reputation Look up Complete!!!
```