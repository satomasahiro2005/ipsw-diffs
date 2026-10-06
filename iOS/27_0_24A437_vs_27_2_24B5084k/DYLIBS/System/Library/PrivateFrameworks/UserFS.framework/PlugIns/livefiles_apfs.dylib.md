## livefiles_apfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_apfs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb1d10` | `0xb2060` | **`+0x350`** |
| `__TEXT.__oslogstring` | `0x16438` | `0x16468` | **`+0x30`** |
| `__TEXT.__cstring` | `0x5c35` | `0x5c47` | **`+0x12`** |
| `__TEXT.__unwind_info` | `0x10a0` | `0x10b0` | **`+0x10`** |

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 2582
+  Functions: 2583

-  CStrings:  2243
+  CStrings:  2245
Symbols:
+ _btree_node_val_space_total
- _decrement_dstream_id_for_deletion_ex
CStrings:
+ "%s:%d: %s failed to remove extents iteratively\n"
+ "3288.40.13"
+ "btree_node_compact"
+ "decrement_dstream_id_for_deletion"
- "3288.2.1"
- "decrement_dstream_id_for_deletion_ex"
```
