<p align="right"><a href="Readme.md">中文</a> · <strong>English</strong></p>

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

I mostly write Python, Java, and Go. On the client side I use TypeScript, including full-stack WeChat Mini Programs. Deployment goes through CI/CD to the cloud.

```mermaid
flowchart LR
    subgraph lang[Languages]
        direction TB
        py[Python]
        java[Java]
        go[Go]
        ts[TypeScript]
    end

    subgraph work[Work]
        direction TB
        ai[AI infrastructure and agents]
        svc[Backend services]
        mini[WeChat Mini Programs]
    end

    subgraph ship[Ship]
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
