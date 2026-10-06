## SPOwner

> `/System/Library/PrivateFrameworks/SPOwner.framework/SPOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77b44` | `0x78078` | **`+0x534`** |
| `__TEXT.__cstring` | `0x6ac9` | `0x6b49` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0x14370` | `0x143d0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x2190` | `0x21b8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xbc0c` | `0xbc24` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2770` | `0x2780` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xf14` | `0xf1c` | **`+0x8`** |

### Other Changes

```diff

-449.31.6.16.19
+449.31.6.16.25

-  Functions: 4414
-  Symbols:   7357
-  CStrings:  1580
+  Functions: 4423
+  Symbols:   7366
+  CStrings:  1583
Symbols:
+ -[SPOwnerSessionLocationFetch callbackQueue]
+ -[SPOwnerSessionLocationFetch queue]
+ _OBJC_IVAR_$_SPOwnerSessionLocationFetch._callbackQueue
+ _OBJC_IVAR_$_SPOwnerSessionLocationFetch._queue
+ ___51-[SPOwnerSessionLocationFetch invalidationHandler:]_block_invoke
+ ___51-[SPOwnerSessionLocationFetch invalidationHandler:]_block_invoke_2
+ ___61-[SPOwnerSessionLocationFetch locationForContext:completion:]_block_invoke_2
+ ___72-[SPOwnerSessionLocationFetch unsubscribeLocationUpdatesWithCompletion:]_block_invoke
+ ___78-[SPOwnerSessionLocationFetch subscribeAndFetchLocationForContext:completion:]_block_invoke_3
+ ___block_descriptor_64_e8_32s40s48bs56w_e5_v8?0ls32l8s40l8s48l8w56l8
- GCC_except_table19
CStrings:
+ "\t"
+ "com.apple.icloud.searchpartyd.SPOwnerSessionLocationFetch"
+ "com.apple.icloud.searchpartyd.SPOwnerSessionLocationFetch.callback"
```
