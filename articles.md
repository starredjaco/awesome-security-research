# 📑 Articles

A curated collection of **vulnerability research articles and blog posts**.  
This file contains the **full list** of articles — the main [README](README.md) only highlights selected ones.


---   

## 📝 Table of Contents
- [AI](#AI)
- [Windows](#-windows)
- [Linux](#-linux)
- [Kubernetes & Cloud](#%EF%B8%8F-kubernetes--cloud)
- [Containers](#-containers)
- [Android & Mobile](#-android--mobile)
- [Web](#web)
- [Bug Bounty](#bug-bounty)
- [Identity](#-identity)
- [Supply Chain & Secrets](#-supply-chain--secrets)
- [Memory & Exploitation](#-memory--exploitation)
- [Cryptography](#-cryptography)
- [Miscellaneous](#-miscellaneous)

---  

## AI  
- [Anatomy of an LLM RCE](https://www.cyberark.com/resources/threat-research-blog/anatomy-of-an-llm-rce) (🔥) by Shaked Reiner, Oct 28, 2024  


## 🪟 Windows   

- [Abusing Arbitrary File Deletes to Escalate Privilege and Other Great Tricks](https://www.zerodayinitiative.com/blog/2022/3/16/abusing-arbitrary-file-deletes-to-escalate-privilege-and-other-great-tricks) (🔥)    
- [Pentester’S Windows NTFS Tricks Collection](https://sec-consult.com/blog/detail/pentesters-windows-ntfs-tricks-collection/)
- [Offensive Windows IPC Internals 2: RPC](https://csandker.io/2021/02/21/Offensive-Windows-IPC-2-RPC.html#the-series) by [Carsten Sandker](https://x.com/0xcsandker), Feb 21, 2021  
- [Offensive Windows IPC Internals 1: Named Pipes](https://csandker.io/2021/01/10/Offensive-Windows-IPC-1-NamedPipes.html) by [Carsten Sandker](https://x.com/0xcsandker), Jan 10, 2021  
- [Zerologon: Unauthenticated domain controller compromise by subverting Netlogon cryptography (CVE-2020-1472) (PDF)](https://cybersecurity.bureauveritas.com/uploads/whitepapers/Zerologon.pdf) (🔥)  by Tom Tervoort (Secura), Sep, 2020  
- [Windows Exploitation](https://web.archive.org/web/20200507040017/https://fullpwnops.com/windows-exploitation-pathway.html) by [Fu11Shade](https://web.archive.org/web/20200713114317/https://github.com/fullshade/), May, 2020  
- [Beware of the GIF: Account Takeover Vulnerability in Microsoft Teams](https://www.cyberark.com/resources/threat-research-blog/beware-of-the-gif-account-takeover-vulnerability-in-microsoft-teams) by Omer Tsarfati, Apr 27, 2020
- [Calling Local Windows RPC Servers from .NET](https://googleprojectzero.blogspot.com/2019/12/calling-local-windows-rpc-servers-from.html) by James Forshaw, Decemeber 17, 2019
- [Windows‌ ‌Exploitation‌ ‌Tricks:‌ ‌Spoofing‌ ‌Named‌ ‌Pipe‌ ‌Client‌ ‌PID](https://googleprojectzero.blogspot.com/2019/09/windows-exploitation-tricks-spoofing.html) by James Forshaw, Sep 25, 2019‌
- [The Definitive Guide on Win32 to NT Path Conversion](https://googleprojectzero.blogspot.com/2016/02/the-definitive-guide-on-win32-to-nt.html) Feb 29, 2016  
- [WATCHING THE WATCHDOG: PROTECTING KERBEROS AUTHENTICATION WITH NETWORK MONITORING (PDF)](https://blackhat.com/docs/eu-15/materials/eu-15-Beery-Watching-The-Watchdog-Protecting-Kerberos-Authentication-With-Network-Monitoring-wp.pdf) by Tal Be’ery and Michael Cherny, Nov 2015  


### Privilege Escalation  
- [Hijacking the Windows "MareBackup" Scheduled Task for Privilege Escalation](https://itm4n.github.io/hijacking-the-windows-marebackup-scheduled-task-for-privilege-escalation/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), May 20, 2025
- [A Practical Guide to PrintNightmare in 2024](https://itm4n.github.io/printnightmare-exploitation/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), Jan 28, 2024  
- [From NETWORK SERVICE to SYSTEM](https://decoder.cloud/2020/05/04/from-network-service-to-system/) by [decoder](https://x.com/decoder_it), May 4, 2020
- [Faxing Your Way to SYSTEM — Part Two](https://windows-internals.com/faxing-your-way-to-system/) (🔥🔥) by [Yarden Shafir](https://x.com/yarden_shafir) & [Alex Ionescu](https://x.com/aionescu), Apr 30, 2020  - [Faxhell tool](https://github.com/ionescu007/faxhell)  
- [Windows DLL Hijacking (Hopefully) Clarified](https://itm4n.github.io/windows-dll-hijacking-clarified/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), Apr 24, 2020  
- [CVE-2020-0729: Remote Code Execution Through .LNK Files](https://www.zerodayinitiative.com/blog/2020/3/25/cve-2020-0729-remote-code-execution-through-lnk-files) by Trend Micro Research Team, March 26, 2020
- [CVE-2020-0863 - An Arbitrary File Read Vulnerability in Windows Diagnostic Tracking Service](https://itm4n.github.io/cve-2020-0863-windows-diagtrack-info-disclo/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), March 18, 2020  
- [CVE-2020-0787 - Windows BITS - An EoP Bug Hidden in an Undocumented RPC Function](https://itm4n.github.io/cve-2020-0787-windows-bits-eop/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), March 11, 2020  
- [From dropbox(updater) to NT AUTHORITY\SYSTEM](https://decoder.cloud/2019/12/18/from-dropboxupdater-to-nt-authoritysystem/) by [decoder](https://x.com/decoder_it), December 18, 2019  
- [Windows Privilege Escalation - DLL Proxying](https://itm4n.github.io/dll-proxying/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), Apr 18, 2019  

### Symbolic Links  
- [Piping Hot Fortinet Vulnerabilities (PDF)](https://pentera.io/wp-content/uploads/2024/11/pentera_labs_fortinet_cves-1.pdf) by Nir Chacko, November 2024
- [Breaking Barriers and Assumptions: Techniques for Privilege Escalation on Windows: Part 2](https://www.zerodayinitiative.com/blog/2024/7/30/breaking-barriers-and-assumptions-techniques-for-privilege-escalation-on-windows-part-2) by Michael DePlante and Nicholas Zubrisky, July 31, 2024  
- [Breaking Barriers and Assumptions: Techniques for Privilege Escalation on Windows: Part 1](https://www.zerodayinitiative.com/blog/2024/7/29/breaking-barriers-and-assumptions-techniques-for-privilege-escalation-on-windows-part-1) by Michael DePlante and Nicholas Zubrisky, July 30, 2024  
- [Avast Anti-Virus privileged arbitrary file create on virus quarantine (CVE-2023-1585 and CVE-2023-1587)](https://the-deniss.github.io/posts/2023/04/26/avast-privileged-arbitrary-file-create-on-quarantine.html) by Denis Skvortcov, April 26, 2023
- [Breaking Docker Named Pipes SYSTEMatically: Docker Desktop Privilege Escalation – Part 2](https://www.cyberark.com/resources/threat-research-blog/breaking-docker-named-pipes-systematically-docker-desktop-privilege-escalation-part-2) by Eviatar Gerzi, Apr 19, 2023
- [Breaking Docker Named Pipes SYSTEMatically: Docker Desktop Privilege Escalation – Part 1](https://www.cyberark.com/resources/threat-research-blog/breaking-docker-named-pipes-systematically-docker-desktop-privilege-escalation-part-1) by Eviatar Gerzi, Feb 2, 2023  
- [Breaking Antivirus: Arbitrary file deletion using Symbolic link](https://nixhacker.com/breaking-antivirus-arbitrary-delete-using-symbolic-link/) Apr 28, 2020  
- [An introduction to privileged file operation abuse on Windows](https://offsec.almond.consulting/intro-to-file-operation-abuse-on-Windows.html) by @clavoillotte
- [Avira Optimizer Local Privilege Escalation](https://enigma0x3.net/2019/08/29/avira-optimizer-local-privilege-escalation/) by enigma0x3, August 29, 2019  
- [CVE-2019-13382: Local Privilege Escalation in SnagIt](https://enigma0x3.net/2019/07/24/cve-2019-13382-privilege-escalation-in-snagit/) by enigma0x3, July 24, 2019  
- [CVE-2019-13142: Razer Surround 1.1.63.0 EoP](https://enigma0x3.net/2019/07/05/cve-2019-13142-razer-surround-1-1-63-0-eop/) by enigma0x3, July 5, 2019
- [Avira VPN (2.15.2.28160) Elevation of Privilege through Insecure Update location](https://enigma0x3.net/2019/03/20/avira-vpn-2-15-2-28160-elevation-of-privilege-through-insecure-update-location/) by enigma0x3, March 20, 2019
- [Razer Synapse 3 Elevation of Privilege](https://enigma0x3.net/2019/01/) by enigma0x3, January 21, 2019  
  
  
---  

## 🐧 Linux  
- [CVE-2021-22555: Turning \x00\x00 into 10000$](https://google.github.io/security-research/pocs/linux/cve-2021-22555/writeup.html) by Andy Nguyen (theflow@), 2021    
--- 

## ☁️ Kubernetes & Cloud   
- [What a Cluster: Local Volumes Vulnerability in Kubernetes](https://www.akamai.com/blog/security-research/kubernetes-local-volumes-command-injection-vulnerability-rce-system-privileges) by Tomer Peled, March 13, 2024 
- [Can't Be Contained: Finding a Command Injection Vulnerability in Kubernetes](https://www.akamai.com/blog/security-research/kubernetes-critical-vulnerability-command-injection) by Tomer Peled, September 13, 2023
- [Mitigating RBAC-Based Privilege Escalation in Popular Kubernetes Platforms](https://unit42.paloaltonetworks.com/kubernetes-privilege-escalation/) by Yuval Avrahami, January 27, 2023  
- [Kubernetes Pod Escape Using Log Mounts](https://www.aquasec.com/blog/kubernetes-security-pod-escape-log-mounts/) by Daniel Sagi (from Aqua)  
- [Dirty DAG: New Vulnerabilities in Azure Data Factory’s Apache Airflow Integration](https://unit42.paloaltonetworks.com/azure-data-factory-apache-airflow-vulnerabilities/) by Ofir Balassiano and David Orlovsky (Palo)
- [SynLapse – Technical Details for Critical Azure Synapse Vulnerability](https://orca.security/resources/blog/synlapse-critical-azure-synapse-analytics-service-vulnerability/) by Tzah Pahima
- [Kubernetes container runtime CRI-O has make-me-root flaw](https://www.theregister.com/2022/03/15/cr8escape_container_runtime_bug/) by Jessica Lyons, March 15, 2022  
- [Container Escape to Shadow Admin: GKE Autopilot Vulnerabilities](https://unit42.paloaltonetworks.com/gke-autopilot-vulnerabilities/) by Yuval Avrahami, March 8, 2022
- [All Roads leads to GKE's Host : 4+ Ways to Escape (PDF)](https://media.defcon.org/DEF%20CON%2030/DEF%20CON%2030%20presentations/Billy%20Jheng%20%20%20Muhammad%20Alifa%20Ramdhan%20-%20All%20Roads%20leads%20to%20GKEs%20Host%20%204%2B%20Ways%20to%20Escape.pdf) by Billy and Ramdhan, Oct 20, 2022  
- [Finding Azurescape – Cross-Account Container Takeover in Azure Container Instances](https://unit42.paloaltonetworks.com/azure-container-instances/) by Yuval Avrahami, September 9, 2021
- [Escaping Virtualized Containers (PDF)](https://i.blackhat.com/USA-20/Thursday/us-20-Avrahami-Escaping-Virtualized-Containers.pdf) by Yuval Avrahami, May 14, 2021  
- [Gaining Persistency on Vulnerable Lambdas](https://unit42.paloaltonetworks.com/gaining-persistency-vulnerable-lambdas/) by Yuval Avrahami, September 2, 2019
- [Securing Jenkins: Active Directory and LDAP Services in a Jenkins Environment](https://www.cyberark.com/resources/threat-research-blog/securing-jenkins-active-directory-and-ldap-services-in-a-jenkins-environment) by Nimrod Stoler, Jan 29, 2019  
- [Tripping the Jenkins Main Security Circuit-Breaker: An Inside Look at Two Jenkins Security Vulnerabilities](https://www.cyberark.com/resources/threat-research-blog/tripping-the-jenkins-main-security-circuit-breaker-an-inside-look-at-two-jenkins-security-vulnerabilities) by Nimrod Stoler, Oct 12, 2018  
- [Jenkins Plugins – Aladdin’s Lamp and the Sultan of Threats](https://www.cyberark.com/resources/threat-research-blog/jenkins-plugins-aladdin-s-lamp-and-the-sultan-of-threats) by Nimrod Stoler, Sep 26, 2018  
- [CyberArk Labs Research: Securing Jenkins Java Web Start Agents](https://www.cyberark.com/resources/threat-research-blog/cyberark-labs-research-securing-jenkins-java-web-start-agents) by Nimrod Stoler, Sep 11, 2018   
- [Configuring and Securing Credentials in Jenkins](https://www.cyberark.com/resources/threat-research-blog/configuring-and-securing-credentials-in-jenkins) by Nimrod Stoler, Aug 15, 2018  
  
### by Wiz  
- [RediShell: Critical Remote Code Execution Vulnerability (CVE-2025-49844) in Redis, 10 CVSS score](https://www.wiz.io/blog/wiz-research-redis-rce-cve-2025-49844) by Benny Isaacs and Nir Brakha, October 6, 2025  
- [Breaking NVIDIA Triton: CVE-2025-23319 - A Vulnerability Chain Leading to AI Server Takeover](https://www.wiz.io/blog/nvidia-triton-cve-2025-23319-vuln-chain-to-ai-server)  
- [NVIDIAScape - Critical NVIDIA AI Vulnerability: A Three-Line Container Escape in NVIDIA Container Toolkit (CVE-2025-23266)](https://www.wiz.io/blog/nvidia-ai-vulnerability-cve-2025-23266-nvidiascape), July 17, 2025  
- [How Wiz found a Critical NVIDIA AI vulnerability:  Deep Dive into a container escape (CVE-2024-0132)](https://www.wiz.io/blog/nvidia-ai-vulnerability-deep-dive-cve-2024-0132)  
- [IngressNightmare: CVE-2025-1974 - 9.8 Critical Unauthenticated Remote Code Execution Vulnerabilities in Ingress NGINX](https://www.wiz.io/blog/ingress-nginx-kubernetes-vulnerabilities)  
- [Wiz Research finds architecture risks that may compromise AI-as-a-Service providers and consequently risk customer data; works with Hugging Face on mitigations](https://www.wiz.io/blog/wiz-and-hugging-face-address-risks-to-ai-infrastructure)  
- [Probllama: Ollama Remote Code Execution Vulnerability (CVE-2024-37032) – Overview and Mitigations](https://www.wiz.io/blog/probllama-ollama-vulnerability-cve-2024-37032)  
- [GameOver(lay): Easy-to-exploit local privilege escalation vulnerabilities in Ubuntu Linux affect 40% of Ubuntu cloud workloads](https://www.wiz.io/blog/ubuntu-overlayfs-vulnerability)  
- [#BrokenSesame: Accidental ‘write’ permissions to private registry allowed potential RCE to Alibaba Cloud Database Services](https://www.wiz.io/blog/brokensesame-accidental-write-permissions-to-private-registry-allowed-potential-r)  
- [BingBang: How a simple developer mistake could have led to Bing.com takeover](https://www.wiz.io/blog/bingbang)  
- [Wiz Research discovers "ExtraReplica"— a cross-account database vulnerability in Azure PostgreSQL](https://www.wiz.io/blog/wiz-research-discovers-extrareplica-cross-account-database-vulnerability-in-azure-postgresql)  
- [ChaosDB explained: Azure's Cosmos DB vulnerability walkthrough](https://www.wiz.io/blog/chaosdb-explained-azures-cosmos-db-vulnerability-walkthrough)  

--- 

## 🐳 Containers  
- [Container Escape Techniques: Breaking Out of Docker, Kubernetes, and Beyond](https://danger-team.org/container-escape-techniques-breaking-out-of-docker-kubernetes-and-beyond/#what-are-containers-and-why-should-security-teams-care) by Rasoul, March 17, 2025  
- [Container Escapes 101 - Host memory meddling with ptrace](https://some-natalie.dev/container-escapes-ptrace/) by Natalie Somersall, Sep 5, 2025  
- [Exploit Notes - Docker Escape](https://exploit-notes.hdks.org/exploit/container/docker/docker-escape/) by hdks, Nov 2024  
- [Container Breakouts: Escape Techniques in Cloud Environments](https://unit42.paloaltonetworks.com/container-escape-techniques/) by Yosef Yaakov and Bar Ben-Michael, July 18, 2024
- [Breaking Free: 26 Advanced Techniques to Escape Docker Containers](https://infosecwriteups.com/breaking-free-26-advanced-techniques-to-escape-docker-containers-530049816b55) by ElNiak  Apr 8, 2024
- [Reversing Windows Container, episode II: Silo](https://blog.quarkslab.com/reversing-windows-container-part-ii-silo-to-server-silo.html) by Lucas Di Martino, March 26, 2024  
- [Buildkit GRPC SecurityMode privilege check: Build-time container breakout (CVE-2024-23653)](https://labs.snyk.io/resources/cve-2024-23653-buildkit-grpc-securitymode-privilege-check/) by Rory McNamara, Jan 31, 2024 
- [Buildkit mount cache race: Build-time race condition container breakout (CVE-2024-23651)](https://labs.snyk.io/resources/cve-2024-23651-docker-buildkit-mount-cache-race/) by Rory McNamara, Jan 31, 2024 
- [Buildkit build-time container teardown arbitrary delete (CVE-2024-23652)](https://labs.snyk.io/resources/cve-2024-23652-buildkit-build-time-container-teardown-arbitrary-delete/) by Rory McNamara, Jan 31, 2024  
- [Vulnerability: runc process.cwd and leaked fds container breakout (CVE-2024-21626)](https://labs.snyk.io/resources/cve-2024-21626-runc-process-cwd-container-breakout/) by Rory McNamara, Jan 31, 2024
- [CVE-2022-0492 (Carpediem) explained](https://www.hackthebox.com/blog/cve-2022-04920-carpe-diem-explained) by [David Glance (CyberMnemosyne)](https://www.hackthebox.com/blog/author/CyberMnemosyne), Dec 26, 2023  
- [Reversing Windows Container, episode I: Silo](https://blog.quarkslab.com/reversing-windows-container-episode-i-silo.html) by Lucas Di Martino, Sep 21, 2023  
- [Docker Security – Step-by-Step Hardening (Docker Hardening)](https://reynardsec.com/en/docker-platform-security-step-by-step-hardening/) by ReynardSec, October 16, 2023  
- [A new method for container escape using file-based DirtyCred](https://starlabs.sg/blog/2023/07-a-new-method-for-container-escape-using-file-based-dirtycred/) by Choo Yi Kai, July 25, 2023  
- [Container breakout (overview)](https://sec.vnpt.vn/2023/07/container-breakout-overview) by Red Team, July 25, 2023
- [Understanding Windows Containers Communication](https://www.cyberark.com/resources/threat-research-blog/understanding-windows-containers-communication) by Eviatar Gerzi, Sep 7, 2022  
- [corCTF 2022 CoRJail: From Null Byte Overflow To Docker Escape Exploiting poll_list Objects In The Linux Kernel](https://syst3mfailure.io/corjail/) by D3vil, Aug 17, 2022
- [Breakout from the Seccomp Unconfined Container](https://tbhaxor.com/breakout-from-seccomp-unconfined-container/) by Gurkirat Singh, May 2, 2022  
- [Container escape using dirtypipe](https://terenceli.github.io/%E6%8A%80%E6%9C%AF/2022/03/19/container-escape-through-dirtypipe), March 19, 2022  
- [Escaping privileged containers for fun](https://pwning.systems/posts/escaping-containers-for-fun/) by Jordy Zomer, March 6, 2022  
- [New Linux Vulnerability CVE-2022-0492 Affecting Cgroups: Can Containers Escape?](https://unit42.paloaltonetworks.com/cve-2022-0492-cgroups/) by Yuval Avrahami, March 3, 2022
- [How Docker Made Me More Capable and the Host Less Secure](https://www.cyberark.com/resources/threat-research-blog/how-docker-made-me-more-capable-and-the-host-less-secure) by Alon Zahavi, Feb 8, 2022  
- [Container escape techniques](https://reaper.gitbook.io/my-penetration-test-guide/privilege-escalation/linux-privilege-escalation/container-escape-techniques)
- [hide the current process executable file](https://scrivano.org/posts/2022-12-21-hide-self-exe/) by Giuseppe Scrivano, Dec 21, 2021
- [Container Host Breakout – Part 2](https://tbhaxor.com/container-host-breakout-part-2/) by Gurkirat Singh, Sep 11, 2021    
- [Container Host Breakout – Part 1](https://tbhaxor.com/container-host-breakout-part-1/)  by Gurkirat Singh, Sep 11, 2021   
- [Container Breakout – Part 2](https://tbhaxor.com/container-breakout-part-2/) by Gurkirat Singh, Sep 10, 2021   
- [Container Breakout – Part 1](https://tbhaxor.com/container-breakout-part-1/) by Gurkirat Singh, Sep 10, 2021  
- [Container escape in 2021 (binfmt_misc) - PDF](https://conference.hitb.org/hitbsecconf2021sin/materials/D2T2%20-%20Ccntainer%20Escape%20in%202021%20-%20Li%20Qiang.pdf) by Li Qiang, Sep 2, 2021
- [The Real-Life Story of the First Mainframe Container Breakout](https://media.defcon.org/DEF%20CON%2029/DEF%20CON%2029%20presentations/Ian%20Coldwater%20Chad%20Rikansrud%20%28Bigendian%20Smalls%29%20-%20The%20Real-Life%20Story%20of%20the%20First%20Mainframe%20Container%20Breakout.pdf) by Ian Coldwater and Chad, Aug 5, 2021  
- [Microsoft Patched the Issue With Windows Containers That Enabled Silosca](https://unit42.paloaltonetworks.com/windows-container-escape-patch/) by Daniel Prizmant, Aug 5, 2021   
- [Siloscape: First Known Malware Targeting Windows Containers to Compromise Cloud Environments](https://unit42.paloaltonetworks.com/siloscape/) by Daniel Prizmant, June 7, 2021
- [Escaping Virtualized Containers (PDF)](https://i.blackhat.com/asia-20/Friday/asia-20-Yuval-Avrahami-Escaping-Virtualized-Containers.pdf) (🔥) by Yuval Avrahami, May 14, 2021 - 🎥 [Talk](https://www.youtube.com/watch?v=jFlqVe11eeM)  
- [Who Contains the Containers?](https://googleprojectzero.blogspot.com/2021/04/who-contains-containers.html) (🔥) by James Forshaw, April 1, 2021   
- [The Strange Case of How We Escaped the Docker Default Container](https://www.cyberark.com/resources/threat-research-blog/the-strange-case-of-how-we-escaped-the-docker-default-container) by Nimrod Stoler and Gilad Reti, March 4, 2021
- [BitBucket Pipelines Kata Containers Virtual Machine Escape](https://blog.ajxchapman.com/posts/2021/02/28/kata-containers-escape.html) by [Alex Chapman](https://github.com/ajxchapman), Feb 28, 2021   
- [Towards Improving Container Security by Preventing Runtime Escapes (PDF)](https://www.osti.gov/servlets/purl/1890908), 2021  
- [Container Breakouts – Part 3: Docker Socket](https://blog.nody.cc/posts/container-breakouts-part3/) by Jan Harrie, July 30, 2020  
- [Container Breakouts – Part 2: Privileged Container](https://blog.nody.cc/posts/container-breakouts-part2/) by Jan Harrie, July 21, 2020  
- [Container Breakouts – Part 1: Access to root directory of the Host](https://blog.nody.cc/posts/container-breakouts-part1/) by Jan Harrie, July 15, 2020
- [Windows Server Containers Are Open, and Here's How You Can Break Out](https://unit42.paloaltonetworks.com/windows-server-containers-vulnerabilities/?pdf=print&lg=en&_wpnonce=49ce28271a) by Daniel Prizmant, July 15, 2020
- [Docker Container Breakout: Abusing SYS_MODULE capability!](https://blog.pentesteracademy.com/abusing-sys-module-capability-to-perform-docker-container-breakout-cf5c29956edd) by Nishant Sharma, May 6, 2020
- [Privileged Container Escape - Control Groups release_agent](https://blog.ajxchapman.com/posts/2020/11/19/privileged-container-escape.html) by [Alex Chapman](https://github.com/ajxchapman), Nov 19, 2020    
- [Privileged Container Escapes with Kernel Modules](https://xcellerator.github.io/posts/docker_escape/) by TheXcellerator, Sep 27, 2020  
- [Security Analysis of User Namespaces and Rootless Containers](https://d-nb.info/1222589206/34) by Anton Semjonov, Jan 2020  
- [What I Learned from Reverse Engineering Windows Containers](https://unit42.paloaltonetworks.com/what-i-learned-from-reverse-engineering-windows-containers/) by Daniel Prizmant, Dec 12, 2019
- [Understanding Docker container escapes](https://blog.trailofbits.com/2019/07/19/understanding-docker-container-escapes/) by Dominik Czarnota, July 19, 2019  
- [CVE-2019-11253: Kubernetes API Server JSON/YAML parsing vulnerable to resource exhaustion attack](https://github.com/kubernetes/kubernetes/issues/83253) by Rory McCune, Sep 27, 2019
- [AppArmor can be bypassed by a malicious image that specifies a volume at /proc](https://github.com/opencontainers/runc/issues/2128), Sep 22, 2019  
- [A Complendium of Container Escapes - PDF](https://i.blackhat.com/USA-19/Thursday/us-19-Edwards-Compendium-Of-Container-Escapes-up.pdf) (🔥) by Brandon Edwards and Nick Freeman from Capsule8, August 2019  
- [Breaking Out of rkt – 3 New Unpatched CVEs](https://unit42.paloaltonetworks.com/breaking-out-of-coresos-rkt-3-new-cves/) by Yuval Avrahami, May 30, 2019  
- [The Route to Root: Container Escape Using Kernel Exploitation](https://www.cyberark.com/resources/threat-research-blog/the-route-to-root-container-escape-using-kernel-exploitation) (🔥) by Nimrod Stoler, March 4, 2019
- [Breaking out of Docker via runC – Explaining CVE-2019-5736](https://unit42.paloaltonetworks.com/breaking-docker-via-runc-explaining-cve-2019-5736/) (🔥) by Yuval Avrahami, Feb 21, 2019
- [An Exercise in Practical Container Escapology](https://web.archive.org/web/20210425171222/https://capsule8.com/blog/practical-container-escape-exercise/) by Capsule8, Feb 21, 2019  
- [How I Hacked Play-with-Docker and Remotely Ran Code on the Host](https://www.cyberark.com/resources/secure-third-party-vendor-and-remote-access/how-i-hacked-play-with-docker-and-remotely-ran-code-on-the-host) (🔥) by Nimrod Stoler, Jan 14, 2019  
- [Container Basics and Escapes](https://0xn3va.gitbook.io/cheat-sheets/container/overview/basics) by [0xn3va](https://github.com/0xn3va)
- [Container Breakout Vulnerabilities](https://www.container-security.site/attackers/container_breakout_vulnerabilities.html), by Rory McCune
- [Csw2016 wang docker_escapetechnology](https://www.slideshare.net/slideshow/csw2016-wang-dockerescapetechnology/60387867) by Wang, 2016  
- [Understanding and Hardening Linux Containers - PDF](https://www.nccgroup.com/media/eoxggcfy/_ncc_group_understanding_hardening_linux_containers-1-1.pdf) by NCC Group, Jun 29, 2016  
- [Abusing Privileged and Unprivileged Linux Containers - PDF](https://www.nccgroup.com/media/bjobstnx/_container_whitepaper.pdf) by NCC Group, Jun 29, 2016
- [PoC for Dirty COW (CVE-2016-5195)](https://github.com/scumjr/dirtycow-vdso) by scumjr, 2016  
- [Docker breakout exploit analysis (shocker)](https://medium.com/@fun_cuddles/docker-breakout-exploit-analysis-a274fff0e6b3) by Jen Andre, Jun 19, 2014
- [Shocker / Docker Breakout PoC](https://github.com/gabrtv/shocker) by Gabe Monroy, Jun 18, 2014
- [shocker: docker PoC VMM-container breakout](http://stealth.openwall.net/xSports/shocker.c) by Sebastian Krahmer, Jun 18, 2014
- [Memory inside Linux containers](https://fabiokung.com/2014/03/13/memory-inside-linux-containers/) by Fabio Kung, March 13, 2014   


--- 

## 📱 Android & Mobile  

---
## Web  
- [Breaking Oracle’s Identity Manager: Pre-Auth RCE (CVE-2025-61757)](https://slcyber.io/research-center/breaking-oracles-identity-manager-pre-auth-rce/) by Adam Kues and Shubham Shah, November 20, 2025  
- [How I Found a Critical Password Reset Bug in the BB program(and Got $4,000)](https://medium.com/@s41n1k/how-i-found-a-critical-password-reset-bug-in-the-bb-program-and-got-4-000-a22fffe285e1)
- [Account Takeover via Password Reset without user interactions](https://gitlab.com/gitlab-org/gitlab/-/issues/436084)
- [Shockwave Identifies Web Cache Deception and Account Takeover Vulnerability affecting OpenAI's ChatGPT](https://www.shockwave.cloud/blog/shockwave-works-with-openai-to-fix-critical-chatgpt-vulnerability) by Gal Nagli, July 15, 2024  
- [CVE-2024-25153: Remote Code Execution in Fortra FileCatalyst](https://www.lrqa.com/en/cyber-labs/cve-2024-25153-remote-code-execution-in-fortra-filecatalyst/) by Tom Wedgbury, March 13, 2024  
- [ChatGPT Account Takeover - Wildcard Web Cache Deception](https://nokline.github.io/bugbounty/2024/02/04/ChatGPT-ATO.html) (🔥) by [Harel](https://x.com/h4r3l), Feb 4, 2024
- [Sandwich Attack UUIDv1](https://x.com/0xLupin/status/1745805050562105739) by [0xLupin](https://x.com/0xLupin), Jan 12, 2024
- [Hacking Chess.com and Accessing 50 Million Customer Records](https://samcurry.net/hacking-chesscom) by Sam Curry, Dec 16, 2020  
- [We Hacked Apple for 3 Months: Here’s What We Found](https://samcurry.net/hacking-apple) by Sam Curry, Oct 7, 2020  
- [Old but GOLD Dot Dot Slash to Get the Flag — Uber Microservice](https://ngailong.wordpress.com/2019/04/07/old-but-gold-dot-dot-slash-to-get-the-flag-uber-microservice/) by Ron Chan, April 7, 2019  
- [Tutorial One: Open Url Redirects](https://web.archive.org/web/20190523023839/https://zseano.com/tutorials/1.html) by Zseano, Sep 14, 2017   
- [Tutorials by zseano](https://web.archive.org/web/20190520052806/https://zseano.com/index.html) by Zseano, Sep 14, 2017
- [Web Cache Deception Attack](https://omergil.blogspot.com/2017/02/web-cache-deception-attack.html) (🔥) by Omer Gil, Feburary 27, 2017
---
## Bug Bounty
- [$10,500 Bounty: A Grammarly Account Takeover Vector](https://infosecwriteups.com/10-500-bounty-a-grammarly-account-takeover-vector-974ef90fb00a) by [Monika sharma](https://medium.com/@commanak46)  
---

## 🌐 Identity  
- [One Token to rule them all - obtaining Global Admin in every Entra ID tenant via Actor tokens](https://dirkjanm.io/obtaining-global-admin-in-every-entra-id-tenant-with-actor-tokens/) by Dirk-jan Mollema, September 17, 2025    
- [Forging Passkeys: Exploring the FIDO2 / WebAuthn Attack Surface](https://nullpt.rs/forging-passkeys) by [vmfunc](https://x.com/vmfunc), June 20, 2025
- [Bypassing Windows Hello Without Masks or Plastic Surgery](https://www.cyberark.com/resources/threat-research-blog/bypassing-windows-hello-without-masks-or-plastic-surgery) by Omer Tsarfati, Jul 17, 2023  
- [Abusing FIDO2 passkeys to take over Global Administrators in Entra ID](https://cybersecurity.bureauveritas.com/services/information-technology/pentesting-services/what-can-be-pentested/cloud-pentesting/abusing-fido2-passkeys) by Max Rozendaal  




### OAuth  

- [Common OAuth Vulnerabilities](https://blog.doyensec.com/2025/01/30/oauth-common-vulnerabilities.html) by Jose Catalan and Szymon Drosdzol, Jan 30, 2025  
- [Understanding OAuth 2.0 and its Common Vulnerabilities](https://www.vaadata.com/blog/understanding-oauth-2-0-and-its-common-vulnerabilities/) by Vaadata, January 9, 2025   
- [Account hijacking using “dirty dancing” in sign-in OAuth-flows](https://labs.detectify.com/writeups/account-hijacking-using-dirty-dancing-in-sign-in-oauth-flows/) (🔥) by Frans Rosén  
- [OAuth Non-Happy Path to ATO](https://blog.voorivex.team/oauth-non-happy-path-to-ato) by Omid Rezaei  
- [Common OAuth Vulnerabilities](https://blog.doyensec.com/2025/01/30/oauth-common-vulnerabilities.html) by Jose Catalan and Szymon Drosdzol, Jan 30, 2025  
- [The OAuth Oversight: When Configuration Errors Turn into Account Hijacks](https://medium.com/@ProwlSec/the-oauth-oversight-when-configuration-errors-turn-into-account-hijacks-5ed1f9c83d16) by ProwlSec, Nov 4, 2024
- [Uber - Navigating the Complexities of redirect_uri: A Bug Bounty Journey](https://www.novasecurity.co.nz/uber-navigating-the-complexities-of-redirect-uri-a-bug-bounty-journey/) by Ron Chan, Jun 14, 2024  
- [Writeup: Keycloak open redirect (CVE-2023-6927)](https://securityblog.omegapoint.se/en/writeup-keycloak-cve-2023-6927/) (🔥🔥) by Pontus Hanssen and Kasper Karlsson, January 11, 2024  
- [Google OAuth is Broken (Sort Of)](https://trufflesecurity.com/blog/google-oauth-is-broken-sort-of) (🔥) by Dylan Ayrey, December 15, 2023
- [nOAuth: How Microsoft OAuth Misconfiguration Can Lead to Full Account Takeover](https://www.descope.com/blog/post/noauth) by Omer Cohen, June 20, 2023
- [OAuth 2.0 Hunting Methodology](https://github.com/KathanP19/HowToHunt/blob/master/OAuth/OAuth%202.0%20Hunting%20Methodology.md) by KathanP19, Sep 18, 2022  
- [OAuth 2.0 Vulnerabilities](https://0xn3va.gitbook.io/cheat-sheets/web-application/oauth-2.0-vulnerabilities) by 0xn3va
- [Make Redirection Evil Again: URL Parser Issues in OAuth](https://i.blackhat.com/asia-19/Fri-March-29/bh-asia-Wang-Make-Redirection-Evil-Again-wp.pdf) by Chinese University, March 29, 2019
- [[Google VRP] SSRF in Google Cloud Platform StackDriver](https://ngailong.wordpress.com/2019/12/19/google-vrp-ssrf-in-google-cloud-platform-stackdriver/) by Ron Chan, Dec 19, 2019
- [[Uber] redirect_uri is difficult to do it right](https://ngailong.wordpress.com/2017/11/22/uber-redirect_uri-is-difficult-to-do-it-right/) (🔥) by Ron Chan, Nov 22, 2017
- [[Uber 8k Bug] Login CSRF + Open Redirect = Account Take Over](https://ngailong.wordpress.com/2017/08/07/uber-login-csrf-open-redirect-account-takeover/) by Ron Chan, August 7, 2017  
- [Facebook's Moves - OAuth redirect_uri bypass](https://www.evil.blog/2016/06/facebooks-moves-oauth-redirecturi-bypass.html) by Paulos Yibelo, June, 2016
- [Oauth 2.0 redirection bypass cheat sheet](https://nbsriharsha.blogspot.com/2016/04/oauth-20-redirection-bypass-cheat-sheet.html) by N B Sri Harsha, Apr, 2016
- [CSRF Vulnerability in OAuth 2.0 Client Implementations](https://web.archive.org/web/20140806042247/http://stephensclafani.com/2011/04/06/oauth-2-0-csrf-vulnerability/) by Stephen Sclafani, Apr 6, 2011  

### by Aviad Carmel from Salt  
- [Traveling with OAuth — Account Takeover on Booking.com](https://salt.security/blog/traveling-with-oauth-account-takeover-on-booking-com) (🔥) - 🎥 [Talk](https://www.youtube.com/watch?v=BxiL4Vf_umI)
- [Salt Labs exposes a new vulnerability in popular OAuth framework, used in hundreds of online services](https://salt.security/blog/a-new-oauth-vulnerability-that-may-impact-hundreds-of-online-services)  
- [Oh-Auth — Abusing OAuth to take over millions of accounts](https://salt.security/blog/oh-auth-abusing-oauth-to-take-over-millions-of-accounts)  
- [Security Flaws within ChatGPT Ecosystem Allowed Access to Accounts On Third-Party Websites and Sensitive Data](https://salt.security/blog/security-flaws-within-chatgpt-extensions-allowed-access-to-accounts-on-third-party-websites-and-sensitive-data)  
- [Over 1 Million websites are at risk of sensitive information leakage — XSS is dead. Long live XSS](https://salt.security/blog/over-1-million-websites-are-at-risk-of-sensitive-information-leakage---xss-is-dead-long-live-xss)  

--- 
## 🔑 Supply Chain & Secrets 
- [Guest Post: How I Scanned all of GitHub’s “Oops Commits” for Leaked Secrets](https://trufflesecurity.com/blog/guest-post-how-i-scanned-all-of-github-s-oops-commits-for-leaked-secrets)


---

## 🧩 Memory & Exploitation  

---

## 🔐 Cryptography  

---

## 🌀 Miscellaneous  

- [Trust Me, I’m a Robot: Can We Trust RPA With Our Most Guarded Secrets?](https://www.cyberark.com/resources/threat-research-blog/trust-me-i-m-a-robot-can-we-trust-rpa-with-our-most-guarded-secrets) (🔥) by Nimrod Stoler
- [CVE-2019-1306: Are you my Index?](https://www.zerodayinitiative.com/blog/2019/10/23/cve-2019-1306-are-you-my-index) by [Mikhail Shcherbakov](https://x.com/yu5k3)
---

## CTFs WriteUps
### Containers  
- [Contain Me If You Can - Wiz Cloud CTF July](https://tresscross.blog/contain-me-if-you-can-wiz-cloud-ctf-july/) by Jason Walker, Aug 31, 2025  
---

⭐ Feel free to [contribute](CONTRIBUTING.md) — add new articles under the correct section, keep entries alphabetized, and provide a short description.
