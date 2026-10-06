## libParallelCompression.dylib

> `/usr/lib/libParallelCompression.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55c14` | `0x55dac` | **`+0x198`** |
| `__TEXT.__eh_frame` | `0x48` | `—` | **`-0x48`** |
| `__TEXT.__cstring` | `0xf55e` | `0xf571` | **`+0x13`** |

### Other Changes

```diff

-462.0.0.0.0
+465.0.0.0.0

-  Functions: 757
-  Symbols:   988
-  CStrings:  2260
+  Functions: 759
+  Symbols:   990
+  CStrings:  2261
Symbols:
+ _SemInit
+ _getDefaultNThreadsWithBlockSize
Functions:
~ _processEntryThreadProc : 5696 -> 5836
~ _resolveSameThreadProc : 788 -> 756
~ _ParallelArchiveWriteDirContents : 8476 -> 8488
~ _InSituStreamClose : 424 -> 440
~ _tempStreamClose : 156 -> 152
~ _resizeStream : 984 -> 960
~ _yaa_decodeHeaderField : 684 -> 688
~ _yaa_decodeHeaderInfo : 876 -> 880
~ _yaa_decodeACL : 300 -> 288
~ _yaa_setEntryAttributes : 1656 -> 1664
~ _yaa_setEntryXAT : 456 -> 460
~ _yaa_setEntryACL : 1356 -> 1376
~ _ParallelArchiveGetPayloadSize : 108 -> 116
~ _fileRequestCloseAndGetKey : 1136 -> 1140
~ _ParallelArchiveWriteEntryHeader : 492 -> 508
~ _BXDiffWithCache : 3852 -> 3880
~ _pc_log_error : 268 -> 272
~ _pc_log_warning : 276 -> 280
~ _pc_log_info : 264 -> 268
~ _filePatchCacheOpen : 628 -> 624
~ _filePatchCacheLookup : 1012 -> 1028
~ _openEntryTemp : 416 -> 444
~ _filePatchCacheUpdate : 612 -> 636
~ _aaForkOutputStreamOpen : 760 -> 768
~ _ForkOutputStreamWrite : 2776 -> 2804
~ _ForkOutputStreamClose : 188 -> 196
~ _directoryPatchBegin : 1716 -> 1724
~ _directoryPatchEnd : 1004 -> 1000
~ _directoryPatchPayload : 160 -> 156
~ _ECC65537GetParity : 740 -> 732
~ _ECC65537CheckAndFix : 1756 -> 1764
~ _ecc65537PolyEval : 112 -> 108
~ _ecc65537Triangulate : 508 -> 464
~ _ecc65537Solve : 348 -> 352
~ _PagedFileCreate : 996 -> 932
~ _PagedFileDump : 720 -> 688
~ _getFreeCachePos : 292 -> 280
~ _PagedFileHasNoIn : 76 -> 80
~ _PagedFileHasAllOut : 116 -> 108
~ _PagedFileReadAndReleaseIn : 540 -> 544
~ _PagedFileRetainAndWriteOut : 576 -> 584
~ _storeCachePos : 740 -> 732
~ _restoreThreadErrorContext : 276 -> 260
~ _load_variants : 388 -> 400
~ _RawImageDiff : 6832 -> 6816
~ _BXDiff5Data_free : 136 -> 124
~ _controls_combo_enforce_copy_fork_boundary : 508 -> 536
~ _SharedBufferCreate : 924 -> 912
~ _ParallelArchiveRead : 1368 -> 1440
~ _readProcessData : 3596 -> 3416
+ _getDefaultNThreadsWithBlockSize
~ _serializeHexString : 80 -> 84
~ _sha1xor : 44 -> 40
~ _makePath : 204 -> 192
~ _statPath : 132 -> 128
~ _concatExtractPathEx : 732 -> 736
~ _pathIsValid : 220 -> 224
~ _getTempDir : 196 -> 204
~ _loadFileContents : 524 -> 528
~ _clearEntryXAT : 416 -> 412
~ _enumerateTree : 228 -> 220
~ _aaSegmentStreamOpen : 672 -> 668
~ _SegmentStreamClose : 104 -> 120
~ _searchThreadMain : 956 -> 972
~ _archiveTreeUpdateChilds : 328 -> 348
~ _ArchiveTreeCreateFromIndex : 984 -> 1012
~ _archiveTreeFromIndexBeginProc : 776 -> 788
~ _archiveTreeSort : 900 -> 884
~ _archiveTreeFromArchiveBlobProc : 184 -> 180
~ _expandDirRange : 988 -> 1016
~ _ArchiveTreeMergeAndDestroy : 816 -> 844
~ _archiveTreeSortStringTable : 184 -> 200
~ _archiveTreeUpdateDepth : 164 -> 180
~ _ArchiveTreePrune : 620 -> 636
~ _ArchiveTreeInsert : 536 -> 524
~ _archiveTreeRemapNodes : 504 -> 524
~ _expandDirRangeThreadProc : 1732 -> 1720
~ _AADecompressionInputStreamOpen : 8 -> 4
~ _OArchiveFileStreamDestroyEx : 484 -> 480
~ _OArchiveFileStreamWrite : 772 -> 788
~ _bxdiff5Free : 508 -> 504
~ _bxdiff5Dump : 908 -> 920
~ _bxdiff5SetIn : 392 -> 380
~ _bxdiff5CreateComboControls : 588 -> 600
~ _bxdiff5CreatePatchBackend : 1852 -> 1876
~ _bxdiff5CreateComboPatch : 476 -> 484
~ _BXDiff5WithIndividualPatches : 1840 -> 1864
~ _StringTableAppendTable : 308 -> 296
~ _StringTableSort : 388 -> 372
~ _getBXDiffControls : 1660 -> 1644
~ _ParallelCompressionAFSCStreamClose : 1928 -> 1932
~ _ParallelCompressionAFSCFixupMetadataEx : 4740 -> 4736
~ _BXPatch5StreamWithFlags : 2864 -> 2940
~ _BXPatch5InPlace : 2952 -> 2908
~ _CC_CKSUM_Update : 80 -> 88
~ _ThreadPipelineCreate : 1212 -> 1160
~ _ThreadPipelineDestroy : 988 -> 992
~ _pc_zero_coder_decode : 348 -> 344
~ _pc_zero_coder_encode : 324 -> 312
~ _PCompressFilter : 2500 -> 2472
~ _ParallelArchiveExtract : 2992 -> 2984
~ _extractBeginProc : 2976 -> 2980
~ _ThreadPoolCreate : 608 -> 604
~ _ThreadPoolDestroy : 732 -> 752
~ _ThreadPoolSync : 528 -> 540
~ _RawImagePatchInternal : 7144 -> 7152
~ _OEncoderStreamCreate : 364 -> 448
~ _ILowMemoryDecoderStreamCreate : 1420 -> 1424
~ _initBestMatchThreadProc : 1076 -> 1064
~ _BXDiffMatchesCreate : 3196 -> 3176
~ _getProfile : 960 -> 968
~ _BXDiffMatchesGetBestMatch : 188 -> 192
~ _bestMatchInRange : 604 -> 548
~ _quicksort64 : 1424 -> 1420
~ _AACompressionOutputStreamOpen : 836 -> 900
~ _CompressionWorkerDataCreate : 316 -> 264
~ _aaCompressionOutputStreamClose : 344 -> 340
~ _generateBOM : 3364 -> 3388
~ _bomBeginProc : 2680 -> 2672
~ _storeBlock : 376 -> 368
~ _createTree : 1524 -> 1452
~ _getTablePK : 24 -> 32
~ _extractClonesBlob : 104 -> 100
~ _pc_array_indirect_sort : 184 -> 192
~ _convertBegin : 1412 -> 1408
~ _convertEnd : 1256 -> 1260
~ _convertBlob : 796 -> 808
~ _ParallelCompressionFileOpen : 3872 -> 3956
~ _ParallelCompressionFileSeek : 156 -> 152
~ _patchCacheKeyFromSHA1 : 64 -> 72
~ _patchCacheLookup : 320 -> 316
~ _patchCacheUpdate : 552 -> 548
~ _aaSequentialDecompressionIStreamOpen : 2232 -> 2264
~ _LargeFileWorker : 1568 -> 1560
~ _LargeFileConsumer : 200 -> 188
~ _GetLargeFileControlsWithStreams : 1876 -> 1872
~ _convert_internal_controls : 124 -> 136
~ _fingerprint_worker : 756 -> 768
~ _aaCacheStreamOpen : 744 -> 740
~ _aaCacheStreamSeek : 144 -> 140
~ _aaCacheStreamClose : 328 -> 324
~ _cacheFlush : 216 -> 204
~ _setAAHeaderFromHeader_ODC : 764 -> 760
~ _yaa_parseFields : 1160 -> 1148
~ _ParallelArchiveECCGenerateCommon : 1616 -> 1584
~ _ParallelArchiveECCFixCommon : 2448 -> 2456
~ _verifyDirThreadProc : 1520 -> 1536
~ _isValidAliasOrEngine : 164 -> 172
~ _ParallelArchiveDBSetCreate : 528 -> 512
~ _ParallelArchiveDBSetDestroy : 308 -> 300
~ _ParallelArchiveDBReadRequestOpenWithSet : 324 -> 320
~ _ParallelArchiveDBCloneWithSet : 320 -> 316
~ _ParallelArchiveSort : 2644 -> 2688
~ _indexPayloadAndPaddingProc : 44 -> 52
~ _toOctal6 : 104 -> 84
~ _toHex8 : 136 -> 108
~ _ParallelArchiveOLDWriterCreate : 724 -> 748
+ _SemInit
~ _ParallelArchiveOLDWriterAddEntry : 1508 -> 1504
~ _pushControls : 240 -> 256
~ _mergeDiffSegmentVectors : 1036 -> 1044
~ _getComboControlsFromMergedDiffSegmentVectors : 584 -> 596
~ _rawimg_force_in_place : 3020 -> 3004
~ _SimStreamClose : 348 -> 360
~ _rawimg_destroy : 168 -> 164
~ _rawimg_show : 476 -> 480
~ _rawimg_add_fork : 368 -> 364
~ _rawimg_verify : 1192 -> 1244
~ _rawimg_get_digests : 3136 -> 3192
~ _rawimg_free_chunks : 124 -> 120
~ _rawimg_set_fork_types : 892 -> 868
~ _BXPatch4 : 1820 -> 1812
~ _ParallelArchiveCombine : 2296 -> 2300
~ _MemGateDestroy : 504 -> 496
~ _MemGateInit : 460 -> 464
~ _loadDirectory : 1332 -> 1316
~ _loadDirectoryProc : 808 -> 804
~ _loadManifest : 1456 -> 1500
~ _loadManifestProc : 2216 -> 2236
~ _mergeContents : 1100 -> 1120
~ _applyRules : 1424 -> 1408
~ _markFilesMatchingPrefixArray : 1344 -> 1360
~ _fixOpsForHardLinkClusters : 932 -> 900
~ _initOps : 1736 -> 1676
~ _updateOps : 2224 -> 2180
~ _checkOps : 540 -> 536
~ _dumpContentsEntries : 836 -> 812
~ _processPatchThreadProc : 1488 -> 1516
~ _computePatches : 1028 -> 1032
~ _DirectoryDiff : 3852 -> 3840
~ _generatePatch : 2844 -> 2816
~ __ZL17dumpContentsStatsPK17DirectoryContents : 340 -> 344
~ __ZL17dumpContentsStatsPK21DirectoryDiffContents : 508 -> 520
CStrings:
+ "invalid block size"
```
