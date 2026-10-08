# Sarde Studio releases

Installers for Sarde Studio, the desktop authoring app for
[Sarde](https://github.com/getsarde/sarde) sites. Sarde Studio is in early
beta (0.x). Its source code is not public; this repository holds the release
builds and the issue tracker.

## Download

Get the latest version from the
[Releases page](https://github.com/getsarde/sarde-studio-releases/releases/latest).
Each release has builds for:

- Windows (x64)
- macOS (Apple silicon and Intel)
- Linux (x64)

Every installer bundles the Sarde engine, so you don't need to install the
`sarde` CLI separately.

## Updates

Sarde Studio gets new versions from this repository. To update, open
**Settings → About** and select **Check for updates**. When a new version is
available, select **Download & install**, then **Restart now**. Studio
installs an update only if its signature matches the release signing key.

## Report a bug or request a feature

[Open an issue](https://github.com/getsarde/sarde-studio-releases/issues/new)
in this repository. For a bug, include your Studio version and engine version
from **Settings → About**, your operating system, and the steps that
reproduce the problem.

Problems with the generated site itself, such as build errors or theme
output, belong to the engine: report those at
[getsarde/sarde](https://github.com/getsarde/sarde/issues).
