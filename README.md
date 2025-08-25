# CircleCast - Public Releases

This repository serves as the **public distribution point** for CircleCast releases and updates.

## 📥 Download CircleCast

### Latest Stable Release
- **Download**: [Latest Stable Release](https://github.com/adamevers/circle-cast-releases/releases/latest)
- **System Requirements**: macOS 13.0 (Ventura) or later

### Beta Releases  
- **Download**: [All Releases](https://github.com/adamevers/circle-cast-releases/releases) (look for "Pre-release" tag)
- **Note**: Beta releases are for testing new features before stable release

## 🔄 Automatic Updates

CircleCast includes built-in automatic update support via Sparkle:

- **Update Feed**: [appcast.xml](https://adamevers.github.io/circle-cast-releases/appcast.xml)
- **Release Notes**: [CircleCast Release Notes](https://adamevers.github.io/circle-cast-releases/)
- **Channel Support**: Beta and Stable channels in single update feed

## 📋 Release Notes

View the latest release notes and version history:
- **Web Version**: [https://adamevers.github.io/circle-cast-releases/](https://adamevers.github.io/circle-cast-releases/)
- **Markdown**: [release_notes_public.md](https://adamevers.github.io/circle-cast-releases/release_notes_public.md)

## 📂 Repository Structure

```
docs/
├── appcast.xml              # Sparkle update feed (unified beta/stable)
├── release_notes_public.md  # Public release notes (markdown)
├── index.html              # Release notes (HTML with styling)
├── releases/               # Download files
│   └── CircleCast-{VERSION}.dmg
└── appcast-archive/        # Historical appcast backups
```

## 🔒 Security & Verification

All releases are:
- ✅ **Code Signed** with Apple Developer ID
- ✅ **Notarized** by Apple for security
- ✅ **Cryptographically Signed** updates via EdDSA signatures
- ✅ **Automatically Distributed** from private source repository

## 🛠️ For Developers

This is the **public distribution repository** for CircleCast. 

- **Source Code**: Private repository (not publicly accessible)
- **CI/CD**: Automated via GitHub Actions from private repo
- **Release Process**: Beta-first strategy with promotion workflow

### Release Channels

**Beta Channel**: New releases for testing
- Users: Early adopters and testers
- Updates: All new versions for validation
- Risk: May contain bugs, use for testing only

**Stable Channel**: Production-ready releases  
- Users: General public and production users
- Updates: Only releases proven stable in beta
- Risk: Low, thoroughly tested releases

## 📞 Support

- **Issues**: Report issues in the main project repository
- **Documentation**: See release notes for feature information
- **Updates**: Automatic via Sparkle, or download manually

---

🤖 This repository is automatically maintained by GitHub Actions
