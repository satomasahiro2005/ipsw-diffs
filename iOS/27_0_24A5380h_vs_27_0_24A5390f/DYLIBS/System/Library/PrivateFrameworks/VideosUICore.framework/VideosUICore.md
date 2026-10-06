## VideosUICore

> `/System/Library/PrivateFrameworks/VideosUICore.framework/VideosUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35308` | `0x353f0` | **`+0xe8`** |
| `__TEXT.__objc_methlist` | `0x560c` | `0x5664` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x8658` | `0x8688` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1ed0` | `0x1ef8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x3c70` | `0x3c98` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x55c` | `0x560` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1145.0.2.0.1
+1145.0.6.0.0

-  Functions: 1873
-  Symbols:   3678
+  Functions: 1880
+  Symbols:   3686
Symbols:
+ +[VUIImageFactory _imageProxyWithURL:impressionIDWrapper:]
+ +[VUIImageFactory makeImageProxyWithDescriptor:impressionIDWrapper:]
+ +[VUIImageFactory makeImageViewWithDescriptor:existingView:impressionIDWrapper:]
+ +[VUIImageFactory makeImageViewWithDescriptor:imageProxy:existingView:impressionIDWrapper:]
+ -[VUIImageProxy initWithObject:imageLoader:groupType:impressionIDWrapper:]
+ -[VUILayeredImageProxy impressionIDWrapper]
+ -[VUILayeredImageProxy setImpressionIDWrapper:]
+ GCC_except_table14
+ _OBJC_IVAR_$_VUILayeredImageProxy._impressionIDWrapper
+ ___block_descriptor_89_e8_32s40s48s56w_e5_v8?0lw56l8s32l8s40l8s48l8
- GCC_except_table24
- GCC_except_table28
```
