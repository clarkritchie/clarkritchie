# ❇️ Clark Ritchie

A platform engineer with a diverse background of experiences, hands-on building and operating scalable SaaS cloud-native systems for over 15 years as both an IC and leader.

I am passionate about building and operating **world-class applications** that **delight its end users**.

Connect with me on:
- [LinkedIn](https://www.linkedin.com/in/clarkritchie)
- [GitHub](https://www.github.com/clarkritchie)
- Or use [Calendly](https://calendly.com/clarkritchie) to get onto my calendar

## 💬 TL;DR

- Core skills:  Linux, Terraform, Docker and containers (Swarm/ECS/K8s), Go (Golang), Python, CI/CD, cloud (AWS/GCP)
- I am a developer, but also very close to infrastructure
- I approach software development with an SRE's mindset -- scalability, fault-tolerance, optimizing spend, monitoring and alerting -- these things, and more, are always part of my thinking
- Sometimes good is better than perfect; I like to ship early and ship often
- Let's go!

## 📌 Career TL;DR

- BS in Computer Science, Univ. of Puget Sound ('96)
- Early career — Intel factory automation, Hewlett-Packard, a startup (’96-’11)
- MS in Computer Science, Oregon State Univ. ('01)
- Experience at 4 startups
- 12 years writing software for fixed wireless networks in US low-income and throughout East Africa, Haiti, The Philippines
- Co-founded an [ISP in Kenya](https://pitchbook.com/profiles/company/113840-47) (’13-’18)
- 5 Years as Platform Engineer at [Specialized Bicycle Components](https://www.specialized.com/us/en) (’18-’23)
- Principal Engineer at Blueboard, a failed HR SaaS startup (’23-’24)
- My current role is as a Senior Staff SRE Software Engineer at [Dexcom](https://www.dexcom.com)

## 🗒️ Random Things on my GitHub

A lot of this is elementary stuff -- sometimes I use these just to prove out a basic concept or maybe to provide myself a template for future use.  Some of the Terraform is more sophisticated.

- [Basic Go Things](https://github.com/clarkritchie/basic-go-things)
  - [gRPC](https://github.com/clarkritchie/basic-go-things/tree/main/grpc) -- gRPC example of a "Hello World" server in Go, with clients in Go and Python
- Terraform Things
  - [GitHub](https://github.com/clarkritchie/terraform-things/tree/main/github-clarkritchie) for doing things with GitHub repos
  - [s3-static-hosting](https://github.com/clarkritchie/terraform-things/tree/main/s3-static-hosting) Very simple web hosting on S3, no https
  - [s3-remote-state](https://github.com/clarkritchie/terraform-things/tree/main/s3-remote-state) Terraform to create the Terraform backend state on AWS, so meta
  - The [Docker Swarm section](https://github.com/clarkritchie/terraform-things/tree/main/docker-swarm) is a series of bespoke Terraform projects I made to create a VPC, subnets, EC2s, ELBs, bootstrap a Docker Swarm cluster, stand up Postgres and MySQL (Serverless) and Elasticache (Redis) instances, as well as SNS for alarms, and more
    - [aws-alarm-infrastructure](https://github.com/clarkritchie/terraform-things/tree/main/docker-swarm/aws-alarm-infrastructure)
    - [aws-docker-swarm](https://github.com/clarkritchie/terraform-things/tree/main/docker-swarm/aws-docker-swarm) -- This is the base layer, the others mostly use `outputs` from this
    - [aws-elasticache-redis](https://github.com/clarkritchie/terraform-things/tree/main/docker-swarm/aws-elasticache-redis)
    - [aws-mysql-rds](https://github.com/clarkritchie/terraform-things/tree/main/docker-swarm/aws-mysql-rds)
    - [aws-postgres-rds](https://github.com/clarkritchie/terraform-things/tree/main/docker-swarm/aws-postgres-rds)
  - [AWS Guard Duty](https://github.com/clarkritchie/terraform-things/tree/main/aws-guardduty) A truly minimalistic setup of Guard Duty
- [Basic Python Things](https://github.com/clarkritchie/basic-python-things)
  - [Go shared lib](https://github.com/clarkritchie/basic-python-things/tree/main/go-shared-lib) -- The _Sieve of Sundaram_ in Python (native) versus it in Python, but with the heavy lifting done in Go (code compiled to a `.so` file)
- [Kubernetes Things](https://github.com/clarkritchie/k8s-things) -- Hello world stuff (I'm finally learning K8s)
- Simple [example](https://github.com/clarkritchie/pizza-store-app) of how you might use Docker Compose to run a small Fast API server that can reach a Maria DB database
- [tickr-rpi-ws281x](https://github.com/clarkritchie/kickr-rpi-ws281x) -- This was a small side project to control a programmable LED light strip using heart rate data from a Wahoo TICKR heart rate monitor -- I never finished this... the Bluetooth to the TICKR part works, IIRC
- [Nexus 7 Deployment Script](https://github.com/clarkritchie/nexus7) -- Something I did over 10 years ago to speed up deploying a bunch of Google tablets
- Quick Python script to [delete old branches](https://gist.github.com/clarkritchie/6be7d3d8fec96901002b01df2eaafb6e)
- Sort a [1Password Note](https://gist.github.com/clarkritchie/1e223f3cd3657cd00722be52f4249c1a) from the command line, uses the 1Password CLI
- I made this Python script to [read Secure Notes from 1Password and push to GitHub Secrets](https://github.com/clarkritchie/1pw-github-secrets) -- this is very bespoke but is how I once used 1Password Notes as the "source of truth" for env vars which were stored as GitHub secrets (environment, repository or organization) -- this code was originally forked from someone else's project but heavily modified for my needs
- [trails.losritchi.es](https://github.com/clarkritchie/trails.losritchi.es) is a tiny SPA (React) I made to help me name my mountain bike rides for Strava, it lives [here](http://trails.losritchi.es/)
- This is cool -- [use Python in a GHA step](https://gist.github.com/clarkritchie/a347d3fe9c72f47d9ece95f4dda38536)
- Trigger a GHA with a `workflow_dispatch` outside of the `main` branch [like this](https://github.com/clarkritchie/etc/blob/main/.github/workflows/run-outside-main.yaml)
- [Manage Cloudflare records](https://gist.github.com/clarkritchie/f518f5f7a8fb889f9fa9f87e7574cbe4)
- Cloudflare [maintenance page worker](https://gist.github.com/clarkritchie/31aa63566ac388332cb2a6275a40396d)
- Shell script to [tag a container with a semvar+sha](https://gist.github.com/clarkritchie/600297e23a05a629664bfbff20d03b51)
- [List, Copy, Delete S3 Bucket](https://gist.github.com/clarkritchie/fdce6b1a365ce176040bc8e7fca3a0c7)
- A few things that I made to make copying a Postgres db from [Heroku to RDS](https://github.com/clarkritchie/heroku-to-rds) a little easier
- Produce [camelCased JSON from a Go Struct](https://gist.github.com/clarkritchie/e98791cfb06f6fcd22e40ddb2516376c) -- I was recently asked in an interview how to do this, I've always referred to this as "JSON Hints", but maybe that's incorrect?  (I think that `json.Marshal` was all they were looking for!)
- Trick GHA into [revealing a secret](https://gist.github.com/clarkritchie/def05211e6dd0ec6a8e1edd48f0f822b) -- yes, this is possible!
- Example of how you might [lint in a GHA](https://gist.github.com/clarkritchie/2f935597b9398a34380e8c9a90005b6f) -- this example is for Terraform, but could be used to lint Python code with Ruff, etc.
- Full example of the [GHA 'context' object](https://gist.github.com/clarkritchie/b84937c0c83bcf1de9f25ca63bcaf77a)
- If you must do a [nested ternary](https://gist.github.com/clarkritchie/d3c35a9feeec5ed62ddbb38172ee62c2) in GHA
- Read Secure Notes from 1Password and push to GitHub Secrets (see above) [but in a GHA](https://gist.github.com/clarkritchie/843c54c66af0833d05a88ab6fd84a544) -- this is the way
- I didn't make this, *but this is amazing* -- a neat [search and replace](https://gist.github.com/clarkritchie/4e1e365085675995d9726d70cd87b9a3) shell hack for use with the [Silver Searcher](https://github.com/ggreer/the_silver_searcher)
- Additional other random notes and code snippets that I did not explicitly link to are [here](https://gist.github.com/clarkritchie)

## Not Mine

Here are some excellent Gists by Andrew Zurn on how to use [Ollama](https://ollama.com/) to write your PRs for you (and other things):

- [https://gist.github.com/AndrewZurn/8050f8ad5bff2c6826cd71eacaa52fb9](https://gist.github.com/AndrewZurn/8050f8ad5bff2c6826cd71eacaa52fb9)
- ⁠[⁠https://gist.github.com/AndrewZurn/ef633ace2f28828d38bbbcac5cca523a](https://gist.github.com/AndrewZurn/ef633ace2f28828d38bbbcac5cca523a)
- [⁠https://gist.github.com/AndrewZurn/01f3fa2e8de80a06ab744b39d472e5d4](⁠https://gist.github.com/AndrewZurn/01f3fa2e8de80a06ab744b39d472e5d4)
- [⁠https://gist.github.com/AndrewZurn/382d20e58c60e9188ff0b12658200c71](⁠https://gist.github.com/AndrewZurn/382d20e58c60e9188ff0b12658200c71)