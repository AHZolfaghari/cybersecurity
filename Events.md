## Windows Events
- Windows Event Types [Microsoft Defination](https://docs.microsoft.com/en-us/windows/win32/eventlog/event-types)
- Windows Event Viewer Types [Microsoft Documentation](https://docs.microsoft.com/en-us/windows/win32/eventlog/eventlog-key)
- [Windows Logging CheatSheet](https://www.malwarearchaeology.com/cheat-sheets)
- [Win Events IDs to Monitor for Security](https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/plan/appendix-l--events-to-monitor)
- [Tampering with Windows Event Tracing - Palantir Blog](https://blog.palantir.com/tampering-with-windows-event-tracing-background-offense-and-defense-4be7ac62ac63)
- Powershell Get-WinEvent command with FilterHashtable [Microsoft Documentation](https://docs.microsoft.com/en-us/powershell/scripting/samples/Creating-Get-WinEvent-queries-with-FilterHashtable?view=powershell-7.1)


## Codes
See a saved file
> Get-WinEvent -Path name.evtx

Count Log events
> Get-WinEvent -ListProvider *msi* | Measure-Object
