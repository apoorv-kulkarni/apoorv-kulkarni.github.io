# LinkedIn rewrite (paste-ready)

Apply in this order. Each step is independent; headline and top skills take two minutes and change what recruiters see first.

Do not paste bracketed placeholders. Fill them or drop the bullet.

Numbers not in your LinkedIn PDF were left out on purpose (cell count, cluster count, regions, time-to-serve, MTTR, PoP count, incident volume). Add any you can say publicly.

---

## 1. Headline

**Use this (128 characters):**

```
Senior Software Engineer, Reliability @ Roblox | Compute & Cluster Infrastructure | Kubernetes, Bare Metal, Distributed Systems
```

Keeps your real title. Puts the search terms in the field LinkedIn weights most.

**Longer option if you want more keywords (under 220):**

```
Compute & Cluster Infrastructure at hyperscale | Senior Software Engineer, Reliability @ Roblox | Bare-metal fleet lifecycle, Kubernetes, Nomad, Go, Terraform
```

Do not change the job title to “Senior Infrastructure Engineer.” That is not the title on the PDF.

---

## 2. Top three skills (pin these)

1. Kubernetes
2. Distributed Systems
3. Go

Then roughly this order for the rest:

Kubernetes, Distributed Systems, Go, Site Reliability Engineering, Infrastructure as Code, Terraform, Linux, Python, Nomad, Consul, Vault, Bare Metal, Incident Response, Prometheus, Grafana, Chef

Keep Chef. Do not pin it. Unpin Prometheus and Grafana from the top three.

---

## 3. About

Paste as separate paragraphs. If the live profile is a wall of text, that is a real bug, not just a PDF artifact.

```
I build the systems that turn raw machines into usable compute.

At Roblox I work on cluster and cell lifecycle: how capacity is provisioned, brought into service, drained, repaired, and retired across a global bare-metal fleet. The platform serves 140M+ daily active users, so a stuck provisioning step or a bad drain is a user-visible outage, not a ticket.

I write Go and Python that talks to real hardware in real datacenters, with Kubernetes and Nomad for orchestration, Consul and Vault for discovery and secrets, and Terraform for declarative state.

Before Roblox: five and a half years at IBM on API Connect — production SRE across 30+ cloud environments worldwide, plus the internal tooling that kept them stable.

I care about the parts that are hard to see. What happens when a node dies mid-drain. Why a config that is correct on disk is not the one the running process loaded. How you tell a cluster reporting healthy from a cluster actually serving traffic.

Interested in compute and cluster infrastructure roles where the scale of the fleet is the hard problem.
```

Removed: “DevOps,” the desktop/SaaS generalist line, the query-latency number (strong, but it pulls toward app backend), and “the guy teammates call when systems are failing” (Senior firefighter, not Staff systems).

Optional last paragraph if you want Featured/Projects to mention Vigiles and it is public:

```
I also ship Go on the side, including Vigiles, a zero-dependency supply chain scanner.
```

---

## 4. Roblox — split into two positions

LinkedIn allows multiple titles under one company. One title for 6 years 1 month erases the SRE → SWE Reliability move and the Cell Lifecycle pod.

Spell the current title out: **Senior Software Engineer, Reliability** (not “Sr”).

### Position 1 — current

**Title:** Senior Software Engineer, Reliability  
**Dates:** [month you moved into this title] – Present  
**Location:** San Francisco Bay Area

```
Founding engineer on the pod that owns compute-cell lifecycle: provision, validate, drain, repair, and decommission. Defined the teardown path when none existed, then reused it.

- Automated cell bringup. Cut Terraform init in a production workspace from minutes to about a second.
- Production cells at new sites, including a Kubernetes-only site.
- Control plane: Kubernetes, Nomad, Consul, Vault, Terraform.
- Stack: Go, Python, Linux, Kubernetes, Nomad, Consul, Vault, Terraform.
```

### Position 2 — prior title at Roblox

**Title:** Senior Site Reliability Engineer  
**Dates:** September 2020 – [month before the title above]

```
Global edge and point-of-presence infrastructure for a platform serving 140M+ daily active users.

- Took bare-metal points of presence from hardware handoff through automated config convergence and health validation.
- Built and operated edge-cell and PoP deployment workflows spanning infrastructure, networking, orchestration, and production readiness.
- Converted production incident root causes into automation rather than longer runbooks.
```

If you can name one multi-quarter, multi-team initiative, it belongs as the first bullet on one of these two roles. That is the Staff/Principal gap. Headline changes will not cover it.

---

## 5. IBM

**Title:** Software Engineer  
**Dates:** January 2015 – June 2020  
**Location:** San Francisco Bay Area

```
Internal tooling and production SRE for IBM API Connect.

- Built automation and monitoring used by distributed engineering and operations teams.
- Supported deployment and reliability of 30+ production cloud environments worldwide.
- Diagnosed and remediated production reliability and performance issues on API Connect so environments stayed available.
```

Delete: “the whole nine yards,” “Sometimes I have fun building slack integration,” “all hands on deck,” “fixing production issues on the fly.”

---

## 6. Techlore

Keep the role. The stack is old; the customer work is not. Cut the fifteen-bullet dump and “Think; Think again; Debate; Negotiate.” Lead with sitting in the room with customers.

**Title:** Software Developer  
**Dates:** August 2011 – July 2013  
**Location:** Pune Area, India

```
Small product shop. I wore a lot of hats, including sitting with customers face to face.

- Worked directly with customers on requirements, delivery, and training — including going on-site / offshore to deploy and train the people using the product.
- Translated what customers actually needed into software, and owned the conversation between the client and the rest of the team.
- Led a team of four and took three projects through to ship.
- Cut a business-critical process from 30 minutes to under a minute.
```

---

## 7. Cengage Learning

Delete the role, or leave a single line. A 2014 AngularJS internship dates you and does not help compute-infra search.

If you keep it:

```
Software engineering intern. Replaced a slow Google Docs workflow with an internal collaboration tool.
```

Do not list AngularJS, Socket.IO, or MongoDB.

---

## 8. Education

Leave as-is:

- M.S. Computer Engineering, Syracuse University (2013–2014)
- B.Eng. Computer Engineering, Savitribai Phule Pune University (2008–2011)

---

## Why this order

Your About already said compute, edge, 140M+ DAU, cells, and PoPs. The PDF’s Experience and pinned skills did not. Recruiters search headline + skills + job text. “Scaling Infra @ Roblox” plus Chef/Prometheus/Grafana plus one generic Roblox sentence is why you read as a 2018 SRE generalist instead of someone who runs physical fleets at Roblox scale.
