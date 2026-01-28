---
layout: default
title: Operations & Code
permalink: /projects/
---

<div align="center" style="margin-bottom: 40px;">
  <code><a href="/">~/HOME</a></code> &nbsp;&mdash;&nbsp;
  <code><a href="/projects/">~/OPS_&_CODE</a></code> &nbsp;&mdash;&nbsp;
  <code><a href="/writeups/">~/CTF_WRITEUPS</a></code>
</div>

<div style="background: #1a1b26; border: 1px solid #2f354b; border-radius: 8px; padding: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.5); margin-bottom: 40px;">
  <div style="margin-bottom: 10px;">
    <span style="color: #ff5f56;">●</span> 
    <span style="color: #ffbd2e;">●</span> 
    <span style="color: #27c93f;">●</span>
    &nbsp; <span style="color: #565f89; font-size: 12px;">bash — 80x24</span>
  </div>
  
  <span style="color: #bb9af7;">root@pwnedByJT</span>:<span style="color: #7dcfff;">~/ops</span>$ cat philosophy.txt<br><br>
  
  <span style="color: #9ece6a;">> [READING] Opening file...</span><br>
  <span style="color: #a9b1d6;">
  My approach to security is driven by automation. If I have to do it twice, I write a script for it.<br><br>
  Below is a collection of my <b>Enterprise Automation Scripts</b> and my <b>Offensive Security Home Lab</b> configuration.
  </span>
</div>

### [ MODULE :: AUTOMATION ]

<div style="background: #0f111a; border-left: 4px solid #7dcfff; padding: 15px; margin-bottom: 20px;">
  <h3 style="margin-top: 0; color: #fff;">[1] Enterprise Print Queue Automation</h3>
  <span style="color: #565f89; font-size: 0.9em;">ROLE: SysAdmin | LANG: Python + Concord | IMPACT: High</span><br><br>
  
  <span style="color: #a9b1d6;">
  <b>The Problem:</b> Print queues at 200+ distribution centers would hang, stalling logistics and wasting 15-20 hours of IT support time monthly.<br><br>
  <b>The Solution:</b> Developed a Python automation workflow integrated with internal CI/CD. The script queries server status, identifies "stuck" jobs via timestamp logic, and clears the queue without human input.<br><br>
  <span style="color: #9ece6a;">✔ Resolved 600+ annual tickets automatically.</span>
  </span>
</div>

<div style="background: #0f111a; border-left: 4px solid #bb9af7; padding: 15px; margin-bottom: 20px;">
  <h3 style="margin-top: 0; color: #fff;">[2] Airtables Workflow Tool</h3>
  <span style="color: #565f89; font-size: 0.9em;">ROLE: Developer | LANG: Python (GUI) | STATUS: Deployed</span><br><br>
  
  <span style="color: #a9b1d6;">
  <b>The Project:</b> A custom GUI application designed to track operational tasks in next-gen facilities. It replaced a fragmented spreadsheet system, allowing facility managers to view real-time task statuses.
  </span>
</div>

<br>

### [ MODULE :: INFRASTRUCTURE ]

<div style="background: #0f111a; border-left: 4px solid #ff5f56; padding: 15px; margin-bottom: 20px;">
  <h3 style="margin-top: 0; color: #fff;">[3] Offensive Security Home Lab</h3>
  <span style="color: #565f89; font-size: 0.9em;">FOCUS: Network Pentesting & Active Directory</span><br><br>
  
  <span style="color: #a9b1d6;">
  I maintain an active home lab to simulate corporate environments for Red Team practice.
  </span>
  <br><br>
  
  <code style="color: #ff5f56;">[ ATTACK_BOX ]</code> &nbsp; Kali Linux (Customized)<br>
  <code style="color: #7dcfff;">[ TARGETS    ]</code> &nbsp; Windows Server 2019 (AD), Metasploitable<br>
  <code style="color: #bb9af7;">[ TOOLING    ]</code> &nbsp; Burp Suite Pro, Bloodhound, Wireshark
</div>

<div align="center" style="margin-top: 40px;">
  <a href="https://github.com/pwnedByJT" style="border: 1px solid #7dcfff; padding: 10px 20px; border-radius: 4px; color: #7dcfff;">
    <i class="fab fa-github"></i> VIEW SOURCE CODE ON GITHUB
  </a>
</div>