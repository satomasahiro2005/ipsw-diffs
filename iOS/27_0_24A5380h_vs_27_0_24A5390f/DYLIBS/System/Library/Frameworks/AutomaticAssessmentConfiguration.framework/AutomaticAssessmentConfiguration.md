## AutomaticAssessmentConfiguration

> `/System/Library/Frameworks/AutomaticAssessmentConfiguration.framework/AutomaticAssessmentConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a7c` | `0x7ae8` | **`+0x6c`** |
| `__AUTH_CONST.__objc_const` | `0x1010` | `0x1040` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x87c` | `0x894` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x6e0` | `0x6f0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x104` | `0x108` | **`+0x4`** |

### Other Changes

```diff

-55.0.0.0.0
+56.0.0.0.0

-  Functions: 256
-  Symbols:   447
+  Functions: 258
+  Symbols:   450
Symbols:
+ -[AEAssessmentConfiguration allowsAccessibilityFullKeyboardAccess]
+ -[AEAssessmentConfiguration setAllowsAccessibilityFullKeyboardAccess:]
+ _OBJC_IVAR_$_AEAssessmentConfiguration._allowsAccessibilityFullKeyboardAccess
```
