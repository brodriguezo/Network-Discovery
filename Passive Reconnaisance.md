[DNSDUMPSTER](https://dnsdumpster.com/)

DNSdumpster.com is a FREE domain research tool that can discover hosts related to a domain. Finding visible hosts from the attackers perspective is an important part of the security assessment process.

[SHODAN](https://www.shodan.io)

Search Engine for the Internet of Everything

Cheatsheet 

|                Purpose               |           Commandline Example            |
|--------------------------------------|------------------------------------------|
| Lookup WHOIS record	               |  whois site.com                          |
| Lookup DNS A records	               |  nslookup -type=A site.com               |
| Lookup DNS MX records at DNS server  |  nslookup -type=MX site.com 1.1.1.1      |
| Lookup DNS TXT records	       |  nslookup -type=TXT site.com             |   
| Lookup DNS A records	               |  dig site.com A                          |
| Lookup DNS MX records at DNS server  |  dig @1.1.1.1 site.com MX                |
| Lookup DNS TXT records               |  dig site.com TXT                        |

