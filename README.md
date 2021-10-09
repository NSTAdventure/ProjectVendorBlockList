# ProjectVendorBlockList
Project to make phone vendor Telemetry blocklist


# how does it's work?
Using host to block domain you can apply
Host list on any adblock apps such as 
Personal DNS Filter etc etc 

# Warnings!
1. Pi-Hole/ Wifi Router Installation will make all 
Connected devices affected by our blocklist

2. You may cannot visit official vendor website
And (or) using vendor services

3. You may cannot update vendor devices
(In our blocklist we block some vendor update
once someone contributed or found it)

# FAQ
1. Why user must use host list to block annoyance?
Blocking website or domain only work via host list

For example:

127.0.0.1 www.example.com

Or

0.0.0.0 www.example.com

2. Why must block telemetry? Something wrong with it?.

Telemetry is designed to track you 

We block them to prevent telemetry collect and send your
Data to the company 

We also want to make vendor devices can claim back it's Privacy!

3. Do this blocklist can working on both non root
And rooted devices?

Depending on case and what app and (or) software that
Are you using

Alternative way is using firewall and
Block all system app and OTA Update

4.do host file support subdomain auto block?

Host file doesn't support of blocking SubDomains,
Eg. If you block example.com then
SubDomains of the website will not be blocked
such as www.example.com or blog.example.com
