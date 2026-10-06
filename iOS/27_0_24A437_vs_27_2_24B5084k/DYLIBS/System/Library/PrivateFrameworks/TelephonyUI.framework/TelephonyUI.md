## TelephonyUI

> `/System/Library/PrivateFrameworks/TelephonyUI.framework/TelephonyUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x2900` | `0x2920` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2d61` | `0x2d81` | **`+0x20`** |
| `__TEXT.__text` | `0x69284` | `0x69294` | **`+0x10`** |

### Other Changes

```diff

-153.100.1.2.29
+156.200.70.2.2

-  CStrings:  537
+  CStrings:  538
Functions:
~ +[UIImage(TelephonyUI) systemImageNameForSymbolType:] : 1236 -> 1248
~ sub_1b9f8c52c -> sub_1bb1fc538 : 392 -> 396
CStrings:
+ "homepod.and.appletv"
```
