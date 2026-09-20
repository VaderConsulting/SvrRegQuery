# SvrRegQuery

VB6 multi-target registry query (`SvrRegQry.exe`): connects to listed servers via `RegConnectRegistry`, queries/creates/writes HKLM keys (e.g. McAfee key lists), with import/export of targets and results. Open `SvrRegQry.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SvrRegQuery` (`SvrRegQry.vbp`) | VB6 | WinForms exe | Query/set registry keys across target servers |
