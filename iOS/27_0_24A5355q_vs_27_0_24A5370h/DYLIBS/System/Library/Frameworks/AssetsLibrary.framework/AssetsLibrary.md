## AssetsLibrary

> `/System/Library/Frameworks/AssetsLibrary.framework/AssetsLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2cc` | `0xa28c` | **`-0x40`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0
Functions:
~ ___28-[ALAsset valueForProperty:]_block_invoke : 856 -> 852
~ ___32-[ALAsset representationForUTI:]_block_invoke : 448 -> 444
~ -[ALAssetsLibraryPrivate photoLibraryDidChange:] : 1436 -> 1416
~ ___68-[ALAssetsLibrary enumerateGroupsWithTypes:usingBlock:failureBlock:]_block_invoke_4 : 288 -> 284
~ ___68-[ALAssetsLibrary enumerateGroupsWithTypes:usingBlock:failureBlock:]_block_invoke_5 : 488 -> 480
~ ___68-[ALAssetsLibrary enumerateGroupsWithTypes:usingBlock:failureBlock:]_block_invoke_6 : 432 -> 424
~ ___68-[ALAssetsLibrary enumerateGroupsWithTypes:usingBlock:failureBlock:]_block_invoke_7 : 272 -> 268
~ ___68-[ALAssetsLibrary enumerateGroupsWithTypes:usingBlock:failureBlock:]_block_invoke_9 : 440 -> 432
~ +[ALAssetRepresentationPrivate _clearFileDescriptorQueue] : 364 -> 360
```
