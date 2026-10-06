## enhancedloggingd

> `/usr/libexec/enhancedloggingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb417c` | `0xb5388` | **`+0x120c`** |
| `__TEXT.__auth_stubs` | `0x2270` | `0x23a0` | **`+0x130`** |
| `__DATA.__objc_const` | `0x25f0` | `0x2718` | **`+0x128`** |
| `__DATA_CONST.__const` | `0xa558` | `0xa450` | **`-0x108`** |
| `__DATA_CONST.__got` | `0x9d0` | `0xa78` | **`+0xa8`** |
| `__TEXT.__objc_methname` | `0x4b5d` | `0x4bfd` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x3380` | `0x3420` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x1148` | `0x11e0` | **`+0x98`** |
| `__TEXT.__swift5_typeref` | `0x1d8b` | `0x1e19` | **`+0x8e`** |
| `__TEXT.__objc_methlist` | `0x13ac` | `0x1434` | **`+0x88`** |
| `__DATA.__data` | `0x2b58` | `0x2bb8` | **`+0x60`** |
| `__TEXT.__const` | `0x57fc` | `0x583c` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x2e04` | `0x2dc4` | **`-0x40`** |
| `__DATA.__objc_selrefs` | `0x1010` | `0x1040` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2fcd` | `0x2ffd` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x5f0` | `0x618` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1ce8` | `0x1d10` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x178c` | `0x17b0` | **`+0x24`** |
| `__DATA_CONST.__cfstring` | `0x580` | `0x5a0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1551` | `0x1571` | **`+0x20`** |
| `__DATA.__objc_data` | `0x8c8` | `0x8d8` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x120b` | `0x11fb` | **`-0x10`** |
| `__DATA.__common` | `0x208` | `0x210` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x37c` | `0x384` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb4` | `0xb8` | **`+0x4`** |
| `__TEXT.__constg_swiftt` | `0x11cc` | `0x11c8` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-267.2.3.0.0
+277.40.4.0.0

+  - /System/Library/Frameworks/Network.framework/Network

