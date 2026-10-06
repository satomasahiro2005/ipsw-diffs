## WebBookmarks

> `/System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa726c` | `0xa7c3c` | **`+0x9d0`** |
| `__TEXT.__gcc_except_tab` | `0xc1e4` | `0xc32c` | **`+0x148`** |
| `__TEXT.__cstring` | `0xfc87` | `0xfd75` | **`+0xee`** |
| `__TEXT.__oslogstring` | `0x9e5d` | `0x9ee9` | **`+0x8c`** |
| `__AUTH_CONST.__cfstring` | `0x6440` | `0x64c0` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0x9f00` | `0x9f50` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x893c` | `0x8964` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x46f8` | `0x4720` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x50a8` | `0x50c8` | **`+0x20`** |
| `__TEXT.__const` | `0x326` | `0x336` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x624` | `0x62c` | **`+0x8`** |

### Other Changes

```diff

-625.1.22.10.3
+625.1.24.10.1

-  Functions: 3706
-  Symbols:   6071
-  CStrings:  2083
+  Functions: 3711
+  Symbols:   6082
+  CStrings:  2089
Symbols:
+ +[WBBookmarkSyncData _decodedTrimmedBookmarkSyncDataWithContentsOfData:]
+ +[WBBookmarkSyncData containsRecordInContentsOfData:]
+ -[WebBookmarkCollection _mergeDuplicateSpecialFolders]
+ -[WebBookmarkCollection bookmarksPendingFeatureTextBackfill:shouldResetStuckBookmarks:foundBookmarksNeedingBackfill:]
+ -[_WBBookmarkSyncDataForFieldSetupDecoding hasRecord]
+ GCC_except_table313
+ GCC_except_table316
+ GCC_except_table320
+ GCC_except_table323
+ GCC_except_table328
+ GCC_except_table329
+ GCC_except_table337
+ GCC_except_table343
+ GCC_except_table348
+ GCC_except_table361
+ GCC_except_table371
+ GCC_except_table372
+ GCC_except_table377
+ GCC_except_table382
+ GCC_except_table385
+ GCC_except_table388
+ GCC_except_table393
+ GCC_except_table394
+ GCC_except_table408
+ GCC_except_table413
+ GCC_except_table422
+ GCC_except_table425
+ GCC_except_table426
+ GCC_except_table433
+ GCC_except_table439
+ GCC_except_table440
+ GCC_except_table444
+ GCC_except_table445
+ GCC_except_table462
+ GCC_except_table466
+ GCC_except_table467
+ GCC_except_table471
+ GCC_except_table474
+ GCC_except_table480
+ GCC_except_table496
+ GCC_except_table499
+ GCC_except_table503
+ GCC_except_table514
+ GCC_except_table515
+ GCC_except_table518
+ GCC_except_table519
+ GCC_except_table536
+ GCC_except_table545
+ GCC_except_table546
+ GCC_except_table556
+ GCC_except_table559
+ GCC_except_table568
+ GCC_except_table571
+ GCC_except_table574
+ GCC_except_table589
+ GCC_except_table590
+ GCC_except_table597
+ GCC_except_table604
+ GCC_except_table605
+ _OBJC_IVAR_$_WebBookmarkCollection._isApplyingInMemoryChanges
+ _OBJC_IVAR_$__WBBookmarkSyncDataForFieldSetupDecoding._hasRecord
+ __ZZ54-[WebBookmarkCollection _mergeDuplicateSpecialFolders]E32specialIDsWithCanonicalServerIDs
+ ___54-[WebBookmarkCollection _mergeDuplicateSpecialFolders]_block_invoke
- -[WebBookmarkCollection bookmarksPendingFeatureTextBackfill:]
- GCC_except_table318
- GCC_except_table322
- GCC_except_table327
- GCC_except_table332
- GCC_except_table333
- GCC_except_table339
- GCC_except_table345
- GCC_except_table350
- GCC_except_table363
- GCC_except_table373
- GCC_except_table374
- GCC_except_table383
- GCC_except_table386
- GCC_except_table389
- GCC_except_table390
- GCC_except_table395
- GCC_except_table396
- GCC_except_table410
- GCC_except_table415
- GCC_except_table424
- GCC_except_table430
- GCC_except_table431
- GCC_except_table435
- GCC_except_table441
- GCC_except_table442
- GCC_except_table450
- GCC_except_table451
- GCC_except_table464
- GCC_except_table469
- GCC_except_table470
- GCC_except_table475
- GCC_except_table478
- GCC_except_table482
- GCC_except_table500
- GCC_except_table501
- GCC_except_table505
- GCC_except_table516
- GCC_except_table517
- GCC_except_table523
- GCC_except_table524
- GCC_except_table538
- GCC_except_table547
- GCC_except_table548
- GCC_except_table561
- GCC_except_table562
- GCC_except_table570
- GCC_except_table573
- GCC_except_table576
- GCC_except_table595
- GCC_except_table602
- GCC_except_table603
CStrings:
+ "625.1.23"
+ "Merging duplicate special folders left behind by a faulty sync-data reset (rdar://179124635)"
+ "Repairing %zu folder(s) claiming special ID %d"
+ "UPDATE bookmarks SET special_id = 0, editable = 1, deletable = 1 WHERE id = %u"
+ "feature_text IS NULL AND type = 0 AND syncable = 1 AND deleted = 0 AND editable = 1 AND deletable = 1"
+ "special_id = %d AND deleted = 0 ORDER BY id ASC"
```
