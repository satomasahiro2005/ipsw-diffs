## NTKUltraBezel

> `/System/Library/PrivateFrameworks/NTKUltraBezel.framework/NTKUltraBezel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x120bc` | `0x14434` | **`+0x2378`** |
| `__AUTH_CONST.__objc_const` | `0x1a10` | `0x1dc0` | **`+0x3b0`** |
| `__TEXT.__objc_methlist` | `0xefc` | `0x110c` | **`+0x210`** |
| `__TEXT.__cstring` | `0xab8` | `0xc38` | **`+0x180`** |
| `__DATA_CONST.__objc_selrefs` | `0xc38` | `0xdb0` | **`+0x178`** |
| `__AUTH_CONST.__cfstring` | `0x9e0` | `0xb40` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x121` | `0x272` | **`+0x151`** |
| `__TEXT.__const` | `0x552` | `0x672` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0xac` | `0x1a8` | **`+0xfc`** |
| `__DATA.__bss` | `0x3f0` | `0x450` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x178` | `0x1c4` | **`+0x4c`** |
| `__TEXT.__unwind_info` | `0x480` | `0x4b0` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x660` | `0x678` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x258` | `0x260` | **`+0x8`** |

### Other Changes

```diff

-2483.523.0.4.0
+2483.543.0.0.0

-  Functions: 423
-  Symbols:   838
-  CStrings:  114
+  Functions: 471
+  Symbols:   915
+  CStrings:  131
Symbols:
+ +[NTKFoghornPreferences readinessDemoModeScore]
+ +[NTKFoghornPreferences readinessDemoMode]
+ -[NTKFoghornFaceBezelView _drawReadinessBezelInContext:tritiumProgress:alpha:]
+ -[NTKFoghornFaceBezelView _readinessLabelColor]
+ -[NTKFoghornFaceBezelView _updateBaseLabelForReadinessBezel]
+ -[NTKFoghornFaceBezelView readinessEmphasizedTickColor]
+ -[NTKFoghornFaceBezelView readinessGoForItColor]
+ -[NTKFoghornFaceBezelView readinessGoForItDotColor]
+ -[NTKFoghornFaceBezelView readinessGoForItInactiveColor]
+ -[NTKFoghornFaceBezelView readinessLocalizedSummary]
+ -[NTKFoghornFaceBezelView readinessMonochrome]
+ -[NTKFoghornFaceBezelView readinessNegativeColor]
+ -[NTKFoghornFaceBezelView readinessPaceColor]
+ -[NTKFoghornFaceBezelView readinessPaceDotColor]
+ -[NTKFoghornFaceBezelView readinessPaceInactiveColor]
+ -[NTKFoghornFaceBezelView readinessPositiveColor]
+ -[NTKFoghornFaceBezelView readinessReadyColor]
+ -[NTKFoghornFaceBezelView readinessReadyDotColor]
+ -[NTKFoghornFaceBezelView readinessReadyInactiveColor]
+ -[NTKFoghornFaceBezelView readinessRecoverColor]
+ -[NTKFoghornFaceBezelView readinessRecoverDotColor]
+ -[NTKFoghornFaceBezelView readinessRecoverInactiveColor]
+ -[NTKFoghornFaceBezelView readinessScoreIsAvailable]
+ -[NTKFoghornFaceBezelView readinessScore]
+ -[NTKFoghornFaceBezelView setReadinessEmphasizedTickColor:]
+ -[NTKFoghornFaceBezelView setReadinessGoForItColor:]
+ -[NTKFoghornFaceBezelView setReadinessGoForItDotColor:]
+ -[NTKFoghornFaceBezelView setReadinessGoForItInactiveColor:]
+ -[NTKFoghornFaceBezelView setReadinessLocalizedSummary:]
+ -[NTKFoghornFaceBezelView setReadinessMonochrome:]
+ -[NTKFoghornFaceBezelView setReadinessNegativeColor:]
+ -[NTKFoghornFaceBezelView setReadinessPaceColor:]
+ -[NTKFoghornFaceBezelView setReadinessPaceDotColor:]
+ -[NTKFoghornFaceBezelView setReadinessPaceInactiveColor:]
+ -[NTKFoghornFaceBezelView setReadinessPositiveColor:]
+ -[NTKFoghornFaceBezelView setReadinessReadyColor:]
+ -[NTKFoghornFaceBezelView setReadinessReadyDotColor:]
+ -[NTKFoghornFaceBezelView setReadinessReadyInactiveColor:]
+ -[NTKFoghornFaceBezelView setReadinessRecoverColor:]
+ -[NTKFoghornFaceBezelView setReadinessRecoverDotColor:]
+ -[NTKFoghornFaceBezelView setReadinessRecoverInactiveColor:]
+ -[NTKFoghornFaceBezelView setReadinessScore:]
+ -[NTKFoghornFaceBezelView setReadinessScoreIsAvailable:]
+ -[NTKFoghornFaceBezelView(UIColor) _setReadinessMultiColors]
+ GCC_except_table25
+ _CGContextSetLineJoin
+ _CGRectGetMinX
+ _NTKFoghornReadinessLocalizedString
+ _NTKFoghornReadinessLocalizedStringForState
+ _NTKFoghornReadinessSnapshotScore
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessEmphasizedTickColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessGoForItColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessGoForItDotColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessGoForItInactiveColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessLocalizedSummary
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessMonochrome
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessNegativeColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessPaceColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessPaceDotColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessPaceInactiveColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessPositiveColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessReadyColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessReadyDotColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessReadyInactiveColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessRecoverColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessRecoverDotColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessRecoverInactiveColor
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessScore
+ _OBJC_IVAR_$_NTKFoghornFaceBezelView._readinessScoreIsAvailable
+ ___destructor_8_s0_s8_s16_s24_s32_s40_s48_s56_s64_s72_s80_s88
+ __foghornPreferences.__readinessDemoMode
+ __foghornPreferences.__readinessDemoModeScore
+ __readinessBandEndFraction
+ __readinessBandMaxLevel
+ __readinessBandMinLevel
+ __readinessBandStartFraction
+ _objc_release_x1
CStrings:
+ "%@"
+ "%s: availability changed from %s to %s"
+ "%s: readiness summary unavailable, setting baseline offset with nil attributed text"
+ "-[NTKFoghornFaceBezelView _updateBaseLabelForReadinessBezel]"
+ "-[NTKFoghornFaceBezelView setReadinessScoreIsAvailable:]"
+ "FOGHORN_READINESS_LABEL_ESTABLISHING"
+ "FOGHORN_READINESS_LABEL_GO_FOR_IT"
+ "FOGHORN_READINESS_LABEL_NO_DATA"
+ "FOGHORN_READINESS_LABEL_PACE_YOURSELF"
+ "FOGHORN_READINESS_LABEL_READY"
+ "FOGHORN_READINESS_LABEL_RECOVER"
+ "NTKFoghornReadinessDemo"
+ "NTKFoghornReadinessDemoScore"
+ "Readiness bezel label format failed validation, falling back to level only: %@"
+ "Readiness bezel updating with dataState: %ld, score: %@"
+ "readiness"
+ "setReadinessScoreIsAvailable: not in readiness bezel style, skipping UI update"
```
