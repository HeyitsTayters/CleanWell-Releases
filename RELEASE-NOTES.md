# CleanWell 1.0.0 development preview 2

- Renamed the interface, window title, About text, Rust app type, package, executable, and temporary icon directory to CleanWell / `cleanwell`.
- Refreshed the Clean and Optimize screenshots from the renamed release build.
- Updated the macOS bundle to launch the `cleanwell` executable.
- No cleanup or maintenance behavior changes.

Apple Silicon (arm64) only. Download `CleanWell-1.0.0-preview.2-macos-arm64.zip`, extract it, and move CleanWell.app to Applications.

This development build is not notarized or signed with a Developer ID certificate. Release compilation succeeded; tests: 3 passed, 1 ignored. The app was launched to capture both screenshots. Interactive cleanup and maintenance operations were not exercised.

Renaming the application identity may start with default preferences instead of the previous Clearwell preferences. Review your settings and protected paths before cleaning.
