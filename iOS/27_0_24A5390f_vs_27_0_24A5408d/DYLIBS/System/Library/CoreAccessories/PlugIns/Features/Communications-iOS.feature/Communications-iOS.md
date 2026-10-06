## Communications-iOS

> `/System/Library/CoreAccessories/PlugIns/Features/Communications-iOS.feature/Communications-iOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0xf60` | `0xf80` | **`+0x20`** |
| `__TEXT.__cstring` | `0xb35` | `0xb51` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x830` | `0x840` | **`+0x10`** |

### Other Changes

```diff

-1210.0.0.502.1
+1216.0.0.0.0

-  Symbols:   727
-  CStrings:  204
+  Symbols:   729
+  CStrings:  205
Symbols:
+ _ACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
+ _kCFACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
CStrings:
+ "BLEPairingAuthTimeoutValueS"
```
