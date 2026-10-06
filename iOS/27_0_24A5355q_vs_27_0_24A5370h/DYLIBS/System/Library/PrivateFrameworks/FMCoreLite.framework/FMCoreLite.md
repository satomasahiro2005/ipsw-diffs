## FMCoreLite

> `/System/Library/PrivateFrameworks/FMCoreLite.framework/FMCoreLite`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x119c4` | `0x119b0` | **`-0x14`** |

### Other Changes

```text
Functions:
~ -[NSData(FMCoreAdditions) fm_hexString] : 176 -> 192
~ ___49-[FMConcurrentMutableDictionary removeAllObjects]_block_invoke : 300 -> 296
~ -[FMValueThrottler _notifyObserversOfValueUpdate] : 288 -> 284
~ -[FMCancelationToken callCancelationBlocks:] : 244 -> 240
~ -[FMFuture _flushCompletionBlocks] : 680 -> 676
~ ___71+[FMFuture(FMConveniences) combineAllFutures:ignoringErrors:scheduler:]_block_invoke : 116 -> 112
~ -[NSArray(FMAdditions) fm_map:] : 364 -> 360
~ -[NSArray(FMAdditions) fm_dictionaryWithKeyGenerator:] : 352 -> 348
~ -[NSDictionary(FMAdditions) fm_dictionaryWithLowercaseKeys] : 372 -> 368
~ __FMDictionaryOfMetrics : 420 -> 416
```
