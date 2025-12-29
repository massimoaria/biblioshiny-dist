# Biblioshiny for Desktop (macOS Apple Silicon/Intel)
Welcome to the official distribution repository for the desktop version of Biblioshiny. This version is a standalone Electron application designed specifically for macOS Apple Silicon (M1, M2, M3, M4) and macOS Intel.

## 🚀 Key Advantages
Zero Configuration: No need to install R or Pandoc separately. Everything is bundled inside the app.

Fully Isolated: The app uses its own internal R 4.5.2 engine and library, ensuring no conflicts with other R versions on your system.

Biblio AI Ready: Pre-configured to support the latest AI-driven features of Bibliometrix 5.2+.

Integrated Reporting: Built-in Pandoc 3.8.3 for high-quality automated reports and screenshots.

## 📥 Installation
Navigate to the Releases page.

Download the latest .pkg installer (e.g., Biblioshiny-5.2.1-arm64.pkg).

Double-click the installer and follow the macOS setup prompts.

Launch Biblioshiny from your Applications folder.

Note: On the first launch, the app might take 10-15 seconds to initialize the internal Biblio AI environment.

## 🔄 Automatic Updates
Biblioshiny includes a built-in update checker.

When a new version is uploaded to this repository, you will receive a notification upon launching the app.

Clicking "Download Now" will take you directly to the latest release page to grab the new installer.

## 🛠 Troubleshooting
### Disconnected from Server (Gray Screen)
If the app suddenly turns gray, the internal R process may have encountered an error.

Solution: Restart the application. Ensure you are not running other processes on port 3838.

### Missing Packages Error
While we strive for a 100% complete library, if you see a "Missing Packages" message, please ensure you have an active internet connection on the first run so Bibliometrix can initialize its AI modules.

## 📄 Citation
If you use this software for your research, please cite:

Aria, M. & Cuccurullo, C. (2017) bibliometrix: An R-tool for comprehensive science mapping analysis, Journal of Informetrics, 11(4), pp 959-975.
