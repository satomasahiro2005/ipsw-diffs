## NFC

> `/System/Library/CoreAccessories/PlugIns/Transports/NFC.transport/NFC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x1040` | `0x1060` | **`+0x20`** |
| `__TEXT.__cstring` | `0xd9f` | `0xdbb` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x8e0` | `0x8f0` | **`+0x10`** |

### Other Changes

```diff

-1210.0.0.502.1
+1216.0.0.0.0

-  Symbols:   645
-  CStrings:  271
+  Symbols:   647
+  CStrings:  272
Symbols:
+ _ACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
+ _kCFACCUserDefaultsKey_BLEPairingAuthTimeoutValueS
CStrings:
+ "BLEPairingAuthTimeoutValueS"
```
