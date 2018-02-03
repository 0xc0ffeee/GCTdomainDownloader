# Registered subdomain Downloader from Google's Certificate Transparency project

![GitHub issues](https://img.shields.io/github/issues/Justsoos/GCTdomainDownloader.svg)
[![Python 3.5](https://img.shields.io/badge/python-3.5-yellow.svg)](https://www.python.org)

### Project Description

**GCTdomainDownloader** is a subdomain list downloader from Google's Certificate Transparency project https://transparencyreport.google.com/https/certificates. GCTsubDomainDL.py Forked from https://github.com/We5ter/GSDF.

Python3.x compatible.

### Recommended Usage:

check all registered Google.com's subdomain names:

```
proxychains4 -q python3 GCTsubDomainDL.py -d google.com -e hide
or
proxychains4 -q python3 GCTsubDomainDL.py -d google.com -e show
```

or uncomment the proxies line in GCTsubDomainDL.py and replace with your own proxy settings:

```
proxies = {'http':'http://127.0.0.1080','https':'http://127.0.0.1:1080'}
and then run:
python3 GCTsubDomainDL.py -d google.com -e hide
or
python3 GCTsubDomainDL.py -d google.com -e show
```
