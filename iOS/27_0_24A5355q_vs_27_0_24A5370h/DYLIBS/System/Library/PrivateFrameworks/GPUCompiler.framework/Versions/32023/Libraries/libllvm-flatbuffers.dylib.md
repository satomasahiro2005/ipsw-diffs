## libllvm-flatbuffers.dylib

> `/System/Library/PrivateFrameworks/GPUCompiler.framework/Versions/32023/Libraries/libllvm-flatbuffers.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d618` | `0x3cd50` | **`-0x8c8`** |
| `__TEXT.__unwind_info` | `0x500` | `0x4f8` | **`-0x8`** |

### Other Changes

```text
Functions:
~ sub_25efd25e0 -> sub_25f07d5e0 : 816 -> 804
~ sub_25efd2ab0 -> sub_25f07daa4 : 1960 -> 1896
~ sub_25efd340c -> sub_25f07e3c0 : 1656 -> 1584
~ __ZN11flatbuffers6Parser11DeserializeEPKN10reflection6SchemaE : 3084 -> 2848
~ __ZN11flatbuffers8FieldDef11DeserializeERNS_6ParserEPKN10reflection5FieldE : 1304 -> 1280
~ __ZN11flatbuffers9StructDef11DeserializeERNS_6ParserEPKN10reflection6ObjectE : 1176 -> 1160
~ __ZN11flatbuffers14DeserializeDocERNSt3__16vectorINS0_12basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEENS5_IS7_EEEEPKNS_6VectorINS_6OffsetINS_6StringEEEEE : 248 -> 240
~ sub_25efd5be0 -> sub_25f080a30 : 888 -> 756
~ __ZN11flatbuffers6Parser15UniqueNamespaceEPNS_9NamespaceE : 484 -> 512
~ __ZN11flatbuffers7EnumDef11DeserializeERNS_6ParserEPKN10reflection4EnumE : 704 -> 688
~ __ZN11flatbuffers7EnumVal11DeserializeERNS_6ParserEPKN10reflection7EnumValE : 484 -> 476
~ __ZN11flatbuffers4Type11DeserializeERKNS_6ParserEPKN10reflection4TypeE : 304 -> 280
~ __ZN11flatbuffers18MakeScreamingCamelERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE : 164 -> 160
~ __ZNK11flatbuffers9Namespace21GetFullyQualifiedNameERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEm : 444 -> 440
~ __ZN11flatbuffers6Parser11ParseHexNumEiPy : 468 -> 472
~ __ZN11flatbuffers6Parser4NextEv : 3052 -> 3072
~ __ZN11flatbuffers6Parser18LookupCreateStructERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEbb : 1020 -> 1024
~ __ZN11flatbuffers6Parser10ParseFieldERNS_9StructDefE : 5820 -> 5840
~ __ZN11flatbuffers6Parser16ParseSingleValueEPKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEERNS_5ValueEb : 5132 -> 5152
~ __ZN11flatbuffers6Parser13ParseAnyValueERNS_5ValueEPNS_8FieldDefEmPKNS_9StructDefEjb : 2372 -> 2380
~ sub_25efdd15c -> sub_25f087f58 : 704 -> 716
~ __ZN11flatbuffers6Parser10ParseTableERKNS_9StructDefEPNSt3__112basic_stringIcNS4_11char_traitsIcEENS4_9allocatorIcEEEEPj : 9656 -> 9552
~ sub_25efdfdcc -> sub_25f08ab6c : 172 -> 168
~ sub_25efdfe78 -> sub_25f08ac14 : 248 -> 244
~ sub_25efdff70 -> sub_25f08ad08 : 248 -> 244
~ sub_25efe0cd0 -> sub_25f08ba64 : 528 -> 520
~ sub_25efe1164 -> sub_25f08bef0 : 312 -> 300
~ __ZN11flatbuffers6Parser21ParseNestedFlatbufferERNS_5ValueEPNS_8FieldDefEmPKNS_9StructDefE : 1276 -> 1272
~ sub_25efe1900 -> sub_25f08c67c : 476 -> 468
~ __ZN11flatbuffers6Parser19ParseEnumFromStringERKNS_4TypeEPNSt3__112basic_stringIcNS4_11char_traitsIcEENS4_9allocatorIcEEEE : 1176 -> 1184
~ sub_25efe2694 -> sub_25f08d410 : 136 -> 148
~ __ZN11flatbuffers6Parser9ParseEnumEbPPNS_7EnumDefE : 4864 -> 4868
~ __ZN11flatbuffers6Parser9ParseDeclEv : 2240 -> 2232
~ __ZN11flatbuffers6Parser7DoParseEPKcPS2_S2_S2_ : 5360 -> 5288
~ __ZNK11flatbuffers9StructDef9SerializeEPNS_17FlatBufferBuilderERKNS_6ParserE : 1440 -> 1420
~ __ZNK11flatbuffers7EnumDef9SerializeEPNS_17FlatBufferBuilderERKNS_6ParserE : 1424 -> 1404
~ sub_25efe89f8 -> sub_25f09370c : 384 -> 380
~ sub_25efe8bb0 -> sub_25f0938c0 : 1168 -> 1164
~ __ZN11flatbuffers10ServiceDef11DeserializeERNS_6ParserEPKN10reflection7ServiceE : 656 -> 644
~ sub_25efe96b0 -> sub_25f0943b0 : 1480 -> 1460
~ sub_25efea584 -> sub_25f095270 : 496 -> 488
~ sub_25efea774 -> sub_25f095458 : 172 -> 168
~ sub_25efeb9b8 -> sub_25f096698 : 1168 -> 1164
~ sub_25efec4a8 -> sub_25f097184 : 1024 -> 936
~ sub_25efec9e4 -> sub_25f097668 : 3992 -> 4020
~ sub_25efedc4c -> sub_25f0988ec : 924 -> 912
~ sub_25efedfe8 -> sub_25f098c7c : 536 -> 488
~ sub_25efee650 -> sub_25f0992b4 : 524 -> 516
~ sub_25efee85c -> sub_25f0994b8 : 528 -> 520
~ sub_25efeea6c -> sub_25f0996c0 : 3516 -> 3608
~ sub_25efefa9c -> sub_25f09a74c : 1028 -> 1024
~ sub_25efefff8 -> sub_25f09aca4 : 640 -> 628
~ sub_25eff03d0 -> sub_25f09b070 : 632 -> 624
~ sub_25eff0794 -> sub_25f09b42c : 2740 -> 2756
~ sub_25eff1248 -> sub_25f09bef0 : 932 -> 928
~ sub_25eff15ec -> sub_25f09c290 : 2740 -> 2756
~ sub_25eff20a0 -> sub_25f09cd54 : 932 -> 928
~ sub_25eff2444 -> sub_25f09d0f4 : 2840 -> 2860
~ sub_25eff30b0 -> sub_25f09dd74 : 772 -> 768
~ sub_25eff36a0 -> sub_25f09e360 : 960 -> 956
~ sub_25eff3f44 -> sub_25f09ec00 : 236 -> 240
~ sub_25eff48f4 -> sub_25f09f5b4 : 252 -> 260
~ sub_25eff49f0 -> sub_25f09f6b8 : 316 -> 312
~ sub_25eff4b2c -> sub_25f09f7f0 : 324 -> 320
~ sub_25eff7a5c -> sub_25f0a271c : 384 -> 380
~ __ZN11flatbuffers12GetAnyValueSEN10reflection8BaseTypeEPKhPKNS0_6SchemaEi : 1648 -> 1504
~ __ZN11flatbuffers10CopyInlineERNS_17FlatBufferBuilderERKN10reflection5FieldERKNS_5TableEmm : 508 -> 496
~ __ZN11flatbuffers9CopyTableERNS_17FlatBufferBuilderERKN10reflection6SchemaERKNS2_6ObjectERKNS_5TableEb : 5532 -> 5288
~ sub_25eff9f94 -> sub_25f0a4ac0 : 780 -> 764
~ __ZN11flatbuffers12VerifyStructERNS_8VerifierERKNS_5TableEtRKN10reflection6ObjectEb : 132 -> 128
~ __ZN11flatbuffers21VerifyVectorOfStructsERNS_8VerifierERKNS_5TableEtRKN10reflection6ObjectEb : 208 -> 204
~ __ZN11flatbuffers11VerifyUnionERNS_8VerifierERKN10reflection6SchemaEyPKhRKNS2_5FieldE : 736 -> 696
~ __ZN11flatbuffers12VerifyObjectERNS_8VerifierERKN10reflection6SchemaERKNS2_6ObjectEPKNS_5TableEb : 2544 -> 2004
~ __ZN11flatbuffers12VerifyVectorERNS_8VerifierERKN10reflection6SchemaERKNS_5TableERKNS2_5FieldE : 3236 -> 3132
~ sub_25effc0b4 -> sub_25f0a691c : 1448 -> 1408
~ __ZN11flatbuffers14StripExtensionERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE : 180 -> 188
~ __ZN11flatbuffers12GetExtensionERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE : 124 -> 140
~ __ZN11flatbuffers9PosixPathEPKc : 144 -> 148
~ __ZN11flatbuffers6Parser11ParseVectorERKNS_4TypeEPjPNS_8FieldDefEm : 4692 -> 4636
~ __ZN11flatbuffers6Parser10ParseArrayERNS_5ValueE : 3332 -> 3292
~ __ZN11flatbuffers6Parser11StartStructERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPPNS_9StructDefE : 272 -> 260
~ __ZN11flatbuffers6Parser9SerializeEv : 5668 -> 5576
~ __ZNK11flatbuffers10ServiceDef9SerializeEPNS_17FlatBufferBuilderERKNS_6ParserE : 1904 -> 1876
~ sub_25f005c5c -> sub_25f0b03d4 : 996 -> 988
~ sub_25f0066a8 -> sub_25f0b0e18 : 768 -> 760
~ sub_25f006cc4 -> sub_25f0b142c : 56 -> 52
~ sub_25f006cfc -> sub_25f0b1460 : 56 -> 52
~ sub_25f00a600 -> sub_25f0b4d60 : 196 -> 184
~ sub_25f00bc4c -> sub_25f0b63a0 : 164 -> 160
~ sub_25f00bcf0 -> sub_25f0b6440 : 192 -> 188
~ sub_25f00bdb0 -> sub_25f0b64fc : 204 -> 200
~ sub_25f00be7c -> sub_25f0b65c4 : 200 -> 196
~ sub_25f00bf44 -> sub_25f0b6688 : 172 -> 168
~ sub_25f00bff0 -> sub_25f0b6730 : 164 -> 160
~ sub_25f00c094 -> sub_25f0b67d0 : 164 -> 160
~ sub_25f00f034 -> sub_25f0b976c : 260 -> 256
~ sub_25f00f3b0 -> sub_25f0b9ae4 : 224 -> 228
```
