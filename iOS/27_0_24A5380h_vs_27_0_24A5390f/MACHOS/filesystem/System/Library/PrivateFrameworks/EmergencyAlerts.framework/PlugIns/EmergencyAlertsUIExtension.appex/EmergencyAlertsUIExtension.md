## EmergencyAlertsUIExtension

> `/System/Library/PrivateFrameworks/EmergencyAlerts.framework/PlugIns/EmergencyAlertsUIExtension.appex/EmergencyAlertsUIExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x527c` | `0x5170` | **`-0x10c`** |
| `__DATA_CONST.__cfstring` | `0x8a0` | `0x7e0` | **`-0xc0`** |
| `__TEXT.__objc_stubs` | `0x1b00` | `0x1a40` | **`-0xc0`** |
| `__TEXT.__objc_methname` | `0x167f` | `0x15e2` | **`-0x9d`** |
| `__TEXT.__cstring` | `0x525` | `0x4c9` | **`-0x5c`** |
| `__TEXT.__oslogstring` | `0x7c9` | `0x7fa` | **`+0x31`** |
| `__DATA.__objc_selrefs` | `0x838` | `0x808` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x218` | `0x200` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x1c0` | `0x1a8` | **`-0x18`** |
| `__TEXT.__const` | `0x12c` | `0x134` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-268.0.0.0.0
+272.1.0.0.0

-  Functions: 96
-  Symbols:   167
-  CStrings:  469
+  Functions: 97
+  Symbols:   161
+  CStrings:  458
Symbols:
+ _MKMapPointForCoordinate
+ _MKMapRectNull
+ _MKMapSizeWorld
+ _objc_retain_x25
- _EACategoryIdentifierGeoAlertWatch
- _EACategoryIdentifierGeoAlertWatchInternal
- _EACategoryIdentifierIgneous
- _NSTextCheckingCityKey
- _NSTextCheckingStateKey
- _NSTextCheckingStreetKey
- _OBJC_CLASS_$_CLLocation
- _OBJC_CLASS_$_NSCharacterSet
- _cos
- _objc_retain_x26
CStrings:
+ "Failed to compute bounding rect for geofences, hiding map."
+ "No overlays to display, hiding map."
+ "bounds"
+ "setVisibleMapRect:edgePadding:"
- " "
- "Failed to determine map location, hiding map."
- "URLHostAllowedCharacterSet"
- "addressComponents"
- "distanceFromLocation:"
- "geo-alert-watch"
- "geo-alert-watch-internal"
- "http://maps.apple.com/?address="
- "igneous"
- "initWithLatitude:longitude:"
- "phoneNumber"
- "setRegion:"
- "stringByAddingPercentEncodingWithAllowedCharacters:"
- "stringByAppendingString:"
- "tel://%@"
```
