## GenerationalStorage

> `/System/Library/PrivateFrameworks/GenerationalStorage.framework/GenerationalStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16a40` | `0x169f4` | **`-0x4c`** |
| `__AUTH_CONST.__auth_got` | `0x4a8` | `0x4b0` | **`+0x8`** |

### Other Changes

```diff

-401.0.0.0.0
+402.0.0.0.0

-  Symbols:   875
+  Symbols:   876
Symbols:
+ _objc_release_x3
Functions:
~ __GSGetNameXattr : 560 -> 556
~ _GSArchiveTree : 1540 -> 1544
~ _GSLibraryCopyGenerationNames : 412 -> 408
~ __copyGenInfos : 940 -> 936
~ _GSLibraryCopyAllGenerationsInfos : 1700 -> 1696
~ ___GSAdditionSaveBlocking_block_invoke : 136 -> 132
~ ___48-[GSPermanentAdditionEnumerator _fetchNextBatch]_block_invoke : 600 -> 596
~ ___59-[GSPermanentStorage additionsWithNames:inNameSpace:error:]_block_invoke : 504 -> 500
~ -[GSPermanentStorage _calculateSpecForAdditionRemoval:] : 432 -> 428
~ -[GSPermanentStorage _removalErrorDictionaryCreation:withAdditions:] : 460 -> 456
~ -[GSPermanentStorage removeAllAdditionsForNamespaces:completionHandler:] : 584 -> 580
~ -[GSStorageManager _connectionWithDaemonWasLost] : 476 -> 468
~ -[GSStorageManager removeAdditionsInNamespace:underPath:withMatchingPredicate:errorPerAddition:error:] : 1608 -> 1604
~ _GSLibraryGetMNTInfo : 428 -> 440
~ -[GSTemporaryStorage additionsWithNames:inNameSpace:error:] : 780 -> 760
~ ___56-[GSTemporaryStorage removeAdditions:completionHandler:]_block_invoke_2 : 788 -> 776
~ ___72-[GSTemporaryStorage removeAllAdditionsForNamespaces:completionHandler:]_block_invoke : 852 -> 844
```
