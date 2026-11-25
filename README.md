# GesSnap Feedback

Welcome to the official public feedback repository for **GesSnap**, a native macOS window management and mouse/trackpad gesture utility. Use GitHub Issues to report bugs, performance issues, or share feature requests.

> **Note**: GesSnap is closed-source software. This repository is used strictly for public issue tracking and user feedback.

---

## Quick Links

- 🌐 **Official Website**: [gessnap.com](https://gessnap.com)
- 📦 **Download & Releases**: [Download v0.1.0](https://gessnap.com/en/download/) · [GitHub Releases](https://github.com/ByteFluffy/gessnap-feedback/releases/latest)
- 📖 **Setup & Permissions Guide**: [Setup & Permissions](https://gessnap.com/en/guide/)
- 📝 **Changelog**: [Changelog](https://gessnap.com/en/changelog/)
- 🐛 **Report a Bug**: [New Bug Report](https://github.com/ByteFluffy/gessnap-feedback/issues/new?template=bug_report.yml)
- 💡 **Request a Feature**: [New Feature Request](https://github.com/ByteFluffy/gessnap-feedback/issues/new?template=feature_request.yml)
- ❓ **Ask a Question**: [Ask a Question](https://github.com/ByteFluffy/gessnap-feedback/issues/new?template=question.yml)
- 📧 **Email Support**: [support@gessnap.com](mailto:support@gessnap.com)

---

## Quick Troubleshooting

- **First launch ("damaged" or "unidentified developer")**: Early builds use ad-hoc signing (not notarized yet). Open GesSnap via **System Settings → Privacy & Security → Open Anyway**, or run `xattr -cr /Applications/GesSnap.app` in Terminal. See the [Setup & Permissions Guide](https://gessnap.com/en/guide/) for details.
- **Gestures or snapping stop working after an update**: Remove or toggle off GesSnap in **System Settings → Privacy & Security → Accessibility**, re-add or re-enable it, and relaunch GesSnap.

---

## Before Opening an Issue

1. **Search existing issues first**: Check whether a similar bug or request has already been reported, and add a reaction (👍) or extra context there.
2. **Keep one topic per issue**: Avoid mixing unrelated bugs or requests in a single thread.
3. **Include basic environment details**:
   - GesSnap version and build number (for example, `0.1.0 (52)`, visible at the bottom of the Settings sidebar or in App Info)
   - macOS version and Mac chip (`Apple Silicon` / `Intel`)
   - Accessibility permission status and display setup (single built-in display / notch / multi-display)
   - Attach screenshots or a short screen recording when reporting window snapping or gesture issues (issues are public — please blur or avoid including sensitive personal information)

---

## Privacy, Terms & Security

- [Privacy Policy](https://gessnap.com/en/privacy/)
- [Terms of Use](https://gessnap.com/en/terms/)
- [Security Policy](./SECURITY.md) — please report security or privacy vulnerabilities privately to [support@gessnap.com](mailto:support@gessnap.com) instead of opening a public issue.
