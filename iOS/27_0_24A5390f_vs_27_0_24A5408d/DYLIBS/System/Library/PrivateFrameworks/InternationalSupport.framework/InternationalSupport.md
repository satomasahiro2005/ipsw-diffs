## InternationalSupport

> `/System/Library/PrivateFrameworks/InternationalSupport.framework/InternationalSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa534` | `0xa588` | **`+0x54`** |
| `__AUTH_CONST.__const` | `0xe8` | `0x108` | **`+0x20`** |
| `__DATA.__bss` | `0x240` | `0x250` | **`+0x10`** |

### Other Changes

```diff

-123.0.0.0.0
+124.0.0.0.0

-  Functions: 224
-  Symbols:   508
+  Functions: 226
+  Symbols:   511
Symbols:
+ ___61+[NSLocale(InternationalSupportExtensions) isOnCalciumDevice]_block_invoke
+ _isOnCalciumDevice.isCalcium
+ _isOnCalciumDevice.onceToken
Functions:
~ +[NSLocale(InternationalSupportExtensions) isOnCalciumDevice] : 72 -> 56
+ ___61+[NSLocale(InternationalSupportExtensions) isOnCalciumDevice]_block_invoke
+ +[NSLocale(InternationalSupportExtensions) isOnCalciumDevice].cold.1
```
