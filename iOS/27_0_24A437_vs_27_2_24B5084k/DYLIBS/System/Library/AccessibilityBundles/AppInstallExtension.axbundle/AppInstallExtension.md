## AppInstallExtension

> `/System/Library/AccessibilityBundles/AppInstallExtension.axbundle/AppInstallExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaea4` | `0xaf08` | **`+0x64`** |
| `__TEXT.__cstring` | `0x3c1a` | `0x3c64` | **`+0x4a`** |
| `__AUTH_CONST.__cfstring` | `0x38a0` | `0x38e0` | **`+0x40`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  CStrings:  497
+  CStrings:  500
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 332 -> 360
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 440 -> 512
CStrings:
+ "AppInstallExtension.EditorialMediaContainerView"
+ "AppInstallExtension.TodayCardEditorialMediaContainerView"
+ "EditorialMediaContainerView"
+ "Optional<EditorialMediaView>"
+ "Optional<MuteButton>"
+ "TodayCardEditorialMediaContainerView"
+ "container"
+ "mediaContainer"
+ "mediaView"
+ "muteButton"
- "AppInstallExtension.StoryCardMediaView"
- "AppInstallExtension.TodayCardEditorialVideoView"
- "EditorialVideoView"
- "StoryCardMediaView"
- "TodayCardEditorialVideoView"
- "editorialVideoView"
- "mediaBackgroundView"
```
