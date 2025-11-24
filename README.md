# Keyscope

<div align="center">
  <img src="https://download.keyscope.dev/logo.png" alt="Keyscope Logo" width="128" height="128">
  <br>
  
  <h1>The Native GUI for Valkey and Redis</h1>
  <p>
    <b>Built for Valkey and Redis</b><br>
    Manage your data, monitor performance, and deploy clusters locally without Docker Desktop.
  </p>

  <p>
    <a href="https://github.com/infradise/keyscope/releases/latest">
      <img src="https://img.shields.io/badge/macOS-gray?logo=apple&style=for-the-badge" alt="macOS"></a>  
    <a href="https://github.com/infradise/keyscope/releases/latest">
      <img src="https://img.shields.io/badge/Windows-blue?logo=windows&style=for-the-badge" alt="Windows"></a>
    <a href="https://github.com/infradise/keyscope/releases/latest">
      <img src="https://img.shields.io/badge/Linux-green?logo=linux&style=for-the-badge" alt="Linux"></a>  
  </p>

  <p>
    <a href="#features">Features</a> •
    <a href="#installation">Installation</a> •
    <a href="#roadmap">Roadmap</a> •
    <a href="https://keyscope.dev">Website</a>
  </p>
</div>

---

## Why Keyscope?

**Keyscope** is not just another Redis GUI client. It is a specialized tool designed to unlock the full potential of **Valkey**. We focus on modern developer experience (DX) and performance.

### Key Features (*Planned*)

* **1-Click Cluster Setup (Docker-less)**
    * Deploy a production-ready **3 Master + 3 Replica** cluster on your local machine in seconds.
    * **No Docker Desktop required.** No complex `docker-compose` files. It just works.
* **Built for Valkey and Redis**
    * Native support for Valkey's new threading model and data structures.
    * Visualized monitoring optimized for Valkey metrics.
* **Native Performance**
    * Built with **Pure Java** and the JetBrains SDK. No web views, no heavy frameworks, and no context switching. It is optimized for speed and minimal resource consumption.
* **Native Look & Feel**
    * We utilize the standard **JetBrains UI components**. Whether you are using the Darkula theme or the new UI, Keyscope blends in perfectly, providing a consistent and comfortable user experience, and an interface designed for long coding sessions.
* **Focus on Essentials**
    * Designed for developers who need to manage Valkey and Redis clusters without leaving their code.

## Supported IDEs

Keyscope is compatible with all IntelliJ Platform-based products (Version 2023.x and later):

* **Android Studio**
* **IntelliJ IDEA** (Community & Ultimate)
* **PyCharm** (Community & Professional)
* PhpStorm, GoLand, WebStorm, CLion, DataGrip, RubyMine, RustRover

> **Note:** This plugin is **NOT** available for VS Code or Eclipse. It is a specialized tool for the JetBrains family.

## Installation

1.  Open your IDE (Android Studio, IntelliJ IDEA, PyCharm, etc.).
2.  Go to **Settings/Preferences** → **Plugins** → **Marketplace**.
3.  Search for **"Keyscope"**.
4.  Click **Install**.

## Roadmap

- [ ] Basic CRUD Operations (Key-Value)
- [ ] **Local Cluster Management (No Docker)**
- [ ] Advanced Performance Monitoring (Real-time graphs)
- [ ] Slow Log & Hot Key Analysis
- [ ] Data Import/Export (JSON, CSV)
- [ ] Team Collaboration Features (Pro)

## Feedback & Support

Found a bug? Please let us know!

* **Bug Report:** [Open an Issue](https://github.com/infradise/keyscope/issues/new?template=bug_report.md)

---

## Legal Notices

© 2025 Infradise Inc. All rights reserved.  

**Keyscope** is a product of Infradise Inc.  

We are **not affiliated with** The Linux Foundation, Redis Ltd., JetBrains s.r.o.  

All other trademarks cited herein are the property of their respective owners.  
For full legal details and a comprehensive list of third-party trademarks, please visit our [Legal Notices](https://keyscope.dev/legal).