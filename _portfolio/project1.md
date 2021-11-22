---
title: Intelligence
subtitle: IP:10.10.10.248
image: assets/img/portfolio/Intelligence/01-full.jpg
alt: hackthebox intelligence image

caption:
  title: Intelligence
  subtitle: OS:Windows LAB:Hackthebox
  thumbnail: assets/img/portfolio/Intelligence/01-thumbnail.jpg
---
# Information Gathering


***Full Nmap scan on all ports***
```
sudo rustscan -a 10.10.10.248 --range 1-65535 -- -Pn -A -sC -sV -T4 -oN ports_scan.txt
```
![This is an image](/assets/img/portfolio/Intelligence/nmap.png)

{:.list-inline}
- Date: September 2021
- Platform: Hackthebox
- Difficulty: Medium

