## ClarityFoundation

> `/System/Library/PrivateFrameworks/ClarityFoundation.framework/ClarityFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c80` | `0x7dbc` | **`+0x13c`** |
| `__TEXT.__oslogstring` | `0x4d9` | `0x511` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x280` | `0x290` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x708` | `0x718` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xb04` | `0xb14` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x388` | `0x398` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x140` | `0x144` | **`+0x4`** |

### Other Changes

```diff

-3245.8.4.2.0
+3245.8.9.0.0

-  Functions: 231
-  Symbols:   568
-  CStrings:  128
+  Functions: 233
+  Symbols:   573
+  CStrings:  129
Symbols:
+ -[CLFAppAvailabilityChecker prepareForAppReplacementSourceLookup]
+ GCC_except_table158
+ GCC_except_table165
+ GCC_except_table169
+ _getIXAppInstallCoordinatorClass
+ _objc_opt_respondsToSelector
+ _objc_retain_x9
- GCC_except_table157
- GCC_except_table167
CStrings:
+ "Failed to prepare for app replacement source lookup: %@"
```
