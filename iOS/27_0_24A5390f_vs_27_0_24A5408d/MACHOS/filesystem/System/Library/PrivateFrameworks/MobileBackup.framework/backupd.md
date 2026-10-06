## backupd

> `/System/Library/PrivateFrameworks/MobileBackup.framework/backupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x247b64` | `0x247bd4` | **`+0x70`** |
| `__DATA.__objc_const` | `0x23740` | `0x23780` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x3774a` | `0x3776a` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x280e0` | `0x28100` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x1998` | `0x19a0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xb7b0` | `0xb7b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3039.0.1.0.0
+3039.2.2.0.0

-  CStrings:  18401
+  CStrings:  18402
Functions:
~ sub_1000cbec0 : 496 -> 528
~ sub_1000cf2e8 -> sub_1000cf308 : 1032 -> 1056
~ sub_10011cd5c -> sub_10011cd94 : 496 -> 528
~ sub_10011f6c0 -> sub_10011f718 : 764 -> 788
CStrings:
+ "d2dBackgroundDisconnectTimeout"
+ "d2dFileTransferDisconnectTimeout"
- "d2dTransferDisconnectTimeout"
```
