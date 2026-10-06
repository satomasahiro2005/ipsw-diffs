## Maps

> `/System/Library/Assistant/Plugins/Maps.assistantBundle/Maps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x17e60` | `0x18068` | **`+0x208`** |
| `__TEXT.__cstring` | `0x9df5` | `0x9ec6` | **`+0xd1`** |
| `__DATA_CONST.__cfstring` | `0x8360` | `0x8400` | **`+0xa0`** |
| `__TEXT.__text` | `0x144dc` | `0x14518` | **`+0x3c`** |
| `__DATA_CONST.__objc_intobj` | `0x810` | `0x828` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2972.30.6.12.32
+2972.30.6.12.54

-  Functions: 1332
-  Symbols:   1289
-  CStrings:  1969
+  Functions: 1337
+  Symbols:   1294
+  CStrings:  1974
Symbols:
+ _MapsConfig_ChromeWindowDragRegionEstimatedHeight
+ _MapsConfig_ContainerEnableLargeDetentForFullHeightCards
+ _MapsConfig_CustomPOIControllerPrefersEnrichedItemOverOthers
+ _MapsConfig_EnableEnhancedExternalDisplaySupport
+ _MapsConfig_EnableSecondScreenNavigationDisplay
+ _MapsConfig_PlaceCardContextSuppressCurrentLocationMarkerInjection
- _MapsConfig_DescriptorResolutionAdressForNameWorkaroundEnabled
CStrings:
+ "ChromeWindowDragRegionEstimatedHeight"
+ "ContainerEnableLargeDetentForFullHeightCards"
+ "CustomPOIControllerPrefersEnrichedItemOverOthers"
+ "EnableEnhancedExternalDisplaySupport"
+ "EnableSecondScreenNavigationDisplay"
+ "PlaceCardContextSuppressCurrentLocationMarkerInjection"
- "DescriptorResolutionAdressForNameWorkaroundEnabled"
```
