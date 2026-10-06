## PosterKit

> `/System/Library/PrivateFrameworks/PosterKit.framework/PosterKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x185f98` | `0x1868a0` | **`+0x908`** |
| `__AUTH_CONST.__objc_const` | `0x55458` | `0x555e8` | **`+0x190`** |
| `__AUTH_CONST.__cfstring` | `0xab80` | `0xace0` | **`+0x160`** |
| `__TEXT.__cstring` | `0xafff` | `0xb0ef` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x1a124` | `0x1a1ec` | **`+0xc8`** |
| `__DATA_CONST.__objc_selrefs` | `0xc4d8` | `0xc550` | **`+0x78`** |
| `__DATA_CONST.__const` | `0x3850` | `0x38c0` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x4b30` | `0x4b80` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x3bc0` | `0x3be0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x62d0` | `0x62e8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1ab4` | `0x1ac8` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x1e90` | `0x1ea0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xb10` | `0xb18` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x8a0` | `0x8a8` | **`+0x8`** |

### Other Changes

```diff

-347.102.0.0.0
+350.1.100.0.0

-  Functions: 10549
-  Symbols:   15619
-  CStrings:  2132
+  Functions: 10566
+  Symbols:   15653
+  CStrings:  2144
Symbols:
+ +[PRPosterStandBySettings settingsControllerModule]
+ -[PREditorRootViewController _updateDesiredTimeStretchInEditorPersistingHeight:]
+ -[PREditorRootViewController titlePopoverArrowDirectionForCompactTimeEnabled:interfaceOrientation:]
+ -[PREditorRootViewController titlePopoverSourceItemForCompactTimeEnabled:]
+ -[PRPosterSettings .cxx_destruct]
+ -[PRPosterSettings setStandBySettings:]
+ -[PRPosterSettings standBySettings]
+ -[PRPosterStandBySettings setDefaultValues]
+ -[PRPosterStandBySettings setStackEditorShrinkAnimationBounce:]
+ -[PRPosterStandBySettings setStackEditorShrinkAnimationDuration:]
+ -[PRPosterStandBySettings setStackEditorShrinkFactorDefault:]
+ -[PRPosterStandBySettings setStackEditorShrinkFactorSystemSmall:]
+ -[PRPosterStandBySettings stackEditorShrinkAnimationBounce]
+ -[PRPosterStandBySettings stackEditorShrinkAnimationDuration]
+ -[PRPosterStandBySettings stackEditorShrinkFactorDefault]
+ -[PRPosterStandBySettings stackEditorShrinkFactorSystemSmall]
+ GCC_except_table174
+ GCC_except_table192
+ GCC_except_table204
+ _OBJC_CLASS_$_PRPosterStandBySettings
+ _OBJC_CLASS_$_PTSliderRow
+ _OBJC_IVAR_$_PRPosterSettings._standBySettings
+ _OBJC_IVAR_$_PRPosterStandBySettings._stackEditorShrinkAnimationBounce
+ _OBJC_IVAR_$_PRPosterStandBySettings._stackEditorShrinkAnimationDuration
+ _OBJC_IVAR_$_PRPosterStandBySettings._stackEditorShrinkFactorDefault
+ _OBJC_IVAR_$_PRPosterStandBySettings._stackEditorShrinkFactorSystemSmall
+ _OBJC_METACLASS_$_PRPosterStandBySettings
+ __OBJC_$_CLASS_METHODS_PRPosterStandBySettings
+ __OBJC_$_INSTANCE_METHODS_PRPosterStandBySettings
+ __OBJC_$_INSTANCE_VARIABLES_PRPosterStandBySettings
+ __OBJC_$_PROP_LIST_PRPosterStandBySettings
+ __OBJC_CLASS_RO_$_PRPosterStandBySettings
+ __OBJC_METACLASS_RO_$_PRPosterStandBySettings
+ ___42-[PREditor _handleTitleStyleEditorChange:]_block_invoke_2
+ ___51+[PRPosterStandBySettings settingsControllerModule]_block_invoke
+ ___block_descriptor_32_e21_"NSString"24?0816l
+ ___block_descriptor_56_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_73_e8_32s_e5_v8?0ls32l8
- -[PREditorRootViewController updateForChangedAdaptiveTimeMode]
- GCC_except_table173
- GCC_except_table191
- GCC_except_table203
CStrings:
+ "%.3f"
+ "@\"NSString\"24@?0@8@16"
+ "Bounce"
+ "Default"
+ "Stack Editor Shrink Animation"
+ "Stack Editor Shrink Factor"
+ "StandBy"
+ "SystemSmall"
+ "stackEditorShrinkAnimationBounce"
+ "stackEditorShrinkAnimationDuration"
+ "stackEditorShrinkFactorDefault"
+ "stackEditorShrinkFactorSystemSmall"
+ "standBySettings"
- "Wake Animation"
```
