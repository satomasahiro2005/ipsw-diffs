## IOKit

> `/System/Library/Frameworks/IOKit.framework/Versions/A/IOKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2770` | `0xa2818` | **`+0xa8`** |
| `__DATA_CONST.__const` | `0x2c88` | `0x2cc8` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2288` | `0x2298` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-100287.0.0.0.0
+100288.0.5.0.1

-  Functions: 3570
-  Symbols:   3955
+  Functions: 3572
+  Symbols:   3957
Symbols:
+ __IOHIDEventCopyDebugInfo
+ ___IOEthernetControllerSetDispatchQueue_block_invoke_3
+ ___IOEthernetControllerSetDispatchQueue_block_invoke_4
- __IOHIDEventDebugInfo
CStrings:
+ "OSKEXT_BUILD_DATE 21:54:50 Jun 26 2026"
- "OSKEXT_BUILD_DATE 00:23:36 Jun 11 2026"
```
