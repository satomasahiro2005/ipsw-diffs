## SystemStatusServer

> `/System/Library/PrivateFrameworks/SystemStatusServer.framework/SystemStatusServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20774` | `0x21038` | **`+0x8c4`** |
| `__TEXT.__oslogstring` | `0xe55` | `0x1001` | **`+0x1ac`** |
| `__TEXT.__cstring` | `0x1d3b` | `0x1dd5` | **`+0x9a`** |
| `__DATA_CONST.__objc_selrefs` | `0x1418` | `0x1490` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `0x17e0` | `0x1840` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1e98` | `0x1ef8` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x44f8` | `0x4528` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x8a0` | `0x8c8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x33c` | `0x35c` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x438` | `0x450` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT.__const` | `0xd8` | `0xe0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2c8` | `0x2cc` | **`+0x4`** |

### Other Changes

```diff

-284.1.0.0.0
+286.101.0.0.0

-  Functions: 766
-  Symbols:   1718
-  CStrings:  303
+  Functions: 777
+  Symbols:   1735
+  CStrings:  314
Symbols:
+ +[STStatusDomainXPCClientWakeUpAssertion _watchdogQueue]
+ -[STStatusDomainXPCClientWakeUpAssertion _cancelWatchdogTimer]
+ -[STStatusDomainXPCClientWakeUpAssertion _startNewWatchdogTimer]
+ -[STStatusDomainXPCClientWakeUpAssertion _terminateClient]
+ -[STStatusDomainXPCClientWakeUpAssertion _watchdogQueue_cancelWatchdogTimer]
+ -[STStatusDomainXPCClientWakeUpAssertion setWatchdogTimer:]
+ -[STStatusDomainXPCClientWakeUpAssertion watchdogTimer]
+ GCC_except_table12
+ _BSStringFromBOOL
+ _OBJC_CLASS_$_RBSProcessPredicate
+ _OBJC_CLASS_$_RBSTerminateContext
+ _OBJC_CLASS_$_RBSTerminateRequest
+ _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._watchdogTimer
+ __OBJC_$_CLASS_METHODS_STStatusDomainXPCClientWakeUpAssertion
+ ___56+[STStatusDomainXPCClientWakeUpAssertion _watchdogQueue]_block_invoke
+ ___62-[STStatusDomainXPCClientWakeUpAssertion _cancelWatchdogTimer]_block_invoke
+ ___64-[STStatusDomainXPCClientWakeUpAssertion _startNewWatchdogTimer]_block_invoke
CStrings:
+ "STStatusDomainXPCClientWakeUpAssertion-Watchdog:%d"
+ "SystemStatus observer watchdog - unresponsive client: %d"
+ "cancelling watchdog timer for client: %d"
+ "com.apple.systemstatus.observer.watchdogqueue"
+ "initialized wake up assertion for client: %d - RunningBoard managed: %@"
+ "invalidating wake up assertion for client: %d"
+ "starting new watchdog timer for client: %d"
+ "wake up assertion failed to create process handle for client: %d"
+ "wake up assertion failed to create process handle for client: %d - error: %@"
+ "watchdog failed to terminate client: %d - error: %@"
+ "watchdog terminating client: %d"
```
