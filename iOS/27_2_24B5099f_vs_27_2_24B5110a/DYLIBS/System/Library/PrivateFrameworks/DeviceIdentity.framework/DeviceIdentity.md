## DeviceIdentity

> `/System/Library/PrivateFrameworks/DeviceIdentity.framework/DeviceIdentity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x7b0` | `0x7e0` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x4880` | `0x48a0` | **`+0x20`** |
| `__TEXT.__text` | `0x1da00` | `0x1da1c` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x504` | `0x514` | **`+0x10`** |
| `__TEXT.__cstring` | `0x42be` | `0x42ca` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b0` | `0x6b8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x54` | `0x58` | **`+0x4`** |

### Other Changes

```diff

-1145.40.5.502.1
+1145.40.5.0.4

-  Functions: 288
-  Symbols:   1010
-  CStrings:  697
+  Functions: 289
+  Symbols:   1012
+  CStrings:  698
Symbols:
+ -[DeviceTypeDeviceIdentity is_home_accessory]
+ _OBJC_IVAR_$_DeviceTypeDeviceIdentity._is_home_accessory
Functions:
~ -[DeviceTypeDeviceIdentity init] : 1956 -> 1976
+ -[DeviceTypeDeviceIdentity ucrt_enforced]
CStrings:
+ "HomeAccessory"
+ "iOS Device Activator (MobileActivation-1145.40.5.0.4)"
- "iOS Device Activator (MobileActivation-1145.40.5.502.1)"
```
