## LocalAuthentication

> `/System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methlist` | `0x3710` | `0x3728` | **`+0x18`** |
| `__TEXT.__text` | `0x34318` | `0x3432c` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c10` | `0x1c20` | **`+0x10`** |
| `__TEXT.__const` | `0x324` | `0x314` | **`-0x10`** |

### Other Changes

```diff

-2319.40.35.0.1
+2319.40.43.0.0

-  Functions: 1501
-  Symbols:   2868
+  Functions: 1503
+  Symbols:   2870
Symbols:
+ -[LAContext optionDisableAutomaticPasscodeFallback]
+ -[LAContext setOptionDisableAutomaticPasscodeFallback:]
Functions:
+ -[LAContext optionDisableAutomaticPasscodeFallback]
+ -[LAContext localizedReason]
```
