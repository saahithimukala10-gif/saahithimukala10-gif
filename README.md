```bash
$ whoami
saahithi@security:~$ cat about.txt

> Final-year Cybersecurity student, building detection engineering skills from the ground up
> Deployed a Wazuh SIEM homelab — measured real ATT&CK coverage across 13 techniques, tuned custom rules to kill false positives
> Modeled AWS attack paths to AdministratorAccess (CloudChain) and tested LLM triage against prompt-injection attacks
> Ranked Top 8% on TryHackMe
> Status: open to opportunities
```

<p align="center">
  <img src="https://img.shields.io/badge/ISC2-Certified%20in%20Cybersecurity-6D4C41?style=for-the-badge&logo=isc2&logoColor=F5E6D3" />
  <img src="https://img.shields.io/badge/Cisco-CCNA-795548?style=for-the-badge&logo=cisco&logoColor=F5E6D3" />
  <img src="https://img.shields.io/badge/TryHackMe-Top%208%25-4E342E?style=for-the-badge&logo=tryhackme&logoColor=F5E6D3" />
</p>

<br>

## About Me

<details open>
<summary><b>Background</b></summary>
<br>

- Final-year B.Tech CSIT (Cyber Security) student at Symbiosis Skills and Professional University
- Background in compliance frameworks — GDPR, DPDP Act 2023, ISO 27001, NIST CSF 2.0
- Ranked Top 8% on TryHackMe
- Enjoy building personal projects outside coursework — productivity tools, small apps, homelabs

</details>

<details>
<summary><b>What I'm building</b></summary>
<br>

**SOC Homelab** — *personal, ongoing*
Deployed a Wazuh SIEM from scratch on an isolated KVM lab, instrumenting a Windows 11 endpoint with layered telemetry (Sysmon, audit policy, PowerShell logging). Ran 13 MITRE ATT&CK techniques across 6 tactics via Atomic Red Team to measure real detection coverage, then authored and paired-validated custom Wazuh rules — including catching LSASS credential dumping and ransomware-precursor shadow-copy deletion — while fixing false positives in stock rules along the way.
[github.com/saahithimukala10-gif/soc-homelabs](https://github.com/saahithimukala10-gif/soc-homelabs)

**SOC Pipeline — Prompt-Injection Resistance in Automated Triage** — *4-person research project*
Owned the evaluation harness for a team research project testing whether LLM-based SOC alert triage can be manipulated by prompt injection. Ran multi-model inference (Qwen 2.5 7B via Ollama, Gemini via API) against clean and poisoned MITRE ATT&CK alert variants, measuring attack-success rate, triage precision/recall, and false-negative rate across models — feeding into a team paper targeting IEEE/Scopus.

**CloudChain** — *team project, contributor*
Attack-path-aware CSPM for AWS — models resources as a dependency graph to find realistic attack chains to `AdministratorAccess` instead of flagging isolated misconfigurations. Implemented read-only path validation and risk scoring; backed by 194 tests and CI/CD.
[github.com/threetheodrummer/CloudChain](https://github.com/threetheodrummer/CloudChain)

**Kernox** — *group project*
An eBPF-based EDR platform monitoring Linux endpoints in real time. Built the React/TypeScript visualization layer surfacing alerts and suspicious-behavior signals from the backend correlation engine, plus supporting API work.

</details>

<details>
<summary><b>Certifications & hands-on labs</b></summary>
<br>

| Status | Credential |
|:---:|---|
| Done | ISC2 Certified in Cybersecurity (CC) |
| Done | Cisco Certified Network Associate (CCNA) |
| Done | TryHackMe — Pre Security |
| In progress | TryHackMe — SOC Level 1 |
| Done | OverTheWire — Bandit, Natas, Krypton, Leviathan |

CTF write-ups: Bandit, Natas, Krypton, Leviathan (OverTheWire), plus TryHackMe rooms — [github.com/saahithimukala10-gif/ctf-writeups](https://github.com/saahithimukala10-gif/ctf-writeups)

</details>

<br>

## Tech & Tools

Python · Flutter · FastAPI · React · TypeScript · MongoDB · SQL · Docker · Wazuh · AWS · Linux

<br>

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=saahithimukala10-gif&show_icons=true&hide_border=true&bg_color=00000000&title_color=8D6E63&text_color=4E342E&icon_color=795548&ring_color=795548" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=saahithimukala10-gif&hide_border=true&background=00000000&ring=795548&fire=8D6E63&currStreakLabel=4E342E&sideLabels=4E342E&currStreakNum=4E342E&sideNums=4E342E&dates=795548" width="48%" />

<br>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=saahithimukala10-gif&layout=compact&hide_border=true&bg_color=00000000&title_color=8D6E63&text_color=4E342E" width="40%" />

</div>

<br>

## Connect

<p align="center">
  <a href="https://linkedin.com/in/saahithi-mukala">
    <img src="https://img.shields.io/badge/-LinkedIn-6D4C41?style=for-the-badge&logo=linkedin&logoColor=F5E6D3" />
  </a>
  <a href="https://github.com/saahithimukala10-gif">
    <img src="https://img.shields.io/badge/-GitHub-4E342E?style=for-the-badge&logo=github&logoColor=F5E6D3" />
  </a>
</p>

<div align="center">
<i>Open to opportunities and conversations in cybersecurity, software development, and beyond.</i>
</div>
