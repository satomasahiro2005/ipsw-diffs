## livefiles_apfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_apfs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb0c20` | `0xb1678` | **`+0xa58`** |
| `__TEXT.__oslogstring` | `0x161c4` | `0x1635c` | **`+0x198`** |
| `__TEXT.__cstring` | `0x5bc5` | `0x5c26` | **`+0x61`** |
| `__AUTH.__data` | `0x250` | `0x258` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1088` | `0x1090` | **`+0x8`** |

### Other Changes

```diff

-3283.0.0.0.0
+3283.0.9.502.1

-  Functions: 2582
+  Functions: 2581

-  CStrings:  2229
+  CStrings:  2239
Symbols:
+ _OUTLINED_FUNCTION_69
+ _OUTLINED_FUNCTION_76
+ _OUTLINED_FUNCTION_77
+ _OUTLINED_FUNCTION_88
+ _OUTLINED_FUNCTION_91
+ _apfs_update_dir_stats_parent
+ _consider_drec_for_size_tracking
+ _fv_unwrap_and_migrate_vek
- _OUTLINED_FUNCTION_55
- _OUTLINED_FUNCTION_67
- _OUTLINED_FUNCTION_72
- _OUTLINED_FUNCTION_80
- _OUTLINED_FUNCTION_85
- _OUTLINED_FUNCTION_90
- _OUTLINED_FUNCTION_92
- _OUTLINED_FUNCTION_95
CStrings:
+ "%s:%d: %s could not get correct parent of ino %llu (%d tries)\n"
+ "%s:%d: %s failed to restore dir-stats for to_ino %llu: %d\n"
+ "%s:%d: %s ino %llu has no name"
+ "%s:%d: %s oid 0x%llx flags 0x%llx type 0x%x/0x%x error freeing new location %d\n"
+ "%s:%d: %s op %d error getting cab %d @ %lld: %d\n"
+ "%s:%d: %s op %d error getting cib %d @ %lld: %d\n"
+ "%s:%d: %s op %d error getting cib %d bitmap %d @ %lld: %d\n"
+ "%s:%d: %s op %d failed to allocate block from internal pool: %d\n"
+ "%s:%d: %s op %d failed to create bitmap object %lld: %d\n"
+ "%s:%d: %s op %d failed to free internal pool block %lld: %d\n"
+ "3283.0.9.502.1"
+ "apfs_update_dir_stats_parent"
+ "consider_drec_for_size_tracking"
+ "nx-tree-node-compact-lock"
- "%s:%d: %s failed to allocate block from internal pool: %d\n"
- "%s:%d: %s failed to create bitmap object %lld: %d\n"
- "%s:%d: %s failed to free internal pool block %lld: %d\n"
- "3283"
```
