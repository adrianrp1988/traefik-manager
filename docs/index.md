---
layout: home

hero:
  name: Traefik Manager
  text: Self-hosted Traefik UI
  tagline: Manage routes, middlewares, static config, backups, and remote servers - without editing YAML.
  image:
    src: /images/icon.png
    alt: Traefik Manager
  actions:
    - theme: brand
      text: Get Started
      link: /guide
    - theme: alt
      text: GitHub
      link: https://github.com/chr0nzz/traefik-manager

features:
  - icon:
      light: /images/icons/route-light.svg
      dark: /images/icons/route-dark.svg
    title: Route Management
    details: Add, edit, clone, and toggle HTTP, TCP, and UDP routes with structured forms. Advanced rule editor for complex expressions. Bulk enable, disable, or delete. TLS Options profiles, wildcard cert domains, and raw YAML editor.
  - icon:
      light: /images/icons/shield-light.svg
      dark: /images/icons/shield-dark.svg
    title: Middleware Wizards
    details: 20+ guided templates - Basic Auth, OIDC Auth, Forward Auth (Authentik, Authelia, Gatekeeper), Rate Limit, IP Allowlist, Secure Headers, CORS, redirects, and more. Save and reuse your own custom templates.
  - icon:
      light: /images/icons/chart-light.svg
      dark: /images/icons/chart-dark.svg
    title: Live Dashboard
    details: Real-time stats, server-side route health pinging with latency, access log analytics, Route Map topology with dagre layout, and provider tabs for Docker, Kubernetes, Swarm, Nomad, ECS, and more.
  - icon: 🌐
    title: Multi-Server Agent Mode
    details: Manage unlimited remote Traefik instances from one TM. The lightweight TMA agent runs alongside Traefik on any server. Switch servers from the nav bar - routes, middlewares, backups, logs, and certs all show that server's data.
  - icon: 🗂️
    title: Git Backup & Restore
    details: Automatically push your config to GitHub, Gitea, GitLab, or any HTTPS Git host after every change. Browse commit history, view side-by-side Monaco diffs, and roll back to any commit in one click.
  - icon:
      light: /images/icons/lock-light.svg
      dark: /images/icons/lock-dark.svg
    title: Security & Monitoring
    details: bcrypt passwords, TOTP 2FA, OIDC SSO, API keys, CSRF, and rate limiting. Static config editor with Traefik restart. CrowdSec decisions and alerts. Notification webhooks for Discord, Slack, and ntfy.
---
