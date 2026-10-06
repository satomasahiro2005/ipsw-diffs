## libAppleArchive.dylib

> `/usr/lib/libAppleArchive.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83790` | `0x83d84` | **`+0x5f4`** |
| `__TEXT.__cstring` | `0x13496` | `0x13577` | **`+0xe1`** |
| `__TEXT.__unwind_info` | `0xd78` | `0xd80` | **`+0x8`** |

### Other Changes

```diff

-469.0.0.0.0
+469.40.4.0.0

-  Functions: 1072
-  Symbols:   1311
-  CStrings:  2911
+  Functions: 1075
+  Symbols:   1314
+  CStrings:  2924
Symbols:
+ _concatSourcePath
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
+ "concatSourcePath"
+ "no variants"
+ "patch_verify_header"
+ "rawimg_check_memory"
+ "variant too large"
```
