## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x153b3c` | `0x153e4c` | **`+0x310`** |
| `__TEXT.__cstring` | `0x4ffa5` | `0x501aa` | **`+0x205`** |

### Other Changes

```diff

-3288.40.14.0.0
-  Functions: 2395
+3288.40.17.0.0
+  Functions: 2397

-  CStrings:  6956
+  CStrings:  6962
CStrings:
+ "%s:%d: %s Cannot decompress data from inode %lld on a sealed volume\n"
+ "%s:%d: %s Detected a hole on a sealed volume at offset %lld in %lld\n"
+ "%s:%d: %s Failed to invalidate and push %llu:%llu for ino %llu, err %d\n"
+ "%s:%d: %s IP base %lld:%lld is not free in the bitmap! error %d isallocated %d\n"
+ "%s:%d: %s IP bm base %lld:%lld is not free in the bitmap! error %d isallocated %d\n"
+ "%s:%d: %s Invalid residency reason %d, out of bounds\n"
+ "%s:%d: %s Missing dstream %lld of inode %lld on a sealed volume\n"
+ "%s:%d: %s find_new_metadata(old_block_count %lld, resize_block_count %lld)\n"
+ "%s:%d: %s punch hole dstream and file size mismatch: [%llu, %llu); ino %llu, file_size %llu, dstream exists %d, size %llu, alloced_size %llu\n"
+ "19:58:45"
+ "2026/09/27"
+ "3288.40.17"
+ "Sep 27 2026"
+ "apfs-3288.40.17"
- "%s:%d: %s Failed to invalidate %llu:%llu for ino %llu, err %d\n"
- "%s:%d: %s Failed to msync for ino %llu\n"
- "%s:%d: %s find_new_metadata(available_block_index %lld, nxr_st->resize_block_count %lld)\n"
- "19:33:45"
- "2026/09/13"
- "3288.40.14"
- "Sep 13 2026"
- "apfs-3288.40.14"
```
