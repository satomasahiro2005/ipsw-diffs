## WebBookmarks

> `/System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa66d4` | `0xa637c` | **`-0x358`** |
| `__TEXT.__gcc_except_tab` | `0xbfc0` | `0xc004` | **`+0x44`** |
| `__TEXT.__oslogstring` | `0x9d51` | `0x9d87` | **`+0x36`** |
| `__DATA_CONST.__const` | `0x3030` | `0x3008` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x6420` | `0x6440` | **`+0x20`** |
| `__TEXT.__cstring` | `0xfbdc` | `0xfbf1` | **`+0x15`** |
| `__AUTH_CONST.__objc_const` | `0x9d90` | `0x9d80` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x7f0` | `0x7f8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x888c` | `0x8884` | **`-0x8`** |

### Other Changes

```diff

-625.1.18.10.4
+625.1.20.10.3

-  Functions: 3696
-  Symbols:   6044
+  Functions: 3692
+  Symbols:   6041
Symbols:
+ -[WebBookmarkCollection _didApplyTemporaryMigrationInFreshDatabaseForKey:]
+ -[WebBookmarkCollection bookmarksByDateAddedWithLimit:skipDecodingSyncData:]
+ GCC_except_table303
+ GCC_except_table312
+ GCC_except_table319
+ GCC_except_table322
+ GCC_except_table324
+ GCC_except_table327
+ GCC_except_table336
+ GCC_except_table342
+ GCC_except_table347
+ GCC_except_table360
+ GCC_except_table370
+ GCC_except_table376
+ GCC_except_table378
+ GCC_except_table380
+ GCC_except_table383
+ GCC_except_table386
+ GCC_except_table392
+ GCC_except_table407
+ GCC_except_table412
+ GCC_except_table421
+ GCC_except_table424
+ GCC_except_table432
+ GCC_except_table438
+ GCC_except_table443
+ GCC_except_table461
+ GCC_except_table465
+ GCC_except_table470
+ GCC_except_table472
+ GCC_except_table475
+ GCC_except_table479
+ GCC_except_table495
+ GCC_except_table497
+ GCC_except_table502
+ GCC_except_table513
+ GCC_except_table517
+ GCC_except_table535
+ GCC_except_table544
+ GCC_except_table555
+ GCC_except_table557
+ GCC_except_table567
+ GCC_except_table570
+ GCC_except_table587
+ GCC_except_table588
+ GCC_except_table595
+ GCC_except_table602
+ GCC_except_table603
+ _WBSDidApplyStartPageSectionPositionHealKey
+ ___76-[WebBookmarkCollection bookmarksByDateAddedWithLimit:skipDecodingSyncData:]_block_invoke
+ ___76-[WebBookmarkCollection bookmarksByDateAddedWithLimit:skipDecodingSyncData:]_block_invoke_2
- -[WBProfileWindow setWindowState:]
- -[WBProfileWindow windowState]
- -[WBTabGroupManager tabGroupInDatabaseWithUUID:hasExpectedTabCount:]
- GCC_except_table276
- GCC_except_table304
- GCC_except_table316
- GCC_except_table320
- GCC_except_table323
- GCC_except_table325
- GCC_except_table331
- GCC_except_table337
- GCC_except_table343
- GCC_except_table348
- GCC_except_table361
- GCC_except_table372
- GCC_except_table377
- GCC_except_table379
- GCC_except_table382
- GCC_except_table385
- GCC_except_table388
- GCC_except_table394
- GCC_except_table408
- GCC_except_table413
- GCC_except_table422
- GCC_except_table429
- GCC_except_table433
- GCC_except_table440
- GCC_except_table449
- GCC_except_table462
- GCC_except_table468
- GCC_except_table471
- GCC_except_table474
- GCC_except_table476
- GCC_except_table480
- GCC_except_table496
- GCC_except_table499
- GCC_except_table503
- GCC_except_table515
- GCC_except_table522
- GCC_except_table536
- GCC_except_table546
- GCC_except_table556
- GCC_except_table560
- GCC_except_table568
- GCC_except_table571
- GCC_except_table574
- GCC_except_table593
- GCC_except_table600
- GCC_except_table601
- _WBSOSLogLaunchQuit
- ___45-[WebBookmarkCollection bookmarksByDateAdded]_block_invoke
- ___45-[WebBookmarkCollection bookmarksByDateAdded]_block_invoke_2
- ___59-[WBSettingsSyncEngineAccess _updateStartPageSectionOrder:]_block_invoke_3
- ___block_descriptor_56_ea8_32s40r_e25_B32?0"NSString"8Q16^B24lr40l8s32l8
CStrings:
+ "%@ %@ (fresh database)"
+ "Did finish migrating temporary feature with name: %{public}@"
+ "Marking temporary migration as already applied for fresh database with name: %{public}@"
+ "Will begin migrating temporary feature with name: %{public}@"
- "A"
- "Active tab group <%{public}@> is nil for windowState %{public}@."
- "Could not find tab group: %{public}@"
- "Tab group: %{public}@ - savedTabs: %zu shownTabs: %zu"
```
