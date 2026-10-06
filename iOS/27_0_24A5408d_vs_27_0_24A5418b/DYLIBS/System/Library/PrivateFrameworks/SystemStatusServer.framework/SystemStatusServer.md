## SystemStatusServer

> `/System/Library/PrivateFrameworks/SystemStatusServer.framework/SystemStatusServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21038` | `0x1fc7c` | **`-0x13bc`** |
| `__TEXT.__oslogstring` | `0x1001` | `0xaee` | **`-0x513`** |
| `__AUTH_CONST.__objc_const` | `0x4528` | `0x4260` | **`-0x2c8`** |
| `__TEXT.__objc_methlist` | `0x1ef8` | `0x1d90` | **`-0x168`** |
| `__DATA_CONST.__objc_selrefs` | `0x1490` | `0x1370` | **`-0x120`** |
| `__TEXT.__cstring` | `0x1dd5` | `0x1cde` | **`-0xf7`** |
| `__AUTH_CONST.__cfstring` | `0x1840` | `0x1780` | **`-0xc0`** |
| `__AUTH_CONST.__const` | `0x2e0` | `0x280` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x8c8` | `0x870` | **`-0x58`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x450` | `0x418` | **`-0x38`** |
| `__TEXT.__gcc_except_tab` | `0x35c` | `0x328` | **`-0x34`** |
| `__DATA.__objc_ivar` | `0x2cc` | `0x2a4` | **`-0x28`** |
| `__DATA_CONST.__const` | `0xe28` | `0xe00` | **`-0x28`** |
| `__DATA_DIRTY.__bss` | `0x80` | `0x60` | **`-0x20`** |
| `__TEXT.__const` | `0xe0` | `0xd0` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x130` | `0x128` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x110` | `0x108` | **`-0x8`** |

### Other Changes

