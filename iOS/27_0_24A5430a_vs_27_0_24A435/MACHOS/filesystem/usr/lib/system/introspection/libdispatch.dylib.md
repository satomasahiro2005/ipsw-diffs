## libdispatch.dylib

> `/usr/lib/system/introspection/libdispatch.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43378` | `0x433c8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xe88` | `0xe80` | **`-0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH_CONST.__auth_got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_DIRTY.__data`
- `__DATA_DIRTY.__objc_data`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```text
Functions:
~ __dispatch_workloop_invoke : 4228 -> 4232
~ __dispatch_root_queue_push_override_stealer : 400 -> 384
~ _voucher_activity_create_with_data_2 : 2468 -> 2472
~ _voucher_activity_flush : 364 -> 368
~ _voucher_activity_trace_v_2 : 2212 -> 2220
~ _firehose_buffer_ring_enqueue : 636 -> 628
~ _firehose_buffer_tracepoint_reserve_slow : 1024 -> 1040
~ _firehose_buffer_stream_chunk_install : 1192 -> 1196
~ _firehose_buffer_tracepoint_reserve_wait_for_chunks_from_logd : 1196 -> 1204
~ _firehose_client_start_quarantine : 1028 -> 1040
~ __dispatch_alloc_continuation_alloc : 268 -> 280
~ __dispatch_alloc_continuation_free : 188 -> 196
~ __dispatch_alloc_continuation_from_heap : 420 -> 440
~ __dispatch_alloc_maybe_madvise_page : 248 -> 252
```
