## AppStore

> `/System/Library/AccessibilityBundles/AppStore.axbundle/AppStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3972` | `0x39aa` | **`+0x38`** |
| `__TEXT.__text` | `0xbe18` | `0xbe50` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x3aa0` | `0x3ac0` | **`+0x20`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  CStrings:  516
+  CStrings:  518
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 300 -> 332
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 416 -> 440
CStrings:
+ "AppStore.EditorialVideoView"
+ "AppStore.TodayCardEditorialVideoView"
+ "EditorialVideoView"
+ "Optional<VideoView>"
+ "TodayCardEditorialVideoView"
+ "editorialVideoView"
- "AppStore.RevealingVideoView"
- "Optional<TodayCardVideoView>"
- "RevealingVideoView"
- "revealingVideoView"
```
