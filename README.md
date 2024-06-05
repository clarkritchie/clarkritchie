# ❇️ Clark Ritchie

A platform engineer with a diverse background of experiences.  Hands-on building and operating scalable SaaS cloud-native systems for over 15 years as both an IC and leader.

Connect with me on [LinkedIn](https://www.linkedin.com/in/clarkritchie) or [GitHub](https://www.github.com/clarkritchie).

## 💬 TL;DR

- Core skills:  Linux, Terraform, Docker and containers (Swarm/ECS/K8s), Go (Golang), Python, CI/CD, cloud (AWS/GCP)
- Developer, but also close to infrastructure
- Possess an SRE mindset -- scalability, fault-tolerance, consolidating resources, monitoring and alerting
- Passionate about building and running world-class systems

## 📌 Career TL;DR

- BS in Computer Science, Univ. of Puget Sound ('96)
- Early career — Intel factory automation, Hewlett-Packard, a startup (’96-’11)
- MS in Computer Science, Oregon State Univ. ('01)
- 12 years writing software for fixed wireless networks in US low-income and throughout East Africa, Haiti, The Philippines
- Co-founder of an [ISP in Kenya](https://pitchbook.com/profiles/company/113840-47) (’13-’18)
- 5 Years as Platform Engineer at Specialized Bicycle Components (’18-’23)
- Principal Engineer at Blueboard, a SaaS startup (’23-’24)
- Experience at 4 startups

## 💪🏼 Kubernetes and GCP

I have been using containers in production for approximately 7 years.  Most of that experience has been with AWS's Elastic Container Service product, which I selected primarily for ease of support and a faster time to production.  I have also built and run my own Docker Swarm clusters, both on bare metal servers and on EC2s in an AWS environment that was 100% Terraformed (by me).

I have used K8s on side/personal projects, some of which is published here.  There are far more similarities between K8s and ECS/Swarm than not.  Task defitinitons are basically Services + Deployments, the concept of Volumes is universal, as are concepts like Ingress, routes, virtual networks, and so on.

I have over 14 years of experience on AWS and extensive experience with IaC using Terraform.  And while I have only ever used GCP for side/personal projects, I am 1,001% confident in my ability to rapidly take up GCP in an Enterprise setting.

At the end of the day, for both K8s and GCP, the vast majority of the concepts are the same. There can be a hundred ways to solve the same problem using these tools, and how you do it is often bespoke to the organization and their established patterns.

If you can drive a Lexus, you can also drive a Toyota.

## 👽 Random Things on my GitHub

This is all **very** elementary stuff, sometimes I use these just to prove out a basic concept or maybe to provide myself a template for future use.

- [Basic Go Things](https://github.com/clarkritchie/basic-go-things)
  - [gRPC](https://github.com/clarkritchie/basic-go-things/tree/main/grpc) -- Hello World server in Go, clients in Go and Python
- [Python + Go Things](https://github.com/clarkritchie/python-go-things)
- [Kubernetes Things](https://github.com/clarkritchie/k8s-things) -- Hello world stuff (yes, I'm finally learning K8s after >6 years with AWS Elastic Container Service and Docker Swarm...)
- Simple [example](https://github.com/clarkritchie/pizza-store-app) of how you might use Docker Compose to run a small Fast API server that can reach a Maria DB database

### 🗒️ Gists -- Code Snippets, Scripts, Other Notes

- Shell script to [delete old branches](https://gist.github.com/clarkritchie/6be7d3d8fec96901002b01df2eaafb6e)
- [Use Python in a GHA step](https://gist.github.com/clarkritchie/a347d3fe9c72f47d9ece95f4dda38536)
- [Manage Cloudflare records](https://gist.github.com/clarkritchie/f518f5f7a8fb889f9fa9f87e7574cbe4)
- Cloudflare [maintenance page worker](https://gist.github.com/clarkritchie/31aa63566ac388332cb2a6275a40396d)
- [Other random notes and code snippets](https://gist.github.com/clarkritchie)
- Shell script to [tag a container with a semvar+sha](https://gist.github.com/clarkritchie/600297e23a05a629664bfbff20d03b51)
- [List, Copy, Delete S3 Bucket](https://gist.github.com/clarkritchie/fdce6b1a365ce176040bc8e7fca3a0c7)
- A few things that I made to make copying a Postgres db from [Heroku to RDS](https://github.com/clarkritchie/heroku-to-rds) a little easier

### 🤖 GitHub Action Related

- Trick GHA into [revealing a secret](https://gist.github.com/clarkritchie/def05211e6dd0ec6a8e1edd48f0f822b)
- Example of how you might [lint in a GHA](https://gist.github.com/clarkritchie/2f935597b9398a34380e8c9a90005b6f) -- this example is for Terraform, but could be used to lint Python code with Ruff, etc.
- Full example of the [context object](https://gist.github.com/clarkritchie/b84937c0c83bcf1de9f25ca63bcaf77a)
- If you must do a [nested ternary](https://gist.github.com/clarkritchie/d3c35a9feeec5ed62ddbb38172ee62c2)

### 🔒️ 1Password Related

- Sort a [1Password Note](https://gist.github.com/clarkritchie/1e223f3cd3657cd00722be52f4249c1a) from the command line, uses the 1Password CLI
- I made this Python script to [read Secure Notes from 1Password and push to GitHub Secrets](https://github.com/clarkritchie/1pw-github-secrets) -- this is very bespoke but is how I once used 1Password Notes as the "source of truth" for env vars which were stored as GitHub secrets (environment, repository or organization) -- this code was originally forked from someone else's project but heavily modified for my needs
- Do the above [but in a GHA](https://gist.github.com/clarkritchie/843c54c66af0833d05a88ab6fd84a544) -- this is the way

### ⚙️ Terraform Related

_TODO:  Revisit and revise these projects before linking to them._

- `app-api-uploads `-- File uploads
- `app-frontends` -- Hosting for React apps on S3 with CloudFront, etc.
- `aws-alarm-infrastructure` -- CloudWatch alarms and monitoring
- `aws-docker-swarm` -- VPC, subnets, EC2s, user data, etc.
- `aws-elasticache-redis` -- Redis
- `aws-guardduty` -- Sets up Guard Duty in 4 regions
- `aws-iam-accounts` -- Used to manage IAM jusers
- `aws-postgres-rds` -- RDS Serverless v2
- `backend-remote-state`-- Terraform for the Terraform
- `github-manager` -- How I managed GitHub... this one needs a lot of refactoring
