## FSKit

> `/System/Library/PrivateFrameworks/FSKit.framework/FSKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53688` | `0x536b4` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x18c8` | `0x18f0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x6278` | `0x6288` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x3f66` | `0x3f76` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c00` | `0x2c08` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1820` | `0x1828` | **`+0x8`** |

### Other Changes

```diff

-974.0.7.0.0
+974.0.11.0.0

-  Functions: 2694
-  Symbols:   4240
+  Functions: 2695
+  Symbols:   4242
Symbols:
+ -[FSFreeSpace(Project) isNoUpdate]
+ ___block_descriptor_112_e8_32s40s48s56s64s72s80s88s96s104bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s104l8s80l8s88l8s96l8
+ ___block_descriptor_120_e8_32s40s48s56s64s72s80s88s96s104s112bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s112l8s88l8s96l8s104l8
+ ___block_descriptor_48_e8_32bs40bs_e17_v16?0"NSError"8ls32l8s40l8
- ___block_descriptor_112_e8_32s40s48s56s64s72s80s88s96s104bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s104l8s88l8s96l8
- ___block_descriptor_120_e8_32s40s48s56s64s72s80s88s96s104s112bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s112l8s96l8s104l8
CStrings:
+ "%s: freeSpaceData called on the \"no update\" sentinel"
- "%s: free space was not populated!"
```
