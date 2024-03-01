# DNS-AXFR
Simple Python script to perform a DNS zone transfer using the AXFR protocol.

## Getting Started
Please, follow the instructions below for installing and running DNS-AXFR.py

### Pre-requisites
Make sure you have installed the following tools:
```
Python 3.0 or later.
python3-dnspython
```

### Installing
```bash
$ git clone https://github.com/KallumParker/dns-axfr.git
$ cd dns-axfr
$ chmod +x dns-axfr.py
```

### Running
```bash
$ python3 dns-axfr.py
```

## Usage
Parameters and examples of use.
```bash
$ python3 dns-axfr.py [options] -d <DOMAIN>
```

### Parameters
```
-h, --help      Show this help message and exit
-d  Domain      Target Domain. Example: example.com
-n  Nameserver  Nameservers seperated by a comma. Example:
                ns1.example.com,ns2.example.com
-v              Prints the version of DNS-AXFR.py
```