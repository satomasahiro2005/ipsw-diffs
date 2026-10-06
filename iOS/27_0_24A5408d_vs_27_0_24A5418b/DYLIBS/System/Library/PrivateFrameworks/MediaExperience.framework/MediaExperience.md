## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2534a8` | `0x252aec` | **`-0x9bc`** |
| `__AUTH_CONST.__objc_const` | `0xd190` | `0xcec0` | **`-0x2d0`** |
| `__AUTH_CONST.__cfstring` | `0x1c100` | `0x1bfe0` | **`-0x120`** |
| `__TEXT.__objc_methlist` | `0x88d8` | `0x8818` | **`-0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x4e0c` | `0x4eb4` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x1db0` | `0x1d10` | **`-0xa0`** |
| `__TEXT.__unwind_info` | `0x5fe0` | `0x5f58` | **`-0x88`** |
| `__DATA_CONST.__const` | `0x72c0` | `0x7248` | **`-0x78`** |
| `__TEXT.__cstring` | `0x38c1a` | `0x38bac` | **`-0x6e`** |
| `__DATA_CONST.__objc_selrefs` | `0x54a8` | `0x5448` | **`-0x60`** |
| `__DATA.__objc_ivar` | `0xca4` | `0xc70` | **`-0x34`** |
| `__DATA.__data` | `0x1428` | `0x1410` | **`-0x18`** |
| `__DATA_CONST.__got` | `0xd18` | `0xd08` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x320` | `0x310` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x2f0` | `0x2e0` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x4fcdf` | `0x4fced` | **`+0xe`** |

### Other Changes

