# Warden for Mac

**Clean your Mac without breaking it.**

Warden frees up space and keeps your Mac tidy — and every clean can be undone.
Nothing is deleted when you clean: items move to Warden's **Vault**, exactly as they were,
and you can put them back for 7 days.

### [⬇ Download Warden for Mac](https://github.com/77neomax/warden-releases/releases/latest/download/Warden.dmg)

macOS 13 Ventura or later · Apple Silicon and Intel · signed and notarized by Apple

---

## What it does

- **Smart Scan** — app caches, logs and build leftovers, with safe choices pre-selected
- **Applications** — uninstall apps completely, including the leftovers they scatter around
- **Clutter** — true duplicate files (byte-for-byte identical) and large forgotten files
- **Space Map** — see what fills your disk, folder by folder
- **System Data** — what's behind macOS's grey "System Data" bar, explained and measured
- **Protection** — what starts at login and who signed it, a malware scan with Apple's own XProtect rules, and a privacy sweep for API keys and credentials left lying around
- **Performance** — live memory and CPU, and the apps using the most — no fake "speed up" buttons
- **Developer** — node_modules, Xcode, Docker, Homebrew and uv caches, local AI models (Hugging Face, Ollama, Whisper, LM Studio) and AI-assistant session history
- **Undelete** — put files back from the Bin exactly where they came from

## Built to be safe

- **Nothing is deleted when you clean.** Everything goes to the Vault and can be restored — all at once or one item at a time.
- **A Guard checks every path** before anything moves, and refuses whenever it isn't sure.
- **Never touched:** anything inside a project or tracked by git, system folders, anything outside your home folder, and Warden itself.
- **Duplicates are not junk:** copies inside projects, builds and backups are intentional, so only your own loose files count.

## Private by design

Warden runs entirely on your Mac. It has no account, no analytics and no tracking.
Its only connection is a once-a-day check for updates (a small file from this page), which you can turn off.
Updates install only if they carry the developer's signature for that exact version.

## Try it, then buy

The **14-day free trial** includes everything. After it, scanning, Protection, Undelete and the Vault stay free —
moving things to the Vault needs a license key. Keys are checked on your Mac, offline.

Licenses: coming soon.

## Install

1. Download **Warden.dmg** and open it.
2. Drag **Warden** into **Applications**.
3. Optional: give Warden **Full Disk Access** (System Settings → Privacy & Security) so it can read the Bin for Undelete and check everything in your Library.

## Verify your download

Each [release](https://github.com/77neomax/warden-releases/releases) lists the SHA-256 checksum. In Terminal:

```
shasum -a 256 ~/Downloads/Warden*.dmg
spctl -a -vv /Applications/Warden.app
```

The second command should show `accepted`, `source=Notarized Developer ID` and
`origin=Developer ID Application: Paulo Barradas (U3YXX23ADX)`.

---

This repository holds Warden's releases and update files only.
© 2026 Paulo Barradas
