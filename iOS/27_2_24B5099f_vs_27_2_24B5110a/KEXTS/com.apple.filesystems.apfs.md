## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x153e4c` | `0x1541bc` | **`+0x370`** |
| `__TEXT.__cstring` | `0x501aa` | `0x50305` | **`+0x15b`** |

### Other Changes

```diff

-3288.40.17.0.0
-  Functions: 2397
+3288.42.1.0.0
+  Functions: 2399

-  CStrings:  6962
+  CStrings:  6967
CStrings:
+ "%s:%d: %s apfs_rr: cleanup 0 failed to decrement head split crypto refcount (ret %d) \n"
+ "%s:%d: %s apfs_rr: cleanup first failed to decrement crypto refcount (ret %d) \n"
+ "%s:%d: %s apfs_rr: cleanup last failed to decrement crypto refcount (ret %d) \n"
+ "%s:%d: %s applied dstream workaround inode %llu\n"
+ "%s:%d: %s ino %llu '%s' cp_open() failed with EILSEQ\n"
+ "01:02:38"
+ "2026/10/10"
+ "3288.42.1"
+ "Oct 10 2026"
+ "apfs-3288.42.1"
- "19:58:45"
- "2026/09/27"
- "3288.40.17"
- "Sep 27 2026"
- "apfs-3288.40.17"
```
