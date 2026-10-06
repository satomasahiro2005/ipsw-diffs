## NewsDaemon

> `/System/Library/PrivateFrameworks/NewsDaemon.framework/NewsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28084` | `0x2d1d8` | **`+0x5154`** |
| `__DATA.__bss` | `0x2cf0` | `0x32f0` | **`+0x600`** |
| `__TEXT.__const` | `0x24a8` | `0x29c8` | **`+0x520`** |
| `__AUTH_CONST.__const` | `0x15b0` | `0x1948` | **`+0x398`** |
| `__TEXT.__swift5_typeref` | `0xa93` | `0xd3e` | **`+0x2ab`** |
| `__TEXT.__eh_frame` | `0xe78` | `0x1078` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0x979` | `0xb4b` | **`+0x1d2`** |
| `__TEXT.__unwind_info` | `0xd00` | `0xe58` | **`+0x158`** |
| `__TEXT.__constg_swiftt` | `0x794` | `0x8e0` | **`+0x14c`** |
| `__DATA.__data` | `0xaa8` | `0xbc0` | **`+0x118`** |
| `__AUTH_CONST.__objc_const` | `0x20b8` | `0x21c8` | **`+0x110`** |
| `__AUTH.__objc_data` | `0x358` | `0x448` | **`+0xf0`** |
| `__AUTH_CONST.__auth_got` | `0xa50` | `0xb30` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x1ac` | `0x28c` | **`+0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x7e0` | `0x890` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x11d9` | `0x1260` | **`+0x87`** |
| `__TEXT.__swift5_reflstr` | `0x659` | `0x6c8` | **`+0x6f`** |
| `__DATA_CONST.__objc_selrefs` | `0x8f8` | `0x960` | **`+0x68`** |
| `__TEXT.__swift5_assocty` | `0x178` | `0x1d8` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x458` | `0x4a8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xf38` | `0xf80` | **`+0x48`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x8c` | **`+0x3c`** |
| `__TEXT.__swift5_proto` | `0x1a4` | `0x1dc` | **`+0x38`** |
| `__AUTH.__data` | `0x338` | `0x360` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0xa4` | `0xb8` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x3c` | `0x4c` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x24` | `0x2c` | **`+0x8`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

+  - /System/Library/PrivateFrameworks/BackgroundSystemTasks.framework/BackgroundSystemTasks

-  Functions: 1176
-  Symbols:   1034
-  CStrings:  171
+  Functions: 1298
+  Symbols:   1097
+  CStrings:  185
Symbols:
+ _BGSystemTaskSchedulerErrorDomain
+ _OBJC_CLASS_$_BGNonRepeatingSystemTaskRequest
+ _OBJC_CLASS_$_BGSystemTaskScheduler
+ _OBJC_CLASS_$_NDSystemScheduledWork
+ _OBJC_METACLASS_$_NDSystemScheduledWork
+ __DATA_NDSystemScheduledWork
+ __INSTANCE_METHODS_NDSystemScheduledWork
+ __IVARS_NDSystemScheduledWork
+ __METACLASS_DATA_NDSystemScheduledWork
+ ___swift_memcpy4_4
+ _associated conformance 10NewsDaemon29NDSystemScheduledWorkPriorityOSHAASQ
+ _associated conformance SC30BGSystemTaskSchedulerErrorCodeLeV10Foundation021_ObjectiveCBridgeableD0SCs0D0
+ _associated conformance SC30BGSystemTaskSchedulerErrorCodeLeV10Foundation13CustomNSErrorSCs0D0
+ _associated conformance SC30BGSystemTaskSchedulerErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0E0AcDP_8RawValueSYs17FixedWidthInteger
+ _associated conformance SC30BGSystemTaskSchedulerErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0E0AcDP_AC01_dE8Protocol
+ _associated conformance SC30BGSystemTaskSchedulerErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0E0AcDP_SY
+ _associated conformance SC30BGSystemTaskSchedulerErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCAC021_ObjectiveCBridgeableD0
+ _associated conformance SC30BGSystemTaskSchedulerErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCAC06CustomI0
+ _associated conformance SC30BGSystemTaskSchedulerErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCSH
+ _associated conformance SC30BGSystemTaskSchedulerErrorCodeLeVSHSCSQ
+ _associated conformance So30BGSystemTaskSchedulerErrorCodeV10Foundation01_dE8ProtocolSC01_D4TypeAcDP_AC21_BridgedStoredNSError
+ _associated conformance So30BGSystemTaskSchedulerErrorCodeV10Foundation01_dE8ProtocolSCSQ
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_retain_x8
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic $s10Foundation18_ErrorCodeProtocolP
+ _symbolic $s10Foundation21_BridgedStoredNSErrorP
+ _symbolic $s10NewsDaemon18NDSystemTaskHandleP
+ _symbolic $s10NewsDaemon22NDSystemTaskSchedulingP
+ _symbolic IeghH_
+ _symbolic Iegh_
+ _symbolic Iegh_Ieghg_
+ _symbolic IeyBh_IeyBhy_
+ _symbolic Sb9cancelled_Sb7resumedScCyyt_____GSg12continuationt s5NeverO
+ _symbolic ScCyyt_____G s5NeverO
+ _symbolic ScCyyt_____GSg s5NeverO
+ _symbolic So7NSErrorC
+ _symbolic _____ 10NewsDaemon21NDSystemScheduledWorkC
+ _symbolic _____ 10NewsDaemon29NDSystemScheduledWorkPriorityO
+ _symbolic _____ 2os6LoggerV
+ _symbolic _____ SC30BGSystemTaskSchedulerErrorCodeLeV
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ So30BGSystemTaskSchedulerErrorCodeV
+ _symbolic _____ s6UInt32V
+ _symbolic _____SgXw 10NewsDaemon21NDSystemScheduledWorkC
+ _symbolic _____SgXwz_Xx 10NewsDaemon21NDSystemScheduledWorkC
+ _symbolic ______p 10NewsDaemon18NDSystemTaskHandleP
+ _symbolic ______p 10NewsDaemon22NDSystemTaskSchedulingP
+ _symbolic ______pIegg_ 10NewsDaemon18NDSystemTaskHandleP
+ _symbolic _____ySb7expired_ScTyyt_____GSg6runnertG 2os21OSAllocatedUnfairLockV s5NeverO
+ _symbolic _____ySb7expired_ScTyyt_____GSg6runnert_____G s13ManagedBufferCsRi__rlE s5NeverO So16os_unfair_lock_sV
+ _symbolic _____ySb9cancelled_Sb7resumedScCyyt_____GSg12continuationt_____G s13ManagedBufferCsRi__rlE s5NeverO So16os_unfair_lock_sV
+ _symbolic _____ySiG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySi_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic yyYaYbc
+ _type_layout_string SC30BGSystemTaskSchedulerErrorCodeLeV
+ _type_layout_string So16os_unfair_lock_sV
CStrings:
+ "NewsDaemon/NDSystemScheduledWork.swift"
+ "Use init(identifier:priority:work:)"
+ "acking expiration, id='%s'"
+ "asyncWork(fromCompletionBased:)"
+ "completed, id='%s'"
+ "expired by system, id='%s'"
+ "failed to ack expiration, id='%s', error=%@"
+ "failed to deregister task, id='%s'"
+ "failed to register, task will never run, id='%s'"
+ "failed to submit task request, id='%s', error=%@"
+ "operation in progress, id='%s'"
+ "running, id='%s'"
+ "submitted task request, id='%s'"
+ "task request already pending, id='%s'"
```
