## ProductPageExtension

> `/System/Library/ExtensionKit/Extensions/ProductPageExtension.appex/ProductPageExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x750c98` | `0x758fc8` | **`+0x8330`** |
| `__TEXT.__objc_methname` | `0x1e4d5` | `0x1e865` | **`+0x390`** |
| `__DATA.__objc_data` | `0x2a858` | `0x2ab70` | **`+0x318`** |
| `__DATA.__objc_const` | `0x6ba08` | `0x6bd08` | **`+0x300`** |
| `__DATA.__data` | `0x29b28` | `0x29db8` | **`+0x290`** |
| `__TEXT.__swift5_reflstr` | `0x17ac9` | `0x17ce9` | **`+0x220`** |
| `__TEXT.__cstring` | `0x13aa5` | `0x13c55` | **`+0x1b0`** |
| `__DATA.__common` | `0x6ef8` | `0x7098` | **`+0x1a0`** |
| `__TEXT.__objc_stubs` | `0xb380` | `0xb520` | **`+0x1a0`** |
| `__TEXT.__swift5_fieldmd` | `0x1254c` | `0x126dc` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x2f78` | `0x2e00` | **`-0x178`** |
| `__TEXT.__constg_swiftt` | `0x19ba4` | `0x19cd8` | **`+0x134`** |
| `__TEXT.__unwind_info` | `0x12498` | `0x125c0` | **`+0x128`** |
| `__DATA_CONST.__const` | `0x25208` | `0x25108` | **`-0x100`** |
| `__TEXT.__auth_stubs` | `0x16190` | `0x16270` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x85d8` | `0x86a8` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0xfa3c` | `0xfb0a` | **`+0xce`** |
| `__DATA.__objc_selrefs` | `0x4858` | `0x48e8` | **`+0x90`** |
| `__DATA.__bss` | `0x35930` | `0x358b0` | **`-0x80`** |
| `__DATA_CONST.__auth_got` | `0xb0d8` | `0xb148` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0xdd84` | `0xddec` | **`+0x68`** |
| `__TEXT.__objc_classname` | `0xbb94` | `0xbbe4` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x6838` | `0x6868` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x4b50` | `0x4b78` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x188` | `0x16c` | **`-0x1c`** |
| `__TEXT.__const` | `0x37b74` | `0x37b64` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x13d8` | `0x13e0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1efc` | `0x1ef8` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x10fc` | `0x1100` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x13c` | `0x138` | **`-0x4`** |

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

-  Functions: 27245
-  Symbols:   877
-  CStrings:  6919
+  Functions: 27394
+  Symbols:   881
+  CStrings:  6974
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
+ "ProductPageExtension.TodayCardTransitionHarnessViewController"
+ "ProductPageExtension/TodayCardTransitionHarnessViewController.swift"
+ "TodaySettings.transitionHarness"
+ "_TtC20ProductPageExtension40TodayCardTransitionHarnessViewController"
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
