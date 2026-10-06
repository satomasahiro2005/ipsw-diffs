## livefiles_apfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_apfs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb19ec` | `0xb1a28` | **`+0x3c`** |
| `__TEXT.__unwind_info` | `0x1090` | `0x10a0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x5c33` | `0x5c35` | **`+0x2`** |

### Other Changes

```diff

-3283.0.13.0.0
+3288.2.1.0.0

-  Functions: 2581
-  Symbols:   1505
+  Functions: 2582
+  Symbols:   1506
Symbols:
+ _decrement_dstream_id_for_deletion_ex
Functions:
~ _fs_delete_inode_internal : 836 -> 840
~ _decrement_dstream_id_for_deletion : 832 -> 12
+ _decrement_dstream_id_for_deletion_ex
CStrings:
+ "3288.2.1"
+ "decrement_dstream_id_for_deletion_ex"
- "3283.0.13"
- "decrement_dstream_id_for_deletion"
```
