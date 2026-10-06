## FindMyDevice

> `/System/Library/PrivateFrameworks/FindMyDevice.framework/FindMyDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a238` | `0x2a318` | **`+0xe0`** |
| `__AUTH_CONST.__objc_const` | `0x7d88` | `0x7db8` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x3fa0` | `0x3fc0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1440` | `0x1458` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2c34` | `0x2c4c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xc00` | `0xbf8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x258` | `0x25c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-479.30.5.16.3
+481.30.6.7.1

-  Functions: 1478
-  Symbols:   2366
-  CStrings:  924
+  Functions: 1480
+  Symbols:   2369
+  CStrings:  925
Symbols:
+ +[FMDRepairDeviceLookupContext fromDevices:useCase:]
+ -[FMDRepairDeviceLookupContext initWithDevices:useCase:]
+ -[FMDRepairDeviceLookupContext useCase]
+ _OBJC_IVAR_$_FMDRepairDeviceLookupContext._useCase
- -[FMDRepairDeviceLookupContext initWithDevices:]
CStrings:
+ "useCase"
```
