## BridgePreferences

> `/System/Library/PrivateFrameworks/BridgePreferences.framework/BridgePreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39130` | `0x392ac` | **`+0x17c`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a18` | `0x2a58` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3248` | `0x3260` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x7b0` | `0x7b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xdd8` | `0xde0` | **`+0x8`** |

### Other Changes

```diff

-1359.0.0.0.0
+1359.3.0.0.0

-  Functions: 1412
-  Symbols:   2548
+  Functions: 1414
+  Symbols:   2550
Symbols:
+ -[BPSWelcomeOptinViewController revalidateColumnLayoutIfNeeded]
+ -[BPSWelcomeOptinViewController viewIsAppearing:]
+ GCC_except_table61
- GCC_except_table59
Functions:
+ -[BPSWelcomeOptinViewController revalidateColumnLayoutIfNeeded]
+ -[BPSWelcomeOptinViewController viewWillDisappear:]
```
