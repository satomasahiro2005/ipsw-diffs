## AppleProResSWEncoder.videoencoder

> `/System/Library/VideoEncoders/AppleProResSWEncoder.videoencoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20cc4` | `0x21224` | **`+0x560`** |
| `__TEXT.__unwind_info` | `0x250` | `0x258` | **`+0x8`** |

### Other Changes

```diff
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorI10EncoderJobNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorI10EncoderJobNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ __ZN13EncoderWorker6runJobEP10EncoderJob : 1080 -> 1060
~ __ZN7PictureD2Ev : 188 -> 184
~ __ZN7Picture6encodeEP10ThreadPoolI13EncoderWorker10EncoderJobvEPK11PixelBufferR15RateControlInfoRb : 4200 -> 4248
~ __ZN7Picture17instantiateSlicesEi : 296 -> 304
~ __ZN14IcpRateControl13estimateBytesEPiPK5Slicei : 1688 -> 1720
~ __ZN12SliceEncoder6encodeER5Slice : 1640 -> 1684
~ __ZN12SliceEncoder9encodeVlcILb1EEEvR5SlicePKtiiiPi : 928 -> 940
~ __ZN12SliceEncoder9encodeVlcILb0EEEvR5SlicePKtiiiPi : 412 -> 432
~ __ZN12SliceEncoder18runLevelScanAndVlcILb1EEEvRiPjS1_S1_S1_PKtiiPKaR15BitstreamWriterIXT_EE : 5308 -> 5432
~ __ZN12SliceEncoder18runLevelScanAndVlcILb0EEEvRiPjS1_S1_S1_PKtiiPKaR15BitstreamWriterIXT_EE : 2008 -> 1956
~ __Z17convertV210ToV216PKhiPhiii : 468 -> 456
~ __Z11pixInFullMBIL11PixelFormat846624121EL12ChromaFormat2EEvPKhiPsi : 672 -> 700
~ __Z11pixInFullMBIL11PixelFormat2037741171EL12ChromaFormat2EEvPKhiPsi : 672 -> 700
~ __Z11pixInFullMBIL11PixelFormat1916036716EL12ChromaFormat3EEvPKhiPsi : 888 -> 908
~ __Z11pixInFullMBIL11PixelFormat1916036716EL12ChromaFormat2EEvPKhiPsi : 752 -> 768
~ __Z11pixInFullMBIL11PixelFormat32EL12ChromaFormat3EEvPKhiPsi : 1344 -> 1392
~ __Z11pixInFullMBIL11PixelFormat32EL12ChromaFormat2EEvPKhiPsi : 1188 -> 1208
~ __Z11pixInFullMBIL11PixelFormat1647719521EL12ChromaFormat3EEvPKhiPsi : 1424 -> 1472
~ __Z11pixInFullMBIL11PixelFormat1647719542EL12ChromaFormat3EEvPKhiPsi : 1524 -> 1572
~ __Z11pixInFullMBIL11PixelFormat1647719521EL12ChromaFormat2EEvPKhiPsi : 1308 -> 1328
~ __Z11pixInFullMBIL11PixelFormat1647719542EL12ChromaFormat2EEvPKhiPsi : 1412 -> 1432
~ __Z11pixInFullMBIL11PixelFormat1848848434EL12ChromaFormat3EEvPKhiPsi : 1344 -> 1392
~ __Z11pixInFullMBIL11PixelFormat1378955371EL12ChromaFormat3EEvPKhiPsi : 1408 -> 1456
~ __Z11pixInFullMBIL11PixelFormat1915892016EL12ChromaFormat3EEvPKhiPsi : 1408 -> 1456
~ __Z12pixInGenericIL11PixelFormat846624121EL12ChromaFormat2EEvPKhPsiiii : 4796 -> 4680
~ __Z12pixInGenericIL11PixelFormat2037741171EL12ChromaFormat2EEvPKhPsiiii : 4796 -> 4680
~ __Z12pixInGenericIL11PixelFormat1983000886EL12ChromaFormat2EEvPKhPsiiii : 3028 -> 2900
~ __Z12pixInGenericIL11PixelFormat2033463352EL12ChromaFormat2EEvPKhPsiiii : 6116 -> 6144
~ __Z12pixInGenericIL11PixelFormat1916022840EL12ChromaFormat2EEvPKhPsiiii : 2792 -> 2840
~ __Z12pixInGenericIL11PixelFormat1983131704EL12ChromaFormat2EEvPKhPsiiii : 6372 -> 6400
~ __Z12pixInGenericIL11PixelFormat2033463606EL12ChromaFormat2EEvPKhPsiiii : 2872 -> 2920
~ __Z12pixInGenericIL11PixelFormat1916036716EL12ChromaFormat2EEvPKhPsiiii : 2240 -> 2512
~ __Z12pixInGenericIL11PixelFormat32EL12ChromaFormat2EEvPKhPsiiii : 2180 -> 2208
~ __Z12pixInGenericIL11PixelFormat1647719521EL12ChromaFormat2EEvPKhPsiiii : 2228 -> 2256
~ __Z12pixInGenericIL11PixelFormat1647719542EL12ChromaFormat2EEvPKhPsiiii : 2228 -> 2256
~ __Z12pixInGenericIL11PixelFormat2033463352EL12ChromaFormat3EEvPKhPsiiii : 2856 -> 2888
~ __Z12pixInGenericIL11PixelFormat1916022840EL12ChromaFormat3EEvPKhPsiiii : 2904 -> 2936
~ __Z12pixInGenericIL11PixelFormat1983131704EL12ChromaFormat3EEvPKhPsiiii : 2920 -> 2952
~ __Z12pixInGenericIL11PixelFormat2033463606EL12ChromaFormat3EEvPKhPsiiii : 3064 -> 3112
~ __Z12pixInGenericIL11PixelFormat1916036716EL12ChromaFormat3EEvPKhPsiiii : 2240 -> 2512
~ __Z12pixInGenericIL11PixelFormat32EL12ChromaFormat3EEvPKhPsiiii : 2180 -> 2208
~ __Z12pixInGenericIL11PixelFormat1848848434EL12ChromaFormat3EEvPKhPsiiii : 2180 -> 2208
~ __Z12pixInGenericIL11PixelFormat1378955371EL12ChromaFormat3EEvPKhPsiiii : 2180 -> 2208
~ __Z12pixInGenericIL11PixelFormat1915892016EL12ChromaFormat3EEvPKhPsiiii : 2180 -> 2208
~ __Z12pixInGenericIL11PixelFormat1647719521EL12ChromaFormat3EEvPKhPsiiii : 2228 -> 2256
~ __Z12pixInGenericIL11PixelFormat1647719542EL12ChromaFormat3EEvPKhPsiiii : 2228 -> 2256
~ __Z17filterChroma_v408Phiii : 232 -> 244
~ __Z17filterChroma_y416Phiii : 240 -> 236
~ __Z17filterChroma_r4flPhiii : 240 -> 236
```
