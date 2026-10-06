## CBORLibrary

> `/System/Library/PrivateFrameworks/CBORLibrary.framework/CBORLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28794` | `0x28814` | **`+0x80`** |

### Other Changes

```text
Functions:
~ ___51+[CBOR(Encoder) encodeMajorType5:encodingKeyOrder:]_block_invoke : 480 -> 464
~ +[NSData(CBOR) dataWithCBOR:encodingKeyOrder:] : 3592 -> 3580
~ -[CBOR(Decoder) asJSON] : 836 -> 828
~ +[CBOR(Decoder_Private) decodeMajorType0And1FromBuffer:length:tag:] : 956 -> 964
~ -[CBOR initWithType:value:valueSize:tag:] : 716 -> 708
~ -[CBOR date] : 952 -> 948
~ -[CBOR description] : 1280 -> 1276
~ -[COSE _parseCommonHeaderParameters:] : 1480 -> 1476
~ -[COSE_Sign1 x509bag] : 468 -> 464
~ -[COSE_Sign1 x509chain] : 492 -> 488
~ -[COSEKey initWithCBOR:] : 2612 -> 2608
~ -[COSEKey _initCBORWithMemberParams] : 1292 -> 1288
~ sub_24f66c610 -> sub_250d515d0 : 432 -> 428
~ sub_24f66c870 -> sub_250d5182c : 256 -> 264
~ sub_24f66c970 -> sub_250d51934 : 244 -> 252
~ sub_24f66ca64 -> sub_250d51a30 : 244 -> 252
~ sub_24f67011c -> sub_250d550f0 : 1976 -> 2032
~ sub_24f671480 -> sub_250d5648c : 384 -> 392
~ sub_24f672390 -> sub_250d573a4 : 588 -> 592
~ sub_24f6725dc -> sub_250d575f4 : 568 -> 572
~ sub_24f675638 -> sub_250d5a654 : 528 -> 524
~ sub_24f675848 -> sub_250d5a860 : 392 -> 384
~ sub_24f675ed4 -> sub_250d5aee4 : 1420 -> 1444
~ sub_24f6766a8 -> sub_250d5b6d0 : 524 -> 508
~ sub_24f6770c0 -> sub_250d5c0d8 : 784 -> 808
~ sub_24f678208 -> sub_250d5d238 : 3328 -> 3408
```
