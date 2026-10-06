## libdispatch_debug.dylib

> `/System/DriverKit/usr/lib/system/libdispatch_debug.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb920` | `0xbb96c` | **`+0x4c`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH_CONST.__auth_got`
- `__AUTH_CONST.__const`
- `__DATA_CONST.__const`
- `__TEXT.__dof_dispatch`
- `__TEXT.__dof_voucher`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ __dispatch_timers_run : 2424 -> 2428
~ __dispatch_timer_unote_arm : 1488 -> 1496
~ __dispatch_timer_heap_remove : 1096 -> 1104
~ _voucher_activity_create_with_data_2 : 7868 -> 7884
~ _voucher_activity_flush : 1492 -> 1500
~ _voucher_activity_trace_v_2 : 5160 -> 5168
~ _firehose_client_start_quarantine : 3660 -> 3684
```
