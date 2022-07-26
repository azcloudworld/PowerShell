Run PowerShell : 
Run as Administrator

PowerShell to Execute The  Scripts :
Set-ExecutionPolicy Unrestricted -force

Configure PowerShell to use TLS 1.2 only 
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12

Install Nuget package Manager :
Install-Module -Name NuGet -Force

Install PowerShellGet :
Install-Module -Name PowerShellGet -Force

Set the installation policy for a repository as trusted
Set-PSRepository -Name 'PSGallery' -InstallationPolicy Trusted

Get the PowerShell Gallery
Get-PSRepository
