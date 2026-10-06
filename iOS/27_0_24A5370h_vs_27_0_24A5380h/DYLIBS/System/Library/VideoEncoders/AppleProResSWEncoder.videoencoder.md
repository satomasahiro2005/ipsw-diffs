## AppleProResSWEncoder.videoencoder

> `/System/Library/VideoEncoders/AppleProResSWEncoder.videoencoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21224` | `0x2150c` | **`+0x2e8`** |
| `__TEXT.__cstring` | `0x40e` | `0x58a` | **`+0x17c`** |
| `__DATA.__bss` | `0x80` | `0x140` | **`+0xc0`** |
| `__AUTH_CONST.__cfstring` | `0x440` | `0x4c0` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x300` | `0x380` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x88` | `0x108` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x2a8` | `0x300` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x258` | `0x290` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x158` | `0x174` | **`+0x1c`** |

### Other Changes

```diff

-50204.0.0.0.0
+60623.0.0.0.0

-  Functions: 160
-  Symbols:   373
-  CStrings:  46
+  Functions: 171
+  Symbols:   392
+  CStrings:  57
Symbols:
+ GCC_except_table3
+ _CFArrayGetCount
+ _CFArrayGetTypeID
+ _CFArrayGetValues
+ _CFPreferencesCopyAppValue
+ _CFStringGetCString
+ _CFStringGetLength
+ _CFStringGetTypeID
+ __ZL21getQuantizationMatrixPKvPKcPh
+ __ZN10Macroblock31getCustomQuantizationMatrixLumaEi
+ __ZN10Macroblock33getCustomQuantizationMatrixChromaEi
+ __ZN23DiscreteCosineTransform8quantizeIstfEEvPKT_PT0_PKT1_
+ ____ZL24getUserDefinedQuantIndexv_block_invoke
+ ____ZL46getUserDefinedMaxCompressionSizeExcludingAlphav_block_invoke
+ ____ZN10Macroblock31getCustomQuantizationMatrixLumaEi_block_invoke
+ ____ZN10Macroblock33getCustomQuantizationMatrixChromaEi_block_invoke
+ _malloc_type_posix_memalign
+ _printf
+ _putchar
+ _strtol
- __ZN23DiscreteCosineTransform8quantizeIstEEvPKT_PT0_S3_
CStrings:
+ "%4d"
+ "ProRes user-defined %s matrix:\n"
+ "ProRes user-defined max compression size excluding alpha: %d\n"
+ "ProRes user-defined quantization index: %d\n"
+ "ProResUserDefinedChromaMatrix"
+ "ProResUserDefinedLumaMatrix"
+ "ProResUserDefinedMaxCompressionSizeExcludingAlpha"
+ "ProResUserDefinedMaxCompressionSizeExcludingAlpha is too small, using %d instead!\n"
+ "ProResUserDefinedQuantizationIndex"
+ "chroma"
+ "luma"
```
