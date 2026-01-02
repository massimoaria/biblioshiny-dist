# Biblioshiny for Desktop (macOS and Windows)

Welcome to the official distribution repository for the desktop version of Biblioshiny. This version is a standalone Electron application available for **macOS** (Apple Silicon M1/M2/M3/M4) and **Windows x64**.

## 🚀 Key Advantages

- **Zero Configuration**: No need to install R or Pandoc separately. Everything is bundled inside the app.
- **Fully Isolated**: The app uses its own internal R 4.5.2 engine and library, ensuring no conflicts with other R versions on your system.
- **Biblio AI Ready**: Pre-configured to support the latest AI-driven features of Bibliometrix 5.2+.
- **Integrated Reporting**: Built-in Pandoc 3.8.3 for high-quality automated reports and screenshots.

## 📥 Installation

### macOS
1. Navigate to the [Releases](../../releases) page
2. Download the appropriate `.pkg` installer:
   - `Biblioshiny-5.2.1-arm64.pkg` for Apple Silicon (M1/M2/M3/M4)
3. Double-click the installer and follow the macOS setup prompts
4. Launch Biblioshiny from your Applications folder

### Windows
1. Navigate to the [Releases](../../releases) page
2. Download the Windows x64 `.exe` installer (e.g., `Biblioshiny-Setup-5.2.1-x64.exe`)
3. Run the installer and follow the setup wizard
4. Launch Biblioshiny from the Start menu or desktop shortcut

**Note**: On the first launch, the app might take 10-15 seconds to initialize the internal Biblio AI environment.

## 🔄 Automatic Updates

Biblioshiny includes a built-in update checker:
- When a new version is uploaded to this repository, you will receive a notification upon launching the app
- Clicking "Download Now" will take you directly to the latest release page to grab the new installer

## 🛠 Troubleshooting

### Disconnected from Server (Gray Screen)
If the app suddenly turns gray, the internal R process may have encountered an error.
- **Solution**: Restart the application. Ensure you are not running other processes on port 3838.

### Missing Packages Error
While we strive for a 100% complete library, if you see a "Missing Packages" message, please ensure you have an active internet connection on the first run so Bibliometrix can initialize its AI modules.

### Platform-Specific Issues

**macOS**: If the app won't open due to security settings, go to System Preferences > Privacy & Security and authorize the app to open.

**Windows**: If Windows Defender blocks the installation, select "More info" and then "Run anyway". The application is safe but may not yet be recognized by all antivirus systems.

## 📄 Citation

If you use this software for your research, please cite:

Aria, M. & Cuccurullo, C. (2017) bibliometrix: An R-tool for comprehensive science mapping analysis, *Journal of Informetrics*, 11(4), pp 959-975.

## 📞 Support

For bugs, feature requests, or questions, please open an [Issue](../../issues) in this repository.
