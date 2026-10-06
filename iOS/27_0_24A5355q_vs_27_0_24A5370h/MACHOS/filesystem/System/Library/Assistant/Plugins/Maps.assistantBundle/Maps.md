## Maps

> `/System/Library/Assistant/Plugins/Maps.assistantBundle/Maps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x179a8` | `0x17c58` | **`+0x2b0`** |
| `__TEXT.__cstring` | `0x9c66` | `0x9d6a` | **`+0x104`** |
| `__DATA_CONST.__cfstring` | `0x8200` | `0x82c0` | **`+0xc0`** |
| `__TEXT.__text` | `0x1440c` | `0x144a0` | **`+0x94`** |
| `__TEXT.__unwind_info` | `0x530` | `0x540` | **`+0x10`** |
| `__TEXT.__const` | `0xe8` | `0xf0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2966.30.5.15.8
+2970.30.6.5.7

-  Functions: 1320
-  Symbols:   1278
-  CStrings:  1957
+  Functions: 1327
+  Symbols:   1284
+  CStrings:  1964
Symbols:
+ _MapsConfig_ContaineeNavigationHeaderEnabled
+ _MapsConfig_ContainerForceRegularGlassInLargeSheets
+ _MapsConfig_ContainerForceRegularGlassInNonLargeSheets
+ _MapsConfig_ContainerUseMapsSignInLargeSheets
+ _MapsConfig_NavigationAutoLaunchDefaultDelay
+ _MapsConfig_POIBusynessLocationTimer
+ _MapsConfig_PlaceCardContextClampToCurrentZoomForIsolatedMarkers
+ _MapsConfig_StartNavigationIntentTimeoutDuration
- _MapsConfig_ContainerUseThickMaterialInLargeSheets
- _MapsConfig_RoutePlanningRefreshEnabled
CStrings:
+ "@\"NSNumber\"16@?0@\"NSNumber\"8"
+ "ContaineeNavigationHeaderEnabled"
+ "ContainerForceRegularGlassInLargeSheets"
+ "ContainerForceRegularGlassInNonLargeSheets"
+ "ContainerUseMapsSignInLargeSheets"
+ "NavigationAutoLaunchDefaultDelay"
+ "POIBusynessLocationTimer"
+ "PlaceCardContextClampToCurrentZoomForIsolatedMarkers"
+ "StartNavigationIntentTimeoutDuration"
- "ContainerUseThickMaterialInLargeSheets"
- "RoutePlanningRefreshEnabled"
```
