## IOKit

> `/System/Library/CoreAccessories/PlugIns/Platform/IOKit.platform/IOKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd6ac` | `0xd67c` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1260` | `0x1280` | **`+0x20`** |
| `__TEXT.__cstring` | `0x11bc` | `0x11d4` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x818` | `0x828` | **`+0x10`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Symbols:   895
-  CStrings:  306
+  Symbols:   897
+  CStrings:  307
Symbols:
+ _ACCUserDefaultsKey_PretendWirelessCTAMatch
+ _kCFACCUserDefaultsKey_PretendWirelessCTAMatch
Functions:
~ ___init_logging_signpost_modules_block_invoke : 608 -> 588
~ -[USBFaultMonitor sendUSBFaultNotification] : 436 -> 432
~ -[USBCableTypeMonitor sendUSBCableTypeChangedNotification] : 412 -> 408
~ ___init_logging_modules_block_invoke : 608 -> 588
CStrings:
+ "PretendWirelessCTAMatch"
```
