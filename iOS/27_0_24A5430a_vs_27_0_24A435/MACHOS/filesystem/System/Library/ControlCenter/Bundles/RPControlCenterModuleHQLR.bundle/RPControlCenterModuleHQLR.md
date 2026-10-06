## RPControlCenterModuleHQLR

> `/System/Library/ControlCenter/Bundles/RPControlCenterModuleHQLR.bundle/RPControlCenterModuleHQLR`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ffbc` | `0x20160` | **`+0x1a4`** |
| `__TEXT.__oslogstring` | `0x107e` | `0x10ce` | **`+0x50`** |
| `__TEXT.__cstring` | `0x18cb` | `0x190b` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x1e00` | `0x1e40` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x30d0` | `0x3100` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x4c0` | `0x4e0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1110` | `0x1130` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xbc8` | `0xbd8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x898` | `0x8a8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x960` | `0x968` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-  Symbols:   273
-  CStrings:  828
+  Symbols:   275
+  CStrings:  833
Symbols:
+ _MGGetProductType
+ _objc_opt_respondsToSelector
Functions:
~ sub_4bd0 : 16 -> 436
CStrings:
+ " [INFO] %{public}s:%d surface rotated, correcting orientation %ld -> %ld"
+ "-[RPCCUIVideoView currentInterfaceOrientation]"
+ "Localizable-V68"
+ "_windowInterfaceOrientation"
+ "surfaceType"
```
