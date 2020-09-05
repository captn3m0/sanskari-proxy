# sanskari-proxy

Original idea on my [ideas repo](https://github.com/captn3m0/ideas#-sanskari-proxy).

A proxy for security researchers outside India to access Indian government websites without resorting to shady VPNs.

## Why?

- Indian government websites are often geo-blocked to India.
- Security researchers outside India have no way to access these.

## How?

- This is a simple tinyproxy configuration running on a Digital Ocean VPN in `BLR1` region.

## Access?

The Proxy configuration is as follows:

- Host: `proxy.sarkar.icu`
- Port: `8888`

The proxy supports both HTTP and HTTPS websites. Please send an email to <mailto:sanskari.proxy@captnemo.in?subject=Sanskari%20Proxy%20Access&body=Please%20add%20a%20link%20to%20some%20public%20profile%20of%20yours%20here.>

## Websites

The list of websites is filtered using a [filter](filter) file. The list was generated from 2 sources:

1. [GOI Directory](http://goidirectory.nic.in/).
2. Subdomains of `gov.in` discovered using [crt.sh](https://crt.sh).

## Configuration changes

If you'd like to add a site to the list of supported websites, please file a PR. This project has a [Code of Conduct](CODE_OF_CONDUCT.md).

## Licence [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
