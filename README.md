<div align="center">
  <h1>Inkwell</h1>
  <p>A focused note-taking app with integrated drawing support.</p>
  <p>
    <a href="https://github.com/tenorio-labs/inkwell-releases/releases/latest">
      <img alt="Latest Release" src="https://img.shields.io/github/v/release/tenorio-labs/inkwell-releases?style=flat-square&color=black">
    </a>
    <img alt="macOS" src="https://img.shields.io/badge/macOS-supported-black?style=flat-square&logo=apple">
    <img alt="Windows" src="https://img.shields.io/badge/Windows-supported-black?style=flat-square&logo=windows">
  </p>
</div>

---

## Installation

### macOS

**Via Homebrew (recommended)**

```sh
brew install --cask tenorio-labs/tap/inkwell
```

Homebrew automatically downloads the correct version for your Mac (Apple Silicon or Intel).

> **Note:** Inkwell is not yet notarized with Apple. On first launch, macOS will show a security warning.
>
> **To open the app:**
> 1. Right-click (or Control-click) `Inkwell.app` → **Open**
> 2. Click **Open** in the dialog
>
> Alternatively, run this once in Terminal:
> ```sh
> sudo xattr -dr com.apple.quarantine /Applications/Inkwell.app
> ```

**Direct download**

Download the correct `.dmg` for your Mac from the [latest release](https://github.com/tenorio-labs/inkwell-releases/releases/latest):

| Mac | File |
|---|---|
| Apple Silicon (M1, M2, M3, M4) | `Inkwell_x.x.x_aarch64.dmg` |
| Intel | `Inkwell_x.x.x_x64.dmg` |

Follow the same steps above to open the app after installation.

---

### Windows

**Via winget (recommended)**

```sh
winget install TenorioLabs.Inkwell
```

> **Note:** Inkwell is not yet code-signed. Windows SmartScreen may show a warning on first run.
>
> **To install:**
> 1. Click **More info** in the SmartScreen dialog
> 2. Click **Run anyway**
>
> This warning disappears as the app builds reputation over time.

**Direct download**

Download the `.msi` installer from the [latest release](https://github.com/tenorio-labs/inkwell-releases/releases/latest).

---

## System Requirements

| Platform | Minimum |
|---|---|
| macOS (Apple Silicon) | macOS 11 Big Sur or later |
| macOS (Intel) | macOS 10.15 Catalina or later |
| Windows | Windows 10 (64-bit) or later |

## Releases

All release notes and downloads are available on the [Releases](https://github.com/tenorio-labs/inkwell-releases/releases) page.

## Issues & Feedback

Found a bug or have a suggestion? [Open an issue](https://github.com/tenorio-labs/inkwell-releases/issues).

## Built with

- [Tauri](https://tauri.app) — Desktop framework
- [Excalidraw](https://excalidraw.com) — Drawing canvas
- [React](https://react.dev) — UI framework
