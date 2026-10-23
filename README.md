# Forge downloads

Forge is a native desktop coding harness. This repository contains release downloads; the source repository is maintained separately.

## Downloads

Open [Releases](https://github.com/ArnabAdhikar/Forge-Downloads/releases) and download the asset for your platform:

- **Windows 10/11, x64:** `Forge-Setup-<version>-x64.exe`. Run the installer; it installs for your user and does not require administrator access.
- **Linux, x86_64:** `Forge-Linux-x64.tar.gz`. Extract it, then run `bash packaging/install-linux.sh` from the extracted directory. The installer places Forge under `~/.local` and preserves your Forge data when uninstalled.

Linux requires GTK 3, WebKitGTK 4.1, libsoup 3, and the X11 or Wayland runtime libraries. Package names vary by distribution.

Forge needs a provider API key, a running local model server, or separately installed command-line agents, depending on which agents you use.

## Source

The Forge source code is maintained in [Forge_Harness](https://github.com/ArnabAdhikar/Forge_Harness).