```diff

-286.101.0.0.0
+286.104.0.0.0

-  Functions: 777
-  Symbols:   1735
-  CStrings:  314
+  Functions: 741
+  Symbols:   1671
+  CStrings:  288
Symbols:
+ _BSDispatchQueueCreateSerialWithQoS
- +[STStatusDomainXPCClientWakeUpAssertion _watchdogQueue]
- -[STStatusDomainXPCClientWakeUpAssertion .cxx_destruct]
- -[STStatusDomainXPCClientWakeUpAssertion _acquireNewHandleMessageAssertion]
- -[STStatusDomainXPCClientWakeUpAssertion _cancelWatchdogTimer]
- -[STStatusDomainXPCClientWakeUpAssertion _invalidateHandleMessageAssertion]
- -[STStatusDomainXPCClientWakeUpAssertion _startNewWatchdogTimer]
- -[STStatusDomainXPCClientWakeUpAssertion _terminateClient]
- -[STStatusDomainXPCClientWakeUpAssertion _watchdogQueue_cancelWatchdogTimer]
- -[STStatusDomainXPCClientWakeUpAssertion acquire]
- -[STStatusDomainXPCClientWakeUpAssertion assertionAcquisitionCount]
- -[STStatusDomainXPCClientWakeUpAssertion clientIsRunningBoardManaged]
- -[STStatusDomainXPCClientWakeUpAssertion clientPID]
- -[STStatusDomainXPCClientWakeUpAssertion dealloc]
- -[STStatusDomainXPCClientWakeUpAssertion handleMessageAssertionAcquisitionTimestamp]
- -[STStatusDomainXPCClientWakeUpAssertion handleMessageAssertion]
- -[STStatusDomainXPCClientWakeUpAssertion initWithClientAuditToken:queue:]
- -[STStatusDomainXPCClientWakeUpAssertion invalidateHandleMessageAssertionTimer]
- -[STStatusDomainXPCClientWakeUpAssertion invalidate]
- -[STStatusDomainXPCClientWakeUpAssertion isInvalidated]
- -[STStatusDomainXPCClientWakeUpAssertion queue]
- -[STStatusDomainXPCClientWakeUpAssertion relinquish]
- -[STStatusDomainXPCClientWakeUpAssertion setAssertionAcquisitionCount:]
- -[STStatusDomainXPCClientWakeUpAssertion setHandleMessageAssertion:]
- -[STStatusDomainXPCClientWakeUpAssertion setHandleMessageAssertionAcquisitionTimestamp:]
- -[STStatusDomainXPCClientWakeUpAssertion setInvalidateHandleMessageAssertionTimer:]
- -[STStatusDomainXPCClientWakeUpAssertion setInvalidated:]
- -[STStatusDomainXPCClientWakeUpAssertion setWatchdogTimer:]
- -[STStatusDomainXPCClientWakeUpAssertion watchdogTimer]
- GCC_except_table12
- GCC_except_table5
- _BSFloatLessThanFloat
- _BSStringFromBOOL
- _OBJC_CLASS_$_RBSAssertion
- _OBJC_CLASS_$_RBSDomainAttribute
- _OBJC_CLASS_$_RBSProcessPredicate
- _OBJC_CLASS_$_RBSTarget
- _OBJC_CLASS_$_RBSTerminateContext
- _OBJC_CLASS_$_RBSTerminateRequest
- _OBJC_CLASS_$_STStatusDomainXPCClientWakeUpAssertion
- _OBJC_IVAR_$_STStatusDomainXPCClientHandle._clientWakeUpAssertion
- _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._assertionAcquisitionCount
- _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._clientIsRunningBoardManaged
- _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._clientPID
- _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._handleMessageAssertion
- _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._handleMessageAssertionAcquisitionTimestamp
- _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._invalidateHandleMessageAssertionTimer
- _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._invalidated
- _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._queue
- _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._watchdogTimer
- _OBJC_METACLASS_$_STStatusDomainXPCClientWakeUpAssertion
- _STSystemStatusLogClientWakeUp
- __OBJC_$_CLASS_METHODS_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_$_INSTANCE_METHODS_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_$_INSTANCE_VARIABLES_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_$_PROP_LIST_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_CLASS_PROTOCOLS_$_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_CLASS_RO_$_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_METACLASS_RO_$_STStatusDomainXPCClientWakeUpAssertion
- ___52-[STStatusDomainXPCClientWakeUpAssertion relinquish]_block_invoke
- ___56+[STStatusDomainXPCClientWakeUpAssertion _watchdogQueue]_block_invoke
- ___62-[STStatusDomainXPCClientWakeUpAssertion _cancelWatchdogTimer]_block_invoke
- ___64-[STStatusDomainXPCClientWakeUpAssertion _startNewWatchdogTimer]_block_invoke
- ___73-[STStatusDomainXPCClientHandle observeData:forDomain:withChangeContext:]_block_invoke_5
- ___STSystemStatusLogClientWakeUp_block_invoke
- ___block_descriptor_40_e8_32w_e31_v16?0"BSContinuousMachTimer"8lw32l8
CStrings:
+ "com.apple.systemstatus.publisher.xpcconnectionqueue.client-%d"
- "ClientWakeUp"
- "Observer-HandleMessage"
- "STStatusDomainXPCClientWakeUpAssertion-Watchdog:%d"
- "STStatusDomainXPCClientWakeUpAssertion:%d"
- "SYSTEMSTATUSSERVER CLIENT ERROR: attempted to acquire wake up assertion that was invalidated"
- "SYSTEMSTATUSSERVER CLIENT ERROR: attempted to relinquish wake up assertion that was invalidated"
- "SYSTEMSTATUSSERVER CLIENT ERROR: invalidated wake up assertion that was already invalidated"
- "SYSTEMSTATUSSERVER CLIENT ERROR: wake up assertion deallocated without being invalidated"
- "SystemStatus observer watchdog - unresponsive client: %d"
- "SystemStatus sending update to observer client: %d"
- "cancelling scheduled invalidation of Observer-HandleMessage assertion for client: %d"
- "cancelling watchdog timer for client: %d"
- "com.apple.systemstatus.observer.watchdogqueue"
- "com.apple.systemstatusd"
- "creating new Observer-HandleMessage assertion for client: %d"
- "failed to acquire Observer-HandleMessage assertion for client: %d"
- "initialized wake up assertion for client: %d - RunningBoard managed: %@"
- "invalidating Observer-HandleMessage assertion immediately for client: %d"
- "invalidating wake up assertion for client: %d"
- "performing scheduled invalidation of Observer-HandleMessage assertion for client: %d"
- "reusing Observer-HandleMessage assertion for client: %d"
- "scheduling invalidation of Observer-HandleMessage assertion for client: %d"
- "starting new watchdog timer for client: %d"
- "wake up assertion failed to create process handle for client: %d"
- "wake up assertion failed to create process handle for client: %d - error: %@"
- "watchdog failed to terminate client: %d - error: %@"
- "watchdog terminating client: %d"
```
