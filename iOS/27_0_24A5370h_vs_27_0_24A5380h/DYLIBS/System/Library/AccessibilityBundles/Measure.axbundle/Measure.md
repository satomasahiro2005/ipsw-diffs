## Measure

> `/System/Library/AccessibilityBundles/Measure.axbundle/Measure`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x15a0` | `0x1580` | **`-0x20`** |
| `__TEXT.__text` | `0x6228` | `0x6210` | **`-0x18`** |
| `__TEXT.__cstring` | `0xe83` | `0xe76` | **`-0xd`** |
| `__DATA.__bss` | `0x24` | `0x2c` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x590` | `0x598` | **`+0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Symbols:   689
-  CStrings:  193
+  Symbols:   690
+  CStrings:  192
Symbols:
+ -[LevelPageViewControllerAccessibility _axAnnounceOrientationChangeIfNeeded:]
+ -[LevelPageViewControllerAccessibility updateDisplay:]
+ __axAnnounceOrientationChangeIfNeeded:.LastAnnouncedOrientation
- -[LevelPageViewControllerAccessibility _updateForRotation:shiftAngle:]
- -[LevelPageViewControllerAccessibility _updateOffsetLabel:]
Functions:
~ -[AccessibilityStateObserverAccessibility axDescriptionForNumberOfPointsAndLines] : 1012 -> 1032
~ +[LevelPageViewControllerAccessibility _accessibilityPerformValidations:] : 328 -> 296
~ -[LevelPageViewControllerAccessibility _accessibilityLoadAccessibilityInformation] -> -[LevelPageViewControllerAccessibility _axAnnounceOrientationChangeIfNeeded:] : 256 -> 168
~ -[LevelPageViewControllerAccessibility viewDidLoad] -> -[LevelPageViewControllerAccessibility _accessibilityLoadAccessibilityInformation] : 76 -> 256
~ -[LevelPageViewControllerAccessibility _updateOffsetLabel:] -> -[LevelPageViewControllerAccessibility viewWillDisappear:] : 92 -> 76
~ -[LevelPageViewControllerAccessibility _updateForRotation:shiftAngle:] -> -[LevelPageViewControllerAccessibility updateDisplay:] : 232 -> 144
CStrings:
+ "Optional<LevelViewProtocol>"
+ "lastDisplayDegrees"
+ "updateDisplay:"
- "LevelView"
- "_orientation"
- "_updateForRotation: shiftAngle:"
- "_updateOffsetLabel:"
```
