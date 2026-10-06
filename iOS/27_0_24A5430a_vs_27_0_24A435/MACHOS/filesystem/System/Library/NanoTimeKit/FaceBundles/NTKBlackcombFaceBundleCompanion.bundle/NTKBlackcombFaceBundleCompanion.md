## NTKBlackcombFaceBundleCompanion

> `/System/Library/NanoTimeKit/FaceBundles/NTKBlackcombFaceBundleCompanion.bundle/NTKBlackcombFaceBundleCompanion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6804` | `0xa67c` | **`+0x3e78`** |
| `__TEXT.__objc_methname` | `0x2148` | `0x2cab` | **`+0xb63`** |
| `__TEXT.__objc_stubs` | `0x1c80` | `0x2740` | **`+0xac0`** |
| `__DATA.__objc_const` | `0xfb0` | `0x1430` | **`+0x480`** |
| `__TEXT.__objc_methlist` | `0x91c` | `0xccc` | **`+0x3b0`** |
| `__DATA.__objc_selrefs` | `0xad0` | `0xde0` | **`+0x310`** |
| `__TEXT.__cstring` | `0x286` | `0x492` | **`+0x20c`** |
| `__DATA_CONST.__objc_intobj` | `0x258` | `0x3a8` | **`+0x150`** |
| `__DATA_CONST.__cfstring` | `0x2e0` | `0x420` | **`+0x140`** |
| `__TEXT.__objc_methtype` | `0x478` | `0x5a9` | **`+0x131`** |
| `__TEXT.__auth_stubs` | `0x400` | `0x510` | **`+0x110`** |
| `__DATA.__objc_data` | `0x190` | `0x280` | **`+0xf0`** |
| `__DATA.__bss` | `0xa8` | `0x188` | **`+0xe0`** |
| `__DATA_CONST.__objc_arraydata` | `0x120` | `0x1f8` | **`+0xd8`** |
| `__DATA_CONST.__objc_arrayobj` | `0x288` | `0x360` | **`+0xd8`** |
| `__TEXT.__unwind_info` | `0x270` | `0x340` | **`+0xd0`** |
| `__TEXT.__const` | `0x80` | `0x140` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x118` | `0x1c0` | **`+0xa8`** |
| `__DATA_CONST.__auth_got` | `0x210` | `0x298` | **`+0x88`** |
| `__TEXT.__objc_classname` | `0xc4` | `0x136` | **`+0x72`** |
| `__TEXT.__oslogstring` | `—` | `0x64` | **`+0x64`** |
| `__DATA_CONST.__objc_doubleobj` | `0x80` | `0xe0` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x180` | `0x1b8` | **`+0x38`** |
| `__DATA_CONST.__objc_catlist` | `0x8` | `0x20` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x40` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x3c` | `0x50` | **`+0x14`** |
| `__DATA_CONST.__objc_superrefs` | `0x30` | `0x38` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-  Functions: 147
-  Symbols:   142
-  CStrings:  485
+  Functions: 240
+  Symbols:   182
+  CStrings:  635
Symbols:
+ _CGRectGetHeight
+ _CGRectGetWidth
+ _CGRectZero
+ _CLKRoundForDevice
+ _NTKBlackcombAnalogDialStyleClassicName
+ _NTKBlackcombAnalogDialStyleMajorMinorName
+ _NTKBlackcombAnalogDialStyleMajorOnlyName
+ _OBJC_CLASS_$_CLKSensitiveUIMonitor
+ _OBJC_CLASS_$_CLKUIAnalogDialRecipe
+ _OBJC_CLASS_$_CLKUIAnalogDialRingRecipe
+ _OBJC_CLASS_$_CLKUIAnalogDialTickGroupRecipe
+ _OBJC_CLASS_$_CLKUIAnalogDialView
+ _OBJC_CLASS_$_CLKUIAnalogHandsView
+ _OBJC_CLASS_$_CLKUIHandsView
+ _OBJC_CLASS_$_CLKUITimeView
+ _OBJC_CLASS_$_CLKUITimeViewConfiguration
+ _OBJC_CLASS_$_NTKBlackcombAnalogDialStyleEditOption
+ _OBJC_CLASS_$_NTKBlackcombPicayuneView
+ _OBJC_CLASS_$_NTKBlackcombPicayuneViewConfiguration
+ _OBJC_CLASS_$_NTKEnumeratedEditOption
+ _OBJC_METACLASS_$_CLKUITimeView
+ _OBJC_METACLASS_$_CLKUITimeViewConfiguration
+ _OBJC_METACLASS_$_NTKBlackcombAnalogDialStyleEditOption
+ _OBJC_METACLASS_$_NTKBlackcombPicayuneView
+ _OBJC_METACLASS_$_NTKBlackcombPicayuneViewConfiguration
+ _OBJC_METACLASS_$_NTKEnumeratedEditOption
+ _UICeilToViewScale
+ _UIRoundToViewScale
+ __NSConcreteGlobalBlock
+ __NTKLoggingObjectForDomain
+ __os_log_error_impl
+ _dispatch_once
+ _objc_autoreleasePoolPop
+ _objc_autoreleasePoolPush
+ _objc_getAssociatedObject
+ _objc_release_x1
+ _objc_retain_x27
+ _objc_retain_x4
+ _objc_retain_x5
+ _objc_retain_x8
+ _objc_setAssociatedObject
+ _os_log_type_enabled
- _NTKCompanionClockFaceLocalizedString
- _OBJC_CLASS_$_CLKUIAnalogTimeView
CStrings:
+ "!"
+ "%s: colorPalette (%@) is not NTKBlackcombColorPalette"
+ "%s: not NTKBlackcombPicayuneViewConfiguration"
+ "+[CLKUIAnalogDialView(NTKBlackcomb) _dialColorStyleFromColorPalette:]"
+ "-[NTKBlackcombPicayuneView setConfiguration:]"
+ "@\"<NTKBlackcombColorPalette>\""
+ "@\"CLKUIAnalogDialView\""
+ "@\"CLKUIHandsView\""
+ "@24@0:8#16"
+ "@36@0:8Q16B24Q28"
+ "@40@0:8Q16Q24@32"
+ "EDIT_MODE_BLACKCOMB_LABEL_BACKGROUND"
+ "EDIT_MODE_BLACKCOMB_LABEL_DIAL_STYLE"
+ "EDIT_OPTION_LABEL_BLACKCOMB_BACKGROUND_OFF"
+ "EDIT_OPTION_LABEL_BLACKCOMB_BACKGROUND_ON"
+ "EDIT_OPTION_LABEL_BLACKCOMB_DIAL_STYLE_CLASSIC"
+ "EDIT_OPTION_LABEL_BLACKCOMB_DIAL_STYLE_MAJORMINOR"
+ "EDIT_OPTION_LABEL_BLACKCOMB_DIAL_STYLE_MAJORONLY"
+ "FACE_BLACKCOMB_DESCRIPTION_27"
+ "NTKBlackcomb"
+ "NTKBlackcombAnalogDialStyleEditOption"
+ "NTKBlackcombPicayuneView"
+ "NTKBlackcombPicayuneViewConfiguration"
+ "NTKLoggingDomainFace"
+ "Q24@0:8@16"
+ "T@\"<CLKUIAnalogDialRecipe>\",R"
+ "T@\"<NTKBlackcombColorPalette>\",&,N"
+ "T@\"<NTKBlackcombColorPalette>\",&,N,V_colorPalette"
+ "T@\"CLKUIAnalogDialView\",&,N,V_analogDialView"
+ "T@\"CLKUIHandsView\",&,N,V_handsView"
+ "TB,N"
+ "TB,N,V_showSensitiveUI"
+ "TQ,N"
+ "TQ,N,V_dialStyle"
+ "TQ,R,N"
+ "Update27"
+ "_analogDialView"
+ "_blackcombColorPaletteKey"
+ "_colorPalette"
+ "_colorPaletteKey"
+ "_dialColorStyleFromColorPalette:"
+ "_dialColorStyleKey"
+ "_dialRecipeForDialStyle:usesLongSideTicks:dialColorStyle:"
+ "_dialStyle"
+ "_dialStyleForDialRecipe:"
+ "_handsView"
+ "_initialDefaultComplicationForSlot:forDevice:"
+ "_optionWithValue:forDevice:"
+ "_orderedValuesForDevice:"
+ "_renderBackgroundViewSwatchImageForBlackcombDialColor:dialStyle:pigmentEditOption:"
+ "_saveDialColorStyle:"
+ "_savedDialColorStyle"
+ "_setColorPalette:"
+ "_setColorsWithColorPalette:tritumProgress:"
+ "_setDialRecipeFromDialStyle:"
+ "_setDialRecipeFromDialStyle:fromUsesLongSideTicks:fromDialColorStyle:toDialStyle:toUsesLongSideTicks:toDialColorStyle:dialFraction:"
+ "_setDialWithConfiguration:tritumProgress:"
+ "_setFromColorPalette:fromDialColorStyle:fromDialStyle:toColorPalette:toDialColorStyle:toDialStyle:fraction:"
+ "_setFromColorPalette:toColorPalette:paletteFraction:fromDialStyle:toDialStyle:dialFraction:"
+ "_showSensitiveUI"
+ "_snapshotKeyForValue:forDevice:"
+ "_updateHandsColorsFromColorPalette:toColorPalette:fraction:"
+ "_usesLongSideTicksForDialRecipe:"
+ "_value"
+ "_valueToFaceBundleStringDict"
+ "activeAppearance"
+ "analogDialView"
+ "anyComplicationOfType:"
+ "blackcombClassic"
+ "blackcombClassicLongSideTicks"
+ "blackcombClassicWithLongSideTicks:"
+ "blackcombMajorMedial"
+ "blackcombMajorMedialBackgroundOn"
+ "blackcombMajorOnly"
+ "blackcombMajorOnlyBackgroundOn"
+ "blackcombMiniClockClassic"
+ "blackcombMiniClockClassic0"
+ "blackcombMiniClockMajorMinor"
+ "blackcombMiniClockMajorOnly"
+ "classic"
+ "collectionType"
+ "colorPalette"
+ "dialColors"
+ "dialRecipe"
+ "dialStyle"
+ "handLength"
+ "handWidth"
+ "handsView"
+ "hourHandView"
+ "initWithDevice:clockTimer:"
+ "initWithDiameter:forDevice:"
+ "initWithDomainName:inBundle:"
+ "initWithEdgeMargin:outer:middle:inner:"
+ "initWithFrame:forDevice:"
+ "initWithGeometry:major:medial:minor:"
+ "initWithTickCount:tickInset:tickLength:tickWidth:tickCapStyle:"
+ "initWithTickCount:tickInset:tickLength:tickWidth:tickCapStyle:tickGeometryFunction:"
+ "isRunningOrchidGMOrLater"
+ "isSensitiveUIEnabled"
+ "length"
+ "major"
+ "majorMedialBackgroundOn:"
+ "majorMinor"
+ "majorOnlyBackgroundOn:"
+ "medial"
+ "miniClockMajorMedial0"
+ "miniClockMajorOnly0"
+ "minor"
+ "minuteHandView"
+ "none"
+ "nullComplication"
+ "numberWithUnsignedInteger:"
+ "optionWithDialStyleStyle:forDevice:"
+ "outer"
+ "pegRadius"
+ "seasons.fall2026.burgundy"
+ "seasons.fall2026.olive"
+ "seasons.fall2026.sand"
+ "seasons.fall2026.wildflowerBlue"
+ "secondHandConfiguration"
+ "secondHandDot"
+ "setAnalogDialView:"
+ "setAodTransform:"
+ "setCenter:"
+ "setColorPalette:"
+ "setColorPaletteFrom:to:fraction:"
+ "setDialRecipe:"
+ "setDialRecipeFrom:to:fraction:"
+ "setDialStyle:"
+ "setDialStyleFrom:to:fraction:"
+ "setEnableBackgroundColorAction:"
+ "setFrame:"
+ "setFromColorPalette:fromDialColorStyle:toColorPalette:toDialColorStyle:fraction:"
+ "setFrozen:"
+ "setHandsView:"
+ "setMajorTickColor:"
+ "setMedialTickColor:"
+ "setMinorTickColor:"
+ "setOverrideDate:"
+ "setPigmentEditOption:"
+ "setPrimaryColor:"
+ "setSecondHandDisabled:"
+ "setShowSensitiveUI:"
+ "setShowingStatusIndicator:inRect:"
+ "setState:"
+ "setUsesLongSideTicksFrom:to:fraction:"
+ "sharedMonitor"
+ "showSensitiveUI"
+ "swatchStyle"
+ "traitCollection"
+ "v32@0:8@16d24"
+ "v32@0:8B16B20d24"
+ "v40@0:8@16@24d32"
+ "v40@0:8Q16Q24d32"
+ "v56@0:8@16Q24@32Q40d48"
+ "v64@0:8@16@24d32Q40Q48d56"
+ "v64@0:8Q16B24Q28Q36B44Q48d56"
+ "v64@0:8{CGAffineTransform=dddddd}16"
+ "v72@0:8@16Q24Q32@40Q48Q56d64"
+ "v8@?0"
- "@\"NTKBlackcombBackgroundView\""
- "EDIT_MODE_BLACKCOMB_LABEL_STYLE"
- "EDIT_OPTION_LABEL_BLACKCOMB_DIAL_BLACK"
- "EDIT_OPTION_LABEL_BLACKCOMB_DIAL_WHITE"
- "Loquat"
- "Short Face Description"
- "_backgroundView"
- "_renderBackgroundViewSwatchImageForBlackcombDialColor:pigmentEditOption:"
- "setHandDotColor:"
- "short description"
```
