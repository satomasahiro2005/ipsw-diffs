## MorpheusExtensions

> `/System/Library/PrivateFrameworks/MorpheusExtensions.framework/MorpheusExtensions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xba510` | `0xba5ac` | **`+0x9c`** |
| `__TEXT.__eh_frame` | `0x7a8c` | `0x7abc` | **`+0x30`** |
| `__TEXT.__cstring` | `0x4a36` | `0x4a46` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2600` | `0x2608` | **`+0x8`** |

### Other Changes

```diff

-46.0.0.0.0
+47.0.0.0.0

-  Functions: 2694
+  Functions: 2695
CStrings:
+ "fetch_all_messages_async"
+ "fetch_next_batch_async"
+ "morpheus.messages.BatchFetcher.fetch_all_messages_async"
+ "morpheus.messages.BatchFetcher.fetch_next_batch_async"
- "fetch_all_messages"
- "fetch_next_batch"
- "morpheus.messages.BatchFetcher.fetch_all_messages"
- "morpheus.messages.BatchFetcher.fetch_next_batch"
```
