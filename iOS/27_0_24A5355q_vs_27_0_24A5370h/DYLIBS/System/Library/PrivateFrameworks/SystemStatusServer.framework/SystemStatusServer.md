## SystemStatusServer

> `/System/Library/PrivateFrameworks/SystemStatusServer.framework/SystemStatusServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fb88` | `0x1fc3c` | **`+0xb4`** |
| `__DATA_CONST.__const` | `0xdd8` | `0xe00` | **`+0x28`** |
| `__TEXT.__cstring` | `0x1c7a` | `0x1ca0` | **`+0x26`** |
| `__DATA_CONST.__got` | `0x410` | `0x418` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1358` | `0x1360` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x868` | `0x870` | **`+0x8`** |

### Other Changes

```diff

-274.0.0.0.0
+279.100.0.0.0

-  Functions: 740
-  Symbols:   1666
-  CStrings:  286
+  Functions: 742
+  Symbols:   1671
+  CStrings:  287
Symbols:
+ +[STStatusDomainPublisherXPCClientHandle _serverCompletionForXPCReplyBlock:]
+ _OBJC_CLASS_$_NSXPCConnection
+ ___76+[STStatusDomainPublisherXPCClientHandle _serverCompletionForXPCReplyBlock:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e37_v16?0"NSObject<OS_dispatch_queue>"8ls32l8
+ ___block_descriptor_74_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
+ _objc_opt_self
+ _objc_retainBlock
- ___block_descriptor_74_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
- _dispatch_block_create
CStrings:
+ "v16@?0@\"NSObject<OS_dispatch_queue>\"8"
```
