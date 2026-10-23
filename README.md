# SC26 World Map Releases

Public binary-only distribution channel. Windows installers are unsigned; normal Windows UAC, SmartScreen and endpoint protections apply. Installation-test prereleases are not production qualification.

## Known failed installer

Do not use **v1.0.4-install-test.4** for installation. Its `SC26-World-Map-Setup-1.0.4.exe` fails during Preparing to Install because its embedded bootstrap table omits `WorldMapDeployment.ps1`. SHA-256: `052df787943bda361d7314145de4391206947f78775094b21055a724ad56e845`.

The immutable release and original installer are retained for historical evidence. A corrected 1.0.5 installation-test build is being validated; it is not yet available. Installation and launch acceptance on the Windows 10 mini PC remain pending.

The mini PC's partial legacy installation requires separately qualified, specifically authorized recovery before another supervised installation. Do not delete protected folders, change ACLs or disable security protections as a workaround. Caspio activation is not required to install or open Connections & Setup.