## MediaKit

> `/System/Library/PrivateFrameworks/MediaKit.framework/MediaKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ceb4` | `0x2cd0c` | **`-0x1a8`** |
| `__TEXT.__unwind_info` | `0x6c0` | `0x6d0` | **`+0x10`** |

### Other Changes

```text
Functions:
~ _lookupDESC : 200 -> 168
~ _PMSchemeSearch : 76 -> 84
~ _BootAttrSearch : 64 -> 44
~ _srequest : 744 -> 720
~ _GPTRecordMapSection : 764 -> 744
~ _loaderReserve : 528 -> 512
~ _PMSchemeSearchByDescriptor : 136 -> 112
~ _GPTWriteMedia : 1772 -> 1740
~ _PMAccountFreespace : 872 -> 896
~ _MBRInfoSearchByType : 60 -> 52
~ _PMLookupDESC : 172 -> 148
~ _GPTUpdatePartitionDictionaries : 360 -> 356
~ _GPTReadMedia : 1096 -> 1060
~ _GPTUuid2Typestr : 236 -> 252
~ _GPTCheckPartBootable : 684 -> 672
~ _MKBootDisposition : 1192 -> 1180
~ _strntrim : 116 -> 104
~ _APMCFRecordPartitions : 240 -> 224
~ _APMCategorize : 64 -> 52
~ _APMCFUpdateSection : 2108 -> 2092
~ _APMReadMediaMap : 2440 -> 2420
~ _IOJobSetup : 2604 -> 2580
~ _ThreadExecutive : 3500 -> 3520
~ _BuildiCache : 264 -> 260
~ _purgeLoader : 812 -> 808
~ _MKPurgeLoader : 748 -> 732
~ _MKMakePartBootable : 2172 -> 2168
~ _GPTCategorize : 64 -> 52
~ _GPTSubReadMBR : 860 -> 836
~ _MKHFSPlusMapFileBlock : 228 -> 220
~ _FindFileBlock : 132 -> 124
~ _InfoFillerGetChecksum : 568 -> 564
~ _IOCV : 472 -> 480
~ _IOSetParams : 432 -> 428
~ _ISOCategorize : 64 -> 52
~ _ISOCFRecordSections : 944 -> 928
~ _MKBSDMountinfo : 168 -> 148
```
