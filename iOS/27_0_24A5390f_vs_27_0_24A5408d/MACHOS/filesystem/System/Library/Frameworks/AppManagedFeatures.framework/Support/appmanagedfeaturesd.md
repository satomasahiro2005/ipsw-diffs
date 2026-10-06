## appmanagedfeaturesd

> `/System/Library/Frameworks/AppManagedFeatures.framework/Support/appmanagedfeaturesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c7a0` | `0x7c1b4` | **`-0x5ec`** |
| `__TEXT.__eh_frame` | `0x5ef0` | `0x5d00` | **`-0x1f0`** |
| `__DATA.__data` | `0x14a8` | `0x15f0` | **`+0x148`** |
| `__DATA.__objc_const` | `0xa20` | `0xb18` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x4593` | `0x44f3` | **`-0xa0`** |
| `__TEXT.__auth_stubs` | `0x1ff0` | `0x2080` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x894` | `0x920` | **`+0x8c`** |
| `__DATA.__bss` | `0x1e80` | `0x1f00` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x13bd` | `0x143d` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x19e8` | `0x1a58` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x11c0` | `0x1220` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x517` | `0x567` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x1000` | `0x1048` | **`+0x48`** |
| `__TEXT.__const` | `0x304c` | `0x308c` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x27a` | `0x2ba` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x7b0` | `0x7e8` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x530` | `0x564` | **`+0x34`** |
| `__TEXT.__swift5_typeref` | `0xb7d` | `0xba3` | **`+0x26`** |
| `__TEXT.__cstring` | `0x12f1` | `0x12d1` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x588` | `0x5a0` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x500` | `0x4ec` | **`-0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x718` | `0x728` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x19d8` | `0x19c8` | **`-0x10`** |
| `__DATA.__common` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xf4` | `0xf8` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x74` | `0x78` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x314` | `0x318` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-46.0.7.0.0
+46.0.15.0.0

+  - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration

-  Functions: 1422
-  Symbols:   952
-  CStrings:  690
+  Functions: 1426
+  Symbols:   967
+  CStrings:  692
Symbols:
+ _$s18AppManagedFeatures0abC9ConstantsO18HeartbeatIntervalsO17heartbeatIntervalyA2EmFWC
+ _$s18AppManagedFeatures14TestingOptionsO16forceSlowCheckInyA2CmFWC
+ _$s2os0A4_log_3dso0B0__ySo0a1_B7_type_ta_SVSo03OS_a1_B0Cs12StaticStringVs7CVarArg_pdtF
+ _$s8Dispatch0A3QoSV0B6SClassO15userInteractiveyA2EmFWC
+ _$sSo17OS_dispatch_queueC8DispatchE5async5group3qos5flags7executeySo0a1_b1_F0CSg_AC0D3QoSVAC0D13WorkItemFlagsVyyXBtF
+ _$sSo9OS_os_logC0B0E7defaultABvgZ
+ _$ss10_HashTableV12previousHole6beforeAB6BucketVAF_tF
+ _$ss15ContinuousClockV7InstantVMa
+ _$ss15ContinuousClockV7InstantVs0C8ProtocolsMc
+ _$ss15ContinuousClockVMa
+ _$ss15ContinuousClockVs0B0sMc
+ _$ss15InstantProtocolP8advanced2byx8DurationQz_tFTj
+ _$ss5ClockP3now7InstantQzvgTj
+ _$ss5ClockP5sleep5until9tolerancey7InstantQz_8DurationQzSgtYaKFTj
+ _$ss5ClockP5sleep5until9tolerancey7InstantQz_8DurationQzSgtYaKFTjTu
+ _$ss5ClockPss010ContinuousA0VRszrlE10continuousADvgZ
+ _$ss5Int32VN
+ _$ss5Int32Vs7CVarArgsWP
+ _$ss7CVarArgMp
+ _OBJC_CLASS_$_MCAppManagedFeaturesBackupExclusions
+ _OBJC_CLASS_$_OS_os_log
- _$s18AppManagedFeatures0abC9ConstantsO18HeartbeatIntervalsO010productionE8IntervalyA2EmFWC
- _$s18AppManagedFeatures0abC9ConstantsO18HeartbeatIntervalsO08internalE8IntervalyA2EmFWC
- _$s18AppManagedFeatures0abC9ConstantsO18HeartbeatIntervalsO26limitedModeCheckInIntervalyA2EmFWC
- _$s18AppManagedFeatures0abC9ConstantsO23DarwinNotificationNamesO33limitedModeCheckInHandlerCompleteyA2EmFWC
- _$sSuN
- _objc_retain_x28
CStrings:
+ "BGSystemTask expiration handler fired for %{public}s; acknowledgement is left to the launch handler."
+ "CFUserNotificationClient"
+ "CFUserNotificationReceiveResponse failed: %d"
+ "DoNotBackupAppIDs"
+ "Draining orphaned limited-mode check-in task; not rescheduling"
+ "Failed to remove do-not-backup handoff: %{public}@"
+ "Failed to write do-not-backup handoff for %{public}s: %{public}@"
+ "Refusing to write do-not-backup handoff with empty bundle ID"
+ "Registering deprecated handler for limited-mode check-in task"
+ "Registering deprecated limited-mode check-in handler for migration"
+ "Removed do-not-backup handoff"
+ "Wrote do-not-backup handoff for %{public}s"
+ "_TtC19appmanagedfeaturesd25UserNotificationPresenter"
+ "com.apple.MobileSMS"
+ "contractCompleteNotification"
+ "forceSlowCheckIn testing option is set; delaying checkIn so the task can be manually expired"
+ "limitedModeNotification"
+ "removeWithError:"
+ "setAppIDs:error:"
+ "setExpirationHandler:"
- "Attempting to register background task handler for limited-mode check-in..."
- "Background limited-mode check-in handler called!"
- "Calling checkIn on ExtensionController for limited-mode check-in"
- "Disabling Siri Features"
- "Enabling Siri Features"
- "Error during limited-mode check-in: %{public}@"
- "Failed to cancel limited-mode check-in task: %{public}@"
- "Failed to receive notification response: %{public}d"
- "Failed to schedule limited-mode check-in task: %{public}@"
- "LimitedModeCheckIn"
- "Registering handler for limited-mode check-in task"
- "Scheduling a new limited-mode check-in task"
- "There was no existing limited-mode check-in task to cancel. This is ok."
- "Unexpected error canceling limited-mode check-in task: %{public}@"
- "Using the existing limited-mode check-in background task"
- "appmanagedfeaturesd-limitedmode-checkin"
- "appmanagedfeaturesd/CFUserNotification+appmanagedfeatures.swift"
- "post(type:provider:)"
```
