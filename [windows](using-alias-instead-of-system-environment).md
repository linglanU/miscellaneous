# reason
set python to system environment is not in effect
+ gui method [x]
+ `setx` [x]

# howto
using alias
1. make `ps1` file executable[^1]
   + open powershell with admin, `Set-ExecutionPolicy -ExecutionPolicy Bypass`
2. set config in `$profile`
   + `Set-Alias -Name python -Value C:\Users\linglan\AppData\Local\Programs\Python\Python312\python.exe`
     in `C:\Users\<username>\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1`

# exammin
`python --version` in normal powershell

----

[^1]: [change-execution-policy](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.4)
