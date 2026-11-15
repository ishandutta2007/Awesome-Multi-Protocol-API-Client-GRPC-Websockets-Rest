<div align="center">

<a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
<a href="LICENSE"><img src="https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=flat-square" alt="License: CC0-1.0" /></a>
<a href="https://github.com/ishandutta2007/Awesome-Multi-Protocol-API-Client-GRPC-Websockets-Rest/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Multi-Protocol-API-Client-GRPC-Websockets-Rest?style=flat-square" alt="Stars" /></a>
<a href="https://github.com/ishandutta2007/Awesome-Multi-Protocol-API-Client-GRPC-Websockets-Rest/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Multi-Protocol-API-Client-GRPC-Websockets-Rest?style=flat-square" alt="Forks" /></a>
<a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

<br /><br />

<a href="#readme">
  <img src="assets/banner.svg" alt="Awesome Multi-Protocol API Client Banner - REST, GraphQL, gRPC, WebSockets, MQTT" width="100%" />
</a>

# 🌐 Awesome Multi-Protocol API Client (gRPC / WebSockets / REST / GraphQL)

> 🚀 A comprehensive, curated directory of the best **Multi-Protocol API Client** platforms, tools, and developer environments. Compare leading SaaS commercial solutions alongside top open-source alternatives for authoring, testing, debugging, and mocking **REST**, **gRPC**, **WebSockets**, **GraphQL**, **SSE**, and **MQTT** APIs from a single unified interface.
> 
> 🌟 *Star this repository to keep track of new releases and emerging tools!* 🌟

</div>

---

## 📑 Table of Contents

