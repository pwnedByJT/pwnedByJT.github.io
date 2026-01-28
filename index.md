---
layout: default
title: Home
---

<script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.9.2/dist/confetti.browser.min.js"></script>

<div align="center" style="margin-bottom: 40px;">
  <code><a href="/">~/HOME</a></code> &nbsp;&mdash;&nbsp;
  <code><a href="/projects/">~/OPS_&_CODE</a></code> &nbsp;&mdash;&nbsp;
  <code><a href="/writeups/">~/CTF_WRITEUPS</a></code>
</div>

<div style="background: #1a1b26; border: 1px solid #2f354b; border-radius: 8px; padding: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
  <div style="margin-bottom: 10px;">
    <span style="color: #ff5f56;">●</span> 
    <span style="color: #ffbd2e;">●</span> 
    <span style="color: #27c93f;">●</span>
    &nbsp; <span style="color: #565f89; font-size: 12px;">bash — 80x24</span>
  </div>
  
  <span style="color: #bb9af7;">root@pwnedByJT</span>:<span style="color: #7dcfff;">~</span>$ <span data-sys-id="PWNED{H7ML_S0urc3_C0d3_M4st3r}" data-trigger="unlock()">whoami</span><span class="blinking-cursor">_</span><br><br>
  
  <span style="color: #9ece6a;">> [SUCCESS] Loading user profile...</span><br>
  <span style="color: #a9b1d6;">
  I am a <b>Systems Administrator at Walmart</b> and a Computer Science student at SNHU (Class of '26).<br><br>
  Currently bridging the gap between <b>Defense (Blue Team)</b> and <b>Offense (Red Team)</b>. My infrastructure background means I don't just find the vulnerability—I understand the business risk behind it.
  </span>
</div>

<br>

### [ MODULE :: CERTIFICATIONS ]
**CompTIA**<br>
[![CompTIA PenTest+](https://img.shields.io/badge/CompTIA-PenTest+-ff5555?style=for-the-badge&logo=comptia&logoColor=white)](https://www.credly.com/badges/71494342-7ae1-44c3-8d5f-a41543060868)
[![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security+-ff5555?style=for-the-badge&logo=comptia&logoColor=white)](https://www.credly.com/badges/bdfa7897-7892-4dfd-b29f-f9c12498f058/public_url)
[![CompTIA Network+](https://img.shields.io/badge/CompTIA-Network+-ff5555?style=for-the-badge&logo=comptia&logoColor=white)](https://www.credly.com/badges/794a9032-0e1f-4b3b-8a33-739bf8eaeb0c/public_url)
[![CompTIA A+](https://img.shields.io/badge/CompTIA-A+-ff5555?style=for-the-badge&logo=comptia&logoColor=white)](https://www.credly.com/badges/51f607b1-440b-43fd-8f82-47eb07de5e8a/public_url)

**Microsoft**<br>
[![Azure Fundamentals](https://img.shields.io/badge/Microsoft-Azure_Fund-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://www.credly.com/badges/b05ff049-5b67-4d36-95e6-f2108c0eecd6/public_url)
[![SC-900](https://img.shields.io/badge/Microsoft-Security_Fund-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://www.credly.com/badges/7795d30e-7866-4e20-90b9-2436b06354ea/public_url)

<br>

### [ MODULE :: ARSENAL ]
**Offensive Tools**<br>
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)

**Automation**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Bash](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)

<br>

### [ MODULE :: UPLINK ]
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/justin-turner-3b41031b8/)
[![GitHub](https://img.shields.io/badge/GitHub-View_Code-181717?style=for-the-badge&logo=github)](https://github.com/pwnedByJT)
[![Resume](https://img.shields.io/badge/Resume-Download_PDF-FF0000?style=for-the-badge&logo=adobeacrobatreader)](/Justin_Turner_Resume.pdf)

<br><br>

[![TryHackMe](https://tryhackme-badges.s3.amazonaws.com/Justin.Turner.png)](https://tryhackme.com/p/Justin.Turner)
[![Hack The Box](https://www.hackthebox.eu/badge/image/2203566)](https://app.hackthebox.com/profile/2203566)

<script>
  // 1. SILENT MODE: No instructions printed.
  // The user must find the function "unlock()" by inspecting the HTML code above.
  
  console.log("%c[+] SYSTEM READY. DEBUGGING PORT OPEN.", "color: #27c93f; font-family: monospace; font-size: 12px;");

  window.unlock = function() {
    let attempt = prompt("Please enter the system flag:");
    
    if (attempt === 'PWNED{H7ML_S0urc3_C0d3_M4st3r}') {
      
      // CONFETTI LOGIC
      // Changed duration from 3 seconds to 15 seconds
      var duration = 15 * 1000;
      var animationEnd = Date.now() + duration;
      var defaults = { startVelocity: 30, spread: 360, ticks: 60, zIndex: 0 };

      var interval = setInterval(function() {
        var timeLeft = animationEnd - Date.now();
        if (timeLeft <= 0) {
          return clearInterval(interval);
        }
        var particleCount = 50 * (timeLeft / duration);
        confetti(Object.assign({}, defaults, { particleCount, origin: { x: randomInRange(0.1, 0.3), y: Math.random() - 0.2 } }));
        confetti(Object.assign({}, defaults, { particleCount, origin: { x: randomInRange(0.7, 0.9), y: Math.random() - 0.2 } }));
      }, 250);

      function randomInRange(min, max) { return Math.random() * (max - min) + min; }

      alert("🎉 ACCESS GRANTED! \n\nYou absolute legend. I'd give you root access, but... actually, no I won't. \n\nEnjoy the confetti though!");
      console.log("%c[+] SYSTEM UNLOCKED.", "color: #00ff00; font-weight: bold;");
      
    } else {
      alert("🚫 ACCESS DENIED \n\nNice try, script kiddie.");
    }
  };
</script>