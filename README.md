# Y2JB Studio v1.0

![Y2JB Studio banner](assets/y2jb-studio-banner.png)

**All-in-one PS5 Homebrew Manager for Windows**  
Portable single-file app · Developed by **MrGee with AI assistance**

**Languages:** Deutsch · English · Español · Français · Português

Y2JB Studio brings PS5 connection tools, FTP workflows, Y2JB management and theme creation together in one Windows application.

## Features

### Dashboard
View PS5 connection diagnostics and the status of FTP and ELF Loader services. Use the dashboard to check the configured console connection before starting a transfer.

### FTP Manager
Manage the FTP connection and start the FTP payload workflow for the console. The app includes the zftpd payload; ftpsrv can also be obtained from its project or through a compatible payload manager.

### Y2JB Manager
Detect the console region, download the matching Y2JB files, and verify downloads with SHA-256 checks. Guarded FTP transfer steps help prevent sending files to the wrong target. The Y2JB application name editor includes backup safeguards.

### Theme Manager
Create Y2JB themes from PNG artwork, organize projects in the project library, and transfer theme files over FTP.

### YouTube PKG workflow
The project owner has successfully tested YouTube PKG installation through Prospero Manager.

## Requirements

- Windows 10 or Windows 11.
- A compatible PS5 homebrew environment.
- A reachable PS5 FTP service for console transfers.
- An ELF Loader or compatible payload launcher for workflows that need it.
- Internet access for downloading external assets.

The FTP connection is unencrypted. Use a trusted local network.

## Quick start

1. Download **Y2JB_Studio_v1.0_Portable.exe** from [Releases](https://github.com/mrguddi84-bit/Y2JB-Studio/releases/latest).
2. Run the portable EXE on Windows; no installer is required.
3. Enter your PS5 IP address in the Dashboard and check the connection status.
4. Open FTP Manager, Y2JB Manager or Theme Manager for the task you want to perform.
5. Confirm the target console and region, and keep backups before changing console files.

For the optional ftpsrv payload, see [ps5-payload-dev/ftpsrv](https://github.com/ps5-payload-dev/ftpsrv).

## Release files and verification

The repository contains the public documentation and banner. The portable application is distributed as the single release asset. Its SHA-256 checksum is recorded in [RELEASE_CHECKSUMS.txt](RELEASE_CHECKSUMS.txt).

## Credits and licenses

See [CREDITS.md](CREDITS.md) for acknowledgements and [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md) for third-party component notices. The application is proprietary; third-party components retain their own licenses. See [LICENSE](LICENSE).

This is an independent homebrew project and is not affiliated with or endorsed by Sony Interactive Entertainment. PlayStation and PS5 are trademarks of their respective owners.
