## ASMessagesProvider

> `/System/Library/AccessibilityBundles/ASMessagesProvider.axbundle/ASMessagesProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3c7b` | `0x3cbd` | **`+0x42`** |
| `__TEXT.__text` | `0xb424` | `0xb45c` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x3940` | `0x3960` | **`+0x20`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  CStrings:  503
+  CStrings:  505
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 300 -> 332
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 416 -> 440
CStrings:
+ "ASMessagesProvider.EditorialVideoView"
+ "ASMessagesProvider.TodayCardEditorialVideoView"
+ "EditorialVideoView"
+ "Optional<VideoView>"
+ "TodayCardEditorialVideoView"
+ "editorialVideoView"
- "ASMessagesProvider.RevealingVideoView"
- "Optional<TodayCardVideoView>"
- "RevealingVideoView"
- "revealingVideoView"
```
