## CoreLocation

> `/System/Library/Frameworks/CoreLocation.framework/CoreLocation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x204088` | `0x205ef0` | **`+0x1e68`** |
| `__TEXT.__cstring` | `0x24781` | `0x24f39` | **`+0x7b8`** |
| `__AUTH_CONST.__cfstring` | `0xb6a0` | `0xb920` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x3a8f4` | `0x3ab5c` | **`+0x268`** |
| `__AUTH_CONST.__const` | `0x3c58` | `0x3d10` | **`+0xb8`** |
| `__DATA_CONST.__const` | `0x20b8` | `0x2158` | **`+0xa0`** |
| `__TEXT.__const` | `0x4c50` | `0x4cd0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x9b0c` | `0x9b74` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x5620` | `0x5688` | **`+0x68`** |
| `__TEXT.__gcc_except_tab` | `0xf1a8` | `0xf1fc` | **`+0x54`** |
| `__AUTH_CONST.__objc_const` | `0x10258` | `0x10298` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5260` | `0x52a0` | **`+0x40`** |
| `__AUTH_CONST.__objc_dictobj` | `0x50` | `0x78` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x90` | `0xa0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xdb0` | `0xdb8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xafc` | `0xb00` | **`+0x4`** |

### Other Changes

```diff

-3176.0.0.0.0
+3183.0.0.0.0

-  Functions: 5178
-  Symbols:   1082
-  CStrings:  5501
+  Functions: 5203
+  Symbols:   1083
+  CStrings:  5541
Symbols:
+ _CLPromoteSystemService
CStrings:
+ "#Spi, CLPromoteSystemService failed"
+ "+[CLMapsXPCServiceManager sharedInstance]_block_invoke"
+ "-[CLLocationInternalClient promoteSystemServiceWithBundlePath:]_block_invoke"
+ "-[CLMapsXPCServiceManager collectMapDataOfType:aroundCoordinate:inRadius:allowNetwork:preferCachedTiles:isPedestrianOrCycling:clearTiles:callSynchronously:includeRoadNames:WithReply:]_block_invoke"
+ "-[CLMapsXPCServiceManager findTunnelEndPointFromLocation:roadID:clRoadID:projection:snapCourse:maxIterations:allowNetwork:preferCachedTiles:clearTiles:callSynchronously:withReply:]_block_invoke"
+ "19:39:25"
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 73,invalid col %zu > %zu."
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 80,invalid col %zu > %zu."
+ "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMVector.h, line 299,invalid index %zu >= %zu."
+ "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMVector.h, line 305,invalid index %zu >= %zu."
+ "Assertion failed: ldx < M*N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 86,invalid element %zu >= %zu."
+ "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 72,invalid row %zu > %zu."
+ "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 79,invalid row %zu > %zu."
+ "CL: CLPromoteSystemService"
+ "CLMM,%{public}.1lf,TEPA,XPC dispatch,roadID,%{private}llu,clRoadID,%{private}llu,projection,%{public}.3lf,snapCourse,%{public}.1lf"
+ "CLMM,%{public}.1lf,no TEPA,XPC scan returned nil"
+ "CLMM,%{public}.1lf,no TEPA,exit lat/lon are null-island in helper reply"
+ "CLMM,%{public}.1lf,no TEPA,gated by launch throttle,launchAge,%{public}.2lf,inFlight,%{public}d,succeeded,%{public}d"
+ "CLMM,%{public}s"
+ "CLMM,CLTSP,CLMapHelperService XPCService asynchronous TEPA tunnel scan error,%{public}lld,domain,%{public}@,description,\"%{private}@\""
+ "CLMM,CLTSP,CLMapHelperService XPCService synchronous TEPA tunnel scan error,%{public}lld,domain,%{public}@,description,\"%{private}@\""
+ "CLMM,CLTSP,MapHelperService,XPCService returned findTunnelEndPoint,success,%{public}d,responseTime,%{public}.1lf,syncCall,%{public}d"
+ "CLMM,CLTSP,Roads,intersection query returned error,useStartOfRoad,%d"
+ "CLMM,CLTSP,Roads,intersection query,semaphore timed out,useStartOfRoad,%d"
+ "CLMM,CarPlayDRLowSpeedCourseUnc,suppressing override,speed,%{public}.2f,courseUnc,%{public}.1f"
+ "CLMM,fetchTunnelEndPointAssistance,anchor crumb invalid"
+ "CLMM,no TEPA,isTunnel,%{public}d,isSnapUsable,%{public}d,lastLaunchTime,%{public}.1lf,inFlight,%{public}d,succeeded,%{public}d"
+ "CLTSP,CLMM,MaphelperService,findTunnelEndPoint ENTRY,roadID,%llu,clRoadID,%llu,projection,%.3lf,snapCourse,%.1lf,allowNetwork,%d,preferCachedTiles,%d"
+ "CLTSP,CLMM,MaphelperService,findTunnelEndPoint EXIT nil,forward scan failed,iterOut,%d,distSoFar,%.1lf,reason,%s"
+ "CLTSP,CLMM,MaphelperService,findTunnelEndPoint EXIT nil,start road not found or not tunnel,startRoad,%d,gmf,%d,isTunnel,%d"
+ "CLTSP,CLMM,MaphelperService,findTunnelEndPoint EXIT ok,distToExit,%.1lf,tunnelLength,%.1lf,iterOut,%d,iterIn,%d,curved,%d"
+ "CLTSP,CLMM,MaphelperService,findTunnelEndPoint,%s,fillFromGEOMapFeatureRoad failed"
+ "CLTSP,CLMM,MaphelperService,findTunnelEndPoint,%s,reached max iterations,%d"
+ "Jul 11 2026"
+ "TEPA,backward scan reached max iterations,"
+ "TEPA,forward scan reached max iterations,"
+ "TEPA,tunnel start point not found (TEPA exit point still valid),backward fillFromGEOMapFeatureRoad failed"
+ "TEPA,tunnel start point not found (TEPA exit point still valid),backward intersection query failed"
+ "TEPA,tunnel start point not found (TEPA exit point still valid),multi-inbound,"
+ "bwd"
+ "bwdFailureReason"
+ "courseAtExitPoint"
+ "endPointDistanceFromCurrentSolution"
+ "failureReason"
+ "fwd"
+ "generateRouteSummary"
+ "isTunnelCurved"
+ "iterationsIn"
+ "iterationsOut"
+ "no TEPA,forward fillFromGEOMapFeatureRoad failed"
+ "no TEPA,forward intersection query failed"
+ "no TEPA,forward scan failed (unknown reason)"
+ "no TEPA,multi-outbound,"
+ "no TEPA,start road not found or not tunnel"
+ "speedLimitMps"
+ "startLatitude"
+ "startLongitude"
+ "tunnelLength"
+ "tunnelWidthAtExitPoint"
+ "v132@?0B8{TunnelEndPositionAssistance=dddddddddBiBidddd}12"
+ "virtual void CLParticleMapMatcher::fetchTunnelEndPointAssistance(double, CLMapGeometryPtr, bool, CLTunnelEndPointReply)_block_invoke"
+ "void CLParticleMapMatcherCommon::SolutionPropagator::fetchTunnelEndPointAssistance(double, CLMapGeometryPtr, bool, CLTunnelEndPointReply)"
+ "void CLParticleMapMatcherCommon::SolutionPropagator::fetchTunnelEndPointAssistance(double, CLMapGeometryPtr, bool, CLTunnelEndPointReply)_block_invoke"
+ "{\"msg%{public}.0s\":\"CLPromoteSystemService\", \"event\":%{public, location:escape_only}s}"
- "+[CLMapsXPCServiceManager sharedInstance]"
- "-[CLMapsXPCServiceManager collectMapDataOfType:aroundCoordinate:inRadius:allowNetwork:preferCachedTiles:isPedestrianOrCycling:clearTiles:callSynchronously:WithReply:]_block_invoke"
- "22:02:43"
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 81,invalid col %zu > %zu."
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 88,invalid col %zu > %zu."
- "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMVector.h, line 292,invalid index %zu >= %zu."
- "Assertion failed: i < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMVector.h, line 298,invalid index %zu >= %zu."
- "Assertion failed: ldx < M*N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 94,invalid element %zu >= %zu."
- "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 80,invalid row %zu > %zu."
- "Assertion failed: row < M, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMMatrix.h, line 87,invalid row %zu > %zu."
- "CLMM,CLTSP,Roads,findRoadsFromNextIntersectionOf returned error"
- "CLMM,CLTSP,Roads,findRoadsFromNextIntersectionOf,semaphore timed out"
- "CLMM,TEPA,incoming reached max iterations,%{public}d"
- "CLMM,TEPA,outgoing reached max iterations,%{public}d"
- "CLMM,TEPA,tunnel start point not found (TEPA exit point still valid),multi-inbound,%{public}d"
- "CLMM,getTunnelEndPointAssistance,m_current.crumb invalid"
- "CLMM,no TEPA,isTunnel,%{public}d,isSnapUsable,%{public}d,lastAssistanceTime,%{public}.1lf"
- "CLMM,no TEPA,multi-outbound,%{public}d"
- "CLTSP,constructRouteUsingFamiliarRoads,routeSummary,%{sensitive}s,tripID,%{public}s,attempt,%{public}d,percentageFamiliarRoads,%{public}.1f%%"
- "Jun 27 2026"
- "[CLPedestrianRTSSmoother]:[runRTS] Course offset is not initialized."
- "bool CLParticleMapMatcherCommon::SolutionPropagator::findTunnelEndPoint(double, CLGpsAssistant_Type::TunnelEndPositionAssistance &, CLMapGeometryPtr, bool)"
- "speedLimit"
- "virtual bool CLParticleMapMatcher::getTunnelEndPointAssistance(double, CLGpsAssistant_Type::TunnelEndPositionAssistance &)"
```
