# serverless-media-pipeline

> Event-driven image pipeline on AWS — S3 upload triggers Python Lambda to resize, convert to WebP and generate AI alt text, with SQS and DynamoDB.

![status](https://img.shields.io/badge/status-in%20progress-yellow) ![area](https://img.shields.io/badge/area-Cloud%20Computing-blue) ![license](https://img.shields.io/badge/license-MIT-green)

🚧 **Work in progress.** This repo is part of my public learning roadmap (**Phase 3 — Cloud**). I build in the open — follow the commits and the roadmap below.

## Why this project

Learn serverless and event-driven design by automating something every website needs: optimised images with good alt text.

## What I'm learning

- AWS Lambda with Python
- Event-driven architecture: S3 events, SQS, dead-letter queues
- DynamoDB data modelling
- Image processing (resize, WebP) with Pillow
- Calling an LLM for accessible alt text
- Deploying with infrastructure as code

## Planned stack

Python · AWS Lambda · S3 · SQS · DynamoDB · Pillow · Terraform / AWS SAM

## Roadmap

- [ ] Lambda that resizes one image locally + tests
- [ ] S3 upload trigger → resized WebP variants
- [ ] SQS queue with retries and dead-letter queue
- [ ] AI-generated alt text
- [ ] Metadata stored in DynamoDB
- [ ] Infrastructure as code + CI deploy
- [ ] Logging, metrics and alarms
- [ ] README: event-flow diagram and costs

## Part of a 10-repo learning roadmap

I'm a full-stack developer in Vilnius ([armansalek.com](https://armansalek.com)) growing into **Python, Go, DevOps, cloud and AI engineering**. These repos connect: the Python and Go services are containerised, deployed and monitored by the DevOps and cloud repos, and the AI projects run on that infrastructure.

| # | Repo | Area | Phase |
|---|---|---|---|
| 1 | [lt-jobs-scraper](https://github.com/arman-aru/lt-jobs-scraper) | Python | 1 |
| 2 | [lt-vocab-api](https://github.com/arman-aru/lt-vocab-api) | Python | 1 |
| 3 | [parcel-locker-api](https://github.com/arman-aru/parcel-locker-api) | Golang | 1 |
| 4 | [go-uptime](https://github.com/arman-aru/go-uptime) | Golang | 1 |
| 5 | [ci-cd-pipelines](https://github.com/arman-aru/ci-cd-pipelines) | DevOps | 2 |
| 6 | [k8s-gitops-lab](https://github.com/arman-aru/k8s-gitops-lab) | DevOps | 2 |
| 7 | [terraform-aws-platform](https://github.com/arman-aru/terraform-aws-platform) | Cloud Computing | 3 |
| 8 | **serverless-media-pipeline** (this repo) | Cloud Computing | 3 |
| 9 | [site-audit-agent](https://github.com/arman-aru/site-audit-agent) | AI Engineering | 4 |
| 10 | [migration-rag-assistant](https://github.com/arman-aru/migration-rag-assistant) | AI Engineering | 4 |

## License

[MIT](LICENSE) © Arman Salek