+  - /usr/lib/swift/libswiftAccelerate.dylib

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 3017
-  Symbols:   984
-  CStrings:  1410
+  Functions: 3018
+  Symbols:   1031
+  CStrings:  1425
Symbols:
+ _$s10Foundation4DateV17timeIntervalSinceySdACF
+ _$s10Foundation4DateV36_unconditionallyBridgeFromObjectiveCyACSo6NSDateCSgFZ
+ _$s10Foundation4DateVACycfC
+ _$s10Foundation4DateVSQAAMc
+ _$s10Foundation4DateVs21_ObjectiveCBridgeableAAMc
+ _$s15EnhancedLogging0aB14AnalyticsEventO11InteractionO11interactiveyA2EmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO11InteractionO8headlessyA2EmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO11InteractionOMa
+ _$s15EnhancedLogging0aB14AnalyticsEventO12uploadFailedyACSd_AC16NetworkInterfaceOSSSitcACmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO15uploadCompletedyACSd_AC16NetworkInterfaceOSis5Int64VtcACmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO16NetworkInterfaceO4wifiyA2EmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO16NetworkInterfaceO5wiredyA2EmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO16NetworkInterfaceO7unknownyA2EmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO16NetworkInterfaceO8cellularyA2EmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO16NetworkInterfaceOMa
+ _$s15EnhancedLogging0aB14AnalyticsEventO16NetworkInterfaceOMn
+ _$s15EnhancedLogging0aB14AnalyticsEventO16sessionCancelledyA2C18CancellationReasonO_tcACmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO17collectionStartedyA2C11InteractionO_tcACmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO18CancellationReasonO4useryA2EmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO18CancellationReasonO6remoteyA2EmFWC
+ _$s15EnhancedLogging0aB14AnalyticsEventO18CancellationReasonOMa
+ _$s15EnhancedLogging0aB14AnalyticsEventO4sendyyF
+ _$s15EnhancedLogging0aB14AnalyticsEventOMa
+ _$s15EnhancedLogging12TargetDeviceV0D4TypeO11isSatisfied2bySbAE_tF
+ _$s15EnhancedLogging22DeviceStringConstraintVAA0cE0AAWP
+ _$s15EnhancedLogging22DeviceStringConstraintVMn
+ _$s15EnhancedLogging27DeviceConditionalConstraintV11isSatisfied2bySbAA06TargetC0V_tF
+ _$s15EnhancedLogging27DeviceConditionalConstraintVAA0cE0AAWP
+ _$s15Synchronization5MutexVMa
+ _$s15Synchronization5_CellVMn
+ _$s7Network11NWInterfaceV13InterfaceTypeO13wiredEthernetyA2EmFWC
+ _$s7Network11NWInterfaceV13InterfaceTypeO4wifiyA2EmFWC
+ _$s7Network11NWInterfaceV13InterfaceTypeO8cellularyA2EmFWC
+ _$s7Network11NWInterfaceV13InterfaceTypeOMa
+ _$s7Network13NWPathMonitorC17pathUpdateHandleryAA0B0VcSgvs
+ _$s7Network13NWPathMonitorC5start5queueySo012OS_dispatch_E0C_tF
+ _$s7Network13NWPathMonitorCACycfc
+ _$s7Network13NWPathMonitorCMa
+ _$s7Network13NWPathMonitorCMn
+ _$s7Network6NWPathV17usesInterfaceTypeySbAA11NWInterfaceV0dE0OF
+ _$s7Network6NWPathV6StatusO2eeoiySbAE_AEtFZ
+ _$s7Network6NWPathV6StatusO9satisfiedyA2EmFWC
+ _$s7Network6NWPathV6StatusOMa
+ _$s7Network6NWPathV6statusAC6StatusOvg
+ _$s7Network6NWPathVMa
+ _$s7Network6NWPathVMn
+ _$sSl15EnhancedLoggingAA16DeviceConstraint7ElementRpzrlE12areSatisfied2bySbAA06TargetC0V_tF
+ _$ss21_ObjectiveCBridgeableP024_conditionallyBridgeFromA1C_6resultSb01_A5CTypeQz_xSgztFZTj
+ _AKSeedBuildHeaderKey
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftIntents
+ _objc_retain_x9
+ _swift_retain_x1
- _$s15EnhancedLogging12TargetDeviceV0D4TypeO10compatible4withSbAE_tF
- _$s15EnhancedLogging12TargetDeviceV10deviceTypeAC0dF0Ovg
- _$s15EnhancedLogging22DeviceStringConstraintV10compatible4withSbAA06TargetC0V_tF
- _$s15EnhancedLogging27DeviceConditionalConstraintV10compatible4withSbAA06TargetC0V_tF
- _$s15EnhancedLogging27DeviceConditionalConstraintV9satisfies7devices13configurationSbSayAA06TargetC0VG_SayACGtFZ
- _AnalyticsSendEventLazy
CStrings:
+ "@\"NSDate\""
+ "@\"NSDate\"16@0:8"
+ "FOLLOWUP_UPLOADING_BODY"
+ "FOLLOWUP_UPLOADING_TITLE"
+ "T@\"NSDate\",&,V_uploadStartedAt"
+ "T@\"NSDate\",N,C"
+ "T@\"NSDate\",R,N"
+ "Tq,N,R"
+ "_uploadStartedAt"
+ "com.apple.enhancedloggingd.file-uploader-path-monitor"
+ "date"
+ "latestPath"
+ "pathMonitor"
+ "setUploadStartedAt:"
+ "shouldHideSeedBuildHeader"
+ "uploadStartedAt"
+ "uploadedByteCount"
+ "uploadedFileCount"
- "@\"NSDictionary\"8@?0"
- "com.apple.EnhancedLogging.CollectionStarted"
- "com.apple.EnhancedLogging.SessionCancelled"
```
