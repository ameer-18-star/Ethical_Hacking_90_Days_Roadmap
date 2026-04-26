# 🛡️ 90 Days of Ethical Hacking

> A complete, day-by-day roadmap to go from zero to job-ready ethical hacker — with curated resources, hands-on labs, time estimates, and real tips from professionals who've been in the trenches.

[![Stars](https://img.shields.io/github/stars/yourusername/90DaysOfEthicalHacking?style=flat-square)](https://github.com/yourusername/90DaysOfEthicalHacking)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)

---

## 🌐 Interactive Roadmap Webpage

**👉 [View the Full Interactive Roadmap →](https://yourusername.github.io/90DaysOfEthicalHacking)**

The web version includes:
- Clickable day-by-day progress tracker
- Expandable topic cards with resources + tips
- Phase filters and search
- Time estimate per topic
- Professional tips from pentesters & bug bounty hunters

---

## 📚 Table of Contents

- [Introduction](#introduction)
- [Who This Is For](#who-this-is-for)
- [How to Use This Roadmap](#how-to-use-this-roadmap)
- [The 6 Phases](#the-6-phases)
  - [Phase 1 — Foundations (Days 1–15)](#phase-1--foundations-days-115)
  - [Phase 2 — Linux & Scripting (Days 16–35)](#phase-2--linux--scripting-days-1635)
  - [Phase 3 — Networking & Traffic (Days 36–50)](#phase-3--networking--traffic-days-3650)
  - [Phase 4 — Web Hacking (Days 51–65)](#phase-4--web-hacking-days-5165)
  - [Phase 5 — System & Network Exploitation (Days 66–80)](#phase-5--system--network-exploitation-days-6680)
  - [Phase 6 — Real-World Practice & Career (Days 81–90)](#phase-6--real-world-practice--career-days-8190)
- [Tools You'll Master](#tools-youll-master)
- [Contributing](#contributing)
- [License](#license)

---

## 📘 Introduction

Most "learn hacking" resources fall into one of two traps. Either they're so shallow you finish the course and still can't find a single vulnerability — or they're so deep and unstructured you burn out by week two.

This roadmap is different.

Every single day has a specific topic. A time estimate. Links to where you learn it AND where you practice it. And at least one tip from someone who actually does this for a living — pentesters, CTF champions, bug bounty hunters, red teamers.

No filler. No vague "just practice on Hack The Box." Real structure, real resources, real guidance.

This is the roadmap I wish existed when I started.

---

## 🎯 Who This Is For

| You are... | This roadmap will... |
|---|---|
| A complete beginner | Give you the exact starting point and order — no guessing |
| A developer curious about security | Show you how attackers think about your code |
| An IT professional pivoting to security | Fill the gaps with hands-on offensive skills |
| A student preparing for CEH or OSCP | Build the practical foundation those certs expect |
| A bug bounty hunter just starting out | Get you to your first valid report faster |

No prior hacking experience required. Familiarity with computers helps. A curious, persistent mindset is mandatory.

---

## 🗺️ How to Use This Roadmap

1. **Follow the phases in order.** Each phase builds on the last. Skipping Phase 1 to jump to exploitation is like trying to run before you can walk — you'll hit a wall fast.
2. **Respect the time estimates.** They're realistic, not padded. Some days are 2 hours. Some are 4. Plan accordingly.
3. **Do the labs.** Reading about SQL injection and actually exploiting one are completely different experiences. The practice links are not optional.
4. **Read the pro tips.** These are distilled from real-world experience. They'll save you hours of confusion.
5. **Track your progress.** Use the interactive webpage or fork this repo and check off days as you go.

**Daily Commitment:** 2–4 hours/day | **Total Hours:** ~240 hours

---

## 🔷 The 6 Phases

---

### Phase 1 — Foundations (Days 1–15)

> *"You can't hack what you don't understand." — Every seasoned pentester, ever.*

Before touching a single exploit, you need to understand how networks work, how the web works, and how attackers think. This phase is not optional.

---

#### Day 1–3: How the Internet Actually Works
**Topics:** TCP/IP model, DNS, HTTP/HTTPS, IP addressing, ports & protocols
**Time:** 2–3 hours/day

**Learn:**
- [Professor Messer's Network+ (N10-009)](https://www.professormesser.com/network-plus/n10-009/n10-009-video/n10-009-training-course/) — Start with OSI/TCP-IP sections
- [How DNS Works (Cloudflare)](https://www.cloudflare.com/learning/dns/what-is-dns/)
- [HTTP: The Protocol Every Web Developer Must Know](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)

**Practice:**
- Use `ping`, `traceroute`, `nslookup`, `curl` in your terminal
- [TryHackMe — Pre-Security Path](https://tryhackme.com/path/outline/presecurity) (free)

**💡 Pro Tip:** *"I've interviewed dozens of junior pentesters. The ones who can explain exactly what happens between typing a URL and seeing a webpage — packet by packet — are the ones who get hired. It's the single best signal of real understanding."* — Senior Pentester, consulting firm

---

#### Day 4–7: Networking Deep Dive
**Topics:** Subnetting, VLAN, firewalls, NAT, routing, VPNs, common protocols (FTP, SSH, SMTP, SMB)
**Time:** 3–4 hours/day

**Learn:**
- [Professor Messer N10-009 Playlist](https://www.professormesser.com/network-plus/n10-009/n10-009-video/n10-009-training-course/) — Networking sections
- [Subnetting Made Easy (YouTube)](https://www.youtube.com/watch?v=BWZ-MHIhqjM)
- [SMB Protocol Explained](https://www.varonis.com/blog/smb-port)

**Practice:**
- [TryHackMe — Network Fundamentals](https://tryhackme.com/module/network-fundamentals)
- Set up Wireshark and capture your own traffic for 30 minutes — just observe

**💡 Pro Tip:** *"Learn subnetting until you can do it in your head. Not because you'll need it in every engagement — but because being slow at the fundamentals makes you slow at everything that comes after."* — Bug Bounty Hunter, top 10 on HackerOne

---

#### Day 8–11: Security Fundamentals
**Topics:** CIA Triad, authentication vs authorization, common attack types, cryptography basics, certificates, hashing
**Time:** 2–3 hours/day

**Learn:**
- [Professor Messer's Security+ SY0-701 Playlist](https://www.professormesser.com/security-plus/sy0-701/sy0-701-video/sy0-701-training-course/)
- [Cryptography 101 (Khan Academy)](https://www.khanacademy.org/computing/computer-science/cryptography)
- [OWASP Top 10 — Official Docs](https://owasp.org/www-project-top-ten/)

**Practice:**
- [TryHackMe — Introduction to Cybersecurity](https://tryhackme.com/path/outline/introtocyber)

**💡 Pro Tip:** *"Read the OWASP Top 10 on Day 8 and re-read it on Day 90. What confused you early on will suddenly click. The document hasn't changed — but you will have."* — Application Security Engineer, Fortune 500

---

#### Day 12–15: The Attacker's Mindset & Legal/Ethical Framework
**Topics:** Penetration testing methodology, rules of engagement, reconnaissance types (passive vs active), CVEs & vulnerability databases, how bug bounty programs work
**Time:** 2–3 hours/day

**Learn:**
- [The Pentester's Bible — PTES Standard](http://www.pentest-standard.org/index.php/Main_Page)
- [What Is a CVE? (Red Hat)](https://www.redhat.com/en/topics/security/what-is-cve)
- [HackerOne's Hacker101 — Free Training](https://www.hacker101.com/)
- [Bug Bounty Hunter Methodology v4 (Jason Haddix)](https://www.youtube.com/watch?v=p4JgIu1mceI)

**Practice:**
- Sign up on [HackerOne](https://hackerone.com) and read 10 disclosed reports in any program
- Sign up on [Bugcrowd](https://bugcrowd.com) — read their code of conduct

**💡 Pro Tip:** *"Reading disclosed bug reports is the single most underrated learning activity in this field. You're seeing real vulnerabilities, real impact, real writeups — for free. I learned more from 50 disclosed reports than from any single course."* — Bug Bounty Hunter, $200k+ in bounties

---

### Phase 2 — Linux & Scripting (Days 16–35)

> *"Linux isn't just where hacking happens. Linux IS hacking."*

Every major offensive tool runs on Linux. Every real target has Linux somewhere. You don't need to be a Linux guru — but you need to be fluent.

---

#### Day 16–22: Linux Fundamentals
**Topics:** File system, permissions, users & groups, processes, package management, file manipulation, shell basics
**Time:** 2–3 hours/day

**Learn:**
- [Linux Journey](https://linuxjourney.com/) — Complete Grasshopper + Journeyman tracks
- [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) — Learn by playing (highly recommended)
- [The Linux Command Line (free online book)](https://linuxcommand.org/tlcl.php)

**Practice:**
- [TryHackMe — Linux Fundamentals](https://tryhackme.com/module/linux-fundamentals) (3-part series)
- [LabEx Linux Free Labs](https://labex.io/free-labs/linux)

**💡 Pro Tip:** *"Type every command yourself. Copy-paste is the enemy of muscle memory. The first time you're on a box with no internet and you can't remember how to find SUID binaries — you'll wish you'd typed it 50 times instead of copying it once."* — Red Team Operator

---

#### Day 23–27: Bash Scripting for Hackers
**Topics:** Variables, loops, conditionals, functions, file I/O, automating recon tasks
**Time:** 3 hours/day

**Learn:**
- [Bash Scripting Tutorial (Ryan's Tutorials)](https://ryanstutorials.net/bash-scripting-tutorial/)
- [The Cyber Mentor — Bash Scripting for Beginners (YouTube)](https://www.youtube.com/watch?v=oxuRxtrO2Ag)

**Practice:**
- Write a script that pings a subnet and logs which IPs are alive
- Write a script that automates directory enumeration with gobuster
- [HackerRank Bash Challenges](https://www.hackerrank.com/domains/shell)

**💡 Pro Tip:** *"Every time you do something manually more than twice — script it. That's the hacker mindset applied to your own workflow. Your future self will thank you at 2am during a CTF."* — CTF Champion

---

#### Day 28–35: Python for Security
**Topics:** Python basics, file handling, network sockets, requests library, writing your first port scanner, automating web requests
**Time:** 3–4 hours/day

**Learn:**
- [Automate the Boring Stuff with Python (free)](https://automatetheboringstuff.com/)
- [The Cyber Mentor — Python for Ethical Hacking (YouTube)](https://www.youtube.com/watch?v=egg-GoT5iVk)
- [Real Python — Networking and Sockets](https://realpython.com/python-sockets/)

**Practice:**
- [HackerRank Python Track](https://www.hackerrank.com/domains/python)
- Build a port scanner from scratch (yes, even though nmap exists — you'll understand nmap better after)
- Build a simple keylogger (in your own controlled VM only)

**💡 Pro Tip:** *"Don't just use tools — understand them well enough to build a bad version of them yourself. A bad port scanner you wrote teaches you more than 100 nmap scans you ran without thinking."* — Penetration Tester, 8 years exp.

---

### Phase 3 — Networking & Traffic Analysis (Days 36–50)

> *"Network traffic doesn't lie. If you know how to read it, everything is visible."*

---

#### Day 36–41: Wireshark & Packet Analysis
**Topics:** Capturing traffic, reading packet headers, following streams, filtering syntax, identifying protocols, spotting anomalies
**Time:** 3 hours/day

**Learn:**
- [Wireshark Official Training](https://www.wireshark.org/#educationalContent)
- [Wireshark Tutorial — guru99](https://guru99.com/wireshark-tutorial.html)
- [Chris Greer — Wireshark YouTube Series](https://www.youtube.com/watch?v=NjvR4LmwcMU&list=PLBf0hzazHTGPgyxeEj_9LBHiqjtNEjsgt)

**Practice:**
- [Wireshark Sample Captures](https://wiki.wireshark.org/SampleCaptures) — Analyze at least 10
- [TryHackMe — Wireshark Room](https://tryhackme.com/room/wireshark)

**💡 Pro Tip:** *"The filters are your superpower. `http.request.method == POST` and `tcp.flags.syn == 1 && tcp.flags.ack == 0` — know your filters cold. A packet capture without filtering is like searching a library with no index."* — Network Security Engineer

---

#### Day 42–46: TCPDump & Command-Line Traffic Analysis
**Topics:** Capturing with tcpdump, writing to pcap files, filtering expressions, analysis without a GUI
**Time:** 2 hours/day

**Learn:**
- [Daniel Miessler's TCPdump Tutorial](https://danielmiessler.com/study/tcpdump/)
- [TCPdump Man Page — read it, seriously](https://www.tcpdump.org/manpages/tcpdump.1.html)

**Practice:**
- Capture and analyze traffic from your own browsing session
- [TryHackMe — Packet Analysis](https://tryhackme.com/room/wireshark101)

**💡 Pro Tip:** *"tcpdump runs everywhere. Wireshark doesn't. On a production server with no GUI, tcpdump is your eyes. Learn it like a backup skill — until the day it becomes your primary one."* — Incident Responder

---

#### Day 47–50: Nmap & Active Reconnaissance
**Topics:** Host discovery, port scanning, service detection, OS fingerprinting, NSE scripts, scan timing & evasion
**Time:** 3 hours/day

**Learn:**
- [Nmap Official Book (free)](https://nmap.org/book/toc.html) — Chapters 1–6
- [The Cyber Mentor — Nmap Tutorial (YouTube)](https://www.youtube.com/watch?v=4t4kBkMsDbQ)

**Practice:**
- Set up a local lab with VirtualBox + Metasploitable2 and scan it
- [TryHackMe — Nmap Room](https://tryhackme.com/room/furthernmap)
- [HackTheBox — Starting Point machines](https://app.hackthebox.com/starting-point)

**💡 Pro Tip:** *"Don't just run `nmap -sV target` and call it done. Read the NSE script categories. One well-chosen script has led to critical findings in real engagements more times than I can count."* — Penetration Tester

---

### Phase 4 — Web Hacking (Days 51–65)

> *"The web is the largest attack surface on the planet. Learning to hack it is learning to hack everything."*

---

#### Day 51–53: Web Application Architecture
**Topics:** How web apps work end-to-end, cookies & sessions, same-origin policy, REST APIs, authentication flows, HTTP methods in depth
**Time:** 2–3 hours/day

**Learn:**
- [PortSwigger Web Security Academy — Getting Started](https://portswigger.net/web-security/getting-started)
- [MDN — HTTP Overview](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
- [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)

**Practice:**
- [DVWA (Damn Vulnerable Web App)](https://github.com/digininja/DVWA) — Set it up locally
- [TryHackMe — How Websites Work](https://tryhackme.com/room/howwebsiteswork)

---

#### Day 54–56: Burp Suite Mastery
**Topics:** Proxy setup, intercepting requests, Repeater, Intruder, Decoder, Scanner, extensions
**Time:** 3 hours/day

**Learn:**
- [PortSwigger Burp Suite Learning Path](https://portswigger.net/burp/documentation/desktop/getting-started)
- [The Cyber Mentor — Burp Suite Tutorial (YouTube)](https://www.youtube.com/watch?v=G3hpAeoZ4ek)

**Practice:**
- [TryHackMe — Burp Suite Module](https://tryhackme.com/module/learn-burp-suite)
- Use Burp on DVWA for every exercise

**💡 Pro Tip:** *"Burp Suite is your command center. Most beginners use it as a proxy and stop there. The Repeater alone has found me more bugs than any automated scanner. Manual testing > automated scanning, every time."* — Bug Bounty Hunter

---

#### Day 57–59: SQL Injection
**Topics:** Error-based, blind, time-based, union-based SQLi, bypass techniques, SQLMap
**Time:** 3 hours/day

**Learn:**
- [PortSwigger — SQL Injection](https://portswigger.net/web-security/sql-injection)
- [OWASP SQLi Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html)

**Practice:**
- [PortSwigger SQLi Labs](https://portswigger.net/web-security/sql-injection#sql-injection-examples) — All 18 labs
- [HackTheBox — SQL injection challenge](https://app.hackthebox.com/challenges)

**💡 Pro Tip:** *"Do every SQLi lab manually before touching SQLMap. Automated tools are a crutch that hides your ignorance — and WAFs will laugh at automated scans. A manual understanding is what gets you past defenses."* — Red Teamer

---

#### Day 60–62: XSS, CSRF & Injection Attacks
**Topics:** Reflected, stored, DOM-based XSS; CSRF; command injection; SSTI
**Time:** 3 hours/day

**Learn:**
- [PortSwigger — XSS](https://portswigger.net/web-security/cross-site-scripting)
- [PortSwigger — CSRF](https://portswigger.net/web-security/csrf)

**Practice:**
- [PortSwigger XSS Labs](https://portswigger.net/web-security/cross-site-scripting#reflected-cross-site-scripting) — Complete all beginner + practitioner labs
- [XSS Game by Google](https://xss-game.appspot.com/)

---

#### Day 63–65: Authentication Attacks & IDOR
**Topics:** Password attacks, brute force, credential stuffing, JWT attacks, IDOR, broken access control
**Time:** 3 hours/day

**Learn:**
- [PortSwigger — Authentication](https://portswigger.net/web-security/authentication)
- [PortSwigger — Access Control & IDOR](https://portswigger.net/web-security/access-control)

**Practice:**
- [PortSwigger Authentication Labs](https://portswigger.net/web-security/authentication#labs)
- [TryHackMe — IDOR Room](https://tryhackme.com/room/idor)

**💡 Pro Tip:** *"IDOR is still the most commonly found vulnerability in bug bounty programs — and the most underestimated. Change a user ID by 1. Check if you can access someone else's invoice. It takes 30 seconds and pays thousands."* — Bug Bounty Hunter, $500k+ earned

---

### Phase 5 — System & Network Exploitation (Days 66–80)

> *"This is where theory meets actual shells."*

---

#### Day 66–70: Metasploit Framework
**Topics:** MSF architecture, modules (exploit/payload/auxiliary), msfvenom, sessions, post-exploitation, meterpreter
**Time:** 3–4 hours/day

**Learn:**
- [Offensive Security — Metasploit Unleashed (free)](https://www.metasploitunleashed.com/)
- [The Cyber Mentor — Metasploit Tutorial (YouTube)](https://www.youtube.com/watch?v=8lR27r8Y_ik)

**Practice:**
- [TryHackMe — Metasploit Module](https://tryhackme.com/module/metasploit)
- Exploit Metasploitable2 with Metasploit (at least 5 different vulnerabilities)

**💡 Pro Tip:** *"Metasploit is not a magic button. Real engagements have AV, EDR, and network monitoring. Learn Metasploit so you understand the underlying techniques — then learn how to do those techniques manually."* — Red Team Operator

---

#### Day 71–74: Privilege Escalation — Linux
**Topics:** SUID/GUID binaries, sudo misconfigurations, cron jobs, path hijacking, kernel exploits, linpeas
**Time:** 3 hours/day

**Learn:**
- [GTFOBins](https://gtfobins.github.io/) — Bookmark this now
- [TryHackMe — Linux PrivEsc](https://tryhackme.com/room/linuxprivesc)
- [PayloadsAllTheThings — Linux PrivEsc](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Linux%20-%20Privilege%20Escalation.md)

**Practice:**
- [TryHackMe — Linux PrivEsc Arena](https://tryhackme.com/room/linuxprivescarena)
- [Vulnhub — Kioptrix machines](https://www.vulnhub.com/?q=kioptrix)

**💡 Pro Tip:** *"Run linpeas, but read every line of the output. Scripts are only as useful as your ability to understand what they're telling you. Automated output you don't understand is noise."* — OSCP Holder

---

#### Day 75–77: Privilege Escalation — Windows
**Topics:** Token impersonation, unquoted service paths, registry misconfigs, AlwaysInstallElevated, PowerShell, winpeas
**Time:** 3 hours/day

**Learn:**
- [Windows PrivEsc Guide (PayloadsAllTheThings)](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Windows%20-%20Privilege%20Escalation.md)
- [TryHackMe — Windows PrivEsc](https://tryhackme.com/room/windows10privesc)

**Practice:**
- [TryHackMe — Windows PrivEsc Arena](https://tryhackme.com/room/windowsprivescarena)
- [HackTheBox — Windows easy machines](https://app.hackthebox.com/machines)

---

#### Day 78–80: Active Directory Attacks
**Topics:** AD structure, Kerberoasting, Pass-the-Hash, BloodHound, LDAP enumeration, common misconfigs
**Time:** 4 hours/day

**Learn:**
- [TCM Security — Practical Ethical Hacking (AD sections)](https://academy.tcm-sec.com/p/practical-ethical-hacking-the-complete-course)
- [HackTricks — Active Directory](https://book.hacktricks.xyz/windows-hardening/active-directory-methodology)

**Practice:**
- [TryHackMe — Active Directory Basics](https://tryhackme.com/room/winadbasics)
- [VulnLab — AD labs](https://www.vulnlab.com/)

**💡 Pro Tip:** *"Active Directory is the golden ticket in real engagements. 90% of corporate environments run it. If you can Kerberoast and move laterally, you're in the top 20% of pentesters already."* — Enterprise Pentester

---

### Phase 6 — Real-World Practice & Career (Days 81–90)

> *"The difference between someone who studied hacking and someone who can hack is 100 boxes."*

---

#### Day 81–85: CTF Practice & HackTheBox
**Topics:** Applying all skills in realistic environments, methodology under pressure, note-taking, report writing
**Time:** 4–5 hours/day

**Platforms:**
- [Hack The Box](https://hackthebox.com) — Start with retired easy machines
- [TryHackMe — Complete Learning Paths](https://tryhackme.com)
- [VulnHub](https://vulnhub.com) — Download and attack offline VMs
- [PicoCTF](https://picoctf.org/) — Great for crypto, forensics, rev eng

**Recommended machines to start:**
- HTB: Lame, Blue, Legacy, Jerry, Netmon
- VulnHub: Kioptrix 1-5, DC-1, Mr. Robot

**💡 Pro Tip:** *"When you're stuck for more than 45 minutes, write down exactly what you've tried, check a hint — but only one. Then try for another 45 minutes before looking at a full walkthrough. This mimics real work. The struggle is the training."* — OSCP #1 exam passer at TCM community

---

#### Day 86–88: Writing Your First Pentest Report
**Topics:** Executive summary, findings, CVSS scoring, risk ratings, remediation advice, appendices
**Time:** 3 hours/day

**Learn:**
- [TCM Security — Sample Pentest Report (free PDF)](https://github.com/hmaverickadams/TCM-Security-Sample-Pentest-Report)
- [PTES — Reporting Guide](http://www.pentest-standard.org/index.php/Reporting)
- [CVSS Calculator](https://www.first.org/cvss/calculator/3.1)

**Practice:**
- Write a mock report for any machine you've pwned
- Get feedback in [TCM Security Discord](https://discord.gg/tcm) or [r/netsec](https://reddit.com/r/netsec)

**💡 Pro Tip:** *"Your report is the only deliverable the client sees. A perfect exploitation chain written up badly is worthless. A clear, well-evidenced report on a medium vulnerability is what gets you rehired."* — Pentest Team Lead, consulting firm

---

#### Day 89–90: Career Launch
**Topics:** Resume, LinkedIn, certifications roadmap, where to apply, networking
**Time:** 3–4 hours/day

**Resume:**
- [TCM Security — Killer Cyber Resume Guide](https://tcm-sec.com/so-you-want-to-be-a-pentester/)
- [Indeed — Cybersecurity Resume Templates](https://www.indeed.com/career-advice/resumes-cover-letters/cybersecurity-resume)

**Certifications to pursue next:**
| Cert | Cost | Best for |
|---|---|---|
| CompTIA Security+ | ~$400 | Entry-level, corporate |
| eJPT (eLearnSecurity) | $200 | First hands-on hacking cert |
| CEH | ~$1,000 | Government/compliance roles |
| OSCP | ~$1,500 | The gold standard for pentesters |
| PNPT (TCM) | $400 | Realistic, affordable OSCP alternative |

**Where to apply:**
- [LinkedIn Jobs — Penetration Tester](https://linkedin.com/jobs)
- [Indeed — Entry Level Security](https://indeed.com)
- Direct applications to MSSP companies (Rapid7, Trustwave, NCC Group, etc.)

**💡 Pro Tip:** *"Don't wait until you feel 'ready.' Apply when you've finished this roadmap. Imposter syndrome is universal in this field. The job will teach you faster than any more studying will."* — CISO, mid-size tech company

---

## 🔧 Tools You'll Master

| Category | Tools |
|---|---|
| Reconnaissance | nmap, theHarvester, Shodan, Maltego, Recon-ng |
| Web Testing | Burp Suite, OWASP ZAP, Nikto, dirsearch, ffuf |
| Exploitation | Metasploit, SQLMap, Hydra, John the Ripper |
| Post-Exploitation | Mimikatz, BloodHound, Impacket, linpeas, winpeas |
| Traffic Analysis | Wireshark, tcpdump, Zeek, Suricata |
| Scripting | Python, Bash, PowerShell |
| Infrastructure | Docker, VirtualBox, Kali Linux |

---

## 🤝 Contributing

This roadmap is a living document. If you've found a better resource, spotted an outdated link, or want to add a pro tip from your own experience — open a PR.

**Contribution categories:**
- 📖 Better or newer learning resources
- 🛠️ Additional practice labs or machines
- 💡 Professional tips from real-world experience
- 🐛 Fixing broken links or outdated content
- 🌐 Translations
- 🧪 Adding quizzes or knowledge checks

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## ⭐ If this roadmap helped you — star the repo. It helps others find it.

---

## 📄 License

MIT License — See [LICENSE](LICENSE) for details.

Use this freely. Learn from it. Build on it. Just don't sell it unchanged.
