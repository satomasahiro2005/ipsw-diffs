## WebBookmarks

> `/System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf171c` | `0xf1d6c` | **`+0x650`** |
| `__TEXT.__oslogstring` | `0xb38c` | `0xb63c` | **`+0x2b0`** |
| `__TEXT.__gcc_except_tab` | `0xc3e0` | `0xc46c` | **`+0x8c`** |
| `__AUTH_CONST.__objc_const` | `0xa828` | `0xa848` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x59a0` | `0x59c0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x5140` | `0x5158` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x8bb0` | `0x8bc8` | **`+0x18`** |
| `__TEXT.__const` | `0x2048` | `0x2058` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x638` | `0x63c` | **`+0x4`** |

### Other Changes

```diff

-625.2.5.10.1
+625.2.7.1.0

-  Functions: 4943
-  Symbols:   6604
-  CStrings:  2190
+  Functions: 4948
+  Symbols:   6611
+  CStrings:  2198
Symbols:
+ -[WebBookmarkCollection _shouldWaitForLockForVersionUpgradeMigrations]
+ -[WebBookmarkCollection _tryPerformDatabaseUpdatesWithApplyInMemoryChanges:secureDelete:shouldWaitForLock:updates:]
+ GCC_except_table224
+ GCC_except_table235
+ GCC_except_table249
+ GCC_except_table278
+ GCC_except_table304
+ GCC_except_table314
+ GCC_except_table315
+ GCC_except_table322
+ GCC_except_table327
+ GCC_except_table331
+ GCC_except_table332
+ GCC_except_table339
+ GCC_except_table345
+ GCC_except_table350
+ GCC_except_table363
+ GCC_except_table373
+ GCC_except_table374
+ GCC_except_table379
+ GCC_except_table381
+ GCC_except_table383
+ GCC_except_table395
+ GCC_except_table396
+ GCC_except_table410
+ GCC_except_table415
+ GCC_except_table424
+ GCC_except_table428
+ GCC_except_table429
+ GCC_except_table436
+ GCC_except_table442
+ GCC_except_table443
+ GCC_except_table447
+ GCC_except_table448
+ GCC_except_table449
+ GCC_except_table467
+ GCC_except_table471
+ GCC_except_table472
+ GCC_except_table473
+ GCC_except_table478
+ GCC_except_table485
+ GCC_except_table501
+ GCC_except_table503
+ GCC_except_table508
+ GCC_except_table519
+ GCC_except_table520
+ GCC_except_table524
+ GCC_except_table525
+ GCC_except_table541
+ GCC_except_table550
+ GCC_except_table551
+ GCC_except_table561
+ GCC_except_table563
+ GCC_except_table565
+ GCC_except_table573
+ GCC_except_table594
+ GCC_except_table595
+ GCC_except_table596
+ GCC_except_table603
+ GCC_except_table610
+ GCC_except_table611
+ GCC_except_table612
+ _OBJC_IVAR_$_WebBookmarkCollection._didRequestDatabaseInterrupt
+ _WBBoundedTransactionLockWaitMilliseconds
+ _WBDatabaseBusyTimeoutMilliseconds
+ __ZN12WebBookmarks26BookmarkSQLReadTransactionC1EP7sqlite3PKNSt3__16atomicIbEE
+ __ZN12WebBookmarks26BookmarkSQLReadTransactionC2EP7sqlite3PKNSt3__16atomicIbEE
+ __ZN12WebBookmarks27BookmarkSQLWriteTransactionC1EP7sqlite3NS0_17ShouldWaitForLockEPKNSt3__16atomicIbEE
+ __ZN12WebBookmarks27BookmarkSQLWriteTransactionC2EP7sqlite3NS0_17ShouldWaitForLockEPKNSt3__16atomicIbEE
+ ___111-[WebBookmarkCollection _updateDatabaseIfNewerVersion:wasLaunchedForSyncStringKey:upgradeSelector:versionType:]_block_invoke_2
+ ___115-[WebBookmarkCollection _tryPerformDatabaseUpdatesWithApplyInMemoryChanges:secureDelete:shouldWaitForLock:updates:]_block_invoke
- GCC_except_table137
- GCC_except_table167
- GCC_except_table186
- GCC_except_table205
- GCC_except_table277
- GCC_except_table305
- GCC_except_table311
- GCC_except_table317
- GCC_except_table321
- GCC_except_table328
- GCC_except_table334
- GCC_except_table335
- GCC_except_table336
- GCC_except_table342
- GCC_except_table348
- GCC_except_table353
- GCC_except_table366
- GCC_except_table376
- GCC_except_table377
- GCC_except_table382
- GCC_except_table392
- GCC_except_table393
- GCC_except_table398
- GCC_except_table399
- GCC_except_table413
- GCC_except_table418
- GCC_except_table433
- GCC_except_table434
- GCC_except_table435
- GCC_except_table439
- GCC_except_table445
- GCC_except_table446
- GCC_except_table455
- GCC_except_table456
- GCC_except_table457
- GCC_except_table470
- GCC_except_table474
- GCC_except_table475
- GCC_except_table482
- GCC_except_table484
- GCC_except_table488
- GCC_except_table506
- GCC_except_table507
- GCC_except_table511
- GCC_except_table522
- GCC_except_table528
- GCC_except_table529
- GCC_except_table530
- GCC_except_table544
- GCC_except_table553
- GCC_except_table554
- GCC_except_table566
- GCC_except_table567
- GCC_except_table568
- GCC_except_table582
- GCC_except_table600
- GCC_except_table607
- GCC_except_table608
- GCC_except_table609
- __ZN12WebBookmarks26BookmarkSQLReadTransactionC1EP7sqlite3
- __ZN12WebBookmarks26BookmarkSQLReadTransactionC2EP7sqlite3
- __ZN12WebBookmarks27BookmarkSQLWriteTransactionC1EP7sqlite3
- __ZN12WebBookmarks27BookmarkSQLWriteTransactionC2EP7sqlite3
- ___97-[WebBookmarkCollection performDatabaseUpdatesWithTransaction:applyInMemoryChanges:secureDelete:]_block_invoke
CStrings:
+ "Abandoning a freshly opened write transaction; interrupted for suspension."
+ "Deferring the %{public}@ upgrade; another process already holds the database write lock."
+ "Deferring the %{public}@ upgrade; interrupted for suspension."
+ "Not opening a write transaction; the database was interrupted for suspension."
+ "Rolling back a write transaction interrupted for suspension, reverting %zu bookmark state changes"
+ "WebBookmarks could not start a bounded-wait immediate transaction. Result code was: %d"
+ "WebBookmarks did not start a deferred transaction; interrupted for suspension. Result code was: %d"
+ "WebBookmarks did not start an immediate transaction; interrupted for suspension. Result code was: %d"
```
