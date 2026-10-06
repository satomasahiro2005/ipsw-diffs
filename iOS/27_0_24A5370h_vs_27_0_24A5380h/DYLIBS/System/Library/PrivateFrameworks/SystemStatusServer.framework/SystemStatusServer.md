## SystemStatusServer

> `/System/Library/PrivateFrameworks/SystemStatusServer.framework/SystemStatusServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fc3c` | `0x1fac4` | **`-0x178`** |
| `__DATA_CONST.__const` | `0xe00` | `0xdd8` | **`-0x28`** |
| `__TEXT.__cstring` | `0x1ca0` | `0x1c7a` | **`-0x26`** |
| `__DATA_CONST.__got` | `0x418` | `0x410` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1360` | `0x1358` | **`-0x8`** |

### Other Changes

```diff

-279.100.0.0.0
+282.0.0.0.0

-  Functions: 742
-  Symbols:   1671
-  CStrings:  287
+  Functions: 740
+  Symbols:   1666
+  CStrings:  286
Symbols:
+ ___block_descriptor_74_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ _dispatch_block_create
- +[STStatusDomainPublisherXPCClientHandle _serverCompletionForXPCReplyBlock:]
- _OBJC_CLASS_$_NSXPCConnection
- ___76+[STStatusDomainPublisherXPCClientHandle _serverCompletionForXPCReplyBlock:]_block_invoke
- ___block_descriptor_40_e8_32bs_e37_v16?0"NSObject<OS_dispatch_queue>"8ls32l8
- ___block_descriptor_74_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
- _objc_opt_self
- _objc_retainBlock
Functions:
~ ___119-[STStatusDomainPublisherXPCClientHandle publishDiff:forDomain:withChangeContext:replacingData:discardingOnExit:reply:]_block_invoke : 912 -> 876
~ -[STLocalStatusServer _internalQueue_updateVolatileDataForPublisherClient:domain:usingDiffProvider:completion:] : 800 -> 788
~ -[STLocalStatusServer _internalQueue_mutateDataForDomain:withChangeContext:block:] : 1148 -> 1164
~ -[STLocalStatusServer _internalQueue_publishData:forPublisherClient:domain:inDataChangeRecord:withChangeContext:completion:] : 428 -> 420
~ -[STLocalStatusServer _internalQueue_publishVolatileData:forPublisherClient:domain:withChangeContext:completion:] : 368 -> 364
~ -[STLocalStatusServer _internalQueue_replaceDataChangeRecord:forPublisherClient:completion:] : 452 -> 448
~ -[STLocalStatusServer _internalQueue_replaceVolatileDataChangeRecord:forPublisherClient:completion:] : 452 -> 448
~ -[STLocalStatusServer _internalQueue_publishData:forPublisherClient:domain:withChangeContext:completion:] : 368 -> 364
~ -[STLocalStatusServer _internalQueue_updateDataForPublisherClient:domain:usingDiffProvider:completion:] : 568 -> 564
~ -[STLocalStatusServer _internalQueue_replaceDataChangeRecord:forPublisherClient:inDataChangeRecord:applyBlock:completion:] : 492 -> 484
~ ___89-[STStatusDomainPublisherXPCClientHandle replaceDataChangeRecord:discardingOnExit:reply:]_block_invoke : 672 -> 636
- ___89-[STStatusDomainPublisherXPCClientHandle replaceDataChangeRecord:discardingOnExit:reply:]_block_invoke_3
~ ___105-[STStatusDomainPublisherXPCClientHandle publishData:forDomain:withChangeContext:discardingOnExit:reply:]_block_invoke : 480 -> 440
- ___76+[STStatusDomainPublisherXPCClientHandle _serverCompletionForXPCReplyBlock:]_block_invoke
CStrings:
- "v16@?0@\"NSObject<OS_dispatch_queue>\"8"
```
