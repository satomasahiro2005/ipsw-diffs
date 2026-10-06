## AccessibilityUIUtilities

> `/System/Library/PrivateFrameworks/AccessibilityUIUtilities.framework/AccessibilityUIUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61578` | `0x62084` | **`+0xb0c`** |
| `__TEXT.__cstring` | `0x5bd2` | `0x5c86` | **`+0xb4`** |
| `__AUTH_CONST.__objc_const` | `0xa130` | `0xa1e0` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x6940` | `0x69e0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x63b4` | `0x6444` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x5080` | `0x50d8` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0xdf3` | `0xe34` | **`+0x41`** |
| `__TEXT.__unwind_info` | `0x1968` | `0x1988` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x7f0` | `0x808` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x11f8` | `0x1208` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x574` | `0x584` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1188` | `0x1190` | **`+0x8`** |

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

-  Functions: 2399
-  Symbols:   4611
-  CStrings:  1060
+  Functions: 2412
+  Symbols:   4633
+  CStrings:  1066
Symbols:
+ -[AXAlertBannerManager pendingDismissalBlock]
+ -[AXAlertBannerManager setPendingDismissalBlock:]
+ -[AXUIFloatingViewPresenter _alignedEdgeConstraintAgainst:]
+ -[AXUIFloatingViewPresenter _avoidanceAffectsAlignedEdge]
+ -[AXUIFloatingViewPresenter _avoidanceRegionDidChange:]
+ -[AXUIFloatingViewPresenter _updateAvoidanceLayoutGuide:]
+ -[AXUIFloatingViewPresenter avoidanceIsVertical]
+ -[AXUIFloatingViewPresenter avoidanceLayoutGuideConstraints]
+ -[AXUIFloatingViewPresenter avoidanceLayoutGuide]
+ -[AXUIFloatingViewPresenter dealloc]
+ -[AXUIFloatingViewPresenter setAvoidanceIsVertical:]
+ -[AXUIFloatingViewPresenter setAvoidanceLayoutGuide:]
+ -[AXUIFloatingViewPresenter setAvoidanceLayoutGuideConstraints:]
+ -[AccessibilityAirPodSettingsController jumpToAVSettings:]
+ GCC_except_table1144
+ GCC_except_table1145
+ GCC_except_table1146
+ GCC_except_table1188
+ GCC_except_table1242
+ GCC_except_table1392
+ GCC_except_table1506
+ GCC_except_table1617
+ GCC_except_table1814
+ GCC_except_table1815
+ GCC_except_table1816
+ GCC_except_table1839
+ GCC_except_table1860
+ GCC_except_table1863
+ GCC_except_table1870
+ GCC_except_table1895
+ _OBJC_IVAR_$_AXAlertBannerManager._pendingDismissalBlock
+ _OBJC_IVAR_$_AXUICaptionSubtitlePreviewView._needsUpdate
+ _OBJC_IVAR_$_AXUIFloatingViewPresenter._avoidanceIsVertical
+ _OBJC_IVAR_$_AXUIFloatingViewPresenter._avoidanceLayoutGuide
+ _OBJC_IVAR_$_AXUIFloatingViewPresenter._avoidanceLayoutGuideConstraints
+ _PSDetailControllerClassKey
+ ___55-[AXUIFloatingViewPresenter _avoidanceRegionDidChange:]_block_invoke
+ _dispatch_block_cancel
+ _dispatch_block_create
+ _kAirPodsFallbackToneVolume
- -[AXAlertBannerManager dismissalTimer]
- -[AXAlertBannerManager setDismissalTimer:]
- GCC_except_table1132
- GCC_except_table1133
- GCC_except_table1134
- GCC_except_table1230
- GCC_except_table1380
- GCC_except_table1494
- GCC_except_table1605
- GCC_except_table1802
- GCC_except_table1803
- GCC_except_table1804
- GCC_except_table1826
- GCC_except_table1834
- GCC_except_table1850
- GCC_except_table1857
- GCC_except_table1882
- _OBJC_IVAR_$_AXAlertBannerManager._dismissalTimer
CStrings:
+ "AXFloatingUIAvoidanceRegionDidChangeNotification"
+ "AXUIFloatingViewPresenter.avoidanceHalf"
+ "AccessibilityAirPodSettingsController: Jumping to Audio Settings"
+ "VolumeControlGroupFooterNonPro"
+ "isVertical"
+ "prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE"
```
