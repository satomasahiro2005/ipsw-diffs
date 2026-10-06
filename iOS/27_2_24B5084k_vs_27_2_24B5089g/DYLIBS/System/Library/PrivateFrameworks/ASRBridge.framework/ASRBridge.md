## ASRBridge

> `/System/Library/PrivateFrameworks/ASRBridge.framework/ASRBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5577c` | `0x56c68` | **`+0x14ec`** |
| `__AUTH_CONST.__const` | `0x16b8` | `0x1760` | **`+0xa8`** |
| `__TEXT.__eh_frame` | `0x298` | `0x318` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x48bb` | `0x492b` | **`+0x70`** |
| `__TEXT.__const` | `0xe48` | `0xea8` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x1bc0` | `0x1c00` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0xbdd` | `0xc1d` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0xf94` | `0xfd0` | **`+0x3c`** |
| `__TEXT.__swift5_fieldmd` | `0x7bc` | `0x7f0` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0x7e8` | `0x818` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0xa0c` | `0xa36` | **`+0x2a`** |
| `__DATA_DIRTY.__objc_data` | `0x728` | `0x750` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x12d8` | `0x12f8` | **`+0x20`** |
| `__DATA.__data` | `0x9b0` | `0x9d0` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x50` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x8d0` | `0x8e0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xb80` | `0xb70` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x6a8` | `0x6b8` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x278` | `0x280` | **`+0x8`** |
| `__DATA.__common` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x5c` | `0x60` | **`+0x4`** |

### Other Changes

```diff

-3605.23.1.0.0
+3605.25.1.0.0

-  Functions: 944
-  Symbols:   612
-  CStrings:  329
+  Functions: 962
+  Symbols:   620
+  CStrings:  331
Symbols:
+ _AFIsATVOnly
+ ___swift_closure_destructor.129Tm
+ ___swift_closure_destructor.144Tm
+ ___swift_closure_destructor.153Tm
+ ___swift_closure_destructor.207Tm
+ ___swift_memcpy4_4
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ySDyS2SGG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySDyS2SG_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _type_layout_string So16os_unfair_lock_sV
- ___swift_closure_destructor.125Tm
- ___swift_closure_destructor.140Tm
- ___swift_closure_destructor.149Tm
- ___swift_closure_destructor.203Tm
CStrings:
+ "Mapped fanned out tcuId(s) back to CoreSpeech's: %s"
+ "No fanned out tcuId matched %s for request: %s"
```
