## enhancedloggingd

> `/usr/libexec/enhancedloggingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb5890` | `0xb5814` | **`-0x7c`** |
| `__TEXT.__objc_stubs` | `0x3420` | `0x3400` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x4bfd` | `0x4bed` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1040` | `0x1038` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xa90` | `0xa88` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   1034
-  CStrings:  1427
+  Symbols:   1033
+  CStrings:  1426
Symbols:
- _AKSeedBuildHeaderKey
Functions:
~ sub_10004a06c : 3568 -> 3444
CStrings:
- "shouldHideSeedBuildHeader"
```
