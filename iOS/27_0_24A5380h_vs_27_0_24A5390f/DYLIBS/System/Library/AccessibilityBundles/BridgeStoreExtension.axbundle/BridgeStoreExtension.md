## BridgeStoreExtension

> `/System/Library/AccessibilityBundles/BridgeStoreExtension.axbundle/BridgeStoreExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3de6` | `0x3e2a` | **`+0x44`** |
| `__TEXT.__text` | `0xb4a4` | `0xb4dc` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x39e0` | `0x3a00` | **`+0x20`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  CStrings:  506
+  CStrings:  508
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 300 -> 332
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 416 -> 440
CStrings:
+ "BridgeStoreExtension.EditorialVideoView"
+ "BridgeStoreExtension.TodayCardEditorialVideoView"
+ "EditorialVideoView"
+ "Optional<VideoView>"
+ "TodayCardEditorialVideoView"
+ "editorialVideoView"
- "BridgeStoreExtension.RevealingVideoView"
- "Optional<TodayCardVideoView>"
- "RevealingVideoView"
- "revealingVideoView"
```
