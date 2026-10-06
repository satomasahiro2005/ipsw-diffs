## SystemApertureUI

> `/System/Library/AccessibilityBundles/SystemApertureUI.axbundle/SystemApertureUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x270c` | `0x2950` | **`+0x244`** |
| `__AUTH_CONST.__cfstring` | `0x740` | `0x700` | **`-0x40`** |
| `__AUTH_CONST.__const` | `0x100` | `0xc0` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x3d4` | `0x3fc` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x208` | `0x1e8` | **`-0x20`** |
| `__TEXT.__cstring` | `0x5de` | `0x5be` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3a8` | `0x3c0` | **`+0x18`** |
| `__DATA.__data` | `0x180` | `0x190` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x150` | `0x160` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb8` | `0xb0` | **`-0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 68
-  Symbols:   246
-  CStrings:  71
+  Functions: 71
+  Symbols:   252
+  CStrings:  69
Symbols:
+ -[SAUIElementViewControllerAccessibility _accessibilityShouldPostScreenChangedOnPresentation]
+ -[SAUIElementViewControllerAccessibility _axAnnounceLiveActivityContent]
+ -[SAUIElementViewControllerAccessibility accessibilityPostScreenChangedForChildViewController:isAddition:]
+ _CFAbsoluteTimeGetCurrent
+ _MACancelDownloadErrorDomain_block_invoke.kLastFocusedPowerAlertKey
+ _OBJC_CLASS_$_AXAttributedString
+ _OBJC_CLASS_$_NSNumber
+ _UIAccessibilityAnnouncementNotification
+ ___53-[SAUIElementViewControllerAccessibility viewDidLoad]_block_invoke
+ ___93-[SAUIElementViewControllerAccessibility viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
+ __axAnnounceLiveActivityContent.kLastAnnounceTimeKey
+ _objc_getAssociatedObject
+ _objc_release_x28
+ _objc_setAssociatedObject
- _AXImageExplorerGenerativeModelsAvailable
- _OBJC_CLASS_$_AXSettings
- _OBJC_CLASS_$_AXVoiceOverServer
- ___58-[SAUIElementViewAccessibility accessibilityCustomActions]_block_invoke_12
- ___58-[SAUIElementViewAccessibility accessibilityCustomActions]_block_invoke_13
- ___block_descriptor_32_e37_B16?0"UIAccessibilityCustomAction"8l
- _kVOTEventCommandActivateScreenExplorer
- _kVOTEventCommandAskAboutScreen
CStrings:
- "ask.about.screen"
- "explore.screen"
```
