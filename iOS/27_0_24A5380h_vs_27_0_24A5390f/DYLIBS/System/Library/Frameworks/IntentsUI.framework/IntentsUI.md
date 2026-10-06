## IntentsUI

> `/System/Library/Frameworks/IntentsUI.framework/IntentsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf54c` | `0xf934` | **`+0x3e8`** |
| `__DATA_CONST.__got` | `0x380` | `0x3b0` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x100` | `0x120` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1248` | `0x1268` | **`+0x20`** |
| `__DATA.__bss` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x16a4` | `0x16ac` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4e0` | `0x4e8` | **`+0x8`** |

### Other Changes

```diff

-4016.0.43.5.0
+4016.0.45.3.0

-  Functions: 405
-  Symbols:   1094
+  Functions: 409
+  Symbols:   1106
Symbols:
+ +[INUIPortableImageLoaderHelper _intents_downsampledBundleImage:traitCollection:]
+ GCC_except_table237
+ GCC_except_table248
+ GCC_except_table268
+ GCC_except_table281
+ GCC_except_table378
+ _UTTypeGIF
+ _UTTypeHEIC
+ _UTTypeHEIF
+ _UTTypeJPEG
+ _UTTypeTIFF
+ __INUIDownsampledBundleImage
+ __INUIImageSourceCreationOptions.onceToken
+ __INUIImageSourceCreationOptions.options
+ ____INUIDownsampledBundleImage_block_invoke
+ ____INUIImageSourceCreationOptions_block_invoke
+ _kCGImageSourceAllowableTypes
- GCC_except_table233
- GCC_except_table244
- GCC_except_table264
- GCC_except_table277
- GCC_except_table374
```
