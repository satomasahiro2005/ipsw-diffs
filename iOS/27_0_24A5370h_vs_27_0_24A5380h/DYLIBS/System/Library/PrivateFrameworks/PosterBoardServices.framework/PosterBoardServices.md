## PosterBoardServices

> `/System/Library/PrivateFrameworks/PosterBoardServices.framework/PosterBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x10c0` | `0xe40` | **`-0x280`** |
| `__DATA_DIRTY.__objc_data` | `0xc80` | `0xf00` | **`+0x280`** |
| `__TEXT.__text` | `0x7de1c` | `0x7df94` | **`+0x178`** |
| `__TEXT.__oslogstring` | `0x37ee` | `0x392e` | **`+0x140`** |
| `__DATA.__bss` | `0xcc0` | `0xc50` | **`-0x70`** |
| `__DATA_DIRTY.__bss` | `0x70` | `0xd8` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x1c50` | `0x1c70` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xfec` | `0xfe0` | **`-0xc`** |
| `__AUTH.__data` | `0x128` | `0x120` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1b90` | `0x1b98` | **`+0x8`** |

### Other Changes

```diff

-344.0.101.0.0
+347.102.0.0.0

-  Functions: 2693
-  Symbols:   3871
-  CStrings:  1092
+  Functions: 2694
+  Symbols:   3873
+  CStrings:  1094
Symbols:
+ GCC_except_table27
+ ___52+[PRSCodableImage dataRepresentationForImage:error:]_block_invoke
+ ___block_descriptor_40_e9_16?0^8l
- GCC_except_table25
CStrings:
+ "PRSServer init: created dataModel BSServiceConnectionListener (domain=com.apple.posterboardservices service=%{public}@)"
+ "PRSServer invalidate: tearing down dataModel BSServiceConnectionListener (%{public}@). Incoming connections will fail with 'no listener to handle it' until the server is re-activated. (rdar://178576719)"
```
