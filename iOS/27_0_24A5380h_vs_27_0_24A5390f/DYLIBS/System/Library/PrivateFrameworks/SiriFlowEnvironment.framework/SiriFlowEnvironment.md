## SiriFlowEnvironment

> `/System/Library/PrivateFrameworks/SiriFlowEnvironment.framework/SiriFlowEnvironment`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x1010` | `0xf90` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0xd90` | `0xe10` | **`+0x80`** |
| `__TEXT.__text` | `0x28b14` | `0x28b94` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x140` | `0x100` | **`-0x40`** |
| `__TEXT.__cstring` | `0x5ab` | `0x58b` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x93a` | `0x94c` | **`+0x12`** |
| `__AUTH_CONST.__auth_got` | `0x858` | `0x868` | **`+0x10`** |
| `__DATA.__data` | `0x300` | `0x2f8` | **`-0x8`** |
| `__DATA_DIRTY.__data` | `0x758` | `0x760` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xf58` | `0xf60` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-3520.17.1.0.0
+3600.1.3.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 1745
-  Symbols:   3122
-  CStrings:  90
+  Functions: 1747
+  Symbols:   3125
+  CStrings:  88
Symbols:
+ _$s15Synchronization5MutexVMn
+ _$s19SiriFlowEnvironment24RefreshableSharedContextC11contextLock33_B61EE3D8A82939508D14603AB10F4B11LL15Synchronization5MutexVyAA0eF7Service_pSgGvpWvd
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _symbolic _____y______pSgG 15Synchronization5MutexVAARi_zrlE 19SiriFlowEnvironment20SharedContextServiceP
- _$s19SiriFlowEnvironment20SharedContextService_pSgWOd
- _$s19SiriFlowEnvironment24RefreshableSharedContextC06sharedF0AA0eF7Service_pSgvpWvd
CStrings:
+ "AudioAccessory"
- "AudioAccessory1,"
- "AudioAccessory5,"
- "AudioAccessory6,"
```
