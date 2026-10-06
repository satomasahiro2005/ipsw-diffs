## CarPlayUIServices

> `/System/Library/PrivateFrameworks/CarPlayUIServices.framework/CarPlayUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38d18` | `0x38e4c` | **`+0x134`** |
| `__TEXT.__oslogstring` | `0x1778` | `0x1818` | **`+0xa0`** |
| `__TEXT.__const` | `0xe94` | `0xea4` | **`+0x10`** |

### Other Changes

```diff

-577.2.0.0.0
+580.0.0.0.0

-  CStrings:  395
+  CStrings:  397
Functions:
~ -[CRSUIWallpaperPreferences setVehicle:] : 476 -> 600
~ -[CRSUIWallpaperPreferences setCurrentWallpaper:requiresDarkAppearanceHandler:] : 840 -> 1024
CStrings:
+ "[CRSUIWallpaperPreferences] -setCurrentWallpaper: vehicle=%p displayID=%{public}@ dataProvider=%p"
+ "[CRSUIWallpaperPreferences] -setVehicle: %p -> %p (self=%p)"
```
