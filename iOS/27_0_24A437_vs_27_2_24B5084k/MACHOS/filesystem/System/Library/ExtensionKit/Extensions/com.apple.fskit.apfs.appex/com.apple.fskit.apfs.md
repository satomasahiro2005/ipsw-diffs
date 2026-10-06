## com.apple.fskit.apfs

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.apfs.appex/com.apple.fskit.apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe51f4` | `0xe56fc` | **`+0x508`** |
| `__TEXT.__unwind_info` | `0x1b78` | `0x1ba0` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x3a0` | `0x3c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3b8b3` | `0x3b898` | **`-0x1b`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-3288.2.1.0.0
+3288.40.13.0.0

-  Functions: 3287
+  Functions: 3286

-  CStrings:  5386
+  CStrings:  5387
Symbols:
+ _decrement_dstream_id_for_deletion
+ _fsck_repairs_count
- _decrement_dstream_id_for_deletion_ex
- _iteratively_remove_extents_of_file
CStrings:
+ "%s:%d: %s failed to remove extents iteratively\n"
+ "3288.40.13"
+ "BTOFF_IS_VALID(offsets[i].off)"
+ "The volume %s with UUID %s was found to have minor issues that can be repaired."
+ "decrement_dstream_id_for_deletion"
+ "dstream->alloced_size == 0"
+ "fsck_repairs_apply_cb"
+ "mount_apfs"
- "3288.2.1"
- "The volume %s with UUID %s could not be verified completely and can not be repaired."
- "decrement_dstream_id_for_deletion_ex"
- "fsck_repairs_apply"
- "offsets[i].off != BTOFF_INVALID && offsets[i].off != BTOFF_MT_GHOST"
- "offsets[i].off != BTOFF_MT_GHOST"
- "offsets[midpoint].off != BTOFF_MT_GHOST"
```
