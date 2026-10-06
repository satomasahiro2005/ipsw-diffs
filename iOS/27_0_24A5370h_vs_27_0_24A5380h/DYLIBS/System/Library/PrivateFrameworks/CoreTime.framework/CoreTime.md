## CoreTime

> `/System/Library/PrivateFrameworks/CoreTime.framework/CoreTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x684c` | `0x6ba8` | **`+0x35c`** |
| `__AUTH.__objc_data` | `—` | `0x78` | **`+0x78`** |
| `__DATA_DIRTY.__objc_data` | `0xa0` | `0x28` | **`-0x78`** |
| `__TEXT.__cstring` | `0xee9` | `0xf1b` | **`+0x32`** |
| `__AUTH_CONST.__cfstring` | `0xe00` | `0xe20` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x140` | `0x160` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x4e0` | `0x4f8` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x504` | `0x518` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x250` | `0x260` | **`+0x10`** |
| `__DATA.__bss` | `0x68` | `0x70` | **`+0x8`** |
| `__TEXT.__const` | `0xf0` | `0xf8` | **`+0x8`** |

### Other Changes

```diff

-340.0.8.0.0
+340.0.11.0.0

-  Functions: 195
-  Symbols:   420
-  CStrings:  181
+  Functions: 201
+  Symbols:   427
+  CStrings:  183
Symbols:
+ GCC_except_table27
+ GCC_except_table35
+ GCC_except_table42
+ _CFAbsoluteTimeGetCurrent
+ _TMGetBestEffortTime
+ _TMIsAutomaticTimeEnabledAsync
+ __TMGetKernelMonotonicClock.onceToken
+ ___TMIsAutomaticTimeEnabledAsync_block_invoke
+ ___TMIsAutomaticTimeEnabledAsync_block_invoke_2
+ ____TMGetKernelMonotonicClock_block_invoke
- GCC_except_table23
- GCC_except_table31
- GCC_except_table38
CStrings:
+ "TMGetBestEffortTime"
+ "TMIsAutomaticTimeEnabledAsync"
```
