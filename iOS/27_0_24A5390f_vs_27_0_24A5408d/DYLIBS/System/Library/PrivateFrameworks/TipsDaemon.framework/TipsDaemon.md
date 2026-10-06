## TipsDaemon

> `/System/Library/PrivateFrameworks/TipsDaemon.framework/TipsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa0254` | `0xa0730` | **`+0x4dc`** |
| `__TEXT.__oslogstring` | `0x21fb` | `0x2474` | **`+0x279`** |
| `__TEXT.__gcc_except_tab` | `0x1394` | `0x1484` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x1e68` | `0x1eb0` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x2d08` | `0x2d30` | **`+0x28`** |
| `__TEXT.__const` | `0x3238` | `0x3258` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3878` | `0x3898` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1220` | `0x1230` | **`+0x10`** |
| `__DATA.__bss` | `0x1d30` | `0x1d40` | **`+0x10`** |
| `__TEXT.__cstring` | `0x428c` | `0x427c` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xd20` | `0xd18` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2690` | `0x2688` | **`-0x8`** |

### Other Changes

```diff

-857.0.0.0.0
+866.0.0.0.0

-  Functions: 3307
-  Symbols:   3444
-  CStrings:  798
+  Functions: 3315
+  Symbols:   3457
+  CStrings:  807
Symbols:
+ +[TPSRegulatoryImageManager _findELabelURLsWithType:completion:]
+ +[TPSRegulatoryImageManager fetchELabelURLsForCurrentDevice:]
+ +[TPSRegulatoryImageManager notifyMetaCompletionsWithDocumentsMap:deliveryInfo:contentMapHash:error:]
+ GCC_except_table33
+ GCC_except_table35
+ GCC_except_table45
+ GCC_except_table53
+ GCC_except_table61
+ ___101+[TPSRegulatoryImageManager notifyMetaCompletionsWithDocumentsMap:deliveryInfo:contentMapHash:error:]_block_invoke
+ ___53+[TPSRegulatoryImageManager fetchMetaWithCompletion:]_block_invoke_3
+ ___64+[TPSRegulatoryImageManager _findELabelURLsWithType:completion:]_block_invoke
+ ___block_descriptor_40_e47_v44?08"NSData"16B24"NSString"28"NSError"36l
+ ___block_descriptor_48_e8_32bs40r_e5_v8?0ls32l8r40l8
+ __isFetchingMeta
+ __pendingMetaCompletions
- GCC_except_table40
- _OBJC_CLASS_$_TPSNotification
CStrings:
+ "Device match: model=%{public}@ family=%{public}@ targets=%{public}@"
+ "Welcome collection %@ missing notification content, fall back to software welcome."
+ "Welcome collection fallback %@ missing notification content."
+ "Welcome collection fallback not found %@"
+ "Welcome collection not found %@"
+ "airpods.pro.gen3"
+ "eLabel XPC: no eLabel returned for type %{public}@ (no cached documents)"
+ "eLabel XPC: no eLabel returned for type %{public}@ style %{public}ld (matched document has no fileURL)"
+ "eLabel XPC: no eLabel returned for type %{public}@ style %{public}ld (no matching document)"
+ "eLabel XPC: returned eLabel for type %{public}@ style %{public}ld at %{public}@"
- "711495D10BB643F6BDA3693886C0BCAF"
```
