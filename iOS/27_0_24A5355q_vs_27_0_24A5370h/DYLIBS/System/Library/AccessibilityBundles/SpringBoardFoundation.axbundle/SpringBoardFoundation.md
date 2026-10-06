## SpringBoardFoundation

> `/System/Library/AccessibilityBundles/SpringBoardFoundation.axbundle/SpringBoardFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x306c` | `0x2fbc` | **`-0xb0`** |
| `__AUTH_CONST.__cfstring` | `0xc80` | `0xc40` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x300` | `0x308` | **`+0x8`** |
| `__TEXT.__cstring` | `0x9bb` | `0x9c3` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x32c` | `0x334` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 99
-  Symbols:   269
-  CStrings:  111
+  Functions: 100
+  Symbols:   270
+  CStrings:  109
Symbols:
+ -[SBFLockScreenDateSubtitleDateViewAccessibility _axProminentSubtitleDateText]
+ GCC_except_table65
+ GCC_except_table92
+ GCC_except_table96
- GCC_except_table64
- GCC_except_table91
- GCC_except_table95
Functions:
~ +[SBFLockScreenDateSubtitleDateViewAccessibility _accessibilityPerformValidations:] : 212 -> 180
~ -[SBFLockScreenDateSubtitleDateViewAccessibility accessibilityLabel] : 248 -> 176
~ -[SBFLockScreenDateSubtitleDateViewAccessibility accessibilityFrame] : 224 -> 16
+ -[SBFLockScreenDateSubtitleDateViewAccessibility _axProminentSubtitleDateText]
~ -[SBFLockScreenDateViewAccessibility _axElements:] : 1036 -> 1032
~ _AXSBMainDisplayWindowScene : 312 -> 308
~ _AXSBContinuityDisplayWindowScene : 312 -> 308
CStrings:
+ "prominentDisplayViewController"
+ "prominentDisplayViewController.view.subtitleView.textLabel"
- "SBFLockScreenAlternateDateLabel"
- "alternateDateLabel"
- "alternateDateLabel.label"
- "label"
```
