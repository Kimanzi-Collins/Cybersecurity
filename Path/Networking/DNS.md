# DNS

**Domain Name System in Full**

It is responsible for translating domain names to IP addresses

## Domain Hierarchy

### Top-Level Domain

- Most right hand part of a domain name ie .com

There are two types:

- Generic TLD (gTLD): Meant to tell the user the domain name's purpose.
- Country Code TLD (ccTLD): Meant to tell the user the country of origin of the website.

### Second-Level Domain

- Limited to 63 characters. Mostly indicates the name of the website eg Google

### Subdomain

- Found on the left of the second-level domain. It mostly indicates an acccess level. Eg admin.google.com

## DNS Record Types

### A Record

- Records resolve to IPv4 addresses

### AAAA Record

- Records resolve to IPv6 addresses eg 2606:4700:20::681a:be5

### CNAME Record

- Records resolve to a different domain name

### MX Record

- Records resolve to the address of the servers that handle the email of the domain you're querying. They normally come with a priority flag.

### TXT Record

- Free text fields where any text-based data can be stored. Mostly used to list servers that have the authority to send an email on behalf of the domain. Can also be used to verify ownership of the domain name when signing up,for third party services