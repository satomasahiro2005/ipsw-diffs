## NTKUltraBezel

> `/System/Library/PrivateFrameworks/NTKUltraBezel.framework/NTKUltraBezel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x151d0` | `0x1606c` | **`+0xe9c`** |
| `__TEXT.__cstring` | `0xc38` | `0xba8` | **`-0x90`** |
| `__TEXT.__gcc_except_tab` | `0x278` | `0x2c8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x115c` | `0x11a4` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x4e0` | `0x520` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xe18` | `0xe48` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x272` | `0x248` | **`-0x2a`** |

### Other Changes

```diff

-2483.556.1.0.0
+2483.560.1.0.0

-  Functions: 483
-  Symbols:   935
-  CStrings:  131
+  Functions: 490
+  Symbols:   945
+  CStrings:  127
Symbols:
+ -[NTKFoghornFaceBezelView(UIColor) _setColorsInPalette:forBezelStyle:]
+ -[NTKFoghornFaceBezelView(UIColor) _setColorsInPalette:forPrimaryColor:strictlyMonochrome:]
+ -[NTKFoghornFaceBezelView(UIColor) _setColorsInPalette:fromPalette:toPalette:fraction:]
+ -[NTKFoghornFaceBezelView(UIColor) _setColorsInPalette:useMulticolor:bezelStyle:primaryColor:strictlyMonochrome:]
+ -[NTKFoghornFaceBezelView(UIColor) _setColorsWithPalette:]
+ -[NTKFoghornFaceBezelView(UIColor) _setHarmoniaMulticolorsInPalette:]
+ -[NTKFoghornFaceBezelView(UIColor) _setReadinessMulticolorsInPalette:]
+ -[NTKFoghornFaceBezelView(UIColor) setColorsFromUseMulticolor:fromBezelStyle:fromPrimaryColor:fromStrictlyMonochrome:toUseMulticolor:toBezelStyle:toPrimaryColor:toStrictlyMonochrome:fraction:]
+ -[NTKFoghornFaceBezelView(UIColor) setColorsUseMulticolor:bezelStyle:primaryColor:strictlyMonochrome:]
+ GCC_except_table10
+ GCC_except_table14
+ GCC_except_table15
+ ___destructor_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88_s96_s104_s112_s120_s128_s136_s144_s152_s160_s168_s176_s184_s192_s200_s208_s216_s224_s232_s248_s256_s264_s272_s280_s288_s296_s304_s312_s320_s328_s336_s344_s352_s360
- -[NTKFoghornFaceBezelView(UIColor) _setColorsFromPrimaryColor:strictlyMonochrome:]
- -[NTKFoghornFaceBezelView(UIColor) _setHarmoniaMultiColors]
- -[NTKFoghornFaceBezelView(UIColor) _setReadinessMultiColors]
CStrings:
- "%s: bezelStyle = %u"
- "%s: primaryColor = %@"
- "+[NTKFoghornFaceBezelView(UIColor) _primaryColorForBezelStyle:]"
- "-[NTKFoghornFaceBezelView(UIColor) _setColorsFromPrimaryColor:strictlyMonochrome:]"
```
