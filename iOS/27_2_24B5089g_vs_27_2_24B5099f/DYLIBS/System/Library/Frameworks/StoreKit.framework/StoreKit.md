## StoreKit

> `/System/Library/Frameworks/StoreKit.framework/StoreKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f5918` | `0x1f4500` | **`-0x1418`** |
| `__TEXT.__eh_frame` | `0x12be8` | `0x12c78` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0xa0b0` | `0xa0e0` | **`+0x30`** |
| `__TEXT.__const` | `0x19304` | `0x192e4` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x1dc0` | `0x1dd0` | **`+0x10`** |
| `__DATA.__data` | `0x6890` | `0x6888` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x3c4c` | `0x3c50` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x11d8` | `0x11dc` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-816.1.14.0.0
+816.1.16.0.0

-  Functions: 15795
-  Symbols:   7226
+  Functions: 15830
+  Symbols:   7223
Symbols:
+ ___swift_closure_destructor.165Tm
+ ___swift_closure_destructor.205Tm
+ ___swift_closure_destructor.209Tm
+ ___swift_closure_destructor.43Tm
+ ___swift_closure_destructor.52Tm
+ ___swift_closure_destructor.57Tm
+ ___swift_closure_destructor.64Tm
+ ___swift_closure_destructor.89Tm
- _OUTLINED_FUNCTION_602
- _OUTLINED_FUNCTION_603
- ___swift_closure_destructor.10Tm
- ___swift_closure_destructor.12Tm
- ___swift_closure_destructor.147Tm
- ___swift_closure_destructor.158Tm
- ___swift_closure_destructor.164Tm
- ___swift_closure_destructor.208Tm
- ___swift_closure_destructor.51Tm
- ___swift_closure_destructor.63Tm
- ___swift_closure_destructor.7Tm
CStrings:
+ "00:53:06"
+ "Sep 28 2026"
- "22:36:01"
- "Sep 13 2026"
```
