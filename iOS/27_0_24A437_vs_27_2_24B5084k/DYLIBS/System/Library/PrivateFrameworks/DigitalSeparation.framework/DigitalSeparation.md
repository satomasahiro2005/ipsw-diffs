## DigitalSeparation

> `/System/Library/PrivateFrameworks/DigitalSeparation.framework/DigitalSeparation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a5a8` | `0x3bd64` | **`+0x17bc`** |
| `__DATA.__bss` | `0x828` | `0x9a8` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x26c4` | `0x2844` | **`+0x180`** |
| `__TEXT.__const` | `0xaf8` | `0xbc8` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x15c0` | `0x1660` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1887` | `0x1927` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x1fac` | `0x202c` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x1548` | `0x15c0` | **`+0x78`** |
| `__AUTH_CONST.__const` | `0xe88` | `0xef8` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0xdd8` | `0xe38` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x2c4` | `0x31c` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x4e88` | `0x4ed8` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x213` | `0x263` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xd90` | `0xdb8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x530` | `0x550` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x280` | `0x29c` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xb78` | `0xb8c` | **`+0x14`** |
| `__TEXT.__swift5_typeref` | `0x50e` | `0x51c` | **`+0xe`** |
| `__TEXT.__swift5_proto` | `0x54` | `0x60` | **`+0xc`** |
| `__DATA.__data` | `0x7a8` | `0x7b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x18c` | `0x194` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x38` | `0x3c` | **`+0x4`** |

### Other Changes

```diff

-653.0.1.0.0
+653.0.7.0.0

+  - /System/Library/Frameworks/FileProvider.framework/FileProvider

+  - /System/Library/Frameworks/ImageCaptureCore.framework/ImageCaptureCore

-  Functions: 1242
-  Symbols:   1815
-  CStrings:  464
+  Functions: 1275
+  Symbols:   1843
+  CStrings:  477
Symbols:
+ -[DSAppSharing addFileAccessPermissionsToAppMap:handler:]
+ -[DSAppSharing resetFileAccessPermissionsForApp:withCompletionHandler:]
+ -[DSSourceDescriptor ignoreDisplayNames]
+ -[DSTCCStorePassThrough allAppsWithFileAccess:handler:]
+ -[DSTCCStorePassThrough resetFilePermissionForApp:completionHandler:]
+ -[DSXPCSharingPermissions _consumePendingCompletion:]
+ -[DSXPCSharingPermissions _failAllPendingOperationsWithError:]
+ -[DSXPCSharingPermissions _registerPendingCompletion:]
+ -[DSXPCSharingPermissions dealloc]
+ -[DSXPCSharingPermissions remoteProxyForCompletionToken:]
+ -[DSXPCSharingPermissions safetycheckdConnectionWithFailureHandlers:]
+ -[DSXPCSharingPermissions setFailureHandlersForConnection:]
+ GCC_except_table33
+ GCC_except_table34
+ GCC_except_table39
+ GCC_except_table44
+ GCC_except_table5
+ GCC_except_table51
+ GCC_except_table9
+ _NSPOSIXErrorDomain
+ _OBJC_CLASS_$_FPAccessControlManager
+ _OBJC_CLASS_$_ICAccessManager
+ _OBJC_CLASS_$_NSUUID
+ _OBJC_IVAR_$_DSXPCSharingPermissions._connectionLock
+ _OBJC_IVAR_$_DSXPCSharingPermissions._pendingCompletions
+ _OUTLINED_FUNCTION_48
+ ___55-[DSTCCStorePassThrough allAppsWithFileAccess:handler:]_block_invoke
+ ___55-[DSTCCStorePassThrough allAppsWithFileAccess:handler:]_block_invoke_2
+ ___56-[DSAppSharing collectPermissionsForApps:queue:handler:]_block_invoke_6
+ ___57-[DSAppSharing addFileAccessPermissionsToAppMap:handler:]_block_invoke
+ ___57-[DSXPCSharingPermissions remoteProxyForCompletionToken:]_block_invoke
+ ___59-[DSXPCSharingPermissions setFailureHandlersForConnection:]_block_invoke
+ ___71-[DSAppSharing resetFileAccessPermissionsForApp:withCompletionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_64_e8_32s40bs48w_e17_v16?0"NSError"8lw48l8s40l8s32l8
+ ___block_descriptor_64_e8_32s40bs48w_e34_v24?0"NSDictionary"8"NSError"16lw48l8s40l8s32l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
+ _associated conformance 17DigitalSeparation21SafetyCheckEntrypointOSHAASQ
+ _symbolic _____ 17DigitalSeparation21SafetyCheckEntrypointO
- -[DSXPCSharingPermissions connectXPC]
- -[DSXPCSharingPermissions disconnect]
- GCC_except_table30
- GCC_except_table31
- GCC_except_table36
- GCC_except_table41
- GCC_except_table46
- ___37-[DSXPCSharingPermissions connectXPC]_block_invoke
- ___block_descriptor_56_e8_32bs40w_e17_v16?0"NSError"8lw40l8s32l8
- ___block_descriptor_56_e8_32bs40w_e34_v24?0"NSDictionary"8"NSError"16lw40l8s32l8
- ___block_descriptor_56_e8_32s40bs48w_e17_v16?0"NSError"8lw48l8s32l8s40l8
CStrings:
+ "Apple Intelligence"
+ "Attempting to reconnect to safetycheckd"
+ "Cannot connect to safetycheckd with error: %{public}@"
+ "DSFiles"
+ "Error resetting file access permissions %@"
+ "FILES"
+ "Failing pending operation %{public}@ due to connection failure"
+ "Sharing Reminder"
+ "XPC connection failure"
+ "XPC connection unavailable, consuming pending completion"
+ "com.apple.MobileSlideShow"
+ "fetchSharedResourcesWithCompletion: completion already consumed by connection failure handler"
+ "ignoreResourceDisplayName"
+ "stopSharingSources: strongSelf is nil"
+ "stopSharingWithParticipants: completion already consumed by connection failure handler"
+ "strongSelf is nil, cannot make sharing people"
- "Cannot connect to remote service with error: %{public}@"
- "Disconnecting xpc"
- "XPC connection failed, completion should be called in proxy error handler"
```
