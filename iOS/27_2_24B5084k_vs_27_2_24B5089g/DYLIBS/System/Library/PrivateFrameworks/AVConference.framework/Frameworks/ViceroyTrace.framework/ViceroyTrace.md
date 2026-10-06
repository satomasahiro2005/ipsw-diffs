## ViceroyTrace

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ViceroyTrace.framework/ViceroyTrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x179b0` | `0x17870` | **`-0x140`** |
| `__TEXT.__text` | `0xba000` | `0xba098` | **`+0x98`** |
| `__DATA.__objc_ivar` | `0x220c` | `0x21e4` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x4740` | `0x4750` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x93e0` | `0x93f0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1898` | `0x18a0` | **`+0x8`** |

### Other Changes

```diff

-2260.9.1.0.0
+2260.11.1.0.0

-  Functions: 4262
-  Symbols:   6753
+  Functions: 4263
+  Symbols:   6744
Symbols:
+ -[MultiwayStream _closeAltVideoStallEpisode]
+ -[MultiwayStream significantVideoStallCountAlt]
+ GCC_except_table1351
+ _OBJC_IVAR_$_MultiwayStream._significantVideoStallCountAlt
- -[MultiwayStream maxVideoStallCountAlt]
- GCC_except_table1350
- _OBJC_IVAR_$_MultiwayStream._maxVideoStallCountAlt
- _OBJC_IVAR_$_VCAggregatorFaceTime._assembledFramesWithRTXPacketsCount
- _OBJC_IVAR_$_VCAggregatorFaceTime._failedToAssembleFramesWithRTXPacketsCount
- _OBJC_IVAR_$_VCAggregatorFaceTime._isRTXTelemetryAvailable
- _OBJC_IVAR_$_VCAggregatorFaceTime._lateFramesScheduledWithRTXCount
- _OBJC_IVAR_$_VCAggregatorFaceTime._nacksFulfilled
- _OBJC_IVAR_$_VCAggregatorFaceTime._nacksFulfilledOnTime
- _OBJC_IVAR_$_VCAggregatorFaceTime._nacksPLRWithRTX
- _OBJC_IVAR_$_VCAggregatorFaceTime._nacksPLRWithoutRTX
- _OBJC_IVAR_$_VCAggregatorFaceTime._nacksSent
- _OBJC_IVAR_$_VCAggregatorFaceTime._uniqueNacksSent
```
