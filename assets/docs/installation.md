# Instalation

No instalation, just go to [Keycap Editor](https://keycapeditor.github.io/)

and begin writing code.

# For Keycap_desktop
Run :
```powershell
powershell -NoProfile -ExecutionPolicy Bypass -Command "Invoke-WebRequest 'https://keycapeditor.github.io/Keycap-desktop/Installer.ps1' -OutFile install.ps1; .\install.ps1"
```
the script will guide you further.
#### Usage :
Open another terminal and run :
```bash
cd Documents
mkdir test_project && cd test_project
echo hello > test.txt
Keycap_desktop ./
```
the editor should open with that **test.txt** file.
