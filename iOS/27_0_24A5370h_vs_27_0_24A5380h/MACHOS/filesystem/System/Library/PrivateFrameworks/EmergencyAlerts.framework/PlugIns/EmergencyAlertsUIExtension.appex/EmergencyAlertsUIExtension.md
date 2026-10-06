## EmergencyAlertsUIExtension

> `/System/Library/PrivateFrameworks/EmergencyAlerts.framework/PlugIns/EmergencyAlertsUIExtension.appex/EmergencyAlertsUIExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c5c` | `0x527c` | **`-0x9e0`** |
| `__TEXT.__objc_stubs` | `0x1c80` | `0x1b00` | **`-0x180`** |
| `__TEXT.__objc_methname` | `0x17b9` | `0x167f` | **`-0x13a`** |
| `__DATA.__objc_selrefs` | `0x898` | `0x838` | **`-0x60`** |
| `__TEXT.__objc_methtype` | `0x367` | `0x317` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x808` | `0x7c9` | **`-0x3f`** |
| `__TEXT.__objc_methlist` | `0x4a4` | `0x474` | **`-0x30`** |
| `__DATA_CONST.__cfstring` | `0x8c0` | `0x8a0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1c0` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x3d0` | `0x3b0` | **`-0x20`** |
| `__TEXT.__const` | `0x114` | `0x12c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x158` | `0x140` | **`-0x18`** |
| `__DATA_CONST.__auth_got` | `0x1f0` | `0x1e0` | **`-0x10`** |
| `__TEXT.__cstring` | `0x52a` | `0x525` | **`-0x5`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-266.0.0.0.0
+268.0.0.0.0

-  Functions: 101
-  Symbols:   173
-  CStrings:  486
+  Functions: 96
+  Symbols:   167
+  CStrings:  469
Symbols:
+ _fmod
- _CLLocationCoordinate2DIsValid
- _OBJC_CLASS_$_CLCircularRegion
- _OBJC_CLASS_$__CLPolygonalRegion
- _OBJC_CLASS_$__CLVertex
- _kCLLocationCoordinate2DInvalid
- _objc_retain_x25
- _objc_retain_x27
CStrings:
- "@40@0:8@16{CLLocationCoordinate2D=dd}24"
- "B40@0:8{CLLocationCoordinate2D=dd}16@32"
- "Cannot get user location"
- "Using user location for rendering map"
- "arrayWithCapacity:"
- "containsCoordinate:"
- "coordinate"
- "findClosestCircularGeofence:toLocation:"
- "findClosestPolygonalGeofence:toLocation:"
- "initWithCenter:radius:identifier:"
- "initWithCoordinate:"
- "initWithVertices:identifier:"
- "isUserLocation:insideCircularGeofence:"
- "isUserLocation:insidePolygonalGeofence:"
- "location"
- "mutableCopy"
- "temp"
```
