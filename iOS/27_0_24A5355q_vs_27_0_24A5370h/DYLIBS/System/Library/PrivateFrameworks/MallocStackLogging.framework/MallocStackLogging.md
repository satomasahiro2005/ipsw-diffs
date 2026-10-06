## MallocStackLogging

> `/System/Library/PrivateFrameworks/MallocStackLogging.framework/MallocStackLogging`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x92e4` | `0x9348` | **`+0x64`** |
| `__TEXT.__cstring` | `0x2107` | `0x20f3` | **`-0x14`** |
| `__TEXT.__unwind_info` | `0x280` | `0x278` | **`-0x8`** |

### Other Changes

```diff

-64578.81.1.0.0
+64578.89.1.0.0
Functions:
~ _radix_tree_insert_recursive : 844 -> 848
~ _radix_tree_delete_recursive : 340 -> 348
~ _radix_tree_count_recursive : 180 -> 176
~ _radix_tree_lookup_recursive : 848 -> 856
~ _radix_tree_allocate_node : 372 -> 388
~ _radix_tree_free_node : 60 -> 68
~ _uniquing_table_unwind_stack_remote : 308 -> 304
~ _uniquing_table_create : 372 -> 376
~ _stack_logging_lite_batch_malloc : 292 -> 300
~ _stack_logging_lite_batch_free : 188 -> 204
~ _add_stack_to_ptr : 360 -> 376
~ _get_remote_env_var : 604 -> 580
~ _update_cache_for_file_streams : 1316 -> 1300
~ _release_file_streams_for_task : 176 -> 184
~ _msl_stop_reading : 176 -> 184
~ _msl_payload_for_malloc_address_in_task_helper : 440 -> 436
~ _msl_disk_stack_logs_enumerate_from_buffer : 244 -> 260
~ _append_int : 180 -> 184
~ _my_mkstemps : 508 -> 504
~ _reap_orphaned_log_files_in_hierarchy : 828 -> 832
~ _retain_file_streams_for_task_with_error : 936 -> 956
~ ___msl_uniquing_table_enumerate_block_invoke : 124 -> 132
CStrings:
+ "reached max uniquing table size\n"
+ "stack id was invalid. Turned off stack logging\n"
- "MallocStackLogging: stack id is invalid. Turning off stack logging\n"
- "no more space in uniquing table\n"
```
