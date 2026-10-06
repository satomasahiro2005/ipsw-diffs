## SystemStatus

> `/System/Library/PrivateFrameworks/SystemStatus.framework/SystemStatus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x16d0` | `0x3c0` | **`-0x1310`** |
| `__DATA_DIRTY.__objc_data` | `0x2120` | `0x3430` | **`+0x1310`** |
| `__TEXT.__text` | `0x59438` | `0x5970c` | **`+0x2d4`** |
| `__DATA_CONST.__const` | `0x1980` | `0x19f8` | **`+0x78`** |
| `__TEXT.__cstring` | `0x3f0e` | `0x3f34` | **`+0x26`** |
| `__TEXT.__unwind_info` | `0x2228` | `0x2238` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x590` | `0x598` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fb0` | `0x1fb8` | **`+0x8`** |

### Other Changes

```diff

-282.0.0.0.0
+284.1.0.0.0

-  Functions: 3172
-  Symbols:   5612
-  CStrings:  767
+  Functions: 3176
+  Symbols:   5618
+  CStrings:  768
Symbols:
+ +[STStatusDomainPublisher _serverCompletionForClientCompletion:]
+ +[STStatusDomainPublisherXPCServerHandle _xpcReplyBlockForServerCompletion:]
+ GCC_except_table50
+ ___64+[STStatusDomainPublisher _serverCompletionForClientCompletion:]_block_invoke
+ ___76+[STStatusDomainPublisherXPCServerHandle _xpcReplyBlockForServerCompletion:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e37_v16?0"NSObject<OS_dispatch_queue>"8ls32l8
+ ___block_descriptor_40_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_73_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
- GCC_except_table48
- ___block_descriptor_65_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- _dispatch_block_create
CStrings:
+ "v16@?0@\"NSObject<OS_dispatch_queue>\"8"
```
