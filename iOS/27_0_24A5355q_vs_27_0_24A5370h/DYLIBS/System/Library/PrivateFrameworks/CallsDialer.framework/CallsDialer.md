## CallsDialer

> `/System/Library/PrivateFrameworks/CallsDialer.framework/CallsDialer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4278c` | `0x43780` | **`+0xff4`** |
| `__AUTH_CONST.__const` | `0xc00` | `0xcf8` | **`+0xf8`** |
| `__TEXT.__const` | `0x16f4` | `0x1794` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x890` | `0x922` | **`+0x92`** |
| `__TEXT.__cstring` | `0x11af` | `0x122f` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x1154` | `0x11d4` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0xb10` | `0xb78` | **`+0x68`** |
| `__TEXT.__swift5_capture` | `0x1ec` | `0x240` | **`+0x54`** |
| `__AUTH_CONST.__objc_const` | `0x5d00` | `0x5d40` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x274e` | `0x278e` | **`+0x40`** |
| `__DATA.__data` | `0xc78` | `0xca0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x16c0` | `0x16e0` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x6b0` | `0x6d0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3f24` | `0x3f44` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x5a1` | `0x5c1` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1238` | `0x1258` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x57c` | `0x598` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x3428` | `0x3440` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x64` | `0x78` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x710` | `0x720` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x8c` | `0x94` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x5c` | `0x60` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x104` | `0x100` | **`-0x4`** |

### Other Changes

```diff

-3060.100.14.2.1
+143.100.11.2.1

-  Functions: 1640
-  Symbols:   2248
-  CStrings:  354
+  Functions: 1654
+  Symbols:   2263
+  CStrings:  358
Symbols:
+ ___swift_closure_destructor.42Tm
+ ___swift_memcpy4_4
+ _objc_retain_x28
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_bridgeObjectRetain_n
+ _swift_release_x24
+ _swift_release_x27
+ _swift_retain_x24
+ _swift_retain_x28
+ _symbolic ScGyytG
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ s6UInt32V
+ _symbolic _____Sg 11CallsDialer38KeypadBusinessAndContactsSearchResultsC
+ _symbolic _____ySaySo21MPContactSearchResultCG7results_Sb16hasCompleteMatchtSgG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySaySo21MPContactSearchResultCG7results_Sb16hasCompleteMatchtSg_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____y_____SgG 2os21OSAllocatedUnfairLockV 11CallsDialer20BusinessSearchResultV
+ _symbolic _____y_____Sg_____G s13ManagedBufferCsRi__rlE 11CallsDialer20BusinessSearchResultV So16os_unfair_lock_sV
+ _type_layout_string So16os_unfair_lock_sV
- ___swift_closure_destructor.12Tm
- ___swift_closure_destructor.19Tm
- ___swift_closure_destructor.4Tm
- _symbolic SaySo21MPContactSearchResultCG7results_Sb16hasCompleteMatchtSg
CStrings:
+ "(contactResults="
+ ", businessResult="
+ ", contactResultsHasCompleteMatch="
+ "KEYPAD_DELETE_AX_LABEL"
+ "[KeypadDataProvider] Failed to complete finding data results for phone number (%s) within time limit (%s). Returning partial completed results %s"
- "[KeypadDataProvider] Failed to find results for phone number (%s) within time limit (%s)."
```
