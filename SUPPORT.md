# Support — Easy Mac Archiver / Mcrar

- **Questions and bug reports:** https://github.com/noneym/Mcrar/issues
- **Finder right-click entries not visible?** Open the app once from Applications. If they still do not appear, enable them in System Settings; the two editions use different mechanisms, so the setting lives in different places:
  - **GitHub edition (Mcrar, Finder Quick Actions):** System Settings → General → Login Items & Extensions → Extensions → Finder, then turn on the Mcrar actions. On macOS 13–14: System Settings → Privacy & Security → Extensions → Finder.
  - **App Store edition (Easy Mac Archiver, app services):** System Settings → Keyboard → Keyboard Shortcuts… → Services → Files and Folders.
- **"Permission to use the folder" prompt (App Store edition):** macOS sandboxing requires you to allow access to folders outside Downloads once. Choose your home folder in Settings → *Allow Home Folder…* to stop being asked.
- **Creating RAR archives:** RAR compression is proprietary to RARLAB. The App Store edition opens and extracts RAR archives but creates ZIP, 7z and TAR instead. The GitHub edition can create RAR if you install RARLAB's "RAR for macOS" yourself.
