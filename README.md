# RefactorIQ — Releases

> **Beta** — this software is not fully verified or tested and may have
> problems. Use at your own risk.

RefactorIQ turns technical debt into measurable engineering economics:
hours, cost, priority, trends, and reports. Native desktop app for
**Windows** and **Linux**.

This repo hosts release binaries only. (Source code is private.)

## Download

Latest release: **v0.1.10** ([GitHub](https://github.com/ImineAmazigh/refactoriq-releases/releases/tag/v0.1.10) · [GitLab](https://gitlab.com/AmazighImine/refactoriq-releases/-/releases/v0.1.10))

| File | Platform | Size |
|---|---|---|
| `RefactorIQ_0.1.0_x64-setup.exe` | Windows 10/11 (NSIS installer) | ~4.8 MB |
| `RefactorIQ_0.1.0_amd64.AppImage` | Linux (portable, any distro) | ~98 MB |
| `RefactorIQ_0.1.0_amd64.deb` | Debian / Ubuntu | ~8.2 MB |
| `RefactorIQ-0.1.0-1.x86_64.rpm` | Fedora / RHEL | ~8.2 MB |

Get them from the **Releases** page on either forge:

- GitHub: <https://github.com/ImineAmazigh/refactoriq-releases/releases>
- GitLab: <https://gitlab.com/AmazighImine/refactoriq-releases/-/releases>

> Note: file names carry the app version (`0.1.0`) while the release tag
> (`v0.1.10`) marks the build. Same binaries on both forges.

## Install

**Windows** — run `RefactorIQ_0.1.0_x64-setup.exe` and follow the wizard.
WebView2 is required (preinstalled on Windows 11 / recent Windows 10).
This build is unsigned, so SmartScreen may warn: *More info → Run anyway*.

**Debian / Ubuntu** — `sudo apt install ./RefactorIQ_0.1.0_amd64.deb`
(pulls in `libwebkit2gtk-4.1-0` automatically).

**Fedora / RHEL** — `sudo dnf install ./RefactorIQ-0.1.0-1.x86_64.rpm`

**AppImage** — `chmod +x RefactorIQ_0.1.0_amd64.AppImage && ./RefactorIQ_0.1.0_amd64.AppImage`
(Some distros need FUSE first: `sudo apt install libfuse2`.)

## Notes

- **v0.1.10 is an unsigned build**: install manually as above. It has no
  auto-updater feed; in-app updates arrive with the next signed release.
- Older versions stay available on the Releases pages above.
