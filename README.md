<!-- Header wave -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7f04a2,100:3b0764&height=190&section=header&text=Jer%C3%B3nimo%20Herdo%C3%ADza&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=DevOps%20%C2%B7%20Cloud%20%C2%B7%20Infrastructure%20%C2%B7%20Networks&descAlignY=58&descSize=18" alt="header" />
</p>

<!-- Typing animation -->
<p align="center">
  <a href="https://github.com/J33r0">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=900&color=A855F7&center=true&vCenter=true&width=640&lines=Master+2+SIRIS+%40+University+of+Strasbourg;I+break+my+own+clusters+on+purpose+%F0%9F%94%A5;Kubernetes+%C2%B7+Docker+%C2%B7+Ansible+%C2%B7+Terraform;Looking+for+a+6-month+internship+from+Feb+2027" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jer%C3%B3nimo-herdo%C3%ADza-fustillos-581b09259/"><img src="https://img.shields.io/badge/LinkedIn-Connect-7f04a2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:jeronimoherdoiza03@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-7f04a2?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to-Internship%20Feb%202027-22c55e?style=for-the-badge" alt="Open to internship"/>
  <img src="https://img.shields.io/badge/Based%20in-Strasbourg%2C%20FR-3b0764?style=for-the-badge" alt="Strasbourg"/>
</p>

---

```console
$ kubectl describe engineer jeronimo
Name:          Jerónimo Herdoíza Fustillos
Namespace:     university-of-strasbourg/cmi-isr
Status:        Running ✅  (Master 2 SIRIS - Networks, Internet & Systems)
Focus:         DevOps · Cloud · SRE · Networks · Security
Languages:     🇫🇷 French · 🇬🇧 English · 🇪🇨 Spanish (native)
Looking-for:   6-month end-of-studies internship, from February 2027
Mobility:      anywhere in France 🚄
Events:
  Normal  Learning      Always            curiosity-controller   Breaking things to understand them
  Normal  Coaching      Weekly            volleyball-team        Coach of my faculty's team 🏐
  Normal  Volunteering  Whenever I can    GirlsCanCode!          Helping participants with their code 👩‍💻
```

## 🛠️ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=kubernetes,docker,ansible,terraform,githubactions,gitlab,prometheus,grafana&perline=8" alt="DevOps tools" />
  <br/>
  <img src="https://skillicons.dev/icons?i=linux,ubuntu,bash,python,git,github,aws,postgres,c,cpp&perline=10" alt="Systems and languages" />
</p>

| ☁️ Cloud & Containers                                                         | 🔁 CI/CD & IaC                                                        | 🌐 Networks & Observability                                                 |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| Kubernetes (k3s), Docker, Docker Compose, OpenStack, AWS S3, RabbitMQ, Celery | GitHub Actions, GitLab CI/CD, GHCR, Ansible, Ansible Vault, Terraform | TCP/IP, BGP, OSPF, IS-IS, 5G, Traefik, keepalived/VRRP, Prometheus, Grafana |

---

## 🚀 Featured work

### 🧱 [Highly available Kubernetes cluster (k3s)](https://github.com/J33r0/projet-cloud-virt) - _built from scratch_

Three VMs, one distributed app, provisioned and deployed automatically. Provisioned with **Ansible**, secrets encrypted with **Ansible Vault** and served as **Kubernetes Secrets**, exposed through **keepalived/VRRP** and **Traefik**, shipped by a **GitHub Actions → GHCR** pipeline.

<p align="center">
  <img src="assets/k3s-architecture.svg" alt="k3s architecture: GitHub Actions to GHCR to a 3-node k3s cluster with keepalived VIP, Traefik, RabbitMQ, Celery and S3" width="100%"/>
</p>

<details>
<summary><b>The part I enjoyed most: killing the primary node on purpose</b> (click me)</summary>
<br/>

<p align="center">
  <img src="assets/failover.svg" alt="Animated failover: Node 1 is stopped and the virtual IP moves to Node 2 without downtime" width="90%"/>
</p>

Before the cluster, everything ran locally first: **Docker Compose**, then **k3s on my laptop**, then the real thing.

</details>

### 📡 IoT, Cloud & Observability platform - _Master's project (ongoing)_

I own the **SRE, Cloud and infrastructure** layer: **OpenStack** provisioned with **Terraform** (VMs, public/private networks, security groups), physical and cloud clusters linked through a **WireGuard** tunnel, services on **Kubernetes**, a **GitLab CI/CD** pipeline (IaC, build, tests, deploy) and **Prometheus + Grafana** for observability.

### 📄 [Resume-automation](https://github.com/J33r0/Resume-automation) - _CV-as-code_

My CV is a repo. On every push, **GitHub Actions** detects changes to the French and English versions, recompiles the PDFs with **headless Chrome** and publishes them. Yes, even my resume has a pipeline. 🤖

---

## 🧪 Experience

<details>
<summary><b>🔬 CNRS × University of Strasbourg - Research intern, 5G / Orchestration</b> · May–Jul 2026</summary>

- Dockerized a **5G traffic generator** and automated its deployment on the **POWDER** testbed.
- Wrote a **Bash** runner driven by **YAML** configs (IP resolution, log collection) with a **Python** orchestration backend and web UI.
- Automated remote pipeline execution and metric collection: no more manual steps in the workflow.
</details>

<details>
<summary><b>🌐 CNRS × University of Strasbourg - Research intern, Networking (BGP)</b> · Jun–Jul 2025</summary>

- Automated **BGP** configuration with an **Ansible** playbook.
- Built an interactive debugging tool (**Python + D3.js**) to diagnose routing anomalies faster.
</details>

<details>
<summary><b>⚡ TER - Speeding up LLMs on mobile</b> · Feb–May 2026</summary>

- Up to **+30%** performance vs OpenMP running language models (Qwen, Llama) on a tablet, with a thread scheduler written in **C**.
</details>

## 🏆 Achievements

- 🥇 **1st prize, Capture The Flag (UDLA, Quito)** · Feb 2021: captain of a 3-person team, exploiting system and web vulnerabilities.

---

## 📊 GitHub activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=J33r0&background=0D0117&border=7F04A2&ring=A855F7&fire=A855F7&currStreakLabel=A855F7&sideLabels=E9D5FF&dates=C4B5FD&currStreakNum=F3E8FF&sideNums=F3E8FF&stroke=3B0764&hide_border=true" alt="GitHub streak" />
</p>

## 🧗 When I'm not in a terminal

`🧗 climbing` · `🏐 volleyball coaching` · `🏋️ weightlifting` · `🥾 hiking` · `🧵 sewing` · `🎸 self-taught guitar`

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3b0764,100:7f04a2&height=110&section=footer" alt="footer" />
</p>