```diff

-360.75.1.1.0
+360.75.1.2.0

-  Functions: 10098
-  Symbols:   13561
-  CStrings:  9876
+  Functions: 10075
+  Symbols:   13504
+  CStrings:  9868
Symbols:
+ -[MXSystemMediaCastingController_Client handleActiveClientResigned:]
+ GCC_except_table60
+ GCC_except_table62
+ GCC_except_table64
+ GCC_except_table70
+ GCC_except_table76
+ GCC_except_table87
+ ___block_descriptor_40_e8_32b_e20_v24?0"NSError"816ls32l8
+ ___block_descriptor_40_e8_32b_e22_v16?0"NSDictionary"8ls32l8
+ ___block_descriptor_48_e8_32o40b_e22_v16?0"NSDictionary"8ls40l8s32l8
+ ___block_descriptor_48_e8_32o40o_e20_v24?0"NSError"816ls32l8s40l8
+ ___block_descriptor_48_e8_32o40r_e22_v16?0"NSDictionary"8lr40l8s32l8
+ ___block_descriptor_56_e8_32o40o48r_e22_v16?0"NSDictionary"8lr48l8s32l8s40l8
- -[MXMDEExtensionRequest .cxx_destruct]
- -[MXMDEExtensionRequest completeWithReplyError:result:]
- -[MXMDEExtensionRequest dealloc]
- -[MXMDEExtensionRequest failUnresponsiveWithError:]
- -[MXMDEExtensionRequest initWithOperation:instance:completion:]
- -[MXMDEExtensionRequest resolveUnresponsive:error:result:]
- -[MXMDEPendingExtensionRequest .cxx_destruct]
- -[MXMDEPendingExtensionRequest completeWithError:result:]
- -[MXMDEPendingExtensionRequest initWithClient:resultOpCode:requestID:]
- -[MXSystemCastingExtensionInstance noteUnresponsiveExtensionForOperation:error:]
- -[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]
- -[MXSystemMediaCastingController_Client flushPendingHandlersWithError:]
- -[MXSystemMediaCastingController_Client handleAsyncResult:]
- -[MXSystemMediaCastingController_Client registerPendingHandler:]
- -[MXSystemMediaCastingController_Client takePendingHandlerForRequestID:]
- GCC_except_table100
- GCC_except_table55
- GCC_except_table77
- GCC_except_table83
- GCC_except_table85
- GCC_except_table90
- _OBJC_CLASS_$_MXMDEExtensionRequest
- _OBJC_CLASS_$_MXMDEPendingExtensionRequest
- _OBJC_IVAR_$_MXMDEExtensionRequest._completion
- _OBJC_IVAR_$_MXMDEExtensionRequest._done
- _OBJC_IVAR_$_MXMDEExtensionRequest._instance
- _OBJC_IVAR_$_MXMDEExtensionRequest._lock
- _OBJC_IVAR_$_MXMDEExtensionRequest._operation
- _OBJC_IVAR_$_MXMDEPendingExtensionRequest._client
- _OBJC_IVAR_$_MXMDEPendingExtensionRequest._done
- _OBJC_IVAR_$_MXMDEPendingExtensionRequest._lock
- _OBJC_IVAR_$_MXMDEPendingExtensionRequest._requestID
- _OBJC_IVAR_$_MXMDEPendingExtensionRequest._resultOpCode
- _OBJC_IVAR_$_MXSystemMediaCastingController_Client.nextRequestID
- _OBJC_IVAR_$_MXSystemMediaCastingController_Client.pendingHandlers
- _OBJC_IVAR_$_MXSystemMediaCastingController_Client.pendingLock
- _OBJC_METACLASS_$_MXMDEExtensionRequest
- _OBJC_METACLASS_$_MXMDEPendingExtensionRequest
- __OBJC_$_INSTANCE_METHODS_MXMDEExtensionRequest
- __OBJC_$_INSTANCE_METHODS_MXMDEPendingExtensionRequest
- __OBJC_$_INSTANCE_VARIABLES_MXMDEExtensionRequest
- __OBJC_$_INSTANCE_VARIABLES_MXMDEPendingExtensionRequest
- __OBJC_CLASS_RO_$_MXMDEExtensionRequest
- __OBJC_CLASS_RO_$_MXMDEPendingExtensionRequest
- __OBJC_METACLASS_RO_$_MXMDEExtensionRequest
- __OBJC_METACLASS_RO_$_MXMDEPendingExtensionRequest
- ___102-[MXSystemCastingExtensionInstance deactivateDeviceWithDescription:withNWEndpoints:completionHandler:]_block_invoke_2
- ___107-[MXSystemCastingExtensionInstance startApplicationWithURL:applicationID:launchType:withCompletionHandler:]_block_invoke_2
- ___112-[MXSystemCastingExtensionInstance activateDeviceWithDescription:withNWEndpoints:isMirroring:completionHandler:]_block_invoke_2
- ___63-[MXMDEExtensionRequest initWithOperation:instance:completion:]_block_invoke
- ___77-[MXSystemCastingExtensionInstance mediaSourceDataForKeys:completionHandler:]_block_invoke_2
- ___82-[MXSystemMediaCastingController_Client mediaSourceDataForKeys:completionHandler:]_block_invoke
- ___84-[MXSystemCastingExtensionInstance sendData:forApplicationID:withCompletionHandler:]_block_invoke_2
- ___89-[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]_block_invoke
- ___89-[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]_block_invoke_2
- ___89-[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]_block_invoke_3
- ___89-[MXSystemMediaCastingController_Client sendData:forApplicationID:withCompletionHandler:]_block_invoke
- ___92-[MXSystemMediaCastingController_Client sendApplicationLaunchMessage:withCompletionHandler:]_block_invoke
- ___block_descriptor_40_e8_32b_e34_v24?0"NSError"8"NSDictionary"16ls32l8
- ___block_descriptor_40_e8_32o_e20_v24?0"NSError"816ls32l8
- ___block_descriptor_40_e8_32o_e22_v16?0"NSDictionary"8ls32l8
- ___block_descriptor_40_e8_32o_e34_v24?0"NSError"8"NSDictionary"16ls32l8
- ___block_descriptor_40_e8_32o_e62_v24?0"<MediaDeviceServerInterface>"8?<v?"NSDictionary">16ls32l8
- ___block_descriptor_44_e8_32o_e62_v24?0"<MediaDeviceServerInterface>"8?<v?"NSDictionary">16ls32l8
- ___block_descriptor_48_e8_32o40b_e34_v24?0"NSError"8"NSDictionary"16ls40l8s32l8
- ___block_descriptor_48_e8_32o40o_e34_v24?0"NSError"8"NSDictionary"16ls32l8s40l8
- ___block_descriptor_48_e8_32o_e62_v24?0"<MediaDeviceServerInterface>"8?<v?"NSDictionary">16ls32l8
- _kMXSystemMediaCastingControllerMsgParam_RequestID
- _kMXSystemMediaCastingControllerReplyParam_ErrorCode
- _kMXSystemMediaCastingControllerReplyParam_Result
CStrings:
+ "-MXSystemMediaCastingController_Server- %s: Failed to create ReportActiveClientResigned message for %{public}@, err %d"
+ "-MXSystemMediaCastingController_Server- %s: Timeout waiting for completion handler"
+ "-MXSystemMediaCastingController_Server- %s: Timeout waiting for sendData completion handler"
+ "-[MXSystemCastingExtensionInstance decreaseVolumeByCount:forDevice:completionHandler:]_block_invoke"
+ "-[MXSystemCastingExtensionInstance getVolumeForDevice:completionHandler:]_block_invoke"
+ "-[MXSystemCastingExtensionInstance increaseVolumeByCount:forDevice:completionHandler:]_block_invoke"
+ "-[MXSystemCastingExtensionInstance mediaSourceDataForKeys:completionHandler:]_block_invoke"
+ "-[MXSystemCastingExtensionInstance sendData:forApplicationID:withCompletionHandler:]_block_invoke"
+ "-[MXSystemCastingExtensionInstance setVolume:forDevice:completionHandler:]_block_invoke"
+ "-[MXSystemCastingExtensionInstance startApplicationWithURL:applicationID:launchType:withCompletionHandler:]_block_invoke"
+ "00:52:54"
+ "Aug 10 2026"
+ "SemaphoreTimedOut"
+ "Send data operation failed"
+ "dataLength"
+ "mxsmccs_SetActiveClient"
+ "result"
+ "success"
- "-MXSystemMediaCasting- %s: <%{public}@> extension did not respond to '%{public}@': %{public}@"
- "-MXSystemMediaCasting- %s: <%{public}@> terminating unresponsive extension after '%{public}@' timed out"
- "-MXSystemMediaCastingController_Client- %s: No pending handler for requestID %llu"
- "-[MXSystemCastingExtensionInstance mediaSourceDataForKeys:completionHandler:]_block_invoke_2"
- "-[MXSystemCastingExtensionInstance noteUnresponsiveExtensionForOperation:error:]"
- "-[MXSystemCastingExtensionInstance sendData:forApplicationID:withCompletionHandler:]_block_invoke_2"
- "-[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]_block_invoke_3"
- "-[MXSystemCastingExtensionInstance startApplicationWithURL:applicationID:launchType:withCompletionHandler:]_block_invoke_2"
- "-[MXSystemMediaCastingController_Client handleAsyncResult:]"
- "08:54:07"
- "Aug  4 2026"
- "Extension was unresponsive to a request"
- "RequestID"
- "Result"
- "activateDevice"
- "com.apple.mediaexperience.SystemCastingExtension"
- "deactivateDevice"
- "decreaseVolume"
- "getVolume"
- "increaseVolume"
- "mediaSourceData"
- "sendData"
- "setVolume"
- "startApplication"
- "v24@?0@\"<MediaDeviceServerInterface>\"8@?<v@?@\"NSDictionary\">16"
- "v24@?0@\"NSError\"8@\"NSDictionary\"16"
```
