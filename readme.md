<h1 align="center">
  <br>
  TheNetRecon
  <br>
</h1>

<h4 align="center">Fastest tool for Enumerate subdomain and network scanning.</h4>

<hr>

### thenetrecon is a fastest tool to detect Cross Site scripting (XSS), SQL Injection, and automatically check urls for any sensetive information. and it's also used for numerate subdomain and network scanning.

<br>

### Main Features
- Find XSS
- Find SQL Injection
- Check URL for important Information.

- Enumirating Subdomains from 4 sources
   - CertsPotter
   - SSL Certificates
   - HackerTarget
   - ThreatCrowd

- Records: 
  - TXT Records
  - CCA Records
  - SOA Records
  - MX Records
  - NS Records
  - AAAA Records
  - A Records
- Advance Error Handling

### Documentation
### install
```yaml
git clone https://github.com/Transmetal/thenetrecon-main
cd thenetrecon
python -m pip install -r requirements.txt
python3 thenetrecon.py --help
```


#### Usage

```yaml

OPTIONS:
  -h, --help            show this help message and exit
  -d DOMAIN, --domain DOMAIN
                        [required] Domain name to enumerate it's subdomains
  -o , --output         Save results in txt file.
  -i, --ignore          Ignore domains pointed to private IPs
  -f , --file           A file contains new line delimited subdomains.
  -s, --save            Save subdomains image map
  -b, --bruteforce      Enable the bruteforce scan
  -t , --threads        Number of threads. [Default 200]
  --enum [ENUM ...]     <optional> Perform enumerations and network mapping
  --full                Full scan, NAMES FILE first_names_full.txt will be used to brute
                                                                        
```
<br>
