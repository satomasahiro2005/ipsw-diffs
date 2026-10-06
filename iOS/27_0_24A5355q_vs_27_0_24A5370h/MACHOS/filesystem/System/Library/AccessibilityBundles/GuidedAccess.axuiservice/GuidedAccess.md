## GuidedAccess

> `/System/Library/AccessibilityBundles/GuidedAccess.axuiservice/GuidedAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e918` | `0x2ec80` | **`+0x368`** |
| `__TEXT.__objc_methname` | `0xc134` | `0xc439` | **`+0x305`** |
| `__TEXT.__objc_methtype` | `0x2242` | `0x24b7` | **`+0x275`** |
| `__DATA.__data` | `0x8e8` | `0xa08` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0x8ca0` | `0x8da0` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x35d4` | `0x367c` | **`+0xa8`** |
| `__DATA.__objc_selrefs` | `0x29a0` | `0x2a40` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x4718` | `0x47b0` | **`+0x98`** |
| `__TEXT.__objc_classname` | `0x6e8` | `0x75f` | **`+0x77`** |
| `__DATA_CONST.__cfstring` | `0x2a20` | `0x29e0` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x1ab8` | `0x1ae8` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0xdbf` | `0xdec` | **`+0x2d`** |
| `__DATA_CONST.__objc_protolist` | `0xb0` | `0xc8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x3e1a` | `0x3e06` | **`-0x14`** |
| `__TEXT.__auth_stubs` | `0xc70` | `0xc60` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x648` | `0x640` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x4e0` | `0x4e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1054.0.0.0.0
+1057.0.0.0.0

-  Symbols:   662
-  CStrings:  2509
+  Symbols:   663
+  CStrings:  2543
Symbols:
+ _GAXUIMessageKeyDisplayIdentifier
+ _OBJC_CLASS_$_UIListContentConfiguration
- _MGGetBoolAnswer
CStrings:
+ "@\"UIViewController\"32@0:8@\"UIPresentationController\"16q24"
+ "@32@0:8@16q24"
+ "B24@0:8@\"UIPopoverPresentationController\"16"
+ "B24@0:8@\"UIPresentationController\"16"
+ "UIAdaptivePresentationControllerDelegate"
+ "UIPopoverPresentationControllerDelegate"
+ "UISheetPresentationControllerDelegate"
+ "_currentDisplayIdentifier"
+ "_reloadInterestAreaPathsForCurrentDisplay"
+ "adaptivePresentationStyleForPresentationController:"
+ "adaptivePresentationStyleForPresentationController:traitCollection:"
+ "contentConfiguration"
+ "dictionaryWithObject:forKey:"
+ "display identifier"
+ "displayConfiguration"
+ "effectiveGeometry"
+ "get interest area paths failed with error %@"
+ "hardwareIdentifier"
+ "imageProperties"
+ "isSymbolImage"
+ "popoverPresentationController:willRepositionPopoverToRect:inView:"
+ "popoverPresentationControllerDidDismissPopover:"
+ "popoverPresentationControllerShouldDismissPopover:"
+ "prepareForPopoverPresentation:"
+ "presentationController:prepareAdaptivePresentationController:"
+ "presentationController:viewControllerForAdaptivePresentationStyle:"
+ "presentationController:willPresentWithAdaptiveStyle:transitionCoordinator:"
+ "presentationControllerDidAttemptToDismiss:"
+ "presentationControllerDidDismiss:"
+ "presentationControllerShouldDismiss:"
+ "presentationControllerWillDismiss:"
+ "q24@0:8@\"UIPresentationController\"16"
+ "q32@0:8@\"UIPresentationController\"16@\"UITraitCollection\"24"
+ "secondaryTextProperties"
+ "setContentConfiguration:"
+ "setObject:forKeyedSubscript:"
+ "setReservedLayoutSize:"
+ "setSecondaryText:"
+ "sheetPresentationControllerDidChangeSelectedDetentIdentifier:"
+ "subtitleCellConfiguration"
+ "textProperties"
+ "v24@0:8@\"UIPopoverPresentationController\"16"
+ "v24@0:8@\"UIPresentationController\"16"
+ "v24@0:8@\"UISheetPresentationController\"16"
+ "v32@0:8@\"UIPresentationController\"16@\"UIPresentationController\"24"
+ "v40@0:8@\"UIPopoverPresentationController\"16N^{CGRect={CGPoint=dd}{CGSize=dd}}24N^@32"
+ "v40@0:8@\"UIPresentationController\"16q24@\"<UIViewControllerTransitionCoordinator>\"32"
+ "v40@0:8@16N^{CGRect={CGPoint=dd}{CGSize=dd}}24N^@32"
+ "v40@0:8@16q24@32"
- "@40@0:8@16@24:32"
- "@56@0:8@16@24{CGSize=dd}32:48"
- "HasMesa"
- "_cachedIconWithName:forPropertyWithSelector:"
- "_cachedIconWithName:inBundle:forPropertyWithSelector:"
- "_cachedIconWithName:inBundle:withSize:forPropertyWithSelector:"
- "detailTextLabel"
- "feature-home"
- "feature-home-mesa"
- "featureViewIconColor"
- "featureViewOptionsButtonFont"
- "flattenedImageWithColor:"
- "hardwareFeatureViewHomeIcon"
- "imageByPreparingThumbnailOfSize:"
- "imageView"
```
