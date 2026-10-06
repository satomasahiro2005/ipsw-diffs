## IconServices

> `/System/Library/PrivateFrameworks/IconServices.framework/IconServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x674f0` | `0x67dc0` | **`+0x8d0`** |
| `__DATA_DIRTY.__objc_data` | `0x2b70` | `0x33e0` | **`+0x870`** |
| `__AUTH.__objc_data` | `0x870` | `0x50` | **`-0x820`** |
| `__TEXT.__const` | `0x8840` | `0x8970` | **`+0x130`** |
| `__AUTH_CONST.__objc_const` | `0x13fe8` | `0x14110` | **`+0x128`** |
| `__TEXT.__objc_methlist` | `0x6994` | `0x6a44` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x31c8` | `0x3230` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x1a10` | `0x1a40` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x4a20` | `0x4a40` | **`+0x20`** |
| `__DATA.__bss` | `0x660` | `0x640` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x220` | `0x240` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x7f0` | `0x808` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x540` | `0x558` | **`+0x18`** |
| `__TEXT.__cstring` | `0x463a` | `0x464d` | **`+0x13`** |
| `__DATA.__objc_ivar` | `0x6d4` | `0x6e0` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x6b0` | `0x6b8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x530` | `0x538` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x408` | `0x410` | **`+0x8`** |

### Other Changes

```diff

-793.1.7.0.0
+793.1.10.0.0

-  Functions: 2621
-  Symbols:   4983
-  CStrings:  1095
+  Functions: 2637
+  Symbols:   5013
+  CStrings:  1096
Symbols:
+ +[OKLChColor cuspLightnessAtHue:]
+ +[OKLChColor maxChromaAtLightness:hue:]
+ -[OKLChColor chroma]
+ -[OKLChColor convertToSRGBRed:green:blue:]
+ -[OKLChColor hue]
+ -[OKLChColor ifColor]
+ -[OKLChColor initFromIFColor:]
+ -[OKLChColor initWithLightness:chroma:hue:]
+ -[OKLChColor initWithSRGBRed:green:blue:]
+ -[OKLChColor lightness]
+ -[OKLChColor setChroma:]
+ -[OKLChColor setHue:]
+ -[OKLChColor setLightness:]
+ -[OKLChColor(FolderAdjustment) adjustForFolder]
+ _OBJC_CLASS_$_OKLChColor
+ _OBJC_IVAR_$_OKLChColor._chroma
+ _OBJC_IVAR_$_OKLChColor._hue
+ _OBJC_IVAR_$_OKLChColor._lightness
+ _OBJC_METACLASS_$_OKLChColor
+ __OBJC_$_CLASS_METHODS_OKLChColor
+ __OBJC_$_INSTANCE_METHODS_OKLChColor(FolderAdjustment)
+ __OBJC_$_INSTANCE_VARIABLES_OKLChColor
+ __OBJC_$_PROP_LIST_OKLChColor
+ __OBJC_CLASS_RO_$_OKLChColor
+ __OBJC_METACLASS_RO_$_OKLChColor
+ _atan2
+ _cbrt
+ _hypot
+ _maxChroma
+ _okLabToLinearSRGB
CStrings:
+ "20:38:04"
+ "badge_pointerarrow"
- "05:24:34"
```
