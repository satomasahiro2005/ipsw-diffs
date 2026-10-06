## libipsec.A.dylib

> `/usr/lib/libipsec.A.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28f0` | `0x2924` | **`+0x34`** |
| `__TEXT.__cstring` | `0x5c3` | `0x5e1` | **`+0x1e`** |

### Other Changes

```diff

-  Functions: 57
+  Functions: 58

-  CStrings:  74
+  CStrings:  75
Functions:
~ ___libipseclex : 2620 -> 2648
~ ___libipsec_create_buffer : 132 -> 128
~ ___libipsec_scan_buffer : 152 -> 144
~ ___libipsec_scan_bytes : 128 -> 140
CStrings:
+ "bad length in yy_scan_bytes()"
```
