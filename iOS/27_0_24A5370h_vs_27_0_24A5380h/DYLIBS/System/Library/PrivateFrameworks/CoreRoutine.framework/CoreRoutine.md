## CoreRoutine

> `/System/Library/PrivateFrameworks/CoreRoutine.framework/CoreRoutine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6de58` | `0x6dfac` | **`+0x154`** |
| `__AUTH.__objc_data` | `0x1630` | `0x14f0` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x1a40` | `0x1b80` | **`+0x140`** |
| `__TEXT.__cstring` | `0x76c3` | `0x773b` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0xff48` | `0xffa8` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x6520` | `0x6560` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x8c58` | `0x8c70` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2bf8` | `0x2c08` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2060` | `0x2070` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x92c` | `0x934` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x548` | `0x550` | **`+0x8`** |

### Other Changes

```diff

-1114.0.0.0.0
+1117.0.0.0.0

-  Functions: 3111
-  Symbols:   5494
-  CStrings:  1216
+  Functions: 3113
+  Symbols:   5498
+  CStrings:  1218
Symbols:
+ -[RTBluePOITile disableDistancePriorForHighDensity]
+ -[RTBluePOITile distancePriorWeight]
+ -[RTBluePOITile initWithIdentifier:apToModelMapping:date:disableDistancePriorForHighDensity:distancePriorWeight:distancePriors:downloadKey:geoCacheInfo:geoTileKey:hashedApToModelMapping:hashedApToModelMappingDataURL:hashSalt:modelCalibrationParameters:models:modelURLs:pointsOfInterest:singlePOIMuid:size:]
+ _OBJC_IVAR_$_RTBluePOITile._disableDistancePriorForHighDensity
+ _OBJC_IVAR_$_RTBluePOITile._distancePriorWeight
- -[RTBluePOITile initWithIdentifier:apToModelMapping:date:distancePriors:downloadKey:geoCacheInfo:geoTileKey:hashedApToModelMapping:hashedApToModelMappingDataURL:hashSalt:modelCalibrationParameters:models:modelURLs:pointsOfInterest:singlePOIMuid:size:]
CStrings:
+ "disableDistancePriorForHighDensity"
+ "distancePriorWeight"
+ "identifier, %@, date, %@, geoTileKey, %@, downloadKey, %@, distance priors, %@, distancePriorWeight, %f, disableDistancePriorForHighDensity, %@, geoCacheInfo, %@, size, %.1f kB, hashSalt, %@, apToModelMapping count, %lu, hashedApToModelMapping count, %lu, hashedApToModelMappingDataURL, %@, singlePOIMuid, %@, models, %@, model URLs, %@, modelCalibrationParameters, %@, pointsOfInterest, %@"
- "identifier, %@, date, %@, geoTileKey, %@, downloadKey, %@, distance priors, %@, geoCacheInfo, %@, size, %.1f kB, hashSalt, %@, apToModelMapping count, %lu, hashedApToModelMapping count, %lu, hashedApToModelMappingDataURL, %@, singlePOIMuid, %@, models, %@, model URLs, %@, modelCalibrationParameters, %@, pointsOfInterest, %@"
```
