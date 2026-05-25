<div align="center">

```
 █████╗ ██████╗ ██╗████████╗██╗  ██╗██╗   ██╗ █████╗     ██████╗  █████╗  ██████╗ 
██╔══██╗██╔══██╗██║╚══██╔══╝██║  ██║╚██╗ ██╔╝██╔══██╗    ██╔══██╗██╔══██╗██╔═══██╗
███████║██║  ██║██║   ██║   ███████║ ╚████╔╝ ███████║    ██████╔╝███████║██║   ██║
██╔══██║██║  ██║██║   ██║   ██╔══██║  ╚██╔╝  ██╔══██║    ██╔══██╗██╔══██║██║   ██║
██║  ██║██████╔╝██║   ██║   ██║  ██║   ██║   ██║  ██║    ██║  ██║██║  ██║╚██████╔╝
╚═╝  ╚═╝╚═════╝ ╚═╝   ╚═╝   ╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝    ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ 
```

### `Site Reliability Engineer · Cloud & DevOps`

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&pause=1200&color=00FF41&background=00000000&center=true&vCenter=true&width=650&lines=Keeping+systems+up+at+3AM+so+you+don%27t+have+to.;if+%28alert%29+%7B+triage%28%29%3B+rca%28%29%3B+fix%28%29%3B+%7D;99.9%25+uptime+is+not+a+goal%2C+it%27s+a+baseline.;Turning+alerts+into+RCAs+since+2024.;Automate+the+toil.+Document+the+context.+Own+the+uptime.;kubectl+get+incidents+--field-selector+status%3Dresolved;Infrastructure+as+Code.+Failure+as+Signal.;On-call+is+not+a+rotation.+It%27s+ownership.;Ship+fast.+Observe+everything.+Break+nothing.)](https://git.io/typing-svg)

</div>

---

## `$ cat /etc/adithya/profile.conf`

```ini
[identity]
name         = Adithya Rao
role         = Site Reliability Engineer (Tier 1.5)
employer     = HCLTech  →  Verizon (client)
location     = India

[scope]
domain       = SD-WAN Enterprise Network Operations, Cloud Infra, SRE, DevOps
clients      = Verizon, American Express, Walmart, PepsiCo, Coca-Cola
coverage     = 24x7 NOC | Multi-geo | Fortune 500

[targets]
uptime_sla   = 99.9%+
mttr_delta   = -20%
repeat_inc   = -25%
vendor_tat   = -15%
```

---

## `$ systemctl status current-role --full`

```
● hcltech-nre.service — Site Reliability Engineer, Tier 1.5
     Loaded: active (running) since Aug 2025
     Client: Verizon (primary) + Fortune 500 enterprise accounts
     Status: "Monitoring SD-WAN, MPLS & DC infra across multiple geographies"

● Scope:
     → SD-WAN tunnel management: Cisco Viptela · Versa · VMware VeloCloud · HPE Aruba SilverPeak
     → ISP incidents: BGP instability · link flapping · last-mile packet loss
     → Firewall ops: Palo Alto PAN-OS · IPSec VPN · NAT policy
     → Full incident lifecycle: Detection → Triage → Escalation → RCA → Closure
```

---

## `$ lsblk --topology --all`

```
NETWORK & SD-WAN                        CLOUD PLATFORMS
├── TCP/IP · BGP · OSPF · MPLS          ├── GCP  (Compute, Monitoring, Logging, IAM)
├── SD-WAN (Viptela / Versa /           ├── AWS  (EC2, CloudWatch, VPC, IAM)
│         VeloCloud / SilverPeak)       └── Azure (VNet, NSG, AKS, Key Vault)
├── VPN  (IPSec / SSL)
├── DNS · HTTP/S · TLS                  CONTAINERS & INFRA-AS-CODE
└── Palo Alto PAN-OS                    ├── Docker · Kubernetes
                                        ├── Terraform · Ansible
OBSERVABILITY                           └── Nginx
├── ETMS · BGW · EZstatus · Canvas
├── GCP Cloud Monitoring                CI / CD PIPELINES
├── AWS CloudWatch                      ├── GitHub Actions
├── SIEM · Wireshark · Suricata         ├── GitLab CI/CD
└── Log Analysis · Alerting             └── Argo CD  (GitOps)

SCRIPTING & AUTOMATION
├── Python  — alert parsing, log correlation, toil reduction
└── Bash    — interface polling, incident automation, runbook scripting
```

---

## `$ cat ~/.certifications`

```
[✓] AZ-104   Microsoft Certified: Azure Administrator Associate
[✓] AZ-305   Microsoft Certified: Azure Solutions Architect Expert
[✓] SD-WAN   Viptela · Versa Networks · VeloCloud · SilverPeak · Meraki
[✓] CCNA     Routing, Switching & Network Fundamentals (Cisco)
```

---

## `$ git log --oneline --all-projects`

```
a3f1c2e  feat: Netflix Clone — containerised + Kubernetes-deployed on GCP
         └── Docker multi-stage build (builder → Nginx/Alpine) · non-root runtime
             2-replica K8s Deployment + NodePort Service · self-healing · rolling updates
             Secure ENV injection via Docker ARG/ENV · 12-factor config practices

b7d09f1  feat: Cloud Monitoring & Alerting Lab — GCP
         └── Uptime checks & dashboards on Compute Engine instances
             CPU / memory / disk alerting policies · email + webhook channels
             Log-based incident investigation via Cloud Logging
```

---

## `$ grep -r "impact" /var/log/adithya/metrics.log`

```log
[METRIC]  MTTR reduced by 20%          via Python/Bash alert automation
[METRIC]  Repeat incidents down 25%    via structured RCA documentation  
[METRIC]  Vendor TAT cut by 15%        via streamlined escalation workflows
[UPTIME]  99.9%+ maintained            across multi-geo SD-WAN environments
[SCALE]   Fortune 500 clients          Verizon · AmEx · Walmart · PepsiCo · Coca-Cola
```

---
---

## `$ ping -c 4 adithya`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=00FF41)](https://linkedin.com/in/iamadithya)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=00FF41)](https://github.com/iam-Adithya)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=00FF41)](https://medium.com/@adicse005)
[![Email](https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=00FF41)](mailto:adicse005@gmail.com)

</div>

```
PING adithya.rao — 4 packets transmitted, 4 received, 0% packet loss
```

---

## `$ tail -f /var/log/philosophy.log`

```
> "An alert firing is a conversation starter — RCA is how you end it for good."
> "On-call isn't just a rotation. It's ownership."
> "Automate the toil. Document the context. Own the uptime."
```

---

<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║   systems nominal · incidents resolved · uptime: ↑      ║
╚══════════════════════════════════════════════════════════╝
```

*Last commit: the incident that didn't page anyone.*

![Visitor Count](https://komarev.com/ghpvc/?username=iam-Adithya&color=00ff41&style=flat-square&label=profile+views)

</div>
