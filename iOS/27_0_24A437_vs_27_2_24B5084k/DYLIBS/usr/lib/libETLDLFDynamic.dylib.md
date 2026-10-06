## libETLDLFDynamic.dylib

> `/usr/lib/libETLDLFDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x200` | `0x25c` | **`+0x5c`** |
| `__TEXT.__cstring` | `—` | `0x52` | **`+0x52`** |

### Other Changes

```diff

-1585.0.0.0.0
+1594.0.0.0.0

-  Symbols:   7
-  CStrings:  0
+  Symbols:   8
+  CStrings:  3
Symbols:
+ __ETLDebugPrint
Functions:
~ _ETLDLFParse : 124 -> 216
CStrings:
+ "ETLDLFParse"
+ "Length %u not enough, need %zu\n"
+ "Length %u not whole payload, need %u\n"
```
