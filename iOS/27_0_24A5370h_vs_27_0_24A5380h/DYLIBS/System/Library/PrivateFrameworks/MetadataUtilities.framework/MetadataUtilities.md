## MetadataUtilities

> `/System/Library/PrivateFrameworks/MetadataUtilities.framework/MetadataUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c34c` | `0x5d7b4` | **`+0x1468`** |
| `__AUTH.__objc_data` | `0x190` | `0x2d0` | **`+0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x1e0` | `0xa0` | **`-0x140`** |
| `__TEXT.__cstring` | `0x71df` | `0x722b` | **`+0x4c`** |
| `__TEXT.__unwind_info` | `0xc78` | `0xcb0` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0xd60` | `0xd88` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x1a18` | `0x1a3a` | **`+0x22`** |
| `__TEXT.__const` | `0x3d56` | `0x3d72` | **`+0x1c`** |
| `__DATA.__bss` | `0x2d8` | `0x2e8` | **`+0x10`** |
| `__DATA.__common` | `0x850` | `0x860` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x348` | `0x338` | **`-0x10`** |
| `__DATA_DIRTY.__common` | `0xf0` | `0xe0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x158` | `0x160` | **`+0x8`** |

### Other Changes

```diff

-2448.100.0.0.0
+2451.1.101.0.0

-  Functions: 1417
-  Symbols:   1891
-  CStrings:  1267
+  Functions: 1446
+  Symbols:   1922
+  CStrings:  1272
Symbols:
+ __db_rwlock_init
+ __db_write_lock
+ __db_write_lock_downgraded
+ _db_convert_to_reader
+ _db_downgrade_lock
+ _db_dryrun_lock
+ _db_longread_lock
+ _db_longread_unlock
+ _db_read_lock
+ _db_read_unlock
+ _db_rwlock_alloc_waiter
+ _db_rwlock_destroy
+ _db_rwlock_is_locked
+ _db_rwlock_reader_excluded
+ _db_rwlock_unlock_unknown
+ _db_rwlock_wait
+ _db_rwlock_waiter_list_dequeue_from_list_inner
+ _db_rwlock_waiter_list_enqueue_inner
+ _db_rwlock_waiter_list_prepend
+ _db_rwlock_wakeup
+ _db_upgrade_lock
+ _db_write_unlock
+ _db_writelock_assertlock
+ _db_writer_yield_lock
+ _exc_pthread_key
+ _pthread_cond_signal
+ _pthread_mutex_trylock
+ _pthread_override_qos_class_end_np
+ _pthread_override_qos_class_start_np
+ _pthread_self
+ _qos_level
CStrings:
+ "*warn* fd[%d] - len:%d %{public}s"
+ "list->head==0"
+ "lock->writer != pthread_self()"
+ "sdb2_rwlock.c"
+ "waiter->threadid"
```
