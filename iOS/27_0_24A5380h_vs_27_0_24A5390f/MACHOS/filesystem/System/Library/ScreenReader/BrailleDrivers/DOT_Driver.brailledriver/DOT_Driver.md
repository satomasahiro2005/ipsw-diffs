## DOT Driver

> `/System/Library/ScreenReader/BrailleDrivers/DOT Driver.brailledriver/DOT Driver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b40` | `0x29c4` | **`-0x17c`** |
| `__TEXT.__objc_stubs` | `0xc20` | `0xc60` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x11a6` | `0x11d4` | **`+0x2e`** |
| `__TEXT.__auth_stubs` | `0x2d0` | `0x2f0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x5b8` | `0x5d0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x170` | `0x180` | **`+0x10`** |
| `__DATA.__objc_const` | `0x9e0` | `0x9e8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x71c` | `0x724` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
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
- `__TEXT.__unwind_info`

### Other Changes

```diff

-460.0.0.0.0
+462.0.0.0.0

-  Symbols:   69
-  CStrings:  338
+  Symbols:   71
+  CStrings:  341
Symbols:
+ _memcpy
+ _objc_retainAutorelease
Functions:
~ sub_10b4 : 520 -> 140
CStrings:
+ "brailleCellData"
+ "bytes"
+ "modelIdentifierForPlist"
```
