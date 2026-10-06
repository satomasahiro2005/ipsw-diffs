## DiagnosticsSupport

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8441.appex/Frameworks/DiagnosticsSupport.framework/DiagnosticsSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xda58` | `0xda10` | **`-0x48`** |

### Same-size Content Changes

- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1351.0.0.0.0
+1369.0.0.0.0
Functions:
~ _smckSMCMakeUInt32Key : 100 -> 96
~ +[DSIODeviceIdentifier identifierForIOHIDDevice:] : 604 -> 600
~ +[DSIOHIDDevice deviceMatchingAccessories:identifierMask:] : 496 -> 492
~ -[DSIOHIDDevice initWithDeviceIdentifiers:identifierMask:] : 1128 -> 1124
~ -[DSHardwareButtonEventMonitor _handlersForTarget:] : 400 -> 396
~ -[DSHardwareButtonEventMonitor _handlersForEvent:] : 380 -> 376
~ -[DSHardwareButtonEventMonitor _triggerHandlers:event:] : 412 -> 408
~ -[DSEADevice initWithSerialNumber:] : 416 -> 412
~ -[DSEADevice initWithModelNumber:] : 416 -> 412
~ +[DSEADevice devicesWithModelNumbers:] : 448 -> 444
~ -[DSGeneralLogCollector logFilesFromEnumerator:] : 336 -> 332
~ -[DSGeneralLogCollector enumerateLogLinesWithBlock:] : 420 -> 416
~ -[DSMutableArchive _addDirectoryToContents:searchQueue:flatten:error:] : 648 -> 644
~ -[DSMutableArchive _writeArchive:error:] : 456 -> 452
~ -[DSMutableArchive archiveAsTempDirectoryWithName:error:] : 1124 -> 1120
~ +[DSLogLine logLinesFromArray:] : 336 -> 332
~ +[DSIOPSDevice deviceMatchingAccessories:] : 492 -> 488
~ -[DSIOPSDevice initWithDeviceIdentifiers:] : 828 -> 816
~ +[UIColor(HexColor) colorWithHexValue:error:] : 544 -> 552
```
