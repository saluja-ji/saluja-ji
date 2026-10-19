<h1 align="center">Pushpit Saluja</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2F81F7&center=true&vCenter=true&width=560&lines=DevOps+%26+Cloud+Engineer;I+automate+infrastructure+with+Terraform;I+ship+it+with+CI%2FCD;I+make+it+observable+with+OpenTelemetry" alt="Typing intro" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/pushpit-saluja">LinkedIn</a> ·
  <a href="mailto:salujapushpit3@gmail.com">Email</a> ·
  <a href="https://cloudodyssey.substack.com">Blog</a>
</p>

```console
pushpit@prayagraj:~$ whoami
devops-engineer · AWS · Terraform · Go

pushpit@prayagraj:~$ cat focus.txt
infrastructure as code, CI/CD pipelines, observability, least-privilege security

pushpit@prayagraj:~$ cat philosophy.txt
if it isn't automated, it's a bug waiting to happen
if it isn't observable, it's already broken
```

## What I build

```mermaid
flowchart LR
  S[EventBridge<br/>daily schedule] --> L[Lambda · Go]
  L --> B[(S3 data lake)]
  B --> Q[Athena]
  L -->|risky permissions<br/>+ daily diff| N[SNS alert]
  L -. OTLP .-> O[OpenTelemetry<br/>X-Ray · CloudWatch]
  G[GitHub Actions<br/>OIDC · Terraform] -->|plan · apply| L
```

<sub>Architecture of <a href="https://github.com/saluja-ji/iam_inventory_pipeline">iam_inventory_pipeline</a>.</sub>

## Projects

| Project | What it does | Stack |
|---|---|---|
| [**iam_inventory_pipeline**](https://github.com/saluja-ji/iam_inventory_pipeline) | Daily AWS IAM snapshots, risk detection, and change alerts. Deployed through Terraform and GitHub Actions with OIDC (no static keys). | `Go` `Terraform` `Lambda` `Athena` `OpenTelemetry` |
| **OpenTelemetry Collector pipeline** | Traces, metrics, and logs from a Go service over OTLP into a Collector. | `Go` `OpenTelemetry` `Docker` |
| [**wikigo**](https://github.com/saluja-ji/wikigo) | Published Go SDK for the Wikimedia API with rate limiting, backoff, and retries. [pkg.go.dev](https://pkg.go.dev/github.com/saluja-ji/wikigo) | `Go` `net/http` |

## Toolbox

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat&logo=opentelemetry&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

## Writing

I write about cloud and systems internals at **[Cloud Odyssey](https://cloudodyssey.substack.com)**.

