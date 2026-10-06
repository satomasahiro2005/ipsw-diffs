## SoftwareUpdateUIFoundation

> `/System/Library/PrivateFrameworks/SoftwareUpdateUIFoundation.framework/SoftwareUpdateUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2ff0` | `0xaaa2c` | **`+0x7a3c`** |
| `__AUTH_CONST.__objc_const` | `0x6010` | `0x69c0` | **`+0x9b0`** |
| `__TEXT.__oslogstring` | `0x9f67` | `0xa757` | **`+0x7f0`** |
| `__TEXT.__cstring` | `0x660e` | `0x6a48` | **`+0x43a`** |
| `__TEXT.__objc_methlist` | `0x1f74` | `0x22cc` | **`+0x358`** |
| `__AUTH_CONST.__cfstring` | `0x3b80` | `0x3e00` | **`+0x280`** |
| `__DATA_CONST.__objc_selrefs` | `0x1360` | `0x1568` | **`+0x208`** |
| `__TEXT.__gcc_except_tab` | `0x21ec` | `0x2394` | **`+0x1a8`** |
| `__AUTH.__objc_data` | `0xeb0` | `0xff0` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x22a8` | `0x23a8` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x1120` | `0x11d8` | **`+0xb8`** |
| `__DATA.__objc_ivar` | `0x254` | `0x300` | **`+0xac`** |
| `__TEXT.__eh_frame` | `0xba8` | `0xb00` | **`-0xa8`** |
| `__AUTH_CONST.__auth_got` | `0x948` | `0x8f8` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x428` | `0x458` | **`+0x30`** |
| `__DATA.__bss` | `0x3608` | `0x35e0` | **`-0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x178` | `0x198` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0xf8` | `0x110` | **`+0x18`** |

### Other Changes

