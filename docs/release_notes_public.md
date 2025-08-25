# Release Notes

All notable changes to CircleCast will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## v1.0.6 - 2025-08-24

### 🐛 Bug Fixes
- **Fixed Update Check Button**: The "Check Now" button in preferences now works properly
  - **Major Fix**: Resolved controller deallocation issue that was preventing button actions
  - Clicking "Check Now" immediately updates the "Last Check" field  
  - Visual feedback shows when update check is in progress
  - Clear success/error messages when check completes
- **Fixed Time Display**: "Last Check" now shows proper relative time ("2 minutes ago" instead of "in 2 minutes")
- **Fixed Version Detection**: App version now properly matches release versions for accurate update checking
- **Fixed Success Messages**: "You're up to date!" now displays as success, not an error

### ⚡ Improvements
- More responsive update checking interface
- Enhanced error handling for network issues
- Extended timeout handling for slower connections
- Better time formatting and user feedback

---

## v1.0.2 - 2025-08-24

### 🚀 New Features
- Complete automated release system now live!
- Sparkle auto-updates with secure EdDSA signatures  
- Public release notes available at our website
- Enhanced download experience via GitHub Pages

### 🐛 Bug Fixes  
- Fixed automatic update system reliability
- Resolved release workflow issues
- Improved download URL consistency

### ✨ Improvements
- Faster, more reliable release process
- Better error handling throughout the app
- Enhanced security with proper code signing

## v1.0.0-fix.1 - 2025-08-24

### 🐛 Bug Fixes
- Fixed automatic update system reliability
- Improved release workflow stability

---

