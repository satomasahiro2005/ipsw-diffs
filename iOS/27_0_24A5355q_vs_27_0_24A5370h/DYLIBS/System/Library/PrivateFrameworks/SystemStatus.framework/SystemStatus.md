## SystemStatus

> `/System/Library/PrivateFrameworks/SystemStatus.framework/SystemStatus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59398` | `0x59824` | **`+0x48c`** |
| `__DATA_CONST.__const` | `0x1960` | `0x19e0` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0xf538` | `0xf578` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x1469` | `0x14a3` | **`+0x3a`** |
| `__TEXT.__cstring` | `0x3ef8` | `0x3f2b` | **`+0x33`** |
| `__AUTH_CONST.__cfstring` | `0x4820` | `0x4840` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x84d0` | `0x84f0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2218` | `0x2238` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fa0` | `0x1fb8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x5d0` | `0x5d4` | **`+0x4`** |

### Other Changes

```diff

-274.0.0.0.0
+279.100.0.0.0

-  Functions: 3170
-  Symbols:   5607
-  CStrings:  764
+  Functions: 3178
+  Symbols:   5620
+  CStrings:  767
Symbols:
+ +[STStatusDomainPublisherXPCServerHandle _xpcReplyBlockForServerCompletion:]
+ -[STMutableStatusBarData setMenuBarEntry:]
+ -[STStatusBarData menuBarEntry]
+ -[STStatusDomainXPCServerHandle _internalQueue_reregisterForDomainsIfNecessary]
+ -[STStatusDomainXPCServerHandle _internalQueue_tearDownXPCConnection]
+ GCC_except_table26
+ GCC_except_table29
+ GCC_except_table50
+ OBJC_IVAR_$_STStatusBarData._menuBarEntry
+ _STStatusBarDataEntryMenuBarKey
+ ___59-[STStatusDomainPublisher _updateDataWithBlock:completion:]_block_invoke_2
+ ___65-[STStatusDomainPublisher _setData:withChangeContext:completion:]_block_invoke
+ ___67-[STStatusDomainPublisher _updateVolatileDataWithBlock:completion:]_block_invoke_2
+ ___73-[STStatusDomainPublisher _setVolatileData:withChangeContext:completion:]_block_invoke
+ ___76+[STStatusDomainPublisherXPCServerHandle _xpcReplyBlockForServerCompletion:]_block_invoke
+ ___77-[STStatusDomainXPCServerHandle _internalQueue_setupXPCConnectionIfNecessary]_block_invoke_2
+ ___86-[STStatusDomainPublisherXPCServerHandle _internalQueue_setupXPCConnectionIfNecessary]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e37_v16?0"NSObject<OS_dispatch_queue>"8ls32l8
+ ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_73_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
- -[STStatusDomainXPCServerHandle _reregisterForDomainsIfNecessary]
- -[STStatusDomainXPCServerHandle _tearDownXPCConnection]
- GCC_except_table30
- GCC_except_table48
- ___55-[STStatusDomainXPCServerHandle _tearDownXPCConnection]_block_invoke
- ___64-[STStatusDomainPublisherXPCServerHandle _tearDownXPCConnection]_block_invoke
- ___block_descriptor_65_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- _dispatch_block_create
CStrings:
+ "Record type %{public}@ is not of required type %{public}@"
+ "menuBarEntry"
+ "v16@?0@\"NSObject<OS_dispatch_queue>\"8"
```
