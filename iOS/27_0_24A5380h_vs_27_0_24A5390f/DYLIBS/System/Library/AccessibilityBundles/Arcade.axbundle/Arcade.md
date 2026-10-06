## Arcade

> `/System/Library/AccessibilityBundles/Arcade.axbundle/Arcade`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa864` | `0xa89c` | **`+0x38`** |
| `__TEXT.__cstring` | `0x36a5` | `0x36db` | **`+0x36`** |
| `__AUTH_CONST.__cfstring` | `0x3960` | `0x3980` | **`+0x20`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  CStrings:  494
+  CStrings:  496
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 300 -> 332
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 416 -> 440
CStrings:
+ "Arcade.EditorialVideoView"
+ "Arcade.TodayCardEditorialVideoView"
+ "EditorialVideoView"
+ "Optional<VideoView>"
+ "TodayCardEditorialVideoView"
+ "editorialVideoView"
- "Arcade.RevealingVideoView"
- "Optional<TodayCardVideoView>"
- "RevealingVideoView"
- "revealingVideoView"
```
