<div align="center">

<div align="center"><a href="https://github.com/ArtistS24"><img src="terminal_unified/01_top.svg" width="100%" align="top" alt="Terminal Window Top: Bio &amp; cd projects" /></a><a href="https://github.com/ArtistS24/blackbox-siem-edr" title="Open Flagship SOC Repository: blackbox-siem-edr"><img src="terminal_unified/04_blackbox.svg" width="100%" align="top" alt="Black Box SIEM &amp; EDR Project Row" /></a><a href="https://github.com/ArtistS24/Engineer-Forensic-tool" title="Explore Engineer Forensics Tool"><img src="terminal_unified/02_engineer.svg" width="100%" align="top" alt="Engineer Forensics Project Row" /></a><a href="https://github.com/ArtistS24/cyberium-cli" title="Explore Cyberium CLI Lab"><img src="terminal_unified/03_cyberium.svg" width="100%" align="top" alt="Cyberium CLI Project Row" /></a><a href="https://github.com/ArtistS24/glaz-audit" title="Explore Glaz Audit Lab"><img src="terminal_unified/05_glaz.svg" width="100%" align="top" alt="Glaz Audit Project Row" /></a><a href="https://github.com/ArtistS24/owasp-ctf-arenas" title="Explore OWASP CTF Arenas"><img src="terminal_unified/06_research.svg" width="100%" align="top" alt="OWASP CTF Arenas Project Row" /></a><a href="https://github.com/ArtistS24"><img src="terminal_unified/07_bottom.svg" width="100%" align="top" alt="Terminal Window Bottom: Edge Motto" /></a></div>

<br/>

