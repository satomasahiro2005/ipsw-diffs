## CoreLocation

> `/System/Library/Frameworks/CoreLocation.framework/CoreLocation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2023e0` | `0x204210` | **`+0x1e30`** |
| `__TEXT.__cstring` | `0x241a5` | `0x24770` | **`+0x5cb`** |
| `__TEXT.__oslogstring` | `0x3a5a3` | `0x3a8f4` | **`+0x351`** |
| `__AUTH_CONST.__cfstring` | `0xb4c0` | `0xb680` | **`+0x1c0`** |
| `__DATA_CONST.__const` | `0x2020` | `0x20b8` | **`+0x98`** |
| `__TEXT.__gcc_except_tab` | `0xf138` | `0xf1b8` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x55a8` | `0x5610` | **`+0x68`** |
| `__TEXT.__const` | `0x4c30` | `0x4c60` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0xd88` | `0xda8` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x3c38` | `0x3c58` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x10208` | `0x10228` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x9ae4` | `0x9afc` | **`+0x18`** |
| `__DATA.__data` | `0x1ea0` | `0x1eb0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5248` | `0x5258` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xaf4` | `0xaf8` | **`+0x4`** |

### Other Changes

```diff

-3164.0.0.0.0
+3169.4.0.0.0

-  Functions: 5163
-  Symbols:   1077
-  CStrings:  5478
+  Functions: 5176
+  Symbols:   1081
+  CStrings:  5500
Symbols:
+ _CFPreferencesCopyAppValue
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
+ _dispatch_source_cancel
CStrings:
+ "%{public}@,vuncCheckRequiredForUsability,%{public}d,altitudeStitchingEnabled,%{public}d,maxUsableAge,%{public}f,maxUsableHunc,%{public}f,minUsableIntegrity,%{public}d"
+ "-[CLLocationSmoother configureWithWorkoutActivityType:shouldReconstructEntireRoute:timeIntervalsThatNeedPopulating:activeTimeIntervals:]_block_invoke"
+ "-[CLLocationSmoother smoothLocations:batchType:handler:]_block_invoke"
+ "-[_CLLocationSmootherProxy createConnection]"
+ "-[_CLSignificantRegion initWithCenter:radius:referenceFrame:lowPower:identifier:onBehalfOfBundleId:notifyOnEntry:notifyOnExit:conservativeEntry:emergency:requiresWirelessClientInfo:deviceId:handoffTag:]"
+ "00:15:46"
+ "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 240,invalid col %zu > %zu."
+ "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 241,invalid element %zu <= %zu."
+ "CLMM,%{public}.1lf,not matching,speed,%{public}.1lf,threshold,%{public}.1lf,priorUsable,%{public}d"
+ "CLMM,%{public}s,T,%{public}.1lf,usable,%{public}d,ambiguous,%{public}d,LL,%{sensitive}.7lf,%{sensitive}.7lf,crse,%{public}.1lf,snapLL,%{sensitive}.7lf,%{sensitive}.7lf,snapCrse,%{public}.1lf,fSnapLL,%{sensitive}.7lf,%{sensitive}.7lf,fSnapCrse,%{public}.1lf,hunc,%{public}.1lf,alt,%{public}.1lf,vunc,%{public}.1lf,crseUnc,%{public}.1lf,spdMps,%{public}.3lf,spdUncMps,%{public}.1lf,a95,%{public}.1lf,b95,%{public}.1lf,theta,%{public}.1lf,shifted,%{public}d,propagated,%{public}d,rail,%{public}d,bridge,%{public}d,tunnel,%{public}d,locationType,%{public}d,sigEnv,%{public}d,sigEnvFid,%{public}d,rw,%{public}.2lf,matchConf,%{public}.3lf"
+ "CLRS,createConnection,delivering pending completion before swap,hasPendingCompletion,%{public}d"
+ "CLRS,smoothLocations timeout fired,timeoutSec,%{public}d,batchType,%{public}lu"
+ "CLSmootherBatchSPITimeoutSeconds"
+ "Date: %@, allowDelayedResponse, %d, requireWirelessClientLocation, %d"
+ "Jun 16 2026"
+ "MachContinuousTimeSec: %.3f, allowDelayedResponse, %d, requireWirelessClientLocation, %d"
+ "NumberOfSeconds: %u, allowDelayedResponse, %d, returnSparseLocations, %d, requireWirelessClientLocation, %d"
+ "R"
+ "bool CLParticleMapMatcher::shallMapMatch(CLMapCrumb &)"
+ "com.apple.locationd.framework.reductivefilter.observation"
+ "maxInputHorizontalAccuracy"
+ "minInputHorizontalAccuracy"
+ "newestInputAge"
+ "oldestInputAge"
+ "p25InputAge"
+ "p25InputHorizontalAccuracy"
+ "p50InputAge"
+ "p50InputHorizontalAccuracy"
+ "p75InputAge"
+ "p75InputHorizontalAccuracy"
+ "requireWCILocation"
+ "timeBetweenObservations"
+ "void CLMapCrumb::condensedDebugOutput(const std::string) const"
- "%{public}@,vuncCheckRequiredForUsability,%{public}d,altitudeStitchingEnabled,%{public}d,maxUsableAge,%{public}f,maxUsableHunc,%{public}f,maxUsableVunc,%{public}f,minUsableIntegrity,%{public}d"
- "-[_CLSignificantRegion initWithCenter:radius:referenceFrame:lowPower:identifier:onBehalfOfBundleId:notifyOnEntry:notifyOnExit:conservativeEntry:emergency:deviceId:handoffTag:]"
- "2"
- "23:20:28"
- "Assertion failed: col < N, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 237,invalid col %zu > %zu."
- "Assertion failed: col > row, file /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreLocationFramework/Oscar/Math/CMFactoredMatrix.h, line 238,invalid element %zu <= %zu."
- "CLMM,%{public}.1lf, not matching"
- "Date: %@, allowDelayedResponse, %d"
- "MachContinuousTimeSec: %.3f, allowDelayedResponse, %d"
- "May 27 2026"
- "NumberOfSeconds: %u, allowDelayedResponse, %d, returnSparseLocations, %d"
```
