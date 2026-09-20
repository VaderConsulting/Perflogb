# Perflogb

CSC VB6 PerfLogB (`PerfLogB.exe`): batch performance-log extract tool — scans KiXtart/batch `.log` files for Logon Start/Finish, Username, and SiteLoc, writes `c:\temp\PerfLogB.csv`, and charts results. Open `Perflogb.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Perflogb.vbp`) | VB6 | WinForms exe | PerfLogB |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Perflogb.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSCHRT20.OCX`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Perflogb`.
Company names in project files: CSC.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
