## CoreCDPInternal

> `/System/Library/PrivateFrameworks/CoreCDPInternal.framework/CoreCDPInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8f7e8` | `0x9011c` | **`+0x934`** |
| `__AUTH_CONST.__objc_const` | `0x100f0` | `0x10260` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x1503e` | `0x1511e` | **`+0xe0`** |
| `__TEXT.__cstring` | `0xe5b5` | `0xe685` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x98a0` | `0x9940` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x5774` | `0x57ec` | **`+0x78`** |
| `__AUTH.__objc_data` | `0x120` | `0x170` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x39b8` | `0x3a00` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x1e70` | `0x1e98` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x3b8` | `0x3d0` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x2608` | `0x2610` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1128` | `0x1130` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x298` | `0x2a0` | **`+0x8`** |

### Other Changes

```diff

-448.125.5.1.0
+448.125.5.2.0

-  Functions: 3196
-  Symbols:   4191
-  CStrings:  2855
+  Functions: 3209
+  Symbols:   4217
+  CStrings:  2862
Symbols:
+ -[CDPDAsyncSecureBackupEnableTracker .cxx_destruct]
+ -[CDPDAsyncSecureBackupEnableTracker _recordOutcomeWithReason:]
+ -[CDPDAsyncSecureBackupEnableTracker _timeOutCurrentWaiter]
+ -[CDPDAsyncSecureBackupEnableTracker awaitSettleWithTimeout:completionHandler:]
+ -[CDPDAsyncSecureBackupEnableTracker enableStarted]
+ -[CDPDAsyncSecureBackupEnableTracker recordDidEnable:error:]
+ -[CDPDAsyncSecureBackupEnableTracker recordEnableStarted]
+ -[CDPDStateMachine _afterAsyncSecureBackupEnableSettles:]
+ -[CDPDStateMachine initWithContext:uiProvider:asyncSecureBackupEnableTracker:]
+ GCC_except_table121
+ GCC_except_table35
+ _CDPDAsyncSecureBackupEnableTrackerErrorDomain
+ _OBJC_CLASS_$_CDPDAsyncSecureBackupEnableTracker
+ _OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._didRecordOutcome
+ _OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._enableStarted
+ _OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._lock
+ _OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._outcomeReason
+ _OBJC_IVAR_$_CDPDAsyncSecureBackupEnableTracker._waiter
+ _OBJC_IVAR_$_CDPDStateMachine._asyncSecureBackupEnableTracker
+ _OBJC_METACLASS_$_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_$_INSTANCE_METHODS_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_$_INSTANCE_VARIABLES_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_$_PROP_LIST_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_CLASS_RO_$_CDPDAsyncSecureBackupEnableTracker
+ __OBJC_METACLASS_RO_$_CDPDAsyncSecureBackupEnableTracker
+ ___54-[CDPDStateMachine _attemptPDPFallbackWithCompletion:]_block_invoke_2
+ ___57-[CDPDStateMachine _afterAsyncSecureBackupEnableSettles:]_block_invoke
+ ___79-[CDPDAsyncSecureBackupEnableTracker awaitSettleWithTimeout:completionHandler:]_block_invoke
- GCC_except_table120
- GCC_except_table34
CStrings:
+ "CDPDAsyncSecureBackupEnableTracker"
+ "CDPDStateMachine: asynchronous secure-backup enable did not deliver, skipping post-Octagon PDP setup: %@"
+ "CDPDStateMachine: waiting up to %@s for asynchronous secure-backup enable to settle before post-Octagon PDP setup"
+ "DBRAsyncEnableSettleTimeout"
+ "com.apple.corecdp.pdpRecordGenerationAhead"
+ "com.apple.corecdp.pdpRecordGenerationCheckSkipped"
+ "com.apple.corecdp.pdpWrappingKeyRepair"
```
