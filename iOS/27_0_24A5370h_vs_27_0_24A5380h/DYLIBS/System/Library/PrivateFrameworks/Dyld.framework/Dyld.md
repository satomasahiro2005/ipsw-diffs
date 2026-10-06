## Dyld

> `/System/Library/PrivateFrameworks/Dyld.framework/Dyld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51d0c` | `0x51ad8` | **`-0x234`** |
| `__TEXT.__cstring` | `0x1374` | `0x13d7` | **`+0x63`** |
| `__DATA.__data` | `0xbb8` | `0xb78` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0xd71` | `0xd3b` | **`-0x36`** |
| `__TEXT.__const` | `0x3438` | `0x3408` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x258` | `0x240` | **`-0x18`** |
| `__AUTH.__data` | `0x1680` | `0x1670` | **`-0x10`** |
| `__AUTH_CONST.__weak_auth_got` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x11e0` | `0x11e8` | **`+0x8`** |

### Other Changes

```diff

-27056.0.0.0.0
+27059.3.0.0.0

-  Functions: 1454
-  Symbols:   1054
-  CStrings:  148
+  Functions: 1448
+  Symbols:   1051
+  CStrings:  152
Symbols:
+ __ZNSt3__119__allocate_at_leastB9fqn220106INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE24__emplace_back_slow_pathIJRKjEEEPjDpOT_
+ __ZSt28__throw_bad_array_new_lengthB9fqn220106v
+ __ZdlPv
+ __ZnwmSt19__type_descriptor_t
+ _abort
+ _task_resume2
+ _task_suspend2
+ _thread_resume2
+ _thread_suspend2
- _get_type_metadata 4Dyld10DeferrableOyAA11EnvironmentV4InfoVG noncopyable
- _get_type_metadata 4Dyld10DeferrableOyAA11SharedCacheV13ProcessRecordV4InfoVG noncopyable
- _get_type_metadata 4Dyld10DeferrableOyAA11SharedCacheV4InfoVG noncopyable
- _get_type_metadata 4Dyld10DeferrableOyAA5ImageV4InfoVG noncopyable
- _get_type_metadata 4Dyld10DeferrableOyAA7SegmentV4InfoVG noncopyable
- _get_type_metadata 4Dyld10DeferrableOyAA8AOTImageV4InfoVG noncopyable
- _get_type_metadata 4Dyld10DeferrableOyAA8SnapshotV4InfoVG noncopyable
- _get_type_metadata 4Dyld10DeferrableOyAA8SubCacheV4InfoVG noncopyable
- _get_type_metadata 4Dyld8MachTaskV noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _task_resume
- _task_suspend
- _thread_resume
- _thread_suspend
CStrings:
+ "/Library/Developer/CoreSimulator/Caches/dyld/"
+ "ProcessScavenger.cpp"
+ "TaskSuspender"
+ "threadCount > 0"
```
