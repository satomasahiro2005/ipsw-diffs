## livefiles_ntfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_ntfs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41f84` | `0x41f64` | **`-0x20`** |

### Other Changes

```text
Functions:
~ _ntfs_read_compressed : 3580 -> 3576
~ _ntfs_rl_find_vcn_nolock : 124 -> 108
~ _ntfs_get_size_for_mapping_pairs : 792 -> 772
~ _ntfs_mapping_pairs_build : 1140 -> 1116
~ _ntfs_rl_truncate_nolock : 564 -> 556
~ _ntfs_rl_punch_nolock : 1116 -> 1160
~ _ntfs_attr_find_vcn_nolock : 372 -> 368
~ _ntfs_attr_find_in_attrdef : 120 -> 100
~ _ntfs_attr_extend_initialized : 2236 -> 2212
~ _ntfs_extent_mft_record_free : 732 -> 740
~ _ntfs_mst_fixup_post_read : 164 -> 160
~ _vfs_fsadd : 1700 -> 1732
~ _ntfs_inode_reclaim : 1032 -> 1040
```
