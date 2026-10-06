## TranslationUI

> `/System/Library/PrivateFrameworks/TranslationUI.framework/TranslationUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a464` | `0x10a508` | **`+0xa4`** |
| `__AUTH_CONST.__auth_got` | `0x1fc8` | `0x1fd8` | **`+0x10`** |

### Other Changes

```diff

-388.0.0.0.0
+389.1.0.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Symbols:   2287
+  Symbols:   2289
Symbols:
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_deviceSupportsInstructionFollowingPruningModels
Functions:
~ sub_2b0c37008 -> sub_2b0b9a048 : 88 -> 196
~ sub_2b0c83c60 -> sub_2b0be6d0c : 200 -> 256
```
