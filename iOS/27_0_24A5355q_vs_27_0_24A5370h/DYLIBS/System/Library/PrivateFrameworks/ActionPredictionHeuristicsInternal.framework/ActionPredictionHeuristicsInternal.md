## ActionPredictionHeuristicsInternal

> `/System/Library/PrivateFrameworks/ActionPredictionHeuristicsInternal.framework/ActionPredictionHeuristicsInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e088` | `0x3e354` | **`+0x2cc`** |
| `__AUTH_CONST.__cfstring` | `0x3500` | `0x3580` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x980` | `0x9c0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x722d` | `0x726a` | **`+0x3d`** |
| `__TEXT.__unwind_info` | `0xed0` | `0xea8` | **`-0x28`** |
| `__TEXT.__cstring` | `0x3204` | `0x322a` | **`+0x26`** |
| `__DATA.__bss` | `0x2f0` | `0x310` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xce8` | `0xd08` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f00` | `0x1f10` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x8f0` | `0x8f8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2a6c` | `0x2a74` | **`+0x8`** |

### Other Changes

```diff

-658.0.9.0.0
+661.0.7.0.0

-  Functions: 1218
-  Symbols:   2488
-  CStrings:  959
+  Functions: 1222
+  Symbols:   2498
+  CStrings:  964
Symbols:
+ -[ATXHeuristicDevice _cacheKeyForParticipant:]
+ GCC_except_table32
+ GCC_except_table36
+ _CNContactStoreDidChangeNotification
+ __ParticipantContactLRUCache.cache
+ __ParticipantContactLRUCache.contactStoreChangeObserver
+ __ParticipantContactLRUCache.observer
+ __ParticipantContactLRUCache.onceToken
+ ____ParticipantContactLRUCache_block_invoke
+ ____ParticipantContactLRUCache_block_invoke_2
+ ___block_descriptor_32_e24_v16?0"NSNotification"8l
- GCC_except_table31
CStrings:
+ "Address book changed; invalidating participant contact cache"
+ "email:"
+ "name:"
+ "participant contact"
+ "url:"
```
