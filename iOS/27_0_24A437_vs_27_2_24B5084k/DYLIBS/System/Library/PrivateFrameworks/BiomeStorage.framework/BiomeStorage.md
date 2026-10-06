## BiomeStorage

> `/System/Library/PrivateFrameworks/BiomeStorage.framework/BiomeStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x291c0` | `0x2a1c8` | **`+0x1008`** |
| `__TEXT.__oslogstring` | `0x43a4` | `0x45c7` | **`+0x223`** |
| `__TEXT.__objc_methlist` | `0x208c` | `0x2174` | **`+0xe8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1340` | `0x13f8` | **`+0xb8`** |
| `__DATA_CONST.__const` | `0x728` | `0x780` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0xb88` | `0xbe0` | **`+0x58`** |
| `__TEXT.__cstring` | `0x16e1` | `0x1735` | **`+0x54`** |
| `__AUTH_CONST.__objc_const` | `0x4cf8` | `0x4d28` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x904` | `0x934` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1560` | `0x1580` | **`+0x20`** |
| `__TEXT.__const` | `0x1f8` | `0x1e8` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x2a0` | `0x2a4` | **`+0x4`** |

### Other Changes

```diff

-250.0.0.3.0
+255.0.2.0.0

-  Functions: 994
-  Symbols:   1534
-  CStrings:  438
+  Functions: 1026
+  Symbols:   1563
+  CStrings:  449
Symbols:
+ +[BMFrameStore isTimeTravelStreamOptInRequired]
+ +[BMFrameStore isTimeTravelStreamResetEnabledForConfig:]
+ +[BMFrameStore isTimeTravelStreamResetEnabled]
+ +[BMFrameStore timestampIsUnreachablyInTheFuture:]
+ -[BMFrameStore newestFrameTimestamp]
+ -[BMFrameStore(V2) newestFrameTimestampV2]
+ -[BMSegmentManager _lockfilePath]
+ -[BMSegmentManager _resetSegmentsOnUnrealisticFutureFrameWithGuardedData:]
+ -[BMSegmentManager _resetSegmentsWithGuardedData:]
+ -[BMSegmentManager resetSegmentsOnUnrealisticFutureFrame]
+ -[BMSegmentManager resetSegments]
+ -[BMSegmentManager segmentWithFilename:existingFileHandle:segmentNames:segmentFileHandles:error:]
+ -[BMStoreConfig recoversFromFutureDatedEvents]
+ -[BMStoreConfig setRecoversFromFutureDatedEvents:]
+ -[BMStreamDatastore _resetOnUnrealisticFutureFrame]
+ -[BMStreamDatastore resetOnUnrealisticFutureFrame]
+ -[BMStreamDatastore resetStreamWithReason:]
+ -[BMStreamDatastore resetSubstoreOnUnrealisticFutureFrame]
+ -[BMStreamDatastorePruner resetStreamWithReason:]
+ GCC_except_table26
+ GCC_except_table35
+ GCC_except_table40
+ GCC_except_table50
+ GCC_except_table54
+ GCC_except_table62
+ GCC_except_table63
+ GCC_except_table71
+ GCC_except_table74
+ GCC_except_table75
+ GCC_except_table80
+ GCC_except_table82
+ _OBJC_IVAR_$_BMStoreConfig._recoversFromFutureDatedEvents
+ _OUTLINED_FUNCTION_13
+ ___33-[BMSegmentManager resetSegments]_block_invoke
+ ___33-[BMSegmentManager resetSegments]_block_invoke_2
+ ___57-[BMSegmentManager resetSegmentsOnUnrealisticFutureFrame]_block_invoke
+ ___57-[BMSegmentManager resetSegmentsOnUnrealisticFutureFrame]_block_invoke_2
+ ___block_descriptor_56_e8_32s40s48r_e40_v16?0"BMSegmentManagerProtectedState"8ls32l8s40l8r48l8
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
- GCC_except_table39
- GCC_except_table43
- GCC_except_table49
- GCC_except_table51
- GCC_except_table55
- GCC_except_table59
- GCC_except_table61
- GCC_except_table64
- GCC_except_table73
- GCC_except_table76
CStrings:
+ "%{public}@ was reset because it held frames stamped unreachably in the future; events written before the reset are gone"
+ "%{public}@ was reset by another process; dropping our mapping of its removed segment %{public}@"
+ "BMFrameWriteStatusNonMonotonicTimestamp"
+ "Failed to assign a frameStore after resetting: %{public}@"
+ "Read %zd of %zu bytes of segment header for %{public}@: %{darwin.errno}d"
+ "TimeTravelStreamOptIn"
+ "TimeTravelStreamReset"
+ "Unable to open segment %{public}@ to read its version: %@"
+ "Unable to remove every segment of %{public}@: %@"
+ "_lockfilePath: Assertion Failed: [_path hasPrefix:_config.datastorePath]"
+ "failed to remove every segment of %{public}@; it stays wedged"
+ "not resetting %{public}@: its segments could not be listed: %@"
+ "resetting %{public}@ because it is stamped %f, unreachably in the future"
- "_segmentAfterFrameStore: Assertion Failed: [_path hasPrefix:_config.datastorePath]"
- "lastFrameStoreOrCreateWithTimestamp: Assertion Failed: [_path hasPrefix:_config.datastorePath]"
```
