## PowerLog

> `/System/Library/PrivateFrameworks/PowerLog.framework/PowerLog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x550` | `0x4d8` | **`-0x78`** |
| `__DATA_DIRTY.__objc_data` | `0xf0` | `0x168` | **`+0x78`** |
| `__TEXT.__text` | `0x1f034` | `0x1f070` | **`+0x3c`** |
| `__TEXT.__gcc_except_tab` | `0x6c8` | `0x6a0` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x540` | `0x560` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x88` | `0x90` | **`+0x8`** |
| `__DATA.__data` | `0x1e8` | `0x1ec` | **`+0x4`** |

### Other Changes

```diff

-3486.40.92.0.0
+3486.40.98.0.0

-  Functions: 836
-  Symbols:   1230
+  Functions: 838
+  Symbols:   1233
Symbols:
+ _PLClientPPSBatchSize.onceToken
+ _PLClientPPSBatchSize.sPPSBatchSize
+ ___PLClientPPSBatchSize_block_invoke
Functions:
~ -[PLClientLogger addToBatchedTaskCacheForType:forClientID:forKey:withPayload:] : 1200 -> 1112
+ ___PLClientPPSBatchSize_block_invoke
+ -[PLClientLogger addToBatchedTaskCacheForType:forClientID:forKey:withPayload:].cold.2
```
