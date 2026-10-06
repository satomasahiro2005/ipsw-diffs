## KeyboardSettings

> `/System/Library/PrivateFrameworks/KeyboardSettings.framework/KeyboardSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29c74` | `0x29d14` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x3180` | `0x31c0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3648` | `0x3678` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x310` | `0x330` | **`+0x20`** |
| `__DATA.__bss` | `0xe8` | `0xf8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2390` | `0x2398` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x950` | `0x958` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 876
-  Symbols:   1796
-  CStrings:  527
+  Functions: 878
+  Symbols:   1799
+  CStrings:  529
Symbols:
+ GCC_except_table69
+ ___46-[KSKeyboardController feedbackFeatureEnabled]_block_invoke
+ _feedbackFeatureEnabled.is_internal_install
+ _feedbackFeatureEnabled.once_token
- GCC_except_table68
Functions:
~ -[KSKeyboardController feedbackFeatureEnabled] : 76 -> 172
+ ___46-[KSKeyboardController feedbackFeatureEnabled]_block_invoke
~ -[KSKeyboardController feedbackFeatureEnabled].cold.1 : 140 -> 20
+ -[KSKeyboardController feedbackFeatureEnabled].cold.2
CStrings:
+ "%s Feedback %@: RC_SEED_BUILD: 0 enabled: %d"
+ "apple-internal-install"
+ "feedbackFeatureEnabled"
- "%s Feedback %@: RC_SEED_BUILD: 1 enabled: %d"
```
