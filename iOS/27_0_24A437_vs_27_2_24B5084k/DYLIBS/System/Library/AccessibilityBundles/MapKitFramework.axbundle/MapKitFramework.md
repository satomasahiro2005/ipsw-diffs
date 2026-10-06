## MapKitFramework

> `/System/Library/AccessibilityBundles/MapKitFramework.axbundle/MapKitFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb17c` | `0xc5e8` | **`+0x146c`** |
| `__AUTH_CONST.__cfstring` | `0x29a0` | `0x30a0` | **`+0x700`** |
| `__TEXT.__cstring` | `0x2067` | `0x22ee` | **`+0x287`** |
| `__AUTH_CONST.__objc_const` | `0x3910` | `0x3a30` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x129c` | `0x1344` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x500` | `0x5a0` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x730` | `0x7b0` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x430` | `0x450` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x328` | `0x338` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xd0` | `0xd8` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 355
-  Symbols:   1047
-  CStrings:  368
+  Functions: 367
+  Symbols:   1074
+  CStrings:  425
Symbols:
+ +[MKLookAroundViewAccessibility _accessibilityPerformValidations:]
+ +[MKLookAroundViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[MKLookAroundViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[MKLookAroundViewAccessibility _axLookAroundAutomationValue]
+ -[MKLookAroundViewAccessibility _axLookAroundCameraValue:]
+ -[MKLookAroundViewAccessibility _axLookAroundCenterValue:]
+ -[MKLookAroundViewAccessibility _axLookAroundLocationValue:]
+ -[MKLookAroundViewAccessibility _axLookAroundPlaceMUIDs]
+ -[MKLookAroundViewAccessibility _axLookAroundPointValue]
+ -[MKLookAroundViewAccessibility _axLookAroundRoadLabelTexts:]
+ -[MKLookAroundViewAccessibility _axLookAroundSelectedLabelValue]
+ -[MKLookAroundViewAccessibility accessibilityValue]
+ GCC_except_table147
+ GCC_except_table170
+ GCC_except_table187
+ _AXDoesRequestingClientDeserveAutomation
+ _OBJC_CLASS_$_MKLookAroundViewAccessibility
+ _OBJC_CLASS_$_NSDecimalNumber
+ _OBJC_CLASS_$_NSJSONSerialization
+ _OBJC_CLASS_$_NSMutableDictionary
+ _OBJC_CLASS_$___MKLookAroundViewAccessibility_super
+ _OBJC_METACLASS_$_MKLookAroundViewAccessibility
+ _OBJC_METACLASS_$___MKLookAroundViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_MKLookAroundViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_MKLookAroundViewAccessibility
+ __OBJC_CLASS_RO_$_MKLookAroundViewAccessibility
+ __OBJC_CLASS_RO_$___MKLookAroundViewAccessibility_super
+ __OBJC_METACLASS_RO_$_MKLookAroundViewAccessibility
+ __OBJC_METACLASS_RO_$___MKLookAroundViewAccessibility_super
+ _objc_retainAutoreleaseReturnValue
- GCC_except_table135
- GCC_except_table158
- GCC_except_table175
CStrings:
+ "%.*f"
+ "GEOCameraFrame"
+ "GEOLocationInfo"
+ "GEOMuninViewState"
+ "I"
+ "MKLookAroundView"
+ "MKLookAroundViewAccessibility"
+ "VKLabelMarker"
+ "VKMarker"
+ "VKMuninMarker"
+ "adequatelyDrawn"
+ "altitude"
+ "buildId"
+ "camera"
+ "cameraFrame"
+ "center"
+ "drawn"
+ "entered"
+ "featureID"
+ "hasAltitude"
+ "hasEnteredLookAround"
+ "hasLatitude"
+ "hasLongitude"
+ "hasPitch"
+ "hasRoll"
+ "hasYaw"
+ "id"
+ "isLoading"
+ "lat"
+ "latitude"
+ "loading"
+ "locality"
+ "localityName"
+ "location"
+ "locationInfo"
+ "locationName"
+ "lon"
+ "longitude"
+ "muid"
+ "muninMarker"
+ "muninViewState"
+ "pitch"
+ "placeMUIDs"
+ "point"
+ "pointId"
+ "roadLabelCount"
+ "roadLabels"
+ "roll"
+ "secondaryLocationName"
+ "secondaryName"
+ "selectedLabel"
+ "selectedLabelMarker"
+ "showsPointLabels"
+ "showsRoadLabels"
+ "visiblePlaceMUIDs"
+ "visibleRoadLabels"
+ "yaw"
```
