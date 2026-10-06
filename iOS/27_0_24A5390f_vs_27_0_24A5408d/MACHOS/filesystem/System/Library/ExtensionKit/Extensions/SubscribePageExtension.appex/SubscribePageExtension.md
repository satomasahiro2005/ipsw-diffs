## SubscribePageExtension

> `/System/Library/ExtensionKit/Extensions/SubscribePageExtension.appex/SubscribePageExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x73205c` | `0x73aa54` | **`+0x89f8`** |
| `__TEXT.__objc_methname` | `0x1de85` | `0x1e265` | **`+0x3e0`** |
| `__DATA.__objc_data` | `0x2a658` | `0x2a970` | **`+0x318`** |
| `__DATA.__objc_const` | `0x6c598` | `0x6c898` | **`+0x300`** |
| `__DATA.__data` | `0x29340` | `0x29570` | **`+0x230`** |
| `__TEXT.__swift5_reflstr` | `0x17535` | `0x17735` | **`+0x200`** |
| `__TEXT.__cstring` | `0x10e29` | `0x10fd9` | **`+0x1b0`** |
| `__DATA.__common` | `0x6e80` | `0x7020` | **`+0x1a0`** |
| `__TEXT.__objc_stubs` | `0xb020` | `0xb1c0` | **`+0x1a0`** |
| `__TEXT.__swift5_fieldmd` | `0x122f4` | `0x12484` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x2de8` | `0x2c6c` | **`-0x17c`** |
| `__TEXT.__constg_swiftt` | `0x19674` | `0x197a8` | **`+0x134`** |
| `__DATA_CONST.__const` | `0x250e0` | `0x24fe0` | **`-0x100`** |
| `__TEXT.__unwind_info` | `0x123a8` | `0x12490` | **`+0xe8`** |
| `__TEXT.__auth_stubs` | `0x158e0` | `0x159c0` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x8498` | `0x8568` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0xf836` | `0xf904` | **`+0xce`** |
| `__DATA.__objc_selrefs` | `0x4728` | `0x47b8` | **`+0x90`** |
| `__DATA.__bss` | `0x35728` | `0x356a8` | **`-0x80`** |
| `__DATA_CONST.__auth_got` | `0xac80` | `0xacf0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0xde14` | `0xde7c` | **`+0x68`** |
| `__TEXT.__objc_classname` | `0xc116` | `0xc166` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x66c0` | `0x66f0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x4920` | `0x4948` | **`+0x28`** |
| `__TEXT.__const` | `0x37854` | `0x37834` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x180` | `0x164` | **`-0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x13d0` | `0x13d8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1ed8` | `0x1ed4` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x10f0` | `0x10f4` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x134` | `0x130` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-27.0.65.0.0
+27.0.75.0.0

+  - /System/Library/PrivateFrameworks/ServicesIntelligence.framework/ServicesIntelligence

-  Functions: 27085
-  Symbols:   865
-  CStrings:  6792
+  Functions: 27235
+  Symbols:   869
+  CStrings:  6847
Symbols:
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _OBJC_CLASS_$_UIGlassContainerEffect
+ _OBJC_CLASS_$_UISlider
+ _UIBarButtonItemVisibilityPriorityHigh
- __UIBarElementVisibilityPriorityHigh
CStrings:
+ "Card Transition Lab"
+ "Compact height (landscape)"
+ "Enable the on screen button that opens the Today card VisualStyle transition harness"
+ "Failed to clear app usage: "
+ "No cards in feed"
+ "SubscribePageExtension.TodayCardTransitionHarnessViewController"
+ "SubscribePageExtension/TodayCardTransitionHarnessViewController.swift"
+ "TodaySettings.transitionHarness"
+ "_TtC22SubscribePageExtension40TodayCardTransitionHarnessViewController"
+ "_gridFootprint"
+ "addClip"
+ "alignedRegionArtworkAspectRatio"
+ "bezierPathWithOvalInRect:"
+ "canvas"
+ "cardPickerButton"
+ "cards"
+ "compactHeightSwitch"
+ "compactHeightToggled"
+ "currentCard"
+ "currentWidth"
+ "dismissHarness"
+ "durationLabel"
+ "durationSlider"
+ "durationSliderChanged"
+ "fontForStyle"
+ "fontStyle"
+ "glassContainer"
+ "gridFootprint"
+ "hostedCell"
+ "inAppPurchaseCompact"
+ "initWithItems:"
+ "initWithPath:retinaScale:"
+ "isMini"
+ "isOriginallyMini"
+ "lastConfiguredContentWidth"
+ "minWidth"
+ "originalGridFootprint"
+ "originalIsMini"
+ "paletteImpressionCalculator"
+ "pathForResource:ofType:"
+ "rectangle.expand.vertical"
+ "refreshGuidedSearchImpressionsOnNextAppear"
+ "removeArrangedSubview:"
+ "setContentsRect:"
+ "setIncludeAppLinksForCallingApplication:"
+ "setMaximumValue:"
+ "setMinimumValue:"
+ "setSearchBarStyle:"
+ "setValue:"
+ "setVisibilityPriority:"
+ "stopCount"
+ "stopsBuiltForMaxWidth"
+ "stopsRow"
+ "stopsSegmentChanged"
+ "stopsSegmentedControl"
+ "systemPurpleColor"
+ "transitionHarnessButton"
+ "usesCompactMetrics"
+ "value"
+ "visualStyle"
+ "widthLabel"
+ "widthSlider"
+ "widthSliderChanged"
- "Compact Extra Wide"
- "_setVisibilityPriority:"
- "_sizeCategory"
- "fontForSizeCategory"
- "initWithFileName:retinaScale:"
- "originalSizeCategory"
- "ratingSubscription"
- "sizeCategory"
```
