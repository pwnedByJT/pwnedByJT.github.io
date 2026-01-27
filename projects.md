---
layout: default
title: Operations & Code
permalink: /projects/
---

<div align="center">
  <h3>
    <a href="/">[ ./Home ]</a> &nbsp;&nbsp;
    <a href="/projects/">[ ./Operations_&_Code ]</a> &nbsp;&nbsp;
    <a href="/writeups/">[ ./CTF_Writeups ]</a>
  </h3>
</div>

<br>

# /var/www/html/projects

My approach to security is driven by automation. If I have to do it twice, I write a script for it.

### [1] Enterprise Print Queue Automation
**Role:** System Administrator | **Lang:** Python / Concord
**Impact:** Resolved 600+ annual tickets across 200+ distribution centers.

> **The Problem:** Print queues at distribution centers would frequently hang, requiring manual intervention from IT support. This stalled logistics and wasted approximately 15-20 hours of support time monthly.

> **The Solution:** Developed a Python-based automation workflow integrated with internal CI/CD (Concord). The script queries the print server status, identifies "stuck" jobs based on timestamp logic, and clears the queue without human input.

> **Security Relevance:** Demonstrates ability to interact with system APIs, handle error logging, and deploy code in a live enterprise environment securely.

---

### [2] AirTables Workflow Tool
**Role:** Developer | **Lang:** Python (GUI)
**Status:** Deployed to next-gen facilities across the US.

> **The Project:** A custom GUI application designed to track operational tasks. It replaced a fragmented spreadsheet system, allowing facility managers to view real-time task statuses.

---

### [3] Offensive Security Home Lab
**Focus:** Network Pentesting & Active Directory

I maintain an active home lab to simulate corporate environments.
* **Attack Box:** Kali Linux (Customized with pimpmykali)
* **Targets:** Metasploitable, Windows Server 2019 (AD Lab)
* **Tools:** Burp Suite Pro, Wireshark, Bloodhound

[>> View My Public Code on GitHub](https://github.com/pwnedByJT)