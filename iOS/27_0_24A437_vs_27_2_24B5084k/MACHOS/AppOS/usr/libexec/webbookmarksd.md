## webbookmarksd

> `/usr/libexec/webbookmarksd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x3be0` | `0x3c00` | **`+0x20`** |
| `__TEXT.__text` | `0x179f4` | `0x17a14` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x4873` | `0x4890` | **`+0x1d`** |
| `__DATA.__objc_selrefs` | `0x1188` | `0x1190` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7f8` | `0x800` | **`+0x8`** |

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

-7625.1.29.10.29
+7625.2.4.1.0

-  Symbols:   448
-  CStrings:  1003
+  Symbols:   449
+  CStrings:  1004
Symbols:
+ _OBJC_CLASS_$_WBSUsageRetentionDonationManager
Functions:
~ sub_10000d128 : 968 -> 1000
CStrings:
+ "clearDonatedEventsSinceDate:"
```
