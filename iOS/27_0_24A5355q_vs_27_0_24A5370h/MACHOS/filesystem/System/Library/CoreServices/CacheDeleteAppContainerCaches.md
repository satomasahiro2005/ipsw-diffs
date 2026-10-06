## CacheDeleteAppContainerCaches

> `/System/Library/CoreServices/CacheDeleteAppContainerCaches`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c54` | `0x4c38` | **`-0x1c`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-901.0.0.0.1
+904.0.0.0.0
Functions:
~ ___39-[CacheDeletePruner pruneDir:bundleID:]_block_invoke : 408 -> 404
~ -[CacheDeleteManagedAssets assetsFromArray:forAmount:] : 464 -> 460
~ ___51-[CacheDeleteManagedAssets purgeAssets:testObject:]_block_invoke : 612 -> 608
~ ___51-[CacheDeleteManagedAssets purgeAssets:testObject:]_block_invoke_2 : 576 -> 572
~ -[CacheDeleteManagedAssets periodic:] : 556 -> 552
~ ___37-[CacheDeleteManagedAssets periodic:]_block_invoke_2 : 340 -> 336
~ ___RegisterCacheManagementAssetsService_block_invoke_4 : 2824 -> 2820
```
