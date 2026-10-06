## HangTracerSettingsClient

> `/System/Library/PrivateFrameworks/HangTracerSettingsClient.framework/HangTracerSettingsClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16a08` | `0x17278` | **`+0x870`** |
| `__AUTH_CONST.__objc_const` | `0x15b0` | `0x1670` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x54c` | `0x60a` | **`+0xbe`** |
| `__TEXT.__objc_methlist` | `0xc2c` | `0xc94` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x410` | `0x3c0` | **`-0x50`** |
| `__DATA_CONST.__const` | `0xd78` | `0xdc8` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xb20` | `0xb60` | **`+0x40`** |
| `__TEXT.__cstring` | `0x31a2` | `0x31ce` | **`+0x2c`** |
| `__AUTH_CONST.__cfstring` | `0x3960` | `0x3980` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x368` | `0x380` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xcc` | `0xdc` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x660` | `0x670` | **`+0x10`** |

### Other Changes

```diff

-415.0.0.0.0
+421.0.0.0.0

-  Functions: 790
-  Symbols:   1157
-  CStrings:  580
+  Functions: 806
+  Symbols:   1177
+  CStrings:  589
Symbols:
+ -[HTHang isBoosted]
+ -[HTHang tailspinPath]
+ -[HTHangReporterService prioritizeTaskWithHangIDAndExpedite:completion:]
+ -[HTHangsDataEntry initWithPath:hangID:creationDate:duration:processBundleID:processPath:processRecord:isBoosted:isBeingProcessed:]
+ -[HTHangsDataEntry isBoosted]
+ -[HTHangsDataFinder hangReporterDoneProcessingTailspin:]
+ -[HTHangsDataFinder initWithLogUpdateCallback:tailspinSavedCallback:tailspinDoneCallback:]
+ -[HTHangsDataFinder setTailspinDoneCallback:]
+ -[HTHangsDataFinder tailspinDoneCallback]
+ GCC_except_table17
+ _OBJC_IVAR_$_HTHang._isBoosted
+ _OBJC_IVAR_$_HTHang._tailspinPath
+ _OBJC_IVAR_$_HTHangsDataEntry._isBoosted
+ _OBJC_IVAR_$_HTHangsDataFinder._tailspinDoneCallback
+ ___72-[HTHangReporterService prioritizeTaskWithHangIDAndExpedite:completion:]_block_invoke
+ ___72-[HTHangReporterService prioritizeTaskWithHangIDAndExpedite:completion:]_block_invoke_2
+ ___72-[HTHangReporterService prioritizeTaskWithHangIDAndExpedite:completion:]_block_invoke_3
+ ___90-[HTHangsDataFinder initWithLogUpdateCallback:tailspinSavedCallback:tailspinDoneCallback:]_block_invoke
+ ___90-[HTHangsDataFinder initWithLogUpdateCallback:tailspinSavedCallback:tailspinDoneCallback:]_block_invoke_2
+ ___90-[HTHangsDataFinder initWithLogUpdateCallback:tailspinSavedCallback:tailspinDoneCallback:]_block_invoke_3
+ ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_41_e8_32bs_e5_v8?0ls32l8
+ _kHTDoneProcessingTailspinNotification
+ _kHTExtendedAttributeIsBoosted
+ _kHTExtendedAttributeTailspinPath
+ _xpc_dictionary_get_bool
- GCC_except_table16
- ___69-[HTHangsDataFinder initWithLogUpdateCallback:tailspinSavedCallback:]_block_invoke
- ___69-[HTHangsDataFinder initWithLogUpdateCallback:tailspinSavedCallback:]_block_invoke_2
- ___69-[HTHangsDataFinder initWithLogUpdateCallback:tailspinSavedCallback:]_block_invoke_3
- ___72-[HTHangsDataFinder findEventsFilteringDeveloperApps:completionHandler:]_block_invoke_3
- _objc_retain_x26
CStrings:
+ "Boost request sent for hangID %@"
+ "Hang UUID is required"
+ "Invalid reply from hangreporter"
+ "boost-task"
+ "handleReporterDidSaveTailspin()"
+ "handleReporterDoneProcessingTailspin()"
+ "hangUUID"
+ "prioritizeTaskWithHangIDAndExpedite: hangID nil"
+ "success"
```
