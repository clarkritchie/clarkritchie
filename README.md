# ❇️ Clark Ritchie

A platform engineer with a diverse background of experiences.  Hands-on building and operating scalable SaaS cloud-native systems for over 15 years as both an IC and leader.

Connect with me on:
- [LinkedIn](https://www.linkedin.com/in/clarkritchie)
- [GitHub](https://www.github.com/clarkritchie)
- Use [Calendly](https://calendly.com/clarkritchie) to get on my calendar

I am passionate about building and operating world-class applications that delight its end users.

I am `#opentowork` -- I am hungry to get to back at it.  Let's go!

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

## 📌 Kubernetes

I have been using Docker containers in production for approximately 7 years.  Most of that experience has been with AWS's Elastic Container Service (ECS) product, which was selected over K8s primarily for ease of use and a faster time to production.  In that organization, with no/limited DevOps resources, it was the right decision; Kubernetes (or Amazon's Elastic Kubernetes Service, EKS) was simply too much tool, and it was overkill for the businesses needs.  That implementation was very bespoke with a Terraform workflow around it.

In addition to ECS, I have built and run my own Docker Swarm clusters, both on bare metal servers and on EC2s in an AWS environment that was 100% Terraformed (by me).

My K8s experience has been on side/personal projects, some of which are published on my GitHub.  There are far more similarities between K8s and ECS/Swarm than there are differences.  Task defitinitons are basically Services + Deployments, and concepts like volumes, ingress, routes, virtual networks, load balancers, port mappings, resource allocations, replicas, failovers, and so on are all very common.  K8s is more sophisticated than ECS, but at the end of the day, the two stacks are _very_ similar.  On AWS, there are services, like API Gateway and Paramater Store (for secrets, that can be combined with ECS (or lambdas) in many similar and different ways.

## ☁️ AWS, GCP & Other Clouds

I have over 14 years of experience using AWS and other cloud providers (Heroku, Linode, Rack Space, etc.) and extensive experience with IaC using Terraform.  And while I have only ever used GCP for side/personal projects, I am 1,001% confident in my ability to rapidly take up GCP in an enterprise setting.  The vast majority of the concepts are the same or very similar.

## 👽 Random Things on my GitHub

This is all **very** elementary stuff -- sometimes I use these just to prove out a basic concept or maybe to provide myself a template for future use.

- [Basic Go Things](https://github.com/clarkritchie/basic-go-things)
  - [gRPC](https://github.com/clarkritchie/basic-go-things/tree/main/grpc) -- gRPC example of a "Hello World" server in Go, with clients in Go and Python
- [Basic Python Things](https://github.com/clarkritchie/basic-python-things)
  - [Go shared lib](https://github.com/clarkritchie/basic-python-things/tree/main/go-shared-lib) -- The Sieve of Sundaram in Python (native) vs Python but with a Go code compiled to a `.so` file
- [Kubernetes Things](https://github.com/clarkritchie/k8s-things) -- Hello world stuff (I'm finally learning K8s)
- Simple [example](https://github.com/clarkritchie/pizza-store-app) of how you might use Docker Compose to run a small Fast API server that can reach a Maria DB database
- [kickr-rpi-ws281x](https://github.com/clarkritchie/kickr-rpi-ws281x) -- This was a small side project to control a programmable LED light strip using heart rate data from a Wahoo TICKR heart rate monitor -- I never finished this, but the Bluetooth to the TICKR part works, IIRC (this project should probably be named `tickr-rpi-ws281x`)

### 🗒️ Gists -- Code Snippets, Scripts, Other Notes

- Shell script to [delete old branches](https://gist.github.com/clarkritchie/6be7d3d8fec96901002b01df2eaafb6e)
- [Use Python in a GHA step](https://gist.github.com/clarkritchie/a347d3fe9c72f47d9ece95f4dda38536)
- [Manage Cloudflare records](https://gist.github.com/clarkritchie/f518f5f7a8fb889f9fa9f87e7574cbe4)
- Cloudflare [maintenance page worker](https://gist.github.com/clarkritchie/31aa63566ac388332cb2a6275a40396d)
- [Other random notes and code snippets](https://gist.github.com/clarkritchie)
- Shell script to [tag a container with a semvar+sha](https://gist.github.com/clarkritchie/600297e23a05a629664bfbff20d03b51)
- [List, Copy, Delete S3 Bucket](https://gist.github.com/clarkritchie/fdce6b1a365ce176040bc8e7fca3a0c7)
- A few things that I made to make copying a Postgres db from [Heroku to RDS](https://github.com/clarkritchie/heroku-to-rds) a little easier
- [camelCased JSON from a Go Struct](https://gist.github.com/clarkritchie/e98791cfb06f6fcd22e40ddb2516376c) -- I was recently asked in an interview how to do this.  I've always referred to this as "JSON Hints", but maybe that's incorrect... I think that `json.Marshal` was all they were looking for.

### 🤖 GitHub Action Related

- Trick GHA into [revealing a secret](https://gist.github.com/clarkritchie/def05211e6dd0ec6a8e1edd48f0f822b) -- yes, this is possible!
- Example of how you might [lint in a GHA](https://gist.github.com/clarkritchie/2f935597b9398a34380e8c9a90005b6f) -- this example is for Terraform, but could be used to lint Python code with Ruff, etc.
- Full example of the [context object](https://gist.github.com/clarkritchie/b84937c0c83bcf1de9f25ca63bcaf77a)
- If you must do a [nested ternary](https://gist.github.com/clarkritchie/d3c35a9feeec5ed62ddbb38172ee62c2)

### 🔒️ 1Password Related

- Sort a [1Password Note](https://gist.github.com/clarkritchie/1e223f3cd3657cd00722be52f4249c1a) from the command line, uses the 1Password CLI
- I made this Python script to [read Secure Notes from 1Password and push to GitHub Secrets](https://github.com/clarkritchie/1pw-github-secrets) -- this is very bespoke but is how I once used 1Password Notes as the "source of truth" for env vars which were stored as GitHub secrets (environment, repository or organization) -- this code was originally forked from someone else's project but heavily modified for my needs
- Do the above [but in a GHA](https://gist.github.com/clarkritchie/843c54c66af0833d05a88ab6fd84a544) -- this is the way

### ⚙️ Terraform Related

- [Terraform Things](https://github.com/clarkritchie/terraform-things)

_TODO:  Revisit and revise these projects before linking to them._

- `app-api-uploads `-- File uploads
- `app-frontends` -- Hosting for React apps on S3 with CloudFront, etc.
- `aws-alarm-infrastructure` -- CloudWatch alarms and monitoring
- `aws-docker-swarm` -- VPC, subnets, EC2s, user data, etc.
- `aws-elasticache-redis` -- Redis
- `aws-guardduty` -- Sets up Guard Duty in 4 regions
- `aws-iam-accounts` -- Used to manage IAM jusers
- `aws-postgres-rds` -- RDS Serverless v2