```diff

-772.0.3.0.0
+772.0.8.0.0

-  Functions: 1990
-  Symbols:   2128
-  CStrings:  905
+  Functions: 2071
+  Symbols:   2282
+  CStrings:  948
Symbols:
+ +[SUUIUserDefaults(Foundation) scanResultsCacheRefreshForcesScanEntry]
+ +[SUUIUserDefaults(Foundation) scanResultsCacheRefreshIntervalOverrideEntry]
+ -[SUUIDeviceDescriptorRef .cxx_destruct]
+ -[SUUIDeviceDescriptorRef buildVersion]
+ -[SUUIDeviceDescriptorRef copyWithZone:]
+ -[SUUIDeviceDescriptorRef description]
+ -[SUUIDeviceDescriptorRef deviceFamilyName]
+ -[SUUIDeviceDescriptorRef hasWapiCapability]
+ -[SUUIDeviceDescriptorRef hash]
+ -[SUUIDeviceDescriptorRef initWithOSName:productFamilyName:productVersion:buildVersion:productVersionExtra:deviceFamilyName:isInternalBuild:isRootsInstalled:isSeedBuild:hasWapiCapability:]
+ -[SUUIDeviceDescriptorRef isEqual:]
+ -[SUUIDeviceDescriptorRef isInternalBuild]
+ -[SUUIDeviceDescriptorRef isRootsInstalled]
+ -[SUUIDeviceDescriptorRef isSeedBuild]
+ -[SUUIDeviceDescriptorRef osName]
+ -[SUUIDeviceDescriptorRef productFamilyName]
+ -[SUUIDeviceDescriptorRef productVersionExtra]
+ -[SUUIDeviceDescriptorRef productVersion]
+ -[SUUIStatefulUIManager checkForAvailableUpdatesWithRetriesCount:forceScan:]
+ -[SUUIStatefulUIManagerFSMParam description]
+ -[SUUIStatefulUIManagerFSMParam initWithRetriesCount:forceScan:]
+ -[SUUITaskGroup .cxx_destruct]
+ -[SUUITaskGroup _armSafetyDeadline]
+ -[SUUITaskGroup _armWaitDeadline]
+ -[SUUITaskGroup _cancelSafetyDeadline]
+ -[SUUITaskGroup _cancelWaitDeadline]
+ -[SUUITaskGroup _dispatchEntry:]
+ -[SUUITaskGroup _errorForException:taskNamed:]
+ -[SUUITaskGroup _resolveToken:result:error:]
+ -[SUUITaskGroup _settleWithOutcome:]
+ -[SUUITaskGroup _timeoutError]
+ -[SUUITaskGroup _unfinishedNames]
+ -[SUUITaskGroup addTaskNamed:context:task:]
+ -[SUUITaskGroup addTaskNamed:task:]
+ -[SUUITaskGroup cancel]
+ -[SUUITaskGroup description]
+ -[SUUITaskGroup initWithIdentifier:timeout:policy:]
+ -[SUUITaskGroup initWithIdentifier:timeout:policy:completionQueue:]
+ -[SUUITaskGroup setStartToJoinSafetyTimeout:]
+ -[SUUITaskGroup setState:]
+ -[SUUITaskGroup startToJoinSafetyTimeout]
+ -[SUUITaskGroup startWithCompletion:]
+ -[SUUITaskGroup start]
+ -[SUUITaskGroup state]
+ -[SUUITaskGroup waitForResult:]
+ -[SUUITaskGroupEntry .cxx_destruct]
+ -[SUUITaskGroupEntry block]
+ -[SUUITaskGroupEntry context]
+ -[SUUITaskGroupEntry dispatched]
+ -[SUUITaskGroupEntry name]
+ -[SUUITaskGroupEntry setBlock:]
+ -[SUUITaskGroupEntry setContext:]
+ -[SUUITaskGroupEntry setDispatched:]
+ -[SUUITaskGroupEntry setName:]
+ -[SUUITaskGroupEntry setToken:]
+ -[SUUITaskGroupEntry token]
+ -[SUUITaskGroupResult .cxx_destruct]
+ -[SUUITaskGroupResult description]
+ -[SUUITaskGroupResult finishedTaskNames]
+ -[SUUITaskGroupResult firstError]
+ -[SUUITaskGroupResult initWithOutcome:firstError:resultsByName:finishedNames:unfinishedNames:]
+ -[SUUITaskGroupResult outcome]
+ -[SUUITaskGroupResult resultForTaskNamed:]
+ -[SUUITaskGroupResult unfinishedTaskNames]
+ -[SUUIUserDefaults(Foundation) scanResultsCacheRefreshForcesScan:]
+ -[SUUIUserDefaults(Foundation) scanResultsCacheRefreshForcesScan]
+ -[SUUIUserDefaults(Foundation) scanResultsCacheRefreshIntervalOverride:]
+ -[SUUIUserDefaults(Foundation) scanResultsCacheRefreshIntervalOverride]
+ GCC_except_table140
+ GCC_except_table151
+ GCC_except_table159
+ GCC_except_table161
+ GCC_except_table164
+ GCC_except_table166
+ GCC_except_table171
+ GCC_except_table179
+ GCC_except_table184
+ GCC_except_table190
+ GCC_except_table192
+ GCC_except_table197
+ GCC_except_table207
+ GCC_except_table210
+ GCC_except_table213
+ GCC_except_table220
+ GCC_except_table228
+ GCC_except_table230
+ GCC_except_table234
+ GCC_except_table241
+ GCC_except_table249
+ GCC_except_table252
+ GCC_except_table254
+ GCC_except_table262
+ GCC_except_table265
+ GCC_except_table271
+ GCC_except_table32
+ GCC_except_table335
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_SUUIDeviceDescriptorRef
+ _OBJC_CLASS_$_SUUITaskGroup
+ _OBJC_CLASS_$_SUUITaskGroupEntry
+ _OBJC_CLASS_$_SUUITaskGroupResult
+ _OBJC_EHTYPE_$_NSException
+ _OBJC_IVAR_$_SUUIDeviceDescriptorRef._buildVersion
+ _OBJC_IVAR_$_SUUIDeviceDescriptorRef._deviceFamilyName
+ _OBJC_IVAR_$_SUUIDeviceDescriptorRef._hasWapiCapability
+ _OBJC_IVAR_$_SUUIDeviceDescriptorRef._isInternalBuild
+ _OBJC_IVAR_$_SUUIDeviceDescriptorRef._isRootsInstalled
+ _OBJC_IVAR_$_SUUIDeviceDescriptorRef._isSeedBuild
+ _OBJC_IVAR_$_SUUIDeviceDescriptorRef._osName
+ _OBJC_IVAR_$_SUUIDeviceDescriptorRef._productFamilyName
+ _OBJC_IVAR_$_SUUIDeviceDescriptorRef._productVersion
+ _OBJC_IVAR_$_SUUIDeviceDescriptorRef._productVersionExtra
+ _OBJC_IVAR_$_SUUITaskGroup._completionQueue
+ _OBJC_IVAR_$_SUUITaskGroup._completions
+ _OBJC_IVAR_$_SUUITaskGroup._entries
+ _OBJC_IVAR_$_SUUITaskGroup._execQueue
+ _OBJC_IVAR_$_SUUITaskGroup._finishedNames
+ _OBJC_IVAR_$_SUUITaskGroup._firstError
+ _OBJC_IVAR_$_SUUITaskGroup._identifier
+ _OBJC_IVAR_$_SUUITaskGroup._joined
+ _OBJC_IVAR_$_SUUITaskGroup._names
+ _OBJC_IVAR_$_SUUITaskGroup._nextToken
+ _OBJC_IVAR_$_SUUITaskGroup._outstanding
+ _OBJC_IVAR_$_SUUITaskGroup._policy
+ _OBJC_IVAR_$_SUUITaskGroup._resultsByName
+ _OBJC_IVAR_$_SUUITaskGroup._safetyTimer
+ _OBJC_IVAR_$_SUUITaskGroup._selfRetain
+ _OBJC_IVAR_$_SUUITaskGroup._settled
+ _OBJC_IVAR_$_SUUITaskGroup._startToJoinSafetyTimeout
+ _OBJC_IVAR_$_SUUITaskGroup._state
+ _OBJC_IVAR_$_SUUITaskGroup._stateQueue
+ _OBJC_IVAR_$_SUUITaskGroup._terminalResult
+ _OBJC_IVAR_$_SUUITaskGroup._timeout
+ _OBJC_IVAR_$_SUUITaskGroup._waitDeadlineArmed
+ _OBJC_IVAR_$_SUUITaskGroup._waitTimer
+ _OBJC_IVAR_$_SUUITaskGroupEntry._block
+ _OBJC_IVAR_$_SUUITaskGroupEntry._context
+ _OBJC_IVAR_$_SUUITaskGroupEntry._dispatched
+ _OBJC_IVAR_$_SUUITaskGroupEntry._name
+ _OBJC_IVAR_$_SUUITaskGroupEntry._token
+ _OBJC_IVAR_$_SUUITaskGroupResult._finishedTaskNames
+ _OBJC_IVAR_$_SUUITaskGroupResult._firstError
+ _OBJC_IVAR_$_SUUITaskGroupResult._outcome
+ _OBJC_IVAR_$_SUUITaskGroupResult._resultsByName
+ _OBJC_IVAR_$_SUUITaskGroupResult._unfinishedTaskNames
+ _OBJC_METACLASS_$_SUUIDeviceDescriptorRef
+ _OBJC_METACLASS_$_SUUITaskGroup
+ _OBJC_METACLASS_$_SUUITaskGroupEntry
+ _OBJC_METACLASS_$_SUUITaskGroupResult
+ __OBJC_$_INSTANCE_METHODS_SUUIDeviceDescriptorRef
+ __OBJC_$_INSTANCE_METHODS_SUUITaskGroup
+ __OBJC_$_INSTANCE_METHODS_SUUITaskGroupEntry
+ __OBJC_$_INSTANCE_METHODS_SUUITaskGroupResult
+ __OBJC_$_INSTANCE_VARIABLES_SUUIDeviceDescriptorRef
+ __OBJC_$_INSTANCE_VARIABLES_SUUITaskGroup
+ __OBJC_$_INSTANCE_VARIABLES_SUUITaskGroupEntry
+ __OBJC_$_INSTANCE_VARIABLES_SUUITaskGroupResult
+ __OBJC_$_PROP_LIST_SUUIDeviceDescriptorRef
+ __OBJC_$_PROP_LIST_SUUITaskGroup
+ __OBJC_$_PROP_LIST_SUUITaskGroupEntry
+ __OBJC_$_PROP_LIST_SUUITaskGroupResult
+ __OBJC_CLASS_PROTOCOLS_$_SUUIDeviceDescriptorRef
+ __OBJC_CLASS_RO_$_SUUIDeviceDescriptorRef
+ __OBJC_CLASS_RO_$_SUUITaskGroup
+ __OBJC_CLASS_RO_$_SUUITaskGroupEntry
+ __OBJC_CLASS_RO_$_SUUITaskGroupResult
+ __OBJC_METACLASS_RO_$_SUUIDeviceDescriptorRef
+ __OBJC_METACLASS_RO_$_SUUITaskGroup
+ __OBJC_METACLASS_RO_$_SUUITaskGroupEntry
+ __OBJC_METACLASS_RO_$_SUUITaskGroupResult
+ ___22-[SUUITaskGroup start]_block_invoke
+ ___23-[SUUITaskGroup cancel]_block_invoke
+ ___31-[SUUITaskGroup waitForResult:]_block_invoke
+ ___32-[SUUITaskGroup _dispatchEntry:]_block_invoke
+ ___33-[SUUITaskGroup _armWaitDeadline]_block_invoke
+ ___35-[SUUITaskGroup _armSafetyDeadline]_block_invoke
+ ___36-[SUUITaskGroup _settleWithOutcome:]_block_invoke
+ ___43-[SUUITaskGroup addTaskNamed:context:task:]_block_invoke
+ ___block_descriptor_56_e8_32s40w_e5_v8?0ls32l8w40l8
+ ___block_descriptor_56_e8_32w_e20_v24?08"NSError"16lw32l8
+ ___block_descriptor_64_e8_32s40bs48w_e5_v8?0ls32l8w48l8s40l8
+ ___block_descriptor_64_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48bs56w_e5_v8?0lw56l8s48l8s32l8s40l8
+ ___block_descriptor_80_e8_32s40s48s56bs64w_e5_v8?0ls32l8w64l8s40l8s48l8s56l8
+ ___os_log_helper_16_2_4_8_32_8_66_8_0_8_0
+ ___os_log_helper_16_2_4_8_32_8_66_8_0_8_66
+ ___os_log_helper_16_2_4_8_32_8_66_8_66_8_32
+ ___os_log_helper_16_2_5_8_32_8_66_8_0_8_0_8_32
+ ___os_log_helper_16_2_5_8_32_8_66_8_0_8_0_8_66
+ ___os_log_helper_16_2_5_8_32_8_66_8_66_8_0_8_0
+ ___os_log_helper_16_2_5_8_32_8_66_8_66_8_66_8_0
+ ___os_log_helper_16_2_5_8_32_8_66_8_66_8_66_8_66
+ __dispatch_queue_attr_concurrent
+ __dispatch_source_type_timer
+ _dispatch_resume
+ _dispatch_source_cancel
+ _dispatch_source_create
+ _dispatch_source_set_event_handler
+ _dispatch_source_set_timer
+ _kSUUIUserDefaultsScanResultsCacheRefreshForceScan
+ _kSUUIUserDefaultsScanResultsCacheRefreshIntervalOverride
- GCC_except_table139
- GCC_except_table150
- GCC_except_table157
- GCC_except_table160
- GCC_except_table162
- GCC_except_table165
- GCC_except_table170
- GCC_except_table178
- GCC_except_table183
- GCC_except_table189
- GCC_except_table191
- GCC_except_table196
- GCC_except_table206
- GCC_except_table209
- GCC_except_table211
- GCC_except_table219
- GCC_except_table227
- GCC_except_table229
- GCC_except_table232
- GCC_except_table240
- GCC_except_table248
- GCC_except_table251
- GCC_except_table253
- GCC_except_table261
- GCC_except_table264
- GCC_except_table270
- GCC_except_table334
- __MergedGlobals
- ___isOSVersionAtLeast
- ___isPlatformVersionAtLeast
- __availability_version_check
- __initializeAvailabilityCheck
- _compatibilityInitializeAvailabilityCheck
- _dispatch_once_f
- _dlsym
- _fclose
- _fopen
- _fread
- _fseek
- _ftell
- _initializeAvailabilityCheck
- _malloc
- _rewind
- _sscanf
- _swift_getEnumCaseMultiPayload
- _swift_storeEnumTagMultiPayload
- _swift_willThrowTypedImpl
CStrings:
+ "#"
+ "%s [%p]: %{public}@ Checkpoint\n\tcurrentState: %{public}@ (%ld)\n\tdelegate: %{public}@ (%p)\n\tscanError: %{public}@\n\tpreferredDescriptor: %{public}@\n\talternateDescriptor: %{public}@\n\tdownload: %{public}@ (%p)\n\tcurrentUpdateOperationType: %{public}@\n\tscheduledForAutoInstall: %{public}@\n\thiddenUpdatesPostSelection: preferred[%{public}@, %{public}@]; alternate[%{public}@, %{public}@];\n\tselectedBetaProgram: %lu (count: %ld, enrollable: %{public}@)\n\tOpFSMs: scan[%p]; refresh[%p]; update[%p]; auxiliaryOperationsCount[%lu]\n\nperformFullScan: [%{public}@]"
+ "%s [%{public}@]: Cancelled with %lu task(s) still outstanding."
+ "%s [%{public}@]: Dispatching task %{public}@ (token %llu)."
+ "%s [%{public}@]: Ignoring -cancel — group already settled."
+ "%s [%{public}@]: Ignoring -start — group is not in the Building state (state=%ld)."
+ "%s [%{public}@]: Ignoring addTask:%{public}@ — a task with this name already exists."
+ "%s [%{public}@]: Ignoring addTask:%{public}@ — the group is already %s."
+ "%s [%{public}@]: Ignoring duplicate/late reply for token %llu."
+ "%s [%{public}@]: Registered task %{public}@ (token %llu); outstanding=%lu."
+ "%s [%{public}@]: Settled: outcome=%ld; firstError=%{public}@."
+ "%s [%{public}@]: Start-to-join safety window (%.0fs) elapsed without a join; releasing the self-retain (%lu task(s) still outstanding). Not settling — a later join will still get the real result if this group is still referenced."
+ "%s [%{public}@]: Starting with %lu task(s); wait-timeout=%.1fs; policy=%s."
+ "%s [%{public}@]: Task %{public}@ failed: %{public}@; outstanding=%lu."
+ "%s [%{public}@]: Task %{public}@ succeeded; outstanding=%lu."
+ "%s [%{public}@]: Task %{public}@ threw %{public}@: %{public}@ — treating as failure."
+ "%s [%{public}@]: Timed out after %.1fs; %lu task(s) unfinished: %{public}@."
+ "%s [%{public}@]: Wait deadline reached but all tasks had finished; settling %ld."
+ "%s [%{public}@]: waitForResult: group already settled (outcome=%ld); replaying."
+ "(no reason)"
+ "-[SUUITaskGroup _armSafetyDeadline]_block_invoke"
+ "-[SUUITaskGroup _armWaitDeadline]_block_invoke"
+ "-[SUUITaskGroup _dispatchEntry:]"
+ "-[SUUITaskGroup _dispatchEntry:]_block_invoke"
+ "-[SUUITaskGroup _dispatchEntry:]_block_invoke_2"
+ "-[SUUITaskGroup _resolveToken:result:error:]"
+ "-[SUUITaskGroup _settleWithOutcome:]"
+ "-[SUUITaskGroup addTaskNamed:context:task:]_block_invoke"
+ "-[SUUITaskGroup cancel]_block_invoke"
+ "-[SUUITaskGroup start]_block_invoke"
+ "-[SUUITaskGroup waitForResult:]_block_invoke"
+ ".exec"
+ ".state"
+ "<%@: %p; id=%@; state=%ld; policy=%ld; timeout=%.1f>"
+ "<%@: %p; outcome=%ld; firstError=%@; finished=%@; unfinished=%@>"
+ "Fixed interval, in seconds, for the scan-results cache refresh timer, overriding the automatic cache-TTL-derived interval. Unset or <= 0 means use the automatic interval."
+ "SUScanResultsCacheRefreshForceScan"
+ "SUScanResultsCacheRefreshIntervalOverride"
+ "SUUIUserDefaults[N]: Read %{public}@ = %{public}@"
+ "SUUIUserDefaults[N]: Write %{public}@ = %{public}@"
+ "Task '%@' raised %@: %@"
+ "Task group '%@' timed out after %.1f seconds. Unfinished: %@"
+ "When YES, the scan-results cache refresh timer performs a scan on every fire regardless of cache validity."
+ "buildVersion"
+ "collect-all"
+ "com.apple.SoftwareUpdateUI.TaskGroup.%@"
+ "fail-fast"
+ "joined (sealed)"
+ "osName"
+ "productFamilyName"
+ "productVersion"
+ "retries=%u forceReload=%d forceScan=%d refreshPreviousState=%ld"
+ "settled"
+ "task block must not be nil"
+ "task name must not be nil"
+ "v24@?0@8@\"NSError\"16"
- "%d.%d.%d"
- "/System/Library/CoreServices/SystemVersion.plist"
- "CFDataCreateWithBytesNoCopy"
- "CFDictionaryGetValue"
- "CFGetTypeID"
- "CFPropertyListCreateFromXMLData"
- "CFPropertyListCreateWithData"
- "CFRelease"
- "CFStringCreateWithCStringNoCopy"
- "CFStringGetCString"
- "CFStringGetTypeID"
- "kCFAllocatorNull"
- "r"
```
