# COOLIFY

> Anticloud offline package — upstream: coollabsio/coolify @ `main`.

## What This Project Does

An open-source, self-hostable PaaS alternative to Vercel, Heroku & Netlify that lets you easily deploy static sites, databases, full-stack applications and 280+ one-click services on your own servers.

**Topics:** coolify, databases, deployment, docker, docker-compose, inertiajs, laravel, mariadb, mysql, nextjs, nodejs, php, postgres, redis, self-hosted, self-hosting, server, static-site, svelte, svelte5

## Upstream README

<div align="center">

<img src="./public/coolify-logo.svg" alt="Coolify logo" width="120" />

# Coolify

**An open-source platform to deploy applications, databases, and services on your own servers.**

Open source & free forever, backed by our [philosophy](https://coolify.io/philosophy).

![Latest Release Version](https://img.shields.io/badge/dynamic/json?labelColor=grey&color=6366f1&label=Latest%20released%20version&url=https%3A%2F%2Fcdn.coollabs.io%2Fcoolify%2Fversions.json&query=coolify.v4.version&style=for-the-badge
)

[Website](https://coolify.io) · [Documentation](https://coolify.io/docs) · [Cloud](https://app.coolify.io) · [Discord](https://coollabs.io/discord) · [Community](https://github.com/coollabsio/coolify/discussions)

</div>

## What is Coolify?

Coolify is an open-source and self-hostable alternative to Heroku, Netlify, and Vercel. It helps you manage servers, applications, and databases on your own hardware. You only need an SSH connection.

You can use a VPS, a bare-metal server, a Raspberry Pi, or any other server that accepts SSH connections. Coolify gives you the convenience of a cloud platform while you keep control of your infrastructure.

Your configurations stay on your servers. If you stop using Coolify, your running resources continue to work and remain manageable.

## What can Coolify do?

- **Deploy any application:** Build from GitHub, GitLab, Bitbucket, or Gitea with Nixpacks, Railpack, Dockerfile, Docker Compose, or a prebuilt Docker image.
- **Run databases and services:** Deploy managed databases and more than 300 one-click services with persistent storage and generated credentials.
- **Automate deployments:** Deploy on every Git push, create pull-request previews, call deployment webhooks, and roll back to retained application images.
- **Manage networking:** Configure custom domains, automatic HTTPS certificates, reverse proxies, health checks, and container networks.
- **Operate your infrastructure:** Manage multiple servers, inspect deployment and runtime logs, open container terminals, and monitor resource status.
- **Protect your workloads:** Configure database and storage backups, scheduled tasks, environment variables, secrets, and notifications.
- **Integrate with your workflow:** Manage resources through the dashboard, API, CLI, MCP, and team-based access controls.

## Quick start

Install Coolify on a supported server with one command:

```bash
curl -fsSL https://cdn.coollabs.io/coolify/install.sh | bash
```

Read the [installation guide](https://coolify.io/docs/installation) for requirements and detailed instructions. You can also review the [installation script](./scripts/install.sh) before you run it.

## Self-hosted or Cloud

| Self-hosted | Coolify Cloud |
| --- | --- |
| Install Coolify on your own server. | Use a Coolify instance that we maintain. |
| Control and maintain the complete platform. | Get high availability and less maintenance. |
| Free and open source. | Paid service with email not

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
