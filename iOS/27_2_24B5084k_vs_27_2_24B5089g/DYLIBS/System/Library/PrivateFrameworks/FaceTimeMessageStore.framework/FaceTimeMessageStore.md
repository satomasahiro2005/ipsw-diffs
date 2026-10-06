## FaceTimeMessageStore

> `/System/Library/PrivateFrameworks/FaceTimeMessageStore.framework/FaceTimeMessageStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b3fcc` | `0x1b5b24` | **`+0x1b58`** |
| `__DATA_DIRTY.__data` | `0x4ca0` | `0x5570` | **`+0x8d0`** |
| `__AUTH.__data` | `0xa20` | `0x318` | **`-0x708`** |
| `__DATA.__bss` | `0x12a60` | `0x123e0` | **`-0x680`** |
| `__DATA_DIRTY.__bss` | `0xab00` | `0xb180` | **`+0x680`** |
| `__AUTH_CONST.__const` | `0xdac8` | `0xd8c8` | **`-0x200`** |
| `__TEXT.__eh_frame` | `0x10704` | `0x1089c` | **`+0x198`** |
| `__DATA.__data` | `0x2140` | `0x1fc0` | **`-0x180`** |
| `__TEXT.__oslogstring` | `0xa4db` | `0xa60b` | **`+0x130`** |
| `__TEXT.__swift5_capture` | `0x2f00` | `0x2e50` | **`-0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x5998` | `0x59f8` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x273d` | `0x277d` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x3c30` | `0x3c60` | **`+0x30`** |
| `__DATA.__common` | `0x128` | `0x108` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `0x498` | `0x4b8` | **`+0x20`** |
| `__TEXT.__const` | `0x12d00` | `0x12ce0` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x575e` | `0x577a` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x1ae0` | `0x1af8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x72e8` | `0x72f8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1858` | `0x1850` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x4b28` | `0x4b30` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x9e4` | `0x9ec` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x550` | `0x558` | **`+0x8`** |

### Other Changes

```diff

-1626.200.53.0.0
+1626.200.65.0.0

-  Functions: 11462
-  Symbols:   2983
-  CStrings:  939
+  Functions: 11480
+  Symbols:   2982
+  CStrings:  942
Symbols:
+ ___swift_closure_destructor.128Tm
+ ___swift_closure_destructor.196Tm
+ ___swift_closure_destructor.244Tm
+ ___swift_closure_destructor.378Tm
+ ___swift_memcpy128_8
+ _symbolic _____Sg 18TelephonyUtilities23MessageStoreBadgeCountsV
+ _symbolic _____Sg_ABt 18TelephonyUtilities23MessageStoreBadgeCountsV
- _OUTLINED_FUNCTION_336
- _OUTLINED_FUNCTION_337
- _OUTLINED_FUNCTION_338
- ___swift_closure_destructor.137Tm
- ___swift_closure_destructor.230Tm
- ___swift_closure_destructor.321Tm
- ___swift_closure_destructor.89Tm
- ___swift_memcpy88_8
CStrings:
+ "Failed to check whether the sender of message with recordUUID %{public}s is a known contact; treating as unknown: %{public}@"
+ "Message store counts unchanged %{public}s; skipping write"
+ "Skipping %{public}s inference for message with recordUUID %{public}s because the sender is a known contact"
```
