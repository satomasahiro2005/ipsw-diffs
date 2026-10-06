## FileIndexerDaemon

> `/System/Library/PrivateFrameworks/FileIndexerDaemon.framework/FileIndexerDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x3500` | `0x2d80` | **`-0x780`** |
| `__DATA_DIRTY.__bss` | `0x1580` | `0x1d00` | **`+0x780`** |
| `__DATA_DIRTY.__data` | `0x1878` | `0x1fd8` | **`+0x760`** |
| `__AUTH.__data` | `0x578` | `0xa0` | **`-0x4d8`** |
| `__TEXT.__text` | `0x685b0` | `0x68164` | **`-0x44c`** |
| `__DATA.__data` | `0x920` | `0x6f8` | **`-0x228`** |
| `__TEXT.__eh_frame` | `0x1da8` | `0x1e48` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x23ba` | `0x23fa` | **`+0x40`** |
| `__TEXT.__const` | `0x33a4` | `0x3374` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x11c8` | `0x11f8` | **`+0x30`** |
| `__DATA.__common` | `0x38` | `0x20` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0x108` | `0x120` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x458` | `0x46c` | **`+0x14`** |
| `__TEXT.__swift5_typeref` | `0x11b2` | `0x11a0` | **`-0x12`** |
| `__DATA_DIRTY.__objc_data` | `0x4e0` | `0x4f0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x1290` | `0x12a0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xf28` | `0xf20` | **`-0x8`** |
| `__AUTH_CONST.__objc_const` | `0x19d0` | `0x19d8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x538` | `0x540` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x6c` | `0x68` | **`-0x4`** |

### Other Changes

```diff

-4838.0.29.502.2
+4838.0.70.0.0

-  Functions: 1579
-  Symbols:   819
-  CStrings:  285
+  Functions: 1581
+  Symbols:   814
+  CStrings:  286
Symbols:
+ ___swift_closure_destructor.118Tm
+ ___swift_closure_destructor.295Tm
+ ___swift_closure_destructor.329Tm
+ ___swift_closure_destructor.93Tm
+ ___swift_closure_destructor.97Tm
- ___swift_closure_destructor.119Tm
- ___swift_closure_destructor.297Tm
- ___swift_closure_destructor.331Tm
- ___swift_closure_destructor.94Tm
- ___swift_closure_destructor.98Tm
- _get_type_metadata 15Synchronization5MutexVySDy10Foundation4UUIDV17FileIndexerDaemon13StateListenerVGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySbG noncopyable
- _get_type_metadata 15Synchronization5MutexVys6UInt64VG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "searchableItemIdentifier requested for %{public}s"
```
