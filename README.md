# 🚀 Microfrontend Template

This project provides a robust and scalable foundation for building microfrontend applications using **React**, bundled together and deployed on a **single port** for seamless integration and performance. 🧩 🌟

---

## 🏗️ Architecture Overview

This project follows the **Module Federation** architecture, comprising:

- 🧞‍♂️ **Host MFE** – Acts as the shell/container that loads and integrates all remote microfrontends.
- 🧱 **Remote MFE 1** – A standalone feature or domain-specific module.
- 🧱 **Remote MFE 2** – Another independent feature or module.

All MFEs are bundled into the host during the build process and **deployed together on a single port** 🚢. This simplifies deployment and avoids CORS/configuration hassles across environments.
