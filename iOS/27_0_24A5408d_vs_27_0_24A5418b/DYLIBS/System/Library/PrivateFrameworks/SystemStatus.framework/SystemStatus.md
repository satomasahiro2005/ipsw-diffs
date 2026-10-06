## SystemStatus

> `/System/Library/PrivateFrameworks/SystemStatus.framework/SystemStatus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59774` | `0x59810` | **`+0x9c`** |
| `__TEXT.__cstring` | `0x3f47` | `0x3f7a` | **`+0x33`** |
| `__AUTH_CONST.__cfstring` | `0x4880` | `0x48a0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fc0` | `0x1fc8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x42c` | `0x430` | **`+0x4`** |

### Other Changes

```diff

-286.101.0.0.0
+286.104.0.0.0

-  Functions: 3177
-  Symbols:   5620
-  CStrings:  769
+  Functions: 3178
+  Symbols:   5621
+  CStrings:  770
Symbols:
+ _BSDispatchBlockCreateWithQualityOfService
+ _st_dispatch_sync_user_initiated
- _BSDispatchQueueCreateSerial
Functions:
~ -[STStatusDomainXPCServerHandle _internalQueue_setupXPCConnectionIfNecessary] : 516 -> 552
~ -[STStatusDomainXPCServerHandle initWithXPCConnectionProvider:serverLaunchObservable:] : 380 -> 384
- ___77-[STStatusDomainXPCServerHandle _internalQueue_setupXPCConnectionIfNecessary]_block_invoke.31
~ -[STLocalDynamicActivityAttributionManager init] : 180 -> 184
+ ___77-[STStatusDomainXPCServerHandle _internalQueue_setupXPCConnectionIfNecessary]_block_invoke.34
~ -[STDynamicActivityAttributionPublisher init] : 140 -> 144
+ _st_dispatch_sync_user_initiated
~ -[STStatusDomainPublisherXPCServerHandle initWithXPCConnectionProvider:serverLaunchObservable:] : 560 -> 564
CStrings:
+ "com.apple.systemstatus.observer.xpcconnectionqueue"
```
