# dev-config
Setup and configure development enviroments

Default Powershell Path: "C:\Program Files\PowerShell\7\pwsh.exe"

Based on the Scott Hanselmann article/video
https://www.hanselman.com/blog/my-ultimate-powershell-prompt-with-oh-my-posh-and-the-windows-terminal

Requires:
https://github.com/devblackops/Terminal-Icons (Updated to install in Powershell_profile.ps1)

Powershell
        Get-Help <pws command>

Update-Module <module-name>
Install-Module <module-name>

1. Download/install new platform ignostic powershell (Version 7+)
2. Download/install font "Cascadia Code" from nerdfonts.com
3. Customize a powershell profile -> json config
4. Create a powershell profile
        scripts\Microsoft.Powershell_profile.ps1
4a. Copy Update Microsoft.Powershell_profile.ps1 to C:\Users\<user>\Documents\Powershell folder.
5. Install Oh-My-Posh
6. Install github-cli
        winget install Github.cli --source winget
7. Setup environment variable to point to OMP themese
        at C:\@Code\dev-config\OMP