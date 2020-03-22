# Squid proxy configuration with SSL support
This repo contains a working config for Squid 4.10 with SSL support
* in certs/ dir you can find the .pem certificate to be imported into your browser CA to browse webwithout errors
* in squid/ dir you can find all Squid config files 

.
├── certs
│   └── CyberSaiyan-mitm.pem
└── squid
    ├── cache
    │   └── exclude
    │       ├── contenttype.conf
    │       ├── domainaddr.conf
    │       ├── domainname.conf
    │       ├── useraddr.conf
    │       └── useragent.conf
    ├── squid.conf
    └── ssl
        ├── error
        │   ├── domains.conf
        │   └── ips.conf
        └── exclude
            ├── domains.conf
            ├── ips.conf
            ├── useraddr.conf
            └── useragent.conf
