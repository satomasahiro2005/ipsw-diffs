## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x153504` | `0x1539a8` | **`+0x4a4`** |
| `__DATA.__bss` | `0xd88` | `0xcf8` | **`-0x90`** |
| `__TEXT.__cstring` | `0x4ff24` | `0x4ff4b` | **`+0x27`** |
| `__DATA.__data` | `0x754` | `0x75c` | **`+0x8`** |

### Other Changes

```diff

-3288.2.1.0.0
-  Functions: 2396
+3288.40.13.0.0
+  Functions: 2395

-  CStrings:  6953
+  CStrings:  6955
CStrings:
+ "%s:%d: %s failed to remove extents iteratively\n"
+ "%s:%d: %s ino %llu, failed to get region covering %llu+%zu, error %d\n"
+ "%s:%d: %s request flags: 0x%llx type: 0x%llx min_size: %lld: max_age %lld desired_amt: %lld (age-for-urgency: %lld, requesting uid: %d, search_start_time: %llu)\n"
+ "2026/09/04"
+ "23:03:37"
+ "3288.40.13"
+ "Sep  4 2026"
+ "apfs-3288.40.13"
+ "btree_node_compact"
+ "decrement_dstream_id_for_deletion"
- "%s:%d: %s request flags: 0x%llx type: 0x%llx min_size: %lld: max_age %lld desired_amt: %lld (age-for-urgency: %lld, requesting uid: %d)\n"
- "%s:%d: container is locked to be loadable only by pid <%d>, refusing request to load the container by pid <%d> device = %s\n"
- "2026/08/13"
- "21:26:23"
- "3288.2.1"
- "Aug 13 2026"
- "apfs-3288.2.1"
- "decrement_dstream_id_for_deletion_ex"
```
