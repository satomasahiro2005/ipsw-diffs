## EmbeddingCore

> `/System/Library/PrivateFrameworks/EmbeddingCore.framework/EmbeddingCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xc70` | `0x50` | **`-0xc20`** |
| `__DATA_DIRTY.__objc_data` | `0x6e0` | `0x1300` | **`+0xc20`** |
| `__TEXT.__text` | `0x6ce28` | `0x6ca30` | **`-0x3f8`** |
| `__DATA_DIRTY.__data` | `0x90` | `0x138` | **`+0xa8`** |
| `__AUTH.__data` | `0x180` | `0xe0` | **`-0xa0`** |
| `__DATA_DIRTY.__bss` | `0x60` | `0xe0` | **`+0x80`** |
| `__DATA.__bss` | `0x231` | `0x1c1` | **`-0x70`** |
| `__DATA.__common` | `0x325` | `0x2fd` | **`-0x28`** |
| `__DATA_DIRTY.__common` | `0xc8` | `0xf0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x3c0` | `0x3d0` | **`+0x10`** |
| `__DATA.__data` | `0x2dc` | `0x2d4` | **`-0x8`** |

### Other Changes

```diff

-435.65.2.0.0
+435.69.2.0.0
Functions:
~ -[MADTextEncoderE5ML getTokenEmbeddingsforChunks:truncatedInput:error:] : 1108 -> 1080
~ -[MADTextEncoderE5ML _unsafeRunOnInput:completion:] : 8228 -> 8212
~ __ZNSt3__15dequeIZNK5Darts15DoubleArrayImplIvvivE16predictiveSearchINS3_16result_pair_typeEEEmPKcPT_mmiE5StateNS_9allocatorISA_EEE19__add_back_capacityEv : 484 -> 472
~ __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqe220106EPKvm : 532 -> 520
~ __ZN13sentencepiece22SentencePieceProcessor4LoadENSt3__110unique_ptrINS_10ModelProtoENS1_14default_deleteIS3_EEEE : 2316 -> 2304
~ __ZNK13sentencepiece22SentencePieceProcessor17ParseExtraOptionsENSt3__117basic_string_viewIcNS1_11char_traitsIcEEEEPNS1_6vectorINS0_11ExtraOptionENS1_9allocatorIS7_EEEE : 2160 -> 2132
~ __ZNK13sentencepiece22SentencePieceProcessor17ApplyExtraOptionsERKNSt3__16vectorINS0_11ExtraOptionENS1_9allocatorIS3_EEEEPNS_17SentencePieceTextE : 1480 -> 1472
~ __ZN13sentencepiece7unigram7Lattice7ViterbiEv : 732 -> 720
~ __ZN13sentencepiece7unigram7Lattice6SampleEf : 996 -> 980
~ __ZNK13sentencepiece7unigram5Model15EncodeOptimizedENSt3__117basic_string_viewIcNS2_11char_traitsIcEEEE : 1232 -> 1236
~ __ZNK13sentencepiece7unigram5Model20SampleEncodeAndScoreENSt3__117basic_string_viewIcNS2_11char_traitsIcEEEEfibb : 3012 -> 3004
~ __ZNK13sentencepiece4word5Model6EncodeENSt3__117basic_string_viewIcNS2_11char_traitsIcEEEE : 380 -> 356
~ __ZNK13sentencepiece31SentencePieceText_SentencePiece18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 708 -> 684
~ __ZN6google8protobuf2io19EpsCopyOutputStream23WriteStringMaybeAliasedEjRKNSt3__112basic_stringIcNS3_11char_traitsIcEENS3_9allocatorIcEEEEPh : 304 -> 292
~ __ZNK13sentencepiece17SentencePieceText18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 500 -> 492
~ __ZNK13sentencepiece22NBestSentencePieceText18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 368 -> 360
~ __ZNK13sentencepiece11TrainerSpec18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 4612 -> 4484
~ __ZNK13sentencepiece12SelfTestData18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 396 -> 388
~ __ZNK13sentencepiece24ModelProto_SentencePiece18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 432 -> 424
~ __ZNK13sentencepiece10ModelProto18_InternalSerializeEPhPN6google8protobuf2io19EpsCopyOutputStreamE : 1040 -> 1000
~ __ZNKSt3__114default_deleteIN13sentencepiece4util6Status3RepEEclB9fqe220106EPS4_ : 116 -> 108
~ __ZN6google8protobuf2io19EpsCopyOutputStream30WriteStringMaybeAliasedOutlineEjRKNSt3__112basic_stringIcNS3_11char_traitsIcEENS3_9allocatorIcEEEEPh : 396 -> 388
~ __ZN6google8protobuf2io19EpsCopyOutputStream18WriteStringOutlineEjRKNSt3__112basic_stringIcNS3_11char_traitsIcEENS3_9allocatorIcEEEEPh : 436 -> 428
~ __ZNK6google8protobuf8internal12ExtensionSet13IsInitializedEv : 212 -> 208
~ __ZNK6google8protobuf8internal12ExtensionSet9Extension44InternalSerializeFieldWithCachedSizesToArrayEiPhPNS0_2io19EpsCopyOutputStreamE : 11144 -> 10532
~ __ZN6google8protobuf8internal12ShutdownDataD2Ev : 164 -> 168
~ __ZN6google8protobuf8internal18EpsCopyInputStream10NextBufferEii : 1064 -> 1068
~ __ZN6google8protobuf8internal17VarintParseSlow32EPKcj : 104 -> 116
~ __ZN6google8protobuf8internal16WireFormatParserINS1_28UnknownFieldLiteParserHelperEEEPKcRT_S5_PNS1_12ParseContextE : 248 -> 252
~ __ZN6google8protobuf8internal11VarintParseIyEEPKcS4_PT_ : 124 -> 128
~ __ZN6google8protobuf8internal16ReadSizeFallbackEPKcj : 120 -> 124
```
