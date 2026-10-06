## CoreNavigation

> `/System/Library/PrivateFrameworks/CoreNavigation.framework/CoreNavigation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x361b44` | `0x362bb8` | **`+0x1074`** |
| `__AUTH_CONST.__const` | `0x1e778` | `0x1e898` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0xec70` | `0xed20` | **`+0xb0`** |
| `__TEXT.__const` | `0x51fa1` | `0x52011` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x1676c` | `0x167d8` | **`+0x6c`** |
| `__DATA.__common` | `0x660` | `0x670` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x238` | `0x240` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3834c` | `0x38344` | **`-0x8`** |

### Other Changes

```diff

-421.0.0.0.0
+423.0.0.0.0

-  Functions: 15512
-  Symbols:   13504
-  CStrings:  3914
+  Functions: 15563
+  Symbols:   13565
+  CStrings:  3915
Symbols:
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate10SharedCtorEv
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate10SharedDtorEv
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate16default_instanceEv
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate17default_instance_E
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate21CheckTypeAndMergeFromERKN20wireless_diagnostics6google8protobuf11MessageLiteE
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate21InitAsDefaultInstanceEv
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate23kCountryCodeFieldNumberE
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate27MergePartialFromCodedStreamEPN20wireless_diagnostics6google8protobuf2io16CodedInputStreamE
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate28kIsInDisputedAreaFieldNumberE
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate35kDateAsCfAbsoluteTimeSecFieldNumberE
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate4SwapEPS3_
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate5ClearEv
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate8CopyFromERKS3_
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate9MergeFromERKS3_
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimateC1ERKS3_
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimateC1Ev
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimateC2ERKS3_
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimateC2Ev
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimateD0Ev
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimateD1Ev
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimateD2Ev
+ __ZN14CoreNavigation3CLP8LogEntry11PrivateData27RecentLocationsFetchOptions41kRequireWirelessClientLocationFieldNumberE
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset10SharedCtorEv
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset10SharedDtorEv
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset16default_instanceEv
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset17default_instance_E
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset21CheckTypeAndMergeFromERKN20wireless_diagnostics6google8protobuf11MessageLiteE
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset21InitAsDefaultInstanceEv
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset21kEventTimeFieldNumberE
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset27MergePartialFromCodedStreamEPN20wireless_diagnostics6google8protobuf2io16CodedInputStreamE
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset4SwapEPS3_
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset5ClearEv
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset8CopyFromERKS3_
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenReset9MergeFromERKS3_
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenResetC1ERKS3_
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenResetC1Ev
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenResetC2ERKS3_
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenResetC2Ev
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenResetD0Ev
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenResetD1Ev
+ __ZN14CoreNavigation3CLP8LogEntry5Raven10RavenResetD2Ev
+ __ZN14CoreNavigation3CLP8LogEntry5Raven11RavenOutput22kResetEventFieldNumberE
+ __ZN5raven26ConvertRavenTimeToProtobufERKNS_9RavenTimeEPN14CoreNavigation3CLP8LogEntry5Raven9TimeStampE
+ __ZNK14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate11GetTypeNameEv
+ __ZNK14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate13IsInitializedEv
+ __ZNK14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate13SetCachedSizeEi
+ __ZNK14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate24SerializeWithCachedSizesEPN20wireless_diagnostics6google8protobuf2io17CodedOutputStreamE
+ __ZNK14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate3NewEv
+ __ZNK14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimate8ByteSizeEv
+ __ZNK14CoreNavigation3CLP8LogEntry5Raven10RavenReset11GetTypeNameEv
+ __ZNK14CoreNavigation3CLP8LogEntry5Raven10RavenReset13IsInitializedEv
+ __ZNK14CoreNavigation3CLP8LogEntry5Raven10RavenReset13SetCachedSizeEi
+ __ZNK14CoreNavigation3CLP8LogEntry5Raven10RavenReset24SerializeWithCachedSizesEPN20wireless_diagnostics6google8protobuf2io17CodedOutputStreamE
+ __ZNK14CoreNavigation3CLP8LogEntry5Raven10RavenReset3NewEv
+ __ZNK14CoreNavigation3CLP8LogEntry5Raven10RavenReset8ByteSizeEv
+ __ZNK5raven27GnssMeasurementPreprocessor21GetCrossCheckPositionEv
+ __ZTIN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimateE
+ __ZTIN14CoreNavigation3CLP8LogEntry5Raven10RavenResetE
+ __ZTSN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimateE
+ __ZTSN14CoreNavigation3CLP8LogEntry5Raven10RavenResetE
+ __ZTVN14CoreNavigation3CLP8LogEntry11PrivateData10RDEstimateE
+ __ZTVN14CoreNavigation3CLP8LogEntry5Raven10RavenResetE
- __ZNK5raven27GnssMeasurementPreprocessor27GetCrossCheckOrWiFiPositionEv
CStrings:
+ "#ngfg,Cross-check filter reset: WiFi age,%.1f,exceeds threshold,%.1f,now,%.3f,last_wifi,%.3f"
+ "CoreNavigation.CLP.LogEntry.PrivateData.RDEstimate"
+ "CoreNavigation.CLP.LogEntry.Raven.RavenReset"
- "#ngce,DAE_CoursePropagated,ravenTime,%.2f,estimated_deg,%.1f,dt,%.2f,delta_hdg_deg,%.2f"
- "#ngce,DAE_Raw,rt,%.4f,dt,%.4f,ax,%.4f,ay,%.4f,az,%.4f,gx,%.4f,gy,%.4f,gz,%.4f,rx,%.6f,ry,%.6f,rz,%.6f,crs,%.4f"
```
