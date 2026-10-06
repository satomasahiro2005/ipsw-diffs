## libsystem_pthread_debug.dylib

> `/System/DriverKit/usr/lib/system/libsystem_pthread_debug.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c200` | `0x1c1c8` | **`-0x38`** |

### Same-size Content Changes

- `__DATA_DIRTY.__data`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ _pthread_qos_max_parallelism : 796 -> 784
~ _pthread_time_constraint_max_parallelism : 480 -> 472
~ __pthread_key_set_destructor : 200 -> 196
~ __pthread_key_unset_destructor : 112 -> 108
~ __pthread_tsd_cleanup_key : 156 -> 152
~ __pthread_atfork_prepare_handlers : 312 -> 308
~ __pthread_atfork_prepare : 256 -> 252
~ __pthread_atfork_parent : 208 -> 204
~ __pthread_atfork_parent_handlers : 304 -> 300
~ __pthread_atfork_child : 252 -> 248
~ __pthread_atfork_child_handlers : 312 -> 308
```
