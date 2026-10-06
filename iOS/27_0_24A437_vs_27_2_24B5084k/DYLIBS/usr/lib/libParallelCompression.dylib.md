## libParallelCompression.dylib

> `/usr/lib/libParallelCompression.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55f68` | `0x563f8` | **`+0x490`** |
| `__TEXT.__cstring` | `0xf581` | `0xf651` | **`+0xd0`** |
| `__TEXT.__const` | `0x830` | `0x820` | **`-0x10`** |

### Other Changes

```diff

-469.0.0.0.0
+469.40.4.0.0

-  Functions: 759
-  Symbols:   990
-  CStrings:  2262
+  Functions: 761
+  Symbols:   992
+  CStrings:  2274
Symbols:
+ _patch_verify_header
+ _rawimg_init_algorithm
CStrings:
+ "bad chunk position"
+ "bad fork compressed"
+ "bad fork flags"
+ "bad image size"
+ "bad page index"
+ "bad stream position"
+ "bad variant size"
+ "chunks too large"
+ "no variants"
+ "patch_verify_header"
+ "rawimg_check_memory"
+ "variant too large"
```
