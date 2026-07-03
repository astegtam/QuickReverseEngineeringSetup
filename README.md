Run this command in PowerShell with administrator privileges to install Boxstarter and Chocolatey, which are required to download our tools.

". { iwr -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force"

Then run this command again in PowerShell in order to download the tools.

"https://raw.githubusercontent.com/astegtam/QuickReverseEngineeringSetup/refs/heads/main/Tools.txt"

I will add more tools, scripts, and other resources in the future to complete my reverse engineering setup.
