## ReplicatorEngine

> `/System/Library/PrivateFrameworks/ReplicatorEngine.framework/ReplicatorEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b1a80` | `0x1b8420` | **`+0x69a0`** |
| `__TEXT.__oslogstring` | `0x7f3d` | `0x846d` | **`+0x530`** |
| `__AUTH_CONST.__const` | `0xab58` | `0xae30` | **`+0x2d8`** |
| `__AUTH.__data` | `0x4bc8` | `0x4df0` | **`+0x228`** |
| `__TEXT.__cstring` | `0x1afa` | `0x1c8a` | **`+0x190`** |
| `__TEXT.__swift5_fieldmd` | `0x34fc` | `0x366c` | **`+0x170`** |
| `__TEXT.__constg_swiftt` | `0x421c` | `0x435c` | **`+0x140`** |
| `__TEXT.__const` | `0xbbf8` | `0xbd18` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x44a0` | `0x4590` | **`+0xf0`** |
| `__TEXT.__swift5_reflstr` | `0x29cf` | `0x2aad` | **`+0xde`** |
| `__DATA.__data` | `0x2b68` | `0x2c28` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x3b9a` | `0x3c2e` | **`+0x94`** |
| `__AUTH_CONST.__auth_got` | `0x1630` | `0x16b0` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0x4908` | `0x4970` | **`+0x68`** |
| `__TEXT.__swift5_capture` | `0x25c8` | `0x2610` | **`+0x48`** |
| `__TEXT.__swift5_types` | `0x39c` | `0x3bc` | **`+0x20`** |
| `__DATA.__common` | `0x1a0` | `0x1b8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x728` | `0x738` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x80` | `0x70` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x40` | `0x38` | **`-0x8`** |

### Other Changes

```diff

-176.0.0.0.0
+176.2.2.0.0

