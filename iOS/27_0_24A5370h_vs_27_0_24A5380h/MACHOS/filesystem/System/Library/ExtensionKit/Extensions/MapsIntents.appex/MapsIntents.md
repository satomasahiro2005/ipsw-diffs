## MapsIntents

> `/System/Library/ExtensionKit/Extensions/MapsIntents.appex/MapsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51e70` | `0x537c8` | **`+0x1958`** |
| `__DATA.__data` | `0x19e0` | `0x1bf8` | **`+0x218`** |
| `__TEXT.__oslogstring` | `0x1786` | `0x195b` | **`+0x1d5`** |
| `__TEXT.__objc_stubs` | `0xfa0` | `0x1140` | **`+0x1a0`** |
| `__TEXT.__objc_methname` | `0x4887` | `0x49df` | **`+0x158`** |
| `__DATA.__objc_const` | `0x1d50` | `0x1e98` | **`+0x148`** |
| `__TEXT.__eh_frame` | `0x26a8` | `0x27a0` | **`+0xf8`** |
| `__TEXT.__const` | `0x4d34` | `0x4df4` | **`+0xc0`** |
| `__TEXT.__objc_classname` | `0x13b` | `0x1cb` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0xcf0` | `0xd70` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1c28` | `0x1ca8` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x1b30` | `0x1ba0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0xf8c` | `0xffc` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x648` | `0x6ac` | **`+0x64`** |
| `__TEXT.__swift5_typeref` | `0x2386` | `0x23c8` | **`+0x42`** |
| `__DATA_CONST.__auth_got` | `0xda0` | `0xdd8` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x9b0` | `0x9e8` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x14d8` | `0x1510` | **`+0x38`** |
| `__DATA_CONST.__objc_protolist` | `0x58` | `0x88` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xfd0` | `0x1000` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x518` | `0x540` | **`+0x28`** |
| `__DATA_CONST.__objc_doubleobj` | `0x380` | `0x3a0` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x28` | `0x40` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x9f8` | `0xa08` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1c85` | `0x1c95` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x10ec` | `0x10fc` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x8c` | `0x94` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x248` | `0x250` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x13c` | `0x144` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0xbc` | `0xc0` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xec` | `0xf0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-2970.30.6.5.7
+2972.30.6.12.16

+  - /System/Library/PrivateFrameworks/MapsSync.framework/MapsSync

-  Functions: 1473
-  Symbols:   249
-  CStrings:  1222
+  Functions: 1489
+  Symbols:   254
+  CStrings:  1252
Symbols:
+ _OBJC_CLASS_$_GEOFeatureStyleAttributes
+ _OBJC_CLASS_$_GEOIdealTransportTypeFinder
+ _OBJC_CLASS_$_MKMapCamera
+ _OBJC_CLASS_$_MKMapSnapshotCustomFeatureAnnotation
+ _OBJC_CLASS_$_MKMapSnapshotOptions
+ _OBJC_CLASS_$_MKMapSnapshotter
+ _swift_getErrorValue
+ _swift_initStackObject
+ _swift_retain_x26
- _OBJC_CLASS_$_MKAnnotatedMapSnapshotter
- _objc_retain_x27
- _objc_retain_x9
- _swift_willThrowTypedImpl
CStrings:
+ "@\"VKCustomFeature\"16@0:8"
+ "CalculateETAIntent: Creating MKMapSnapshotter"
+ "CalculateETAIntent: Failed to fetch favorite item for GEOMapItem: %@. Error=%s."
+ "IntentsUtil.mapItem: MKMapItemRequest failed: %s — rethrowing as unableToResolveLocation"
+ "IntentsUtil.mapItem: MKMapService.shared() unavailable — throwing unableToFetchMapService"
+ "MKCustomFeatureAnnotation"
+ "Td,?,N"
+ "T{?=dd},N"
+ "VKAnnotation"
+ "VKCustomFeatureAnnotation"
+ "_TtC11MapsIntentsP33_6597ACF131A204F9DE7B67B3B7CF945219ResourceBundleClass"
+ "_setCustomFeatureAnnotations:"
+ "_setSearchResultsType:"
+ "calculateETA(from:to:departureTime:resolvedTransportationType:)"
+ "cameraLookingAtMapItem:forViewSize:allowPitch:"
+ "course"
+ "customFeatureAnnotationForMapItem:styleAttributes:"
+ "favoriteType"
+ "feature"
+ "homeStyleAttributes"
+ "idealTransportTypeForCoordinates:count:mapType:"
+ "initWithOptions:"
+ "resolveTransportationType: explicit type=%s, passing through"
+ "resolveTransportationType: idealTTF resolved .any → %s"
+ "resolveTransportationType: insufficient coordinates (%ld), returning .any"
+ "schoolStyleAttributes"
+ "setCamera:"
+ "setCoordinate:"
+ "setCourse:"
+ "setSize:"
+ "showsBalloonCallout"
+ "v32@0:8{?=dd}16"
+ "workStyleAttributes"
- "CalculateETAIntent: Creating MKAnnotatedMapSnapshotter"
- "calculateETA(from:to:departureTime:)"
- "initWithMapItems:mapSize:useSnapshotService:"
```
