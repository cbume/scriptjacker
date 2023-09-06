# Tool Methodology
### My tool perform a specifc methodology for recon:-
```
1. Host discovery (It check wheather the host is up or down.)
2. Firewall check (It check is there any Firewall and identify its signature.)
3. CMS Detection (Check which CMS is in use. If any)
4. DNS recon (Basically identify information related to DNS.)
5. Basic Info (Identify small and big informaton about target.)
6. Google Dorking (Perform google dorks to gather sensitve info.)
7. Github Dorking (Perform github dorking to gather sensitive info.)
8. Javascript Recon (Identify JS files and also try to extract words from it.)
9. Subdomain Enumeration (Gather many subdomains to increase attack surface.)
10. Active Subdomans (Filter the active and inactive subdomains.)
11. Network Scanning (Perform port scanning and service scanning.)
12. Subdomain Takeover (Check for subdomain takeover vulnerability.)
13. Directory Busting (Bruteforce the hidden directories and files.)
14. Grabing Parameters (It crawl the website and grab urls and parameters.)
15. Vulnerable Parameters (It filter the parameters according to the vulnerability testing.)
16. Bypass 403 (It try to bypass directories with 403 code.)
17. Vulnerability Scanning (It perform vulnerablity scanning on target.)
18. Test SQLI (It automate the SQL injaction.)
19. Test XSS (It automate the XSS tests.)
20. Test SSTI (It automate the SSTI vulnerability scan.)
21. Find Buckets (It scan for publically open buckets for target.)
```
## Important:
`This tool will work when you are a root user.`
```
sudo su
```

### Installation and Setup

#### copy github repository
```
git clone https://github.com/scriptjacker/scriptjacker.git
```

#### go inside reporitory
```cd scriptjacker```

#### give permissions
```sudo su```

chmod +x scriptjacker.sh
chmod +x install.sh

#### Run the tool
```sudo su```

```./scriptjacker.sh -h```
