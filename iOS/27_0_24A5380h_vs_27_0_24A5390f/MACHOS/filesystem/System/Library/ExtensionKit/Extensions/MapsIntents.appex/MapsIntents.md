## MapsIntents

> `/System/Library/ExtensionKit/Extensions/MapsIntents.appex/MapsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x537c8` | `0x560c0` | **`+0x28f8`** |
| `__TEXT.__swift5_typeref` | `0x23c8` | `0x2a4e` | **`+0x686`** |
| `__TEXT.__objc_stubs` | `0x1140` | `0x12a0` | **`+0x160`** |
| `__TEXT.__eh_frame` | `0x27a0` | `0x28f8` | **`+0x158`** |
| `__TEXT.__objc_methname` | `0x49df` | `0x4abe` | **`+0xdf`** |
| `__DATA.__data` | `0x1bf8` | `0x1cc8` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x1c95` | `0x1d65` | **`+0xd0`** |
| `__TEXT.__const` | `0x4df4` | `0x4eb4` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x1ba0` | `0x1c40` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0xd70` | `0xdc8` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0x10fc` | `0x114e` | **`+0x52`** |
| `__DATA_CONST.__auth_got` | `0xdd8` | `0xe28` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x1ca8` | `0x1cf8` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x195b` | `0x19ab` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x540` | `0x578` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1510` | `0x1538` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x9e8` | `0xa0c` | **`+0x24`** |
| `__DATA_CONST.__auth_ptr` | `0xa08` | `0xa20` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x780` | `0x798` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x144` | `0x158` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0xc0` | `0xd0` | **`+0x10`** |
| `__DATA.__common` | `0x120` | `0x128` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x250` | `0x258` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xf0` | `0xf8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2972.30.6.12.16
+2972.30.6.12.32

-  Functions: 1489
-  Symbols:   254
-  CStrings:  1252
+  Functions: 1510
+  Symbols:   259
+  CStrings:  1266
Symbols:
+ _OBJC_CLASS_$_MKGeodesicPolyline
+ _OBJC_CLASS_$_MKOverlayRenderer
+ _OBJC_CLASS_$_MKPolylineRenderer
+ _OBJC_CLASS_$_NSNumber
+ __MKMapRectThatFits
CStrings:
+ "CalculateETAIntent: Geodesic snapshotter error: %s"
+ "CalculateETAIntent: currentLocationFlags — missing current-location geoMapItem, treating as not current location"
+ "CalculateETAIntent: currentLocationFlags — origin=%{bool}d, destination=%{bool}d"
+ "CalculateETAIntent: currentLocationFlags — unable to fetch current location: %s"
+ "No valid destination waypoints were provided."
+ "This operation is not supported for the current navigation type."
+ "_setOverlayRenderers:forOverlayLevel:"
+ "boundingMapRect"
+ "cameraLookingAtMapItem:forViewSize:allowPitch:viewInsets:"
+ "colorWithAlphaComponent:"
+ "generateGeodesicDistanceSnapshot(from:to:)"
+ "initWithDouble:"
+ "initWithInteger:"
+ "initWithPolyline:"
+ "polylineWithCoordinates:count:"
+ "setLineDashPattern:"
+ "setLineWidth:"
+ "setMapRect:"
+ "setStrokeColor:"
+ "whiteColor"
- "CalculateETAIntent: originIsCurrentLocation — equalForDirectionsWaypoint=%{bool}d"
- "CalculateETAIntent: originIsCurrentLocation — missing geoMapItem, treating as not current location"
- "CalculateETAIntent: originIsCurrentLocation — unable to fetch current location: %s"
- "cameraLookingAtMapItem:forViewSize:allowPitch:"
- "result"
- "systemBackgroundColor"
```
