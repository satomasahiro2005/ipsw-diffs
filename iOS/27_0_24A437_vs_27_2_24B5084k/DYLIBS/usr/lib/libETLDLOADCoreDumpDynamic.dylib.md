## libETLDLOADCoreDumpDynamic.dylib

> `/usr/lib/libETLDLOADCoreDumpDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x998` | `0x9e4` | **`+0x4c`** |
| `__TEXT.__cstring` | `0x179` | `0x1a5` | **`+0x2c`** |

### Other Changes

```diff

-1585.0.0.0.0
+1594.0.0.0.0

-  CStrings:  10
+  CStrings:  11
Functions:
~ _ETLDLOADCoreDumpCaptureRecord : 904 -> 936
~ _ETLDLOADCoreDumpCaptureRecordFast : 1552 -> 1596
CStrings:
+ "Capture 0x%x, length 0x%x, chunk size 0x%x\n"
```
