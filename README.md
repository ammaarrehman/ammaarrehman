<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:0d1117&height=130&section=header&text=&animation=fadeIn" width="100%"/>

<img src="assets/higuruma.gif" width="420" alt="Anime profile GIF"/>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=30&duration=2800&pause=1200&color=58A6FF&center=true&vCenter=true&width=900&lines=Ammaar+Rehman;Information+Systems+Student;Cloud+%26+AI+Ops+Intern;Homelab+Builder;AWS+Certified+Cloud+Practitioner" alt="Typing SVG" />

<br/>

<p>
  <img src="https://img.shields.io/badge/Focus-Cloud%20%7C%20Cybersecurity%20%7C%20AI-1f6feb?style=flat-square"/>
  &nbsp;
  <img src="https://img.shields.io/badge/AWS-Certified%20Cloud%20Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Homelab-Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/>
</p>

<p>
  <a href="https://ammaarrehman.com">
    <img src="https://img.shields.io/badge/Portfolio-ammaarrehman.com-58A6FF?style=for-the-badge&logo=googlechrome&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/ammaarrehman">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://github.com/ammaarrehman">
    <img src="https://img.shields.io/badge/GitHub-ammaarrehman-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=ammaarrehman&color=1f6feb&style=flat-square&label=Profile+Views"/>
&nbsp;
<img src="https://img.shields.io/github/followers/ammaarrehman?style=flat-square&color=58A6FF&label=Followers"/>
&nbsp;
<img src="https://img.shields.io/github/stars/ammaarrehman?style=flat-square&color=58A6FF&label=Stars"/>

</div>

<br/>

---

## About

I’m an **Information Systems student** focused on cloud infrastructure, cybersecurity, AI tools, and practical systems engineering.

I use GitHub to document the projects I build while learning: cloud labs, homelab infrastructure, AI workflow tools, cybersecurity projects, and portfolio websites. My goal is to build useful systems, explain them clearly, and make them safe to hand off to real users.

**Current direction:** Cloud engineering · Cybersecurity · AI operations · Public-sector technology

---

## Current Focus

