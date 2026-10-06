## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/AirPlaySender`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2463d4` | `0x246784` | **`+0x3b0`** |
| `__TEXT.__cstring` | `0x8f88f` | `0x8f9e4` | **`+0x155`** |
| `__DATA.__data` | `0x18690` | `0x18620` | **`-0x70`** |
| `__DATA_DIRTY.__data` | `0xf78` | `0xfe8` | **`+0x70`** |
| `__TEXT.__const` | `0x61f0` | `0x6190` | **`-0x60`** |
| `__AUTH_CONST.__const` | `0x7780` | `0x77b0` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x58f0` | `0x5908` | **`+0x18`** |

### Other Changes

```diff

-1005.7.1.0.0
+1005.8.1.0.0

-  Functions: 11457
-  Symbols:   8671
-  CStrings:  11654
+  Functions: 11465
+  Symbols:   8677
+  CStrings:  11659
Symbols:
+ GCC_except_table128
+ GCC_except_table50
+ _APSIsUpdateInfoForwardingEnabled
+ _APTransportDeviceForwardAirPlayInfoToBrowser
+ _FigCFNumberGetCFIndex
+ _carManager_reportBonjourEventToCarKit
+ _carManager_reportBonjourSuccessIfNeeded
+ _endpointCluster_failDelayMSecsForFailureCount.kFailDelayLadderPercent
+ _endpointCluster_failureCountForSubEndpoint
+ _endpoint_forwardUpdateInfo
- GCC_except_table127
- GCC_except_table48
- _carManager_isDisconnectCausedBySignalInterference
- _carManager_reportBonjourFailureToCarKit
CStrings:
+ "1005.8.1"
+ "Eligible for fast reactivate"
+ "Local HT first loss"
+ "[%{ptr}] Bonjour events monitoring: sending Bonjour info to CarKit: %@"
+ "[%{ptr}] Fail delay timer already running, discarding requested delay of %llu ms for subEndpoint [%{ptr}]%?{end}, failure count %ld"
+ "[%{ptr}] Ignoring subEndpoint [%{ptr}] failure, cluster is deactivated"
+ "[%{ptr}] Immediately triggering lost cluster buddy reconnect logic for [%{ptr}] (session state: %s, reason: %s)"
+ "[%{ptr}] Starting fail delay timer for seed %llu, subEndpoint [%{ptr}], with delay of %llu ms%?{end}, failure count %ld"
+ "carManager_reportBonjourEventToCarKit"
+ "endpoint_forwardUpdateInfo"
+ "void carManager_reportBonjourEventToCarKit(FigEndpointManagerRef, Boolean, APCarPlayFailureInfoReason)"
+ "void endpointCluster_startFailDelayTimerIfNeeded(FigEndpointRef, FigEndpointRef)"
- "1005.7.1"
- "[%{ptr}] Bonjour events monitoring: sending Bonjour failure info to CarKit: %@"
- "[%{ptr}] Immediately triggering lost cluster buddy reconnect logic for [%{ptr}] during startup\n"
- "[%{ptr}] Starting fail delay timer for seed %llu with delay of %llu seconds.\n"
- "carManager_reportBonjourFailureToCarKit"
- "void carManager_reportBonjourFailureToCarKit(FigEndpointManagerRef, Boolean, APCarPlayFailureInfoReason)"
- "void endpointCluster_startFailDelayTimerIfNeeded(FigEndpointRef)"
```
