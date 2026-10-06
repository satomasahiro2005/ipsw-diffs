## ProductPageExtension

> `/System/Library/AccessibilityBundles/ProductPageExtension.axbundle/ProductPageExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaf58` | `0xafbc` | **`+0x64`** |
| `__TEXT.__cstring` | `0x3cec` | `0x3d36` | **`+0x4a`** |
| `__AUTH_CONST.__cfstring` | `0x38c0` | `0x3900` | **`+0x40`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  CStrings:  500
+  CStrings:  503
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 332 -> 360
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 440 -> 512
CStrings:
+ "EditorialMediaContainerView"
+ "Optional<EditorialMediaView>"
+ "Optional<MuteButton>"
+ "ProductPageExtension.EditorialMediaContainerView"
+ "ProductPageExtension.TodayCardEditorialMediaContainerView"
+ "TodayCardEditorialMediaContainerView"
+ "container"
+ "mediaContainer"
+ "mediaView"
+ "muteButton"
- "EditorialVideoView"
- "ProductPageExtension.StoryCardMediaView"
- "ProductPageExtension.TodayCardEditorialVideoView"
- "StoryCardMediaView"
- "TodayCardEditorialVideoView"
- "editorialVideoView"
- "mediaBackgroundView"
```
