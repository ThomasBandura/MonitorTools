# PowerShell Module Installation

The module is not published to the PowerShell Gallery. Install it from the release ZIP.

## Installation

1. Download the latest release from [Releases](https://github.com/ThomasBandura/MonitorTools/releases)
2. Extract the ZIP file
3. Copy the `PSMonitorTools` folder to one of your PowerShell module paths:
   - PowerShell 7, current user: `$HOME\Documents\PowerShell\Modules`
   - PowerShell 7, all users: `C:\Program Files\PowerShell\Modules`
   - Windows PowerShell 5.1, current user: `$HOME\Documents\WindowsPowerShell\Modules`
   - Windows PowerShell 5.1, all users: `C:\Program Files\WindowsPowerShell\Modules`

## Verify Installation

```powershell
Get-Module -ListAvailable PSMonitorTools
Import-Module PSMonitorTools
Get-Command -Module PSMonitorTools
```

## Requirements

- Windows 11
- PowerShell 5.1 or newer

