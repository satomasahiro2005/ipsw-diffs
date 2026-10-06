## ProductPageExtension

> `/System/Library/AccessibilityBundles/ProductPageExtension.axbundle/ProductPageExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3e39` | `0x3e7d` | **`+0x44`** |
| `__TEXT.__text` | `0xb53c` | `0xb574` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x39e0` | `0x3a00` | **`+0x20`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  CStrings:  508
+  CStrings:  510
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 300 -> 332
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 416 -> 440
CStrings:
+ "EditorialVideoView"
+ "Optional<VideoView>"
+ "ProductPageExtension.EditorialVideoView"
+ "ProductPageExtension.TodayCardEditorialVideoView"
+ "TodayCardEditorialVideoView"
+ "editorialVideoView"
- "Optional<TodayCardVideoView>"
- "ProductPageExtension.RevealingVideoView"
- "RevealingVideoView"
- "revealingVideoView"
```
