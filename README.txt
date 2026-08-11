Trust Main Wallet — iPhone 11 Pro Max optimized

The app is sized to the iPhone 11 Pro Max CSS viewport (414 × 896) and uses
the full viewport when installed to the iPhone Home Screen.

Key deployment details:
- Root entry point is index.html (not index.html.html).
- viewport-fit=cover is enabled.
- iOS safe-area insets are handled with env(safe-area-inset-*).
- The app fills the screen in standalone/PWA mode with no centered mock-phone frame.
- On desktop screens 600px and wider, a true 414 × 896 preview is retained.
