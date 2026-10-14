## CoreUtils

> `/System/Library/PrivateFrameworks/CoreUtils.framework/CoreUtils`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x118e84` | `0x118ec8` | **`+0x44`** |
| `__TEXT.__objc_methlist` | `0xa0e8` | `0xa120` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x45a0` | `0x45c0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x13ca0` | `0x13cc0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x51c0` | `0x51e0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2a48` | `0x2a58` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1d8d0` | `0x1d8de` | **`+0xe`** |

### Other Changes

```diff

-910.29.0.0.0
+910.31.0.0.0

-  CStrings:  4869
+  CStrings:  4870
Functions:
~ _DeviceOSVersionAtOrLaterEx : 148 -> 156
~ _GestaltProductTypeStringToDeviceClass : 284 -> 312
~ -[CUPairingDaemon _activate] : 572 -> 584
~ _CUGestaltDeviceClassToString : 196 -> 216
CStrings:
+ "HomeAccessory"
```
