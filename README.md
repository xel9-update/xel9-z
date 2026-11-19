# XEL9-Z

**Secure. Compress. Protect.**

Fast compression, safe keeping in a vault. XEL9-Z is a file compression app for Windows, macOS and Linux. It opens almost any archive you receive (zip, 7z, rar, alz/egg and more), and keeps your sensitive files in **XEL9 Vault (`.x9z`)**, its own encrypted format. Without the password, nobody can see what is inside, not even the file names.

This is the **official download repository** for XEL9-Z. It holds only the installers and in-app update packages; there is no source code here.

![XEL9-Z extract screen](https://raw.githubusercontent.com/wiki/xel9-update/xel9-z/images/extract.png)

- Website: https://www.xel9.com
- User guide: **[XEL9-Z Wiki](../../wiki)**
- Release notes: [Releases](../../releases)

## Download

These links always point to the newest release.

| System | Download |
|---|---|
| Windows 10/11 (64-bit) | [Installer (.exe)](../../releases/latest/download/XEL9-Z_x64-setup.exe) · [MSI package](../../releases/latest/download/XEL9-Z_x64_en-US.msi) |
| macOS 11 or later (Apple silicon and Intel) | [Disk image (.dmg)](../../releases/latest/download/XEL9-Z_universal.dmg) |
| Linux (64-bit) | [AppImage](../../releases/latest/download/XEL9-Z_amd64.AppImage) · [.deb](../../releases/latest/download/XEL9-Z_amd64.deb) · [.rpm](../../releases/latest/download/XEL9-Z.x86_64.rpm) |
| Command-line tool only | [Windows](../../releases/latest/download/xel9-z-cli-windows-x86_64.zip) · [macOS](../../releases/latest/download/xel9-z-cli-macos-universal.zip) · [Linux](../../releases/latest/download/xel9-z-cli-linux-x86_64.tar.gz) |

Which file to pick, and how to check that a download is intact, is explained in [Installation and Updates](../../wiki/Installation-and-Updates) on the wiki.

## User guide

The full guide is on the wiki.

| Wiki page | What it covers |
|---|---|
| [Installation and Updates](../../wiki/Installation-and-Updates) | Which file to download, in-app updates, installing over the old version, downloading safely |
| [Desktop App Guide](../../wiki/Desktop-App-Guide) | Compressing, extracting, managing vaults, settings and the right-click menu, with screenshots |
| [Command-Line Guide](../../wiki/Command-Line-Guide) | The `x9z` command with examples |

## Features

- **A vault that encrypts file names too:** not just the contents but file names, sizes and folder structure are hidden. Every password guess costs a lot of memory, which makes mass guessing hard.
- **Opens almost any archive you receive:** zip, 7z, rar, alz/egg, the tar family, and disk images such as ISO and DMG. The format is recognized by content, not by extension.
- **Dangerous archives are stopped:** paths that escape the target folder, zip bombs and unsafe links are caught before anything is written.
- **Desktop app (GUI) and command line (CLI):** a desktop app you use with the mouse, plus the `x9z` command for scripts and servers.
- **No ads, no upsell:** there are no ads in the app and no prompts to upgrade or pay.
- **Everything stays on your computer:** the app never connects to the internet unless you turn on update checks.

## Download safely

- Get XEL9-Z **only from this repository or https://www.xel9.com**.
- In-app updates are checked against the public key built into the app and are not installed if the signature does not match.
- To report a security problem, use the contact details on the website.

## Terms of use

> Anyone, including individuals, companies, schools and public institutions, may install and use XEL9-Z freely without asking for permission.

> XEL9-Z is provided as is. The developer is not responsible for data loss or any other problem that arises from using it. Keep backups of important files.

© 2026 XEL9 by 1Pixel Inc. You are free to use it, but you may not modify, redistribute or sell it without permission from 1Pixel Inc. Licenses of the open-source components used in the app are listed under Settings → About → **Third-party licenses**.
