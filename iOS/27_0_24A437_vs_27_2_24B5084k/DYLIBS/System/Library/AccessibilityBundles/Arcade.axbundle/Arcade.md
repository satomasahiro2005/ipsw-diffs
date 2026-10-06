## Arcade

> `/System/Library/AccessibilityBundles/Arcade.axbundle/Arcade`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa374` | `0xa3d8` | **`+0x64`** |
| `__TEXT.__cstring` | `0x3574` | `0x35be` | **`+0x4a`** |
| `__AUTH_CONST.__cfstring` | `0x3840` | `0x3880` | **`+0x40`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  CStrings:  486
+  CStrings:  489
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 332 -> 360
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 440 -> 512
CStrings:
+ "Arcade.EditorialMediaContainerView"
+ "Arcade.TodayCardEditorialMediaContainerView"
+ "EditorialMediaContainerView"
+ "Optional<EditorialMediaView>"
+ "Optional<MuteButton>"
+ "TodayCardEditorialMediaContainerView"
+ "container"
+ "mediaContainer"
+ "mediaView"
+ "muteButton"
- "Arcade.StoryCardMediaView"
- "Arcade.TodayCardEditorialVideoView"
- "EditorialVideoView"
- "StoryCardMediaView"
- "TodayCardEditorialVideoView"
- "editorialVideoView"
- "mediaBackgroundView"
```
