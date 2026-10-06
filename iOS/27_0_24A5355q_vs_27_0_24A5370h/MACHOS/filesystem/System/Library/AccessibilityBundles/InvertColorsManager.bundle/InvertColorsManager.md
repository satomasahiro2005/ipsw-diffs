## InvertColorsManager

> `/System/Library/AccessibilityBundles/InvertColorsManager.bundle/InvertColorsManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f558` | `0x2093c` | **`+0x13e4`** |
| `__TEXT.__oslogstring` | `0x607` | `0xb76` | **`+0x56f`** |
| `__DATA.__objc_const` | `0x211f8` | `0x21558` | **`+0x360`** |
| `__DATA_CONST.__cfstring` | `0x8b00` | `0x8d80` | **`+0x280`** |
| `__DATA.__objc_data` | `0x109a0` | `0x10b80` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x8b67` | `0x8d34` | **`+0x1cd`** |
| `__TEXT.__objc_methname` | `0x2b30` | `0x2c65` | **`+0x135`** |
| `__TEXT.__objc_classname` | `0xa102` | `0xa230` | **`+0x12e`** |
| `__TEXT.__objc_stubs` | `0x2700` | `0x2820` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x76ac` | `0x77bc` | **`+0x110`** |
| `__TEXT.__auth_stubs` | `0x750` | `0x7e0` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x7a0` | `0x818` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0xdb8` | `0xe10` | **`+0x58`** |
| `__DATA_CONST.__auth_got` | `0x3b8` | `0x400` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0xf30` | `0xf70` | **`+0x40`** |
| `__DATA_CONST.__objc_classlist` | `0x1a90` | `0x1ac0` | **`+0x30`** |
| `__TEXT.__const` | `0x98` | `0xc8` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x314` | `0x334` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1bc` | `0x1d8` | **`+0x1c`** |
| `__DATA_CONST.__objc_superrefs` | `0x5f0` | `0x608` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x170` | `0x178` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 1894
-  Symbols:   1875
-  CStrings:  2084
+  Functions: 1917
+  Symbols:   1897
+  CStrings:  2135
Symbols:
+ _CFNotificationCenterRemoveObserver
+ _NSStringFromCGRect
+ _OBJC_CLASS_$_SBDeviceApplicationSceneViewInvertColorsAccessibility
+ _OBJC_CLASS_$_SBHWidgetContainerViewInvertColorsAccessibility
+ _OBJC_CLASS_$_SBSceneViewInvertColorsAccessibility
+ _OBJC_CLASS_$___SBDeviceApplicationSceneViewInvertColorsAccessibility_super
+ _OBJC_CLASS_$___SBHWidgetContainerViewInvertColorsAccessibility_super
+ _OBJC_CLASS_$___SBSceneViewInvertColorsAccessibility_super
+ _OBJC_METACLASS_$_SBDeviceApplicationSceneViewInvertColorsAccessibility
+ _OBJC_METACLASS_$_SBHWidgetContainerViewInvertColorsAccessibility
+ _OBJC_METACLASS_$_SBSceneViewInvertColorsAccessibility
+ _OBJC_METACLASS_$___SBDeviceApplicationSceneViewInvertColorsAccessibility_super
+ _OBJC_METACLASS_$___SBHWidgetContainerViewInvertColorsAccessibility_super
+ _OBJC_METACLASS_$___SBSceneViewInvertColorsAccessibility_super
+ __dispatch_main_q
+ _dispatch_after
+ _dispatch_async
+ _dispatch_time
+ _notify_post
+ _objc_getAssociatedObject
+ _objc_opt_respondsToSelector
+ _objc_setAssociatedObject
CStrings:
+ "<unknown>"
+ "AXLaunchOverlay/app: not posting appready — applyWindowLevelInvert is NO (window %@, isDarkWindow=%d, supportsDarkWindowInvert=%d)"
+ "AXLaunchOverlay/app: posted %{public}@ for window %@ (notify_post status=%u)"
+ "AXLaunchOverlay: GOT app-ready notification %{public}@ for sceneView %@"
+ "AXLaunchOverlay: INSTALLED overlay bundleID=%{public}@ sceneView=%@ overlayFrame=%@ observing=%{public}@"
+ "AXLaunchOverlay: REMOVING overlay bundleID=%{public}@ reason=%{public}@ animated=%d"
+ "AXLaunchOverlay: bundleID resolve fail — application %@ has empty bundleIdentifier"
+ "AXLaunchOverlay: bundleID resolve fail — application %@ has no -bundleIdentifier"
+ "AXLaunchOverlay: bundleID resolve fail — no -application selector (class %@)"
+ "AXLaunchOverlay: install aborted — bundleID resolution failed"
+ "AXLaunchOverlay: install aborted — self is not a UIView (class %@)"
+ "AXLaunchOverlay: pre-install diagnostics — sceneView bounds %@, window %@, window has invert filter: %d, traitStyle: %ld"
+ "AXLaunchOverlay: resolved bundleID %{public}@ for app %@"
+ "AXLaunchOverlay: sceneView didMoveToWindow window=%@ windowHasInvertFilter=%d traitStyle=%ld supportsDarkInvert=%d"
+ "AXLaunchOverlay: setDisplayMode:%{public}@ on %@ (sceneViewKindOfApplication=%d)"
+ "AXLaunchOverlay: skip — Smart Invert not enabled"
+ "AXLaunchOverlay: skip — not in system-wide Dark Mode"
+ "AXLaunchOverlay: skip — overlay already installed on %@"
+ "CustomContent"
+ "LiveContent"
+ "LiveSnapshot"
+ "None"
+ "PlaceholderContent"
+ "SBApplicationProcessState"
+ "SBCoverSheetWindow"
+ "SBDeviceApplicationSceneViewInvertColorsAccessibility"
+ "SBHWidgetContainerView"
+ "SBHWidgetContainerViewController"
+ "SBHWidgetContainerViewInvertColorsAccessibility"
+ "SBSceneViewInvertColorsAccessibility"
+ "__SBDeviceApplicationSceneViewInvertColorsAccessibility_super"
+ "__SBHWidgetContainerViewInvertColorsAccessibility_super"
+ "__SBSceneViewInvertColorsAccessibility_super"
+ "_axShouldCounterCoverSheetDarkWindowInvert"
+ "_ax_launchOverlayInstall"
+ "_ax_launchOverlayRemoveAnimated:reason:"
+ "_ax_launchOverlayResolveBundleID"
+ "_ax_launchOverlayShouldInstall"
+ "animateWithDuration:animations:completion:"
+ "app-ready"
+ "bringSubviewToFront:"
+ "com.apple.accessibility.invertcolors.appready.%@"
+ "frame"
+ "invalidate"
+ "pid"
+ "processState"
+ "setDisplayMode:animationFactory:completion:"
+ "timeout"
+ "updateDarkModeWindowInvert:"
+ "v12@?0B8"
+ "v28@0:8B16@20"
+ "v40@0:8q16@24@?32"
- "toggleDarkModeWindowInvert:"
```