```yaml
Learning:
  - Cloud infrastructure
  - Linux systems administration
  - Networking and cybersecurity fundamentals
  - Monitoring and observability
  - AI workflow design

Building:
  - Raspberry Pi homelab infrastructure
  - Claude-powered workflow tools
  - AWS projects with Terraform
  - Portfolio and documentation projects

Career Interests:
  - Cloud Engineering
  - Cybersecurity
  - AI Operations
  - Federal and public-sector technology

## Tech Stack

### Cloud, Infrastructure & DevOps

<p>
  <img src="https://skillicons.dev/icons?i=aws,terraform,linux,docker,github,git&theme=dark"/>
</p>

### Programming & Automation

<p>
  <img src="https://skillicons.dev/icons?i=python,javascript,html,css,bash&theme=dark"/>
</p>

### Monitoring, Networking & Homelab

<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailscale-242424?style=for-the-badge&logo=tailscale&logoColor=white"/>
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white"/>
</p>

### AI & Productivity Tools

<p>
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white"/>
</p>

---

## Featured Projects

<details open>
<summary><b>Claude Intake Triage Assistant</b></summary>

<br/>

> A Claude-powered workflow that turns free-text community help requests into structured, reviewable records.

| Attribute | Detail |
|---|---|
| **Stack** | Claude API · Google Forms · Google Apps Script · Google Sheets · Python |
| **Purpose** | Help staff review and organize community intake requests |
| **Outputs** | Primary need · Secondary needs · Urgency · Summary · Next step · Follow-up questions · Human-review flag |
| **Evaluation** | Python eval harness with 15 test cases |
| **Result** | Multi-need coverage improved from 0% to 90%; 100% scoped classification accuracy |
| **Repository** | [github.com/ammaarrehman/claude-intake-triage](https://github.com/ammaarrehman/claude-intake-triage) |

**What it shows:** AI workflow design, prompt iteration, evaluation, documentation, safety notes, and human-in-the-loop handoff.

</details>

<details>
<summary><b>Raspberry Pi Homelab</b></summary>

<br/>

> A two-node Raspberry Pi homelab for DNS filtering, monitoring, dashboards, and secure remote access.

| Attribute | Detail |
|---|---|
| **Stack** | Raspberry Pi · Linux · Docker · AdGuard Home · Unbound · Tailscale · Uptime Kuma · Prometheus · Grafana |
| **Primary Node** | Raspberry Pi 5 8GB infrastructure node |
| **Secondary Node** | Raspberry Pi 5 2GB kiosk and backup services node |
| **Networking** | Local DNS filtering, recursive DNS, per-device DNS, Tailscale remote access |
| **Monitoring** | Uptime Kuma, Prometheus, Grafana, node-exporter, cAdvisor |

**What it shows:** Linux administration, networking constraints, monitoring, documentation, and practical infrastructure operations.

</details>

<details>
<summary><b>AWS Static Site with Terraform</b></summary>

<br/>

> Infrastructure-as-code project for deploying a private S3 static website behind CloudFront.

| Attribute | Detail |
|---|---|
| **Stack** | AWS S3 · CloudFront · Origin Access Control · Terraform · ACM · AWS Budgets |
| **Architecture** | Private S3 origin served through CloudFront |
| **Security** | Origin Access Control instead of public bucket access |
| **Cost Awareness** | Free-tier-friendly design with budget monitoring |
| **Focus** | Repeatable deployment, documentation, and cloud fundamentals |

**What it shows:** AWS fundamentals, Terraform, cloud architecture, and cost-conscious infrastructure design.

</details>

<details>
<summary><b>Portfolio Website</b></summary>

<br/>

> Personal portfolio site for showcasing projects, experience, and technical growth.

| Attribute | Detail |
|---|---|
| **Stack** | HTML · CSS · JavaScript · GitHub Pages |
| **Website** | [ammaarrehman.com](https://ammaarrehman.com) |
| **Purpose** | Central hub for projects, experience, and documentation |

</details>

---

## Experience

### Cloud & AI Ops Intern — NextGen Cyber Initiative

Supporting cloud and AI workflows using AWS services, Claude, VS Code, backend troubleshooting, testing, and documentation. My work focuses on translating technical issues into clear steps, supporting internal systems, and improving operational workflows.

`AWS` `Claude` `VS Code` `Documentation` `Testing` `Troubleshooting`

<br/>

### IT Ops Intern — NextGen Cyber Initiative

Supported IT operations, account configuration, mobile app testing, user troubleshooting, and internal documentation.

`IT Operations` `User Support` `Testing` `Documentation`

---

## Certifications & Learning

<div align="center">

![AWS Certified Cloud Practitioner](https://img.shields.io/badge/AWS-Certified%20Cloud%20Practitioner-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
&nbsp;
![Claude API](https://img.shields.io/badge/Claude-Building%20with%20the%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
&nbsp;
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-Learning-58A6FF?style=for-the-badge)

</div>

<br/>

- AWS Certified Cloud Practitioner
- Claude 101
- Claude Code 101
- Claude Platform 101
- Building with the Claude API
- Introduction to Model Context Protocol
- AI Fluency: Framework & Foundations

---

## GitHub Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ammaarrehman&theme=github-dark&hide_border=true&area=true" width="100%" alt="GitHub activity graph"/>

</div>

---

## What I’m Building Toward

I’m working toward cloud, cybersecurity, and AI operations roles where I can build practical systems, document them clearly, and support real users.

My goal is to keep improving through hands-on projects, strong documentation, and honest iteration.

---

<div align="center">

*Building practical systems. Documenting the process. Improving one project at a time.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:0d1117&height=110&section=footer" width="100%"/>

</div>