## fairplaydeviceidentityd

> `/usr/libexec/fairplaydeviceidentityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5522a8` | `0x5a7edc` | **`+0x55c34`** |
| `__DATA_CONST.__const` | `0x322a0` | `0x35dc0` | **`+0x3b20`** |
| `__TEXT.__const` | `0x4de10` | `0x4e280` | **`+0x470`** |
| `__DATA.__common` | `0xb40` | `0xce8` | **`+0x1a8`** |
| `__DATA.__data` | `0x1e70` | `0x1fc0` | **`+0x150`** |
| `__TEXT.__unwind_info` | `0x4d8` | `0x530` | **`+0x58`** |
| `__TEXT.__eh_frame` | `0xd0` | `0x100` | **`+0x30`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`

### Other Changes

```diff

-  Functions: 318
-  Symbols:   176
+  Functions: 340
+  Symbols:   199
Symbols:
+ _clock_gettime
+ _clock_gettime_nsec_np
+ _fclose
+ _fopen
+ _fprintf
+ _fwrite
+ _nanosleep
+ _pthread_cond_broadcast
+ _pthread_cond_destroy
+ _pthread_cond_init
+ _pthread_cond_signal
+ _pthread_cond_timedwait
+ _pthread_cond_wait
+ _pthread_create
+ _pthread_detach
+ _pthread_join
+ _pthread_mutex_destroy
+ _pthread_mutex_init
+ _pthread_mutex_lock
+ _pthread_mutex_unlock
+ _qsort
+ _snprintf
+ _strlen
```
