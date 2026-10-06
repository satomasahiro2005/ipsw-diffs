## MaterialKit

> `/System/Library/PrivateFrameworks/MaterialKit.framework/MaterialKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe578` | `0xf148` | **`+0xbd0`** |
| `__AUTH_CONST.__objc_const` | `0x3480` | `0x3660` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0x161c` | `0x1794` | **`+0x178`** |
| `__AUTH_CONST.__cfstring` | `0x12e0` | `0x1440` | **`+0x160`** |
| `__TEXT.__cstring` | `0xf23` | `0x1018` | **`+0xf5`** |
| `__DATA_CONST.__objc_selrefs` | `0x11d8` | `0x12b8` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0x180` | `0x100` | **`-0x80`** |
| `__DATA.__bss` | `0x50` | `0x18` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0x588` | `0x5b8` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x138` | `0x160` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x3b8` | `0x3c0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3c0` | `0x3b8` | **`-0x8`** |
| `__TEXT.__const` | `0x250` | `0x248` | **`-0x8`** |

### Other Changes

```diff

-224.0.0.0.0
+226.0.0.0.0

-  Functions: 490
-  Symbols:   1026
-  CStrings:  204
+  Functions: 519
+  Symbols:   1062
+  CStrings:  215
Symbols:
+ +[MTLumaDodgePillView _defaultScreen]
+ +[MTLumaDodgePillView _defaultUserInterfaceIdiom]
+ +[MTLumaDodgePillView suggestedSizeForContentWidth:screen:settings:]
+ -[MTLumaDodgePillSettings _defaultScreen]
+ -[MTLumaDodgePillSettings _defaultUserInterfaceIdiom]
+ -[MTLumaDodgePillSettings edgeSpacingForUserInterfaceIdiom:screen:]
+ -[MTLumaDodgePillSettings heightForUserInterfaceIdiom:screen:]
+ -[MTLumaDodgePillSettings largePadMaximumWidth]
+ -[MTLumaDodgePillSettings largePadMinimumWidth]
+ -[MTLumaDodgePillSettings maximumWidthForUserInterfaceIdiom:screen:]
+ -[MTLumaDodgePillSettings minimumWidthForUserInterfaceIdiom:screen:]
+ -[MTLumaDodgePillSettings padEdgeSpacing]
+ -[MTLumaDodgePillSettings padHeight]
+ -[MTLumaDodgePillSettings phoneEdgeSpacing]
+ -[MTLumaDodgePillSettings phoneHeight]
+ -[MTLumaDodgePillSettings phoneMaximumWidthRatio]
+ -[MTLumaDodgePillSettings phoneMinimumWidthRatio]
+ -[MTLumaDodgePillSettings setLargePadMaximumWidth:]
+ -[MTLumaDodgePillSettings setLargePadMinimumWidth:]
+ -[MTLumaDodgePillSettings setPadEdgeSpacing:]
+ -[MTLumaDodgePillSettings setPadHeight:]
+ -[MTLumaDodgePillSettings setPhoneEdgeSpacing:]
+ -[MTLumaDodgePillSettings setPhoneHeight:]
+ -[MTLumaDodgePillSettings setPhoneMaximumWidthRatio:]
+ -[MTLumaDodgePillSettings setPhoneMinimumWidthRatio:]
+ -[MTLumaDodgePillSettings setSmallPadMaximumWidth:]
+ -[MTLumaDodgePillSettings setSmallPadMinimumWidth:]
+ -[MTLumaDodgePillSettings smallPadMaximumWidth]
+ -[MTLumaDodgePillSettings smallPadMinimumWidth]
+ -[MTLumaDodgePillView suggestedEdgeSpacingForScreen:]
+ -[MTLumaDodgePillView suggestedSizeForContentWidth:screen:]
+ _CGRectGetWidth
+ _CGRectZero
+ _OBJC_IVAR_$_MTLumaDodgePillSettings._largePadMaximumWidth
+ _OBJC_IVAR_$_MTLumaDodgePillSettings._largePadMinimumWidth
+ _OBJC_IVAR_$_MTLumaDodgePillSettings._padEdgeSpacing
+ _OBJC_IVAR_$_MTLumaDodgePillSettings._padHeight
+ _OBJC_IVAR_$_MTLumaDodgePillSettings._phoneEdgeSpacing
+ _OBJC_IVAR_$_MTLumaDodgePillSettings._phoneHeight
+ _OBJC_IVAR_$_MTLumaDodgePillSettings._phoneMaximumWidthRatio
+ _OBJC_IVAR_$_MTLumaDodgePillSettings._phoneMinimumWidthRatio
+ _OBJC_IVAR_$_MTLumaDodgePillSettings._smallPadMaximumWidth
+ _OBJC_IVAR_$_MTLumaDodgePillSettings._smallPadMinimumWidth
+ ___51+[MTLumaDodgePillSettings settingsControllerModule]_block_invoke_3
+ ___51+[MTLumaDodgePillSettings settingsControllerModule]_block_invoke_4
+ ___block_descriptor_40_e8_32s_e56_"NSNumber"24?0"NSNumber"8"MTLumaDodgePillSettings"16ls32l8
- _OBJC_CLASS_$_CADisplay
- _OBJC_CLASS_$_FBSDisplayConfiguration
- __MainScreenReferenceBounds
- __MainScreenReferenceBounds.__bounds
- __MainScreenReferenceBounds.__once
- __RunningInSpringBoard.__once
- __RunningInSpringBoard.__result
- ____MainScreenReferenceBounds_block_invoke
- ____RunningInSpringBoard_block_invoke
- ___block_descriptor_32_e56_"NSNumber"24?0"NSNumber"8"MTLumaDodgePillSettings"16l
CStrings:
+ "Large Narrow Width"
+ "Large Wide Width"
+ "Narrow Width Ratio"
+ "Small Narrow Width"
+ "Small Wide Width"
+ "Wide Width Ratio"
+ "iPad Geometry"
+ "iPhone Geometry"
+ "largePadMaximumWidth"
+ "largePadMinimumWidth"
+ "padEdgeSpacing"
+ "padHeight"
+ "phoneEdgeSpacing"
+ "phoneHeight"
+ "phoneMaximumWidthRatio"
+ "phoneMinimumWidthRatio"
+ "screen != nil"
+ "smallPadMaximumWidth"
+ "smallPadMinimumWidth"
+ "\xf0e"
- "Geometry"
- "Narrow Width"
- "Wide Width"
- "com.apple.springboard"
- "edgeSpacing"
- "height"
- "maxWidth"
- "minWidth"
- "\xb5"
```
