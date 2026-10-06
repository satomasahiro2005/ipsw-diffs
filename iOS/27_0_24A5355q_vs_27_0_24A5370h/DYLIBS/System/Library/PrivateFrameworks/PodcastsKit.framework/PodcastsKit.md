## PodcastsKit

> `/System/Library/PrivateFrameworks/PodcastsKit.framework/PodcastsKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a680` | `0x2a614` | **`-0x6c`** |
| `__AUTH_CONST.__cfstring` | `0x1200` | `0x11e0` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x2644` | `0x262c` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x6b0` | `0x6a0` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c38` | `0x1c30` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xd20` | `0xd18` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-4027.100.59.0.0
+4027.100.70.0.0

-  Functions: 1303
-  Symbols:   1839
-  CStrings:  291
+  Functions: 1302
+  Symbols:   1835
+  CStrings:  290
Symbols:
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_MTPodcastPlaylistSettings_$_DB
+ __OBJC_$_CATEGORY_MTPodcastPlaylistSettings_$_DB
- +[MTPodcastPlaylistSettings(NSPredicate) predicateForPlaylistSettingsUuid:]
- __OBJC_$_CATEGORY_CLASS_METHODS_MTPodcastPlaylistSettings_$_NSPredicate
- __OBJC_$_CATEGORY_MTPodcastPlaylistSettings_$_NSPredicate
- __OBJC_$_INSTANCE_METHODS_MTPodcastPlaylistSettings(NSPredicate|DB)
- _kEpisodeCleanedTitle
- _kPlaylistSettingUuid
CStrings:
- "%K = %@"
```
