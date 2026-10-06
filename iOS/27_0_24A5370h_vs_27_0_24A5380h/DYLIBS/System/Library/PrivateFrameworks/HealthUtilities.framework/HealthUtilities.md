## HealthUtilities

> `/System/Library/PrivateFrameworks/HealthUtilities.framework/HealthUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x148` | `0x308` | **`+0x1c0`** |
| `__AUTH.__data` | `0x1c0` | `0x88` | **`-0x138`** |
| `__TEXT.__text` | `0xf854` | `0xf79c` | **`-0xb8`** |
| `__DATA.__data` | `0x1f8` | `0x168` | **`-0x90`** |
| `__DATA.__bss` | `0x1480` | `0x1400` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `—` | `0x80` | **`+0x80`** |
| `__TEXT.__cstring` | `0x5c` | `0x9c` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x5fc` | `0x606` | **`+0xa`** |
| `__DATA_CONST.__const` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x598` | `0x590` | **`-0x8`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 473
-  Symbols:   230
-  CStrings:  5
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 472
+  Symbols:   231
+  CStrings:  7
Symbols:
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_FORCE_LOAD_$_swiftos_$_HealthUtilities
+ _symbolic _____ySDySSypGG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____yxG 15Synchronization5MutexVAARi_zrlE
- _get_type_metadata 15HealthUtilities19UserDefaultStorableRzl15Synchronization5MutexVyxG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDySSypGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "com.apple.Health"
+ "com.apple.HealthKit"
```
