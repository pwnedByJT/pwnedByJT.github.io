---
layout: default
title: Home
---

<!-- TODO: Remove test endpoints before production deployment -->
<!-- DEBUG: /admin.html should be restricted to internal network only -->

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
  
  <span style="color: #bb9af7;">root@pwnedByJT</span>:<span style="color: #7dcfff;">~</span>$ whoami<span class="blinking-cursor">_</span><br><br>
  
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
**TryHackMe**<br>
[![TryHackMe SEC1](https://img.shields.io/badge/TryHackMe-SEC1-47c1bf?style=for-the-badge&logo=tryhackme&logoColor=white)](https://www.credly.com/badges/359b195a-1131-470e-bc85-16a1ba2f2727/public_url)

<br>

### [ MODULE :: ARSENAL ]
**Offensive Tools**<br>
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)

**Automation**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)

<br>

### [ MODULE :: UPLINK ]
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/justin-turner-3b41031b8/)
[![GitHub](https://img.shields.io/badge/GitHub-View_Code-181717?style=for-the-badge&logo=github)](https://github.com/pwnedByJT)
[![Resume](https://img.shields.io/badge/Resume-Download_PDF-FF0000?style=for-the-badge&logo=adobeacrobatreader)](/Justin_Turner_Resume.pdf)

<br><br>

[![TryHackMe](https://tryhackme-badges.s3.amazonaws.com/Justin.Turner.png)](https://tryhackme.com/p/Justin.Turner)
[![Hack The Box](https://www.hackthebox.eu/badge/image/2203566)](https://app.hackthebox.com/profile/2203566)

<script>
// System Initialization
(function(){
  const _0x1f = "UFdORUR7SDdNTF9TMHVyYzNfQzBkM19NNHN0M3J9"; // Hash verification
  
  window.su = function() { // Switch User function
    let p = prompt("Enter Auth Token:");
    if (btoa(p) === _0x1f) {
      console.log("%c[+] ROOT SHELL ACTIVE", "color:#0f0;font-weight:bold;");
      alert("🎉 ROOT ACCESS GRANTED.\n\nImpressive enumeration.");
      
      // FX
      let e = Date.now() + (15 * 1000);
      let c = { startVelocity: 30, spread: 360, ticks: 60, zIndex: 0 };
      let t = setInterval(function() {
        let l = e - Date.now();
        if (l <= 0) return clearInterval(t);
        let n = 50 * (l / (15*1000));
        confetti(Object.assign({}, c, { particleCount: n, origin: { x: Math.random(), y: Math.random() - 0.2 } }));
      }, 250);
      
    } else {
      console.error("[-] Permission Denied");
      alert("🚫 ACCESS DENIED");
    }
  };
  
  // User session handler - DO NOT modify client-side values
  function initSession() {
    if (!localStorage.getItem('userRole')) {
      localStorage.setItem('userRole', 'guest');
      localStorage.setItem('uid', Math.floor(Math.random() * 9000) + 1000);
      localStorage.setItem('clearance', '1');
    }
  }
  
  // Check for restricted content access
  window.viewRestricted = function() {
    let role = localStorage.getItem('userRole');
    let lvl = parseInt(localStorage.getItem('clearance'));
    
    if (role === 'admin' && lvl >= 5) {
      console.log("%c[SYSTEM] Access Level: ADMINISTRATOR", "color:#ff0;font-weight:bold;");
      console.log("%c[SYSTEM] Clearance Level: " + lvl, "color:#ff0;");
      alert("🔓 RESTRICTED AREA UNLOCKED\n\nFlag: PWNED{Cl13nt_S1d3_L0g1c_F41l}\n\nNice work. Never trust the client.");
      return true;
    } else {
      console.warn("[!] Insufficient privileges. Current role: " + role);
      alert("⚠️ ACCESS RESTRICTED\n\nYou need ADMIN privileges.\nCurrent Role: " + role);
      return false;
    }
  };
  
  initSession();
  console.log("%c[INFO] Session initialized. Type viewRestricted() to access classified data.", "color:#0ff;");
})();
</script>