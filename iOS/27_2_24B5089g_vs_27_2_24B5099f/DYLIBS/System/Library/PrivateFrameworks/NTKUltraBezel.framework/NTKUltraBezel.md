## NTKUltraBezel

> `/System/Library/PrivateFrameworks/NTKUltraBezel.framework/NTKUltraBezel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14434` | `0x151d0` | **`+0xd9c`** |
| `__TEXT.__gcc_except_tab` | `0x1a8` | `0x278` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0xdb0` | `0xe18` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x1dc0` | `0x1e10` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x110c` | `0x115c` | **`+0x50`** |
| `__TEXT.__const` | `0x672` | `0x6a2` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x4b0` | `0x4e0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x260` | `0x280` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x48` | `0x60` | **`+0x18`** |
| `__DATA.__bss` | `0x450` | `0x460` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x208` | `0x218` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x678` | `0x680` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1c4` | `0x1cc` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-2483.544.0.0.0
+2483.556.1.0.0

-  Functions: 471
-  Symbols:   915
+  Functions: 483
+  Symbols:   935
Symbols:
+ +[CLKFont(NTKFoghornFaceAdditions) _foghornCaseSensitiveFontDescriptor]
+ +[CLKFont(NTKFoghornFaceAdditions) foghornReadinessBezelLabelFontOfSize:]
+ -[NTKFoghornFaceBezelView _readinessBaseLabelAllocatedWidth]
+ -[NTKFoghornFaceBezelView _readinessDeemphasizedBaseColor]
+ -[NTKFoghornFaceBezelView _updateBaseLabelAllocatedWidthForStyle:]
+ -[NTKFoghornFaceBezelView readinessDataState]
+ -[NTKFoghornFaceBezelView readinessLevel]
+ -[NTKFoghornFaceBezelView setReadinessDataState:]
+ -[NTKFoghornFaceBezelView setReadinessLevel:]
+ GCC_except_table26
+ _CGRectGetWidth
+ _NTKFoghornReadinessSnapshotLevel
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._baseLabelMaxWidthConstraint
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessDataState
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessLevel
+ _UIFontFeatureSelectorIdentifierKey
+ _UIFontFeatureTypeIdentifierKey
+ ___71+[CLKFont(NTKFoghornFaceAdditions) _foghornCaseSensitiveFontDescriptor]_block_invoke
+ ___block_descriptor_40_e5_v8?0l
+ ___copy_constructor_8_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88
+ ___move_assignment_8_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88
+ __foghornCaseSensitiveFontDescriptor.fontDescriptor
+ __foghornCaseSensitiveFontDescriptor.onceToken
+ __readinessColorByScalingAlpha
+ __readinessDeemphasizedColors
- -[NTKFoghornFaceBezelView readinessScore]
- -[NTKFoghornFaceBezelView setReadinessScore:]
- GCC_except_table25
- _NTKFoghornReadinessSnapshotScore
- _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessScore
CStrings:
+ "Readiness bezel updating with dataState: %ld, level: %@"
- "Readiness bezel updating with dataState: %ld, score: %@"
```
