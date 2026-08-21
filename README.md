<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0078D4&height=180&section=header&text=Tarun%20Teja%20Reddy&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Blue%20Team%20Security%20Engineer%20%C2%B7%20Microsoft%20Azure%20Specialist&descAlignY=58&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1000&color=0078D4&center=true&vCenter=true&width=650&lines=Incident+Investigation+%26+Response;KQL+Detection+Engineering;Threat+Hunting+%7C+MITRE+ATT%26CK;Microsoft+Azure+Security+Specialist" alt="Typing SVG"/>

<br/><br/>

[![Email](https://img.shields.io/badge/-tarunteja.desireddy9%40gmail.com-0078D4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tarunteja.desireddy9@gmail.com)

</div>

<br/>

## About

Security engineer specializing in **defensive operations on Microsoft Azure** — incident investigation, KQL-based detection engineering, and threat hunting across a multi-tenant government and critical-infrastructure client base. Outside client work, building and open-sourcing a personal Azure SIEM lab from the ground up: infrastructure as code, custom detections, and SOAR automation — deployed and tested, not templated.

<br/>

## 🚀 Featured Work

Proof of the SIEM side of the job: architecting and deploying from zero, not just operating on top of what a client already built.

### [cybersoc-portfolio](https://github.com/TaruntejaDesireddy/cybersoc-portfolio) — a Sentinel SOC, end to end

| Inside | What it is |
|---|---|
| **Analytics rules** | 60 custom-authored scheduled rules — no gallery templates. Every one written against a table confirmed to be ingesting, because a rule that *cannot* fire is worse than no rule: it fakes coverage |
| **SOAR playbooks** | Logic Apps for multi-source IP enrichment and containment — secrets in Key Vault, read at runtime via managed identity, never in the workflow |
| **Workbooks** | Hunt & Investigate and SOC Overview dashboards, built against genuine lab telemetry rather than vendor sample data |
| **Infrastructure** | Bicep IaC — workspace, Sentinel onboarding, and Data Collection Rules, deployable in one command |

The containment playbook *recommends* rather than acts — disabling an account outright needs a
tenant-wide `User.ReadWrite.All` grant on an unattended identity, and one false-positive High
incident would lock out a real user with no human in the loop. That tradeoff is documented in
the repo rather than glossed over.

**Currently deepening:** SOAR/Logic Apps automation · data connector configuration · Bicep/ARM · working toward **SC-300**

<br/>

## 🎯 Focus Areas

What the day job actually consists of:

| | Area | In practice |
|:---:|:---|:---|
| 🔎 | **Incident Investigation** | Own confirmed compromises end to end — BEC, lateral movement, honeytoken triggers — from first alert to closure, not just triage |
| 📝 | **Detection Engineering** | Author KQL analytics and NRT rules with full entity mapping, hand-written rather than AI-generated |
| 🎯 | **Threat Hunting** | Run 58+ MITRE ATT&CK-mapped hunt packages proactively, ahead of an alert firing |
| 📊 | **SIEM Workbooks** | Build multi-tenant dashboards analysts actually work from during an investigation, not demo screenshots |
| 🛰️ | **Threat Intelligence** | Operate IOC ingestion and deduplication pipelines across multiple live feeds |
| 🔐 | **SOAR Automation** | Ship Logic Apps playbooks authenticated by managed identity, with zero stored credentials |

<br/>

## 🧰 Toolset

<div align="center">

![Azure](https://skillicons.dev/icons?i=azure,git,github,linux,bash,py&theme=dark)

</div>

<br/>

## 📜 Certifications

<div align="center">

[![AZ-500](https://img.shields.io/badge/AZ--500-Azure%20Security%20Engineer-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](#)
[![SC-200](https://img.shields.io/badge/SC--200-Security%20Ops%20Analyst-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](#)
[![Google SecOps](https://img.shields.io/badge/Google%20SecOps-Chronicle-0078D4?style=flat-square&logo=google&logoColor=white)](#)
[![LRSA](https://img.shields.io/badge/LRSA-Certified-0078D4?style=flat-square)](#)
[![LRPA](https://img.shields.io/badge/LRPA-Certified-0078D4?style=flat-square)](#)
[![SC-300](https://img.shields.io/badge/SC--300-In%20Progress-24292e?style=flat-square&logo=microsoftazure&logoColor=white)](#)

</div>

<br/>

## 📊 Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=TaruntejaDesireddy&theme=dark&hide_border=true&ring=0078D4&fire=0078D4&currStreakLabel=0078D4">
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=TaruntejaDesireddy&theme=default&hide_border=true&ring=0078D4&fire=0078D4&currStreakLabel=0078D4">
  <img src="https://streak-stats.demolab.com/?user=TaruntejaDesireddy&theme=default&hide_border=true&ring=0078D4&fire=0078D4&currStreakLabel=0078D4" alt="GitHub streak"/>
</picture>

</div>

---

<div align="center">

### Let's talk

Open to conversations about SOC engineering, detection content, or Azure security roles.

[![Email](https://img.shields.io/badge/-tarunteja.desireddy9%40gmail.com-0078D4?style=flat-square&logo=gmail&logoColor=white)](mailto:tarunteja.desireddy9@gmail.com)

<sub>Everything linked here is real, deployed, and tested — not a template.</sub>

</div>
