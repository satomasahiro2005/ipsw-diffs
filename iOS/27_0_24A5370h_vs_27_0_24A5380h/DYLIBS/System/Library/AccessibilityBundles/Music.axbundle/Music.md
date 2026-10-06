## Music

> `/System/Library/AccessibilityBundles/Music.axbundle/Music`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__objc_data` | `—` | `0x19f0` | **`+0x19f0`** |
| `__AUTH.__objc_data` | `0x1bd0` | `0x280` | **`-0x1950`** |
| `__TEXT.__text` | `0xbedc` | `0xc458` | **`+0x57c`** |
| `__AUTH_CONST.__objc_const` | `0x3250` | `0x3370` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x1284` | `0x131c` | **`+0x98`** |
| `__DATA_CONST.__objc_selrefs` | `0x7c8` | `0x810` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x3620` | `0x3660` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x498` | `0x4c8` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2998` | `0x29b8` | **`+0x20`** |
| `__DATA.__bss` | `0x28` | `0x18` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1b0` | `0x1c0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2c8` | `0x2d8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `—` | `0x10` | **`+0x10`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 385
-  Symbols:   1011
-  CStrings:  484
+  Functions: 398
+  Symbols:   1039
+  CStrings:  485
Symbols:
+ +[SingIndicatorViewAccessibility _accessibilityPerformValidations:]
+ +[SingIndicatorViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[SingIndicatorViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[AudioTraitButtonAccessibility accessibilityFrame]
+ -[NowPlayingTrackTitleStackViewAccessibility _axActionableSubtitleButton]
+ -[NowPlayingTrackTitleStackViewAccessibility accessibilityActivate]
+ -[NowPlayingTrackTitleStackViewAccessibility accessibilityTraits]
+ -[SingIndicatorViewAccessibility accessibilityLabel]
+ -[SingIndicatorViewAccessibility accessibilityTraits]
+ -[SingIndicatorViewAccessibility didMoveToSuperview]
+ -[SingIndicatorViewAccessibility isAccessibilityElement]
+ GCC_except_table120
+ GCC_except_table151
+ GCC_except_table220
+ GCC_except_table228
+ GCC_except_table278
+ _CGRectGetHeight
+ _CGRectGetWidth
+ _OBJC_CLASS_$_SingIndicatorViewAccessibility
+ _OBJC_CLASS_$___SingIndicatorViewAccessibility_super
+ _OBJC_METACLASS_$_SingIndicatorViewAccessibility
+ _OBJC_METACLASS_$___SingIndicatorViewAccessibility_super
+ _UIAccessibilityFrameForBounds
+ _UIAccessibilityTraitPopupButton
+ _UIAccessibilityTraitStaticText
+ __OBJC_$_CLASS_METHODS_SingIndicatorViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_SingIndicatorViewAccessibility
+ __OBJC_CLASS_RO_$_SingIndicatorViewAccessibility
+ __OBJC_CLASS_RO_$___SingIndicatorViewAccessibility_super
+ __OBJC_METACLASS_RO_$_SingIndicatorViewAccessibility
+ __OBJC_METACLASS_RO_$___SingIndicatorViewAccessibility_super
+ ___67-[NowPlayingTrackTitleStackViewAccessibility accessibilityActivate]_block_invoke
+ ___73-[NowPlayingTrackTitleStackViewAccessibility _axActionableSubtitleButton]_block_invoke
- GCC_except_table108
- GCC_except_table139
- GCC_except_table208
- GCC_except_table216
- GCC_except_table265
CStrings:
+ "MPModelPlaylistEntryReaction"
+ "Music.SingIndicatorView"
+ "SingIndicatorViewAccessibility"
+ "accountBarButtonItem"
+ "reactionText"
+ "singIndicatorLabel"
- "AccountButtonWrapper"
- "Music.NowPlayingLyricsViewController"
- "MusicCoreUI.Reactions"
- "accountButton"
- "cardHeight"
```
