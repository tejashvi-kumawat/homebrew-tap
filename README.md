# tejashvi-kumawat/homebrew-tap

Homebrew packages for [Document Studio](https://github.com/tejashvi-kumawat/DocumentStudio).

## Install

```bash
brew tap tejashvi-kumawat/tap
```

| Platform | Command |
| --- | --- |
| **macOS** | `brew install --cask document-studio` |
| **Linux** | `brew install document-studio` |
| **Windows** | Use **winget** (see below) — Homebrew cannot install Windows GUI `.exe` apps |

One-shot (no prior tap):

```bash
# macOS
brew install --cask tejashvi-kumawat/tap/document-studio
# Linux
brew install tejashvi-kumawat/tap/document-studio
```

## Upgrade

```bash
brew update
brew upgrade --cask document-studio   # macOS
brew upgrade document-studio          # Linux
```

## Windows

Homebrew Casks are for macOS application bundles, and this tap’s Linux formula installs the `.deb`.  
There is **no supported Homebrew path for the Windows Setup.exe**.

On Windows, install with:

```powershell
winget install DocumentStudio.DocumentStudio
```

(Available after the package is merged into [microsoft/winget-pkgs](https://github.com/microsoft/winget-pkgs). Until then, download `DocumentStudio-*-Setup.exe` from [GitHub Releases](https://github.com/tejashvi-kumawat/DocumentStudio/releases).)

## Docs

https://tejashvi-kumawat.github.io/DocumentStudio/#/install
