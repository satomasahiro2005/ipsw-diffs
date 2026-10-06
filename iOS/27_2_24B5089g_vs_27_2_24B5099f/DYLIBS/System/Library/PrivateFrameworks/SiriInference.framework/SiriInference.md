## SiriInference

> `/System/Library/PrivateFrameworks/SiriInference.framework/SiriInference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x311cb4` | `0x312344` | **`+0x690`** |
| `__DATA.__bss` | `0x2e120` | `0x2dd20` | **`-0x400`** |
| `__DATA_DIRTY.__bss` | `0x9600` | `0x9a00` | **`+0x400`** |
| `__TEXT.__unwind_info` | `0xaf00` | `0xaf38` | **`+0x38`** |
| `__DATA_DIRTY.__data` | `0x8d80` | `0x8db0` | **`+0x30`** |
| `__TEXT.__cstring` | `0xe5b4` | `0xe5e4` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x283b8` | `0x283e0` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x12430` | `0x1244c` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x8c62` | `0x8c74` | **`+0x12`** |
| `__AUTH_CONST.__auth_got` | `0x2fb8` | `0x2fc8` | **`+0x10`** |
| `__TEXT.__const` | `0x25ed0` | `0x25ee0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x5954` | `0x595c` | **`+0x8`** |

### Other Changes

```diff

-3605.13.1.0.0
+3605.19.1.0.0

-  Functions: 20082
-  Symbols:   4985
-  CStrings:  3201
+  Functions: 20089
+  Symbols:   4986
+  CStrings:  3202
Symbols:
+ ___swift_closure_destructor.548Tm
+ _symbolic _____ySbG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySb_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
- ___swift_closure_destructor.547Tm
- _symbolic Sbz_Xx
CStrings:
+ "com.apple.siriinferenced.expirationHandler"
```
