## Maps

> `/System/Library/Assistant/UIPlugins/Maps.siriUIBundle/Maps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x174b0` | `0x17760` | **`+0x2b0`** |
| `__TEXT.__cstring` | `0x925c` | `0x9360` | **`+0x104`** |
| `__DATA_CONST.__cfstring` | `0x7900` | `0x79c0` | **`+0xc0`** |
| `__TEXT.__text` | `0x10b64` | `0x10bc0` | **`+0x5c`** |
| `__TEXT.__unwind_info` | `0x498` | `0x4a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2966.30.5.15.8
+2970.30.6.5.7

-  Functions: 1279
-  Symbols:   1181
-  CStrings:  2335
+  Functions: 1286
+  Symbols:   1187
+  CStrings:  2342
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
