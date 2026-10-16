# Rays Connect

A Rust-powered connection app with SOCKS5, system VPN, configurable routing and optional server administration.

**[Website & downloads](https://raysconnect.github.io/rays-connect/)** · **[Latest release](https://github.com/RaysConnect/rays-connect/releases/latest)**

This public repository hosts the download website and versioned application releases. Install a package for your device, import the profile provided by your server administrator, then choose SOCKS or system VPN.

## Packages

- Windows: version 1.1.0, x64 EXE and MSI installers. SOCKS and system VPN verified in bounded live checks. Installers are not Authenticode-signed.
- Other platforms below retain version 0.2.0; Android 1.1.0 is deferred until device testing.

- macOS: Apple Silicon (ARM64), DMG. Ad-hoc signed; not Apple notarized.
- Android: ARM64 APK, Android 7.0 or newer. Release signed.
- Linux: AMD64 and ARM64 DEB packages. Distribution compatibility and test results are recorded in each release.

Download `SHA256SUMS.txt` from the same release to verify package integrity. The website pins each platform to its published release tag, so adding Windows 1.1.0 does not break the older Android, macOS or Linux downloads. Update release.json and the platform links when publishing a newer package.

Rays Connect requires a server profile. Downloads do not include server credentials or a hosted VPN subscription. Network availability and performance depend on the server and transport. Existing live TCP sessions cannot migrate between different servers.

For v0.2.0, SOCKS was verified on macOS ARM64, Android ARM64 and Linux AMD64. Linux ARM64 is build-only and not runtime-tested. VPN testing was skipped on all platforms. See the release notes for the test scope and package requirements.