-  Functions: 6824
-  Symbols:   1937
-  CStrings:  668
+  Functions: 6935
+  Symbols:   1962
+  CStrings:  689
Symbols:
+ _BSTimerIntervalMax
+ _BSTimerIntervalMin
+ _OBJC_CLASS_$_OS_os_log
+ ___swift_assignWithCopy_strong
+ ___swift_assignWithTake_strong
+ ___swift_closure_destructor.180Tm
+ ___swift_closure_destructor.38Tm
+ ___swift_closure_destructor.507Tm
+ ___swift_closure_destructor.513Tm
+ ___swift_closure_destructor.529Tm
+ ___swift_closure_destructor.546Tm
+ ___swift_closure_destructor.597Tm
+ ___swift_closure_destructor.641Tm
+ ___swift_closure_destructor.647Tm
+ ___swift_closure_destructor.754Tm
+ ___swift_destroy_strong
+ ___swift_initWithCopy_strong
+ ___swift_memcpy73_8
+ __os_signpost_emit_with_name_impl
+ _symbolic SDySS_____G 16ReplicatorEngine9SignpostsV13IntervalTokenV
+ _symbolic SDy_____SDy__________GG 10Foundation4UUIDV 16ReplicatorEngine4ZoneC2IDC AD0C0C0E10SyncCounts33_F10836812482E990E1DEB34C756D81E7LLV
+ _symbolic So9OS_os_logC
+ _symbolic _____ 16ReplicatorEngine0A0C14ZoneSyncCounts33_F10836812482E990E1DEB34C756D81E7LLV
+ _symbolic _____ 16ReplicatorEngine9SignpostsV
+ _symbolic _____ 16ReplicatorEngine9SignpostsV13EventSignpostV
+ _symbolic _____ 16ReplicatorEngine9SignpostsV13IntervalTokenV
+ _symbolic _____ 16ReplicatorEngine9SignpostsV14RecordSignpostV
+ _symbolic _____ 16ReplicatorEngine9SignpostsV14RecordSignpostV8MetadataV
+ _symbolic _____ 16ReplicatorEngine9SignpostsV17HandshakeSignpostV
+ _symbolic _____ 16ReplicatorEngine9SignpostsV8Interval33_5B4911F68C5A543F2D093C6184E1ADE8LLV
+ _symbolic _____ 2os12OSSignposterV
+ _symbolic _____ 2os23OSSignpostIntervalStateC
+ _symbolic _____ s12StaticStringV
+ _symbolic ______SDy__________Gt 10Foundation4UUIDV 16ReplicatorEngine4ZoneC2IDC AD0C0C0E10SyncCounts33_F10836812482E990E1DEB34C756D81E7LLV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 16ReplicatorEngine9SignpostsV13IntervalTokenV
+ _symbolic _____y_____SDy__________GG s18_DictionaryStorageC 10Foundation4UUIDV 16ReplicatorEngine4ZoneC2IDC AF0E0C0G10SyncCounts33_F10836812482E990E1DEB34C756D81E7LLV
+ _symbolic _____y__________G s18_DictionaryStorageC 16ReplicatorEngine4ZoneC2IDC AC0C0C0E10SyncCounts33_F10836812482E990E1DEB34C756D81E7LLV
+ _type_layout_string 16ReplicatorEngine0A0C14ZoneSyncCounts33_F10836812482E990E1DEB34C756D81E7LLV
+ _type_layout_string 16ReplicatorEngine9SignpostsV13IntervalTokenV
+ _type_layout_string 16ReplicatorEngine9SignpostsV14RecordSignpostV8MetadataV
- __OBJC_$_PROTOCOL_REFS_OS_dispatch_source_timer
- __OBJC_LABEL_PROTOCOL_$_OS_dispatch_source_timer
- __OBJC_PROTOCOL_$_OS_dispatch_source_timer
- ___swift_closure_destructor.31Tm
- ___swift_closure_destructor.499Tm
- ___swift_closure_destructor.505Tm
- ___swift_closure_destructor.521Tm
- ___swift_closure_destructor.538Tm
- ___swift_closure_destructor.588Tm
- ___swift_closure_destructor.632Tm
- ___swift_closure_destructor.638Tm
- ___swift_closure_destructor.745Tm
- _flat unique So24OS_dispatch_source_timer_p
- _symbolic Say_____G So18OS_dispatch_sourceC8DispatchE10TimerFlagsV
- _symbolic ______pSg So24OS_dispatch_source_timerP
CStrings:
+ "%{public}s <RemoteDevice>=%{public}s, <RecordID>=%{public}s, <Zone>=%{name=Zone, signpost.telemetry:string1,public}s, <Client>=%{name=Client, signpost.telemetry:string2,public}s, <DataSize>=%{name=DataSize, signpost.telemetry:number1,public}ld, <error.present>=%{name=error.present, signpost.telemetry:number2,public}s, enableTelemetry=YES"
+ "%{public}s Abandoning handshake request because replicator is disabled"
+ "%{public}s: Data source does not exist for validation"
+ "(%{public}s) Abandoning handshake complete because handshaking is not permitted"
+ "(%{public}s) Abandoning handshake request because handshaking is not permitted"
+ "(%{public}s) Cannot handshake because replicator is disabled: %{public}s"
+ "(%{public}s) Cannot handshake with a device that is unknown to the sync service: %{public}s"
+ "(%{public}s) Cannot handshake with a non-me device: %{public}s"
+ "(%{public}s) Device %{public}s is being treated as the me device"
+ "(%{public}s) [Send Response] Abandoning handshake response because handshaking is not permitted"
+ "All records are valid in zone %{public}s"
+ "Applied record"
+ "Cannot handshake because of condition monitor"
+ "Cannot handshake because scheduler is not started"
+ "Completed handshake <RemoteDevice>=%{public}s, <error.present>=%{name=error.present, signpost.telemetry:number1,public}s, enableTelemetry=YES"
+ "Corrupted %{public}ld invalid remote records in zone %{public}s"
+ "Device unavailable"
+ "HandshakeInterval"
+ "RecordApplyInterval"
+ "RecordSyncInterval"
+ "Removed %{public}ld invalid local records in zone %{public}s"
+ "Repaired %{public}ld invalid remote records in zone %{public}s"
+ "Synced record"
+ "Zone sync summary <RemoteDevice>=%{public}s, <Zone>=%{name=Zone, signpost.telemetry:string1,public}s, <Client>=%{name=Client, signpost.telemetry:string2,public}s, <synced>=%{name=synced, signpost.telemetry:number1,public}ld, <applied>=%{name=applied, signpost.telemetry:number2,public}ld, <complete>=%{bool,public}d, enableTelemetry=YES"
+ "ZoneSyncSummary"
+ "[Error] Interval already ended"
+ "com.apple.ReplicatorEngine.BasicTimer"
+ "com.apple.ReplicatorEngine.Replicator.validation"
+ "com.apple.ReplicatorEngine.Watchdog"
+ "enableTelemetry=YES"
+ "signpostsSummary"
- "%{public}s skipping handshake request, replicator is disabled"
- "%{public}s: Data source does not exist"
- "(%{public}s) Abandoning handshake request because replicator is disabled"
- "(%{public}s) [Send Response] Abandoning handshake response because replicator is disabled"
- "All records are valid"
- "Cannot handshake with discovered device: %{public}s, sync service does not know about it yet"
- "Corrupted %ld invalid remote records"
- "Handshake scheduler can handshake: %{bool,public}d"
- "Removed %ld invalid local records"
- "Repaired %ld invalid remote records"
```
