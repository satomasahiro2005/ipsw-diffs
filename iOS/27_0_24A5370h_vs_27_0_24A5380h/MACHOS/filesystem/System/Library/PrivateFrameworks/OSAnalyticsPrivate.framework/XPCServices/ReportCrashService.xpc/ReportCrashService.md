## ReportCrashService

> `/System/Library/PrivateFrameworks/OSAnalyticsPrivate.framework/XPCServices/ReportCrashService.xpc/ReportCrashService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fa20` | `0x53218` | **`+0x37f8`** |
| `__DATA.__bss` | `0xab0` | `0x1530` | **`+0xa80`** |
| `__TEXT.__const` | `0xde0` | `0x12f0` | **`+0x510`** |
| `__DATA_CONST.__const` | `0x16c0` | `0x1998` | **`+0x2d8`** |
| `__TEXT.__objc_methname` | `0x4563` | `0x47fd` | **`+0x29a`** |
| `__TEXT.__eh_frame` | `0x810` | `0xa10` | **`+0x200`** |
| `__TEXT.__swift5_fieldmd` | `0x6d8` | `0x840` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0x330e` | `0x346e` | **`+0x160`** |
| `__DATA.__data` | `0xbc0` | `0xcd0` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0xbd8` | `0xcd8` | **`+0x100`** |
| `__TEXT.__swift5_typeref` | `0x666` | `0x75e` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x59d5` | `0x5ab5` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x428` | `0x4e8` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x2b60` | `0x2c10` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x4ef` | `0x597` | **`+0xa8`** |
| `__TEXT.__objc_stubs` | `0x3d40` | `0x3de0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0xfac` | `0x1034` | **`+0x88`** |
| `__DATA.__objc_selrefs` | `0x10e8` | `0x1148` | **`+0x60`** |
| `__TEXT.__swift5_proto` | `0x48` | `0x9c` | **`+0x54`** |
| `__TEXT.__objc_methtype` | `0xd21` | `0xd71` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x26d0` | `0x2710` | **`+0x40`** |
| `__DATA_CONST.__objc_arrayobj` | `0x1e0` | `0x210` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1378` | `0x1398` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x4c` | `0x64` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x390` | `0x3a0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x278` | `0x280` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x358` | `0x360` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x598` | `0x5a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1056.0.3.0.0
+1056.0.12.0.0

-  Functions: 1027
-  Symbols:   624
-  CStrings:  2284
+  Functions: 1128
+  Symbols:   623
+  CStrings:  2316
Symbols:
+ _IOPMPSRawExternalConnectedKey
+ _OBJC_CLASS_$_NSJSONSerialization
+ _fclose
+ _fdopen
+ _pipe
+ _posix_spawn
+ _posix_spawn_file_actions_addclose
+ _posix_spawn_file_actions_adddup2
+ _posix_spawn_file_actions_destroy
+ _posix_spawn_file_actions_init
+ _runDiagToolWithArg
+ _waitpid
- _IOPSCopyExternalPowerAdapterDetails
- _IOPSCopyPowerSourcesInfo
- _IOPSCopyPowerSourcesList
- _IOPSGetPowerSourceDescription
- _IOPSInternalType
- _IOPSIsChargingKey
- _IOPSRawExternalConnectedKey
- _IOPSTransportTypeKey
- ___stdoutp
- _fflush
- _pclose
- _popen
- _swift_unknownObjectRelease_n
CStrings:
+ "AppleRawExternalConnected"
+ "AppleSmartBattery"
+ "B60@0:8@16i24i28B32^@36^@44^@52"
+ "B76@0:8Q16Q24i32^i36^@44^i52^i60^B68"
+ "Could not read malloc_num_zones at 0x%llx (got %lu bytes, expected %zu)"
+ "ExternalConnected"
+ "Failed to enumerate AppleSmartBattery services"
+ "Failed to read AppleSmartBattery properties"
+ "JSONObjectWithData:options:error:"
+ "MetricKit unavailable, skipping ExcResource pre-extraction"
+ "No AppleSmartBattery service found"
+ "Prefetched filteredLog contained non-string element; ignoring"
+ "Prefetched filteredLog payload was not an array (err=%{public}@); ignoring"
+ "Skipping crash reporter extension for restrictive sandbox profile: %{public}@"
+ "T@\"NSArray\",C,N,V_prefetchedFilteredLog"
+ "T@\"NSString\",N,R"
+ "T@\"NSString\",R,N,V_ktriage_info"
+ "TB,N,V_disallowInProcessSyslogQuery"
+ "TB,R,N,V_is64Bit"
+ "Ti,R,N,V_cpuType"
+ "Ti,R,N,V_ppid"
+ "Unable to allocate argv for '%s'"
+ "Unable to create pipe for '%s' (errno %d)"
+ "Unable to spawn '%s' (error %d)"
+ "Using daemon-prefetched filteredLog (%lu lines)"
+ "_disallowInProcessSyslogQuery"
+ "_prefetchedFilteredLog"
+ "binaryUUIDString"
+ "buildFilteredSyslogQueryForProcName:procID:signal:isDriverkit:outPids:outSenders:outPredicates:"
+ "callStackPayload"
+ "container"
+ "disallowInProcessSyslogQuery"
+ "extractCrashIdentityFromKcdata:size:machException:outPid:outProcName:outSignal:outExceptionType:outIsCorpseFork:"
+ "failed to read syslog"
+ "is64Bit"
+ "ktriage_info"
+ "length > 0"
+ "metricKitClientIdentifier"
+ "ppid"
+ "prefetchedFilteredLog"
+ "prefetched_filtered_log"
+ "setDisallowInProcessSyslogQuery:"
+ "setPrefetchedFilteredLog:"
- "\nError closing pipe of '%s' (errno %d)"
- "%s %@"
- "Failed to get power source description for index %ld"
- "Failed to get power sources info"
- "Failed to get power sources list"
- "Internal"
- "Is Charging"
- "No power sources found"
- "Raw External Connected"
- "Transport Type"
- "Unable to open '%s' (errno %d)"
```
