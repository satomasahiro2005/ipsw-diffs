## libdispatch.dylib

> `/usr/lib/system/libdispatch.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3dcf0` | `0x3de80` | **`+0x190`** |
| `__TEXT.__const` | `0x760` | `0x750` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xde0` | `0xde8` | **`+0x8`** |

### Other Changes

```diff

-1601.0.0.0.1
+1605.0.0.0.0

-  Functions: 1377
+  Functions: 1379
Functions:
~ __dispatch_async_and_wait_f : 112 -> 116
~ __dispatch_async_and_wait_block_with_privdata : 556 -> 560
~ __dispatch_workloop_dispose : 184 -> 192
~ __dispatch_lane_push_waiter : 936 -> 964
~ __dispatch_queue_atfork_child : 156 -> 160
~ __dispatch_sync_f_slow : 256 -> 260
~ __dispatch_workloop_push_stealer : 392 -> 396
~ __dispatch_apply_invoke_and_wait : 372 -> 364
~ _dispatch_source_set_timer : 1352 -> 1344
~ _os_workgroup_get_working_arena : 152 -> 148
~ _dispatch_mach_mig_demux : 480 -> 488
~ _OUTLINED_FUNCTION_4 : 36 -> 28
~ _OUTLINED_FUNCTION_5 : 20 -> 36
+ _OUTLINED_FUNCTION_6
~ __dispatch_event_loop_drain_timers : 1180 -> 1208
~ __dispatch_kq_immediate_update : 204 -> 216
~ __dispatch_kq_deferred_update : 556 -> 560
~ __dispatch_kq_unote_update : 1520 -> 1548
~ __dispatch_event_loop_drain : 736 -> 740
~ __dispatch_kq_drain : 384 -> 404
~ __dispatch_event_loop_merge : 320 -> 336
~ __dispatch_event_loop_leave_deferred : 512 -> 520
~ __dispatch_event_loop_wake_owner : 996 -> 948
~ __dispatch_event_loop_wait_for_ownership : 676 -> 764
~ __dispatch_event_loop_end_ownership : 500 -> 504
~ __dispatch_mach_notify_merge : 448 -> 444
~ __dispatch_mach_notification_merge_msg : 336 -> 352
~ __voucher_create_without_importance : 720 -> 716
~ _voucher_create_with_mach_msg : 340 -> 336
~ __voucher_atfork_child : 280 -> 272
~ _voucher_activity_create_with_data_2 : 2204 -> 2200
~ _OUTLINED_FUNCTION_3 : 16 -> 20
~ _OUTLINED_FUNCTION_5 : 36 -> 16
~ _OUTLINED_FUNCTION_13 : 12 -> 36
~ _OUTLINED_FUNCTION_14 : 36 -> 32
~ _firehose_buffer_create : 460 -> 468
~ _firehose_buffer_update_limits_unlocked : 300 -> 304
~ _firehose_client_reconnect : 896 -> 880
~ _firehose_buffer_ring_enqueue : 632 -> 636
~ _firehose_buffer_tracepoint_reserve_slow : 1036 -> 1032
~ _firehose_buffer_tracepoint_reserve_wait_for_chunks_from_logd : 1156 -> 1152
~ __dispatch_fd_entry_cleanup_operations : 412 -> 408
~ ____dispatch_io_stop_block_invoke_3 : 172 -> 168
~ __dispatch_stream_complete_operation : 168 -> 176
~ ____dispatch_operation_enqueue_block_invoke_2 : 180 -> 184
~ __dispatch_stream_init : 192 -> 188
~ _OUTLINED_FUNCTION_3 : 40 -> 28
+ _OUTLINED_FUNCTION_4
~ __dispatch_data_dispose : 312 -> 316
~ _dispatch_data_create_concat : 324 -> 328
~ _dispatch_data_create_subrange : 528 -> 568
~ __dispatch_data_apply : 236 -> 264
~ _dispatch_data_copy_region : 344 -> 356
~ ____dispatch_transform_from_base32_with_table_block_invoke : 568 -> 572
~ ____dispatch_transform_to_base32_with_table_block_invoke : 908 -> 892
~ ____dispatch_transform_from_base64_block_invoke : 476 -> 480
~ ____dispatch_transform_to_base64_block_invoke : 684 -> 648
~ ____dispatch_transform_to_utf16_block_invoke : 784 -> 788
~ __dispatch_transform_read_utf8_sequence : 128 -> 124
~ __dispatch_alloc_maybe_madvise_page : 276 -> 244
~ _firehoseReply_server_routine : 60 -> 64
~ _firehoseReply_server : 152 -> 156
~ __dispatch_queue_debug_attr : 748 -> 740
~ __dispatch_mach_msg_debug : 568 -> 556
~ __dispatch_mach_debug : 176 -> 164
~ __dispatch_event_loop_wake_owner.cold.1 : 56 -> 256
+ __dispatch_event_loop_wait_for_ownership.cold.2
- __dispatch_event_loop_wait_for_ownership.cold.2
~ _voucher_kvoucher_debug : 1464 -> 1444
~ _voucher_copy_with_persona_mach_voucher.cold.1 : 676 -> 672
~ __dispatch_io_debug : 120 -> 108
~ __dispatch_operation_debug : 120 -> 108
```
