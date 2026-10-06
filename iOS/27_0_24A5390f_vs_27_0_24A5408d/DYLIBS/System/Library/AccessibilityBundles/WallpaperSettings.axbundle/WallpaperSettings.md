## WallpaperSettings

> `/System/Library/AccessibilityBundles/WallpaperSettings.axbundle/WallpaperSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x3e` | `0x3be` | **`+0x380`** |
| `__TEXT.__text` | `0x18d8` | `0x1c44` | **`+0x36c`** |
| `__TEXT.__const` | `0x20` | `0x38` | **`+0x18`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Symbols:   134
-  CStrings:  212
+  Symbols:   136
+  CStrings:  219
Symbols:
+ _AXAIWhiteGloveLoggingEnabled
+ __os_log_error_impl
+ _objc_retain_x24
- _objc_retain_x19
Functions:
~ _AXWallpaperLabel : 848 -> 1176
~ -[SwiftUIAccessibilityNode__WallpaperSettings__SwiftUI _axWallpaperDescription] : 524 -> 776
~ -[SwiftUIAccessibilityNode__WallpaperSettings__SwiftUI accessibilityLabel] : 332 -> 628
CStrings:
+ "rdar://168563356 AXWallpaperLabel called with nil filename, returning nil"
+ "rdar://168563356 AXWallpaperLabel return-localized rawFilename=%{public}@ stripped=%{public}@ key=%{public}@ axDesc=%{public}@"
+ "rdar://168563356 AXWallpaperLabel return-raw-filename rawFilename=%{public}@ stripped=%{public}@ key=%{public}@ (no localized string found)"
+ "rdar://168563356 WallpaperSwiftUIAccessibilityNode _axWallpaperDescription enter identifier=%{public}@ superLabel=%{public}@"
+ "rdar://168563356 WallpaperSwiftUIAccessibilityNode _axWallpaperDescription return identifier=%{public}@ wallpaper=%{public}@"
+ "rdar://168563356 WallpaperSwiftUIAccessibilityNode accessibilityLabel enter identifier=%{public}@ superLabel=%{public}@ traits=%lu"
+ "rdar://168563356 WallpaperSwiftUIAccessibilityNode accessibilityLabel return identifier=%{public}@ label=%{public}@ (axWallpaperDescription=%{public}@ superLabel=%{public}@)"
```
