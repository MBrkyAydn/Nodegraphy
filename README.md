<div align="center">

# ⚡ NODEGRAPHY
### *Next-Gen Interactive 2D Architecture Engine for IntelliJ IDEA*

**Turn complex Spring Boot architectures into living, interactive node graphs directly inside your IDE.**

[![Status](https://img.shields.io/badge/Status-Coming%20Soon-F59E0B?style=for-the-badge&logo=rocket)](#-availability)
[![IDE Compatibility](https://img.shields.io/badge/IntelliJ%20IDEA-2024.2+-0891B2?style=for-the-badge&logo=intellijidea)](#-features)
[![Security](https://img.shields.io/badge/Security-Air--Gapped%20%2F%20100%25%20Offline-10B981?style=for-the-badge&logo=shield)](#-security--privacy)

<br/>

<!-- HERO GIF: Projenin açılışını ve tuvalin yüklenişini gösteren GIF -->
<p align="center">
  <img width="1874" height="955" alt="assetsdemo-hero-launch" src="https://github.com/user-attachments/assets/02870dab-0b1e-4ec9-af79-31e450515de2" />
</p>


</div>

---

## 🌟 Overview

**Nodegraphy** replaces static class diagrams with an Unreal Engine Blueprint / ComfyUI inspired canvas right inside JetBrains IntelliJ IDEA. 

Powered by IntelliJ's internal **AST / PSI** engine and hardware-accelerated **JCEF**, it dynamically tracks classes, method-level invocations, HTTP endpoints, and field injections with 60 FPS fluidity.

---

## ⚡ Key Highlights & Visual Tour

### 1. 🔄 Real-Time Live Sync & Bi-directional Navigation
> *Edit code, inject beans, or switch files — watch your architectural graph adapt instantly without compiling or reloading.*

* **Zero-Lag Reactivity:** Instant AST-based graph mutation as you type in the editor.
* **Jump-to-Source:** Click any node header, method socket, or connector line to jump straight to the source code line.
* **HTTP Endpoint Badges:** Live tags (`[GET]`, `[POST]`, `[PUT]`, `[DELETE]`) and request paths mapped directly onto controller sockets.

<div align="center">

<img width="1872" height="955" alt="assetsdemo-live-coding" src="https://github.com/user-attachments/assets/32079fc8-6806-4290-a50b-52e2f7dc7639" />

</div>

---

### 2. 🎯 1-Hop Focus Mode & Architecture Theming
> *Deep-dive into individual components without losing sight of the upstream and downstream flow.*

* **Smart Call Hierarchy:** Inbound callers (`Controllers`, `Services`) automatically dock on the **LEFT**, while outbound dependencies (`Repositories`, `Models`) flow to the **RIGHT**.
* **Anti-Tangling & Multi-Column Layout:** Prevents vertical line-spaghetti by intelligently organizing sockets and ports.
* **Color Themes & Layer Legends:** Effortlessly toggle visibility for Entities/DTOs and customize accent palettes via the built-in color engine.

<div align="center">
<img width="1917" height="1028" alt="assetsdemo-focus-theming" src="https://github.com/user-attachments/assets/898dc054-bdd4-42b4-8bdb-74d88e1e8eba" />

</div>

---

## 🧩 Semantic Stereotype Palette

Nodegraphy recognizes standard Spring Boot roles out-of-the-box:

| Layer / Role | Stereotype Markers | Visual Theme | Description |
| :--- | :--- | :--- | :--- |
| **Controller** | `@RestController`, `@Controller` | 🟣 **Purple** | HTTP entrypoints & REST routes |
| **Service** | `@Service` | 🔵 **Cyan / Blue** | Business logic & transaction managers |
| **Component** | `@Component`, `@Configuration` | 🟠 **Amber / Red** | Mappers, clients, and custom beans |
| **Repository** | `@Repository`, Spring Data JPA | 🟢 **Emerald** | Database interfaces & persistence |
| **Model / POJO** | Entities, DTOs, Records | ⚪ **Slate Gray** | Core domain objects & schemas |

---

## 🔒 Security & Privacy (Enterprise-Grade)

- 🛡️ **100% Air-Gapped & Offline:** No external API requests, no telemetry, no analytics.
- ⚡ **Local JVM Execution:** All AST parsing runs strictly inside your IDE process.
- 🏢 **Corporate Compliant:** Safe for classified, proprietary, and strictly governed enterprise codebases.

---

## 🚀 Availability

Nodegraphy is currently undergoing final quality assurance in preparation for submission to the **JetBrains Marketplace**.

* 🔔 **Stay Tuned:** Public distribution will be available through the IntelliJ IDEA Marketplace.
* ⭐ **Support the Project:** Star this repository to get notified the moment v1.0 goes live!

---

<div align="center">

<sub>Copyright © 2026 Mert Berkay Aydın. All rights reserved.</sub>  
<sub>Nodegraphy is proprietary software. Reverse engineering or unauthorized distribution is strictly prohibited.</sub>

</div>
