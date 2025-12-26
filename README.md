# Biblioshiny Distribution Files

This repository contains binary files for Biblioshiny:

## 📦 R Installers
- `R/R-4.5.1-arm64.pkg` - R for Apple Silicon
- `R/R-4.5.1-x86_64.pkg` - R for Intel Mac

## 🔧 R Portable Archives
Available in [Releases](https://github.com/massimoaria/biblioshiny-dist/releases):
- `R-portable-arm64.tar.gz` - Precompiled R with all packages (arm64)
- `R-portable-x64.tar.gz` - Precompiled R with all packages (x64)

## 📥 Usage

### Download R Installers
```bash
curl -L -O https://github.com/massimoaria/biblioshiny-dist/raw/main/R/R-4.5.1-arm64.pkg
```

### Download R Portable Archives
```bash
curl -L -O https://github.com/massimoaria/biblioshiny-dist/releases/download/r-portable-v1/R-portable-arm64.tar.gz
```

## 📝 Notes

R Portable archives are large files (~400MB) and are distributed via GitHub Releases to avoid repository bloat.
