## Setup

> `/Applications/Setup.app/Setup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24cca8` | `0x24ce00` | **`+0x158`** |
| `__TEXT.__gcc_except_tab` | `0x4e64` | `0x4e2c` | **`-0x38`** |
| `__TEXT.__objc_methname` | `0x40a4e` | `0x40a7e` | **`+0x30`** |
| `__DATA.__objc_const` | `0x496b0` | `0x496d0` | **`+0x20`** |
| `__DATA.__objc_data` | `0xcac8` | `0xcae8` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1508c` | `0x150ac` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1ce9` | `0x1d09` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x3a14` | `0x3a2c` | **`+0x18`** |
| `__TEXT.__cstring` | `0xfd10` | `0xfcfb` | **`-0x15`** |
| `__TEXT.__objc_methtype` | `0xcae2` | `0xcad0` | **`-0x12`** |
| `__DATA.__data` | `0x7a28` | `0x7a38` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1a2c` | `0x1a38` | **`+0xc`** |
| `__TEXT.__objc_methlist` | `0x1dc28` | `0x1dc20` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x9e08` | `0x9e10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
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
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5411.104.0.0.0
+5411.2.2.0.0

-  Functions: 12341
+  Functions: 12342

-  CStrings:  14880
+  CStrings:  14882
CStrings:
+ "Already restored auto lock"
+ "Restore AutoLock"
+ "Sep 26 2026"
+ "TRANSFER_OPTIONS_NO_MEGA_BACKUP_DESCRIPTION"
+ "TRANSFER_OPTIONS_RESTORE_OPTION_DETAIL"
+ "ensureAppNetworkAccessForCapabilities:completionHandler:"
+ "isCapturingAutoLock"
+ "v32@0:8Q16@?<v@?B>24"
- "Q32@0:8@\"RUIObjectModel\"16@\"RUIPage\"24"
- "Sep 13 2026"
- "TRANSFER_OPTIONS_DESCRIPTION"
- "TRANSFER_OPTIONS_RESTORE_OPTION_DETAIL_WIFI"
- "pretermination task %@ did not complete in time"
- "supportedInterfaceOrientationsForObjectModel:page:"
```
