## CoreLocation

> `/System/Library/Frameworks/CoreLocation.framework/CoreLocation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x207058` | `0x208954` | **`+0x18fc`** |
| `__TEXT.__oslogstring` | `0x3abea` | `0x3aeb6` | **`+0x2cc`** |
| `__TEXT.__cstring` | `0x2514e` | `0x2525f` | **`+0x111`** |
| `__TEXT.__objc_methlist` | `0x9bd4` | `0x9cb4` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0xf25c` | `0xf188` | **`-0xd4`** |
| `__AUTH_CONST.__cfstring` | `0xba40` | `0xbae0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x21b0` | `0x2248` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0x10468` | `0x104e0` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x52d0` | `0x5338` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x56c0` | `0x5710` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0xb24` | `0xb30` | **`+0xc`** |
| `__AUTH_CONST.__const` | `0x3d30` | `0x3d38` | **`+0x8`** |

### Other Changes

```diff

-3185.0.6.0.3
+3186.0.12.0.0

-  Functions: 5216
-  Symbols:   1084
-  CStrings:  5556
+  Functions: 5240
+  Symbols:   1085
+  CStrings:  5584
Symbols:
+ _CLCopyAuthorization
CStrings:
+ "#Spi, CLCopyAuthorization failed"
+ "-[CLLocationInternalClient copyAuthorizationFromBundleID:toBundleID:]_block_invoke"
+ "22:37:18"
+ "AllowedAlways"
+ "AllowedAlwaysProvisionally"
+ "AllowedWhenInUse"
+ "AuthContext InUse:%d  RegResult Transient:%s Effective:%s  EffectiveMask:%d  ProvisionalMask:%d  DiagnosticMask:%d"
+ "CL: CLCopyAuthorization"
+ "CLMM,%{public}.1lf,TEPA,XPC dispatch,roadID,%{private}llu,clRoadID,%{sensitive}llu,projection,%{public}.3lf,snapCourse,%{public}.1lf"
+ "CLRS,CLTSP,intervalCountMismatch,decoded,%{public}lu,recorded,%{public}lu"
+ "CLRS,CLTSP,malformedPackedAltitudeBlob,bytes,%{public}lu,stride,%{public}lu"
+ "CLRS,CLTSP,malformedPackedLocationBlob,bytes,%{public}lu,stride,%{public}lu"
+ "CLRS,CLTSP,malformedPackedOdometryBlob,bytes,%{public}lu,stride,%{public}lu"
+ "CLRS,CLTSP,packedAltitudeBlobAllocationFailed,samples,%{public}lu"
+ "CLRS,CLTSP,packedLocationBlobAllocationFailed,samples,%{public}lu"
+ "CLRS,CLTSP,packedOdometryBlobAllocationFailed,samples,%{public}lu"
+ "CLRS,CLTSP,unsupportedBatchInputSchemaVersion,decoded,%{public}lu,oldestSupported,%{public}lu,current,%{public}lu"
+ "CLTSP,%{public}.1lf,A* Search road already added,%{sensitive}llu"
+ "CLTSP,%{public}.1lf,aStarConstruct,added first road,%{sensitive}llu,processingTime,%{private}.2lf"
+ "CLTSP,%{public}.1lf,aStarConstruct,search road already added,%{sensitive}llu"
+ "CLTSP,%{public}.1lf,added first road,%{sensitive}llu"
+ "CLTSP,%{public}.1lf,added last road,%{sensitive}llu"
+ "CLTSP,%{public}.3lf,aStarConstruct,found neighbors for %{sensitive}llu,size,%{public}lu,g,%{public}.2lf,h,%{public}.2lf,cost,%{public}.2lf,iterationCount,%{public}d,stopLL,%{sensitive}.7lf,%{sensitive}.7lf,stopJunction,%{private}d,stopAlt,%{private}.2lf,processingTime,%{private}.2lf,openSet,%{public}d,closedSet,%{public}d,iterationThreshold,%{public}d"
+ "CLTSP,%{public}.3lf,constructing between,start,%{sensitive}llu,stop,%{sensitive}llu"
+ "CLTSP,%{public}.3lf,found neighbors for %{sensitive}llu,size,%{public}lu,g,%{public}.2lf,h,%{public}.2lf,cost,%{public}.2lf,iterationCount,%{public}d"
+ "CLTSP,%{sensitive}llu,KPIComputer,findClosestPointOnRoad returned false,isRouteWithSkippedPart,%{public}d"
+ "CLTSP,getCLTripSegmentRoadDataArrayAsCLMapRoadVector,findRoadsNear call failed,roadID,%{sensitive}llu"
+ "CLTSP,getCLTripSegmentRoadDataArrayAsCLMapRoadVector,road data query failed,roadID,%{sensitive}llu"
+ "FailedBlocklisted"
+ "FailedUnavailable"
+ "FailedUnverified"
+ "FailedUserDenied"
+ "Missing"
+ "RegistrationResultString"
+ "RequiresAgent"
+ "Sep 10 2026"
+ "TransientAwareRegistrationResultString"
+ "UNKNOWN"
+ "altitudeSamplesPacked"
+ "intervalCount"
+ "locationSamplesPacked"
+ "odometrySamplesPacked"
+ "v16@?0@?<v@?B>8"
+ "{\"msg%{public}.0s\":\"CLCopyAuthorization\", \"event\":%{public, location:escape_only}s}"
+ "\x81"
+ "\xb1"
- "21:18:53"
- "Aug 20 2026"
- "AuthContext InUse:%d  RegResult:%d(%d) EffectiveMask:%d  ProvisionalMask:%d  DiagnosticMask:%d"
- "CLMM,%{public}.1lf,TEPA,XPC dispatch,roadID,%{private}llu,clRoadID,%{private}llu,projection,%{public}.3lf,snapCourse,%{public}.1lf"
- "CLRS,CLTSP,unsupportedBatchInputSchemaVersion,decoded,%{public}lu,expected,%{public}lu"
- "CLTSP,%{private}llu,KPIComputer,findClosestPointOnRoad returned false,isRouteWithSkippedPart,%{public}d"
- "CLTSP,%{public}.1lf,A* Search road already added,%{private}lld"
- "CLTSP,%{public}.1lf,aStarConstruct,added first road,%{private}lld,processingTime,%{private}.2lf"
- "CLTSP,%{public}.1lf,aStarConstruct,search road already added,%{private}lld"
- "CLTSP,%{public}.1lf,added first road,%lld"
- "CLTSP,%{public}.1lf,added last road,%lld"
- "CLTSP,%{public}.3lf,aStarConstruct,found neighbors for %{private}lld,size,%{public}lu,g,%{public}.2lf,h,%{public}.2lf,cost,%{public}.2lf,iterationCount,%{public}d,stopLL,%{sensitive}.7lf,%{sensitive}.7lf,stopJunction,%{private}d,stopAlt,%{private}.2lf,processingTime,%{private}.2lf,openSet,%{public}d,closedSet,%{public}d,iterationThreshold,%{public}d"
- "CLTSP,%{public}.3lf,constructing between,start,%{public}lld,stop,%{public}lld"
- "CLTSP,%{public}.3lf,found neighbors for %{private}lld,size,%{public}lu,g,%{public}.2lf,h,%{public}.2lf,cost,%{public}.2lf,iterationCount,%{public}d"
- "CLTSP,CLMM,MaphelperService,findTunnelEndPoint ENTRY,roadID,%llu,clRoadID,%llu,projection,%.3lf,snapCourse,%.1lf,allowNetwork,%d,preferCachedTiles,%d"
- "CLTSP,getCLTripSegmentRoadDataArrayAsCLMapRoadVector,findRoadsNear call failed,roadID,%{public}lld"
- "CLTSP,getCLTripSegmentRoadDataArrayAsCLMapRoadVector,road data query failed,roadID,%{public}lld"
- "\xa1"
```
