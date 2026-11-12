## Tamedia Technology

We build the digital products behind Tamedia, Switzerland's largest media house, part of [TX Group](https://tx.group).
Our platforms serve news in German and French to readers across the country, including
Tages-Anzeiger, 24 heures, Tribune de Genève, BZ Berner Zeitung, Der Bund, Basler Zeitung,
Finanz und Wirtschaft, SonntagsZeitung and Le Matin Dimanche.

Most of our code is private. What we can share lives here: the tools we use to build, ship and run our platforms.

### Delivery and CI/CD

| Repository | What it does |
|------------|--------------|
| [tamci](https://github.com/DND-IT/tamci) | One Go CLI for our GitHub Actions: workflow matrices, Helm rollouts, releases, locks, step summaries |
| [github-workflows](https://github.com/DND-IT/github-workflows) | Shared, reusable GitHub Actions workflows |
| [helm-charts](https://github.com/DND-IT/helm-charts) | Helm charts for apps on Kubernetes: `web`, `worker`, `task`, `generic` and more |

### Cloud and infrastructure

| Repository | What it does |
|------------|--------------|
| [containers](https://github.com/DND-IT/containers) | Multi-arch, rootless container images for cloud work |
| [terraform-aws-github-token-broker](https://github.com/DND-IT/terraform-aws-github-token-broker) | Serverless GitHub App token broker: octo-sts on Lambda, App key in KMS |
| [terraform-aws-cloudfront-okta-auth](https://github.com/DND-IT/terraform-aws-cloudfront-okta-auth) | Okta OIDC login in front of a CloudFront distribution |

### Developer tools and libraries

| Repository | What it does |
|------------|--------------|
| [tamedia-tools](https://github.com/DND-IT/tamedia-tools) | Tools for Tamedia developers |
| [homebrew-tap](https://github.com/DND-IT/homebrew-tap) | Homebrew formulas for our tools |
| [skills](https://github.com/DND-IT/skills) | Curated collection of agent skills |
| [dnd-iframe-messaging](https://github.com/DND-IT/dnd-iframe-messaging) | Cross-frame messaging for iframes embedded across our titles |
| [go-imagequant](https://github.com/DND-IT/go-imagequant) | Go wrapper for libimagequant, for image compression |

### Data journalism

Code behind data stories from our newsrooms, for example
[Swiss baby names](https://github.com/DND-IT/2025-08_babynames) and
[Gaza: destruction and the humanitarian situation](https://github.com/DND-IT/2025-08_data_gaza).

### Quick start

```bash
helm repo add dnd-it https://dnd-it.github.io/helm-charts
helm search repo dnd-it
```

### Work with us

Found a bug or have an idea? Open an issue or pull request in the repository.
Want to join the team? See open roles at [jobs.tamedia.ch](https://jobs.tamedia.ch).
