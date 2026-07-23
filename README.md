# Ori Notebook releases

Download and self-update artifacts for [Ori Notebook](https://ori.dorsr.com),
the local-first notebook. Notes are plain Markdown files in a folder you own.

**The friendly download page is [ori.dorsr.com/download](https://ori.dorsr.com/download).**
This repo is the artifact shelf behind it.

## Linux

- [Ori-Notebook-x86_64.AppImage](https://github.com/dor-sr/ori-notebook-releases/releases/latest/download/Ori-Notebook-x86_64.AppImage)
  is the recommended install: one portable file, updates itself from inside the app.
- A `.deb` for Debian and Ubuntu ships with every release under
  [Releases](https://github.com/dor-sr/ori-notebook-releases/releases); it updates by
  installing the newer `.deb`.

## Windows

The clean install path is the **Microsoft Store** listing, which is signed and
updates automatically. It is in certification now; the download page above will
carry the Store link the moment it is live.

`Ori-Notebook-Setup-x64.exe` in the release assets is the app's **self-update
artifact**. It is not code-signed, so a fresh install from it triggers the
Windows SmartScreen warning. Installed copies of Ori Notebook fetch it silently
as an in-app update, which is what it exists for. If you install from it anyway,
that warning is the tradeoff; the Store install will not have it.

## macOS

Not built yet. It follows once the Windows release clears certification.

## Versions and updates

- The version-less asset names above always point at the newest complete release.
- Installed apps check for updates on launch and every few hours, verify the
  update signature, and show a "Restart to update" prompt.
- Found a problem? [Open an issue](https://github.com/dor-sr/ori-notebook-releases/issues).
