# Forge downloads

Forge is a native desktop coding harness. This page provides the published desktop builds.

## Current release: v0.1.0

- [Windows 10/11, x64 installer](https://github.com/ArnabAdhikar/Forge_Harness/releases/download/v0.1.0/Forge-Setup-0.1.0-x64.exe) — installs for your user; no administrator access required.
- [Linux, x86_64 archive](https://github.com/ArnabAdhikar/Forge_Harness/releases/download/v0.1.0/Forge-Linux-x64.tar.gz) — extract it, then run `bash packaging/install-linux.sh` from the extracted directory. The installer places Forge under `~/.local` and preserves Forge data when uninstalled.

SHA-256 checksums:

- Windows: `18cebd51192bab344ef35203ca768a4142750ad392323264bdb3042ae5d550fd`
- Linux: `96dbf74595908025cefd6040120e3beb5742dff60a2e4e9836f5bb7beffa8f42`

Linux requires GTK 3, WebKitGTK 4.1, libsoup 3, and the X11 or Wayland runtime libraries. Package names vary by distribution.

Forge needs a provider API key, a running local model server, or separately installed command-line agents, depending on which agents you use.

Future builds will be listed under [Releases](https://github.com/ArnabAdhikar/Forge-Downloads/releases).
