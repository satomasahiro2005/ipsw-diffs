## SMBSearch

> `/System/Library/PrivateFrameworks/SMBSearch.framework/SMBSearch`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21d30` | `0x21ca0` | **`-0x90`** |

### Other Changes

```diff

-  Symbols:   1673
+  Symbols:   1674
Symbols:
+ _objc_release_x11
Functions:
~ -[cdbProp encodeBuffer:BufferOffset:BytesWritten:] : 628 -> 624
~ -[cbaseVariant setStrVectorType:ValueArray:] : 548 -> 544
~ -[cbaseVariant setIntVectorType:ValueArray:] : 432 -> 428
~ -[cbaseVariant setStrArrayType:ValueArray:] : 604 -> 600
~ -[cbaseVariant encodeBuffer:BufferOffset:BytesWritten:] : 1372 -> 1368
~ -[cbaseVariant encodeArray:BufferOffset:BytesWritten:] : 820 -> 816
~ -[cbaseVariant encodeStrArray:BufferOffset:BytesWritten:] : 684 -> 680
~ -[cbaseVariant encodeIntArray:BufferOffset:BytesWritten:] : 1588 -> 1572
~ -[cbaseVariant encodeVector:BufferOffset:BytesWritten:] : 444 -> 440
~ -[cbaseVariant encodeStrVector:BufferOffset:BytesWritten:] : 712 -> 708
~ -[cbaseVariant encodeIntVector:BufferOffset:BytesWritten:] : 1564 -> 1548
~ -[wspHeader decodeBuffer:BufferOffset:BytesDecoded:] : 428 -> 424
~ _dumpBufferMsg : 11072 -> 11160
~ -[wspGetRows encodeBuffer:BufferOffset:BytesWritten:] : 1092 -> 1088
~ -[wspContext logContents] : 1040 -> 1032
~ -[wspQueryIn makeSecondaryCnodeRestriction] : 3616 -> 3552
~ -[wspQueryIn encodePrimaryQuery:BufferOffset:BytesWritten:] : 3312 -> 3300
~ -[wspQueryIn encodeSecondaryQuery:BufferOffset:BytesWritten:] : 3000 -> 2996
~ -[cRowsetProperties encodeBuffer:BufferOffset:BytesWritten:] : 440 -> 436
~ -[wspQueryStatusIn encodeBuffer:BufferOffset:BytesWritten:] : 308 -> 304
~ -[wspQueryStatusExIn encodeBuffer:BufferOffset:BytesWritten:] : 376 -> 372
~ -[wspFreeCursorIn encodeBuffer:BufferOffset:BytesWritten:] : 272 -> 268
~ -[wspDisconnectIn encodeBuffer:BufferOffset:BytesWritten:] : 216 -> 212
~ -[wspPropertySet propertyForPropID:] : 332 -> 328
~ -[wspPropertySet encodeBuffer:BufferOffset:BytesWritten:] : 884 -> 876
~ -[cRestrictionArray encodeBuffer:BufferOffset:BytesWritten:] : 428 -> 424
~ -[cRestriction encodeBuffer:BufferOffset:BytesWritten:] : 360 -> 356
~ -[cNodeRestriction encodeBuffer:BufferOffset:BytesWritten:] : 808 -> 800
~ -[cPropertyRestriction encodeBuffer:BufferOffset:BytesWritten:] : 668 -> 664
~ -[cCoercionRestriction encodeBuffer:BufferOffset:BytesWritten:] : 416 -> 412
~ -[cContentRestriction encodeBuffer:BufferOffset:BytesWritten:] : 724 -> 720
~ -[reuseWhereRestriction encodeBuffer:BufferOffset:BytesWritten:] : 328 -> 324
~ -[wspConnectIn encodeBuffer:BufferOffset:BytesWritten:] : 1752 -> 1748
```
