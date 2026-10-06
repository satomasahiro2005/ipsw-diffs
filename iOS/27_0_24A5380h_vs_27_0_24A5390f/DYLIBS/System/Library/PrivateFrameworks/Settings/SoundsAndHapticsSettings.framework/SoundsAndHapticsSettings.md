## SoundsAndHapticsSettings

> `/System/Library/PrivateFrameworks/Settings/SoundsAndHapticsSettings.framework/SoundsAndHapticsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2392c` | `0x23ad4` | **`+0x1a8`** |
| `__TEXT.__oslogstring` | `0x11c1` | `0x11f0` | **`+0x2f`** |
| `__AUTH_CONST.__objc_const` | `0x2a00` | `0x2a20` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x184` | `0x188` | **`+0x4`** |

### Other Changes

```diff

-2027.0.1.100.0
+2027.0.3.0.0

-  Symbols:   1441
-  CStrings:  458
+  Symbols:   1442
+  CStrings:  459
Symbols:
+ _OBJC_IVAR_$_SHSSoundsPrefController._viewIsDisappearing
Functions:
~ -[SHSSoundsPrefController willForeground] : 56 -> 164
~ -[SHSSoundsPrefController viewWillAppear:] : 488 -> 504
~ -[SHSSoundsPrefController viewDidAppear:] : 164 -> 180
~ -[SHSSoundsPrefController viewWillDisappear:] : 468 -> 488
~ -[SHSSoundsPrefController startVolumePreviewForAlertType:] : 484 -> 600
~ -[SHSSoundsPrefController startSystemSoundVolumePreview] : 444 -> 560
~ -[SHSSoundsPrefController alertSliderTouchBegan:] : 216 -> 232
~ -[SHSSoundsPrefController alarmSliderTouchBegan:] : 228 -> 244
CStrings:
+ "%s: View is disappearing, suppressing preview."
```
