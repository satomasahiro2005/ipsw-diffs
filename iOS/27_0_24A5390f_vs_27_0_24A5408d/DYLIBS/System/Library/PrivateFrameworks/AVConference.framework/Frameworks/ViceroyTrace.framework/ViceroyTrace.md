## ViceroyTrace

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ViceroyTrace.framework/ViceroyTrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb9250` | `0xb9378` | **`+0x128`** |
| `__TEXT.__oslogstring` | `0xf2dd` | `0xf32a` | **`+0x4d`** |
| `__AUTH_CONST.__cfstring` | `0xede0` | `0xee00` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x178f8` | `0x17918` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x480` | `0x498` | **`+0x18`** |
| `__TEXT.__cstring` | `0xf45c` | `0xf46e` | **`+0x12`** |
| `__AUTH_CONST.__auth_got` | `0x6d0` | `0x6d8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x21f8` | `0x21fc` | **`+0x4`** |

### Other Changes

```diff

-2235.57.1.0.0
+2235.63.1.1.0

-  Functions: 4248
-  Symbols:   6734
-  CStrings:  3350
+  Functions: 4249
+  Symbols:   6736
+  CStrings:  3352
Symbols:
+ _CFPropertyListCreateDeepCopy
+ _OBJC_IVAR_$_VCAggregatorAirPlay._reportedMediaStreamType
Functions:
~ -[VCAggregatorAirPlay initWithDelegate:options:] : 1388 -> 1408
~ -[VCAggregatorAirPlay composeSegmentReport:] : 904 -> 956
~ -[VCAggregatorAirPlay updateSenderVideoStreamConfiguration:] : 448 -> 488
~ -[RTCReportingAgent reportPeriodicTelemetryWithCategory:type:payload:lock:] : 368 -> 420
~ -[VCPersistentDataStore finalizeInternal] : 144 -> 128
~ -[VCPersistentDataStore closeDatabase] : 100 -> 104
~ ___VCPersistentDataStore_DumpMessage_block_invoke_2 : 296 -> 288
~ -[VCAggregatorHomeKitAudio dispatchedAggregatedSessionReport] : 324 -> 348
~ -[RTCReportingAgent reportPeriodicTelemetryWithCategory:type:payload:lock:].cold.1 : 124 -> 128
+ -[RTCReportingAgent reportPeriodicTelemetryWithCategory:type:payload:lock:].cold.3
CStrings:
+ "ReportingVC [%s] %s:%d Failed to populate payload snapshot for Periodic Task"
+ "VCMediaStreamType"
```
