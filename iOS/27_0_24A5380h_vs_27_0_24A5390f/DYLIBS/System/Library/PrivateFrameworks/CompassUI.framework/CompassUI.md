## CompassUI

> `/System/Library/PrivateFrameworks/CompassUI.framework/CompassUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x52f0` | `0x53f0` | **`+0x100`** |
| `__AUTH_CONST.__cfstring` | `0x500` | `0x580` | **`+0x80`** |
| `__TEXT.__ustring` | `0x4` | `0x2e` | **`+0x2a`** |
| `__TEXT.__cstring` | `0x3bb` | `0x3a0` | **`-0x1b`** |

### Other Changes

```diff

-367.30.6.12.6
+367.30.6.12.7

-  CStrings:  49
+  CStrings:  48
Symbols:
+ _objc_release_x28
- _WebLocalizedString
Functions:
~ _CreateCoordinateComponentString : 436 -> 464
~ _StringWithLocationDirection : 464 -> 704
~ sub_25794ac14 -> sub_258f79d20 : 1592 -> 1580
CStrings:
- ""
```
