## KeyboardSettings

> `/System/Library/PrivateFrameworks/KeyboardSettings.framework/KeyboardSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29d14` | `0x29c2c` | **`-0xe8`** |
| `__TEXT.__cstring` | `0x3678` | `0x35f8` | **`-0x80`** |
| `__AUTH_CONST.__cfstring` | `0x31c0` | `0x3180` | **`-0x40`** |
| `__AUTH_CONST.__const` | `0x330` | `0x310` | **`-0x20`** |
| `__DATA.__bss` | `0xf8` | `0xe8` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x2ab0` | `0x2ac0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x958` | `0x950` | **`-0x8`** |

### Other Changes

```diff

-147.100.0.0.0
+148.1.3.0.0

-  Functions: 878
-  Symbols:   1799
-  CStrings:  529
+  Functions: 876
+  Symbols:   1797
+  CStrings:  525
Symbols:
+ -[KSKeyboardListController updateEditButtonEnabledState]
+ GCC_except_table60
+ GCC_except_table68
+ GCC_except_table73
- GCC_except_table59
- GCC_except_table69
- GCC_except_table72
- ___46-[KSKeyboardController feedbackFeatureEnabled]_block_invoke
- _feedbackFeatureEnabled.is_internal_install
- _feedbackFeatureEnabled.once_token
CStrings:
+ "%s Feedback %@: RC_SEED_BUILD: 1 enabled: %d"
- "%s Feedback %@: RC_SEED_BUILD: 0 enabled: %d"
- "-[KSKeyboardListController setEditing:animated:]"
- "_numberOfEnabledKeyboards > 1"
- "apple-internal-install"
- "feedbackFeatureEnabled"
```
