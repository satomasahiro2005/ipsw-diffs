## CoreFoundation

> `/System/Library/Frameworks/CoreFoundation.framework/CoreFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d4bc4` | `0x1d4be8` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x140d80` | `0x140da0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x14b3eb` | `0x14b3fe` | **`+0x13`** |

### Other Changes

```diff

-5027.1.7.0.0
+5027.1.8.0.0

-  CStrings:  44301
+  CStrings:  44303
Functions:
~ ____CFGetProductName_block_invoke.cold.3 : 204 -> 240
CStrings:
+ "HomeAccessory"
+ "home"
```
