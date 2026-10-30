<div align="center">

<pre>
┌─────────────────────────────────────────────────────────────────────────────┐
│  ●  ●  ●   [Investigator-S@soc-workstation: ~] - Defensive Ops Terminal     │
└─────────────────────────────────────────────────────────────────────────────┘
</pre>

<a href="https://github.com/Investigator-S">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=1000&color=00FF66&background=0D111700&center=true&vCenter=true&width=700&lines=Investigator-S+--role=%22OSINT+Analyst+%26+Defensive+Security%22;extracting+threat-actor+infrastructure+%26+malicious+C2+IPs;intercepting+pre-encryption+ransomware+telemetry;auditing+AWS+IAM+posture+%26+cloud+misconfigurations" alt="Animated Terminal Header" />
</a>

<p align="center">
  <img src="https://img.shields.io/badge/OPERATIONAL%20STATUS-ACTIVE-00FF66?style=flat-square&logo=radar&logoColor=black" />
  <img src="https://img.shields.io/badge/PRIMARY%20FOCUS-BLUE%20TEAM%20DEFENSE-0d1117?style=flat-square&logo=shield&logoColor=00FF66" />
  <img src="https://img.shields.io/badge/THREAT%20TELEMETRY-MONITORING-0d1117?style=flat-square&logo=wireshark&logoColor=00FF66" />
  <img src="https://img.shields.io/badge/CLOUD-AWS%20HARDENED-0d1117?style=flat-square&logo=amazonwebservices&logoColor=00FF66" />
</p>

</div>

---

### ⚡ Operational Telemetry & Active Arsenal

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,bash,c,linux,aws,docker,git,regex,vscode,githubactions&theme=dark" />
  </a>
</p>

```diff
+ [SYSTEM READY] Node: Investigator-S | Role: OSINT & Threat Defense
+ [TELEMETRY]    Scanning C2 endpoints, entropy spikes, and cloud perimeters
+ [SUBSYSTEMS]   AWS Auditing (Active) • Malware Triage (Active) • EDR Watchdog (Active)
```

---

### 🖥️ `$ cat /etc/security_modules/active_deployments` *(Click to expand)*

<details open>
  <summary><b>🟢 [MODULE 01] Ransomware-Early-Warning-System-Design</b></summary>
  <br/>

  > **Mission:** Intercept and neutralize ransomware behavior before payload encryption completes.

  ```bash
  $ ./edr_watchdog --monitor-io --canary-trap /var/canaries/ --entropy-threshold 7.25
  ```
  * **Shannon Entropy Analysis:** Real-time calculation of bulk file entropy to spot rapid AES/ChaCha cipher operations.
  * **Tripwire Canary Decoys:** High-sensitivity sentinel files that trigger instant process tree quarantine upon alteration.
  * **VSS Defense:** Behavioral interception of shadow copy purge commands (`vssadmin delete shadows`, `wbadmin`, `wmic`).
</details>

<details open>
  <summary><b>🟢 [MODULE 02] AWS_SPLOIT_TOOL (Cloud Posture Engine)</b></summary>
  <br/>

  > **Mission:** Continuous vulnerability assessment and attack-path enumeration across AWS estates.

  ```bash
  $ python3 aws_sploit.py --audit-iam --enumerate-s3 --check-security-groups --region all
  ```
  * **IAM Privilege Escalation:** Detects dangerous permission combinations (`iam:PassRole`, `sts:AssumeRole` policy loopholes).
  * **Public Storage Leaks:** Scans S3 buckets for open ACLs, public write privileges, and missing KMS encryption.
  * **Exposed Ingress Vectors:** Flags unmonitored security groups exposing high-risk ports (`22`, `3389`, `5432`, `9200`).
</details>

<details>
  <summary><b>🟢 [MODULE 03] ThreatLens-Security-Suite (Malware Triage)</b></summary>
  <br/>

  > **Mission:** Automated binary dissection, memory inspection, and C2 IP indicator harvesting.

  ```bash
  $ threatlens triage --sample payload.bin --extract-c2 --enrich-abuseipdb
  ```
  * **C2 Harvester:** Extracts hardcoded IP addresses, domains, and port markers from unpacked PE configurations.
  * **Static Forensics:** Section entropy mapping, string decryption, and suspicious import analysis.
  * **Threat Intel Feeds:** Correlates extracted infrastructure against VirusTotal, AlienVault OTX, and AbuseIPDB.
</details>

<details>
  <summary><b>🟢 [MODULE 04] TR3-Astra (Network & Recon Surface)</b></summary>
  <br/>

  > **Mission:** Asynchronous reconnaissance engine for digital asset mapping and surface attack audits.

  ```bash
  $ astra scan --target target.domain --concurrency 50 --verify-headers
  ```
  * **Port & Service Sweep:** High-throughput TCP SYN/ACK scanner with heuristic banner grabbing.
  * **Compliance & Headers:** Automatic verification of `HSTS`, `Content-Security-Policy`, and SSL/TLS cipher suites.
  * **Passive OSINT Footprinting:** Certificate transparency mining (`crt.sh`) and reverse ASN routing correlation.
</details>

---

### 🕹️ `$ ./launch_arcade.sh --mode=all` *(Interactive Contribution Games)*

<details open>
  <summary><b>🎮 Arcade 01: Cyber Snake Defense Grid</b></summary>
  <br/>
  <p align="center">
    <img alt="Cyber Snake Game" src="https://raw.githubusercontent.com/Investigator-S/Investigator-S/gh-pages/github-contribution-grid-snake-dark.svg" width="100%" />
  </p>
</details>

<details open>
  <summary><b>🕹️ Arcade 02: Pac-Man Threat Ingestion Arena</b></summary>
  <br/>
  <p align="center">
    <img alt="Pacman Contribution Game" src="https://raw.githubusercontent.com/Investigator-S/Investigator-S/gh-pages/github-contribution-grid-pacman-dark.svg" width="100%" />
  </p>
</details>

---

### 📊 Live Activity Stream & Contribution Metrics

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Investigator-S&theme=tokyonight&hide_border=true" width="49%" alt="GitHub Streak" />
</p>

---

<div align="center">
  <sub><code>[EOF] Threat monitoring subroutines active. Terminal idle.</code></sub>
</div>
