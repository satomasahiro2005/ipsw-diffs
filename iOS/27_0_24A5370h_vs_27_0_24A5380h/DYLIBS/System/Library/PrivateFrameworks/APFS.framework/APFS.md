## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/APFS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53c24` | `0x53f5c` | **`+0x338`** |
| `__AUTH.__data` | `—` | `0x148` | **`+0x148`** |
| `__DATA_DIRTY.__data` | `0x148` | `—` | **`-0x148`** |
| `__TEXT.__cstring` | `0xe653` | `0xe776` | **`+0x123`** |

### Other Changes

```diff

-3283.0.0.0.0
+3283.0.9.502.1

-  CStrings:  1395
+  CStrings:  1400
Functions:
~ _omap_reap : 5244 -> 5360
~ _btree_node_compact : 1208 -> 1364
~ _spaceman_currently_available_space : 288 -> 304
~ _spaceman_modify_bits : 3372 -> 3592
~ __ZN6Base856DecodeEPKcmPhmRm : 648 -> 596
~ _nx_unmount_internal : 332 -> 300
~ _growCaptureFile : 212 -> 272
~ _APFSGetExclavePath : 668 -> 672
~ _xf_get_from_blob : 168 -> 176
~ __ZN16MetricsCompactor4ReadER12Perfcounters : 424 -> 416
~ _dev_init_common : 400 -> 416
~ _obj_write_prepare : 1572 -> 1592
~ _obj_alloc : 2512 -> 2520
~ _obj_delete_internal : 988 -> 1204
~ _obj_type_free : 128 -> 136
~ _nx_init : 316 -> 332
~ _nx_destroy : 128 -> 164
~ _mounted_device_internal : 236 -> 252
CStrings:
+ "%s:%d: %s oid 0x%llx flags 0x%llx type 0x%x/0x%x error freeing new location %d\n"
+ "%s:%d: %s op %d error getting cab %d @ %lld: %d\n"
+ "%s:%d: %s op %d error getting cib %d @ %lld: %d\n"
+ "%s:%d: %s op %d error getting cib %d bitmap %d @ %lld: %d\n"
+ "%s:%d: %s op %d failed to allocate block from internal pool: %d\n"
+ "%s:%d: %s op %d failed to create bitmap object %lld: %d\n"
+ "%s:%d: %s op %d failed to free internal pool block %lld: %d\n"
+ "3283.0.9.502.1"
+ "nx-tree-node-compact-lock"
- "%s:%d: %s failed to allocate block from internal pool: %d\n"
- "%s:%d: %s failed to create bitmap object %lld: %d\n"
- "%s:%d: %s failed to free internal pool block %lld: %d\n"
- "3283"
```
