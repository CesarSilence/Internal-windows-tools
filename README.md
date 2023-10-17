# Internal-windows-tools

I created this repository with the idea of scenarios where you can't install tools on the compromised windows host
## Tools

Some of the tools were extracted from one of the latest versions of [Impacket](https://github.com/fortra/impacket)
ssh and ftp login were created to test credentials.
[DFSCoerce](https://github.com/Wh04m1001/DFSCoerce) and [PrintNigtmare](https://github.com/ly4k/PrintNightmare) were compiled in order to test some classic and quick-to-exploit vulnerabilities.
> **Note:** if you need the dll to exploit the PrintNightmare vulnerability you can find it in my personal fork [here](https://github.com/CesarSilence/PrintNightmare/blob/main/adduser.c).

The rbcd tool does not come from Impacket suite was compiled from the [tohi](https://github.com/tothi/rbcd-attack) version

and I followed the compilation instructions provided by: [maaaaz](https://github.com/maaaaz/CrackMapExecWin/wiki/How-to-compile-CrackMapExec-for-Windows)

## List of tools


| Tool                |Version                          
|----------------|-------------------------------
|addcomputer|`v0.10.0`            
|describeTicket          |`v0.10.0`            
|dfscoerce          |`v1`
|DumpNTLMInfo          |`v0.10.0`
|findDelegation          |`v0.10.0`
|ftp_login          |`v1`
|GetADUsers          |`v0.10.0`
|GetNPUsers         |`v0.10.0`
|getST          |`v0.10.0`
|getTGT          |`v0.10.0`
|GetUsersSPN          |`v0.10.0`
|netview          |`v0.10.0`
|printnightmare          |`v1`
|psexec          |`v0.10.0`
|rbcd          |`v0.10.0 (?)`
|secretsdump          |`v0.10.0`
|smbpasswd          |`v0.10.0`
|ssh_login          |`v1`
|ticketer          |`v0.10.0`
|wmiexec          |`v0.10.0`


## Screenshots

Some screenshots of the executables in action.

### Help Menu
![Help Menu](https://i.imgur.com/smS16ZH.png)
### PrintNightmare check
![PrintNightmare](https://i.imgur.com/FLn2dXT.png)
### Secretsdump
![secretsdump](https://i.imgur.com/PPyjGy0.png)
### wmiexec
![wmiexec](https://i.imgur.com/uaFJ8L3.png)
## Credits

- [Impacket](https://github.com/fortra/impacket)
- [tothi](https://github.com/tothi/rbcd-attack)
- [maaaaz](https://github.com/maaaaz/impacket-examples-windows)
- [ly4k](https://github.com/ly4k/PrintNightmare)

