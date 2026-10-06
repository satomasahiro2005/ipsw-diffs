## AppStoreComponents

> `/System/Library/PrivateFrameworks/AppStoreComponents.framework/AppStoreComponents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90e94` | `0x90ea8` | **`+0x14`** |

### Other Changes

```diff

-  Functions: 3825
+  Functions: 3826
Functions:
~ _OUTLINED_FUNCTION_1 : 16 -> 32
~ _OUTLINED_FUNCTION_2 : 32 -> 16
+ -[ASCLockupViewGroup(BundleID) _lockupRequestForBundleID:withContext:completionBlock:]
~ -[ASCLockupViewGroup scheduleBatchRequestsIfNeeded].cold.1 : 64 -> 72
~ -[ASCLockupViewGroup performBatchRequests].cold.1 : 168 -> 164
~ -[ASCLockupViewGroup performBatchRequests].cold.2 : 64 -> 72
~ -[ASCLockupViewGroup lockupWithRequest:].cold.1 : 92 -> 88
```
