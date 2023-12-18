# PowerDump

PowerDump project includes various PowerShell scripts for Windows credential harvesting.


## Functions

```
Invoke-DpapiDump                -   dumps credentials protected by DPAPI
Invoke-HiveDump                 -   dumps credentials from registry hives
Invoke-LsassDump                -   dumps credentials from LSASS process
```


## Acknowledgments

DpapiDump is based on the following projects:

  * [SharpDPAPI](https://github.com/GhostPack/SharpDPAPI), by @harmj0y

  * [WifiSquid](https://github.com/k-mistele/wifi-squid)

HiveDump is based on the following projects:

  * [Invoke-PowerDump from Empire](https://github.com/EmpireProject/Empire/blob/master/data/module_source/credentials/Invoke-PowerDump.ps1), by @darkoperator and @Cx01N

  * [AD utils from AADInternals](https://github.com/Gerenios/AADInternals/blob/master/AD_utils.ps1), by @NestoriSyynimaa

LsassDump is based on the following project:

  * [MiniDump](https://github.com/cube0x0/MiniDump), by @cube0x0
  