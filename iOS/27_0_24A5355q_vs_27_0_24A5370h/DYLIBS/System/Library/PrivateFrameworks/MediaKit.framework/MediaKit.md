## MediaKit

> `/System/Library/PrivateFrameworks/MediaKit.framework/MediaKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2cdc4` | `0x2ceb4` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x6c8` | `0x6c0` | **`-0x8`** |

### Other Changes

```text
Functions:
~ _GPTuuidType2HumanExtended : 232 -> 236
~ _lookupDESC : 168 -> 200
~ _GPTCFCreateMap : 1544 -> 1516
~ _BootAttrSearch : 56 -> 64
~ _addPartitionRecord : 312 -> 316
~ _srequest : 720 -> 744
~ _addentry : 248 -> 240
~ _GPTRecordMapSection : 744 -> 764
~ _GPTCFCreatePartition : 1076 -> 1080
~ _loaderReserve : 512 -> 528
~ _mediaLoaderSupport : 2800 -> 2412
~ _sreqbefore : 196 -> 204
~ _PMSchemeSearchByDescriptor : 112 -> 136
~ _GPTCFUpdateSection : 3320 -> 3328
~ _svalidate : 184 -> 188
~ _GPTWriteMedia : 1728 -> 1772
~ _strncpypad : 128 -> 116
~ _MBRInfoSearchByType : 52 -> 60
~ _PMLookupDESC : 148 -> 172
~ _PMNewPartitionExtended : 1104 -> 1100
~ _delentry : 152 -> 144
~ _MBRWriteMedia : 1056 -> 1036
~ _GPTUpdatePartitionDictionaries : 356 -> 360
~ _GPTReadMedia : 1072 -> 1096
~ _GPTUuid2Typestr : 232 -> 236
~ _GPTCheckPartBootable : 672 -> 684
~ _ReadDosPBR : 812 -> 820
~ _MBRCFRecordMapSection : 628 -> 624
~ _PMPSpecificIndex : 216 -> 224
~ _MBRCFRecordPartitions : 260 -> 264
~ _MKBootDisposition : 1184 -> 1192
~ _APMCodeSearch : 64 -> 60
~ _PMGenPartition : 592 -> 604
~ _strntrim : 120 -> 116
~ _APMCFRecordPartitions : 224 -> 240
~ _APMCategorize : 52 -> 64
~ _APMCFUpdateSection : 2092 -> 2108
~ _PMGuidSearch : 100 -> 112
~ _MKMediaUpdateExtended : 748 -> 736
~ _APMWriteMedia : 3040 -> 3052
~ _APMReadMediaMap : 2416 -> 2440
~ _PMPSearchBlock : 108 -> 112
~ _APMCFRecordSections : 1168 -> 1184
~ _TAO_HFSPlusForkData_HostToBig : 68 -> 72
~ _TAO_HFSPlusExtentRecord_HostToBig : 40 -> 44
~ _IOJobSetup : 2576 -> 2604
~ _ThreadExecutive : 3572 -> 3500
~ _BuildiCache : 260 -> 264
~ _SetupStep : 272 -> 268
~ _IOJobDispose : 332 -> 344
~ _purgeLoader : 796 -> 812
~ _MKScavangeDross : 324 -> 320
~ _MKPurgeLoader : 720 -> 748
~ _PMRemovePartition : 292 -> 296
~ _MKMakePartBootable : 2144 -> 2172
~ _APMDDMGenerate : 484 -> 492
~ _PMSetDriver : 420 -> 424
~ _PMWriteDriver : 384 -> 392
~ _PMAddpatch : 932 -> 936
~ _ApplyToHFSPlusBTreeRecords : 1064 -> 1052
~ _MKRecordEFATFSRuns : 1632 -> 1628
~ _MKFSDescriptorIdentity : 196 -> 192
~ _pwriteoffline : 1432 -> 1436
~ _GPTCategorize : 52 -> 64
~ _GPTSubReadMBR : 856 -> 860
~ _MKHFSPlusMapFileBlock : 220 -> 228
~ _FindFileBlock : 128 -> 132
~ _MKHFSDescriptorIdentity : 104 -> 100
~ _TAO_HFSMasterDirectoryBlock_HostToBig : 388 -> 412
~ _TAO_HFSExtentRecord_HostToBig : 52 -> 60
~ _TAO_HFSCatalogFile_HostToBig : 288 -> 312
~ _TAO_HFSPlusCatalogKey_BigToHost : 88 -> 96
~ _TAO_HFSUniStr255_BigToHost : 72 -> 80
~ _TAO_HFSPlusCatalogKey_HostToBig : 88 -> 96
~ _TAO_HFSUniStr255_HostToBig : 68 -> 76
~ _TAO_HFSPlusCatalogThread_BigToHost : 104 -> 112
~ _TAO_HFSPlusCatalogThread_HostToBig : 104 -> 112
~ _TAO_HFSPlusAttrExtents_HostToBig : 52 -> 56
~ _TAO_HFSPlusAttrRecord_BigToHost : 180 -> 184
~ _TAO_HFSPlusAttrRecord_HostToBig : 176 -> 180
~ _TAO_BTHeaderRec_HostToBig : 152 -> 156
~ _TAOpopenl : 216 -> 212
~ _TAOlaccess2 : 248 -> 256
~ _InfoFillerGetChecksum : 560 -> 568
~ _IOSetParams : 428 -> 432
~ _ISOCodeSearch : 64 -> 60
~ _ISOCategorize : 52 -> 64
~ _ISOCFRecordSections : 924 -> 944
~ _DOSPBR_NtoL : 108 -> 104
~ _WriteDOSExtendedChain : 660 -> 664
~ _MBRCFCreateMapRuns : 388 -> 384
~ _RebuildPatches : 1228 -> 1240
~ _TAOCopyHFSPlusParametersDict : 2176 -> 2168
~ _MKFATFSDescriptorIdentity : 104 -> 100
~ _GrowAllocFile : 728 -> 736
~ _ReadWriteFileToFromBuffer : 1088 -> 1084
~ _LastExtentFinder : 124 -> 128
~ __MKHFSReadWriteFile : 292 -> 320
~ __MKMediaBufferPoolGetBuffer : 192 -> 188
~ _scalenumstr : 144 -> 140
~ _MKBSDMountinfo : 148 -> 168
~ _MKRecordNTFSRuns : 1788 -> 1792
~ _PMSearchBlock : 136 -> 140
~ _VErasePartition : 116 -> 120
~ _FindSTOC : 132 -> 136
```
