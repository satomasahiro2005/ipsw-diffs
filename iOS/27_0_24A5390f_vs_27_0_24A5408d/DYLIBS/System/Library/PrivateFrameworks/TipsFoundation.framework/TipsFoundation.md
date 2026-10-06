## TipsFoundation

> `/System/Library/PrivateFrameworks/TipsFoundation.framework/TipsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50c` | `0x798` | **`+0x28c`** |
| `__DATA_CONST.__const` | `0x50` | `0x78` | **`+0x28`** |
| `__TEXT.__cstring` | `0x3e` | `0x64` | **`+0x26`** |
| `__TEXT.__objc_methlist` | `0x148` | `0x164` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0x80` | `0x90` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x1a0` | `0x1a8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xe8` | `0xf0` | **`+0x8`** |

### Other Changes

```diff

-857.0.0.0.0
+866.0.0.0.0

-  Functions: 7
-  Symbols:   54
-  CStrings:  3
+  Functions: 10
+  Symbols:   58
+  CStrings:  4
Symbols:
+ +[TPSRegulatoryImageFetcher fetchELabelURLsForCurrentDevice:]
+ ___61+[TPSRegulatoryImageFetcher fetchELabelURLsForCurrentDevice:]_block_invoke
+ ___61+[TPSRegulatoryImageFetcher fetchELabelURLsForCurrentDevice:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40bs_e37_v32?0"NSURL"8"NSURL"16"NSError"24ls32l8s40l8
CStrings:
+ "v32@?0@\"NSURL\"8@\"NSURL\"16@\"NSError\"24"
```
