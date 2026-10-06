## ContactsFoundation

> `/System/Library/PrivateFrameworks/ContactsFoundation.framework/ContactsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9c220` | `0x9ce34` | **`+0xc14`** |
| `__TEXT.__ustring` | `0x2e2` | `0x514` | **`+0x232`** |
| `__TEXT.__oslogstring` | `0x2818` | `0x28f8` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0xab5c` | `0xac0c` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0x3328` | `0x33a0` | **`+0x78`** |
| `__TEXT.__dlopen_cstrs` | `0x167` | `0x117` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0xaf20` | `0xaf60` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3ab8` | `0x3af0` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x38c0` | `0x38d8` | **`+0x18`** |
| `__DATA.__bss` | `0xc80` | `0xc70` | **`-0x10`** |
| `__TEXT.__cstring` | `0x7224` | `0x7214` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x123c` | `0x122c` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x388` | `0x398` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x11f0` | `0x11f8` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x16620` | `0x16628` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x5f8` | `0x5f0` | **`-0x8`** |

### Other Changes

```diff

-1427.100.1.0.0
+1430.200.21.0.0

-  Functions: 5236
-  Symbols:   8736
+  Functions: 5265
+  Symbols:   8757
Symbols:
+ -[CNBlockCountingSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[CNCallStackRecordingSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[CNCoalescingSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[CNInhibitingSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[CNQualityOfServiceSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[CNSuspendableSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[CNTimeProfilingSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[CNVirtualScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[_CNImmediateScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[_CNInlineScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[_CNJumpToMainQueueScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[_CNJumpToMainRunLoopScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[_CNMainThreadScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[_CNOffMainThreadScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[_CNOperationQueueScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[_CNQueueScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]
+ -[_CNSynchronousQueueScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]
+ _CNProcessSharedLockSandboxHintKey
+ ___36-[CNProcessSharedLock openLockFile:]_block_invoke_2
+ ___77-[_CNQueueScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___77-[_CNQueueScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke_2
+ ___78-[CNVirtualScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___78-[_CNInlineScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___78-[_CNInlineScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke_2
+ ___85-[_CNOffMainThreadScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___86-[_CNOperationQueueScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___87-[_CNJumpToMainQueueScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___88-[_CNSynchronousQueueScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___89-[_CNJumpToMainRunLoopScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___89-[_CNJumpToMainRunLoopScheduler afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke_2
+ ___90-[CNCoalescingSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___90-[CNInhibitingSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___91-[CNSuspendableSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___91-[CNSuspendableSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke_2
+ ___93-[CNBlockCountingSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___93-[CNTimeProfilingSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___98-[CNCallStackRecordingSchedulerDecorator afterDelay:performBlock:delayTolerance:qualityOfService:]_block_invoke
+ ___block_descriptor_44_e8_32s_e14_"NSError"8?0ls32l8
+ ___block_descriptor_80_e8_32s40s48s56r64r72w_e5_v8?0lw72l8s32l8r56l8r64l8s40l8s48l8
+ ___block_descriptor_88_e8_32s40s48s56s64r72r80w_e5_v8?0ls32l8w80l8s40l8r64l8r72l8s48l8s56l8
+ _strerror
- -[CNFeatureFlags isUIKitEnhancedLandscapeEnabled]
- _UIKitCoreLibraryCore.frameworkLibrary
- ___62-[_CNQueueScheduler afterDelay:performBlock:qualityOfService:]_block_invoke
- ___62-[_CNQueueScheduler afterDelay:performBlock:qualityOfService:]_block_invoke_2
- ___63-[CNVirtualScheduler afterDelay:performBlock:qualityOfService:]_block_invoke
- ___63-[_CNInlineScheduler afterDelay:performBlock:qualityOfService:]_block_invoke
- ___63-[_CNInlineScheduler afterDelay:performBlock:qualityOfService:]_block_invoke_2
- ___71-[_CNOperationQueueScheduler afterDelay:performBlock:qualityOfService:]_block_invoke
- ___72-[_CNJumpToMainQueueScheduler afterDelay:performBlock:qualityOfService:]_block_invoke
- ___73-[_CNSynchronousQueueScheduler afterDelay:performBlock:qualityOfService:]_block_invoke
- ___74-[_CNJumpToMainRunLoopScheduler afterDelay:performBlock:qualityOfService:]_block_invoke
- ___74-[_CNJumpToMainRunLoopScheduler afterDelay:performBlock:qualityOfService:]_block_invoke_2
- ___76-[CNSuspendableSchedulerDecorator afterDelay:performBlock:qualityOfService:]_block_invoke
- ___76-[CNSuspendableSchedulerDecorator afterDelay:performBlock:qualityOfService:]_block_invoke_2
- ___UIKitCoreLibraryCore_block_invoke
- ___block_descriptor_72_e8_32s40s48s56r64w_e5_v8?0lw64l8s32l8r56l8s40l8s48l8
- ___block_descriptor_80_e8_32s40s48s56s64r72w_e5_v8?0ls32l8w72l8s40l8r64l8s48l8s56l8
- ___get_UIEnhancedLandscapeEnabledSymbolLoc_block_invoke
- _audit_stringUIKitCore
- _get_UIEnhancedLandscapeEnabledSymbolLoc.ptr
CStrings:
+ "CNProcessSharedLockSandboxHint"
+ "Failed to open shared lock file %{public}@ (errno=%d %{public}s). This is usually a client sandbox denial — the process's sandbox profile must grant the AddressBook locks directory (import contacts.sb). See rdar://147462310."
+ "The lock file could not be opened because of a permission denial (EPERM/EACCES). This is usually a client sandbox denial — the process's sandbox profile must grant the AddressBook locks directory (.AddressBookLocks), typically by importing contacts.sb and calling contacts-client."
- "_UIEnhancedLandscapeEnabled"
- "enhanced_landscape_contacts"
- "softlink:r:path:/System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore"
```
