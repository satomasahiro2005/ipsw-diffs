## AuthenticationServices

> `/System/Library/Frameworks/AuthenticationServices.framework/AuthenticationServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14376c` | `0x1431a8` | **`-0x5c4`** |
| `__AUTH_CONST.__const` | `0x9bd8` | `0x9a98` | **`-0x140`** |
| `__TEXT.__swift5_capture` | `0xea8` | `0xde8` | **`-0xc0`** |
| `__TEXT.__eh_frame` | `0x6eac` | `0x6e04` | **`-0xa8`** |
| `__TEXT.__oslogstring` | `0x34db` | `0x356b` | **`+0x90`** |
| `__TEXT.__const` | `0x13f64` | `0x13ef4` | **`-0x70`** |
| `__DATA.__data` | `0x38e0` | `0x38a0` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0x328e` | `0x324e` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x5d40` | `0x5d00` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x16b8` | `0x1680` | **`-0x38`** |
| `__TEXT.__gcc_except_tab` | `0x1204` | `0x11d4` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x10130` | `0x10150` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4ca0` | `0x4cb8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x10a0` | `0x1090` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x8074` | `0x8064` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x500` | `0x508` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x250` | `0x248` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x2cc` | `0x2d4` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x6fc` | `0x700` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-625.1.24.10.1
+625.1.29.10.3

-  Functions: 8193
+  Functions: 8182

-  CStrings:  1350
+  CStrings:  1352
Symbols:
+ -[_ASPasswordManagerIconController resumeFetching]
+ -[_ASPasswordManagerIconController suspendFetching]
+ GCC_except_table60
+ GCC_except_table66
+ GCC_except_table67
+ _OBJC_IVAR_$__ASPasswordManagerIconController._fetchingSuspended
+ ___50-[_ASPasswordManagerIconController resumeFetching]_block_invoke
+ ___51-[_ASPasswordManagerIconController suspendFetching]_block_invoke
- GCC_except_table54
- GCC_except_table62
- ___73-[_ASAgentPeriodicMaintenanceActivity _runActivityWithCompletionHandler:]_block_invoke_4
- ___73-[_ASAgentPeriodicMaintenanceActivity _runActivityWithCompletionHandler:]_block_invoke_5
- ___73-[_ASAgentPeriodicMaintenanceActivity _runActivityWithCompletionHandler:]_block_invoke_6
- _symbolic Sny_____G 10Foundation4DateV
- _symbolic So25WBSPasswordWarningManagerC
- _symbolic _____5lower_AA5uppert 10Foundation4DateV
CStrings:
+ "Allow “%@” to temporarily access verification codes?"
+ "Skipping touch icon fetch while suspended; domain=%{sensitive, mask.hash}@"
+ "Suspending icon fetching; cancelling %d in-flight request(s)"
+ "“%@” will be able to use one-time verification codes in apps like %@ while it signs in to your accounts."
+ "“%@” will be able to use one-time verification codes while it signs in to your accounts."
+ "\xf01"
- "Allow “%@” to temporarily access verification codes you receive?"
- "This will make one-time verification codes available to “%@” for up to %@."
- "This will make one-time verification codes received in apps like %@ available to “%@” for up to %@."
- "\xf0!"
```
