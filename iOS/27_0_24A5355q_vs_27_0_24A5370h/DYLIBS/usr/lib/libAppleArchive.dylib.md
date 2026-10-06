## libAppleArchive.dylib

> `/usr/lib/libAppleArchive.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__eh_frame` | `0x48` | `—` | **`-0x48`** |
| `__TEXT.__text` | `0x832a8` | `0x832a0` | **`-0x8`** |

### Other Changes

```diff

-462.0.0.0.0
+465.0.0.0.0

-  Functions: 1071
-  Symbols:   1309
+  Functions: 1072
+  Symbols:   1310
Symbols:
+ _getDefaultNThreadsWithBlockSize
Functions:
~ _PCompressFilter : 2500 -> 2472
~ _extractStreamWriteBlob : 1728 -> 1732
~ _retireThreadProc : 1276 -> 1332
~ _AAExtractArchiveOutputStreamOpen : 1352 -> 1364
~ _SharedBufferCreate : 924 -> 912
~ _aaSequentialDecompressionIStreamOpen : 2232 -> 2264
~ _AADecompressionInputStreamOpen : 8 -> 4
~ _ThreadPipelineCreate : 1212 -> 1160
~ _ThreadPipelineDestroy : 988 -> 992
~ _rawimg_destroy : 168 -> 164
~ _rawimg_show : 476 -> 480
~ _rawimg_add_fork : 368 -> 364
~ _rawimg_verify : 1192 -> 1244
~ _rawimg_get_digests : 3136 -> 3192
~ _rawimg_free_chunks : 124 -> 120
~ _rawimg_set_fork_types : 892 -> 868
~ _pc_array_indirect_sort : 184 -> 192
~ _AEADecryptAsyncStreamOpen : 788 -> 780
~ _pushRange : 312 -> 316
~ _decryptAsyncClose : 484 -> 480
~ _processClusterHeader : 1928 -> 1936
~ _processPadding : 820 -> 816
~ _pushPaddingRange : 168 -> 176
~ _startStreaming : 712 -> 708
~ _AAArchiveStreamWritePathList : 5808 -> 5784
~ _AEADecryptionRandomAccessInputStreamOpen : 700 -> 716
~ _RandomAccessDecryptionStreamDestroy : 268 -> 252
~ _writeProc : 3072 -> 3068
~ _asyncContext : 760 -> 756
~ _AAAssetExtractorWrite : 1124 -> 1116
~ _AAAssetExtractorSetParameterCallback : 132 -> 128
~ _AEAAuthDataCreateWithContext : 1264 -> 1268
~ _AEAAuthDataGetEntry : 356 -> 344
~ _AEAAuthDataSetEntry : 712 -> 708
~ _AAPathFilterAddRule : 1272 -> 1248
~ _AAPathFilterApply : 1068 -> 1060
~ _aeaChecksum : 496 -> 500
~ _AAVerifyDirectoryArchiveOutputStreamOpen : 1828 -> 1820
~ _verifyDirectoryStreamWriteBlob : 636 -> 632
~ _AEADecryptionInputStreamOpen : 1440 -> 1452
~ _aeaInputStreamRead : 540 -> 544
~ _aeaInputStreamClose : 452 -> 448
~ _aeaInputStreamAuthenticatePadding : 1180 -> 1176
~ _aaCacheStreamOpen : 744 -> 740
~ _aaCacheStreamSeek : 144 -> 140
~ _aaCacheStreamClose : 328 -> 324
~ _cacheFlush : 216 -> 204
~ _aeaOutputStreamRunThreads : 1172 -> 1164
~ _aeaOutputStreamWrite : 564 -> 568
~ _aeaOutputStreamCloseAndUpdateContext : 1076 -> 1088
~ _afStreamClose : 416 -> 400
~ _BXPatch5StreamWithFlags : 2864 -> 2940
~ _BXPatch5InPlace : 2952 -> 2908
~ _aeaKeychainCreateAttributes : 732 -> 744
~ _RawImagePatchInternal : 7144 -> 7152
~ _AARandomAccessByteStreamProcess : 1444 -> 1460
~ _ECC65537GetParity : 740 -> 732
~ _ECC65537CheckAndFix : 1756 -> 1764
~ _ecc65537PolyEval : 112 -> 108
~ _ecc65537Triangulate : 508 -> 464
~ _ecc65537Solve : 348 -> 352
~ _ILowMemoryDecoderStreamCreate : 1420 -> 1424
~ _rawimg_force_in_place : 3020 -> 3004
~ _SimStreamClose : 348 -> 360
~ _AARemoveArchiveOutputStreamOpen : 876 -> 868
~ _workerProc : 252 -> 232
~ _removeStreamClose : 752 -> 756
~ _removeStreamWriteHeader : 1080 -> 1084
~ _asyncContext : 816 -> 812
~ _aeaContainerCreateExisting : 4112 -> 4140
~ _aaForkOutputStreamOpen : 760 -> 768
~ _ForkOutputStreamWrite : 2776 -> 2804
~ _ForkOutputStreamClose : 188 -> 196
~ _StringTableAppendTable : 308 -> 296
~ _StringTableSort : 388 -> 372
~ _ParallelArchiveECCFixCommon : 2448 -> 2456
~ _initBestMatchThreadProc : 1076 -> 1064
~ _BXDiffMatchesCreate : 3196 -> 3176
~ _getProfile : 960 -> 968
~ _BXDiffMatchesGetBestMatch : 188 -> 192
~ _bestMatchInRange : 604 -> 548
~ _quicksort64 : 1424 -> 1420
~ _OArchiveFileStreamDestroyEx : 484 -> 480
~ _OArchiveFileStreamWrite : 772 -> 788
~ _writeProc : 1732 -> 1780
~ _aaAssetDecompressionStreamOpenWithState : 1424 -> 1432
~ _ParallelCompressionAFSCStreamClose : 1928 -> 1932
~ _ParallelCompressionAFSCFixupMetadataEx : 4740 -> 4736
~ _AAChunkInputStreamOpen : 592 -> 616
~ _streamClose : 344 -> 340
~ _streamPRead : 996 -> 1024
~ _CC_CKSUM_Update : 80 -> 88
~ _chunkAsyncClose : 484 -> 480
~ _lockedStateReserveActiveChunks : 400 -> 392
~ _chunkAsyncGetRange : 456 -> 464
~ _chunkAsyncProcess : 456 -> 476
~ _streamProc : 3412 -> 3440
~ _stateSortRanges : 128 -> 124
~ _AAAsyncByteStreamProcessAllRanges : 728 -> 736
+ _getDefaultNThreadsWithBlockSize
~ _serializeHexString : 80 -> 84
~ _makePath : 204 -> 192
~ _normalizePath : 308 -> 284
~ _concatExtractPathEx : 732 -> 736
~ _pathIsValid : 220 -> 224
~ _getTempDir : 196 -> 204
~ _enumerateTree : 228 -> 220
~ _restoreThreadErrorContext : 276 -> 260
~ _aaInPlaceStreamOpen : 728 -> 744
~ _aaInPlaceStreamClose : 228 -> 216
~ _aaSegmentStreamOpen : 672 -> 668
~ _SegmentStreamClose : 104 -> 120
~ _load_variants : 388 -> 400
~ _RawImageDiff : 6832 -> 6816
~ _BXDiff5Data_free : 136 -> 124
~ _controls_combo_enforce_copy_fork_boundary : 508 -> 536
~ _tempStreamClose : 156 -> 152
~ _resizeStream : 984 -> 960
~ _bxdiff5Free : 508 -> 504
~ _bxdiff5Dump : 908 -> 920
~ _bxdiff5SetIn : 392 -> 380
~ _bxdiff5CreateComboControls : 588 -> 600
~ _bxdiff5CreatePatchBackend : 1852 -> 1876
~ _bxdiff5CreateComboPatch : 476 -> 484
~ _BXDiff5WithIndividualPatches : 1840 -> 1864
~ _InSituStreamClose : 424 -> 440
~ _LargeFileWorker : 1568 -> 1560
~ _LargeFileConsumer : 200 -> 188
~ _GetLargeFileControlsWithStreams : 1876 -> 1872
~ _convert_internal_controls : 124 -> 136
~ _fingerprint_worker : 756 -> 768
~ _pc_log_error : 268 -> 272
~ _pc_log_warning : 276 -> 280
~ _pc_log_info : 264 -> 268
~ _AAChunkOutputStreamOpen : 788 -> 784
~ _streamClose : 796 -> 804
~ _streamPWrite : 1908 -> 1860
~ _chunkAppendHole : 408 -> 416
~ _loadAndDecodeHeader_Cpio : 3536 -> 3496
~ _getBXDiffControls : 1660 -> 1644
~ _aaEntryYFPBlobInitWithPath : 1172 -> 1164
~ _writeProc : 5396 -> 5392
~ _setupContext : 2620 -> 2608
~ _retireEntryRange : 1188 -> 1196
~ _aaEntryAttributesApplyToPath : 1604 -> 1608
~ _AARandomAccessDecodeAndExtract : 5328 -> 5360
~ _stateDestroy : 180 -> 176
~ _workerProc : 8268 -> 8104
~ _stateShouldCreateFileInCluster : 240 -> 236
~ _stateAppendEntry : 1564 -> 1568
~ _AAFieldKeySetContainsKey : 228 -> 232
~ _AAFieldKeySetInsertKey : 464 -> 480
~ _AAFieldKeySetRemoveKey : 272 -> 284
~ _AAFieldKeySetInsertKeySet : 472 -> 488
~ _AAFieldKeySetSerialize : 128 -> 132
~ _AAPathListCreateWithDirectoryContents : 2604 -> 2612
~ _normalize : 668 -> 672
~ _AAPathListCreateWithPath : 972 -> 964
~ _AAPathListGetNode : 328 -> 324
~ _extractStreamClose : 3132 -> 3100
~ _extractStreamWriteHeader : 2724 -> 2744
~ _aaHeaderInitWithPath : 3376 -> 3372
~ _aaHeaderBlobArrayPayloadSize : 52 -> 64
~ _update_field_sizes : 668 -> 672
~ _AAHeaderGetKeyIndex : 56 -> 64
~ _AAHeaderGetFieldString : 288 -> 284
~ _AAHeaderGetFieldTimespec : 360 -> 348
~ _AAHeaderSetFieldHash : 636 -> 632
~ _aaEntryXATBlobInitWithEncodedData : 868 -> 872
~ _aaEntryXATBlobInitWithFD : 792 -> 784
~ _aaEntryXATBlobApplyToFD : 752 -> 756
~ _AAEntryXATBlobGetEntry : 356 -> 344
~ _AAEntryXATBlobSetEntry : 712 -> 708
~ _loadAndDecodeHeader_Ustar : 4532 -> 4476
~ _isZero : 108 -> 112
~ _aaEntryACLBlobInitWithEncodedData : 1108 -> 1100
~ _AAEntryACLBlobSetEntry : 792 -> 788
~ _AAAssetBuilderGenerate : 5332 -> 5348
~ _stateGenerateArchive : 7060 -> 7084
~ _stateDestroy : 300 -> 276
~ _stateCollectorStreamWriteHeader : 2428 -> 2444
~ _computePatchesWorkerProc : 2660 -> 2612
~ _encoderStreamWriteHeader : 432 -> 444
~ _encoderStreamWriteBlob : 652 -> 656
~ _pushControls : 240 -> 256
~ _mergeDiffSegmentVectors : 1036 -> 1044
~ _getComboControlsFromMergedDiffSegmentVectors : 584 -> 596
~ _aaCreateArchString : 432 -> 452
~ _aaEntryMCOStringCreateWithPath : 1852 -> 1844
~ _decompressToData : 1948 -> 1952
~ _afscStreamWrite : 1060 -> 1048
~ _AACompressionOutputStreamOpen : 836 -> 900
~ _CompressionWorkerDataCreate : 316 -> 264
~ _aaCompressionOutputStreamClose : 344 -> 340
~ _AACompressionOutputStreamOpenExisting : 2112 -> 2168
~ _ThreadPoolCreate : 608 -> 604
~ _ThreadPoolDestroy : 732 -> 752
~ _ThreadPoolSync : 528 -> 540
~ _AADecompressionRandomAccessInputStreamOpen : 1820 -> 1840
~ _RandomAccessDecompressStreamDestroy : 120 -> 116
~ _AAAsyncByteStreamGetRange : 1004 -> 1000
~ _graisClose : 836 -> 844
~ _AAGenericRandomAccessInputStreamOpen : 2020 -> 2016
~ _streamProc : 1772 -> 1756
~ _writerProc : 1204 -> 1208
~ _AEADecryptToStreamChunk : 2164 -> 2156
~ _PagedFileCreate : 996 -> 932
~ _PagedFileDump : 720 -> 688
~ _getFreeCachePos : 292 -> 280
~ _PagedFileHasNoIn : 76 -> 80
~ _PagedFileHasAllOut : 116 -> 108
~ _PagedFileReadAndReleaseIn : 540 -> 544
~ _PagedFileRetainAndWriteOut : 576 -> 584
~ _storeCachePos : 740 -> 732
```
