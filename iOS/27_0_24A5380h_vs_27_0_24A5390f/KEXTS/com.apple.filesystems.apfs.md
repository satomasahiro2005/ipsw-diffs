## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x150f10` | `0x1512ec` | **`+0x3dc`** |
| `__TEXT.__cstring` | `0x4fc39` | `0x4fdbb` | **`+0x182`** |

### Other Changes

```diff

-3283.0.9.502.1
-  Functions: 2399
+3283.0.13.0.0
+  Functions: 2400

-  CStrings:  6946
+  CStrings:  6952
CStrings:
+ "%s:%d: %s Invalid reap list free entry %d\n"
+ "%s:%d: %s ino %llu: fs_map_file_offset() returned %llu:%llu (%llu) but that does not cover %llu:%llu (map_flags 0x%x; dstream %llu/%llu\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u\n"
+ "%s:%d: %s reap list object expected %u entries, max %u, but we walked %u + %u = %u\n"
+ "%s:%d: Failed to fetch BSD name, (temp name is %s), dangling mounts will not be unmounted\n"
+ "%s:%d: Failed to start unmount dangling thread for container %s, error %d"
+ "%s:%d: obj is NULL or not apfs object!\n"
+ "(fext_valid(fext, apfs_get_block_size(apfs)))"
+ "2026/07/14"
+ "21:11:49"
+ "3283.0.13"
+ "Jul 14 2026"
+ "apfs-3283.0.13"
+ "apfs_sanity_check"
+ "fext_valid(fext, apfs_get_block_size(apfs))"
- "\"ino %lld: fs_map_file_offset() returned %lld:%lld (%lld) but that does not cover %lld:%lld (map_flags 0x%x; dstream %lld/%lld\\n\" @%s:%d"
- "%s:%d: Failed to start unmount dangling thread, error %d"
- "%s:%d: obj is NULL or not apfs object!"
- "(fext_sanitize(fext))"
- "2026/06/30"
- "21:00:16"
- "3283.0.9.502.1"
- "Jun 30 2026"
- "apfs-3283.0.9.502.1"
```
