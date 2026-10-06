## AccessibilityUI

> `/System/Library/PrivateFrameworks/AccessibilityUI.framework/AccessibilityUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4410` | `0x4930` | **`+0x520`** |
| `__TEXT.__oslogstring` | `0x812` | `0x8b9` | **`+0xa7`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a0` | `0x500` | **`+0x60`** |
| `__TEXT.__cstring` | `0x272` | `0x2cb` | **`+0x59`** |
| `__AUTH_CONST.__cfstring` | `0x140` | `0x180` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x26c` | `0x2a4` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x610` | `0x640` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x484` | `0x4b4` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x20` | `0x40` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x228` | `0x248` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x128` | `0x148` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 96
-  Symbols:   288
-  CStrings:  56
+  Functions: 101
+  Symbols:   301
+  CStrings:  63
Symbols:
+ -[AXUIClientConnection _acquireServerWakeAssertionIfNeeded]
+ -[AXUIClientConnection _releaseServerWakeAssertion]
+ -[AXUIClientConnection serverWakeAssertion]
+ -[AXUIClientConnection setServerWakeAssertion:]
+ GCC_except_table54
+ GCC_except_table59
+ GCC_except_table61
+ GCC_except_table63
+ GCC_except_table67
+ GCC_except_table73
+ GCC_except_table86
+ GCC_except_table87
+ GCC_except_table88
+ GCC_except_table95
+ _OBJC_CLASS_$_NSBundle
+ _OBJC_CLASS_$_RBSAssertion
+ _OBJC_CLASS_$_RBSProcessIdentity
+ _OBJC_CLASS_$_RBSTarget
+ _OBJC_IVAR_$_AXUIClientConnection._serverWakeAssertion
+ ___59-[AXUIClientConnection _acquireServerWakeAssertionIfNeeded]_block_invoke
+ ___block_descriptor_32_e34_v24?0"RBSAssertion"8"NSError"16l
- GCC_except_table52
- GCC_except_table58
- GCC_except_table62
- GCC_except_table68
- GCC_except_table76
- GCC_except_table78
- GCC_except_table82
- GCC_except_table90
CStrings:
+ ")"
+ "AXUIClient in %@ keeping AXUIServer resumable"
+ "AXUIServer wake assertion invalidated: %@. %@"
+ "AXUIServer wake assertion invalidation error: %@"
+ "Acquiring AXUIServer wake assertion"
+ "Releasing AXUIServer wake assertion"
+ "unknown"
+ "v24@?0@\"RBSAssertion\"8@\"NSError\"16"
- "("
```
