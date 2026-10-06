## IMTranscoderAgent

> `/System/Library/PrivateFrameworks/IMTranscoderAgent.framework/IMTranscoderAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `—` | `0x230` | **`+0x230`** |
| `__DATA_DIRTY.__objc_data` | `0x500` | `0x2d0` | **`-0x230`** |
| `__TEXT.__text` | `0x1e724` | `0x1e838` | **`+0x114`** |
| `__AUTH_CONST.__cfstring` | `0xb80` | `0xc00` | **`+0x80`** |
| `__TEXT.__cstring` | `0xe07` | `0xe33` | **`+0x2c`** |
| `__TEXT.__gcc_except_tab` | `0x1fcc` | `0x1ff8` | **`+0x2c`** |
| `__TEXT.__oslogstring` | `0x50dc` | `0x5108` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x688` | `0x6a0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5e8` | `0x5f0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xcb8` | `0xcc0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xaec` | `0xaf4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5b8` | `0x5c0` | **`+0x8`** |

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 277
-  Symbols:   415
-  CStrings:  572
+  Functions: 279
+  Symbols:   416
+  CStrings:  577
Symbols:
+ __IMStringFromTranscodeRepresentations
CStrings:
+ "  transcodeRepresentations: %@"
+ "17:07:30"
+ "Attempting copy+add props for size %lu (reason: the source is wide gamut and fits the largest limit %lu)"
+ "Couldn't use copy of wide-gamut image with added properties (size %ld max %ld), falling back to original"
+ "Jul  2 2026"
+ "Multiple"
+ "Single"
+ "SingleWithThumbnail"
+ "Unknown"
- "22:31:26"
- "Attempting copy+add props for size %lu (reason: the source is wide gamut and smaller than the limit %lu)"
- "Couldn't use copy of wide-gamut image with added properties (size %ld max %ld), transcoding"
- "Jun 18 2026"
```
