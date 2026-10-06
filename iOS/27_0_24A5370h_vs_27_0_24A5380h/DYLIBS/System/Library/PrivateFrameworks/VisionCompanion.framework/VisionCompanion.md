## VisionCompanion

> `/System/Library/PrivateFrameworks/VisionCompanion.framework/VisionCompanion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x74230` | `0x76ea4` | **`+0x2c74`** |
| `__TEXT.__oslogstring` | `0x1dc4` | `0x1f94` | **`+0x1d0`** |
| `__TEXT.__cstring` | `0x17af` | `0x18ef` | **`+0x140`** |
| `__AUTH_CONST.__const` | `0x3850` | `0x3988` | **`+0x138`** |
| `__TEXT.__eh_frame` | `0x6028` | `0x60e8` | **`+0xc0`** |
| `__AUTH.__data` | `0x358` | `0x3d8` | **`+0x80`** |
| `__TEXT.__const` | `0x3cbc` | `0x3d3c` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1dc0` | `0x1e28` | **`+0x68`** |
| `__TEXT.__swift5_reflstr` | `0x740` | `0x7a0` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0xa70` | `0xac0` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x1592` | `0x15da` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x1004` | `0x1048` | **`+0x44`** |
| `__DATA.__data` | `0xa78` | `0xab8` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0xea0` | `0xed8` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0xa04` | `0xa28` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x660` | `0x680` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x650` | `0x65c` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x110` | `0x118` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x334` | `0x338` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x3fc` | `0x400` | **`+0x4`** |

### Other Changes

```diff

-35.0.2.0.0
+35.0.5.0.0

+  - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration

-  Functions: 1961
-  Symbols:   798
-  CStrings:  295
+  Functions: 1993
+  Symbols:   809
+  CStrings:  313
Symbols:
+ _MCFeatureDiagnosticsSubmissionAllowed
+ _OBJC_CLASS_$_MCProfileConnection
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getSingletonMetadata
+ _swift_storeEnumTagSinglePayloadGeneric
+ _symbolic SS_So8NSObjectCt
+ _symbolic _____ 15VisionCompanion0B7SessionV
+ _symbolic _____ 15VisionCompanion19DiagnosticUtilitiesO
+ _symbolic _____ s5Int64V
+ _symbolic _____Sg_ABt 10Foundation4DateV
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
CStrings:
+ "%s DNU isAllowed: %{bool}d"
+ "%s cross device analytics task completed"
+ "%s fetched session: sessionCount=%lld, lastSessionDate=%s"
+ "%s fetching CompanionSession for cross-device analytics"
+ "%s received unexpected cross device analytics task %s"
+ "%s reset session"
+ "%s wipe skipped: KVS already empty"
+ "%s wipe sync failed: %@"
+ "%s wipe sync succeeded"
+ "%s wiping session keys (DNU disabled)"
+ "AnalyticsCoordinator"
+ "CompanionToDeviceActivation"
+ "CompanionToDeviceActivationThreeDays"
+ "recentlyOpenedSession_one_day"
+ "recentlyOpenedSession_seven_days"
+ "recentlyOpenedSession_thirty_days"
+ "recentlyOpenedSession_three_days"
+ "sessionsSinceLastDeviceUse"
```
