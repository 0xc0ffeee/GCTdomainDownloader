# Subdomain Enumeration from Google's CT Project

![GitHub issues](https://img.shields.io/github/issues/Justsoos/GCTdomainDownloader.svg)
[![Python 3.5](https://img.shields.io/badge/python-3.5-yellow.svg)](https://www.python.org)

### Project Description

**GCTdomainDownloader** is a subdomain list downloader from Google's Certificate Transparency project https://transparencyreport.google.com/https/certificates. GCTsubDomainDL.py Forked from https://github.com/We5ter/GSDF.

Python3.x compatible.

### Recommended Usage:

```
python3 GCTsubDomainDL.py -d google.com -e hide
or
python3 GCTsubDomainDL.py -d google.com -e show
```

### TODO
Reduce false positives as you may obtain domains that are not in scope.
