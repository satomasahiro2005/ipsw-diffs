## PanicProcessingSupport

> `/System/Library/PrivateFrameworks/PanicProcessingSupport.framework/PanicProcessingSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc548` | `0xc578` | **`+0x30`** |

### Other Changes

```diff

-30.0.0.0.0
+31.0.0.0.0
Functions:
~ _pst_decoder : 680 -> 684
~ _decodeExtPaniclog : 624 -> 620
~ -[EmbeddedPanicDataDecoder dumpHexToString:size:] : 204 -> 208
~ -[PanicReport generateLogAtLevel:withBlock:] : 5992 -> 5984
~ sub_28f24dd7c -> sub_290a28d78 : 280 -> 276
~ sub_28f24e39c -> sub_290a29394 : 1412 -> 1436
~ sub_28f24e920 -> sub_290a29930 : 1424 -> 1448
~ sub_28f24f084 -> sub_290a2a0ac : 524 -> 508
~ sub_28f24f3dc -> sub_290a2a3f4 : 384 -> 396
~ sub_28f24fd18 -> sub_290a2ad3c : 80 -> 68
~ sub_28f25013c -> sub_290a2b154 : 1548 -> 1572
```
