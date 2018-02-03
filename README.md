# Registered subdomain Downloader from Google's Certificate Transparency project

![GitHub issues](https://img.shields.io/github/issues/Justsoos/GCTdomainDownloader.svg)
[![Python 3.5](https://img.shields.io/badge/python-3.5-yellow.svg)](https://www.python.org)

### Project Description

**GCTdomainDownloader** is a subdomain list downloader from Google's Certificate Transparency project https://transparencyreport.google.com/https/certificates. Forked from https://github.com/We5ter/GSDF.

Python3.x compatible.

### Recommended Usage:

'''
proxychains4 -q python3 GCTsubDomainDL.py -d google.com -e hide
'''

or uncomment the line in GCTsubDomainDL.py and replace with your proxy settings:

'''
proxies = {'http':'http://127.0.0.1080','https':'http://127.0.0.1:1080'}
'''
