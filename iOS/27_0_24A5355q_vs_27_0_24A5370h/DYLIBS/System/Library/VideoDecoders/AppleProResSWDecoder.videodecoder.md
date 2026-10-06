## AppleProResSWDecoder.videodecoder

> `/System/Library/VideoDecoders/AppleProResSWDecoder.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x57a68` | `0x56f70` | **`-0xaf8`** |
| `__TEXT.__unwind_info` | `0x600` | `0x670` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x538` | `0x550` | **`+0x18`** |

### Other Changes

```diff
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorI10DecoderJobNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI13PRRDecoderJobNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI17SliceDecodeParamsNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI20PRRSliceDecodeParamsNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN10Bytestream11MemoryBlockENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN17MemoryBufferCache18MemoryBufferRecordENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIP10__CVBufferNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorI10DecoderJobNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI13PRRDecoderJobNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI17SliceDecodeParamsNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI20PRRSliceDecodeParamsNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN10Bytestream11MemoryBlockENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN17MemoryBufferCache18MemoryBufferRecordENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIP10__CVBufferNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ __ZN27PreFaultedCVPixelBufferPool8fillPoolEPv : 616 -> 608
~ __ZN27PreFaultedCVPixelBufferPool11setCapacityEm : 284 -> 280
~ __ZNSt3__16vectorIP10__CVBufferNS_9allocatorIS2_EEE24__emplace_back_slow_pathIJRKS2_EEEPS2_DpOT_ : 228 -> 224
~ __ZN17MemoryBufferCache18returnMemoryBufferEPh : 140 -> 148
~ __ZNSt3__16vectorIN17MemoryBufferCache18MemoryBufferRecordENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_ : 228 -> 224
~ __ZN15IcpVideoDecoder11decodeFrameEP25OpaqueVTVideoDecoderFrameP20opaqueCMSampleBufferjPj : 1528 -> 1524
~ ____ZN15IcpVideoDecoder11decodeFrameEP25OpaqueVTVideoDecoderFrameP20opaqueCMSampleBufferjPj_block_invoke_2 : 752 -> 748
~ __ZN15IcpVideoDecoder21createPixelBufferPoolEj : 672 -> 668
~ __ZN22CreatePixelFormatArray8functionEPv : 264 -> 248
~ __ZN15PRRVideoDecoder11decodeFrameEP25OpaqueVTVideoDecoderFrameP20opaqueCMSampleBufferjPj : 2224 -> 2232
~ ____ZN15PRRVideoDecoder11decodeFrameEP25OpaqueVTVideoDecoderFrameP20opaqueCMSampleBufferjPj_block_invoke_2 : 1796 -> 1788
~ __ZNSt3__16vectorIN10Bytestream11MemoryBlockENS_9allocatorIS2_EEE24__emplace_back_slow_pathIJS2_EEEPS2_DpOT_ : 228 -> 224
~ __ZN5Frame6Header6decodeERK15SegmentedBuffer : 1968 -> 1960
~ __ZN12FrameDecoder6decodeERK15SegmentedBufferPK11PixelBuffer13DownScaleModebPb : 2420 -> 2416
~ __ZNSt3__16vectorI10DecoderJobNS_9allocatorIS1_EEE6resizeEm : 408 -> 404
~ __ZNSt3__16vectorI17SliceDecodeParamsNS_9allocatorIS1_EEE6resizeEm : 448 -> 468
~ __ZN13DecoderWorker6runJobEP10DecoderJob : 1204 -> 1292
~ __ZN12SliceDecoder6decodeERK17SliceDecodeParams : 3308 -> 3300
~ __ZL7VLD_RLDP15BitstreamReaderPsiiiPKa : 3724 -> 3708
~ __Z17convertY416ToX444PKhiPhiS1_iiibt : 316 -> 324
~ __Z17convertV216ToV210PKhiPhiii : 356 -> 348
~ __ZL14decodeIntAlphaILi8EhLb1EEbP15BitstreamReaderPhjjj : 1912 -> 1932
~ __Z16from_422_to_2vuyILi8ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 408 -> 400
~ __Z16from_422_to_2vuyILi8ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 408 -> 400
~ __Z16from_422_to_2vuyILi8ELi4EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 408 -> 400
~ __Z16from_422_to_2vuyILi8ELi4EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 408 -> 400
~ __Z16from_422_to_2vuyILi4ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 748 -> 708
~ __Z16from_422_to_2vuyILi4ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 748 -> 708
~ __Z16from_422_to_2vuyILi4ELi4EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 748 -> 708
~ __Z16from_422_to_2vuyILi4ELi4EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 748 -> 708
~ __Z16from_422_to_2vuyILi4ELi2EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 720 -> 696
~ __Z16from_422_to_2vuyILi4ELi2EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 720 -> 696
~ __Z16from_422_to_2vuyILi2ELi4EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 680 -> 668
~ __Z16from_422_to_2vuyILi2ELi4EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 680 -> 668
~ __Z16from_422_to_y408ILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 488 -> 492
~ __Z16from_422_to_y408ILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 488 -> 492
~ __Z16from_422_to_y408ILi8ELi4EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 484 -> 488
~ __Z16from_422_to_y408ILi8ELi4EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 484 -> 488
~ __Z16from_422_to_y408ILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 452 -> 428
~ __Z16from_422_to_y408ILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 452 -> 428
~ __Z16from_422_to_y408ILi8ELi4EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 452 -> 428
~ __Z16from_422_to_y408ILi8ELi4EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 452 -> 428
~ __Z16from_422_to_y408ILi4ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 756 -> 720
~ __Z16from_422_to_y408ILi4ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 756 -> 720
~ __Z16from_422_to_y408ILi4ELi4EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 756 -> 720
~ __Z16from_422_to_y408ILi4ELi4EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 756 -> 720
~ __Z16from_422_to_y408ILi4ELi2EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 736 -> 708
~ __Z16from_422_to_y408ILi4ELi2EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 736 -> 708
~ __Z16from_422_to_r408ILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 508 -> 512
~ __Z16from_422_to_r408ILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 508 -> 512
~ __Z16from_422_to_r408ILi8ELi4EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 504 -> 508
~ __Z16from_422_to_r408ILi8ELi4EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 504 -> 508
~ __Z16from_422_to_r408ILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 472 -> 448
~ __Z16from_422_to_r408ILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 472 -> 448
~ __Z16from_422_to_r408ILi8ELi4EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 472 -> 448
~ __Z16from_422_to_r408ILi8ELi4EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 472 -> 448
~ __Z16from_422_to_r408ILi4ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 800 -> 764
~ __Z16from_422_to_r408ILi4ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 800 -> 764
~ __Z16from_422_to_r408ILi4ELi4EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 800 -> 764
~ __Z16from_422_to_r408ILi4ELi4EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 800 -> 764
~ __Z16from_422_to_r408ILi4ELi2EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 780 -> 752
~ __Z16from_422_to_r408ILi4ELi2EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 780 -> 752
~ __Z16from_422_to_v408ILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 564 -> 568
~ __Z16from_422_to_v408ILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 564 -> 568
~ __Z16from_422_to_v408ILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 528 -> 504
~ __Z16from_422_to_v408ILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 528 -> 504
~ __Z25from_422_to_v216_10bits_AILi8ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 816 -> 784
~ __Z25from_422_to_v216_10bits_AILi8ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 816 -> 784
~ __Z25from_422_to_v216_10bits_BILi8ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 816 -> 784
~ __Z25from_422_to_v216_10bits_BILi8ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 816 -> 784
~ __Z23from_422_to_v216_12bitsILi8ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 816 -> 784
~ __Z23from_422_to_v216_12bitsILi8ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 816 -> 784
~ __Z16from_422_to_v216ILi4ELi8EL17AlphaOutputMethod0ELb0EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 500 -> 540
~ __Z16from_422_to_v216ILi4ELi8EL17AlphaOutputMethod0ELb1EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 500 -> 540
~ __Z23from_422_to_y416_10bitsILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 1040 -> 1096
~ __Z23from_422_to_y416_10bitsILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1040 -> 1096
~ __Z23from_422_to_y416_10bitsILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 948 -> 960
~ __Z23from_422_to_y416_10bitsILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 948 -> 960
~ __Z23from_422_to_y416_12bitsILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 1040 -> 1096
~ __Z23from_422_to_y416_12bitsILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1040 -> 1096
~ __Z23from_422_to_y416_12bitsILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 948 -> 960
~ __Z23from_422_to_y416_12bitsILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 948 -> 960
~ __Z16from_422_to_r4flILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 1584 -> 1624
~ __Z16from_422_to_r4flILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1584 -> 1624
~ __Z16from_444_to_2vuyILi8ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 508 -> 516
~ __Z16from_444_to_2vuyILi8ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 508 -> 516
~ __Z16from_444_to_2vuyILi8ELi4EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 508 -> 516
~ __Z16from_444_to_2vuyILi8ELi4EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 508 -> 516
~ __Z16from_444_to_2vuyILi2ELi4EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 840 -> 828
~ __Z16from_444_to_2vuyILi2ELi4EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 840 -> 828
~ __Z16from_444_to_y408ILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 540 -> 560
~ __Z16from_444_to_y408ILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 540 -> 560
~ __Z16from_444_to_y408ILi8ELi4EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 536 -> 556
~ __Z16from_444_to_y408ILi8ELi4EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 536 -> 556
~ __Z16from_444_to_y408ILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 504 -> 496
~ __Z16from_444_to_y408ILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 504 -> 496
~ __Z16from_444_to_y408ILi8ELi4EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 504 -> 496
~ __Z16from_444_to_y408ILi8ELi4EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 504 -> 496
~ __Z16from_444_to_y408ILi4ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 852 -> 824
~ __Z16from_444_to_y408ILi4ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 852 -> 824
~ __Z16from_444_to_y408ILi4ELi4EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 852 -> 824
~ __Z16from_444_to_y408ILi4ELi4EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 852 -> 824
~ __Z16from_444_to_y408ILi4ELi2EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 832 -> 804
~ __Z16from_444_to_y408ILi4ELi2EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 832 -> 804
~ __Z16from_444_to_r408ILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 560 -> 580
~ __Z16from_444_to_r408ILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 560 -> 580
~ __Z16from_444_to_r408ILi8ELi4EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 556 -> 576
~ __Z16from_444_to_r408ILi8ELi4EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 556 -> 576
~ __Z16from_444_to_r408ILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 524 -> 516
~ __Z16from_444_to_r408ILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 524 -> 516
~ __Z16from_444_to_r408ILi8ELi4EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 524 -> 516
~ __Z16from_444_to_r408ILi8ELi4EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 524 -> 516
~ __Z16from_444_to_v408ILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 640 -> 660
~ __Z16from_444_to_v408ILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 640 -> 660
~ __Z16from_444_to_v408ILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 604 -> 596
~ __Z16from_444_to_v408ILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 604 -> 596
~ __Z25from_444_to_v216_10bits_AILi8ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 872 -> 884
~ __Z25from_444_to_v216_10bits_AILi8ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 872 -> 884
~ __Z25from_444_to_v216_10bits_BILi8ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 872 -> 884
~ __Z25from_444_to_v216_10bits_BILi8ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 872 -> 884
~ __Z23from_444_to_v216_12bitsILi8ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 872 -> 884
~ __Z23from_444_to_v216_12bitsILi8ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 872 -> 884
~ __Z16from_444_to_v216ILi4ELi8EL17AlphaOutputMethod0ELb0EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 516 -> 532
~ __Z16from_444_to_v216ILi4ELi8EL17AlphaOutputMethod0ELb1EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 516 -> 532
~ __Z23from_444_to_y416_10bitsILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 1080 -> 1088
~ __Z23from_444_to_y416_10bitsILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1080 -> 1088
~ __Z23from_444_to_y416_10bitsILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 988 -> 972
~ __Z23from_444_to_y416_10bitsILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 988 -> 972
~ __Z23from_444_to_y416_12bitsILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 1080 -> 1088
~ __Z23from_444_to_y416_12bitsILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1080 -> 1088
~ __Z23from_444_to_y416_12bitsILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 988 -> 972
~ __Z23from_444_to_y416_12bitsILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 988 -> 972
~ __Z16from_444_to_r4flILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 1528 -> 1584
~ __Z16from_444_to_r4flILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1528 -> 1584
~ __Z16from_444_to_r4flILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 1476 -> 1492
~ __Z16from_444_to_r4flILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 1476 -> 1492
~ __Z18from_444_to_32ARGBILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 1864 -> 1844
~ __Z18from_444_to_32ARGBILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1864 -> 1844
~ __Z18from_444_to_32ARGBILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 1816 -> 1768
~ __Z18from_444_to_32ARGBILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 1816 -> 1768
~ __Z18from_444_to_32BGRAILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 1864 -> 1844
~ __Z18from_444_to_32BGRAILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1864 -> 1844
~ __Z18from_444_to_32BGRAILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 1816 -> 1768
~ __Z18from_444_to_32BGRAILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 1816 -> 1768
~ __Z16from_444_to_n302ILi8ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 2112 -> 2128
~ __Z16from_444_to_n302ILi8ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 2112 -> 2128
~ __Z16from_444_to_R10kILi8ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 2208 -> 2224
~ __Z16from_444_to_R10kILi8ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 2208 -> 2224
~ __Z16from_444_to_r210ILi8ELi8EL17AlphaOutputMethod0ELb0EEvPhPKsiiPKhji : 2208 -> 2224
~ __Z16from_444_to_r210ILi8ELi8EL17AlphaOutputMethod0ELb1EEvPhPKsiiPKhji : 2208 -> 2224
~ __Z16from_444_to_b64aILi8ELi8EL17AlphaOutputMethod1ELb0EEvPhPKsiiPKhji : 2172 -> 2220
~ __Z16from_444_to_b64aILi8ELi8EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 2172 -> 2220
~ __Z16from_444_to_b64aILi8ELi8EL17AlphaOutputMethod2ELb0EEvPhPKsiiPKhji : 2120 -> 2136
~ __Z16from_444_to_b64aILi8ELi8EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 2120 -> 2136
~ __ZNK11PixelWriter12processMBRowEPKhiS1_iPhiS2_iiiib : 2644 -> 2664
~ __ZL25from_422_to_AYUV_UYVY_WxHIL11PixelFormat846624121EL17AlphaOutputMethod0EEvPhPKsiiPKhjii : 888 -> 884
~ __ZL25from_422_to_y408_r408_4xHILb0EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1096 -> 1028
~ __ZL25from_422_to_AYUV_UYVY_WxHIL11PixelFormat2033463352EL17AlphaOutputMethod1EEvPhPKsiiPKhjii : 1992 -> 1996
~ __ZL25from_422_to_AYUV_UYVY_WxHIL11PixelFormat2033463352EL17AlphaOutputMethod2EEvPhPKsiiPKhjii : 1844 -> 1852
~ __ZL25from_422_to_y408_r408_4xHILb1EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1140 -> 1076
~ __ZL25from_422_to_AYUV_UYVY_WxHIL11PixelFormat1916022840EL17AlphaOutputMethod1EEvPhPKsiiPKhjii : 2032 -> 2040
~ __ZL25from_422_to_AYUV_UYVY_WxHIL11PixelFormat1916022840EL17AlphaOutputMethod2EEvPhPKsiiPKhjii : 1872 -> 1884
~ __ZL20from_422_to_v216_8xHIL11PixelFormat1983000886ELb0EL20PixelOutputStoreType0EEvPhPKsiii : 884 -> 940
~ __ZL20from_422_to_v216_8xHIL11PixelFormat1983000886ELb1EL20PixelOutputStoreType0EEvPhPKsiii : 884 -> 940
~ __ZL20from_422_to_y416_8xHIL11PixelFormat2033463606EL17AlphaOutputMethod1ELb0EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 1172 -> 1064
~ __ZL20from_422_to_y416_8xHIL11PixelFormat2033463606EL17AlphaOutputMethod1ELb1EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 1172 -> 1064
~ __ZL25from_422_to_AYUV_UYVY_WxHIL11PixelFormat2033463606EL17AlphaOutputMethod1EEvPhPKsiiPKhjii : 2544 -> 2444
~ __ZL20from_422_to_y416_8xHIL11PixelFormat2033463606EL17AlphaOutputMethod2ELb0EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 1044 -> 948
~ __ZL20from_422_to_y416_8xHIL11PixelFormat2033463606EL17AlphaOutputMethod2ELb1EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 1044 -> 948
~ __ZL25from_422_to_AYUV_UYVY_WxHIL11PixelFormat2033463606EL17AlphaOutputMethod2EEvPhPKsiiPKhjii : 2284 -> 2276
~ __ZL20from_444_to_2vuy_4xHILb1EEvPhPKsiii : 1208 -> 1140
~ __ZL25from_444_to_AYUV_UYVY_WxHIL11PixelFormat846624121EL17AlphaOutputMethod0EEvPhPKsiiPKhjii : 900 -> 896
~ __ZL25from_444_to_y408_r408_4xHILb0EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1300 -> 1344
~ __ZL25from_444_to_AYUV_UYVY_WxHIL11PixelFormat2033463352EL17AlphaOutputMethod1EEvPhPKsiiPKhjii : 2004 -> 1996
~ __ZL25from_444_to_y408_r408_4xHILb1EL17AlphaOutputMethod1ELb1EEvPhPKsiiPKhji : 1336 -> 1388
~ __ZL25from_444_to_AYUV_UYVY_WxHIL11PixelFormat1916022840EL17AlphaOutputMethod1EEvPhPKsiiPKhjii : 2044 -> 2036
~ __ZL25from_444_to_y408_r408_4xHILb1EL17AlphaOutputMethod2ELb1EEvPhPKsiiPKhji : 1132 -> 1056
~ __ZL20from_444_to_v216_8xHIL11PixelFormat1983000886ELb0EL20PixelOutputStoreType0EEvPhPKsiii : 1088 -> 932
~ __ZL20from_444_to_v216_8xHIL11PixelFormat1983000886ELb1EL20PixelOutputStoreType0EEvPhPKsiii : 1088 -> 932
~ __ZL20from_444_to_y416_8xHIL11PixelFormat2033463606EL17AlphaOutputMethod1ELb0EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 1248 -> 1132
~ __ZL20from_444_to_y416_8xHIL11PixelFormat2033463606EL17AlphaOutputMethod1ELb1EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 1248 -> 1132
~ __ZL25from_444_to_AYUV_UYVY_WxHIL11PixelFormat2033463606EL17AlphaOutputMethod1EEvPhPKsiiPKhjii : 2464 -> 2224
~ __ZL20from_444_to_y416_8xHIL11PixelFormat2033463606EL17AlphaOutputMethod2ELb0EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 1176 -> 1000
~ __ZL20from_444_to_y416_8xHIL11PixelFormat2033463606EL17AlphaOutputMethod2ELb1EL20PixelOutputStoreType0EEvPhPKsiiPKhji : 1176 -> 1000
~ __ZL25from_444_to_AYUV_UYVY_WxHIL11PixelFormat2033463606EL17AlphaOutputMethod2EEvPhPKsiiPKhjii : 2160 -> 2192
~ _scale_horizontal_3to4_2vuy : 1260 -> 1244
~ _scale_horizontal_3to4_v216 : 1320 -> 1292
~ _scale_horizontal_3to4_4444_8b : 1572 -> 1556
~ _scale_horizontal_3to4_4444_16bBE : 1848 -> 1832
~ _scale_horizontal_3to4_4444_16bLE : 1640 -> 1624
~ _scale_horizontal_2to3_2vuy : 1088 -> 1084
~ _scale_horizontal_2to3_v216 : 1136 -> 1120
~ __ZN15PRRSliceDecoder6decodeERK20PRRSliceDecodeParams : 3016 -> 2916
~ __ZL41scanned_coefficients_and_inverse_scanningP15BitstreamReaderPsjjjPKh : 5236 -> 5228
~ __ZN15PRRFrameDecoder6decodeE10BytestreamP14PRRPixelBufferjb : 2504 -> 2460
~ __ZNSt3__16vectorI13PRRDecoderJobNS_9allocatorIS1_EEE6resizeEm : 320 -> 316
~ __Z27from_GbGrBR_to_b16q__scalarPKPhPKtS3_S3_S3_mjS3_S3_ : 408 -> 460
~ __Z28from_GBR_to_bp64_8x8__scalarPKPhPKtS3_S3_S3_mjS3_S3_ : 468 -> 420
~ __Z28from_GBR_to_bp64_4x4__scalarPKPhPKtS3_S3_S3_mjS3_S3_ : 784 -> 696
~ __Z28from_GBR_to_bp64_2x2__scalarPKPhPKtS3_S3_S3_mjS3_S3_ : 416 -> 376
~ __Z27from_GbGrBR_to_bp16__scalarIL10CFAPattern0EEvPKPhPKtS5_S5_S5_mjS5_S5_ : 360 -> 284
~ __Z27from_GbGrBR_to_bp16__scalarIL10CFAPattern1EEvPKPhPKtS5_S5_S5_mjS5_S5_ : 360 -> 284
~ __Z27from_GbGrBR_to_bp16__scalarIL10CFAPattern2EEvPKPhPKtS5_S5_S5_mjS5_S5_ : 360 -> 284
~ __Z27from_GbGrBR_to_bp16__scalarIL10CFAPattern3EEvPKPhPKtS5_S5_S5_mjS5_S5_ : 360 -> 284
```
