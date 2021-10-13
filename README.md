# PowerDump

PowerDump project includes various PowerShell scripts for Windows credential harvesting.


## Functions

```
Invoke-HiveDump                 -   dumps credentials from registry hives
Invoke-LsassDump                -   dumps credentials from LSASS process
```


## Acknowledgments

HiveDump is based on the following projects:

  * [Empire's Invoke-PowerDump](https://github.com/EmpireProject/Empire/blob/master/data/module_source/credentials/Invoke-PowerDump.ps1) by @darkoperator and @Cx01N

  * [AADInternals's AD utils](https://github.com/Gerenios/AADInternals/blob/master/AD_utils.ps1) by @NestoriSyynimaa

LsassDump is based on the following projects:

  * [MiniDump](https://github.com/cube0x0/MiniDump) by @cube0x0