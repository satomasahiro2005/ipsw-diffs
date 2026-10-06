## NanoMusicSync

> `/System/Library/PrivateFrameworks/NanoMusicSync.framework/NanoMusicSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4de74` | `0x4e6ac` | **`+0x838`** |
| `__AUTH_CONST.__objc_const` | `0x6968` | `0x6b58` | **`+0x1f0`** |
| `__AUTH.__objc_data` | `0x12e8` | `0x1338` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x4104` | `0x414c` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x1358` | `0x1388` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x9e4` | `0xa10` | **`+0x2c`** |
| `__DATA.__objc_ivar` | `0x458` | `0x480` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x12e0` | `0x1308` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2b80` | `0x2ba0` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x270` | `0x278` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1f8` | `0x200` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2024.100.46.0.0
+2024.100.50.0.0

-  Functions: 1738
-  Symbols:   3135
+  Functions: 1747
+  Symbols:   3161
Symbols:
+ +[NMSPodcastsFetchRequests stationFetchRequestsForStationUUID:downloadedOnly:ctx:]
+ -[NMSStationFetchRequestItemEnumerator .cxx_destruct]
+ -[NMSStationFetchRequestItemEnumerator _getNextItem]
+ -[NMSStationFetchRequestItemEnumerator initWithStationUUID:downloadSettings:downloadedOnly:ctx:]
+ -[NMSStationFetchRequestItemEnumerator nextItem]
+ GCC_except_table2
+ GCC_except_table7
+ _OBJC_CLASS_$_NMSStationFetchRequestItemEnumerator
+ _OBJC_IVAR_$_NMSStationFetchRequestItemEnumerator._ctx
+ _OBJC_IVAR_$_NMSStationFetchRequestItemEnumerator._didLoadSegmentRequests
+ _OBJC_IVAR_$_NMSStationFetchRequestItemEnumerator._downloadSettings
+ _OBJC_IVAR_$_NMSStationFetchRequestItemEnumerator._downloadedOnly
+ _OBJC_IVAR_$_NMSStationFetchRequestItemEnumerator._episodesRemaining
+ _OBJC_IVAR_$_NMSStationFetchRequestItemEnumerator._segmentIndex
+ _OBJC_IVAR_$_NMSStationFetchRequestItemEnumerator._segmentItemIndex
+ _OBJC_IVAR_$_NMSStationFetchRequestItemEnumerator._segmentItems
+ _OBJC_IVAR_$_NMSStationFetchRequestItemEnumerator._segmentRequests
+ _OBJC_IVAR_$_NMSStationFetchRequestItemEnumerator._stationUUID
+ _OBJC_METACLASS_$_NMSStationFetchRequestItemEnumerator
+ __OBJC_$_INSTANCE_METHODS_NMSStationFetchRequestItemEnumerator
+ __OBJC_$_INSTANCE_VARIABLES_NMSStationFetchRequestItemEnumerator
+ __OBJC_CLASS_PROTOCOLS_$_NMSStationFetchRequestItemEnumerator
+ __OBJC_CLASS_RO_$_NMSStationFetchRequestItemEnumerator
+ __OBJC_METACLASS_RO_$_NMSStationFetchRequestItemEnumerator
+ ___48-[NMSStationFetchRequestItemEnumerator nextItem]_block_invoke
+ ___82+[NMSPodcastsFetchRequests stationFetchRequestsForStationUUID:downloadedOnly:ctx:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48s56r_e5_v8?0ls32l8s40l8r56l8s48l8
- GCC_except_table3
```
