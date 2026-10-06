## Bom

> `/System/Library/PrivateFrameworks/Bom.framework/Bom`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a6a0` | `0x5a6bc` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0xad0` | `0xae8` | **`+0x18`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ _pkzip_crypto_init : 104 -> 112
~ _pkzip_crypto_decrypt_buffer : 124 -> 132
~ _BOMStackPeek : 40 -> 44
~ _BOMStackPoke : 32 -> 36
~ _darc_format_entry_free : 284 -> 272
~ _darc_format_entry_set_attribute : 584 -> 576
~ _darc_format_entry_get_attribute : 264 -> 248
~ _BOMPatternListExtractFromFile : 348 -> 340
~ _BOMPatternListExtractFromStrings : 280 -> 272
~ __BOMFileDirectRead : 952 -> 948
~ _BOMFileWrite : 460 -> 456
~ _BOMFileSeek : 648 -> 644
~ _search_for_data_descriptor : 120 -> 112
~ _fts_agent_read : 4600 -> 4596
~ _bom_crc32_update : 208 -> 216
~ _bom_crc32_finalize : 380 -> 376
~ _BOMCRC32ForBufferSegment : 216 -> 224
~ _crc32_clever : 236 -> 244
~ _BOMCRC32ForBufferSegmentFinal : 384 -> 388
~ __readArchInfo : 212 -> 208
~ __writeArchInfo : 172 -> 168
~ _BOMBomNewFromBomWithOptions : 1468 -> 1452
~ _BOMBomNewFromDirectoryWithSys : 2204 -> 2208
~ __visitDir : 1336 -> 1324
~ _BOMBomPathIDAndArchsForKey : 276 -> 272
~ __removeArchInfoForFSObject : 244 -> 252
~ __addArchInfoForFSObject : 340 -> 348
~ _BOMBomApproximateBytesRepresentedByVariantWithBlockSize : 1164 -> 1180
~ __addPathsToList : 372 -> 368
~ _release_fts_agent_state : 296 -> 324
~ _drain_fts_state : 1032 -> 1064
~ _parse_entry_cpio : 1580 -> 1584
~ _path_tree_node_release : 120 -> 116
~ _populate_sequester_stack : 332 -> 328
~ ___add_sequester_entry_block_invoke : 800 -> 796
~ _path_tree_node_push : 548 -> 540
~ _BOMCopierDestinationFree : 600 -> 576
~ _make_path : 624 -> 616
~ _create_entry_filesystem : 6896 -> 6900
~ _BOMCopierDestinationEntryWriteFatHeader : 720 -> 704
~ _BOMCopierCopySourceEntryToDestinationSet : 4104 -> 4068
~ _release_copy_state : 156 -> 140
~ _BOMBomHLIndexFree : 220 -> 224
~ _BOMBomHLIndexCommit : 240 -> 232
~ __resetCopier : 788 -> 780
~ __prepareCopierState : 612 -> 604
~ __copyFromDirToDir : 2928 -> 2836
~ __copyExtendedAttributes : 916 -> 920
~ __copyDataFork : 6552 -> 6596
~ __copyFromCPIO : 1892 -> 1868
~ __copyFromPKZip : 2092 -> 2108
~ _BOMCopierPrepareMatchContext : 1336 -> 1332
~ _BOMCopierReleaseMatchContext : 160 -> 168
~ _BOMCopierMatchBinary : 1096 -> 1092
~ _BOMFSOArchInfoInitialize : 1036 -> 1068
~ _BOMFSOArchInfoCopy : 156 -> 152
~ _BOMFSOArchInfoContainsArchitecture : 108 -> 124
~ _BOMFSOArchInfoThinKeepingArchs : 356 -> 360
~ _BOMFSOArchInfoSet : 228 -> 240
~ _BOMNameForFSObjectType : 32 -> 36
~ _BOMCopierSourceEntryNewFromPath : 1012 -> 1008
~ _BOMCopierSourceEntryFree : 588 -> 580
~ _parse_regular_file : 1416 -> 1420
~ _capture_extended_attributes : 1140 -> 1148
~ _BOMCopierSourceEntryNewFromFTSENT : 1076 -> 1072
~ _BOMCopierSourceEntryNewFromFSObject : 1924 -> 1920
~ _BOMCopierSourceEntrySkip : 824 -> 808
~ _skip_remaining_file_data : 252 -> 248
~ _BOMFSOTypeInfoInitialize : 400 -> 396
~ _BOMFSOTypeInfoInitializeDeferred : 532 -> 528
~ _BOMFSOTypeInfoSummary : 656 -> 664
~ _BOMFSOTypeInfoSummaryWithFormat : 2612 -> 2636
~ _BOMFSOTypeInfoParseSummaryWithSys : 884 -> 880
~ _BOMFSOArchInfoArchive : 272 -> 292
~ _BOMFSOArchInfoUnarchive : 360 -> 380
~ __ReadBlockTable : 328 -> 340
~ _BOMStorageCommit : 496 -> 512
~ __buildKey : 308 -> 320
~ _BOMCKTreeCount : 512 -> 516
~ _BOMTreeFree : 224 -> 232
~ __SyncCache : 84 -> 96
~ __WritePage : 236 -> 224
~ __PageSetValue : 924 -> 908
~ __findRemove : 1748 -> 1744
~ __BOMTreeDiagnosticTraverse : 476 -> 456
~ _BOMMemoryDump : 632 -> 628
~ __ReadPage : 244 -> 232
~ __removePageFromCache : 196 -> 208
~ __shiftKeysAndValues : 420 -> 380
~ _BOMBomEnumeratorNext : 1548 -> 1540
~ _BOMAppleDoubleADPathToPath : 180 -> 176
~ _BOMCPIOReadHeader : 568 -> 564
~ _BOMPKZipFree : 216 -> 192
~ _BOMPKZipReadLocalHeader : 1100 -> 1096
~ _BOMPKZipWriteLocalHeader : 940 -> 936
~ _BOMPKZipWriteCentralDirectory : 768 -> 760
~ _BOMPKZipStoreQuarantinePath : 368 -> 364
~ _is_valid_utf8_string : 88 -> 84
~ __chPerms : 476 -> 484
~ __createNewFatArchArray : 88 -> 96
~ __normalizeBomCopySpecification : 660 -> 692
~ __printBomCopySpecification : 580 -> 584
~ __sanitizePath : 720 -> 716
~ __dense_initialize : 128 -> 156
~ _BOMFilesystemInfoCreate : 384 -> 416
~ _BOMFilesystemInfoQuery : 944 -> 936
~ __fat_header_big_to_host : 104 -> 120
~ __fat_header_host_to_big : 100 -> 116
~ _BOMGetArchInfoFromName : 80 -> 100
~ _BOMGetArchInfoFromCpuType : 296 -> 312
~ _BOMSwapFatArch : 68 -> 80
~ _BOMSwapFatArch64 : 76 -> 88
~ _BOMCopierSandbox_opendir : 464 -> 460
CStrings:
+ "Jun  9 2026"
- "May 21 2026"
```
