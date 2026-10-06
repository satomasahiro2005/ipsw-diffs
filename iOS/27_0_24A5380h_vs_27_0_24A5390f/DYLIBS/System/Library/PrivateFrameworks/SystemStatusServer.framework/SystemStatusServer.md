## SystemStatusServer

> `/System/Library/PrivateFrameworks/SystemStatusServer.framework/SystemStatusServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fac4` | `0x20774` | **`+0xcb0`** |
| `__TEXT.__oslogstring` | `0xaee` | `0xe55` | **`+0x367`** |
| `__AUTH_CONST.__objc_const` | `0x4260` | `0x44f8` | **`+0x298`** |
| `__TEXT.__objc_methlist` | `0x1d90` | `0x1e98` | **`+0x108`** |
| `__TEXT.__cstring` | `0x1c7a` | `0x1d3b` | **`+0xc1`** |
| `__DATA_CONST.__objc_selrefs` | `0x1358` | `0x1418` | **`+0xc0`** |
| `__AUTH_CONST.__cfstring` | `0x1760` | `0x17e0` | **`+0x80`** |
| `__AUTH.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xdd8` | `0xe28` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x870` | `0x8a0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x410` | `0x438` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x2a4` | `0x2c8` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x328` | `0x33c` | **`+0x14`** |
| `__DATA_DIRTY.__bss` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x128` | `0x130` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x108` | `0x110` | **`+0x8`** |
| `__TEXT.__const` | `0xd0` | `0xd8` | **`+0x8`** |

### Other Changes

```diff

-282.0.0.0.0
+284.1.0.0.0

-  Functions: 740
-  Symbols:   1666
-  CStrings:  286
+  Functions: 766
+  Symbols:   1718
+  CStrings:  303
Symbols:
+ +[STStatusDomainPublisherXPCClientHandle _serverCompletionForXPCReplyBlock:]
+ -[STStatusDomainXPCClientWakeUpAssertion .cxx_destruct]
+ -[STStatusDomainXPCClientWakeUpAssertion _acquireNewHandleMessageAssertion]
+ -[STStatusDomainXPCClientWakeUpAssertion _invalidateHandleMessageAssertion]
+ -[STStatusDomainXPCClientWakeUpAssertion acquire]
+ -[STStatusDomainXPCClientWakeUpAssertion assertionAcquisitionCount]
+ -[STStatusDomainXPCClientWakeUpAssertion clientIsRunningBoardManaged]
+ -[STStatusDomainXPCClientWakeUpAssertion clientPID]
+ -[STStatusDomainXPCClientWakeUpAssertion dealloc]
+ -[STStatusDomainXPCClientWakeUpAssertion handleMessageAssertionAcquisitionTimestamp]
+ -[STStatusDomainXPCClientWakeUpAssertion handleMessageAssertion]
+ -[STStatusDomainXPCClientWakeUpAssertion initWithClientAuditToken:queue:]
+ -[STStatusDomainXPCClientWakeUpAssertion invalidateHandleMessageAssertionTimer]
+ -[STStatusDomainXPCClientWakeUpAssertion invalidate]
+ -[STStatusDomainXPCClientWakeUpAssertion isInvalidated]
+ -[STStatusDomainXPCClientWakeUpAssertion queue]
+ -[STStatusDomainXPCClientWakeUpAssertion relinquish]
+ -[STStatusDomainXPCClientWakeUpAssertion setAssertionAcquisitionCount:]
+ -[STStatusDomainXPCClientWakeUpAssertion setHandleMessageAssertion:]
+ -[STStatusDomainXPCClientWakeUpAssertion setHandleMessageAssertionAcquisitionTimestamp:]
+ -[STStatusDomainXPCClientWakeUpAssertion setInvalidateHandleMessageAssertionTimer:]
+ -[STStatusDomainXPCClientWakeUpAssertion setInvalidated:]
+ GCC_except_table5
+ _BSFloatLessThanFloat
+ _OBJC_CLASS_$_NSXPCConnection
+ _OBJC_CLASS_$_RBSAssertion
+ _OBJC_CLASS_$_RBSDomainAttribute
+ _OBJC_CLASS_$_RBSTarget
+ _OBJC_CLASS_$_STStatusDomainXPCClientWakeUpAssertion
+ _OBJC_IVAR_$_STStatusDomainXPCClientHandle._clientWakeUpAssertion
+ _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._assertionAcquisitionCount
+ _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._clientIsRunningBoardManaged
+ _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._clientPID
+ _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._handleMessageAssertion
+ _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._handleMessageAssertionAcquisitionTimestamp
+ _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._invalidateHandleMessageAssertionTimer
+ _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._invalidated
+ _OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._queue
+ _OBJC_METACLASS_$_STStatusDomainXPCClientWakeUpAssertion
+ _STSystemStatusLogClientWakeUp
+ __OBJC_$_INSTANCE_METHODS_STStatusDomainXPCClientWakeUpAssertion
+ __OBJC_$_INSTANCE_VARIABLES_STStatusDomainXPCClientWakeUpAssertion
+ __OBJC_$_PROP_LIST_STStatusDomainXPCClientWakeUpAssertion
+ __OBJC_CLASS_PROTOCOLS_$_STStatusDomainXPCClientWakeUpAssertion
+ __OBJC_CLASS_RO_$_STStatusDomainXPCClientWakeUpAssertion
+ __OBJC_METACLASS_RO_$_STStatusDomainXPCClientWakeUpAssertion
+ ___52-[STStatusDomainXPCClientWakeUpAssertion relinquish]_block_invoke
+ ___76+[STStatusDomainPublisherXPCClientHandle _serverCompletionForXPCReplyBlock:]_block_invoke
+ ___STSystemStatusLogClientWakeUp_block_invoke
+ ___block_descriptor_40_e8_32bs_e37_v16?0"NSObject<OS_dispatch_queue>"8ls32l8
+ ___block_descriptor_40_e8_32w_e31_v16?0"BSContinuousMachTimer"8lw32l8
+ ___block_descriptor_74_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
+ _objc_opt_self
+ _objc_retainBlock
- ___block_descriptor_74_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
- _dispatch_block_create
CStrings:
+ "ClientWakeUp"
+ "Observer-HandleMessage"
+ "STStatusDomainXPCClientWakeUpAssertion:%d"
+ "SYSTEMSTATUSSERVER CLIENT ERROR: attempted to acquire wake up assertion that was invalidated"
+ "SYSTEMSTATUSSERVER CLIENT ERROR: attempted to relinquish wake up assertion that was invalidated"
+ "SYSTEMSTATUSSERVER CLIENT ERROR: invalidated wake up assertion that was already invalidated"
+ "SYSTEMSTATUSSERVER CLIENT ERROR: wake up assertion deallocated without being invalidated"
+ "SystemStatus sending update to observer client: %d"
+ "cancelling scheduled invalidation of Observer-HandleMessage assertion for client: %d"
+ "com.apple.systemstatusd"
+ "creating new Observer-HandleMessage assertion for client: %d"
+ "failed to acquire Observer-HandleMessage assertion for client: %d"
+ "invalidating Observer-HandleMessage assertion immediately for client: %d"
+ "performing scheduled invalidation of Observer-HandleMessage assertion for client: %d"
+ "reusing Observer-HandleMessage assertion for client: %d"
+ "scheduling invalidation of Observer-HandleMessage assertion for client: %d"
+ "v16@?0@\"NSObject<OS_dispatch_queue>\"8"
```
