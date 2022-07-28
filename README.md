Run PowerShell : 
Run as Administrator

PowerShell to Execute The  Scripts :
Set-ExecutionPolicy Unrestricted -force

Configure PowerShell to use TLS 1.2 only  :
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12

Install Nuget package Manager :
Install-Module -Name NuGet -Force

Install PowerShellGet :
Install-Module -Name PowerShellGet -Force

Set the installation policy for a repository as trusted : 
Set-PSRepository -Name 'PSGallery' -InstallationPolicy Trusted

Get the PowerShell Gallery :
Get-PSRepository



Notes:

TLS :  Transport Layer Security (TLS) 1.2 is the successor to Secure Sockets Layer (SSL) used by endpoint devices and applications to authenticate and encrypt data securely when transferred over a network. TLS protocol is a widely accepted standard used by devices such as computers, phones, IoTs, meters, and sensors.

NuGet : Nuget is the package management tool for the . NET and it is similar to PowerShellGet, MSI packages which support several commands and packages to work with PowerShell.


PowerShellGet : PowerShell providers are . NET programs that provide access to specialized data stores for easier viewing and management. The data appears in a drive, and you access the data in a path like you would on a hard disk drive.

MSI : Windows Installer, alternatively known as Microsoft installer or MSI, is a type of installer developed by Microsoft for use in the Microsoft operating system. The way Windows Installer's MSI files behave is slight different from the standard EXE installation programs.

MSI used by some versions of Windows when installing updates from Windows Update, as well as by other installer tools. An MSI file holds all the information necessary for installing the software, including the files that should be installed and where on the computer those files should be installed to.
