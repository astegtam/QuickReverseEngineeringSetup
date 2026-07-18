Run this command in PowerShell with administrator privileges to install Boxstarter and Chocolatey, which are required to download our tools.  (You might need to adjust your security settings to allow the installation to complete.)

". { iwr -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force"

Then run this command in PowerShell in order to download the tools.

"Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/astegtam/QuickReverseEngineeringSetup/refs/heads/main/tl.txt -DisableReboots"

I will add more tools, scripts, and other resources in the future to complete my reverse engineering setup.
