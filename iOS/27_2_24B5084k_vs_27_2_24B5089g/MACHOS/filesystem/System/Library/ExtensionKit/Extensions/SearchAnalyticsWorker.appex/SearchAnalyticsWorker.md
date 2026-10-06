## SearchAnalyticsWorker

> `/System/Library/ExtensionKit/Extensions/SearchAnalyticsWorker.appex/SearchAnalyticsWorker`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x372c` | `0x3be4` | **`+0x4b8`** |
| `__TEXT.__oslogstring` | `0x128` | `0x179` | **`+0x51`** |
| `__TEXT.__swift5_typeref` | `0x11e` | `0x148` | **`+0x2a`** |
| `__DATA.__data` | `0xc8` | `0xe0` | **`+0x18`** |
| `__TEXT.__const` | `0x2e2` | `0x2f2` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x390` | `0x3a0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1c0` | `0x1d0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x3c` | `0x40` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-3605.21.1.1.1
+3605.23.1.1.1

-  Functions: 113
-  Symbols:   64
-  CStrings:  12
+  Functions: 120
+  Symbols:   63
+  CStrings:  13
Symbols:
+ _swift_getTypeByMangledNameInContextInMetadataState2
- _swift_allocError
- _swift_willThrow
CStrings:
+ "Recipe %s is not eligible to run yet; waiting for its next scheduled run"
```
