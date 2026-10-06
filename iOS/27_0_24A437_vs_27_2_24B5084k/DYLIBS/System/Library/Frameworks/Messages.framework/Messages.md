## Messages

> `/System/Library/Frameworks/Messages.framework/Messages`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ff00` | `0x309e0` | **`+0xae0`** |
| `__DATA_CONST.__const` | `0x738` | `0x7f8` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x4d60` | `0x4db0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xf30` | `0xf70` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x194` | `0x1c0` | **`+0x2c`** |
| `__DATA_CONST.__objc_selrefs` | `0x2758` | `0x2780` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x7f8` | `0x818` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x5f18` | `0x5f28` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1f2f` | `0x1f3f` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x798` | `0x7a0` | **`+0x8`** |

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Functions: 1722
-  Symbols:   2688
+  Functions: 1737
+  Symbols:   2710
Symbols:
+ -[MSConversation _insertMessage:replyingToMessage:skipShelf:completionHandler:]
+ -[MSConversation insertMessage:replyingToMessage:completionHandler:]
+ -[_MSMessageAppBundleContext stageAppItem:replyingToMessage:skipShelf:completionHandler:]
+ -[_MSMessageAppBundleHostContext _stageAppItem:replyingToMessage:skipShelf:completionHandler:]
+ -[_MSMessageAppContext stageAppItem:replyingToMessage:skipShelf:completionHandler:]
+ -[_MSMessageAppExtensionContext stageAppItem:replyingToMessage:skipShelf:completionHandler:]
+ -[_MSMessageAppExtensionHostContext _stageAppItem:replyingToMessage:skipShelf:completionHandler:]
+ GCC_except_table53
+ ___79-[MSConversation _insertMessage:replyingToMessage:skipShelf:completionHandler:]_block_invoke
+ ___92-[_MSMessageAppExtensionContext stageAppItem:replyingToMessage:skipShelf:completionHandler:]_block_invoke
+ ___92-[_MSMessageAppExtensionContext stageAppItem:replyingToMessage:skipShelf:completionHandler:]_block_invoke_2
+ ___92-[_MSMessageAppExtensionContext stageAppItem:replyingToMessage:skipShelf:completionHandler:]_block_invoke_3
+ ___92-[_MSMessageAppExtensionContext stageAppItem:replyingToMessage:skipShelf:completionHandler:]_block_invoke_4
+ ___92-[_MSMessageAppExtensionContext stageAppItem:replyingToMessage:skipShelf:completionHandler:]_block_invoke_5
+ ___94-[_MSMessageAppBundleHostContext _stageAppItem:replyingToMessage:skipShelf:completionHandler:]_block_invoke
+ ___97-[_MSMessageAppExtensionHostContext _stageAppItem:replyingToMessage:skipShelf:completionHandler:]_block_invoke
+ ___block_descriptor_32_e20_v20?0B8"NSError"12l
+ ___block_descriptor_40_e8_32bs_e17_v16?0"NSError"8ls32l8
+ ___block_descriptor_40_e8_32bs_e20_v20?0B8"NSError"12ls32l8
+ ___block_descriptor_48_e8_32bs40r_e20_v20?0B8"NSError"12lr40l8s32l8
+ ___block_descriptor_57_e8_32s40s48bs_e17_v16?0"NSError"8ls32l8s48l8s40l8
+ _objc_release_x2
CStrings:
+ "PhotosUIFoundation"
- "PhotosUICore"
```
