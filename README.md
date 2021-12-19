# Windows11Debloater
Debloater for Windows 11


Enable execution of PowerShell scripts:

PS> Set-ExecutionPolicy Unrestricted -Scope CurrentUser

Unblock PowerShell scripts and modules within this directory:

PS> ls -Recurse *.ps*1 | Unblock-File

    Download the .zip file on the main page of the GitHub and extract the .zip file to your desired location
    Once extracted, open PowerShell (or PowerShell ISE) as an Administrator
    Enable PowerShell execution Set-ExecutionPolicy Unrestricted -Force
