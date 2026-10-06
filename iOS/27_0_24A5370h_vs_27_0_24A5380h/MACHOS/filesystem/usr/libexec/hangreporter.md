## hangreporter

> `/usr/libexec/hangreporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23978` | `0x25e20` | **`+0x24a8`** |
| `__TEXT.__objc_methname` | `0x5751` | `0x5c78` | **`+0x527`** |
| `__DATA.__objc_const` | `0x2a10` | `0x2eb8` | **`+0x4a8`** |
| `__TEXT.__objc_stubs` | `0x30a0` | `0x3460` | **`+0x3c0`** |
| `__TEXT.__objc_methlist` | `0x1144` | `0x136c` | **`+0x228`** |
| `__TEXT.__cstring` | `0x4132` | `0x42bf` | **`+0x18d`** |
| `__DATA.__objc_selrefs` | `0x1178` | `0x1298` | **`+0x120`** |
| `__DATA_CONST.__const` | `0x1530` | `0x1640` | **`+0x110`** |
| `__TEXT.__gcc_except_tab` | `0xbb4` | `0xc7c` | **`+0xc8`** |
| `__DATA.__objc_data` | `0x4b0` | `0x550` | **`+0xa0`** |
| `__DATA_CONST.__cfstring` | `0x5200` | `0x52a0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x578` | `0x608` | **`+0x90`** |
| `__DATA.__objc_ivar` | `0x28c` | `0x2e0` | **`+0x54`** |
| `__TEXT.__objc_methtype` | `0x89d` | `0x8ef` | **`+0x52`** |
| `__DATA_CONST.__got` | `0x288` | `0x2c8` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0xef0` | `0xf20` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x160` | `0x183` | **`+0x23`** |
| `__DATA_CONST.__auth_got` | `0x788` | `0x7a0` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x4d39` | `0x4d4f` | **`+0x16`** |
| `__DATA.__bss` | `0x208` | `0x218` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x78` | `0x88` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA.__common` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA.__data` | `0x750` | `0x758` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`

### Other Changes

```diff

-415.0.0.0.0
+421.0.0.0.0

-  Functions: 684
-  Symbols:   331
-  CStrings:  2039
+  Functions: 757
+  Symbols:   334
+  CStrings:  2132
Symbols:
+ _dispatch_sync
+ _os_signpost_id_generate
+ _xpc_dictionary_set_bool
CStrings:
+ "@\"HTTailspinWorkItem\""
+ "@\"NSMutableSet\""
+ "@\"NSSet\""
+ "@?"
+ "@?16@0:8"
+ "Boost hangUUID %@ - %s"
+ "Boost request for hangUUID: %@"
+ "Boost request missing hangUUID"
+ "Discovered task: %@"
+ "Failed to parse reason dictionary from tailspin at %@: %@"
+ "HTTailspinQueue"
+ "HTTailspinWorkItem"
+ "Idle-exit timer fired, calling xpc_transaction_exit_clean."
+ "Ignoring non tailspin file or leftover .tailspin: %@"
+ "Scan finish, wait conversion to complete..."
+ "ShouldMonitorCPURoleForAppExtensions"
+ "T@\"NSArray\",C,N,V_infoDictArray"
+ "T@\"NSDate\",&,N,V_startTime"
+ "T@\"NSObject<OS_os_transaction>\",&,N,V_transaction"
+ "T@\"NSSet\",C,N,V_hangUUIDs"
+ "T@\"NSString\",C,N,V_filePath"
+ "T@\"NSString\",C,N,V_tailspinFileName"
+ "T@?,C,N,V_workBlock"
+ "TB,N,V_isBoosted"
+ "TB,N,V_isPriority"
+ "TB,R,V_shouldMonitorCPURoleForAppExtensions"
+ "TQ,N,V_taskSignpostID"
+ "TaskProcessing"
+ "Td,N,V_processingDurationMs"
+ "Td,N,V_totalHangDurationMs"
+ "_accessQueue"
+ "_currentProcessingItem"
+ "_hangUUIDs"
+ "_idleExitTimeoutMsec"
+ "_idleExitTimer"
+ "_inFlightPaths"
+ "_infoDictArray"
+ "_isBoosted"
+ "_isPriority"
+ "_normalQueue"
+ "_priorityQueue"
+ "_processingDurationMs"
+ "_shouldMonitorCPURoleForAppExtensions"
+ "_startTime"
+ "_tailspinFileName"
+ "_taskSignpostID"
+ "_totalHangDurationMs"
+ "_workBlock"
+ "_workerQueue"
+ "addInFlightPath:"
+ "beginProcessingItem:"
+ "boost-task"
+ "com.apple.hangreporter.doneProcessingTailspin"
+ "com.apple.hangreporter.httailspinqueue.work-available"
+ "com.apple.hangreporter.tailspinqueue"
+ "com.apple.hangreporter.taskregistry.changed"
+ "com.apple.hangreporter.worker"
+ "com.apple.hangtracer.processAllAvailableTailspins"
+ "completeProcessingItem:"
+ "dequeueNonBlocking"
+ "enqueueNormal:"
+ "enqueuePriority:"
+ "getProcessingHangEntries"
+ "hangUUIDs"
+ "hangreporter_tailspin_processing"
+ "hangtracer.tailspin_path"
+ "hasItems"
+ "hasPriorityItems"
+ "infoDictArray"
+ "isBoosted"
+ "isPathInFlight:"
+ "isPriority"
+ "nil"
+ "not found in pending queue"
+ "postDidSaveTailspinNotification()"
+ "postDoneProcessingTailspinNotification"
+ "processingDurationMs"
+ "promoteItemWithHangUUID:"
+ "promoted/boosted"
+ "removeInFlightPath:"
+ "removeObject:"
+ "set"
+ "setHangUUIDs:"
+ "setInfoDictArray:"
+ "setIsBoosted:"
+ "setIsPriority:"
+ "setProcessingDurationMs:"
+ "setStartTime:"
+ "setTailspinFileName:"
+ "setTaskSignpostID:"
+ "setTotalHangDurationMs:"
+ "setWorkBlock:"
+ "sharedQueue"
+ "shouldMonitorCPURoleForAppExtensions"
+ "startDispatcherWithNotifyToken:"
+ "success"
+ "tailspinFile=%{public}@"
+ "tailspinFile=%{public}@ durationMs=%.1f"
+ "tailspinFileName"
+ "taskSignpostID"
+ "totalHangDurationMs"
+ "v24@0:8@?16"
+ "v24@0:8d16"
+ "workBlock"
- "Calling xpc_transaction_exit_clean() now"
- "Done..."
- "Encountered error trying to procesxs %@"
- "File=%@, Bytes=%{signpost.telemetry:number1}llu, Symbolicate=%{signpost.telemetry:string1}s enableTelemetry=YES "
- "Ignoring non tailspin file: %@"
- "NumSuccessfulReports=%{signpost.telemetry:number2}d enableTelemetry=YES "
- "Post-Processing Tailspin file: %@\n"
- "Posting com.apple.hangreporter.processing notification"
- "Sentry tailspin detected."
- "TailspinConversionInterval"
- "hangreporter_tailspin_conversion"
```
