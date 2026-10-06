## AppInstallExtension

> `/System/Library/AccessibilityBundles/AppInstallExtension.axbundle/AppInstallExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3d65` | `0x3da8` | **`+0x43`** |
| `__TEXT.__text` | `0xb488` | `0xb4c0` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x39c0` | `0x39e0` | **`+0x20`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  CStrings:  505
+  CStrings:  507
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 300 -> 332
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 416 -> 440
CStrings:
+ "AppInstallExtension.EditorialVideoView"
+ "AppInstallExtension.TodayCardEditorialVideoView"
+ "EditorialVideoView"
+ "Optional<VideoView>"
+ "TodayCardEditorialVideoView"
+ "editorialVideoView"
- "AppInstallExtension.RevealingVideoView"
- "Optional<TodayCardVideoView>"
- "RevealingVideoView"
- "revealingVideoView"
```
