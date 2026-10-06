## livefiles_apfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_apfs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb0754` | `0xb0c20` | **`+0x4cc`** |
| `__TEXT.__unwind_info` | `0x1070` | `0x1088` | **`+0x18`** |
| `__TEXT.__cstring` | `0x5bcd` | `0x5bc5` | **`-0x8`** |

### Other Changes

```diff

-3277.0.0.0.1
+3283.0.0.0.0

-  Functions: 2574
-  Symbols:   1503
+  Functions: 2582
+  Symbols:   1505
Symbols:
+ _apfs_uvfsop_sync_file
+ _sanitize_drec_name_len
CStrings:
+ "3283"
- "3277.0.0.0.1"
```
