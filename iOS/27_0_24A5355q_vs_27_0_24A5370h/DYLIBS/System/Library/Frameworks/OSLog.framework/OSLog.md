## OSLog

> `/System/Library/Frameworks/OSLog.framework/OSLog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0xd8` | `0xe8` | **`+0x10`** |
| `__TEXT.__text` | `0xabac` | `0xaba0` | **`-0xc`** |

### Other Changes

```diff

-1952.0.0.0.0
+1958.0.0.0.1
Functions:
~ __catalog_procinfo_uuidinfo_remove : 588 -> 584
~ __catalog_create_with_chunk : 2488 -> 2492
~ _catalog_chunk_parse_persona : 552 -> 564
~ ___catalog_chunk_parse_procinfo_v2_block_invoke : 848 -> 840
~ _catalog_chunk_parse_procinfo_uuidinfo : 568 -> 560
~ _catalog_chunk_parse_procinfo_subsystem : 944 -> 976
~ ___catalog_chunk_parse_procinfo_legacy_block_invoke : 756 -> 748
~ _hashtable_iterate : 336 -> 328
~ _hashtable_lookup : 232 -> 228
~ _hashtable_destroy : 544 -> 528
~ __timesync_repair : 1064 -> 1088
~ __timesync_db_openat : 856 -> 860
~ __os_trace_uuiddb_get_pathsuffix : 360 -> 356
~ __os_trace_uuiddb_dsc_validate_hdr : 820 -> 816
~ __os_trace_uuiddb_dsc_foreach_range_with_uuid : 180 -> 172
~ __os_trace_uuiddb_dsc_foreach_uuid : 132 -> 120
~ -[OSLogMessageComponent initWithCoder:] : 472 -> 468
```
