Run this command in PowerShell with administrator privileges to install Boxstarter and Chocolatey, which are required to download our tools.

". { iwr -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force"

