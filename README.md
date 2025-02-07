# Awesome Linux IDEs 
<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![View on GitHub](https://img.shields.io/badge/View%20on-GitHub-181717?logo=github&logoColor=white)](https://github.com/danielrosehill/Awesome-Linux-IDEs)

![Linux IDEs Banner](images/image.png)

A curated list of development environments for Linux distributions, with primary focus on Ubuntu compatibility.

[View Author's Website](https://www.danielrosehill.com) | [Contact](mailto:public@danielrosehill.com)

</div>

## 📋 Table of Contents

- [Awesome Linux IDEs](#awesome-linux-ides)
  - [📋 Table of Contents](#-table-of-contents)
  - [🔍 About](#-about)
    - [Important Notes](#important-notes)
    - [Credits](#credits)
  - [💻 Cross Platform IDEs](#-cross-platform-ides)
    - [Visual Studio Code (VS Code)](#visual-studio-code-vs-code)
    - [Sublime Text](#sublime-text)
    - [Phoenix Code](#phoenix-code)
    - [Apache NetBeans](#apache-netbeans)
    - [Eclipse IDE](#eclipse-ide)
    - [Geany](#geany)
    - [JetBrains IDE Family](#jetbrains-ide-family)
  - [🔧 Language And Project Focused IDEs](#-language-and-project-focused-ides)
    - [KDevelop](#kdevelop)
    - [Wing](#wing)
    - [RStudio Desktop](#rstudio-desktop)
  - [� Kubernetes IDEs And Managers](#-kubernetes-ides-and-managers)
    - [Lens](#lens)
    - [Jet Pilot](#jet-pilot)
  - [🔬 Data \& Science Focused IDEs](#-data--science-focused-ides)
    - [Spyder IDE](#spyder-ide)
    - [Jupyter IDEs](#jupyter-ides)
    - [Arduino IDE](#arduino-ide)
    - [Android Studio](#android-studio)
  - [🎮 Game Development IDEs](#-game-development-ides)
    - [Unity](#unity)
    - [Godot Engine](#godot-engine)
    - [Defold](#defold)
  - [💼 Paid And Commercial IDEs](#-paid-and-commercial-ides)
    - [GNAT Studio](#gnat-studio)
  - [🤖 AI Assisted IDEs](#-ai-assisted-ides)
    - [Cursor](#cursor)
    - [Windsurf Editor (Codeium)](#windsurf-editor-codeium)
    - [Zed](#zed)
  - [🛠 IDE Components And Add-Ons](#-ide-components-and-add-ons)
    - [Code Snippet Managers](#code-snippet-managers)
  - [☁️ Cloud IDEs](#️-cloud-ides)
  - [🤝 Contributing](#-contributing)
  - [📄 License](#-license)
    - [License Terms Summary](#license-terms-summary)

## 🔍 About

### Important Notes

- 📝 Package availability and distro support is subject to ongoing change
- 📝 Distro badges are added when support is confirmed or explicitly stated
- 📝 This list is non-exhaustive and continuously growing

### Credits

- Original list compilation by: [Daniel Rosehill](https://www.danielrosehill.com)
- Markdown badges: [@Ileriayo](https://github.com/Ileriayo/markdown-badges)

## 💻 Cross Platform IDEs

### [Visual Studio Code (VS Code)](https://code.visualstudio.com/download)

The popular, extensible code editor from Microsoft.

**Available Formats:**
- `deb`
- `rpm`
- `tar.gz`
- `Snap`
- `CLI (standalone)`

![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white) ![openSUSE](https://img.shields.io/badge/openSUSE-%2364B345?style=for-the-badge&logo=openSUSE&logoColor=white) ![Fedora](https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white) ![Red Hat](https://img.shields.io/badge/Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white)

### [Sublime Text](https://www.sublimetext.com/docs/linux_repositories.html)

Fast, lightweight text editor with powerful features.

**Available via:**
- `apt`
- `pacman`
- `yum`
- `dnf`
- `zypper`

![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white) ![openSUSE](https://img.shields.io/badge/openSUSE-%2364B345?style=for-the-badge&logo=openSUSE&logoColor=white) ![Fedora](https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white) ![Red Hat](https://img.shields.io/badge/Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white) ![Suse](https://img.shields.io/badge/SUSE-0C322C?style=for-the-badge&logo=SUSE&logoColor=white)

### [Phoenix Code](https://phcode.io/#/home)

Evolution of the Brackets.io project, optimized for web development.

**Linux Support:**
Native binaries for Ubuntu/Debian, Fedora, and Arch

![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white) ![Fedora](https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white)

### [Apache NetBeans](https://netbeans.apache.org/front/main/index.html)

Full-featured IDE with advanced code analysis and refactoring tools.

**Linux Support:** Available as `snap` package

### [Eclipse IDE](https://www.eclipse.org/downloads/packages/)

Extensible IDE platform with rich plugin ecosystem.

**Download Options:**
- [Eclipse Installer](https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2024-03/R/eclipse-inst-jre-linux64.tar.gz)
- [Eclipse Packages](https://www.eclipse.org/downloads/packages/)

### [Geany](https://www.geany.org/)

Lightweight IDE supporting 50+ programming languages.

**Linux Format:** Available as `.tar.gz`

### [JetBrains IDE Family](https://www.jetbrains.com/toolbox-app/)

Professional IDE suite with specialized tools for different languages.

**Requirements:**
- x86_64: glibc 2.17 (Ubuntu 18.04+)
- arm64: glibc 2.29 (Ubuntu 20.04+)
- FUSE support
- Required packages: `libfuse2 libxi6 libxrender1 libxtst6 mesa-utils libfontconfig libgtk-3-bin tar dbus-user-session`

## 🔧 Language And Project Focused IDEs

### [KDevelop](https://kdevelop.org/)

Powerful IDE for C, C++, Python, QML/JavaScript and PHP.

**Linux Support:** Available as Snap package and native packages

### [Wing](https://wingware.com/)

Python-specific IDE with advanced debugging capabilities.

**Available Formats:**
- Ubuntu/Debian package
- RPM package
- `.tar`

### [RStudio Desktop](https://posit.co/download/rstudio-desktop/)

Professional IDE for R programming.

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white) ![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white) ![Fedora](https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white) ![Red Hat](https://img.shields.io/badge/Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white)

## 🐳 Kubernetes IDEs And Managers

### [Lens](https://k8slens.dev/)

The most popular Kubernetes IDE in the world.

**Available Formats:**
- `.deb`
- `.rpm`
- `.snap`
- `.appimage`

### [Jet Pilot](https://www.jet-pilot.app/)

Open-source Kubernetes desktop client focused on speed and usability.

**Linux Support:** Available via [GitHub releases](https://github.com/unxsist/jet-pilot/releases)

## 🔬 Data & Science Focused IDEs

### [Spyder IDE](https://www.spyder-ide.org/)

Scientific Python Development Environment designed for scientists and data analysts.

**Linux Installation:** Available via [Anaconda](https://www.anaconda.com/download/)

### [Jupyter IDEs](https://jupyter.org/install)

Suite of tools for interactive computing and data analysis.

**Products:**
- JupyterLab
- Jupyter Notebook
- Voila

### [Arduino IDE](https://www.arduino.cc/en/software)

Official IDE for Arduino development.

**Available Formats:**
- `.zip`
- `.appimage`

### [Android Studio](https://developer.android.com/studio)

Google's official IDE for Android development with full Linux support.

**Features:**
- Native Linux support
- Gemini AI assistance
- Complete Android development toolkit

## 🎮 Game Development IDEs

### [Unity](https://unity.com/download)

Professional game development platform.

**Supported Distributions:**
- CentOS
- Rocky Linux
- Ubuntu

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white) ![Cent OS](https://img.shields.io/badge/cent%20os-002260?style=for-the-badge&logo=centos&logoColor=F0F0F0) ![Rocky Linux](https://img.shields.io/badge/-Rocky%20Linux-%2310B981?style=for-the-badge&logo=rockylinux&logoColor=white)

### [Godot Engine](https://godotengine.org/download/linux/)

Free, open-source game engine for 2D and 3D development.

**Available Formats:**
- x86_64
- x86
- .NET - Standard (x86_64)

### [Defold](https://defold.com/)

High-performance cross-platform game engine.

**Linux Support:** Ubuntu compatible

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

## 💼 Paid And Commercial IDEs

### [GNAT Studio](https://www.adacore.com/gnatpro/toolsuite/gnatstudio)

Professional IDE with advanced support for Ada, SPARK, C, C++, and Python.

## 🤖 AI Assisted IDEs

### [Cursor](https://www.cursor.com/)

AI-first code editor with integrated AI capabilities.

**Linux Support:** Available as AppImage

### [Windsurf Editor (Codeium)](https://codeium.com/)

Modern AI-powered code editor built on Codeium's AI capabilities.

**Linux Support:**
- Debian/Ubuntu installer
- Universal tarball

![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

### [Zed](https://zed.dev/)

High-performance multiplayer code editor with AI capabilities.

**Linux Support:** Available via Bash installer

## 🛠 IDE Components And Add-Ons

### Code Snippet Managers

- [Codiga](https://www.codiga.io/get-codiga/linux/) - Code snippet manager with AI capabilities
- [massCode](https://masscode.io/download/) - Free and open source snippet manager (available as `snap`)
- [CodeSpace](https://codespace.app/) - Premium snippet manager for Ubuntu

## ☁️ Cloud IDEs

Cloud-hosted development environments that are OS-agnostic by nature.

**Popular Options:**
- GitHub Codespaces
- Browxy
- CodePen

For more online IDEs, see [awesome-online-ide](https://github.com/styfle/awesome-online-ide).

## 🤝 Contributing

To add an IDE with Linux support:
1. Create a pull request
2. Or contact the author via [website](https://www.danielrosehill.com)


## 📄 License

This repository is licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/).

### License Terms Summary

You are free to:
- **Share** — Copy and redistribute the material in any medium or format
- **Adapt** — Remix, transform, and build upon the material for any purpose

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made

---

<div align="center">
<i>Contributions welcome! Please see the contributing guidelines or contact the author.</i>
</div>
