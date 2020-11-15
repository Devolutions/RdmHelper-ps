# RDM Helper PowerShell Module

The `RdmHelper` PowerShell module provides helper commands to deal with  [Devolutions Remote Desktop Manager](https://remotedesktopmanager.com) installation, configuration and detection. For instance, `Install-RdmPackage` will install or update RDM, while `Import-RdmModule` will load the real RDM PowerShell module from the detect RDM installation path.

## Package Commands

 * `Get-RdmPackage` Get the latest RDM package download URL and version.
 * `Install-RdmPackage` Download and install RDM.
 * `Uninstall-RdmPackage` Uninstall RDM from the system.
 * `Update-RdmPackage` Download and update RDM.

## Detection Commands

 * `Get-RdmCommand` Find and return full path to RDM executable
 * `Get-RdmPath` Find RDM ConfigPath or InstallPath
 * `Get-RdmProcess` Find RDM running process
 * `Get-RdmVersion` Find RDM installed version

## Module Commands

 * `Import-RdmModule` Find and import real RDM PowerShell module

## Process Commands

 * `Start-RdmProcess` Start RDM process
 * `Stop-RdmProcess` Kill RDM process
 * `Restart-RdmProcess` Restart RDM process
