# SvrRegQuery

VB6 Server Registry Query (`SvrRegQry.exe`): connects to a list of target servers via `RegConnectRegistry`, then queries, creates, and writes HKLM keys (for example McAfee key lists), with import and export of targets and results. `frmTargets` manages the server list; `RegistryGrip.bas` wraps the registry API. Open `SvrRegQry.vbp` in the VB6 IDE.

**Source last updated:** 2001-06-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SvrRegQuery` (`SvrRegQry.vbp`) | VB6 | WinForms exe | Query/set registry keys across target servers |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `SvrRegQry.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Common Dialog control (COMDLG32.OCX)
- Remote Registry access to the target servers

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/SvrRegQuery`. Project company field: CSC. Sample key and server lists: `McAfee_keys.txt`, `smallsrvs.txt`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
