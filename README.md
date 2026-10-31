
<div align="center">

<a href="https://github.com/Investigator-S">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=2800&pause=1000&color=00FF66&background=0D111700&center=true&vCenter=true&width=600&height=100&multiline=true&repeat=true&lines=Investigator-S+%7C+OSINT+Analyst;Threat+Intelligence+%26+Defensive+Security;Malware+Analysis+%7C+Cloud+Security;Network+Forensics+%7C+Infrastructure+Mapping" width="100%" alt="Investigator-S Terminal Header" />
</a>

**OSINT ANALYST | DEFENSIVE SECURITY | CYBER FORENSICS**

<img src="https://img.shields.io/badge/STATUS-ACTIVE-00FF66?style=flat-square&logo=radar&logoColor=black" />
<img src="https://img.shields.io/badge/FOCUS-BLUE%20TEAM-0d1117?style=flat-square&logo=shield&logoColor=00FF66" />
<img src="https://img.shields.io/badge/THREAT%20INTEL-MONITORING-0d1117?style=flat-square&logo=wireshark&logoColor=00FF66" />
<img src="https://img.shields.io/badge/CLOUD-AWS-0d1117?style=flat-square&logo=amazonwebservices&logoColor=00FF66" />

</div>

---

## `$ whoami`

```bash
USER       : Investigator-S
ROLE       : OSINT Analyst & Defensive Security
SPECIALTY  : Cyber Threat Intelligence
FOCUS      : Malware Analysis | Network Forensics
OPERATIONS : Threat Hunting | Cloud Security
ENVIRONMENT: Linux | Python | AWS
STATUS     : ACTIVE
```

---

##  Operational Arsenal

<div align="center">

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=py,bash,c,linux,aws,docker,git,regex,vscode,githubactions&theme=dark" width="100%" alt="Technical Skills" />
</a>

</div>

---

## `$ cat /etc/security_modules/active_deployments`

<b>MODULE 01 — Ransomware Early Warning System</b>

Detect and interrupt ransomware activity before payload encryption completes.

```bash
./edr_watchdog --monitor-io --canary-trap /var/canaries--entropy-threshold 7.25
```

**CAPABILITIES**

- **Shannon Entropy Analysis:** Detect abnormal file entropy changes and bulk encryption behavior.
- **Tripwire Canary Decoys:** Monitor sentinel files and trigger alerts on unauthorized modification.
- **VSS Defense:** Detect attempts to delete Windows shadow copies using `vssadmin`, `wbadmin`, and `wmic`.



<b>MODULE 02 — AWS_SPLOIT | Cloud Posture Engine</b>

Continuous AWS security assessment and attack-path enumeration.

```bash
python3 aws_sploit.py --audit-iam --enumerate-s3 --check-security-groups --region all
```

**CAPABILITIES**

- **IAM Privilege Escalation:** Identify dangerous permission combinations, including `iam:PassRole` and `sts:AssumeRole`.
- **Public Storage Exposure:** Detect risky S3 ACLs, public write permissions, and missing encryption.
- **Exposed Ingress Vectors:** Identify risky security group rules involving ports `22`, `3389`, `5432`, and `9200`.


<b>MODULE 03 — ThreatLens | Malware Triage Suite</b>

Automated binary analysis, malware triage, and C2 indicator extraction.

```bash
threatlens triage --sample payload.bin --extract-c2 --enrich-abuseipdb
```

**CAPABILITIES**

- **C2 Harvester:** Extract embedded IP addresses, domains, and port indicators.
- **Static Forensics:** Section entropy mapping, string analysis, and suspicious import inspection.
- **Threat Intelligence:** Correlate extracted infrastructure with VirusTotal, AlienVault OTX, and AbuseIPDB.


<b>MODULE 04 — TR3-Astra | Network Reconnaissance</b>

Asynchronous reconnaissance and external attack-surface assessment.

```bash
astra scan --target target.domain --concurrency 50 --verify-headers
```

**CAPABILITIES**

- **Port & Service Discovery:** TCP service scanning and banner analysis.
- **Security Auditing:** Verify HSTS, Content Security Policy, and SSL/TLS configurations.
- **Passive OSINT:** Certificate transparency analysis and ASN infrastructure correlation.


---

<div align="center">
</div>
<div align="center">
<img
  src="https://raw.githubusercontent.com/Investigator-S/Investigator-S/output/pacman-contribution-graph.svg"
  width="100%"
  alt="Pac-Man GitHub Contribution Animation"
/>
</div>

<div align="center">

<img
  src="https://raw.githubusercontent.com/Investigator-S/Investigator-S/gh-pages/github-contribution-grid-snake-dark.svg"
  width="100%"
  alt="Cyber Snake Contribution Animation"
/>

</div>

---

## `$ cat /etc/identity/operational_profile`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Investigator-S&show_icons=true&theme=chartreuse-dark&hide_border=true&bg_color=0D1117&title_color=00FF66&icon_color=00FF66&text_color=C9D1D9" width="100%" alt="GitHub Statistics" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Investigator-S&theme=dark&hide_border=true&background=0D1117&ring=00FF66&fire=00FF66&currStreakLabel=00FF66" width="100%" alt="GitHub Contribution Streak" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Investigator-S&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0D1117&title_color=00FF66&text_color=C9D1D9" width="100%" alt="Top Programming Languages" />

</div>

---

## `$ ./system_status.sh`

```text
[+] OSINT ENGINE              : ONLINE
[+] THREAT INTELLIGENCE       : ACTIVE
[+] MALWARE TRIAGE            : READY
[+] NETWORK FORENSICS         : READY
[+] CLOUD SECURITY            : MONITORING
[+] CYBER ARCADE              : INITIALIZED

[EOF] Threat monitoring subroutines active.
```

---

<div align="center">

### INVESTIGATOR-S

**OSINT • DIGITAL FORENSICS • THREAT INTELLIGENCE • DEFENSIVE SECURITY**

<a href="https://github.com/Investigator-S">
  <img src="https://img.shields.io/badge/GitHub-INVESTIGATOR--S-0d1117?style=for-the-badge&logo=github&logoColor=00FF66" />
</a>

<sub><code>[EOF] Terminal idle. Monitoring continues.</code></sub>

</div>
