# awesome-devtools

> 🛠️ Curated collection of developer tools — from databases to AI coding assistants, from local dev tunnels to production monitoring.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Contents:** [Databases](#databases) · [API Clients](#api-clients) · [AI Coding](#ai-coding) · [DevOps & Infra](#devops--infra) · [Productivity](#productivity) · [Local Dev](#local-dev) · [CI/CD](#cicd) · [Monitoring & Observability](#monitoring--observability) · [Code Quality](#code-quality) · [Testing](#testing) · [Security](#security) · [Design & Docs](#design--docs) · [Collaboration](#collaboration)

---

## Databases

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [DBeaver](https://dbeaver.io) | Universal SQL client — supports 80+ databases, ERDs, data export | Free/EE | Best all-around DB GUI |
| [Adminer](https://www.adminer.org) | Single PHP file DB management UI | GPL | Drop-in, no install needed |
| [Beekeeper Studio](https://beekeeperstudio.io) | Modern, beautiful SQL editor | Apache 2 | Dark mode, autocompletion |
| [Azure Data Studio](https://learn.microsoft.com/en-us/azure-data-studio/) | VS Code-based DB tool from Microsoft | Free | Great for SQL Server/PostgreSQL |
| [DbVisualizer](https://www.dbvis.com) | Universal DB client, cross-platform | Free/Pro | ERD diagrams, query history |
| [TablePlus](https://tableplus.com) | Native macOS/Windows DB client | Free/Paid | Blazing fast, clean UI |
| [Datasette](https://datasette.io) | Explore and publish SQLite databases | Apache 2 | Great for data journalism |
| [SQLite Viewer](https://marketplace.visualstudio.com/items?itemName=meowie.sqlite-viewer) | VS Code extension for browsing .sqlite files | MIT | No export needed |
| [Medusa Data Editor](https://github.com/necauqua/medusa) | Edit databases like a spreadsheet | MIT | Inline editing for any DB |
| [pgAdmin](https://www.pgadmin.org) | Feature-rich PostgreSQL administration | PostgreSQL | The go-to for Postgres |
| [MongoDB Compass](https://www.mongodb.com/products/compass) | Official MongoDB GUI with visual query builder | Free | Schema visualization |
| [TableClip](https://github.com/0x706b/tableclip) | Spreadsheet-as-DB viewer, supports CSV/TSV | MIT | Zero-setup CSV exploration |

---

## API Clients

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [Bruno](https://www.usebruno.com) | Git-friendly API client — collections stored as plain text | MIT | Best for team collaboration |
| [Insomnia](https://insomnia.rest) | Design, debug, test REST/gRPC/GraphQL | Apache 2 | Beautiful, powerful |
| [Postman](https://www.postman.com) | Industry-standard API platform | Free/Pro | Huge ecosystem |
| [HTTPie](https://httpie.io) | User-friendly CLI HTTP client | BSD-3 | `http GET example.com` |
| [Curli](https://curli.app) | Lightweight web-based API tester | Free | No install, browser-based |
| [Schematic](https://schematic.com) | API design & mock server | Free/Pro | Spec-first workflow |
| [SoapUI](https://www.soapui.org) | SOAP/REST API testing tool | Free/Pro | Enterprise-grade |
| [RapidAPI](https://rapidapi.com) | Test & discover public APIs | Free/Pro | 35k+ APIs in marketplace |
| [EchoAPI](https://www.echoapi.com) | Lightweight API debugging (Postman-like) | Free | Ultra-lightweight alternative |
| [Apidog](https://apidog.com) | API design, debug, mocking, testing | Free/Pro | All-in-one API platform |

---

## AI Coding

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [Cursor](https://cursor.com) | AI-first code editor, built on VS Code | Pro | Composer, Agent mode |
| [Windsurf](https://codeium.com/windsurf) | Flow-based AI coding agent | Free/Pro | Cascade AI engine |
| [Augment Code](https://www.augmentcode.com) | Enterprise AI developer platform | Enterprise | Context-aware, privacy-focused |
| [Tabnine](https://www.tabnine.com) | AI code completion, runs locally | Free/Pro | Privacy-first, 100+ languages |
| [GitHub Copilot](https://github.com/features/copilot) | AI pair programmer in VS Code, JetBrains | Paid | Best overall DX |
| [Codeium](https://codeium.com) | Free AI code completion | Free | Good Copilot alternative |
| [Replit Agent](https://replit.com) | AI that builds full apps from prompts | Free/Pro | Full app generation |
| [Devin](https://devin.ai) | Autonomous AI software engineer | Paid | End-to-end task completion |
| [Cody](https://sourcegraph.com/cody) | AI coding assistant by Sourcegraph | Free/Pro | Context-aware, repo-wide |
| [Continue](https://continue.dev) | Open-source AI code assistant for VS Code/IntelliJ | Apache 2 | Self-hostable, extensible |
| [Aider](https://aider.chat) | Terminal-based AI pair programming | AGPL-3 | Works with any editor |
| [Copilot Chat (JetBrains)](https://www.jetbrains.com/help/idea/resharper_gpu.html) | AI assistant in JetBrains IDEs | Bundled | Built into IDEA/Rider |

---

## DevOps & Infra

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [Portainer](https://www.portainer.io) | Web UI for Docker & Kubernetes | Community/EE | Easiest container management |
| [Traefik](https://traefik.io) | Modern reverse proxy & load balancer | MIT | Auto HTTPS, hot reload |
| [Nginx Proxy Manager](https://nginxproxymanager.com) | Beautiful GUI for Nginx reverse proxy | MIT | SSL made easy |
| [Watchtower](https://github.com/containrrr/watchtower) | Auto-update running Docker containers | Apache 2 | Zero-downtime updates |
| [CasaOS](https://www.casaos.io) | Simple, smart home-friendly OS interface | Apache 2 | Home lab friendly |
| [1Panel](https://1panel.cn) | Modern Linux server management panel | GPL-3 | Chinese open-source, feature-rich |
| [Coolify](https://coolify.io) | Self-host Heroku/Vercel alternative | Apache 2 | One-click deploys |
| [Caddy](https://caddyserver.com) | Automatic HTTPS web server | Apache 2 | Zero-config SSL |
| [Docker Compose V2](https://github.com/docker/compose) | Multi-container Docker orchestration | Apache 2 | `docker compose up` |
| [K9s](https://k9scli.io) | Terminal UI for Kubernetes | Apache 2 | `kubectl` without the pain |
| [Lens](https://k8slens.dev) | Kubernetes IDE / multi-cluster management | MIT | Best Kubernetes GUI |
| [Rancher](https://rancher.com) | Enterprise Kubernetes management platform | Apache 2 | Multi-cluster, multi-cloud |
| [Grafana](https://grafana.com) | Observability platform, dashboards & alerting | AGPL-3 | The standard for metrics |
| [Prometheus](https://prometheus.io) | Systems monitoring and alerting toolkit | Apache 2 | Pull-based metrics collection |
| [Ansible](https://www.ansible.com) | IT automation: config, provisioning, deployment | GPL-3 | Agentless, YAML-based |
| [Terraform](https://www.terraform.io) | Infrastructure as Code | BSL | Declarative cloud provisioning |
| [Tailscale](https://tailscale.com) | Zero-config VPN built on WireGuard | Free/Pro | Easiest VPN ever |
| [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks) | Expose local services via Cloudflare edge | Free | No open ports needed |

---

## Productivity

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [Warp](https://www.warp.dev) | AI-powered terminal with blocks & workflow | Free/Pro | Best modern terminal |
| [Fig](https://fig.io) | Interactive autocomplete for terminal | Free/Pro | Bash/Zsh/Fish completions |
| [lazygit](https://github.com/jesseduffield/lazygit) | TUI for Git commands | GPL-3 | Makes Git painless |
| [lazydocker](https://github.com/jesseduffield/lazydocker) | TUI for Docker containers | GPL-3 | Docker without the headache |
| [zoxide](https://github.com/ajeetdsouza/zoxide) | Smarter `cd`, learns your habits | MIT | Blazing fast directory jumps |
| [fzf](https://github.com/junegunn/fzf) | Fuzzy finder for terminal | MIT | Works everywhere |
| [rg (ripgrep)](https://github.com/BurntSushi/ripgrep) | Ultra-fast grep alternative | MIT | The fastest grep, ever |
| [bat](https://github.com/sharkdp/bat) | `cat` with syntax highlighting and git diff | MIT | Better cat |
| [eza](https://github.com/eza-community/eza) | Modern `ls` with icons and git status | MIT | Beautiful directory listings |
| [delta](https://github.com/dandavison/delta) | Git diff viewer with syntax highlighting | MIT | Makes git diff gorgeous |
| [tldr-pages](https://tldr.sh) | Simplified man pages with examples | MIT | Quick command help |
| [httpie](https://httpie.io) | Human-friendly CLI HTTP client | BSD-3 | cURL but readable |
| [jq](https://jqlang.github.io/jq/) | JSON processor for the command line | MIT | Filter JSON at CLI |
| [yq](https://github.com/mikefarah/yq) | YAML/JSON/TOML processor | MIT | Like jq but for YAML |
| [sheldon](https://github.com/rossmacarthur/sheldon) | Fast, configurable plugin manager for shells | MIT | Rust-based |
| [ atuin](https://github.com/atuinsh/atuin) | Magical shell history | MIT | Searchable, syncable history |
| [Direnv](https://direnv.net) | Per-directory environment variables | MIT | Auto-load .envrc files |
| [Mission Control](https://github.com/missioncontrol-sh/missioncontrol) | AI-powered shell agent | MIT | Natural language → shell commands |

---

## Local Dev

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [ngrok](https://ngrok.com) | Secure tunnels to localhost | Free/Pro | Industry standard |
| [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks) | Free public URLs via Cloudflare edge | Free | No account needed for basic |
| [DevTunnel](https://learn.microsoft.com/en-us/azure/azure-devtools/repos/tunneling) | Microsoft-backed localhost tunnel | Free | Azure DevOps integrated |
| [Localtunnel](https://theboroer.github.io/localtunnel-us/) | Free, no-auth tunnel to localhost | MIT | Quick sharing without signup |
| [inlets](https://inlets.dev) | Cloud-native tunnel in Go | Apache 2 | Self-hostable |
| [Expose](https://expose.dev) | ngrok alternative, open source | MIT | Simple, fast |
| [Valet](https://laravel.com/docs/valet) | Laravel Valet — share local sites | MIT | macOS-only, zero config |
| [DDEV](https://ddev.com) | Docker-based local development environment | MIT | PHP/Drupal/WordPress optimized |
| [Lando](https://lando.dev) | Local dev environments with Docker | GPL-3 | Composable, reproducible |
| [Devcontainers](https://containers.dev) | VS Code devcontainers spec | MIT | Standardized dev environments |
| [Mailpit](https://github.com/axllent/mailpit) | Local SMTP tester & browser UI | Apache 2 | Catch emails without sending |
| [Mockoon](https://mockoon.com) | Mock REST APIs in seconds | MIT | Desktop app + CLI |
| [httpbin](https://httpbin.org) | HTTP Request & Response test service | Apache 2 | Great for debugging HTTP |
| [JSONPlaceholder](https://jsonplaceholder.typicode.com) | Fake REST API for testing | MIT | 100 users, 100 posts, etc. |
| [Beeceptor](https://beeceptor.com) | Mock HTTP endpoints, free tier | Free | No setup needed |
| [Webhook.site](https://webhook.site) | Custom webhook URLs for testing | Free | Instant unique URLs |
| [ngrokokal](https://github.com/mxschmitt/ngrokokal) | ngrok with local API key management | MIT | Manage multiple tunnels |

---

## CI/CD

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [GitHub Actions](https://github.com/features/actions) | CI/CD built into GitHub | Free/Pro | Largest ecosystem |
| [Gitea Actions](https://docs.gitea.com/usage/_actions/overview) | GitHub Actions-compatible CI for Gitea | MIT | Self-hosted alternative |
| [Jenkins](https://www.jenkins.io) | Extendable CI/CD automation server | MIT | Classic, battle-tested |
| [Drone](https://www.drone.io) | Container-native CI/CD | Apache 2 | Docker-based pipelines |
| [Woodpecker CI](https://woodpecker-ci.org) | Community fork of Drone | Apache 2 | Open-source, simple |
| [Tekton](https://tekton.dev) | Kubernetes-native CI/CD framework | Apache 2 | Cloud-native pipelines |
| [Argo Workflows](https://argoproj.github.io/workflows/) | Container-native workflow engine for K8s | Apache 2 | GitOps + ML pipelines |
| [Codemagic](https://codemagic.io) | Flutter & mobile CI/CD | Free/Pro | Best for mobile |
| [Bitrise](https://www.bitrise.io) | Mobile CI/CD platform | Free/Pro | Native iOS/Android |
| [Depot](https://depot.dev) | Fast container builds in the cloud | Free/Pro | 10x faster than GitHub Actions |
| [CircleCI](https://circleci.com) | Modern CI/CD platform | Free/Pro | Great parallelism |
| [Semaphore](https://semaphoreci.com) | CI/CD with parallel jobs | Free/Pro | Simple setup |
| [Danger](https://danger.systems) | Automated PR feedback | MIT | Keep PRs clean |
| [Reviewdog](https://github.com/reviewdog/reviewdog) | Automated code review in PRs | MIT | Linter results as comments |
| [Renovate](https://renovatebot.com) | Automated dependency updates | AGPL-3 | Keep deps fresh |
| [Dependabot](https://github.com/dependabot) | GitHub-native dependency updates | GitHub | Native integration |
| [Renovate](https://renovatebot.com) | Automated dependency updates | AGPL-3 | Keep deps fresh |

---

## Monitoring & Observability

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [Grafana](https://grafana.com) | Observability dashboards | AGPL-3 | The gold standard |
| [Prometheus](https://prometheus.io) | Metrics collection & alerting | Apache 2 | Pull-based, powerful |
| [Loki](https://grafana.com/oss/loki/) | Log aggregation system | AGPL-3 | Like Prometheus, for logs |
| [Tempo](https://grafana.com/oss/tempo/) | Distributed tracing backend | AGPL-3 | Integrates with Grafana |
| [Uptime Kuma](https://github.com/louislam/uptime-kuma) | Self-hosted monitoring with web UI | MIT | Beautiful status pages |
| [Better Uptime](https://betterstack.com/uptime) | Uptime monitoring & on-call | Free/Pro | Great free tier |
| [Sentry](https://sentry.io) | Error tracking & performance monitoring | Free/Pro | Essential for production |
| [Glitchtip](https://glitchtip.com) | Open-source Sentry alternative | MIT | Self-hostable error tracking |
| [Jaeger](https://www.jaegertracing.io) | Distributed tracing | Apache 2 | OpenTelemetry native |
| [Zipkin](https://zipkin.io) | Distributed tracing system | Apache 2 | Lightweight alternative |
| [OpenTelemetry Collector](https://opentelemetry.io/docs/collector/) | Vendor-neutral telemetry collection | Apache 2 | The standard for observability |
| [Vector](https://vector.dev) | High-performance log/metric processor | MPL-2 | Written in Rust |
| [Datadog](https://datadoghq.com) | SaaS APM & infrastructure monitoring | Paid | Enterprise-grade |
| [New Relic](https://newrelic.com) | Full-stack observability | Free/Pro | Comprehensive |
| [Checkly](https://www.checklyhq.com) | API & browser synthetic monitoring | Free/Pro | Playwright-based |
| [StatusPal](https://statuspal.io) | Status page hosting | Free/Pro | Clean, simple |

---

## Code Quality

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [SonarQube](https://www.sonarsource.com/products/sonarqube/) | Code quality & security analysis | Community/Enterprise | The standard |
| [CodeClimate](https://codeclimate.com) | Automated code review | Free/Pro | GitHub-integrated |
| [Snyk](https://snyk.io) | Vulnerability scanning for code & deps | Free/Pro | Best for security |
| [Socket](https://socket.dev) | Detect supply chain attacks in npm/pip | Free/Pro | npm audit on steroids |
| [Dependabot](https://github.com/dependabot) | Automated dependency updates | GitHub | Native to GitHub |
| [Renovate](https://renovatebot.com) | Multi-language dependency updater | AGPL-3 | Most configurable |
| [Prettier](https://prettier.io) | Opinionated code formatter | MIT | Zero-config, universal |
| [ESLint](https://eslint.org) | JavaScript/TypeScript linter | MIT | Extensible, huge ecosystem |
| [Ruff](https://astral.sh/ruff) | Extremely fast Python linter | MIT | 10-100x faster than flake8 |
| [golangci-lint](https://golangci-lint.run) | Go linter aggregator | GPL-3 | Best Go linting experience |
| [Actionlint](https://github.com/rhysd/actionlint) | Linter for GitHub Actions YAML | MIT | Catch GitHub Actions errors |
| [Trunk](https://trunk.io) | Monorepo linter manager | Apache 2 | Unified linting config |
| [Codecov](https://about.codecov.io) | Code coverage tracking | Free/Pro | GitHub-integrated |
| [Coveralls](https://coveralls.io) | Coverage tracking for CI | Free/Pro | Historical coverage tracking |
| [Cursorrules](https://github.com/Thwindbird/CursorRules) | Cursor AI coding rules | MIT | Standardized AI prompts |

---

## Testing

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [agent-qa](https://vostride.com) | Natural-language web, Android and iOS QA | [FSL-1.1-ALv2](https://vostride.com/license.md), competing-use limits | Persistent memidex memory, validated self-improvement, inspectable run evidence; model/infra costs separate |
| [Cucumber](https://cucumber.io) | BDD testing with Gherkin | MIT | Living documentation |
| [Cypress](https://www.cypress.io) | End-to-end web testing | MIT | Great DX, time-travel debug |
| [Gauge](https://gauge.org) | Lightweight test automation | Apache 2 | Spec-driven, markdown-based |
| [Jest](https://jestjs.io) | Delightful JavaScript testing | MIT | The most popular JS test runner |
| [Jest Preview](https://www.jest-preview.com) | Live browser preview for Jest tests | MIT | See your tests run visually |
| [K6](https://k6.io) | Load testing with JS scripting | AGPL-3 | Developer-friendly load testing |
| [Karate](https://karatelabs.github.io/karate) | API test automation in one file | MIT | DSL-free, plain English |
| [Locust](https://locust.io) | Distributed load testing in Python | MIT | Script with Python |
| [Mock Service Worker](https://mswjs.io) | API mocking for browser & Node | MIT | Intercept requests natively |
| [Playwright](https://playwright.dev) | Web testing & automation | Apache 2 | Cross-browser, auto-wait |
| [Pytest](https://pytest.org) | Mature Python testing framework | MIT | Powerful fixtures, plugins |
| [Selenium](https://www.selenium.dev) | Browser automation for testing | Apache 2 | Classic, language-agnostic |
| [Testcontainers](https://testcontainers.com) | Real databases in Docker for tests | Apache 2 | Integration tests made easy |
| [Testing Library](https://testing-library.com) | Testing utilities for accessible UIs | MIT | DOM Testing Library + friends |
| [Vitest](https://vitest.dev) | Blazing fast unit test framework | MIT | Vite-native, Jest-compatible |
| [Wiremock](https://wiremock.org) | Stub and mock HTTP APIs | Apache 2 | Great for integration testing |

---

## Security

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [1Password](https://1password.com) | Password manager for teams | Paid | Best password manager |
| [Bitwarden](https://bitwarden.com) | Open-source password manager | GPL-3 | Self-hostable |
| [Vault](https://www.vaultproject.io) | Secrets management & encryption | MPL-2 | HashiCorp's solution |
| [SOPS](https://github.com/mozilla/sops) | Secrets OPerationS — encrypted files | MPL-2 | Encrypt YAML/JSON/ENV |
| [CrowdSec](https://crowdsec.net) | Collaborative IP threat intelligence | MIT | Like Fail2Ban but modern |
| [Trivy](https://aquasecurity.github.io/trivy/) | Vulnerability scanner for containers | Apache 2 | Scan images in seconds |
| [Semgrep](https://semgrep.dev) | Static analysis for security bugs | LGPL-3 | Fast, precise |
| [Bandit](https://bandit.readthedocs.io) | Python security linter | Apache 2 | Find common security issues |
| [ZAP](https://www.zaproxy.org) | OWASP Zed Attack Proxy | Apache 2 | Web app security scanner |
| [Burp Suite Community](https://portswigger.net/burp/community) | Web vulnerability scanner | Free/Pro | Industry standard |
| [Nuclei](https://nuclei.projectdiscovery.io) | Fast vulnerability scanner with templates | MIT | Community-driven templates |
| [ClamAV](https://www.clamav.net) | Open-source antivirus engine | GPL-2 | Malware detection |
| [Wazuh](https://wazuh.com) | Open-source XDR & SIEM | GPL-2 | Threat detection & response |
| [Tailscale SSH](https://tailscale.com/tailscale-ssh) | Short-lived SSH certificates via Tailscale | Free/Pro | No keys to manage |
| [Authentik](https://goauthentik.io) | Identity provider & SSO | Apache 2 | Self-hosted Auth0 alternative |
| [Keycloak](https://www.keycloak.org) | Open-source identity broker | Apache 2 | Enterprise SSO, SAML, OIDC |

---

## Design & Docs

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [Figma](https://figma.com) | Collaborative interface design | Free/Pro | The industry standard |
| [Penpot](https://penpot.app) | Open-source design tool, web-based | MPL-2 | Figma alternative, self-hostable |
| [Excalidraw](https://excalidraw.com) | Hand-drawn style diagrams | MIT | Great for architecture diagrams |
| [Draw.io (diagrams.net)](https://app.diagrams.net) | Free online diagram editor | Apache 2 | Flowcharts, UML, everything |
| [Mermaid](https://mermaid.js.org) | Diagrams from text (flowcharts, Gantt, etc.) | MIT | Markdown-embeddable |
| [Canva](https://canva.com) | Design platform for non-designers | Free/Pro | Quick visuals |
| [Shields.io](https://shields.io) | SVG badges for README files | CC0 | Auto-generated, customizable |
| [Carbon](https://carbon.now.sh) | Beautiful code screenshot generator | MIT | Beautiful code images |
| [Ray.so](https://ray.so) | Code to image converter | Free | Quick sharing |
| [Readme.so](https://readme.so) | README generator with templates | MIT | Markdown templates |
| [Docusaurus](https://docusaurus.io) | Documentation site generator | MIT | React-based, MDX |
| [Mintlify](https://mintlify.com) | Beautiful documentation | Free/Pro | Auto-generated from MDX |
| [Notion](https://notion.so) | All-in-one workspace & docs | Free/Pro | Great for team wikis |
| [Obsidian](https://obsidian.md) | Local-first knowledge base | Free/Pro | Markdown, backlinks, graphs |
| [Slite](https://slite.com) | Simple team wiki & docs | Free/Pro | Clean, focused |
| [Swimm](https://swimm.io) | Docs that stay in sync with code | Free/Pro | Auto-updating documentation |

---

## Collaboration

| Tool | Description | License | Notes |
|------|-------------|---------|-------|
| [GitHub](https://github.com) | Code hosting & collaboration | Free/Pro | Largest dev community |
| [Gitea](https://gitea.com) | Lightweight self-hosted Git service | MIT | Drop-in GitHub alternative |
| [GitLab](https://about.gitlab.com) | Complete DevOps platform | EE/Core | All-in-one |
| [Linear](https://linear.app) | Issue tracking for software teams | Free/Pro | Fastest issue tracker |
| [Plane](https://plane.so) | Open-source project management | Apache 2 | Self-hostable Linear alternative |
| [Zulip](https://zulip.com) | Threaded team chat | Apache 2 | Async-first, open-source |
| [Discourse](https://www.discourse.org) | Forum & community platform | GPL-2 | Modern, mobile-friendly |
| [Mattermost](https://mattermost.com) | Open-source Slack alternative | MIT | Self-hostable |
| [Supavisor](https://github.com/nicholaslarock/supavisor) | Multi-tenant Postgres proxy | MIT | Connection pooling for Supabase |
| [Turso](https://turso.tech) | SQLite for production (edge) | Free/Pro | Distributed SQLite |
| [Neon](https://neon.tech) | Serverless Postgres | Free/Pro | Autoscaling, branching |
| [Canny](https://canny.io) | User feedback & roadmap board | Free/Pro | Track feature requests |
| [Loom](https://loom.com) | Async video messaging | Free/Pro | Record screen + cam instantly |
| [Codespaces](https://github.com/features/codespaces) | Cloud dev environments | Free/Pro | Full VS Code in browser |

---

## Contributing

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a PR.

*Star and watch — this list grows weekly.*
