## libcopyfile.dylib

> `/usr/lib/system/libcopyfile.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ab0` | `0x7b00` | **`+0x50`** |
| `__TEXT.__cstring` | `0x1bf1` | `0x1c1e` | **`+0x2d`** |

### Other Changes

```diff

-260.40.3.0.0
+260.40.4.0.0

-  CStrings:  202
+  CStrings:  203
Functions:
~ _copyfile_pack : 4452 -> 4532
CStrings:
+ "skipping attr \"%s\" due to fetch error %d: %m"
```
