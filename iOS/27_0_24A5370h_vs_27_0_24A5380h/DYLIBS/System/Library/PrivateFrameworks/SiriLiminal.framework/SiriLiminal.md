## SiriLiminal

> `/System/Library/PrivateFrameworks/SiriLiminal.framework/SiriLiminal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5718c` | `0x56dd4` | **`-0x3b8`** |
| `__AUTH.__objc_data` | `0x460` | `0x2d0` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x410` | `0x5a0` | **`+0x190`** |

### Other Changes

```diff

-3600.70.8.0.0
+3600.70.20.1.1
Functions:
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
~ __ZNKSt3__114default_deleteIN13sentencepiece4util6Status3RepEEclB9fqe220106EPS4_ : 96 -> 108
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
