## ReportCrash

> `/System/Library/CoreServices/ReportCrash`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4960c` | `0x4def4` | **`+0x48e8`** |
| `__DATA.__bss` | `0xae0` | `0x1560` | **`+0xa80`** |
| `__TEXT.__const` | `0xbe0` | `0x1100` | **`+0x520`** |
| `__TEXT.__objc_methname` | `0x4432` | `0x4710` | **`+0x2de`** |
| `__DATA_CONST.__const` | `0x1678` | `0x1950` | **`+0x2d8`** |
| `__TEXT.__eh_frame` | `0x438` | `0x638` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0x2b81` | `0x2d11` | **`+0x190`** |
| `__TEXT.__swift5_fieldmd` | `0x59c` | `0x704` | **`+0x168`** |
| `__TEXT.__unwind_info` | `0xb28` | `0xc50` | **`+0x128`** |
| `__DATA.__data` | `0x8f0` | `0x9f8` | **`+0x108`** |
| `__TEXT.__swift5_typeref` | `0x4ec` | `0x5e4` | **`+0xf8`** |
| `__TEXT.__constg_swiftt` | `0x3a4` | `0x474` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x5b1b` | `0x5beb` | **`+0xd0`** |
| `__DATA.__objc_const` | `0x25d0` | `0x2680` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x440` | `0x4f0` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x3f80` | `0x4020` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0xf30` | `0xfb8` | **`+0x88`** |
| `__DATA.__objc_selrefs` | `0x10f0` | `0x1160` | **`+0x70`** |
| `__TEXT.__swift5_proto` | `0x48` | `0x9c` | **`+0x54`** |
| `__TEXT.__objc_methtype` | `0xb2e` | `0xb7e` | **`+0x50`** |
| `__DATA_CONST.__objc_arrayobj` | `0x1e0` | `0x228` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x24f0` | `0x2530` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x1288` | `0x12a8` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x7dc0` | `0x7da0` | **`-0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x390` | `0x3a8` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x38` | `0x50` | **`+0x18`** |
| `__DATA.__objc_data` | `0x908` | `0x918` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x328` | `0x338` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x280` | `0x288` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x578` | `0x580` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
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

-  Functions: 974
-  Symbols:   865
-  CStrings:  2250
+  Functions: 1078
+  Symbols:   869
+  CStrings:  2284
Symbols:
+ _$sBbWV
+ _$ss22KeyedDecodingContainerV6decode_6forKeyS2Sm_xtKF
+ _$ss22KeyedDecodingContainerV6decode_6forKeyqd__qd__m_xtKSeRd__lF
+ _$ss22KeyedEncodingContainerV6encode_6forKeyySS_xtKF
+ _$ss22KeyedEncodingContainerV6encode_6forKeyyqd___xtKSERd__lF
+ _OBJC_CLASS_$_NSJSONSerialization
+ _fclose
+ _fdopen
+ _pipe
+ _posix_spawn
+ _posix_spawn_file_actions_addclose
+ _posix_spawn_file_actions_adddup2
+ _posix_spawn_file_actions_destroy
+ _posix_spawn_file_actions_init
+ _waitpid
- _$sSa10FoundationE34_conditionallyBridgeFromObjectiveC_6resultSbSo7NSArrayC_SayxGSgztFZ
- _$syXlN
- _IOPSCopyExternalPowerAdapterDetails
- _IOPSCopyPowerSourcesInfo
- _IOPSCopyPowerSourcesList
- _IOPSGetPowerSourceDescription
- ___stdoutp
- _fflush
- _pclose
- _popen
- _swift_unknownObjectRelease_n
CStrings:
+ "%{public}s: not a MetricKit client at dispatch time"
+ "AppleRawExternalConnected"
+ "AppleSmartBattery"
+ "B60@0:8@16i24i28B32^@36^@44^@52"
+ "B76@0:8Q16Q24i32^i36^@44^i52^i60^B68"
+ "Could not read malloc_num_zones at 0x%llx (got %lu bytes, expected %zu)"
+ "ExternalConnected"
+ "Failed to enumerate AppleSmartBattery services"
+ "Failed to read AppleSmartBattery properties"
+ "MetricKit unavailable, skipping ExcResource dispatch"
+ "MetricKit unavailable, skipping ExcResource pre-extraction"
+ "No AppleSmartBattery service found"
+ "Sending ExcResource to MetricKit for %{public}s"
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
+ "_disallowInProcessSyslogQuery"
+ "_prefetchedFilteredLog"
+ "binaryUUIDString"
+ "buildFilteredSyslogQueryForProcName:procID:signal:isDriverkit:outPids:outSenders:outPredicates:"
+ "callStackPayload"
+ "carrierInstall"
+ "dataWithJSONObject:options:error:"
+ "disallowInProcessSyslogQuery"
+ "extractCrashIdentityFromKcdata:size:machException:outPid:outProcName:outSignal:outExceptionType:outIsCorpseFork:"
+ "failed to read syslog"
+ "getSyslogAtCaptureTime:forPids:andOptionalSenders:additionalPredicates:"
+ "is64Bit"
+ "ktriage_info"
+ "length > 0"
+ "metricKitClientIdentifier"
+ "ppid"
+ "prefetchedFilteredLog"
+ "prefetched_filtered_log"
+ "rc_prefetch_filtered_syslog: %lu lines for %{public}@[%d]"
+ "rc_prefetch_filtered_syslog: JSON serialization failed: %{public}@"
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
