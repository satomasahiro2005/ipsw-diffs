## MobileSlideShowSettings

> `/System/Library/PreferenceBundles/MobileSlideShowSettings.bundle/MobileSlideShowSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c650` | `0x1c484` | **`-0x1cc`** |
| `__TEXT.__cstring` | `0x3457` | `0x33c8` | **`-0x8f`** |
| `__DATA_CONST.__cfstring` | `0x2d00` | `0x2ca0` | **`-0x60`** |
| `__TEXT.__objc_methname` | `0x48dc` | `0x488c` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x708` | `0x740` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0xe00` | `0xdd0` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x13f8` | `0x13d0` | **`-0x28`** |
| `__DATA.__objc_selrefs` | `0x1480` | `0x1468` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x710` | `0x6f8` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x740` | `0x738` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 502
-  Symbols:   445
-  CStrings:  1351
+  Functions: 498
+  Symbols:   442
+  CStrings:  1345
Symbols:
+ _PXSharedAlbumsSettingsLearnMoreString
+ _PXSharedAlbumsSettingsLearnMoreURL
- _NSLog
- _PXPreferencesSetShowSharedAlbumsActivityInAppNotifications
- _PXPreferencesShowSharedAlbumsActivityInAppNotifications
- _PXSharedAlbumsLearnMoreString
- _PXSharedAlbumsLearnMoreURL
CStrings:
+ "ARCHIVED_SHARED_ALBUMS_FOOTER_DESCRIPTION"
+ "SHARED_ALBUMS_FOOTER_DESCRIPTION"
+ "reloadWallpaperSuggestions:forceImmediate:reply:"
- "Failed to open Shared Albums Learn More URL %@: %@"
- "SHARED_ALBUMS_ACTIVITY_NOTIFICATIONS_FOOTER"
- "SHARED_ALBUMS_ACTIVITY_NOTIFICATIONS_SWITCH"
- "SharedAlbumsActivityNotificationsGroup"
- "SharedAlbumsActivityNotificationsSwitch"
- "_activityNotificationsEnabled:"
- "_didTapLearnMoreLink:"
- "_setActivityNotifications:specifier:"
- "reloadWallpaperSuggestions:reply:"
```
