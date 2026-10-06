## CarbonCore

> `/System/Library/PrivateFrameworks/CarbonCore.framework/CarbonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x342bc` | `0x34288` | **`-0x34`** |
| `__AUTH_CONST.__auth_got` | `0xa48` | `0xa38` | **`-0x10`** |

### Other Changes

```diff

-1404.0.0.0.0
+1405.0.0.0.0

-  Symbols:   1608
+  Symbols:   1606
Symbols:
- ___sprintf_chk
- ___strcpy_chk
Functions:
~ ___FileIDTreeGetCachedPort_block_invoke : 340 -> 284
~ _FSNodeServer_SyncSystemUniverseInternal : 1552 -> 1572
~ _FSNodeSyncVolumesCallback : 500 -> 516
~ _FSNodeServer_SyncWithSystemUniverseInternal : 896 -> 900
~ _FileIDTreePrintNodeTreeInternal : 416 -> 392
~ _PrintVolumeIDCallbacks_LeafNodeFoundCallback : 348 -> 320
~ _FileIDTreeGetAndLockVolumeEntryFromVolumeStringPtr : 1076 -> 1080
~ _OUTLINED_FUNCTION_33 : 20 -> 12
~ _OUTLINED_FUNCTION_34 : 12 -> 20
~ _OUTLINED_FUNCTION_38 : 20 -> 12
~ _OUTLINED_FUNCTION_39 : 12 -> 20
~ _TERMINATING_DUE_TO_FILE_ID_TREE_PORTCACHE_MEMORY_CORRUPTION : 216 -> 212
~ _FileIDTree_BeginTransactionInternal : 816 -> 832
```
