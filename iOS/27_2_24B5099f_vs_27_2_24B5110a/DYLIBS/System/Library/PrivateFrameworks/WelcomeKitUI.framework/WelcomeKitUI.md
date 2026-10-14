## WelcomeKitUI

> `/System/Library/PrivateFrameworks/WelcomeKitUI.framework/WelcomeKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14b64` | `0x14d28` | **`+0x1c4`** |
| `__TEXT.__cstring` | `0x4fd0` | `0x5000` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x5b0` | `0x5d8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x1b7c` | `0x1ba4` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x4d60` | `0x4d80` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x38c0` | `0x38e0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x14d0` | `0x14e8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x630` | `0x640` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x24c` | `0x250` | **`+0x4`** |

### Other Changes

```diff

-1441.40.1.0.0
+1441.42.1.0.0

-  Functions: 510
-  Symbols:   1229
-  CStrings:  653
+  Functions: 513
+  Symbols:   1234
+  CStrings:  654
Symbols:
+ -[WLWelcomeController _abandonAttemptIfPaneLeftNavigationStack:]
+ -[WLWelcomeController _abandonAttempt]
+ -[WLWelcomeController _navigationStackContainsViewController:]
+ GCC_except_table88
+ GCC_except_table94
+ GCC_except_table99
+ _OBJC_IVAR_$_WLWelcomeController._isAttemptAbandoned
+ ___block_descriptor_48_e8_32w40w_e5_v8?0lw32l8w40l8
- GCC_except_table82
- GCC_except_table91
- GCC_except_table96
CStrings:
+ "%@ abandons its attempt: %@ left the navigation stack."
```
