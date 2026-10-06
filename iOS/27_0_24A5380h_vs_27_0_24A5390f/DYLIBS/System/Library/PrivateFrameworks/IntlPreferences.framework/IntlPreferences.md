## IntlPreferences

> `/System/Library/PrivateFrameworks/IntlPreferences.framework/IntlPreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x690` | `0xa0` | **`-0x5f0`** |
| `__DATA_DIRTY.__objc_data` | `0xa0` | `0x690` | **`+0x5f0`** |
| `__TEXT.__text` | `0x1b92c` | `0x1b9c4` | **`+0x98`** |
| `__AUTH_CONST.__auth_got` | `0x600` | `0x610` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x11ac` | `0x11bc` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1090` | `0x1098` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5e0` | `0x5e8` | **`+0x8`** |

### Other Changes

```diff

-494.3.0.0.0
+494.6.0.0.0

-  Functions: 464
-  Symbols:   979
+  Functions: 465
+  Symbols:   982
Symbols:
+ +[IntlUtility persistRejectedLanguage:]
+ GCC_except_table95
+ GCC_except_table99
+ _CFArrayGetTypeID
+ _CFGetTypeID
- GCC_except_table94
- GCC_except_table98
Functions:
+ +[IntlUtility persistRejectedLanguage:]
~ +[IntlUtility rejectDiscoveredLanguage:clearFollowUp:] : 276 -> 124
```
