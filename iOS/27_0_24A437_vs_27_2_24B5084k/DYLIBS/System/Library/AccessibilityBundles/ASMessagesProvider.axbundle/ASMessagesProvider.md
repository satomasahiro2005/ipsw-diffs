## ASMessagesProvider

> `/System/Library/AccessibilityBundles/ASMessagesProvider.axbundle/ASMessagesProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae40` | `0xaea4` | **`+0x64`** |
| `__TEXT.__cstring` | `0x3b32` | `0x3b7c` | **`+0x4a`** |
| `__AUTH_CONST.__cfstring` | `0x3820` | `0x3860` | **`+0x40`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  CStrings:  495
+  CStrings:  498
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 332 -> 360
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 440 -> 512
CStrings:
+ "ASMessagesProvider.EditorialMediaContainerView"
+ "ASMessagesProvider.TodayCardEditorialMediaContainerView"
+ "EditorialMediaContainerView"
+ "Optional<EditorialMediaView>"
+ "Optional<MuteButton>"
+ "TodayCardEditorialMediaContainerView"
+ "container"
+ "mediaContainer"
+ "mediaView"
+ "muteButton"
- "ASMessagesProvider.StoryCardMediaView"
- "ASMessagesProvider.TodayCardEditorialVideoView"
- "EditorialVideoView"
- "StoryCardMediaView"
- "TodayCardEditorialVideoView"
- "editorialVideoView"
- "mediaBackgroundView"
```
