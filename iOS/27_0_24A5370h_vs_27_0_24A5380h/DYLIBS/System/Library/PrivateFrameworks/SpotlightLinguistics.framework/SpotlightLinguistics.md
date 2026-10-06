## SpotlightLinguistics

> `/System/Library/PrivateFrameworks/SpotlightLinguistics.framework/SpotlightLinguistics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x482b8` | `0x472ec` | **`-0xfcc`** |
| `__TEXT.__cstring` | `0x2ca0` | `0x2c54` | **`-0x4c`** |
| `__AUTH_CONST.__auth_got` | `0xc28` | `0xc00` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x1030` | `0x1008` | **`-0x28`** |
| `__TEXT.__const` | `0x5520` | `0x5510` | **`-0x10`** |
| `__DATA.__common` | `0xcc` | `0xc4` | **`-0x8`** |

### Other Changes

```diff

-2448.100.0.0.0
+2451.1.101.0.0

-  Functions: 1315
-  Symbols:   1836
-  CStrings:  1020
+  Functions: 1288
+  Symbols:   1807
+  CStrings:  1016
Symbols:
- __db_write_lock_downgraded
- _db_convert_to_reader
- _db_downgrade_lock
- _db_dryrun_lock
- _db_longread_lock
- _db_longread_unlock
- _db_read_unlock
- _db_rwlock_alloc_waiter
- _db_rwlock_reader_excluded
- _db_rwlock_wait
- _db_rwlock_waiter_list_enqueue_inner
- _db_rwlock_wakeup
- _db_upgrade_lock
- _db_write_unlock
- _db_writelock_assertlock
- _db_writer_yield_lock
- _exc_pthread_key
- _pthread_cond_destroy
- _pthread_cond_init
- _pthread_cond_signal
- _pthread_cond_wait
- _pthread_mutex_destroy
- _pthread_mutex_init
- _pthread_mutex_trylock
- _pthread_override_qos_class_end_np
- _pthread_override_qos_class_start_np
- _pthread_self
- _qos_class_self
- _qos_level
CStrings:
- "list->head==0"
- "lock->writer != pthread_self()"
- "sdb2_rwlock.c"
- "waiter->threadid"
```
