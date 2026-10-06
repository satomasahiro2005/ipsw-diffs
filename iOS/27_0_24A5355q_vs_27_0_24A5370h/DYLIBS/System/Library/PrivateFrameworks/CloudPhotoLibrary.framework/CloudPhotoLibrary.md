## CloudPhotoLibrary

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/CloudPhotoLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c714c` | `0x1c9d34` | **`+0x2be8`** |
| `__AUTH_CONST.__objc_const` | `0x23240` | `0x23660` | **`+0x420`** |
| `__TEXT.__gcc_except_tab` | `0x4a40` | `0x4d0c` | **`+0x2cc`** |
| `__TEXT.__cstring` | `0x17e47` | `0x18083` | **`+0x23c`** |
| `__AUTH_CONST.__cfstring` | `0x17a20` | `0x17be0` | **`+0x1c0`** |
| `__TEXT.__objc_methlist` | `0x15afc` | `0x15cac` | **`+0x1b0`** |
| `__TEXT.__unwind_info` | `0x6b88` | `0x6cc8` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x16bd2` | `0x16cf3` | **`+0x121`** |
| `__DATA_CONST.__objc_selrefs` | `0x9258` | `0x9310` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0x910` | `0x960` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x6ee8` | `0x6f38` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x1bbc` | `0x1c08` | **`+0x4c`** |
| `__AUTH_CONST.__const` | `0x2c80` | `0x2ca0` | **`+0x20`** |
| `__DATA.__bss` | `0xcd0` | `0xce8` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x9d8` | `0x9e0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x938` | `0x940` | **`+0x8`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 9698
-  Symbols:   15384
-  CStrings:  5120
+  Functions: 9763
+  Symbols:   15489
+  CStrings:  5140
Symbols:
+ +[CPLCollectionShareScopeChange setShouldForceInitialDownloadWhenJoining:]
+ +[CPLCollectionShareScopeChange shouldForceInitialDownloadWhenJoining]
+ +[CPLEngineScheduler dontDiscardPersistentSession]
+ +[CPLEngineScheduler setDontDiscardPersistentSession:]
+ -[CPLBeforeUploadCheckItem appliesRulesFor:]
+ -[CPLBeforeUploadCheckItems knownCloudRecordWithScopedIdentifier:]
+ -[CPLCollectionShareScopeChange shouldAlwaysUpdateScopeInfoWhenPossibleWithConfiguration:]
+ -[CPLCommentChange propertiesDescription]
+ -[CPLConfiguration(CPLSyncSessionConfiguration) shouldAlwaysUpdateScopeInfoForSharedCollections]
+ -[CPLEngineForceSyncTask setAllowsForcedTaskQueuing:]
+ -[CPLEngineScheduler _noteScopeNeedsToPullFromTransport]
+ -[CPLEngineScheduler noteScopeNeedsToPullFromTransportWithSignificantEvent]
+ -[CPLEngineScopeStorage setScopeHasChangesToPullFromTransport:alsoUpdateScopeInfoIfNecessary:error:]
+ -[CPLEngineTransport createGroupForChangeUploadInScopeChange:]
+ -[CPLEngineTransport createGroupForDirectUploadInScopeChange:]
+ -[CPLLibraryInfo setTransportData:]
+ -[CPLLibraryInfo transportData]
+ -[CPLLibraryShareScopeChange shouldAlwaysUpdateScopeInfoWhenPossibleWithConfiguration:]
+ -[CPLLibraryState setTransportData:]
+ -[CPLLibraryState transportData]
+ -[CPLScopeChange setTransportData:]
+ -[CPLScopeChange shouldAlwaysUpdateScopeInfoWhenPossibleWithConfiguration:]
+ -[CPLScopeChange transportData]
+ -[CPLTurboSyncObserver .cxx_destruct]
+ -[CPLTurboSyncObserver _shouldUseTurboModeLocked]
+ -[CPLTurboSyncObserver _updateExpirationDateLockedWithNewDate:]
+ -[CPLTurboSyncObserver _updateExpirationDateLocked]
+ -[CPLTurboSyncObserver batterySaverWatcherDidChangeState:]
+ -[CPLTurboSyncObserver canUseTurboModeInLowDataMode]
+ -[CPLTurboSyncObserver canUseTurboModeInLowPowerMode]
+ -[CPLTurboSyncObserver dealloc]
+ -[CPLTurboSyncObserver delegate]
+ -[CPLTurboSyncObserver expirationDate]
+ -[CPLTurboSyncObserver initWithQueue:]
+ -[CPLTurboSyncObserver init]
+ -[CPLTurboSyncObserver queue]
+ -[CPLTurboSyncObserver setCanUseTurboModeInLowDataMode:]
+ -[CPLTurboSyncObserver setCanUseTurboModeInLowPowerMode:]
+ -[CPLTurboSyncObserver setDelegate:]
+ -[CPLTurboSyncObserver setExpirationDate:]
+ -[CPLTurboSyncObserver shouldUseTurboMode]
+ -[CPLTurboSyncObserver watcher:stateDidChangeToNetworkState:]
+ GCC_except_table2014
+ GCC_except_table2022
+ GCC_except_table2246
+ GCC_except_table2247
+ GCC_except_table2250
+ GCC_except_table2257
+ GCC_except_table2261
+ GCC_except_table2288
+ GCC_except_table2295
+ GCC_except_table2305
+ GCC_except_table2308
+ GCC_except_table2497
+ GCC_except_table2596
+ GCC_except_table2670
+ GCC_except_table2711
+ GCC_except_table2803
+ GCC_except_table2810
+ GCC_except_table2963
+ GCC_except_table3052
+ GCC_except_table3338
+ GCC_except_table3340
+ GCC_except_table3422
+ GCC_except_table3426
+ GCC_except_table3436
+ GCC_except_table3446
+ GCC_except_table3504
+ GCC_except_table3506
+ GCC_except_table3636
+ GCC_except_table3660
+ GCC_except_table3742
+ GCC_except_table3746
+ GCC_except_table3748
+ GCC_except_table3750
+ GCC_except_table3754
+ GCC_except_table3915
+ GCC_except_table3962
+ GCC_except_table4207
+ GCC_except_table4283
+ GCC_except_table4287
+ GCC_except_table4289
+ GCC_except_table4298
+ GCC_except_table4501
+ GCC_except_table4515
+ GCC_except_table4672
+ GCC_except_table4702
+ GCC_except_table4733
+ GCC_except_table4758
+ GCC_except_table4766
+ GCC_except_table4768
+ GCC_except_table4782
+ GCC_except_table4784
+ GCC_except_table4787
+ GCC_except_table5159
+ GCC_except_table5192
+ GCC_except_table5194
+ GCC_except_table5220
+ GCC_except_table5354
+ GCC_except_table5364
+ GCC_except_table5421
+ GCC_except_table5424
+ GCC_except_table5602
+ GCC_except_table5610
+ GCC_except_table5704
+ GCC_except_table5710
+ GCC_except_table5717
+ GCC_except_table5732
+ GCC_except_table5733
+ GCC_except_table5739
+ GCC_except_table5785
+ GCC_except_table5791
+ GCC_except_table5795
+ GCC_except_table5821
+ GCC_except_table5826
+ GCC_except_table5828
+ GCC_except_table5830
+ GCC_except_table5832
+ GCC_except_table5834
+ GCC_except_table5836
+ GCC_except_table5838
+ GCC_except_table5846
+ GCC_except_table5848
+ GCC_except_table5850
+ GCC_except_table5851
+ GCC_except_table5898
+ GCC_except_table5900
+ GCC_except_table5902
+ GCC_except_table5914
+ GCC_except_table6063
+ GCC_except_table6105
+ GCC_except_table6115
+ GCC_except_table6116
+ GCC_except_table6175
+ GCC_except_table6178
+ GCC_except_table6263
+ GCC_except_table6265
+ GCC_except_table6281
+ GCC_except_table6304
+ GCC_except_table6320
+ GCC_except_table6322
+ GCC_except_table6482
+ GCC_except_table6551
+ GCC_except_table6571
+ GCC_except_table6597
+ GCC_except_table6608
+ GCC_except_table6629
+ GCC_except_table6649
+ GCC_except_table6653
+ GCC_except_table6679
+ GCC_except_table6711
+ GCC_except_table6751
+ GCC_except_table6814
+ GCC_except_table6840
+ GCC_except_table6844
+ GCC_except_table6853
+ GCC_except_table6871
+ GCC_except_table6884
+ GCC_except_table6889
+ GCC_except_table6897
+ GCC_except_table6898
+ GCC_except_table6912
+ GCC_except_table6967
+ GCC_except_table7092
+ GCC_except_table7106
+ GCC_except_table7109
+ GCC_except_table7236
+ GCC_except_table7238
+ GCC_except_table7240
+ GCC_except_table7244
+ GCC_except_table7247
+ GCC_except_table7623
+ GCC_except_table7665
+ GCC_except_table7669
+ GCC_except_table7671
+ GCC_except_table7686
+ GCC_except_table7692
+ GCC_except_table7700
+ GCC_except_table7710
+ GCC_except_table7718
+ GCC_except_table7721
+ GCC_except_table7748
+ GCC_except_table7771
+ GCC_except_table7837
+ GCC_except_table7848
+ GCC_except_table7868
+ GCC_except_table7871
+ GCC_except_table7873
+ GCC_except_table7875
+ GCC_except_table7906
+ GCC_except_table7956
+ GCC_except_table8105
+ GCC_except_table8128
+ GCC_except_table8158
+ GCC_except_table8313
+ GCC_except_table8315
+ GCC_except_table8345
+ GCC_except_table8354
+ GCC_except_table8359
+ GCC_except_table8375
+ GCC_except_table8389
+ GCC_except_table8399
+ GCC_except_table8404
+ GCC_except_table8488
+ GCC_except_table8575
+ GCC_except_table8634
+ GCC_except_table8712
+ GCC_except_table8727
+ GCC_except_table8749
+ GCC_except_table8774
+ GCC_except_table8784
+ GCC_except_table8826
+ GCC_except_table8828
+ GCC_except_table8908
+ _CPLSetDebugTurboMode
+ _CPLUploadCheckRuleEnsureRelatedRecordIsOnServerFunction
+ _OBJC_CLASS_$_CPLTurboSyncObserver
+ _OBJC_IVAR_$_CPLBeforeUploadCheckItems._knownCloudRecords
+ _OBJC_IVAR_$_CPLDirectUploadTask._scopeChange
+ _OBJC_IVAR_$_CPLEngineForceSyncTask._allowsForcedTaskQueuing
+ _OBJC_IVAR_$_CPLEngineScheduler._closingBlock
+ _OBJC_IVAR_$_CPLLibraryInfo._transportData
+ _OBJC_IVAR_$_CPLLibraryState._transportData
+ _OBJC_IVAR_$_CPLPushToTransportScopeTask._scopeChange
+ _OBJC_IVAR_$_CPLScopeChange._transportData
+ _OBJC_IVAR_$_CPLTurboSyncObserver._canUseTurboModeInLowDataMode
+ _OBJC_IVAR_$_CPLTurboSyncObserver._canUseTurboModeInLowPowerMode
+ _OBJC_IVAR_$_CPLTurboSyncObserver._delegate
+ _OBJC_IVAR_$_CPLTurboSyncObserver._expirationDate
+ _OBJC_IVAR_$_CPLTurboSyncObserver._expireTimer
+ _OBJC_IVAR_$_CPLTurboSyncObserver._lock
+ _OBJC_IVAR_$_CPLTurboSyncObserver._lowPowerModeWatcher
+ _OBJC_IVAR_$_CPLTurboSyncObserver._networkWatcher
+ _OBJC_IVAR_$_CPLTurboSyncObserver._queue
+ _OBJC_IVAR_$_CPLTurboSyncObserver._turboModeFlags
+ _OBJC_IVAR_$_CPLTurboSyncObserver._turboModeObserver
+ _OBJC_METACLASS_$_CPLTurboSyncObserver
+ __OBJC_$_INSTANCE_METHODS_CPLTurboSyncObserver
+ __OBJC_$_INSTANCE_VARIABLES_CPLTurboSyncObserver
+ __OBJC_$_PROP_LIST_CPLTurboSyncObserver
+ __OBJC_CLASS_PROTOCOLS_$_CPLTurboSyncObserver
+ __OBJC_CLASS_RO_$_CPLTurboSyncObserver
+ __OBJC_METACLASS_RO_$_CPLTurboSyncObserver
+ ___32-[CPLTurboSyncObserver delegate]_block_invoke
+ ___36-[CPLTurboSyncObserver setDelegate:]_block_invoke
+ ___38-[CPLTurboSyncObserver expirationDate]_block_invoke
+ ___39-[CPLTurboSyncObserver _startObserving]_block_invoke
+ ___42-[CPLTurboSyncObserver setExpirationDate:]_block_invoke
+ ___42-[CPLTurboSyncObserver shouldUseTurboMode]_block_invoke
+ ___52-[CPLTurboSyncObserver canUseTurboModeInLowDataMode]_block_invoke
+ ___53-[CPLTurboSyncObserver canUseTurboModeInLowPowerMode]_block_invoke
+ ___55-[CPLTurboSyncObserver _updateExpirationDateFromTimer:]_block_invoke
+ ___56-[CPLTurboSyncObserver setCanUseTurboModeInLowDataMode:]_block_invoke
+ ___57-[CPLTurboSyncObserver setCanUseTurboModeInLowPowerMode:]_block_invoke
+ ___58-[CPLTurboSyncObserver batterySaverWatcherDidChangeState:]_block_invoke
+ ___59-[CPLEngineScheduler closeAndDeactivate:completionHandler:]_block_invoke_2
+ ___59-[CPLEngineScheduler closeAndDeactivate:completionHandler:]_block_invoke_3
+ ___59-[CPLEngineScheduler closeAndDeactivate:completionHandler:]_block_invoke_4
+ ___61-[CPLTurboSyncObserver watcher:stateDidChangeToNetworkState:]_block_invoke
+ ___62-[CPLTurboSyncObserver _updateExpirationDateAndNotifyDelegate]_block_invoke
+ ___62-[CPLTurboSyncObserver _updateExpirationDateAndNotifyDelegate]_block_invoke_2
+ ___63-[CPLTurboSyncObserver _updateExpirationDateLockedWithNewDate:]_block_invoke
+ ___75-[CPLEngineScheduler noteScopeNeedsToPullFromTransportWithSignificantEvent]_block_invoke
+ ___CPLSetDebugTurboMode_block_invoke
+ ___CPLShouldUseDebugTurboMode_block_invoke
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_48_e8_32s40w_e5_v8?0lw40l8s32l8
+ __debugTurboModeLock
+ __dontDiscardPersistentSession
+ __shouldForceInitialDownloadWhenJoining
+ __shouldUseDebugTurboMode
+ __shouldUseDebugTurboModeSet
- -[CPLEngineScopeStorage setScopeHasChangesToPullFromTransport:error:]
- -[CPLLibraryShareScopeChange shouldAlwaysUpdateScopeInfoWhenPossible]
- -[CPLScopeChange shouldAlwaysUpdateScopeInfoWhenPossible]
- GCC_except_table2009
- GCC_except_table2017
- GCC_except_table2240
- GCC_except_table2241
- GCC_except_table2244
- GCC_except_table2251
- GCC_except_table2255
- GCC_except_table2282
- GCC_except_table2289
- GCC_except_table2299
- GCC_except_table2302
- GCC_except_table2489
- GCC_except_table2588
- GCC_except_table2654
- GCC_except_table2703
- GCC_except_table2795
- GCC_except_table2802
- GCC_except_table2955
- GCC_except_table3044
- GCC_except_table3330
- GCC_except_table3332
- GCC_except_table3411
- GCC_except_table3415
- GCC_except_table3425
- GCC_except_table3435
- GCC_except_table3493
- GCC_except_table3495
- GCC_except_table3620
- GCC_except_table3644
- GCC_except_table3726
- GCC_except_table3730
- GCC_except_table3732
- GCC_except_table3734
- GCC_except_table3738
- GCC_except_table3899
- GCC_except_table3946
- GCC_except_table4191
- GCC_except_table4267
- GCC_except_table4271
- GCC_except_table4273
- GCC_except_table4282
- GCC_except_table4484
- GCC_except_table4498
- GCC_except_table4655
- GCC_except_table4685
- GCC_except_table4716
- GCC_except_table4734
- GCC_except_table4741
- GCC_except_table4749
- GCC_except_table4765
- GCC_except_table4767
- GCC_except_table4770
- GCC_except_table5142
- GCC_except_table5175
- GCC_except_table5177
- GCC_except_table5203
- GCC_except_table5337
- GCC_except_table5347
- GCC_except_table5404
- GCC_except_table5407
- GCC_except_table5585
- GCC_except_table5593
- GCC_except_table5683
- GCC_except_table5687
- GCC_except_table5693
- GCC_except_table5715
- GCC_except_table5716
- GCC_except_table5722
- GCC_except_table5766
- GCC_except_table5772
- GCC_except_table5776
- GCC_except_table5837
- GCC_except_table5839
- GCC_except_table6002
- GCC_except_table6044
- GCC_except_table6054
- GCC_except_table6055
- GCC_except_table6114
- GCC_except_table6117
- GCC_except_table6202
- GCC_except_table6204
- GCC_except_table6220
- GCC_except_table6243
- GCC_except_table6259
- GCC_except_table6261
- GCC_except_table6421
- GCC_except_table6449
- GCC_except_table6490
- GCC_except_table6536
- GCC_except_table6547
- GCC_except_table6568
- GCC_except_table6588
- GCC_except_table6592
- GCC_except_table6618
- GCC_except_table6650
- GCC_except_table6690
- GCC_except_table6753
- GCC_except_table6779
- GCC_except_table6783
- GCC_except_table6792
- GCC_except_table6810
- GCC_except_table6823
- GCC_except_table6828
- GCC_except_table6836
- GCC_except_table6837
- GCC_except_table6851
- GCC_except_table6906
- GCC_except_table7031
- GCC_except_table7045
- GCC_except_table7048
- GCC_except_table7174
- GCC_except_table7176
- GCC_except_table7178
- GCC_except_table7182
- GCC_except_table7185
- GCC_except_table7560
- GCC_except_table7600
- GCC_except_table7604
- GCC_except_table7606
- GCC_except_table7621
- GCC_except_table7627
- GCC_except_table7635
- GCC_except_table7641
- GCC_except_table7645
- GCC_except_table7653
- GCC_except_table7656
- GCC_except_table7676
- GCC_except_table7683
- GCC_except_table7772
- GCC_except_table7783
- GCC_except_table7803
- GCC_except_table7808
- GCC_except_table7810
- GCC_except_table7841
- GCC_except_table7891
- GCC_except_table8040
- GCC_except_table8063
- GCC_except_table8093
- GCC_except_table8248
- GCC_except_table8250
- GCC_except_table8280
- GCC_except_table8289
- GCC_except_table8294
- GCC_except_table8310
- GCC_except_table8324
- GCC_except_table8334
- GCC_except_table8339
- GCC_except_table8423
- GCC_except_table8510
- GCC_except_table8569
- GCC_except_table8647
- GCC_except_table8662
- GCC_except_table8684
- GCC_except_table8690
- GCC_except_table8709
- GCC_except_table8719
- GCC_except_table8762
- GCC_except_table8843
- _CPLSetTurboMode
- ___CPLSetTurboMode_block_invoke
- ___CPLShouldUseTurboMode_block_invoke
- __shouldUseTurboMode
- __shouldUseTurboModeSet
- __turboModeLock
CStrings:
+ "%@ (related to %@) is not known to be on server - will have to check"
+ "%@ called but it is already observing"
+ "%@ called but it is not observing"
+ "%@ should be called before setting a delegate"
+ "%@: scheduling expiration timer %@"
+ "%@: updating expiration date from %@ to %@"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/workspaces/cloudphotolibrary/Framework/Sources/CPLTurboSyncObserver.m"
+ "CPLDontAlwaysUpdateScopeInfoForSharedCollections"
+ "CloudPhotoLibrary-910.21.101"
+ "EnsureRelatedRecordIsOnServer"
+ "Updating turbo mode: %@"
+ "asset: %@"
+ "deactivating scheduler"
+ "enabled"
+ "finishSyncSession"
+ "post: %@"
+ "related record does not exist on server"
+ "shared-collections.always-update-scope-info"
+ "traData"
+ "transportData"
+ "turbosync.observer"
+ "\xf0\xf0a"
- "CloudPhotoLibrary-910.14.107"
- "\xf0\xf0Q"
```
