
# Emulator Forensics Tool (EFT)

This repository contains partial source code for the Emulator Forensics Tool (EFT), developed to support the Emulator Forensics Investigation Model (EFIM). EFT is designed to detect Android emulator environments (e.g., Bluestacks, NoxPlayer, Waydroid) and extract forensic artifacts from mounted disk images (e.g., VDI, VHD, VHDX, VMDK). EFT_Emulator-Forensic-Tool The EFT software has the functionality to detect and analyze emulators on Microsoft Windows operating systems.
Kindly contact sensedat34@gmail.com.

## Project Structure

```
EFT_Tool_Source/
├── Models/
│   ├── Tum_Dosyalar_Boyut.cs
│   ├── Tum_Dosyalar_List.cs
│   ├── Sanalmakine_Boyut.cs
│   ├── Sanalmakine_List.cs
│   └── DirectoryDetail.cs
├── Helpers/
│   ├── DirectoryHelper.cs
│   ├── ProgressBarWidthConverter.cs
│   └── DateTimeColumnConverter.cs
├── Views/
│   └── Sanal_Makine_Yolları_Treeview.cs
├── Startup/
│   └── Yetikilendirmeli_Baslangic.cs
```

## About

- **Purpose**: Facilitates emulator detection and artifact analysis in forensic disk images.
- **Technology Stack**: Developed in C# (.NET Framework 4.8), XAML for UI.
- **Note**: Only non-sensitive visual and functional modules are included. Core analysis logic, encryption/decryption routines, and platform-specific modules are not disclosed.

## Usage

These modules support:
- Directory size visualization
- Virtual disk structure parsing
- TreeView-based emulator directory representation
- SQLite file viewer and converter integration

## Disclaimer

This is a partial academic release to fulfill reproducibility requirements. The full source, including encryption handling, advanced analysis modules, and cross-platform support, remains proprietary.

## Authors

- Sedat ŞEN — [EFIM Author], PhD Candidate, Forensic Sciences
- Harun ARTUNER — Assoc. Prof., Computer Engineering

## Related Publication

The complete study and findings are available in the manuscript submitted to *IEEE Access* (2025).

