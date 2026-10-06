## IOKit

> `/System/Library/CoreAccessories/PlugIns/Platform/IOKit.platform/IOKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x12c0` | `0x12e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1208` | `0x1224` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x848` | `0x858` | **`+0x10`** |

### Other Changes

```diff

-1210.0.0.502.1
+1216.0.0.0.0

-  Symbols:   901
-  CStrings:  309
+  Symbols:   903
+  CStrings:  310
Symbols:
+ _ACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
+ _kCFACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
CStrings:
+ "BLEPairingAuthTimeoutValueS"
```
