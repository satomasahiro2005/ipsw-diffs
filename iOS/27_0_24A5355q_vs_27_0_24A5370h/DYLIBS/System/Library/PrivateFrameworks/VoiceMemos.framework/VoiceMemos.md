## VoiceMemos

> `/System/Library/PrivateFrameworks/VoiceMemos.framework/VoiceMemos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47f80` | `0x47e60` | **`-0x120`** |
| `__TEXT.__unwind_info` | `0x1a80` | `0x1a78` | **`-0x8`** |

### Other Changes

```diff

-1428.0.0.0.0
+1431.0.0.0.0
Symbols:
+ _NSPersistentStoreRemoteChangeNotificationPostOptionKey
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- _NSXPCStorePostUpdateNotificationsKey
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIfEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ +[NSManagedObjectModel(NewObjectModel) updateAllowsCloudEncryptionAttributes:] : 456 -> 452
~ _RCObserveChangesToKeyPaths : 408 -> 404
~ ___46+[RCBuiltinRecordingsFolder allBuiltInFolders]_block_invoke : 224 -> 212
~ ___59-[RCSavedRecordingsModel eraseRecordingsDeletedBeforeDate:]_block_invoke : 452 -> 448
~ -[NSFileManager(RCAdditions) rc_cleanUpTemporaryDirectory] : 752 -> 748
~ -[RCDurationFormatter _replaceComponentPlaceholderForType:withString:inLocalizedDataFormatTemplate:] : 388 -> 384
~ ___56-[RCSSavedRecordingService observeFinalizingRecordings:]_block_invoke.99 : 576 -> 572
~ -[RCWaveformGenerator _onQueue_performInternalFinishedLoadingBlocksAndFinishObservers] : 476 -> 472
~ -[RCWaveformGenerator _onQueue_performObserversBlock:] : 312 -> 308
~ ___63-[RCWaveformGenerator _appendPowerMeterValuesFromSampleBuffer:]_block_invoke : 128 -> 116
~ ___76-[RCWaveformGenerator _appendAveragePowerLevelsByDigestingWaveformSegments:]_block_invoke : 372 -> 368
~ -[RCWaveformSegment verboseDescription] : 396 -> 392
~ -[RCWaveformSegment hasUniformPowerLevel:] : 144 -> 140
~ -[RCWaveformSegment isWaveformDataAlmostEqualToDataInSegment:] : 244 -> 236
~ +[RCWaveformSegment segmentsByShiftingSegments:byTimeOffset:] : 440 -> 436
~ +[RCWaveformSegment segmentsByMergingSegments:preferredSegmentDuration:beforeTime:andThenUsePreferredSegmentDuration:] : 1184 -> 1176
~ +[RCWaveformSegment _segmentsByJoiningSegment:toSegmentIfNecessaryWithGreaterSegment:averagePowerLevelJoinLimit:] : 1016 -> 1012
~ +[RCWaveformSegment _segmentByMergingMergableSegments:] : 592 -> 588
~ +[NSManagedObjectModel(NewObjectModel) modelCompatibleWithStoreMetadata:forStoreURL:] : 796 -> 788
~ ___100-[RCSavedRecordingsModel enumerateExistingRecordingsWithProperties:predicate:sortDescriptors:block:]_block_invoke : 632 -> 628
~ ___59-[RCSavedRecordingsModel _enumerateFetchedRecordingTitles:]_block_invoke : 412 -> 408
~ ___79-[RCSavedRecordingsModel enumerateChangeHistorySinceToken:forStore:usingBlock:]_block_invoke : 352 -> 348
~ -[RCSavedRecordingsModel _postProcessCloudRecordingForRecordingWithId:named:userInfo:isMigrationImport:isMusicMemoImport:sharingMetadata:] : 2272 -> 2268
~ ___49-[RCSavedRecordingsModel addRecordings:toFolder:]_block_invoke : 300 -> 296
~ ___42-[RCSavedRecordingsModel eraseRecordings:]_block_invoke : 540 -> 536
~ ___43-[RCSavedRecordingsModel deleteRecordings:]_block_invoke : 536 -> 532
~ ___51-[RCSavedRecordingsModel restoreDeletedRecordings:]_block_invoke : 512 -> 508
~ ___41-[RCSavedRecordingsModel eraseAllDeleted]_block_invoke : 448 -> 444
~ -[RCSavedRecordingsModel mergeRecordings:] : 920 -> 916
~ -[RCSavedRecordingsModel _mergeFolders:intoTargetFolder:] : 356 -> 352
~ -[RCSavedRecordingsModel _mergeDuplicateUUIDFolders:] : 572 -> 568
~ -[RCSavedRecordingsModel _rerankFolders] : 496 -> 492
~ ___isUniqueMusicMemo_block_invoke : 280 -> 276
~ -[RCComposition _initWithDictionaryPListRepresentation:bundleURLForRebasing:] : 912 -> 908
~ -[RCComposition dictionaryPListRepresentation] : 556 -> 552
~ -[RCComposition compositionByDeletingAndSplittingAtComposedTimeRange:] : 832 -> 828
~ -[RCComposition compositionByClippingToComposedTimeRange:] : 568 -> 564
~ -[RCComposition compositionByOverdubbingWithFragment:] : 1216 -> 1212
~ -[RCComposition enumerateOrphanedFragmentsWithBlock:] : 864 -> 856
~ -[RCComposition _findOriginalComposedAsset:] : 576 -> 572
~ -[RCComposition _calculateComposedAVURLDerivedValues] : 824 -> 820
~ -[RCComposition _calculateComposedFragments] : 2184 -> 2176
~ -[RCComposition rcs_allAssetsAreMissing] : 340 -> 336
~ -[RCComposition moveTo:recordingID:error:] : 688 -> 684
~ +[RCSavedRecording deleteOrphanedEntityRevisionsWithContext:] : 528 -> 524
~ +[RCSavedRecording fetchLegacyRecordingsForMigrationWithContext:] : 924 -> 916
~ -[RCWaveformDataSource _performObserversBlock:] : 484 -> 480
~ -[RCWaveform hasUniformPowerLevel:] : 404 -> 400
~ -[RCWaveform averagePowerLevelsRate] : 436 -> 432
~ -[RCComposition(RCAVFoundation) _enumerateTracksForInsertionPreferringSpatial:enumeratorBlock:error:] : 1028 -> 1024
~ ___54+[RCSSavedRecordingServiceConnection serviceInterface]_block_invoke : 2296 -> 2300
~ -[NSFetchedResultsController(RCAdditions) rc_sectionsByName] : 324 -> 320
~ -[AVAudioPCMBuffer(RCAdditions) initWithCoder:] : 436 -> 440
~ ___49-[AVAudioPCMBuffer(RCAdditions) extractChannels:]_block_invoke : 52 -> 60
~ -[AVAudioPCMBuffer(RCAdditions) trimmedBuffer:] : 248 -> 272
~ ___49-[RCSSavedRecordingService openServiceConnection]_block_invoke.27 : 248 -> 244
~ ___56-[RCSSavedRecordingService observeFinalizingRecordings:]_block_invoke : 636 -> 632
~ ___55-[RCSSavedRecordingService checkRecordingAvailability:]_block_invoke : 332 -> 328
~ ___81-[RCSSavedRecordingService _onQueueInvalidatePendingCompletionHandlersWithError:]_block_invoke : 256 -> 252
~ -[RCSSavedRecordingService _invalidatePendingSynchronousCompletionHandlersWithError:] : 380 -> 376
~ -[__RCKeyPathObservance remove] : 320 -> 316
~ ___47-[RCCompositionWaveformDataSource startLoading]_block_invoke_3 : 728 -> 724
~ -[RCCaptureInputWaveformDataSource _initializeCaptureComposition] : 796 -> 792
~ -[RCCaptureInputWaveformDataSource waveformSegmentsInTimeRange:] : 964 -> 956
~ -[RCSpatialAsset _findSpatialTrack] : 304 -> 300
~ -[RCSpatialAsset _findOverdubTrack] : 392 -> 388
~ -[RCSpatialAsset _findSpatialMetadataGroup] : 300 -> 296
~ -[RCSpatialAsset _metadataGroupFor:] : 800 -> 796
~ -[RCSpatialAsset _isSpatialTrack:] : 352 -> 348
~ -[RCSpatialAsset _descriptionIsSpatial:] : 140 -> 152
~ -[NSFileManager(RCAdditions) rc_uniqueFileSystemURLWithPreferredURL:] : 736 -> 732
~ -[NSFileManager(RCAdditions) rc_cleanUpAssetsInDirectory:] : 496 -> 492
~ -[AVAsset(RCAdditions) rc_allCodecNames] : 676 -> 668
~ -[AVAsset(RCAdditions) rc_trackIsSpatial:] : 584 -> 580
~ -[AVAsset(RCAdditions) rc_hasSpatialTracks] : 424 -> 420
~ +[AVURLAsset(RCAdditions) rc_updateFile:withTranscriptionData:error:] : 1072 -> 1060
```
