## Security

> `/System/Library/Frameworks/Security.framework/Security`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x1b9c8` | `0x1b9e8` | **`+0x20`** |
| `__TEXT.__text` | `0x182790` | `0x1827ac` | **`+0x1c`** |

### Other Changes

```diff

-62460.40.74.0.0
+62460.40.78.0.0

-  Symbols:   13685
+  Symbols:   13686
Symbols:
+ _SecKeyCopySystemKey.gsmakObjectIDBytes
Functions:
~ sub_18954fba8 -> sub_189550ba8 : 60 -> 64
~ _SecKeyCopySystemKey : 684 -> 708
```
