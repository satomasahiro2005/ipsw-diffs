## BridgeStoreExtension

> `/System/Library/AccessibilityBundles/BridgeStoreExtension.axbundle/BridgeStoreExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaec0` | `0xaf24` | **`+0x64`** |
| `__TEXT.__cstring` | `0x3c99` | `0x3ce3` | **`+0x4a`** |
| `__AUTH_CONST.__cfstring` | `0x38c0` | `0x3900` | **`+0x40`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  CStrings:  498
+  CStrings:  501
Functions:
~ +[StoryCardCollectionViewCellAccessibility _accessibilityPerformValidations:] : 332 -> 360
~ -[StoryCardCollectionViewCellAccessibility accessibilityElements] : 440 -> 512
CStrings:
+ "BridgeStoreExtension.EditorialMediaContainerView"
+ "BridgeStoreExtension.TodayCardEditorialMediaContainerView"
+ "EditorialMediaContainerView"
+ "Optional<EditorialMediaView>"
+ "Optional<MuteButton>"
+ "TodayCardEditorialMediaContainerView"
+ "container"
+ "mediaContainer"
+ "mediaView"
+ "muteButton"
- "BridgeStoreExtension.StoryCardMediaView"
- "BridgeStoreExtension.TodayCardEditorialVideoView"
- "EditorialVideoView"
- "StoryCardMediaView"
- "TodayCardEditorialVideoView"
- "editorialVideoView"
- "mediaBackgroundView"
```
