## SystemStatus

> `/System/Library/PrivateFrameworks/SystemStatus.framework/SystemStatus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3c0` | `0x16d0` | **`+0x1310`** |
| `__DATA_DIRTY.__objc_data` | `0x3430` | `0x2120` | **`-0x1310`** |
| `__TEXT.__text` | `0x59824` | `0x59438` | **`-0x3ec`** |
| `__DATA_CONST.__const` | `0x19e0` | `0x1980` | **`-0x60`** |
| `__AUTH_CONST.__cfstring` | `0x4840` | `0x4860` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3f2b` | `0x3f0e` | **`-0x1d`** |
| `__TEXT.__unwind_info` | `0x2238` | `0x2228` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fb8` | `0x1fb0` | **`-0x8`** |

### Other Changes

```diff

-279.100.0.0.0
+282.0.0.0.0

-  Functions: 3178
-  Symbols:   5620
+  Functions: 3172
+  Symbols:   5612
Symbols:
+ GCC_except_table48
+ ___block_descriptor_65_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ _dispatch_block_create
- +[STStatusDomainPublisherXPCServerHandle _xpcReplyBlockForServerCompletion:]
- GCC_except_table50
- ___59-[STStatusDomainPublisher _updateDataWithBlock:completion:]_block_invoke_2
- ___65-[STStatusDomainPublisher _setData:withChangeContext:completion:]_block_invoke
- ___67-[STStatusDomainPublisher _updateVolatileDataWithBlock:completion:]_block_invoke_2
- ___73-[STStatusDomainPublisher _setVolatileData:withChangeContext:completion:]_block_invoke
- ___76+[STStatusDomainPublisherXPCServerHandle _xpcReplyBlockForServerCompletion:]_block_invoke
- ___block_descriptor_40_e8_32bs_e37_v16?0"NSObject<OS_dispatch_queue>"8ls32l8
- ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
- ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
- ___block_descriptor_73_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
CStrings:
+ "ethernet"
- "v16@?0@\"NSObject<OS_dispatch_queue>\"8"
```
