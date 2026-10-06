## StreamingZip

> `/System/Library/PrivateFrameworks/StreamingZip.framework/StreamingZip`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x123cc` | `0x12338` | **`-0x94`** |
| `__TEXT.__unwind_info` | `0x2c0` | `0x2c8` | **`+0x8`** |

### Other Changes

```diff

-256.0.0.0.0
+257.0.0.0.0
Functions:
~ ___68+[SZExtractor(KnownImplementations) knownSZExtractorImplementations]_block_invoke : 400 -> 396
~ _ZipStreamAddStatisticsForCDRecord : 460 -> 452
~ _ZipStreamWriteLocalFile : 5972 -> 5916
~ _ZipStreamConcoctFixedStreamData : 280 -> 276
~ _ZipStreamShouldOrderFileEarly : 544 -> 552
~ _ZipStreamWriteCentralDirectoryAndEndRecords : 5208 -> 5204
~ _CreateMutableCDRecord : 788 -> 792
~ __ReadOriginalCentralDirectory : 1620 -> 1580
~ __GetCDIndexOfBundleExecutableForInfoPlist : 1940 -> 1936
~ __WriteLocalFile : 2008 -> 1968
~ _SZArchiverCopyStatsKeys : 184 -> 188
~ _SZArchiverCopyStatsDescriptions : 520 -> 516
```
