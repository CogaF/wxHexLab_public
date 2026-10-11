# wxHexLab

A hex editor for Windows, built with wxWidgets 3.3.3.

| | |
|---|---|
| **Platform** | Windows, 64-bit |
| **Built with** | wxWidgets 3.3.3 |
| **Source code** | Private (this repository contains the program only) |
| **Language file** | Italian (`wxHexLab data/language-it.xml`) |

## Which folder do I use?

Each folder is a complete, self-contained copy of the program. Use **one** of them.

| Folder | What it contains | Choose it if |
|---|---|---|
| `x64/Release/` | One standalone `wxHexLab.exe` | you want the simplest option |
| `x64/Release_DLL/` | A smaller `wxHexLab.exe` plus the wxWidgets DLLs | you prefer shared libraries |

Keep everything in the folder together: the `.exe`, the `wxHexLab data` folder and, in `Release_DLL/`, all the
`.dll` files.

To get the files, use **Code > Download ZIP** on this page, or clone the repository.

## Verify your download

The program is not code-signed, so Windows SmartScreen may show a warning the first time you run it. Before
running, check that the file matches the published checksum in `SHA256SUMS.txt`.

PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 ".\x64\Release\wxHexLab.exe"
```

Compare the result with the line for that file in `SHA256SUMS.txt`. On Linux or macOS use
`sha256sum -c SHA256SUMS.txt` from the repository folder.

## Back up your files

A hex editor changes files byte by byte. Keep a copy of any file you edit.

## Third-party components

The program uses wxWidgets under the wxWindows Library Licence, listed in
[THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).

## Terms

No license file is included yet. Until one is added, all rights are reserved by the author.

## Support

Questions and problem reports: please open an issue in this repository.
