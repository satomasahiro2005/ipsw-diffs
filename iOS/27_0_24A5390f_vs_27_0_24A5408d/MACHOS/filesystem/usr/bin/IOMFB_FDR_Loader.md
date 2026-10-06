## IOMFB_FDR_Loader

> `/usr/bin/IOMFB_FDR_Loader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x8ec9` | `0x8f1e` | **`+0x55`** |
| `__TEXT.__text` | `0x34878` | `0x34890` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x3d4` | `0x3e0` | **`+0xc`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-700.50.85.0.0
+700.50.96.5.0

-  CStrings:  1064
+  CStrings:  1066
Functions:
~ sub_10000efac : 2276 -> 2308
~ sub_100024e78 -> sub_100024e98 : 276 -> 268
CStrings:
+ "Parser e: cannot allocate IOMFBACSSConfig"
+ "Parser e: cannot allocate IOMFBACSSConfig\n"
```
