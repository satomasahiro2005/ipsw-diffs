## InvertColorsManager

> `/System/Library/AccessibilityBundles/InvertColorsManager.bundle/InvertColorsManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20898` | `0x20b20` | **`+0x288`** |
| `__TEXT.__oslogstring` | `0xb76` | `0xdb4` | **`+0x23e`** |
| `__TEXT.__unwind_info` | `0xf60` | `0xf70` | **`+0x10`** |
| `__TEXT.__const` | `0xc8` | `0xd0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  CStrings:  2137
+  CStrings:  2142
Functions:
~ sub_11d68 : 116 -> 308
~ sub_11ddc -> sub_11e9c : 116 -> 212
~ sub_193ec -> sub_1950c : 116 -> 264
~ sub_19460 -> sub_19614 : 180 -> 392
CStrings:
+ "CAMSecureWindow: isInHostedDarkWindow=YES window=%@"
+ "CAMSecureWindow: locked + dark — opting OUT of own window-level dark invert, deferring to SB counter-invert. window=%@"
+ "CAMSecureWindow: supportsDarkWindowInvert=YES (screenLocked=%d darkModeActive=%d) window=%@"
+ "SBDeviceApplicationSceneView: _accessibilityLoadInvertColors shouldCounter=%d window=%@ windowClass=%@ invertColorsEnabled=%d isDarkWindow=%d supportsDarkWindowInvert=%d sceneView=%@"
+ "SBDeviceApplicationSceneView: _axShouldCounterCoverSheetDarkWindowInvert=%d globalSmartInvertDrivesDisplayFilter=%d window=%@"
```
