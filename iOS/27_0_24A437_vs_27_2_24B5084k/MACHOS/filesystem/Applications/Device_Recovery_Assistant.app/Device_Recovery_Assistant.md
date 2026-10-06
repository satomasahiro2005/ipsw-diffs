## Device Recovery Assistant

> `/Applications/Device Recovery Assistant.app/Device Recovery Assistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1facc` | `0x21314` | **`+0x1848`** |
| `__TEXT.__oslogstring` | `0x3956` | `0x3efb` | **`+0x5a5`** |
| `__TEXT.__objc_methname` | `0x8dc2` | `0x92ca` | **`+0x508`** |
| `__TEXT.__objc_stubs` | `0x6500` | `0x69a0` | **`+0x4a0`** |
| `__TEXT.__cstring` | `0x36a7` | `0x3956` | **`+0x2af`** |
| `__DATA.__objc_const` | `0x6718` | `0x6910` | **`+0x1f8`** |
| `__DATA.__objc_selrefs` | `0x2390` | `0x24d0` | **`+0x140`** |
| `__DATA_CONST.__cfstring` | `0x1980` | `0x1aa0` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x2eb8` | `0x2f88` | **`+0xd0`** |
| `__DATA.__objc_data` | `0xb40` | `0xbe0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0xa80` | `0xb18` | **`+0x98`** |
| `__TEXT.__objc_methtype` | `0x2597` | `0x2614` | **`+0x7d`** |
| `__TEXT.__unwind_info` | `0x748` | `0x790` | **`+0x48`** |
| `__TEXT.__const` | `0xa8` | `0xe8` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x699` | `0x6bf` | **`+0x26`** |
| `__TEXT.__auth_stubs` | `0x850` | `0x870` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x224` | `0x234` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x438` | `0x448` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x120` | `0x130` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x110` | `0x120` | **`+0x10`** |
| `__DATA.__bss` | `0x90` | `0x98` | **`+0x8`** |
| `__DATA.__data` | `0xce0` | `0xcd8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-150.0.2.0.0
+150.40.7.0.0

-  Functions: 822
-  Symbols:   310
-  CStrings:  2410
+  Functions: 846
+  Symbols:   315
+  CStrings:  2502
Symbols:
+ _CFDataGetLength
+ _CGRectGetWidth
+ _NSStringFromUIEdgeInsets
+ _OBJC_CLASS_$_BKSHIDUISensorMode
+ _OBJC_CLASS_$_BKSHIDUISensorService
+ _OBJC_METACLASS_$_OBNavigationController
+ _OBJC_METACLASS_$_UIWindow
- _BKSHIDServicesSetHIDUILockedState
- _UIEdgeInsetsZero
CStrings:
+ "%{public}s: Current language re-selected, returning to the previous screen."
+ "%{public}s: Current language row re-selected, dismissing without relaunching the shell."
+ "%{public}s: Current language row resolved to index %lu"
+ "%{public}s: Custom Back button tapped."
+ "%{public}s: Language picker: %lu of %lu system languages are localized in this bundle."
+ "%{public}s: Skipping custom Back button install: left bar button item already in use."
+ "%{public}s: [DisplayManager] No BKSHIDUISensorService for display %{public}@ (uuid=%{public}@); skipping."
+ "%{public}s: [DisplayManager] No hardwareIdentifier for display %{public}@; falling back to +sharedInstance."
+ "%{public}s: [DisplayManager] Requested digitizerEnabled=%d for display %{public}@ (uuid=%{public}@)"
+ "%{public}s: [DisplayManager] requestUISensorMode: returned nil for display %{public}@ (uuid=%{public}@); digitizer state for this display is now unknown."
+ "%{public}s: [Geometry] island bottom %.2f pt exceeds sanity limit %.2f pt (raw %d px, scale %.2f); treating part as no-cutout"
+ "%{public}s: [Geometry] island-notch-location = %d px"
+ "%{public}s: [Geometry] island-notch-location absent; treating part as no-cutout"
+ "%{public}s: [Geometry] island-notch-location too short (%ld bytes)"
+ "%{public}s: [RecoveryWindow] form=%{public}s islandBottom=%.2f base=%{public}@ reported=%{public}@ orientation=%ld locked=%{public}s"
+ "%{public}s: [StatusBar] Overlay placed: centred=%{public}s centerY=%.2f clearance=%.2f"
+ "-"
+ "-[DRNavigationController dr_backButtonTapped:]"
+ "-[DRNavigationController dr_installCustomBackButtonForViewController:]"
+ "-[DisplayManager _setDigitizerEnabledOnAllDisplays:]"
+ "-[LanguageViewController readSupportedLanguages]"
+ "-[RecoveryWindow layoutSubviews]"
+ "-[SceneDelegate languageViewControllerDidChooseCurrentLanguage:]"
+ "-[StatusBar setupStatusBarForWindowScene:]"
+ "AppleLanguages"
+ "B24@?0@\"NSString\"8@\"NSDictionary\"16"
+ "B32@?0@\"NSString\"8Q16^B24"
+ "BACK_BUTTON_LABEL"
+ "DRDynamicIslandBottom"
+ "DRNavigationController"
+ "DRRawIslandNotchPixels_block_invoke"
+ "DeviceRecovery dim"
+ "DeviceRecovery undim"
+ "RecoveryWindow"
+ "T@\"NSDictionary\",&,N,V_digitizerSensorModeTokensByDisplayUUID"
+ "TB,N,V_hasReportedInsets"
+ "TQ,N,V_currentLanguageIndex"
+ "T{UIEdgeInsets=dddd},N,V_lastReportedInsets"
+ "_"
+ "__mainDisplayFallback__%lu__%@"
+ "_currentLanguageIndex"
+ "_digitizerSensorModeTokensByDisplayUUID"
+ "_hasReportedInsets"
+ "_indexOfCurrentLanguage"
+ "_lastReportedInsets"
+ "_setDigitizerEnabledOnAllDisplays:"
+ "accessibilityIdentifier"
+ "acquireTransactionForReason:"
+ "buildModeForReason:builder:"
+ "canonicalLanguageIdentifierFromString:"
+ "caseInsensitiveCompare:"
+ "chevron.backward"
+ "currentLanguageIndex"
+ "cutout"
+ "digitizerSensorModeTokensByDisplayUUID"
+ "dr.navigationBar.backButton"
+ "dr_backButtonTapped:"
+ "dr_installCustomBackButtonForViewController:"
+ "dr_installCustomBackButtonsForCurrentStack"
+ "effectiveGeometry"
+ "hardwareIdentifier"
+ "hasPrefix:"
+ "hasReportedInsets"
+ "hidesBackButton"
+ "indexOfObjectPassingTest:"
+ "initWithImage:style:target:action:"
+ "interfaceOrientation"
+ "isInterfaceOrientationLocked"
+ "languageViewControllerDidChooseCurrentLanguage:"
+ "lastReportedInsets"
+ "layoutSubviews"
+ "leftBarButtonItem"
+ "leftBarButtonItems"
+ "localeIdentifier"
+ "localizations"
+ "makeObjectsPerformSelector:"
+ "no-cutout"
+ "popViewControllerAnimated:"
+ "predicateWithBlock:"
+ "requestUISensorMode:"
+ "serviceForDisplayUUID:"
+ "setCurrentLanguageIndex:"
+ "setDigitizerEnabled:"
+ "setDigitizerSensorModeTokensByDisplayUUID:"
+ "setDisplayState:"
+ "setHasReportedInsets:"
+ "setLastReportedInsets:"
+ "stringByReplacingOccurrencesOfString:withString:"
+ "synchronize"
+ "v16@?0@\"BKSMutableHIDUISensorMode\"8"
+ "v24@0:8@\"LanguageViewController\"16"
+ "v48@0:8{UIEdgeInsets=dddd}16"
+ "viewControllers"
+ "{UIEdgeInsets=\"top\"d\"left\"d\"bottom\"d\"right\"d}"
+ "{UIEdgeInsets=dddd}16@0:8"
- "d24@0:8@16"
- "dynamicIslandBottom:"
- "languageCode"
```
