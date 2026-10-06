## PegasusKit

> `/System/Library/PrivateFrameworks/PegasusKit.framework/PegasusKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x74e8` | `0x84e8` | **`+0x1000`** |
| `__AUTH.__data` | `0xbe0` | `0x150` | **`-0xa90`** |
| `__TEXT.__text` | `0x10603c` | `0x1067cc` | **`+0x790`** |
| `__DATA.__data` | `0x11f0` | `0xc98` | **`-0x558`** |
| `__AUTH.__objc_data` | `0x2d0` | `0x50` | **`-0x280`** |
| `__DATA_DIRTY.__objc_data` | `0x460` | `0x6e0` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x325f` | `0x32ef` | **`+0x90`** |
| `__DATA.__bss` | `0x2b20` | `0x2aa0` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x1600` | `0x1680` | **`+0x80`** |
| `__DATA.__common` | `0xd0` | `0x110` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x31c0` | `0x31e8` | **`+0x28`** |
| `__TEXT.__const` | `0x6980` | `0x69a0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1d18` | `0x1d30` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-3605.21.1.1.1
+3605.23.1.1.1

-  Functions: 5919
-  Symbols:   1698
-  CStrings:  599
+  Functions: 5930
+  Symbols:   1703
+  CStrings:  600
Symbols:
+ _OUTLINED_FUNCTION_424
+ _OUTLINED_FUNCTION_425
+ _OUTLINED_FUNCTION_426
+ _pow
+ _swift_stdlib_random
CStrings:
+ "BackoffPolicy misconfigured: maxBackoff (%{public}s) must be > initialBackoff (%{public}s); jitter window will collapse to 0 until corrected."
```
