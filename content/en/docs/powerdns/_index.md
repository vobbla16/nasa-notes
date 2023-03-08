---
title: "PowerDNS setup"
type: docs
description: >
    PowerDNS Authoratative/Recursor server installation and basic configuration
---

# PowerDNS Authoratative

## Installation

Install PDNS itself:
```
apt install pdns
```

Also you need to install backend for PDNS(in this guide we will use `MariaDB`, so we need to install `mysql` backend):
```
apt install pdns-backend-mysql
```
