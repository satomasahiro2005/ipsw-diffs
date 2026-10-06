## servicesintelligenced

> `/System/Library/PrivateFrameworks/ServicesIntelligence.framework/servicesintelligenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1275c` | `0x139a0` | **`+0x1244`** |
| `__TEXT.__eh_frame` | `0xe38` | `0x1078` | **`+0x240`** |
| `__TEXT.__oslogstring` | `0xd6c` | `0xe5c` | **`+0xf0`** |
| `__TEXT.__auth_stubs` | `0xb80` | `0xc50` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x688` | `0x5c8` | **`-0xc0`** |
| `__DATA_CONST.__got` | `0x190` | `0x230` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x5c8` | `0x630` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x498` | `0x4e8` | **`+0x50`** |
| `__TEXT.__const` | `0x2ca` | `0x302` | **`+0x38`** |
| `__DATA.__data` | `0x290` | `0x2c0` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x177` | `0x193` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x54` | `0x68` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x98` | `0xac` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x1c8` | `0x1d4` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x740` | `0x748` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xe0` | `0xe8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`

### Other Changes

```diff

-1.65.0.0.0
+1.69.0.0.0

+  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 269
-  Symbols:   274
-  CStrings:  166
+  Functions: 285
+  Symbols:   309
+  CStrings:  162
Symbols:
+ _$s20ServicesIntelligence16PowerLogReporterO6DomainO8appstoreyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO6DomainO8platformyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO6DomainOMa
+ _$s20ServicesIntelligence16PowerLogReporterO6warmUpyyFZ
+ _$s20ServicesIntelligence16PowerLogReporterO7TriggerO12notifydEventyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO7TriggerO17dasBackgroundTaskyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO7TriggerOMa
+ _$s20ServicesIntelligence16PowerLogReporterO8BGTaskIDO15semanticProfileyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO8BGTaskIDO19notInBackgroundTaskyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO8BGTaskIDO4cronyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO8BGTaskIDOMa
+ _$s20ServicesIntelligence16PowerLogReporterO8TaskTypeO12cacheCleanupyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO8TaskTypeO12flushMetricsyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO8TaskTypeO13refreshConfigyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO8TaskTypeO17refreshTreatmentsyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO8TaskTypeO18initializeSystemDByA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO8TaskTypeO20refreshTopicMappingsyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO8TaskTypeO22computeSemanticProfileyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO8TaskTypeO9dataFetchyA2EmFWC
+ _$s20ServicesIntelligence16PowerLogReporterO8TaskTypeOMa
+ _$s20ServicesIntelligence18PowerLogBookkeeperC4wrap8taskType6domain9isExpired9errorCode9operationxSgAA0cD8ReporterO04TaskH0O_AL6DomainOSbyXESis5Error_pXExyYaKXEtYalF
+ _$s20ServicesIntelligence18PowerLogBookkeeperC4wrap8taskType6domain9isExpired9errorCode9operationxSgAA0cD8ReporterO04TaskH0O_AL6DomainOSbyXESis5Error_pXExyYaKXEtYalFTu
+ _$s20ServicesIntelligence18PowerLogBookkeeperC6finish10wasExpiredySb_tF
+ _$s20ServicesIntelligence18PowerLogBookkeeperC7trigger8bgTaskID6domainAcA0cD8ReporterO7TriggerO_AH06BGTaskI0OAH6DomainOtcfc
+ _$s20ServicesIntelligence18PowerLogBookkeeperC8taskOnly6domainAcA0cD8ReporterO6DomainO_tFZ
+ _$s20ServicesIntelligence18PowerLogBookkeeperCMa
+ _$s20ServicesIntelligence8PlatformO3iOSyA2CmFWC
+ _$s20ServicesIntelligence8PlatformO7currentACvgZ
+ _$s20ServicesIntelligence8PlatformOMa
+ _$s20ServicesIntelligence8PlatformOMn
+ _$s20ServicesIntelligence8PlatformOSHAAMc
+ _$s20ServicesIntelligence8PlatformOSQAAMc
+ _$s2os6LoggerV20ServicesIntelligenceE2si8categoryA2cDE8CategoryO_tFZ
+ _$s2os6LoggerV20ServicesIntelligenceE8CategoryO6daemonyA2FmFWC
+ _$s2os6LoggerV20ServicesIntelligenceE8CategoryOMa
+ _$sSH13_rawHashValue4seedS2i_tFTj
+ _$sSQ2eeoiySbx_xtFZTj
+ _$ss11_SetStorageC8allocate8capacityAByxGSi_tFZ
+ _$ss11_SetStorageCMn
+ __swift_FORCE_LOAD_$_swiftCompression
+ _swift_release_x24
+ _swift_release_x27
+ _swift_retain_x23
- _$s20ServicesIntelligence13MemoryTrackerO7measure_9operationxSS_xyYaKXEtYaKlFZ
- _$s20ServicesIntelligence13MemoryTrackerO7measure_9operationxSS_xyYaKXEtYaKlFZTu
- _$s2os6LoggerV9subsystem8categoryACSS_SStcfC
- _objc_release_x28
- _objc_retain_x25
- _swift_release_x21
- _swift_release_x28
- _swift_retain_x25
CStrings:
+ "[Daemon][listenForLaunchEvents] Proactive workloads unsupported on this platform; registering no background tasks"
+ "[Daemon][run] Proactive workloads unsupported on this platform; skipping startup sync (XPC stays active)"
+ "executeSemanticProfileWorkload(bookkeeper:)"
- ".computeSemanticProfile"
- ".refreshDomainData"
- ".refreshTopicMappingsViaPIR"
- "com.apple.ServicesIntelligence"
- "executeSemanticProfileWorkload(label:)"
- "semantic-profile"
- "semantic-profile-postinstall"
```
