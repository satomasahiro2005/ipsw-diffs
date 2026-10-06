## browserkitd

> `/usr/libexec/browserkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xffa4` | `0xff68` | **`-0x3c`** |
| `__DATA_CONST.__auth_ptr` | `0x338` | `0x340` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x250` | `0x248` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.20.10.3
+7625.1.22.10.3

-  Functions: 306
+  Functions: 305
Symbols:
+ _$s10SafariCore16WBSOSTransactionVMn
- _swift_runtimeSupportsNoncopyableTypes
Functions:
~ sub_100010ab0 : 60 -> 72
- sub_100010aec
```
