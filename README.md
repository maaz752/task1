# task1
**1. Port 53 TCP on 192.168.1.1 – DNS (Domain Name System)**
Purpose:
Port 53 is used for DNS, which translates domain names (like google.com) into IP addresses.

Protocol: TCP (used for zone transfers or DNS over TCP; most DNS queries use UDP)

Common Usage:

DNS servers (e.g., BIND, Windows DNS)

May indicate a router or internal DNS service

Security Risks:

DNS amplification attacks if misconfigured

Zone transfer leaks if AXFR (TCP-based) is not restricted

May reveal internal DNS structure if exposed

Mitigation Tips:

Restrict zone transfers to authorized hosts

Disable public access to DNS if not needed

Use DNSSEC for added integrity
**2. Port 80 TCP on 192.168.1.2 – HTTP (Web Server**)
Purpose:
Port 80 serves unencrypted web traffic via HTTP.

. **Port 443 TCP on 192.168.1.6 – HTTPS (Secure Web Server)**
Purpose:
HTTPS provides encrypted web communication using SSL/TLS.
** Port 5679 TCP on 192.168.1.7 – Unknown / Possibly VMware Infrastructure
Purpose:
**
