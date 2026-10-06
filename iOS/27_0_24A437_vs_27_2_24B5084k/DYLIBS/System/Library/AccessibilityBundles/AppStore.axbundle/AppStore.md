## AppStore

> `/System/Library/AccessibilityBundles/AppStore.axbundle/AppStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x386d` | `0x3927` | **`+0xba`** |
| `__TEXT.__text` | `0xb9dc` | `0xba80` | **`+0xa4`** |
| `__AUTH_CONST.__cfstring` | `0x39c0` | `0x3a40` | **`+0x80`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  CStrings:  508
+  CStrings:  515
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 268 -> 360
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 440 -> 512
CStrings:
+ "AppStore.EditorialMediaContainerView"
+ "AppStore.EditorialVideoView"
+ "AppStore.TodayCardEditorialMediaContainerView"
+ "EditorialMediaContainerView"
+ "Optional<EditorialMediaView>"
+ "Optional<MuteButton>"
+ "TodayCardEditorialMediaContainerView"
+ "container"
+ "mediaContainer"
+ "mediaView"
+ "muteButton"
- "AppStore.StoryCardMediaView"
- "StoryCardMediaView"
- "editorialVideoView"
- "mediaBackgroundView"
```
