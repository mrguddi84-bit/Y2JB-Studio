<div align="center">

<img src="assets/y2jb-studio-banner.png" alt="Y2JB Studio — FTP Manager, Y2JB Manager and Theme Manager" width="100%">

# Y2JB Studio

### One workspace. Three managers. Your Y2JB workflow.

**Check · Download · Install · Build · Upload**  
A streamlined Y2JB workflow for Windows: simplified FTP and Y2JB Autoloader installation, plus a Theme Manager for icons, backgrounds and app names.

[![Version](https://img.shields.io/badge/version-1.0-00cfe8?style=for-the-badge)](https://github.com/mrguddi84-bit/Y2JB-Studio/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows-18283c?style=for-the-badge)](https://github.com/mrguddi84-bit/Y2JB-Studio)
[![Languages](https://img.shields.io/badge/languages-5-18283c?style=for-the-badge)](#-five-interface-languages)

[**Download Y2JB Studio v1.0**](https://github.com/mrguddi84-bit/Y2JB-Studio/releases/latest) · [Quick start](#-quick-start) · [Features](#-features) · [Credits](#-credits--acknowledgements)

**Language:** English · [Deutsch](README.de.md) · [Español](README.es.md) · [Français](README.fr.md) · [Português](README.pt.md)

</div>

---

## ✨ Meet Y2JB Studio

Y2JB Studio simplifies the Y2JB setup workflow in one Windows app: guided FTP and Y2JB Autoloader installation, plus a Theme Manager for PS5 icons, backgrounds and app names.

| FTP Manager | Y2JB Manager | Theme Manager |
| --- | --- | --- |
| Detect FTP availability, download supported payloads and set up access. | Check Y2JB prerequisites, fetch the required files and guide their transfer. | Create themes from PNG artwork, build and upload them, and edit supported app names. |
| **Detect · Download · Install · Connect** | **Check · Download · Transfer · Update** | **Create · Build · Upload · Rename** |

> Y2JB Studio is an independent utility for the Y2JB workflow and theme creation. It is not affiliated with, endorsed by or sponsored by Sony Interactive Entertainment.

## 🚀 Features

### 📊 Dashboard — connection and readiness at a glance

The Dashboard brings the console connection and manager diagnostics together:

- Show PS5 connection status and check whether an FTP service is reachable.
- Check that the configured ELF Loader endpoint responds on port **9021**.
- Run read-only checks for Y2JB target folders, required icon files and icon protection status.
- Show diagnostics for Theme Manager transfer readiness and app-name database prerequisites.
- Check whether `app.db` and `appinfo.db` are available before a supported name-editing workflow.
- View readiness status for FTP Manager, Y2JB Manager and Theme Manager in one place.

Connection and readiness checks are diagnostics; they do not intentionally change PS5 files.

### 🌐 FTP Manager — guided setup for external payloads

FTP Manager checks for an available FTP service and guides you through setup and file transfers.

- Discover whether FTP is already reachable on the PS5.
- Download supported FTP payloads such as [**ftpsrv**](https://github.com/ps5-payload-dev/ftpsrv) or [**zftpd**](https://github.com/seregonwar/zftpd) from their upstream projects/releases when needed. **Neither payload is bundled with Y2JB Studio.**
- Guide the supported transfer/setup workflow so a payload can be made available through the PS5 Payload Manager.
- Connect and transfer files after an FTP service is running.

The ELF Loader and an FTP server are separate services. For first-time FTP setup, Y2JB Studio can use the reachable ELF Loader to help start a supported payload; the payload itself is downloaded when needed.

### ⚙️ Y2JB Manager — installation and updates

- Detect the console region and select matching Y2JB files.
- Download required files and check their SHA-256 hashes.
- Guide guarded FTP transfers to the intended PS5 locations.
- Check the YouTube/Y2JB setup and guide the simplified installation or update of the itsPLK Y2JB Autoloader.
- The YouTube PKG workflow through **Prospero Manager** was successfully tested by the project owner.
- Edit the Y2JB application name with the integrated editor and backup safeguards.

### 🎨 Theme Manager — create, build, upload and rename

Choose your artwork, enter the names you want and use the manager actions:

- Select PNG icon and background artwork from your folders.
- Convert and build a Y2JB-compatible theme package.
- Save, reopen, import and organize projects in the local Theme Library.
- Upload supported theme files to the PS5 over FTP.
- Edit supported Y2JB app names using the backup workflow.

### ⚡ Built around button-driven workflows

| You choose | Y2JB Studio handles |
| --- | --- |
| Check / Connect | PS5 connection and FTP diagnostics |
| FTP setup | Supported payload download and guided setup / transfer |
| Y2JB setup | Region checks, file downloads, SHA-256 verification and guarded FTP deployment |
| PNGs and Build | Theme conversion and package creation |
| Upload | FTP transfer to the configured PS5 |
| A new app name | Supported name editing with backup safeguards |

### 🌍 Five interface languages

Deutsch · English · Español · Français · Português

Choose a language from the app's language selector. Y2JB Studio keeps the selected interface language for later launches.

## 📦 Requirements

Before starting, you need:

- A **Windows PC**.
- A **jailbroken PS5** with **ELF Loader (elfldr) reachable on port 9021**.

Connect the PC and PS5 to a network where they can reach each other. Y2JB Studio can download and set up the additional supported FTP and Y2JB components through its managers. Internet access is needed for downloads.

## ⚡ Quick start

1. Download **Y2JB_Studio_v1.0_Portable.exe** from [GitHub Releases](https://github.com/mrguddi84-bit/Y2JB-Studio/releases/latest).
2. Run the portable EXE on Windows; no installer is required.
3. Enter your PS5 IP address in the Dashboard and run the connection/readiness checks.
4. Open **FTP Manager** to check for FTP or follow its guided payload setup.
5. Open **Y2JB Manager** to check the region, fetch required files and follow the guided install/update workflow.
6. Open **Theme Manager** to create a theme from PNGs, build it and upload it over FTP.

Back up important console data before making changes. Review the target and confirmation prompts before a transfer or database edit.

## 🛡️ Safety and network

FTP traffic is unencrypted. Use a trusted local network and check the PS5 address before transferring files. Diagnostic checks are read-only; setup actions, transfers and app-name edits can change console data. Keep backups before using the app-name editor.

## 🤝 Credits & acknowledgements

Y2JB Studio is developed by **MrGee with AI assistance**.

Thanks to the projects and contributors whose work supports the app's workflows:

| Project / contributors | Contribution |
| --- | --- |
| [itsPLK](https://github.com/itsPLK/ps5-y2jb-autoloader) | Y2JB Autoloader used by the Y2JB workflow |
| [ftpsrv contributors](https://github.com/ps5-payload-dev/ftpsrv) | External PS5 FTP payload; downloaded when needed, not bundled |
| [Seregon and zftpd contributors](https://github.com/seregonwar/zftpd) | External PS5 FTP payload; downloaded when needed, not bundled |
| TheWizWikii / PS5-Stuff | YouTube PKG source links used by the app |
| Qt for Python, Python, Pillow, ispc_texcomp, certifi, Tcl/Tk and PyInstaller contributors | Frameworks, runtime and packaging components |

See [CREDITS.md](CREDITS.md) and [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md) for acknowledgements and notices. Third-party components remain under their respective licenses. See [LICENSE](LICENSE) for the Y2JB Studio license notice.

## 📄 Release files and verification

The public repository contains the README, documentation and banner; it does not contain application source code. The portable app is distributed as the release download. Its SHA-256 checksum is listed in [RELEASE_CHECKSUMS.txt](RELEASE_CHECKSUMS.txt).

## 📣 Releases and support

- [Download releases](https://github.com/mrguddi84-bit/Y2JB-Studio/releases)
- [Report an issue or request a feature](https://github.com/mrguddi84-bit/Y2JB-Studio/issues)

When reporting a bug, include the Studio version, Windows version, affected manager and steps to reproduce. Do not publish console credentials or private network details.

---

<div align="center">

**Built for the Y2JB community**  
Y2JB Studio v1.0 · Developed by MrGee with AI assistance

[Releases](https://github.com/mrguddi84-bit/Y2JB-Studio/releases) · [Issues](https://github.com/mrguddi84-bit/Y2JB-Studio/issues) · [Back to top](#y2jb-studio)

</div>


