## InvertColorsManager

> `/System/Library/AccessibilityBundles/InvertColorsManager.bundle/InvertColorsManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20b20` | `0x220ec` | **`+0x15cc`** |
| `__DATA.__objc_const` | `0x214c8` | `0x21708` | **`+0x240`** |
| `__DATA_CONST.__cfstring` | `0x8d00` | `0x8f40` | **`+0x240`** |
| `__TEXT.__cstring` | `0x8cc4` | `0x8ebf` | **`+0x1fb`** |
| `__TEXT.__oslogstring` | `0xdb4` | `0xfa9` | **`+0x1f5`** |
| `__TEXT.__objc_stubs` | `0x28c0` | `0x2a80` | **`+0x1c0`** |
| `__TEXT.__objc_methname` | `0x2cfb` | `0x2ea7` | **`+0x1ac`** |
| `__DATA.__objc_data` | `0x10a90` | `0x10bd0` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x818` | `0x930` | **`+0x118`** |
| `__TEXT.__objc_classname` | `0xa17e` | `0xa264` | **`+0xe6`** |
| `__TEXT.__objc_methlist` | `0x779c` | `0x783c` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0xe40` | `0xeb8` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0xf70` | `0xfe0` | **`+0x70`** |
| `__DATA.__bss` | `0xb0` | `0xe8` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x1d8` | `0x200` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x334` | `0x357` | **`+0x23`** |
| `__DATA_CONST.__objc_classlist` | `0x1aa8` | `0x1ac8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x7f0` | `0x810` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x408` | `0x418` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x190` | `0x1a0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x600` | `0x610` | **`+0x10`** |
| `__TEXT.__const` | `0xd0` | `0xe0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-3245.8.4.2.0
+3245.8.9.0.0

-  Functions: 1917
-  Symbols:   1893
-  CStrings:  2142
+  Functions: 1939
+  Symbols:   1906
+  CStrings:  2186
Symbols:
+ _OBJC_CLASS_$_AXDispatchTimer
+ _OBJC_CLASS_$_NSConstantArray
+ _OBJC_CLASS_$_SBFLegacyWallpaperWakeAnimatorInvertColorsAccessibility
+ _OBJC_CLASS_$_SBTraitsSingleSceneWindowInvertColorsAccessibility
+ _OBJC_CLASS_$_UIWindowScene
+ _OBJC_CLASS_$___SBFLegacyWallpaperWakeAnimatorInvertColorsAccessibility_super
+ _OBJC_CLASS_$___SBTraitsSingleSceneWindowInvertColorsAccessibility_super
+ _OBJC_METACLASS_$_SBFLegacyWallpaperWakeAnimatorInvertColorsAccessibility
+ _OBJC_METACLASS_$_SBTraitsSingleSceneWindowInvertColorsAccessibility
+ _OBJC_METACLASS_$___SBFLegacyWallpaperWakeAnimatorInvertColorsAccessibility_super
+ _OBJC_METACLASS_$___SBTraitsSingleSceneWindowInvertColorsAccessibility_super
+ _objc_release_x9
+ _objc_retain_x4
CStrings:
+ "AXInvertColorsManager.trailingStatusChange"
+ "AXInvertColors_CoverSheet.backgroundStyleDebounce"
+ "AXWakeEffectToken"
+ "B16@?0#8"
+ "BackgroundStyleDebounceTimer"
+ "CoverSheet: non-dark backgroundStyle %ld observed, debouncing before un-ignoring invert colors"
+ "CoverSheet: wake effect layer %@, dark mode: %d, invert: %d"
+ "FBScene"
+ "FBSceneClientHandle"
+ "IC status change too soon, deferring"
+ "PBUIPosterFloatingLayerReplica"
+ "PBUIPosterWallpaperRemoteViewController appeared, re-evaluating dark window invert for %@"
+ "SBFLegacyWallpaperWakeAnimatorInvertColorsAccessibility"
+ "SBHomeScreenWindow"
+ "SBStatusBarWindow"
+ "SBTraitsOrientedContentViewControllerView"
+ "SBTraitsSingleSceneWindow"
+ "SBTraitsSingleSceneWindow: hosting Siri AI, no dark mode window filter: %@"
+ "SBTraitsSingleSceneWindowInvertColorsAccessibility"
+ "WakeAnimator: %{public}@ invert on %lu floating layer replica(s)"
+ "_UIScenePresentationView"
+ "__SBFLegacyWallpaperWakeAnimatorInvertColorsAccessibility_super"
+ "__SBTraitsSingleSceneWindowInvertColorsAccessibility_super"
+ "_accessibilityApplyBackgroundIsDark:toView:invertEnabled:"
+ "_accessibilityApplyFloatingLayerInvert:"
+ "_accessibilitySetUnsignedIntegerValue:forKey:"
+ "_accessibilityUnsignedIntegerValueForKey:"
+ "_axHostsSiriAIScene"
+ "_isSecure"
+ "_isSpringBoardHomeScreenWindow:"
+ "_scene"
+ "afterDelay:processBlock:"
+ "applying"
+ "cancel"
+ "clientHandle"
+ "com.apple.campo"
+ "connectedScenes"
+ "initWithTargetSerialQueue:"
+ "removing"
+ "setLabel:"
+ "toggleSpringBoardHomeScreenWindowInvert Apply window: %@"
+ "toggleSpringBoardHomeScreenWindowInvert Remove window: %@"
+ "toggleSpringBoardHomeScreenWindowInvert:"
+ "updateWakeEffectsForWake:animated:completion:"
+ "v32@0:8B16@20B28"
+ "v32@0:8B16B20@?24"
+ "windows"
- "Ignoring IC status change: too soon"
- "_screenWakeAnimationController"
- "target"
```
