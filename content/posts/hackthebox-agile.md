+++
title = "Hackthebox Agile"
date = "2025-12-06T04:19:57-05:00"
#dateFormat = "2006-01-02" # This value can be configured for per-post date formatting
author = ""
draft = false
authorTwitter = "" #do not include @
cover = ""
tags = ["", ""]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
+++

# Agile - HackTheBox Walkthrough

This was a really fun machine involving an Nginx vulnerability.

## Reconnaissance
I started with a classic Nmap scan:
```bash
nmap -sC -sV 10.10.11.203
```
