## BiomeStorage

> `/System/Library/PrivateFrameworks/BiomeStorage.framework/BiomeStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28eac` | `0x291c4` | **`+0x318`** |
| `__TEXT.__oslogstring` | `0x4340` | `0x43a4` | **`+0x64`** |
| `__TEXT.__objc_methlist` | `0x207c` | `0x208c` | **`+0x10`** |
| `__DATA.__bss` | `0x210` | `0x218` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1338` | `0x1340` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb80` | `0xb88` | **`+0x8`** |

### Other Changes

```diff

-236.0.2.0.0
+239.0.2.0.0

-  Functions: 992
-  Symbols:   1532
-  CStrings:  436
+  Functions: 994
+  Symbols:   1533
+  CStrings:  437
Symbols:
+ -[BMStoreEvent initWithEventBody:eventBodyData:eventBodyDataVersion:timestamp:]
+ GCC_except_table39
+ GCC_except_table69
- GCC_except_table68
- GCC_except_table72
Functions:
~ -[BMFrameStore(V2) enumerateWithOptionsV2:fromOffset:usingBlock:] : 5312 -> 5420
~ -[BMFrameStore(V2) initWithFileHandleV2:permission:] : 2972 -> 3452
~ -[BMSegmentManager orderedSegmentsInDirectory:error:] : 516 -> 512
~ -[BMFrame dataVersion] : 88 -> 84
+ -[BMStoreEvent initWithEventBody:eventBodyData:eventBodyDataVersion:timestamp:]
~ -[BMStoreEvent(Testing) initWithEventBody:timestamp:] : 144 -> 156
~ -[BMStreamDatastore _removeEventsFrom:to:reason:policyID:pruneFutureEvents:shouldDeleteUsingBlock:] : 1124 -> 1120
~ -[BMStreamDatastore pruneStreamToMaxCount:] : 720 -> 716
~ -[BMStreamDatastore(HealthCheck) verifyStreamHealthFromV1:to:frameStore:error:] : 2316 -> 2324
~ -[BMStreamDatastore(HealthCheck) verifyStreamHealthFromV2:to:frameStore:error:] : 2120 -> 2128
+ ___52-[BMFrameStore(V2) initWithFileHandleV2:permission:]_block_invoke.12
~ -[BMSegmentManager pruneSegmentsToMaxSizeInBytes:] : 596 -> 592
~ -[BMSegmentManager pruneSegmentsToMaxAge:] : 568 -> 564
~ -[BMSegmentManager openFiles:saveToOpenFiles:] : 344 -> 340
CStrings:
+ "Attempted to open %{public}@ for writing but the file is already full, remaining space:%ld, fileSize:%zu"
+ "Attempted to open %{public}@ for writing but the file size is: %zu, which lacks space for an offsetTable with %u frames"
+ "Cannot read last offset table entry of %{public}@ at offset %lld (got %zd bytes): %{darwin.errno}d"
- "Attempted to open %{public}@ for writing but the file is already full, remaining space:%d, fileSize:%zu"
- "Attempted to open %{public}@ for writing but the file size is: %zu, which lacks space for an offsetTable with %d frames"
```
