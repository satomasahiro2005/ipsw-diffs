## cloudd

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/Support/cloudd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x100` | `0x120` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x740` | `0x760` | **`+0x20`** |
| `__TEXT.__text` | `0x932c` | `0x934c` | **`+0x20`** |
| `__TEXT.__cstring` | `0x560` | `0x578` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xe50` | `0xe60` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x738` | `0x740` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2710.116.0.0.0
+2710.119.0.0.0

-  Functions: 244
-  Symbols:   351
-  CStrings:  253
+  Functions: 245
+  Symbols:   352
+  CStrings:  254
Symbols:
+ _CKOncePerBoot
Functions:
~ sub_10000440c : 2736 -> 2756
+ sub_1000063b4
CStrings:
+ "CKAccountInfoCacheReset"
```
