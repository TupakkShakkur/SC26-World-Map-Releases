# SC26 World Map Releases

Public binary-only distribution channel. Windows installers are unsigned; normal Windows UAC, SmartScreen and endpoint protections apply. Installation-test prereleases are not production qualification.

## Current installation-test build

[Download SC26-World-Map-Setup-1.0.5.exe](https://github.com/TupakkShakkur/SC26-World-Map-Releases/releases/download/v1.0.5-install-test.5/SC26-World-Map-Setup-1.0.5.exe)

Immutable prerelease: `v1.0.5-install-test.5`. The actual Setup EXE passed temporary extraction and SHA-256 verification of all eleven embedded assets on the authorized Windows 11 development computer. Exact-source CI and independent review passed. The public EXE and checksum were downloaded anonymously and verified.

SHA-256: `1d47ec6b6c74eb13721631a990d1fa51f883da62df70563156eaeb0cbbedd229`

Windows 10 installation, ordinary-user shortcut launch, show-PC acceptance and full native lifecycle qualification remain NOT RUN. Extraction validation is not installation acceptance.

## Known failed installer

Do not use **v1.0.4-install-test.4** for installation. Its `SC26-World-Map-Setup-1.0.4.exe` fails during Preparing to Install because its embedded bootstrap table omits `WorldMapDeployment.ps1`. SHA-256: `052df787943bda361d7314145de4391206947f78775094b21055a724ad56e845`.

The immutable release and original installer are retained for historical evidence. Version 1.0.5 corrects the embedded-file mapping.

The mini PC's partial legacy installation requires separately qualified, specifically authorized recovery before another supervised installation. Do not delete protected folders, change ACLs or disable security protections as a workaround. Caspio activation is not required to install or open Connections & Setup.