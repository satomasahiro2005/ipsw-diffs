## MusicApplication

> `/System/Library/AccessibilityBundles/MusicApplication.axbundle/MusicApplication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4415` | `0x43ee` | **`-0x27`** |
| `__AUTH_CONST.__cfstring` | `0x4f80` | `0x4f60` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8c0` | `0x8b8` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  CStrings:  685
+  CStrings:  684
Functions:
~ +[ReactionsButtonAccessibility _accessibilityPerformValidations:] : 132 -> 172
~ -[ReactionsButtonAccessibility accessibilityValue] : 228 -> 240
~ +[MusicApplicationUIScrollViewAccessibility _accessibilityPerformValidations:] : 204 -> 152
CStrings:
+ "MPModelPlaylistEntryReaction"
+ "reactionText"
- "MusicApplication.NowPlayingLyricsViewController"
- "MusicCoreUI.Reactions"
- "cardHeight"
```
