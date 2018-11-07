# Domainker
Domainker is a tool to check if a website is down or not with a multithreading support  
This tool mainly for a bounty hunters that offent get a huge list of subdomains and alot of them isn't working  
So domainker acts as a checker for the domains  

![](screenshots/0.png)

# How to use 
Basic example
```bash
$ python domainker.py -d domains.txt
```
Basic output example
```bash
$ python domainker.py -d domains.txt -o out.txt
```

Advanced example
```bash
$ python domainker.py -d domains.txt -t 50 -T 5 -rt 3 -o out.txt
```

# File format
I want add different formats at the future but currenlty this tool only support this format
```
https://sub.domain.com
http://sub.domain.com
sub.domain.com
.sub.domain.com
```
Which genrated by:
- amass
- aquatone (hosts.txt)
- subfinder
- sublist3r
- ... and many other subdomain finders
