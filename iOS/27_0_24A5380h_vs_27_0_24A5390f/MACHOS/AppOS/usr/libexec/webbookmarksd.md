## webbookmarksd

> `/usr/libexec/webbookmarksd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x180a8` | `0x180cc` | **`+0x24`** |
| `__TEXT.__objc_stubs` | `0x3bc0` | `0x3be0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x4856` | `0x4873` | **`+0x1d`** |
| `__DATA.__objc_selrefs` | `0x1180` | `0x1188` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7f0` | `0x7f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.22.10.3
+7625.1.24.10.1

-  Symbols:   447
-  CStrings:  1002
+  Symbols:   448
+  CStrings:  1003
Symbols:
+ _OBJC_CLASS_$_WBSBiomeDonationManager
Functions:
~ sub_10000d518 : 932 -> 968
CStrings:
+ "clearEventsDonatedSinceDate:"
```
