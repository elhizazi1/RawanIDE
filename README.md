<div align="center">

<a href="https://rawanide.elhizazi.me"><img src="app_icon_original.png" alt="RawanIDE icon" width="100" /></a>

# RawanIDE

### Your Android. Your Workspace. Your IDE.

**Build, edit, run, and preview projects — right from Android.**

<img src="assets/typing-banner.svg" alt="Code. Build. Preview. Anywhere." width="760" />

<p>
<a href="https://github.com/elhizazi1/RawanIDE/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/elhizazi1/RawanIDE?style=for-the-badge&color=19b9ad&label=Release" /></a>
<img alt="Android 8.0+" src="https://img.shields.io/badge/Android-8.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
<img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-Android-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
<a href="https://github.com/elhizazi1/rawanide-extension-sdk"><img alt="Extension SDK" src="https://img.shields.io/badge/Extension%20SDK-v1.0.0-19b9ad?style=for-the-badge" /></a>
</p>

**[Download APK](https://github.com/elhizazi1/RawanIDE/releases/latest)** · **[Help Center](https://rawanide.elhizazi.me/help)** · **[Extension SDK](https://github.com/elhizazi1/rawanide-extension-sdk)** · **[العربية](README.ar.md)**

<img src="feature_graphic.png" alt="RawanIDE feature graphic" width="100%" />

</div>

---

## ✨ Develop on Android, your way

RawanIDE brings **project navigation, code editing, terminal-assisted development, and an integrated browser preview** into a single workspace on your phone or tablet. Work with local files, explore your code, and test supported web projects without constantly switching between apps.

<table>
<tr>
<td width="50%" valign="top">

### 📁 Project workspace
Create, import, browse, and organize local project folders and source files.

</td>
<td width="50%" valign="top">

### ✍️ Code editing
Edit source files and navigate project structures from the IDE.

</td>
</tr>
<tr>
<td valign="top">

### 💻 Termux integration
Run supported development commands and local servers through a configured Termux environment.

</td>
<td valign="top">

### 🌐 Live web preview
Preview locally served projects in an embedded Android WebView, including supported Vite and Nuxt workflows.

</td>
</tr>
<tr>
<td valign="top">

### 📱 Responsive testing
Switch between phone, tablet, and desktop preview layouts, with a desktop touchpad and cursor controls.

</td>
<td valign="top">

### 🛠 Developer tools
Inspect the preview using console features and Eruda debugging tools.

</td>
</tr>
<tr>
<td valign="top">

### 🌿 Git workflows
Work with repositories and supported version-control operations.

</td>
<td valign="top">

### 🧩 Extensible by design
Explore optional extensions and language packs through the RawanIDE Marketplace.

</td>
</tr>
</table>

> [!NOTE]
> Some workflows depend on separately installed Termux, project dependencies, permissions, optional services, or extensions. Shizuku and Dhizuku are optional integrations; they are not required for basic editing.

## 🔍 Detailed features

The following describes RawanIDE's application capabilities and supported integrations. Availability may depend on the installed build, Android version, configuration, and optional components.

| Area | Capabilities |
| :-- | :-- |
| **Projects and files** | Create, import and browse local projects; manage project files and folders; open external project locations with a safety warning. |
| **Code editor** | Edit project source files; save changes; `.bak` backup and restore workflow; editor diagnostics and optional language-tool integration. |
| **Terminal and Node.js** | Termux-assisted command execution, `npm install` for project dependencies, and development scripts such as `npm run dev`. Node.js/npm are provided by the configured Termux environment, **not** bundled as the Extension SDK. |
| **Web development** | Local development-server workflows for supported Vite/React and Nuxt projects, with in-app browser preview. |
| **Responsive preview** | Phone, Tablet and Desktop layouts; desktop touchpad, configurable pointer appearance and controls. |
| **Preview debugging** | Console panel with copy/select/clear controls and Eruda debugging in supported contexts. |
| **Development tooling** | Git workflows; optional LSP/DAP integration requiring separately configured language servers or debug adapters. |
| **Extensions and languages** | Marketplace browsing, `.r1` extension installation, optional language packs and extension-specific features. |
| **Extension safety** | Package metadata and integrity checks, trust controls, and developer-oriented settings. Exact enforcement depends on the installed version and repository configuration. |
| **Interface and utilities** | Light/dark themes, notification center, project and terminal settings, and optional Shizuku/Dhizuku integration for supported operations. |

> [!NOTE]
> This is an overview, not a guarantee that every experimental or optional feature is enabled in the public APK release. Consult the release notes for version-specific availability.

## 📸 Explore RawanIDE

<div align="center">
<table>
<tr><td align="center"><img src="preview_mockups/01_projects.png" alt="Projects screen" width="260" /><br /><strong>Projects</strong></td><td align="center"><img src="preview_mockups/02_editor.png" alt="Code editor" width="260" /><br /><strong>Editor</strong></td><td align="center"><img src="preview_mockups/03_terminal.png" alt="Terminal" width="260" /><br /><strong>Terminal</strong></td></tr>
<tr><td align="center"><img src="preview_mockups/04_preview.png" alt="Web preview" width="260" /><br /><strong>Live Preview</strong></td><td align="center"><img src="preview_mockups/05_git.png" alt="Git integration" width="260" /><br /><strong>Git</strong></td><td align="center"><img src="preview_mockups/06_marketplace.png" alt="Extension marketplace" width="260" /><br /><strong>Marketplace</strong></td></tr>
</table>
</div>

## 🚀 Download & install

1. Open the **[latest GitHub release](https://github.com/elhizazi1/RawanIDE/releases/latest)**.
2. Download **`RawanIDE-release-signed.apk`** from the release assets.
3. Compare the APK's SHA-256 checksum with the checksum published for that release, if available.
4. Install the APK on a compatible Android device, approving the installation prompt when required.
5. Open RawanIDE and configure the features you intend to use.

**Compatibility:** Android 8.0 (API 26) or later. Optional integrations and development tooling may have additional requirements.

> [!IMPORTANT]
> Download APKs only from releases published by this repository. Review permissions and the trustworthiness of any extensions you install.

## ⚡ Quick start

```text
1. Open RawanIDE
2. Create or import a project
3. Open the editor and browse your files
4. Configure Termux if your project needs a local server
5. Install project dependencies and start the development server
6. Open Live Preview and choose Phone, Tablet, or Desktop mode
```

For full setup instructions, visit the **[Help Center](https://rawanide.elhizazi.me/help)**.

## 🧰 Tools & integrations

| Component | Role | Requirement |
| :-- | :-- | :-- |
| Android WebView | Embedded web preview | Included in the app / device WebView |
| Termux | Local development commands and servers | Separate setup for relevant workflows |
| Eruda | Web debugging | Available in supported preview contexts |
| Git | Repository workflows | Feature support depends on the project setup |
| Shizuku / Dhizuku | Optional privileged integrations | Only for features that use them |
| RawanIDE Marketplace | Extensions and language packs | Optional |

## 🧩 RawanIDE developer ecosystem

**This repository is for the RawanIDE Android APK and its release information.** The developer resources below are separate projects; the SDK npm package is **not** the Android application.

| Project | Purpose | Link |
| :-- | :-- | :-- |
| **RawanIDE Android** | Download and install the Android IDE (APK) | [APK releases](https://github.com/elhizazi1/RawanIDE/releases/latest) |
| **Extension SDK** | Create, validate, and package RawanIDE `.r1` extensions | [GitHub source](https://github.com/elhizazi1/rawanide-extension-sdk) · [npm package](https://www.npmjs.com/package/@elhizazi1/extension-sdk) |
| **RawanIDE Marketplace** | Discover and manage optional extensions and language packs from within RawanIDE | [RawanIDE website](https://rawanide.elhizazi.me/) |
| **Community Repository Template** | Starting point for developers who want to set up a community extension repository | [GitHub template](https://github.com/elhizazi1/rawanide-community-repository-template) |
| **Community Repository — GitHub (live example)** | Example of a community extension repository hosted on GitHub | [Source repository](https://github.com/elhizazi1/jamal-repository) · [Published repository](https://elhizazi1.github.io/jamal-repository/) |
| **Community Repository — GitLab (live example)** | Example of a community extension repository hosted on GitLab | [Source repository](https://gitlab.com/elhizazi1/jamal-repository) · [Published repository](https://jamal-repository-5d923d.gitlab.io/) |

### Install the Extension SDK (developers only)

```bash
npm install @elhizazi1/extension-sdk
```

The command installs the **SDK in a Node.js project**. To install RawanIDE on Android, download the **APK** from this repository's Releases page instead. For SDK usage and compatibility details, consult the [SDK repository](https://github.com/elhizazi1/rawanide-extension-sdk). Community repositories and their extensions remain subject to RawanIDE's marketplace validation and trust rules.

## 📚 Documentation & community

| Resource | Link |
| :-- | :-- |
| 📖 Help Center | [Read the guide](https://rawanide.elhizazi.me/help) |
| ℹ️ About | [About RawanIDE](https://rawanide.elhizazi.me/about) |
| 🔐 Privacy Policy | [Privacy](https://rawanide.elhizazi.me/privacy) |
| 🧩 Marketplace | [Explore extensions](https://rawanide.elhizazi.me/) |
| 📦 Releases | [Download versions](https://github.com/elhizazi1/RawanIDE/releases) |
| 🐞 Issues | [Report a problem](https://github.com/elhizazi1/RawanIDE/issues) |
| 🛠 Extension SDK | [GitHub](https://github.com/elhizazi1/rawanide-extension-sdk) · [npmjs](https://www.npmjs.com/package/@elhizazi1/extension-sdk) |
| 🧱 Community repository template | [GitHub](https://github.com/elhizazi1/rawanide-community-repository-template) |
| 🌍 Arabic README | [README.ar.md](README.ar.md) |

## 🤝 Contributing & feedback

Contributions, bug reports, and constructive feedback are welcome. Read **[CONTRIBUTING.md](CONTRIBUTING.md)** and open an issue describing your Android version, RawanIDE version, reproduction steps, and relevant sanitized logs.

For security-sensitive findings, consult **[SECURITY.md](SECURITY.md)** before disclosing details publicly.

## 🔒 Privacy & security

RawanIDE works with local project files. Optional extensions or integrations may request additional access or communicate with external services. Review the [privacy policy](https://rawanide.elhizazi.me/privacy), grant only the permissions you need, and never share credentials or private project data in issue reports.

## Copyright and distribution

Copyright © 2026 Jamal El Hizazi. All rights reserved. This repository publishes application information and release materials; it is not the complete Android application source repository. The separate Extension SDK has its own license and distribution terms. Third-party software retains its respective licenses.

---

<div align="center">

**Built for creators who develop on Android.**

<sub>RawanIDE · Code. Build. Preview. Anywhere.</sub>

<br /><br />

<a href="https://github.com/elhizazi1/RawanIDE/releases/latest">Download</a> · <a href="https://rawanide.elhizazi.me/help">Docs</a> · <a href="https://github.com/elhizazi1/RawanIDE/issues">Feedback</a>

</div>
