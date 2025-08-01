---
title: "TryHackMe: SeaSurfer Writeup"
date: 2025-08-04 12:45:00 +0530
categories: [TryHackMe]
tags: [recon, ssh, walkthrough]
---

## Nmap Scan

```bash
nmap -sC -sV -oN seasurfer.txt 10.10.X.X
```

Found open SSH and a web server.

## Web Recon

Default page shows a CMS. Found a hidden login panel at `/admin`.

More details coming soon...