- [📈 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [📋 Quick Comparison Table (SaaS vs OSS)](#-quick-comparison-table)
- [🟦 SaaS / Commercial Hosted Platforms](#-saas--commercial-hosted-platforms)
- [🟩 Open-Source Software Tools](#-open-source-software-tools)
  - [1. Hoppscotch](#1-hoppscotch)
  - [2. Bruno](#2-bruno)
  - [3. Kong Insomnia](#3-kong-insomnia)
  - [4. Yaak](#4-yaak)
  - [5. grpcurl](#5-grpcurl)
  - [6. BloomRPC](#6-bloomrpc)
  - [7. grpcui](#7-grpcui)
  - [8. API Dash](#8-api-dash)
  - [9. Restfox](#9-restfox)
  - [10. Step CI](#10-step-ci)
  - [11. Milkman](#11-milkman)
  - [12. Warthog](#12-warthog)
  - [13. OneOpen Postkid](#13-oneopen-postkid)
- [🤝 Contributing](#-contributing)
- [💖 Support](#-support)
- [📈 Star History](#-star-history)
- [📄 License](#-license)

---

## 📈 Sector Overview & Market Dynamics

The global API management and testing tools market is estimated between **$8 billion and $15 billion** (projected to reach over $35 billion by 2032 at an annual CAGR of ~18–22%). 

The ecosystem is **moderately fragmented**: while enterprise incumbents like Postman and Kong command significant developer mindshare, no single vendor maintains a "winner-take-all" monopoly across every protocol. The landscape is split across specialized gRPC debugging utilities, privacy-first local-first desktop apps, Git-native CI/CD tooling, and browser-based real-time clients.

---

## 🟦 SaaS / Commercial Hosted Platforms

Commercial, cloud-hosted, and hybrid multi-protocol API client platforms. The table below is sorted in **descending order by company valuation / scale**:

| Platform | Company Scale / Valuation | Starting Paid Tier Pricing | Free Tier / Trial Limits | Supported Protocols | Key Strengths |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **📮 [Postman](https://www.postman.com/)** | **$5.6B Valuation** *(~$310M+ ARR)* | **$14/user/month** *(Basic, billed annually)* or **$19/mo** monthly | **Free Forever Plan**: Capped at 1 user, 10,000 Postman API calls/month, up to 5 integrations, 3 active collection runners, unlimited mock servers/specs. | REST, GraphQL, gRPC, WebSockets, Socket.IO, MQTT, SSE | Global industry standard with cloud workspaces, team governance, API cataloging, and comprehensive CI/CD integrations. |
| **🌙 [Kong Insomnia](https://insomnia.rest/)** | **$2.0B Parent Valuation** *(Kong: $100M+ ARR)* | **$12/user/month** *(Team, billed annually)* or **$15/mo** monthly | **Free Essentials Plan**: Capped at 1 user for cloud projects (up to 3 users for Git Sync), 1,000 mock server requests/month, local scratchpad mode. | REST, GraphQL, gRPC, WebSockets, SSE | Deep GraphQL schema introspection, local-first option with End-to-End Encryption (E2EE), and native Kong Gateway plugins. |
| **🐕 [Apidog](https://apidog.com/)** | **Privately Held / Bootstrapped** *(Self-funded, 5M+ users)* | **$9/user/month** *(Basic, billed annually)* or **$12/mo** monthly | **Free Forever Plan**: Free for up to 4 team members, up to 5 projects per team, unlimited test runs, and unlimited mock requests. | REST, GraphQL, WebSockets, gRPC, SSE | All-in-one platform unifying automated API testing, interactive visual documentation, smart mocking, and contract validation. |
| **🛡️ [Kreya](https://kreya.app/)** | **Independent Indie Dev** *(Bootstrapped, Solo-entity)* | **$4.17/month** *(Pro, billed annually at $50/yr)* | **Free Forever Plan**: 1 user, unlimited gRPC/REST/GraphQL/WebSockets over HTTP/2 & HTTP/3, local storage only, request history limited to latest request. *(10-day full-feature trial for Pro)* | gRPC, REST, GraphQL, WebSockets, SSE | Privacy-first desktop client with deep native gRPC features, protobuf reflection, client streaming, and Windows named pipes. |

---

## 🟩 Open-Source Software Tools

Community-driven, self-hostable, and offline-first open-source API clients. The table and detailed list below are sorted in **descending order by GitHub stargazers**:

| Tool | GitHub_Stars | License | Primary Tech Stack | REST | gRPC | WebSockets | GraphQL | MQTT | Architecture / Type |
| :--- | :---: | :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| **[Hoppscotch](#1-hoppscotch)** | [![GitHub_Stars](https://img.shields.io/github/stars/hoppscotch/hoppscotch?style=social&color=white)](https://github.com/hoppscotch/hoppscotch/stargazers) | MIT | TypeScript, Vue.js | ✅ | ❌ | ✅ | ✅ | ✅ | Web / PWA / Desktop / Self-Hostable |
| **[Bruno](#2-bruno)** | [![GitHub_Stars](https://img.shields.io/github/stars/usebruno/bruno?style=social&color=white)](https://github.com/usebruno/bruno/stargazers) | MIT | JS, Electron | ✅ | ✅ | ✅ | ✅ | ❌ | Git-native Local Desktop App |
| **[Insomnia (Core)](#3-kong-insomnia)** | [![GitHub_Stars](https://img.shields.io/github/stars/Kong/insomnia?style=social&color=white)](https://github.com/Kong/insomnia/stargazers) | Apache-2.0 | Electron, React | ✅ | ✅ | ✅ | ✅ | ❌ | Desktop App with Cloud/Git Sync |
| **[Yaak](#4-yaak)** | [![GitHub_Stars](https://img.shields.io/github/stars/mountain-loop/yaak?style=social&color=white)](https://github.com/mountain-loop/yaak/stargazers) | MIT (Source) | Tauri, Rust, React | ✅ | ✅ | ✅ | ✅ | ❌ | Ultra-fast Local Desktop Client |
| **[grpcurl](#5-grpcurl)** | [![GitHub_Stars](https://img.shields.io/github/stars/fullstorydev/grpcurl?style=social&color=white)](https://github.com/fullstorydev/grpcurl/stargazers) | MIT | Go | ❌ | ✅ | ❌ | ❌ | ❌ | CLI "cURL for gRPC" |
| **[BloomRPC](#6-bloomrpc)** | [![GitHub_Stars](https://img.shields.io/github/stars/bloomrpc/bloomrpc?style=social&color=white)](https://github.com/bloomrpc/bloomrpc/stargazers) | GPL-3.0 | TypeScript, Electron | ❌ | ✅ | ❌ | ❌ | ❌ | GUI Client for gRPC Services |
| **[grpcui](#7-grpcui)** | [![GitHub_Stars](https://img.shields.io/github/stars/fullstorydev/grpcui?style=social&color=white)](https://github.com/fullstorydev/grpcui/stargazers) | MIT | Go | ❌ | ✅ | ❌ | ❌ | ❌ | Interactive Web UI for gRPC Servers |
| **[API Dash](#8-api-dash)** | [![GitHub_Stars](https://img.shields.io/github/stars/foss42/apidash?style=social&color=white)](https://github.com/foss42/apidash/stargazers) | Apache-2.0 | Dart, Flutter | ✅ | ❌ | ✅ | ❌ | ❌ | Beautiful Cross-Platform Desktop UI |
| **[Restfox](#9-restfox)** | [![GitHub_Stars](https://img.shields.io/github/stars/flawiddsouza/Restfox?style=social&color=white)](https://github.com/flawiddsouza/Restfox/stargazers) | MIT | Vue.js | ✅ | ❌ | ✅ | ❌ | ❌ | Lightweight Offline Web & Desktop Client |
| **[Step CI](#10-step-ci)** | [![GitHub_Stars](https://img.shields.io/github/stars/stepci/stepci?style=social&color=white)](https://github.com/stepci/stepci/stargazers) | Apache-2.0 | TypeScript, Node.js | ✅ | ✅ | ✅ | ✅ | ❌ | Declarative Multi-Protocol Automated Testing |
| **[Milkman](#11-milkman)** | [![GitHub_Stars](https://img.shields.io/github/stars/warmuuh/milkman?style=social&color=white)](https://github.com/warmuuh/milkman/stargazers) | Apache-2.0 | Java, JavaFX | ✅ | ✅ | ✅ | ✅ | ❌ | Extensible Plugin-based Workbench |
| **[Warthog](#12-warthog)** | [![GitHub_Stars](https://img.shields.io/github/stars/Forest33/warthog?style=social&color=white)](https://github.com/Forest33/warthog/stargazers) | Apache-2.0 | Go, Wails | ❌ | ✅ | ❌ | ❌ | ❌ | Dedicated Cross-Platform gRPC GUI |
| **[OneOpen Postkid](#13-oneopen-postkid)** | [![GitHub_Stars](https://img.shields.io/badge/PyPI-postkid-blue?style=social&color=white)](https://pypi.org/project/oneopen-postkid/) | Open Source | Python, Flet | ✅ | ❌ | ✅ | ✅ | ✅ | Pure-Python Local-First API Client |

---

### Detailed Profiles

### 1. Hoppscotch
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/hoppscotch/hoppscotch?style=social&color=white)](https://github.com/hoppscotch/hoppscotch/stargazers)
- **🛠️ Stack:** TypeScript / Vue.js | **📜 License:** MIT
- **📝 Overview:** Hoppscotch is the most popular open-source API request client on GitHub. It features a modern web-first interface alongside desktop packages, a command-line interface, and self-hosted instances. It provides out-of-the-box support for REST, GraphQL, WebSockets, Server-Sent Events (SSE), Socket.IO, and MQTT.
- **🎯 Best for:** Developers who want an instant web-accessible client with broad protocol support including MQTT and Socket.IO.

### 2. Bruno
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/usebruno/bruno?style=social&color=white)](https://github.com/usebruno/bruno/stargazers)
- **🛠️ Stack:** JavaScript / Electron | **📜 License:** MIT
- **📝 Overview:** Bruno reimagines API testing with a Git-friendly, offline-first philosophy. Instead of saving data into proprietary clouds, Bruno saves requests in your repository as plain-text files using the `.bru` markup format. Collections can be version-controlled, diffed, and merged using standard Git workflows.
- **🎯 Best for:** Teams requiring pure local privacy and Git collaboration without vendor cloud lock-in.

### 3. Kong Insomnia
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/Kong/insomnia?style=social&color=white)](https://github.com/Kong/insomnia/stargazers)
- **🛠️ Stack:** Electron / React | **📜 License:** Apache-2.0
- **📝 Overview:** Insomnia is a widely adopted desktop development client providing robust GraphQL schema autocompletion, REST execution, WebSockets, and gRPC support with reflection. It offers end-to-end encrypted project synchronization and local scratchpad capabilities.
- **🎯 Best for:** Developers needing schema-driven GraphQL workflows coupled with gRPC in an established GUI.

### 4. Yaak
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/mountain-loop/yaak?style=social&color=white)](https://github.com/mountain-loop/yaak/stargazers)
- **🛠️ Stack:** Tauri / Rust / React | **📜 License:** MIT (Source code) / Commercial (Pre-built Binaries)
- **📝 Overview:** Created by the original author of Insomnia, Yaak is engineered for maximum speed, low memory overhead, and absolute privacy. Built with Rust and Tauri, Yaak operates entirely offline without telemetry or account requirements.
- **🎯 Best for:** Developers seeking an ultra-responsive native desktop client with complete offline privacy.

### 5. grpcurl
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/fullstorydev/grpcurl?style=social&color=white)](https://github.com/fullstorydev/grpcurl/stargazers)
- **🛠️ Stack:** Go | **📜 License:** MIT
- **📝 Overview:** `grpcurl` is the industry-standard command-line tool for interacting with gRPC servers, effectively functioning as cURL for protobuf services. It dynamically inspects servers with reflection and accepts JSON payloads.
- **🎯 Best for:** DevOps engineers, CLI-centric developers, automated shell scripts, and terminal debugging.

### 6. BloomRPC
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/bloomrpc/bloomrpc?style=social&color=white)](https://github.com/bloomrpc/bloomrpc/stargazers)
- **🛠️ Stack:** TypeScript / Electron | **📜 License:** GPL-3.0
- **📝 Overview:** BloomRPC provided one of the earliest dedicated graphical desktop interfaces for gRPC, offering proto file imports, TLS authentication, and streaming call visualization.
- **🎯 Best for:** Quick visual exploration of local proto files and standalone gRPC calls.

### 7. grpcui
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/fullstorydev/grpcui?style=social&color=white)](https://github.com/fullstorydev/grpcui/stargazers)
- **🛠️ Stack:** Go | **📜 License:** MIT
- **📝 Overview:** From the creators of `grpcurl`, `grpcui` spawns an interactive web application that lets developers test gRPC services in a browser via an intuitive form-based interface.
- **🎯 Best for:** Testing gRPC endpoints interactively in a browser without installing dedicated desktop software.

### 8. API Dash
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/foss42/apidash?style=social&color=white)](https://github.com/foss42/apidash/stargazers)
- **🛠️ Stack:** Dart / Flutter | **📜 License:** Apache-2.0
- **📝 Overview:** API Dash is an open-source, lightweight alternative to Postman built with Flutter. It focuses on clean UI design, fast startup times, offline-first execution, and code generation across various programming languages.
- **🎯 Best for:** Developers who want an aesthetically clean, lightweight desktop API client without Electron bloat.

### 9. Restfox
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/flawiddsouza/Restfox?style=social&color=white)](https://github.com/flawiddsouza/Restfox/stargazers)
- **🛠️ Stack:** Vue.js | **📜 License:** MIT
- **📝 Overview:** Restfox is a minimalist, offline-first HTTP and WebSocket client. It runs in the web browser, as an offline desktop utility, or as an embedded component within web systems.
- **🎯 Best for:** Zero-install browser testing and lightweight HTTP/WebSocket requests.

### 10. Step CI
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/stepci/stepci?style=social&color=white)](https://github.com/stepci/stepci/stargazers)
- **🛠️ Stack:** TypeScript / Node.js | **📜 License:** Apache-2.0
- **📝 Overview:** Step CI is an open-source framework for declarative multi-protocol API testing and contract monitoring. It supports REST, GraphQL, gRPC, and WebSockets through simple YAML/JSON test definitions that execute in CI/CD pipelines.
- **🎯 Best for:** Automated testing, multi-step API regression workflows, and CI/CD quality gates.

### 11. Milkman
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/warmuuh/milkman?style=social&color=white)](https://github.com/warmuuh/milkman/stargazers)
- **🛠️ Stack:** Java / JavaFX | **📜 License:** Apache-2.0
- **📝 Overview:** Milkman is an extensible workbench crafted for craftspeople. With an architecture inspired by IDEs, it supports plugins for REST, gRPC, WebSockets, JDBC SQL, Cassandra, and message queues.
- **🎯 Best for:** Polyglot developers who want a single workbench for APIs, database queries, and messaging protocols.

### 12. Warthog
- **GitHub**: [![GitHub_Stars](https://img.shields.io/github/stars/Forest33/warthog?style=social&color=white)](https://github.com/Forest33/warthog/stargazers)
- **🛠️ Stack:** Go / Wails | **📜 License:** Apache-2.0
- **📝 Overview:** Warthog is a cross-platform desktop gRPC client providing server reflection schema inspection, proto parsing, multi-workspace environments, and streaming invocation.
- **🎯 Best for:** Dedicated gRPC developers requiring a fast, lightweight native GUI.

### 13. OneOpen Postkid
- **Package**: [![PyPI](https://img.shields.io/badge/PyPI-oneopen--postkid-blue?style=social&color=white)](https://pypi.org/project/oneopen-postkid/)
- **🛠️ Stack:** Python / Flet | **📜 License:** Open Source
- **📝 Overview:** OneOpen Postkid is a local-first, pure-Python desktop API client supporting HTTP, GraphQL, WebSockets, MQTT, and SOAP. It allows developers to author test scripts in native Python.
- **🎯 Best for:** Python developers desiring an extensible, local-first API client scriptable in Python.

---

## 🤝 Contributing

Contributions are warmly welcomed! If you know of an outstanding open-source or multi-protocol API client that should be featured:

1. Fork this repository.
2. Add your tool with a short description, tech stack, license, and GitHub repository link.
3. Submit a pull request!

Please review our community guidelines:
- Multi-protocol capabilities (REST, GraphQL, gRPC, WebSockets, MQTT, etc.).
- Active maintenance (updates within the last 12 months).
- Clear licensing and documentation.

---

## 💖 Support

If you find this repository valuable for your daily development workflow, please consider supporting the project:

- ⭐ **Star this repository** to help other developers discover it!
- 🍴 **Fork and share** with your teammates and community.
- ☕ **Buy a coffee & sponsor ongoing maintenance:**  
  👉 **[Support on GitHub Sponsors](https://github.com/sponsors/ishandutta2007)**

Your support helps keep this curated directory continuously updated and maintained!

---

## 📈 Star History

[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Multi-Protocol-API-Client-GRPC-Websockets-Rest&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Multi-Protocol-API-Client-GRPC-Websockets-Rest&type=date&legend=top-left)

---

## 📄 License

This collection is distributed under the [CC0 1.0 Universal](LICENSE) (Public Domain Dedication).  
Individual tools and platforms maintain their respective licenses and terms of service.
