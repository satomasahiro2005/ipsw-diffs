## USBHost

> `/System/Library/CoreAccessories/PlugIns/Transports/USBHost.transport/USBHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x17c0` | `0x17e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x19ac` | `0x19c8` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x9d8` | `0x9e8` | **`+0x10`** |

### Other Changes

```diff

-1210.0.0.502.1
+1216.0.0.0.0

-  Symbols:   1242
-  CStrings:  495
+  Symbols:   1244
+  CStrings:  496
Symbols:
+ _ACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
+ _kCFACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
CStrings:
+ "BLEPairingAuthTimeoutValueS"
```
