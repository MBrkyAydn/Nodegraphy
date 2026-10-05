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
  <img src="assets/demo-hero-launch.gif" alt="Nodegraphy Launch Preview" width="95%" style="border-radius: 12px; box-shadow: 0 8px 30px rgba(0,0,0,0.5);" />
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
  <!-- 2. GIF: Sol tarafta kod yazılırken sağda anlık güncellenen Nodegraphy canlı akışı -->
  <img src="assets/demo-live-coding.gif" alt="Live Code Sync Demo" width="95%" style="border-radius: 8px; border: 1px solid #2d3748;" />
</div>

---

### 2. 🎯 1-Hop Focus Mode & Architecture Theming
> *Deep-dive into individual components without losing sight of the upstream and downstream flow.*

* **Smart Call Hierarchy:** Inbound callers (`Controllers`, `Services`) automatically dock on the **LEFT**, while outbound dependencies (`Repositories`, `Models`) flow to the **RIGHT**.
* **Anti-Tangling & Multi-Column Layout:** Prevents vertical line-spaghetti by intelligently organizing sockets and ports.
* **Color Themes & Layer Legends:** Effortlessly toggle visibility for Entities/DTOs and customize accent palettes via the built-in color engine.

<div align="center">
  <!-- 3. GIF: Task, TaskService odaklanması, soket bağlantıları ve renk/tema ayarları -->
  <img src="assets/demo-focus-theming.gif" alt="Focus Mode & Theming Demo" width="95%" style="border-radius: 8px; border: 1px solid #2d3748;" />
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
