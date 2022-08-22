# Host Argu on your own domain

Your Argu website is by default available at argu.co/websitename, but can also be made available from another domain or subdomain. To do this, you need to change your DNS Records in the management environment of your domain name, and pass them on to us. Which DNS Records you need to change, depends on whether you want a subdomain or not:

## On a subdomain (subdomain.example.com)

1. On the chosen subdomain, add a DNS CNAME record with the value argu.co.
1. Provide us with the URL and name of the Website on Argu at info@argu.co.

## On a main domain (example.com)

1. On the chosen domain, add an A Record with value 188.166.203.193.
1. Add an AAAA Record with value 2a03:b0c0:2:f0::229:d001
1. Provide us with the URL and name of the Website on Argu at info@argu.co.
