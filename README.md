# Database

VB6 department-details viewer bound to a Microsoft Access database via the legacy Data control, DAO 3.5, DBGrid, and DBList. The main form ("Wee Department details") switches department option buttons (WEE, MEE, Support, Aviation, Operations) and shows billet / rank / surname fields from the `DEPTLIST` table in `WEReg.mdb`. Ships with a sample Northwind.mdb alongside the forms.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Database.vbp`) | VB6 | WinForms exe | Access-bound department details UI |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Database.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Microsoft DAO 3.5 Object Library
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `DBGRID32.OCX`
  - `dblist32.ocx`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Database`.
Company names in project files: Chips, Bits and Bytes.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
