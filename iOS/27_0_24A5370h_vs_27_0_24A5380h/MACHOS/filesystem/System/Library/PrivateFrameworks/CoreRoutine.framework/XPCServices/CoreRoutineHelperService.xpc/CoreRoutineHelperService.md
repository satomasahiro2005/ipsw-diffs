## CoreRoutineHelperService

> `/System/Library/PrivateFrameworks/CoreRoutine.framework/XPCServices/CoreRoutineHelperService.xpc/CoreRoutineHelperService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc2af8` | `0xc311c` | **`+0x624`** |
| `__TEXT.__objc_methname` | `0x9ed1` | `0xa1d9` | **`+0x308`** |
| `__TEXT.__oslogstring` | `0x31a2` | `0x3294` | **`+0xf2`** |
| `__TEXT.__objc_stubs` | `0x5e00` | `0x5ee0` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x3544` | `0x35ec` | **`+0xa8`** |
| `__DATA.__objc_const` | `0x39e8` | `0x3a88` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x2808` | `0x2880` | **`+0x78`** |
| `__TEXT.__objc_methtype` | `0x3d07` | `0x3d5b` | **`+0x54`** |
| `__DATA_CONST.__cfstring` | `0x1ff00` | `0x1ff40` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3addf` | `0x3ae1d` | **`+0x3e`** |
| `__DATA_CONST.__got` | `0x588` | `0x5a8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x178` | `0x180` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x2194` | `0x2190` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1114.0.0.0.0
+1117.0.0.0.0

-  Functions: 1203
+  Functions: 1213

-  CStrings:  6317
+  CStrings:  6342
CStrings:
+ "%@, blended POI muid %@, rankProb %.6f, sigmaProb %.6f, weight %.4f, blended %.6f"
+ "%@, invalid distancePriorWeight %.6f, expected [0, 1]"
+ "%@, tile missing distancePriorWeight, computed default %.6f from modelCoveredMuids count %lu, threshold %u"
+ "@56@0:8@16@24@32@40d48"
+ "Skipping distance model for high density area"
+ "TB,N,V_disableDistancePriorForHighDensity"
+ "Td,N,V_distancePriorWeight"
+ "_disableDistancePriorForHighDensity"
+ "_distancePriorWeight"
+ "createFloorMapForLOI:reply:"
+ "createFloorMapForVisit:reply:"
+ "disableDistancePriorForHighDensity"
+ "disable_distance_prior_for_high_density"
+ "distancePriorWeight"
+ "distance_prior_weight"
+ "fetchTransactionDiagnosticsSampledWithReply:"
+ "hasDisableDistancePriorForHighDensity"
+ "hasDistancePriorWeight"
+ "initWithIdentifier:apToModelMapping:date:disableDistancePriorForHighDensity:distancePriorWeight:distancePriors:downloadKey:geoCacheInfo:geoTileKey:hashedApToModelMapping:hashedApToModelMappingDataURL:hashSalt:modelCalibrationParameters:models:modelURLs:pointsOfInterest:singlePOIMuid:size:"
+ "probabilityDistributionOfNearbyPointsOfInterestsWithReferenceLocation:pointsOfInterest:modelCoveredMuids:distancePriors:distancePriorWeight:"
+ "rankBasedDistributionWithReferenceLocation:pointsOfInterest:modelCoveredMuids:distancePriors:"
+ "setDisableDistancePriorForHighDensity:"
+ "setDistancePriorWeight:"
+ "setHasDisableDistancePriorForHighDensity:"
+ "setHasDistancePriorWeight:"
+ "setTransactionDiagnosticsSampled:reply:"
+ "sigmaBasedDistributionWithReferenceLocation:pointsOfInterest:modelCoveredMuids:"
+ "unionSet:"
+ "{?=\"distancePriorWeight\"b1\"tileKey\"b1\"disableDistancePriorForHighDensity\"b1}"
+ "\x89"
- "Skipping distance model: model has %lu classes"
- "initWithIdentifier:apToModelMapping:date:distancePriors:downloadKey:geoCacheInfo:geoTileKey:hashedApToModelMapping:hashedApToModelMappingDataURL:hashSalt:modelCalibrationParameters:models:modelURLs:pointsOfInterest:singlePOIMuid:size:"
- "probabilityDistributionOfNearbyPointsOfInterestsWithReferenceLocation:pointsOfInterest:modelCoveredMuids:distancePriors:"
- "y"
- "{?=\"tileKey\"b1}"
```
