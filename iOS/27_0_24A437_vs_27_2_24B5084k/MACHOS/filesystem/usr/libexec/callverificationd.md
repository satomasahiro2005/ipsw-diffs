## callverificationd

> `/usr/libexec/callverificationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12ea8` | `0x12f3c` | **`+0x94`** |
| `__TEXT.__objc_stubs` | `0x520` | `0x540` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x87f` | `0x899` | **`+0x1a`** |
| `__DATA.__objc_selrefs` | `0x2a0` | `0x2a8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x190` | `0x198` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 705
-  Symbols:   363
-  CStrings:  213
+  Functions: 706
+  Symbols:   364
+  CStrings:  214
Symbols:
+ _AKSeedBuildHeaderKey
Functions:
~ sub_10000ab24 : 1116 -> 1220
+ sub_10000d104
CStrings:
+ "shouldHideSeedBuildHeader"
```
