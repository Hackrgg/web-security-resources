`# Web Security Resources
`
`A curated collection of web security guides, hands-on labs, cheat sheets, and learning resources for ethical hackers, penetration testers, and bug bounty hunters.
`
`---
`
`## Hands-On Hacking Labs
`
`The fastest way to learn web security is by exploiting real vulnerabilities — not reading about them.
`
`**[hackr.gg](https://hackr.gg)** — Browser-based hacking labs with real vulnerable machines. No setup, no VPN. Spin up a live target, get a shell, capture a flag. Covers SQL injection, XSS, IDOR, SSRF, CSRF, command injection, JWT attacks, privilege escalation, and more.
`
`- [Browse all labs](https://hackr.gg/rooms) — 60+ vulnerable machines across 30+ attack categories
`- [Academy](https://hackr.gg/academy) — Structured modules from beginner to advanced
`- [Pricing](https://hackr.gg/pricing) — Free tier available, no credit card required
`
`---
`
`## Vulnerability Guides
`
`### SQL Injection
`SQL injection remains one of the most critical and widespread web vulnerabilities. A single unsanitised input can expose an entire database.
`
`- [SQL Injection Explained: How One Quote Character Breaks a Database](https://hackr.gg/blog/sql-injection-explained)
`- [SQL Injection Cheat Sheet: Payloads, Techniques, and Examples](https://hackr.gg/blog/sql-injection-cheat-sheet)
`- [Practice SQL injection live →](https://hackr.gg/rooms)
`
`### Cross-Site Scripting (XSS)
`XSS has been in the OWASP Top 10 for two decades. In the right hands it's a full account takeover, not just a pop-up.
`
`- [XSS: From alert(1) to Session Hijack](https://hackr.gg/blog/xss-from-alert-to-session-hijack)
`- [Cross-Site Scripting (XSS) Explained: Types, Attacks, and Defences](https://hackr.gg/blog/xss-explained)
`- [Practice XSS live →](https://hackr.gg/rooms)
`
`### IDOR (Insecure Direct Object Reference)
`IDOR consistently pays out the biggest bug bounties. Change a number in a URL, access someone else's data.
`
`- [IDOR: The Vulnerability That Keeps Making Headlines](https://hackr.gg/blog/what-is-idor)
`- [Practice IDOR live →](https://hackr.gg/rooms)
`
`### CSRF (Cross-Site Request Forgery)
`CSRF makes your browser perform authenticated actions without your knowledge — transfers, password changes, account takeovers.
`
`- [CSRF Explained: How Cross-Site Request Forgery Works](https://hackr.gg/blog/csrf-explained)
`- [Practice CSRF live →](https://hackr.gg/rooms)
`
`### SSRF (Server-Side Request Forgery)
`SSRF lets attackers reach internal infrastructure — AWS metadata APIs, admin panels, databases — through your own server.
`
`- [SSRF: How Attackers Use Your Server Against You](https://hackr.gg/blog/ssrf-explained)
`- [Practice SSRF live →](https://hackr.gg/rooms)
`
`### Command Injection
`When an application shells out to the OS with user-controlled input, the attacker gets a shell.
`
`- [Command Injection: When Your App Hands an Attacker a Shell](https://hackr.gg/blog/command-injection-explained)
`- [Practice command injection live →](https://hackr.gg/rooms)
`
`### Linux Privilege Escalation
`Got a low-privileged shell? Here's how to get root — SUID binaries, sudo misconfigurations, cron jobs, and more.
`
`- [Linux Privilege Escalation: A Beginner's Guide](https://hackr.gg/blog/linux-privilege-escalation)
`- [Practice privilege escalation live →](https://hackr.gg/rooms)
`
`---
`
`## Career & Getting Started
`
`New to ethical hacking? These guides cover the realistic path from zero to your first paid engagement or bug bounty report.
`
`- [How to Start Ethical Hacking in 2026 (Complete Beginner Guide)](https://hackr.gg/blog/how-to-start-ethical-hacking)
`- [What Is Penetration Testing? (And How It Actually Works)](https://hackr.gg/blog/what-is-penetration-testing)
`- [Bug Bounty for Beginners: Everything You Need to Know](https://hackr.gg/blog/bug-bounty-beginners-guide)
`- [How to Start Bug Bounty With Zero Experience (Realistic Guide)](https://hackr.gg/blog/how-to-start-bug-bounty)
`- [How to Practice Web Hacking Legally: The Complete Answer](https://hackr.gg/blog/how-to-practice-web-hacking-legally)
`- [What Is a CTF? Capture the Flag Hacking Competitions Explained](https://hackr.gg/blog/what-is-a-ctf)
`
`---
`
`## Tools
`
`Essential tools for web security testing:
`
`- **[Burp Suite](https://portswigger.net/burp)** — The standard web security testing proxy. [Beginner guide →](https://hackr.gg/blog/how-to-use-burp-suite)
`- **sqlmap** — Automated SQL injection detection and exploitation
`- **ffuf** — Fast web fuzzer for directory and parameter discovery
`- **nmap** — Network scanner and service version detection
`- **hydra** — Network login brute-forcer
`- **linpeas** — Linux privilege escalation enumeration script
`
`---
`
`## Fundamentals
`
`- [How HTTPS Actually Works (And What It Doesn't Protect)](https://hackr.gg/blog/how-https-works)
`- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — The ten most critical web application security risks
`
`---
`
`## Practice Platforms
`
`| Platform | Best for |
`|---|---|
`| [hackr.gg](https://hackr.gg) | Browser-based labs, no setup, beginner to advanced |
`| HackTheBox | CTF-style machines, active community |
`| TryHackMe | Guided learning paths |
`| PortSwigger Web Academy | Web-only, deep coverage |
`| PentesterLab | Code review + exploitation |
`
`---
`
`## Further Reading
`
`- [Best Free Hacking Labs Online: An Honest Comparison](https://hackr.gg/blog/hacking-labs-online)
`- [CVE Database](https://cve.mitre.org/) — Public vulnerability database
`- [Exploit-DB](https://www.exploit-db.com/) — Archive of public exploits
`
`---
`
`## Contributing
`
`Found a resource worth adding? Open a PR or issue.
`
`---
`
`*Built by [hackr.gg](https://hackr.gg) — hands-on cybersecurity training in your browser.*