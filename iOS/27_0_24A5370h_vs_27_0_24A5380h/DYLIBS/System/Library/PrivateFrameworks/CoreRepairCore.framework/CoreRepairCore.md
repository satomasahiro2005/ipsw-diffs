## CoreRepairCore

> `/System/Library/PrivateFrameworks/CoreRepairCore.framework/CoreRepairCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b738` | `0x8ca88` | **`+0x1350`** |
| `__AUTH_CONST.__objc_const` | `0x64e8` | `0x6910` | **`+0x428`** |
| `__TEXT.__oslogstring` | `0x9a50` | `0x9d45` | **`+0x2f5`** |
| `__TEXT.__cstring` | `0x6ff8` | `0x72cc` | **`+0x2d4`** |
| `__TEXT.__objc_methlist` | `0x45ac` | `0x47d4` | **`+0x228`** |
| `__AUTH_CONST.__cfstring` | `0x84c0` | `0x86e0` | **`+0x220`** |
| `__DATA_CONST.__objc_selrefs` | `0x25c0` | `0x26a0` | **`+0xe0`** |
| `__AUTH.__objc_data` | `0x1180` | `0x1220` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x5d0` | `0x660` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x540` | `0x5a0` | **`+0x60`** |
| `__DATA.__data` | `0x5f8` | `0x658` | **`+0x60`** |
| `__DATA_DIRTY.__objc_data` | `0xd70` | `0xdc0` | **`+0x50`** |
| `__DATA.__bss` | `0xe8` | `0x120` | **`+0x38`** |
| `__DATA_DIRTY.__bss` | `0x168` | `0x1a0` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1420` | `0x1458` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x358` | `0x37c` | **`+0x24`** |
| `__DATA_CONST.__objc_classlist` | `0x318` | `0x330` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xbb8` | `0xba8` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1d8` | `0x1e8` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x68` | `0x70` | **`+0x8`** |

### Other Changes

```diff

-1307.0.16.0.0
+1307.0.26.502.1

-  - /usr/lib/updaters/libT200Updater.dylib
-  Functions: 2517
+  Functions: 2568

-  CStrings:  2422
+  CStrings:  2469
Symbols:
+ _OBJC_CLASS_$_CRBatteryUpdaterFactory
+ _OBJC_METACLASS_$_CRBatteryUpdaterFactory
+ _dlclose
- _T200UpdaterCopyFirmwareWithLogging
- _T200UpdaterCreateRequestWithLogging
- _isVeridianUpdateRequired
CStrings:
+ " NOT"
+ "/usr/lib/updaters/libT200Updater.dylib"
+ "AppleGasGaugeUpdate"
+ "BC__getInfo"
+ "Battery FW update is%s required, error: %@"
+ "BatteryGetBoardIdFromDT is nil"
+ "BatteryUpdaterCopyFirmwareWithLogging is nil"
+ "BatteryUpdaterCreate is nil"
+ "BatteryUpdaterCreateRequestWithLogging is nil"
+ "BatteryUpdaterExecCommand is nil"
+ "BatteryUpdaterGetInfo failed with rc: %d"
+ "BatteryUpdaterGetInfo is nil"
+ "BatteryUpdaterIsDone is nil"
+ "BatteryUpdaterIsFWUpdateRequired is nil"
+ "Configuration"
+ "DNVDSector1"
+ "DNVDSector2"
+ "Failed to create shared instance for battery firmware updater"
+ "Failed to get version info for battery"
+ "Failed to load updater dylib"
+ "Failed to open T200 updater dylib"
+ "Failed to resolve GetBoardIdFromDT"
+ "Failed to resolve T200 symbols"
+ "Failed to resolve UpdaterCopyFirmwareWithLogging"
+ "Failed to resolve UpdaterCreateRequestWithLogging"
+ "Failed to resolve UpdaterExecCommand"
+ "Failed to resolve UpdaterIsDone"
+ "Failed to resolve isUpdateRequired"
+ "Firmware"
+ "Firmware update required: %d, system partition path %@"
+ "GetBoardIdFromDT failed, error: %d"
+ "Instantiating CRT200Updater"
+ "Missing updater context"
+ "Request created by battery updater: %@"
+ "Setting up updater with options: %@"
+ "T200"
+ "T200 dylib handle nil"
+ "T200GetBoardIdFromDT"
+ "T200Updater dylib not correctly loaded"
+ "T200UpdaterCopyFirmwareWithLogging"
+ "T200UpdaterCreate"
+ "T200UpdaterCreate failed"
+ "T200UpdaterCreateRequestWithLogging"
+ "T200UpdaterExecCommand"
+ "T200UpdaterGetInfo is not supported or missing arguments"
+ "T200UpdaterIsDone"
+ "Underlying battery controller is Veridian or Volchok"
+ "batteryFirmware"
+ "isVeridianUpdateRequired"
- "isVeridianUpdateRequired :%@:%d"
- "veridianFirmware"
```
