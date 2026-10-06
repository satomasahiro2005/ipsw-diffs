## libdispatch_debug.dylib

> `/System/DriverKit/usr/lib/system/libdispatch_debug.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbba0c` | `0xbba7c` | **`+0x70`** |
| `__TEXT.__cstring` | `0x8a0b` | `0x8a15` | **`+0xa`** |
| `__DATA_CONST.__const` | `0x6f0` | `0x6f8` | **`+0x8`** |
| `__TEXT.__const` | `0x553` | `0x54b` | **`-0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH_CONST.__auth_got`
- `__AUTH_CONST.__const`
- `__TEXT.__dof_dispatch`
- `__TEXT.__dof_voucher`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1601.0.0.0.1
+1605.0.0.0.0

-  CStrings:  792
+  CStrings:  793
Functions:
~ _dispatch_get_current_queue : 100 -> 96
~ __dispatch_queue_attr_from_info : 304 -> 300
~ __dispatch_async_and_wait_f : 392 -> 400
~ __dispatch_async_and_wait_block_with_privdata : 1180 -> 1192
~ _dispatch_queue_get_label : 184 -> 180
~ __dispatch_workloop_drain_barrier_waiter : 1656 -> 1640
~ __dispatch_workloop_invoke2 : 2260 -> 2232
~ __dispatch_workloop_barrier_complete : 3972 -> 3960
~ __dispatch_workloop_push : 716 -> 704
~ __dispatch_workloop_push_waiter : 2956 -> 2920
~ __dispatch_lane_push_waiter : 3872 -> 4012
~ __dispatch_queue_atfork_child : 720 -> 712
~ __dispatch_sync_f_slow : 2480 -> 2488
~ __dispatch_apply_invoke : 984 -> 980
~ __dispatch_apply_redirect_invoke : 988 -> 984
~ __dispatch_apply_invoke_and_wait : 988 -> 984
~ __dispatch_source_dispose : 616 -> 604
~ __dispatch_source_cancel_callout : 624 -> 612
~ __dispatch_source_set_handler_slow : 632 -> 628
~ __dispatch_source_registration_callout : 304 -> 300
~ __dispatch_source_latch_and_call : 2916 -> 2912
~ __dispatch_timers_program : 2708 -> 2704
~ __dispatch_timer_unote_disarm : 464 -> 460
~ __dispatch_timer_heap_shrink : 284 -> 276
~ __dispatch_timer_heap_grow : 324 -> 316
~ __dispatch_unote_register_muxed : 2176 -> 2172
~ __dispatch_event_loop_leave_deferred : 1380 -> 1384
~ __dispatch_kq_fill_workloop_sync_event : 960 -> 1044
~ __dispatch_event_loop_cancel_waiter : 932 -> 936
~ __dispatch_event_loop_wait_for_ownership : 2200 -> 2352
~ __dispatch_event_loop_end_ownership : 1440 -> 1432
~ __dispatch_mach_notify_merge : 1188 -> 1184
~ _firehose_buffer_update_limits_unlocked : 944 -> 940
~ _firehose_client_reconnect : 3024 -> 3004
~ _firehose_buffer_ring_enqueue : 932 -> 928
~ _firehose_buffer_tracepoint_reserve_slow : 3728 -> 3720
~ _firehose_buffer_tracepoint_reserve_wait_for_chunks_from_logd : 2980 -> 2972
~ __dispatch_stream_complete_operation : 432 -> 428
~ __dispatch_stream_enqueue_operation : 320 -> 308
~ __dispatch_fd_entry_create_with_fd : 632 -> 628
~ __dispatch_disk_init : 584 -> 580
~ _continuation_address : 256 -> 252
~ _supermap_address : 40 -> 36
~ _alloc_continuation_from_first_page : 264 -> 260
~ _bitmap_address : 56 -> 52
~ __dispatch_alloc_maybe_madvise_page : 548 -> 544
CStrings:
+ "sync-hint"
```
