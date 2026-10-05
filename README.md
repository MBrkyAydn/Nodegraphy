<img width="1872" height="955" alt="NodeGraphy (2)" src="https://github.com/user-attachments/assets/48a7f377-fd84-4f70-9ce4-08a82d9498ff" />
<img width="1917" height="1028" alt="NodeGraphy (1)" src="https://github.com/user-attachments/assets/c03492cc-fd91-4ffc-943f-f6f8f7745de7" />
[# ⚡ Nodegraphy

> **Real-time Interactive 2D Architecture Graph Visualizer for IntelliJ IDEA**

[![Status](https://img.shields.io/badge/Status-Early%20Access-blue.svg)](../../releases)
[![Compatibility](https://img.shields.io/badge/IntelliJ%20IDEA-2024.2+-orange.svg)](https://www.jetbrains.com/idea/)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](#-license)

Nodegraphy brings a modern, game-engine-inspired node graph experience (similar to Unreal Engine Blueprints and ComfyUI) directly into JetBrains IntelliJ IDEA.

It analyzes Java and Spring Boot projects in real-time using IntelliJ's native AST / PSI (Program Structure Interface) engine and renders an interactive, hardware-accelerated 2D architecture canvas via embedded JCEF.

---

## ✨ Key Features

### 🎯 1-Hop Focus Mode
Dynamically centers the active Java class from your editor:
* **Inbound Callers ("Who is calling me?"):** Places callers (Controllers, Services, Mappers) hierarchically on the **LEFT**.
* **Outbound Dependencies ("What do I call?"):** Places injected dependencies, repositories, and models on the **RIGHT**.
* **Multi-Column Distribution:** Automatically wraps large dependency sets into balanced columns to prevent vertical clutter.

![1-Hop Focus Demo](assets/demo-

---

### 🌐 Whole Project Architecture Mode
* **Dagre / Sugiyama 2D Hierarchical Layout:** Ranks classes topologically from left to right based on real method invocations and field injections.
* **Anti-Crossing & Strict Flow:** Preserves source-to-target orientation to eliminate tangled or reverse-looping lines.
* **Masonry Grid for Standalone Classes:** Neatly organizes independent DTOs, utilities, and models in a clean grid beneath the main graph.

![Whole Project Demo](assets/demo-project.gif)

---

### 🎨 Semantic Stereotypes & Theme Customization
Spring Boot roles are automatically color-coded for instant visual recognition:
* 🟣 **Controller:** `@RestController`, `@Controller`
* 🔵 **Service:** `@Service`
* 🟢 **Repository:** `@Repository`, Spring Data JPA interfaces
* 🟡 **Component:** `@Component`, `@Configuration`, external clients
* ⚪ **POJO / Model:** Entities, DTOs, records, request/response models

*Includes a **Layer Legend** to toggle roles on/off and a **Theme Drawer** to customize accent colors.*

![Customization Demo](assets/demo-customization.gif)

---

### 🚀 Developer-Centric Capabilities
* **HTTP Endpoint Badges:** View `[GET]`, `[POST]`, `[PUT]`, `[DELETE]` badges and route paths directly on method sockets.
* **Bi-directional Navigation:** Click any node, method, or port in the canvas to jump directly to that exact line in the code editor.
* **Compact Mode:** Collapse inactive methods on large classes to eliminate visual noise.
* **100% Offline & Secure (Air-Gapped):** Zero external API calls, zero telemetry, zero analytics. AST analysis runs entirely within your local JVM.

---

## 📦 Installation (Early Access / Beta)

Nodegraphy is currently in early distribution before its official JetBrains Marketplace launch.

1. Download the latest `nodegraphy-1.0.0.zip` from the [Releases](../../releases) section.
2. Open IntelliJ IDEA.
3. Go to **Settings** (`Ctrl+Alt+S` on Windows/Linux or `Cmd+,` on macOS) -> **Plugins**.
4. Click the gear icon (⚙️) next to the "Installed" tab and select **"Install Plugin from Disk..."**.
5. Select the downloaded `nodegraphy-1.0.0.zip` file.
6. Restart IntelliJ IDEA when prompted.
7. You will find the **Nodegraphy** tool window icon on the right sidebar.

---

## 💡 Quick Start

1. Open any Java / Spring Boot project in IntelliJ IDEA.
2. Click the **Nodegraphy** tab on the right tool window stripe.
3. Open any Java class in the editor — the graph updates instantly.
4. **Canvas Navigation:**
   * **Pan:** Click and drag on empty canvas space.
   * **Zoom:** Mouse wheel or touchpad pinch.
   * **Rearrange:** Drag nodes freely at 60 FPS.
   * **Jump to Code:** Click on any method socket or class header.

---

## 🐛 Feedback & Issue Reporting

Found a bug or have a feature request? Please submit an issue via the [GitHub Issue Tracker](../../issues).

---

## 📄 License
Copyright © 2026 Mert Berkay Aydın. All rights reserved.

Nodegraphy is proprietary and closed-source software. The binaries provided in releases are free for individual and commercial evaluation. Reverse engineering, decompilation, redistribution, or unauthorized reuse of the plugin binaries or public documentation assets is strictly prohibited without explicit written permission.](https://img.shields.io/badge/License-Proprietary-red.svg)](#-license))
