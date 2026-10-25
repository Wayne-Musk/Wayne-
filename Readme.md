<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img src="assets/banner-light.svg" alt="Wayne" width="100%">
</picture>

Software engineer working on AI infrastructure and agent tooling.

```console
$ whoami
Wayne

$ ls ~/work
backend/  ai-infra/  agent-tooling/  oss/
```

## Now

Looking for a role in AI infrastructure or backend engineering. In the meantime, I'm building agent tooling and contributing to open source.

## Stack

I work mostly in Python, Java, and Go, and use TypeScript for full-stack WeChat Mini Program development. Deployment goes through CI/CD to the cloud.

```mermaid
flowchart LR
    subgraph Languages
        direction TB
        py[Python]
        java[Java]
        go[Go]
        ts[TypeScript]
    end

    subgraph Work
        direction TB
        ai[AI infrastructure and agents]
        svc[Backend services]
        mini[WeChat Mini Programs]
    end

    subgraph Ship
        direction TB
        ci[CI/CD]
        cloud[Cloud deployment]
    end

    py --> ai
    go --> ai
    py --> svc
    java --> svc
    go --> svc
    ts --> mini
    ts --> svc
    ai --> ci
    svc --> ci
    mini --> ci
    ci --> cloud
```
