## ReplayKitAngel

> `/Applications/ReplayKitAngel.app/ReplayKitAngel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e1c8` | `0x3e42c` | **`+0x264`** |
| `__TEXT.__objc_stubs` | `0x2640` | `0x26a0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x1c95` | `0x1cd5` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1fc1` | `0x1ff1` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x50f3` | `0x5123` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x1280` | `0x12a0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x11a8` | `0x11b8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x950` | `0x960` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xe40` | `0xe48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

+  - /usr/lib/libMobileGestalt.dylib

-  Symbols:   577
-  CStrings:  1310
+  Symbols:   579
+  CStrings:  1314
Symbols:
+ _MGGetProductType
+ _objc_opt_respondsToSelector
Functions:
~ sub_100003bf0 -> sub_100003c30 : 16 -> 436
~ sub_1000085e4 -> sub_1000087c8 : 1032 -> 1052
~ sub_100008a98 -> sub_100008c90 : 388 -> 408
~ sub_100008c1c -> sub_100008e28 : 280 -> 300
~ sub_100008e00 -> sub_100009020 : 168 -> 292
~ sub_10003e538 -> sub_10003e7d4 : 2236 -> 2244
CStrings:
+ " [INFO] %{public}s:%d surface rotated, correcting orientation %ld -> %ld"
+ "-[RPCCUIVideoView currentInterfaceOrientation]"
+ "_windowInterfaceOrientation"
+ "surfaceType"
```
