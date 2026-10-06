## CloudDocs

> `/System/Library/PrivateFrameworks/CloudDocs.framework/CloudDocs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e7cc` | `0x7f0bc` | **`+0x8f0`** |
| `__AUTH_CONST.__objc_const` | `0xda18` | `0xdb30` | **`+0x118`** |
| `__TEXT.__cstring` | `0xb775` | `0xb87c` | **`+0x107`** |
| `__TEXT.__oslogstring` | `0x8c91` | `0x8d76` | **`+0xe5`** |
| `__TEXT.__gcc_except_tab` | `0x3aec` | `0x3bc0` | **`+0xd4`** |
| `__TEXT.__objc_methlist` | `0x668c` | `0x66ec` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x14f0` | `0x1540` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2608` | `0x2640` | **`+0x38`** |
| `__AUTH_CONST.__cfstring` | `0x5f40` | `0x5f20` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0x1060` | `0x1080` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4230` | `0x4250` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x5d4` | `0x5e8` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x310` | `0x318` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x238` | `0x240` | **`+0x8`** |

### Other Changes

```diff

-5044.0.0.0.0
+5140.0.0.0.0

-  Functions: 3015
-  Symbols:   5086
-  CStrings:  2194
+  Functions: 3030
+  Symbols:   5110
+  CStrings:  2202
Symbols:
+ +[BRPosixOperationsWrapper processCanUseArbitraryPersonas]
+ -[BRContainersMonitor _checkChangesForContainerID:personaID:]
+ -[BRUploadAllFilesOperation initWithContainerID:]
+ -[BRWaitForContainersDownloadOperation .cxx_destruct]
+ -[BRWaitForContainersDownloadOperation cancel]
+ -[BRWaitForContainersDownloadOperation downloadCompletionBlock]
+ -[BRWaitForContainersDownloadOperation finishWithResult:error:]
+ -[BRWaitForContainersDownloadOperation initWithContainerIdentifiers:]
+ -[BRWaitForContainersDownloadOperation main]
+ -[BRWaitForContainersDownloadOperation setDownloadCompletionBlock:]
+ -[NSError(BRFPAdditions) _br_fileProviderErrorWithFallbackFileProviderErrorCode:isSpeculativeDownload:]
+ -[NSError(BRFPAdditions) _br_getFileProviderDomainErrorCode:isSpeculativeDownload:]
+ -[NSError(BRFPAdditions) br_fileProviderErrorForDownloadFlowWithIsSpeculative:]
+ GCC_except_table24
+ _OBJC_CLASS_$_BRWaitForContainersDownloadOperation
+ _OBJC_IVAR_$_BRContainersMonitor._latestContainerForegroundStatusByPersonaID
+ _OBJC_IVAR_$_BRContainersMonitor._observersByPersonaIDAndContainerID
+ _OBJC_IVAR_$_BRContainersMonitor._queue
+ _OBJC_IVAR_$_BRDownloadAndUploadAllFilesForLogOutOperation._downloadOp
+ _OBJC_IVAR_$_BRUploadAllFilesOperation._containerID
+ _OBJC_IVAR_$_BRWaitForContainersDownloadOperation._containerIdentifiers
+ _OBJC_IVAR_$_BRWaitForContainersDownloadOperation._downloadCompletionBlock
+ _OBJC_IVAR_$_BRWaitForContainersDownloadOperation._fileCoordinators
+ _OBJC_IVAR_$_BRWaitForContainersDownloadOperation._internalQueue
+ _OBJC_METACLASS_$_BRWaitForContainersDownloadOperation
+ __OBJC_$_INSTANCE_METHODS_BRWaitForContainersDownloadOperation
+ __OBJC_$_INSTANCE_VARIABLES_BRWaitForContainersDownloadOperation
+ __OBJC_$_PROP_LIST_BRWaitForContainersDownloadOperation
+ __OBJC_CLASS_RO_$_BRWaitForContainersDownloadOperation
+ __OBJC_METACLASS_RO_$_BRWaitForContainersDownloadOperation
+ ___28-[BRContainersMonitor close]_block_invoke
+ ___44-[BRWaitForContainersDownloadOperation main]_block_invoke
+ ___53-[BRDownloadAndUploadAllFilesForLogOutOperation main]_block_invoke_2
+ ___61-[BRContainersMonitor _checkChangesForContainerID:personaID:]_block_invoke
+ ___83-[NSError(BRFPAdditions) _br_getFileProviderDomainErrorCode:isSpeculativeDownload:]_block_invoke
+ ___block_descriptor_57_e8_32s40s48w_e5_v8?0lw48l8s32l8s40l8
+ __br_getFileProviderDomainErrorCode:isSpeculativeDownload:.cloudKitErrorToFPError
+ __br_getFileProviderDomainErrorCode:isSpeculativeDownload:.clouddocsErrorToFPError
+ __br_getFileProviderDomainErrorCode:isSpeculativeDownload:.cocoaErrorToFPError
+ __br_getFileProviderDomainErrorCode:isSpeculativeDownload:.once
- -[BRContainersMonitor _checkChangesForConainerID:]
- -[BRRemoteUserDefaults minFileSizeForThumbnailTransfer]
- -[NSError(BRFPAdditions) _br_fileProviderErrorWithFallbackFileProviderErrorCode:]
- -[NSError(BRFPAdditions) _br_getFileProviderDomainErrorCode:]
- OBJC_IVAR_$_BRContainersMonitor._observersByContainerID
- OBJC_IVAR_$_BRContainersMonitor._queue
- _OBJC_IVAR_$_BRContainersMonitor._observedContainerIDsToLatestForegroundStatus
- _OBJC_IVAR_$_BRDownloadAndUploadAllFilesForLogOutOperation._fileCoordinators
- ___50-[BRContainersMonitor _checkChangesForConainerID:]_block_invoke
- ___55-[BRRemoteUserDefaults minFileSizeForThumbnailTransfer]_block_invoke
- ___61-[NSError(BRFPAdditions) _br_getFileProviderDomainErrorCode:]_block_invoke
- ___block_descriptor_49_e8_32s40w_e5_v8?0lw40l8s32l8
- __br_getFileProviderDomainErrorCode:.cloudKitErrorToFPError
- __br_getFileProviderDomainErrorCode:.clouddocsErrorToFPError
- __br_getFileProviderDomainErrorCode:.cocoaErrorToFPError
- __br_getFileProviderDomainErrorCode:.once
CStrings:
+ "-[BRContainersMonitor _checkChangesForContainerID:personaID:]"
+ "-[BRContainersMonitor _checkChangesForContainerID:personaID:]_block_invoke"
+ "-[BRDownloadAndUploadAllFilesForLogOutOperation main]_block_invoke_2"
+ "-[BRWaitForContainersDownloadOperation cancel]"
+ "-[BRWaitForContainersDownloadOperation finishWithResult:error:]"
+ "-[BRWaitForContainersDownloadOperation main]"
+ "-[BRWaitForContainersDownloadOperation main]_block_invoke"
+ "5140"
+ "BRNotifyNameForForegroundChangeWithContainerID"
+ "[CRIT] Assertion failed: personaID%@"
+ "[DEBUG] %@ (persona %@) is now %s%@"
+ "[DEBUG] Container %@ (persona %@) foreground changed (%@ -> %d)%@"
+ "[DEBUG] Notifying that container %@ (persona %@) is now %s%@"
+ "[DEBUG] completed download%@"
+ "[DEBUG] ┏%llx Adding observer for %@ (persona %@)%@"
+ "[DEBUG] ┏%llx Removing observer for %@ (persona %@)%@"
+ "[ERROR] invalid owner name, expected regex %@%@"
+ "[NOTICE] downloading all files for containers: %@%@"
+ "[NOTICE] waiting for containers download finished\n status: %@%@"
+ "[WARNING] invalid container name, expected regex %@%@"
+ "[WARNING] invalid container name, max length is %u%@"
+ "[WARNING] invalid library name%@"
- "-[BRContainersMonitor _checkChangesForConainerID:]"
- "-[BRContainersMonitor _checkChangesForConainerID:]_block_invoke"
- "-[BRDownloadAndUploadAllFilesForLogOutOperation cancel]"
- "5044"
- "[DEBUG] %@ is now %s%@"
- "[DEBUG] Container %@ foreground changed (%@ -> %d)%@"
- "[DEBUG] Notifying that container %@ is now %s%@"
- "[DEBUG] ┏%llx Adding observer for %@%@"
- "[DEBUG] ┏%llx Removing observer for %@%@"
- "[ERROR] invalid owner name '%@', expected regex %@%@"
- "[WARNING] invalid container name '%@', expected regex %@%@"
- "[WARNING] invalid container name '%@', max length is %u%@"
- "[WARNING] invalid library name %@%@"
- "min-file-size-for-thumb-transfer"
```
