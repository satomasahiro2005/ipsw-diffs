## CoreRepairKit

> `/System/Library/PrivateFrameworks/CoreRepairKit.framework/CoreRepairKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__auth_got` | `0x178` | `0x0` | **`-0x178`** |
| `__TEXT.__text` | `0x1940` | `0x183c` | **`-0x104`** |
| `__AUTH_CONST.__cfstring` | `0x220` | `0x1a0` | **`-0x80`** |
| `__TEXT.__cstring` | `0x186` | `0x157` | **`-0x2f`** |
| `__TEXT.__oslogstring` | `0x2e9` | `0x2f2` | **`+0x9`** |
| `__DATA_CONST.__got` | `0x90` | `0x88` | **`-0x8`** |

### Other Changes

```diff

-1307.0.16.0.0
+1307.0.26.502.1

-  - /usr/lib/updaters/libT200Updater.dylib

-  Symbols:   83
-  CStrings:  46
+  Symbols:   79
+  CStrings:  42
Symbols:
+ _OBJC_CLASS_$_CRBatteryUpdaterFactory
- _BC__getInfo
- _OBJC_CLASS_$_NSMutableDictionary
- ___stack_chk_fail
- ___stack_chk_guard
- _objc_opt_new
Functions:
~ sub_257cef2e8 -> sub_25c7c1250 : 492 -> 232
CStrings:
+ "Battery FW version dict: %@"
+ "Failed to get battery FW version info"
- "Configuration"
- "DNVDSector1"
- "DNVDSector2"
- "Failed to get version info for battery"
- "Firmware"
- "versiondict is:%@"
```
