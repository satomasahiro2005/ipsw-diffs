## ANEStorageMaintainer

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/XPCServices/ANEStorageMaintainer.xpc/ANEStorageMaintainer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7818` | `0x7800` | **`-0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-382.7.4.0.0
+382.9.0.0.0
Functions:
~ +[_ANEStorageHelper garbageCollectDanglingModelsAtPath:] : 3176 -> 3168
~ +[_ANEStorageHelper uniqueFirstLevelSubdirectories:] : 376 -> 372
~ +[_ANEStorageHelper sizeOfModelCacheAtPath:purgeSubdirectories:] : 1448 -> 1444
~ +[_ANEStorageHelper mergeModelCacheStorageInformation:with:] : 796 -> 792
~ -[_ANEPatchManager deletePatchedModelsInDirectory:forModelURL:onlyIfOrphaned:error:] : 2192 -> 2188
```