[![Verified Credentials](https://img.shields.io/badge/VERIFIED_CREDENTIALS-CITY_%26_GUILDS-0284c7?style=flat-square&logo=openbadges&logoColor=white)](https://digitalcredentials.cityandguilds.com/profile/denisalbin263984/wallet)
[![Direct Contact](https://img.shields.io/badge/DIRECT_CONTACT-albindeniswork%40gmail.com-10b981?style=flat-square&logo=gmail&logoColor=white)](mailto:albindeniswork@gmail.com)

<br/>
<br/>

<p>
  <img src="https://img.shields.io/badge/PROJECT_POC_DOSSIERS-TECHNICAL_DOCUMENTATION_(PDF)-d97706?style=flat-square&amp;logo=readthedocs&amp;logoColor=white" alt="Project PoC Documentation (PDF)" />
  <br/>
  <a href="https://github.com/ArtistS24/blackbox-siem-edr/blob/main/docs/Blackbox_SIEM_EDR_Portfolio.pdf"><img src="https://img.shields.io/badge/SOC_%26_EDR_Spec-BlackBox_SIEM_(18_Pages)-6366f1?style=flat-square&amp;logo=linux&amp;logoColor=white" alt="BlackBox SIEM PoC" /></a>
  <a href="https://github.com/ArtistS24/Engineer-Forensic-tool/blob/main/docs/Engineer_Portfolio.pdf"><img src="https://img.shields.io/badge/Forensics_Dossier-Engineer_(13_Pages)-38bdf8?style=flat-square&amp;logo=linux&amp;logoColor=white" alt="Engineer Forensics PoC" /></a>
  <a href="https://github.com/ArtistS24/cyberium-cli/blob/main/docs/Cyberium_CLI_POC_Denis_Albin.pdf"><img src="https://img.shields.io/badge/TUI_Spec_%26_POC-Cyberium_CLI_(8_Pages)-10b981?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Cyberium CLI PoC" /></a>
  <a href="https://github.com/ArtistS24/glaz-audit/blob/main/docs/Glaz_Portfolio.pdf"><img src="https://img.shields.io/badge/Pentest_Dossier-Glaz_Audit_(12_Pages)-f59e0b?style=flat-square&amp;logo=kalilinux&amp;logoColor=white" alt="Glaz Pentest PoC" /></a>
  <a href="https://github.com/ArtistS24/owasp-ctf-arenas#walkthroughs"><img src="https://img.shields.io/badge/CTF_Walkthroughs-OWASP_CTF_Arenas_(75_Pages)-e879f9?style=flat-square&amp;logo=target&amp;logoColor=white" alt="OWASP CTF Arenas" /></a>
</p>

</div>

<details>
<summary><b>Plain-text terminal session</b></summary>

```bash
artist@host:~$ whoami
Denis Albin · ArtistS24

artist@host:~$ id
uid=1000(artist) gid=1000(artist) groups=10(wheel),36(kvm),220(soc-analyst),42(blue-team),24(red-team),1337(rtx-pentest)

artist@host:~$ cat ~/.about
Cybersecurity practitioner & Linux enthusiast · systems & craft.
Cybersecurity graduate (694h · City & Guilds) · Currently in RTX (Red Team Expert).
Building Linux SIEM/EDR, forensics & lab automation in Bash & CLI.

artist@host:~$ cat ~/.domains
[+] Defensive Security : SIEM log triage (Splunk / ELK), EDR telemetry, forensics
[+] Offensive Security : Network recon, Exploit-DB mapping, OWASP web labs
[+] Infrastructure     : Linux kernel primitives, KVM virtualization
[+] Alert & Log Triage : Windows Events, Sysmon, Linux auditd, Suricata / PCAP

artist@host:~$ cat ~/.stack
languages   : Bash, POSIX Shell, Python 3 (Lab Tooling)
systems     : Fedora (Daily Driver), Kali Linux (Container), KVM
toolchains  : Splunk, ELK, Wireshark, Volatility 3, Nmap, Docker

artist@host:~$ cd ~/projects

artist@host:~/projects$ ls -la --color=always --hyperlink=auto
total 40 · 5 repositories · OSC-8 hyperlinks active
drwxr-xr-x 2 artist 4.0K Oct 15 >_ blackbox-siem-edr/ ↗  ● SOC PLATFORM
  ├─ stack: bash | inotify | socat | siem
  ├─ defensive: socat TCP:9000 JSON SIEM ingest, jq parser & live SOC dashboard
  ├─ endpoint : inotifywait, /proc & ss sensor · MITRE rules · SIGKILL & iptables
  └─ Documentation: [  18-Page SIEM & EDR Architecture & PoC (PDF) ]

drwxr-xr-x 2 artist 4.0K Oct 18 >_ Engineer-Forensic-tool/ ↗  ● FORENSICS CLI
  ├─ stack: bash | volatility 3 | binwalk
  ├─ Automated file carving, artifact extraction & Volatility 3 memory triage
  ├─ Workflow: 13-option interactive CLI dispatcher · *_Automation.zip bundle
  └─ Documentation: [  13-Page Forensics Walkthrough & PoC (PDF) ]

drwxr-xr-x 2 artist 4.0K Oct 15 >_ cyberium-cli/ ↗  ● LAB HELPER TUI
  ├─ stack: python 3 | curses | tui | sqlite
  ├─ Curses TUI dashboard, browser session sync & lab submission CLI
  └─ Documentation: [  8-Page Curses TUI Walkthrough & PoC (PDF) ]

drwxr-xr-x 2 artist 4.0K Oct 15 >_ glaz-audit/ ↗  ● PENTEST SUITE
  ├─ stack: bash | nmap | cve | recon
  ├─ Automated Nmap recon, Searchsploit mapping & Hydra audit
  └─ Documentation: [  12-Page Pentest Walkthrough & CVE Mapping (PDF) ]

drwxr-xr-x 2 artist 4.0K Oct 19 >_ owasp-ctf-arenas/ ↗  ● CTF ARENAS
  ├─ stack: docker | php | mysql | sqlite | owasp
  ├─ arenas: 3 Dockerized OWASP Top 10 web apps (CorpLink, CorpNet, BrightBoard)
  └─ Documentation: [  7 Step-by-Step CTF Walkthrough PDFs (75 Pages) ]

artist@host:~/projects$ cat ~/edge
"the paint meets the kernel — where shadow gives depth to the blade"
```

</details>
