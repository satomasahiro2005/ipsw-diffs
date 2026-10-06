## ZoomWindow

> `/System/Library/AccessibilityBundles/ZoomWindow.axuiservice/ZoomWindow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69dc4` | `0x6a514` | **`+0x750`** |
| `__TEXT.__oslogstring` | `0x437` | `0x8df` | **`+0x4a8`** |
| `__TEXT.__objc_stubs` | `0xbaa0` | `0xbb40` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x1112b` | `0x111ab` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2580` | `0x25b6` | **`+0x36`** |
| `__TEXT.__objc_methtype` | `0x3a2e` | `0x3a5a` | **`+0x2c`** |
| `__DATA.__objc_selrefs` | `0x37f0` | `0x3818` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x17e0` | `0x1800` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x2220` | `0x2240` | **`+0x20`** |
| `__TEXT.__const` | `0x1f50` | `0x1f70` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x4cf0` | `0x4d08` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1120` | `0x1130` | **`+0x10`** |
| `__DATA.__objc_const` | `0x7910` | `0x7918` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x948` | `0x950` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1a08` | `0x1a10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-904.0.0.0.0
+906.0.0.0.0

-  Functions: 2524
-  Symbols:   4959
-  CStrings:  3243
+  Functions: 2525
+  Symbols:   4968
+  CStrings:  3261
Symbols:
+ -[ZWRootViewController windowSceneForAutopanner:]
+ GCC_except_table1352
+ GCC_except_table1521
+ _AXAIWhiteGloveLoggingEnabled
+ _CAColorMatrixMakeColorSourceOver
+ _kCAFilterColorMatrix
+ _objc_msgSend$accessibilityIgnoresInvertColors
+ _objc_msgSend$minimumTrackTintColor
+ _objc_msgSend$textColor
+ _objc_msgSend$valueWithBytes:objCType:
+ _objc_msgSend$windowSceneForAutopanner:
- GCC_except_table1351
- GCC_except_table1520
Functions:
~ -[ZWMenuViewController loadView] : 884 -> 1060
~ -[ZWMenuViewController viewWillAppear:] : 340 -> 512
~ -[ZWMenuViewController _invertColorsChange] : 56 -> 180
~ -[ZWMenuViewController tableView:cellForRowAtIndexPath:] : 800 -> 1020
~ -[ZWMenuViewController _setBackgroundStyleWithInvertColors] : 68 -> 252
~ -[ZWLensZoomView updateLensEffect:animated:completion:] : 1512 -> 1668
~ -[ZWMenuItemZoomLevelSliderTableViewCell initWithStyle:reuseIdentifier:] : 1356 -> 2040
~ -[ZWUIServer removeScene:] : 416 -> 432
+ -[ZWRootViewController windowSceneForAutopanner:]
~ ___86-[ZWRootViewController fullscreenEventHandler:continueZoomMovementWithVelocity:angle:]_block_invoke : 628 -> 668
CStrings:
+ "@\"UIWindowScene\"24@0:8@\"ZWLensAutopanner\"16"
+ "accessibilityIgnoresInvertColors"
+ "inputColorMatrix"
+ "minimumTrackTintColor"
+ "rdar://171256179 ZWMenuItemZoomLevelSliderTableViewCell init enter invertColorsEnabled=%d vibrantBlendModes=%d solariumEnabled=%d"
+ "rdar://171256179 cell.accessibilityIgnoresInvertColors=YES slider.ignoresInvert=%d zoomInIV.ignoresInvert=%d zoomOutIV.ignoresInvert=%d"
+ "rdar://171256179 non-vibrant branch: setDrawsAsBackdropOverlay=NO maxTrackTint=darkGray invertColors=%d"
+ "rdar://171256179 set slider.minimumTrackTintColor=white zoomInTint=%{public}@ zoomOutTint=%{public}@"
+ "rdar://171256179 vibrant branch: applied BackdropOverlayBlendModeVibrant to slider+icons invertColors=%d"
+ "rdar://172074412 ZWMenuViewController _setBackgroundStyleWithInvertColors invertColorsEnabled=%d hasPopover=%d viewIgnoresInvert=%d"
+ "rdar://172074412 ZWMenuViewController cellForRow solarium pill tag=%lu invertColorsEnabled=%d cellIgnoresInvert=%d labelTextColor=%{public}@"
+ "rdar://172074412 ZWMenuViewController loadView solarium=%d invertColorsEnabled=%d bgIgnoresInvert=%d userInterfaceStyle=%ld"
+ "rdar://172074412 ZWMenuViewController viewWillAppear invertColorsEnabled=%d vibrantBlend=%d solarium=%d"
+ "rdar://172074412, rdar://171256179 ZWMenuViewController _invertColorsChange invertColorsEnabled=%d isViewLoaded=%d"
+ "textColor"
+ "valueWithBytes:objCType:"
+ "windowSceneForAutopanner:"
+ "{CAColorMatrix=ffffffffffffffffffff}"
```
