## AppleFlatBuffers

> `/System/Library/PrivateFrameworks/AppleFlatBuffers.framework/AppleFlatBuffers`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x122ac` | `0x1222c` | **`-0x80`** |

### Other Changes

```diff
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106ILi0EEEPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIN5apple4aiml12flatbuffers26OffsetINS4_6StringEEEEENS_16allocator_traitsIS8_EEEENS_19__allocation_resultINT0_7pointerENSC_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16__treeIN5apple4aiml12flatbuffers26OffsetINS3_6StringEEENS3_17FlatBufferBuilder19StringOffsetCompareENS_9allocatorIS6_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS6_PvEE
+ __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetINS3_6StringEEENS_9allocatorIS6_EEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220100ILi0EEEPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIN5apple4aiml12flatbuffers26OffsetINS4_6StringEEEEENS_16allocator_traitsIS8_EEEENS_19__allocation_resultINT0_7pointerENSC_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16__treeIN5apple4aiml12flatbuffers26OffsetINS3_6StringEEENS3_17FlatBufferBuilder19StringOffsetCompareENS_9allocatorIS6_EEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeIS6_PvEE
- __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetINS3_6StringEEENS_9allocatorIS6_EEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ -[AFBBufferBuilder createVectorOfBoolWithArray:] : 928 -> 924
~ -[AFBBufferBuilder createVectorOfBoolWithCArray:count:] : 724 -> 716
~ -[AFBBufferBuilder createVectorOfInt8WithArray:] : 924 -> 920
~ -[AFBBufferBuilder createVectorOfInt8WithCArray:count:] : 724 -> 716
~ -[AFBBufferBuilder createVectorOfUInt8WithArray:] : 924 -> 920
~ -[AFBBufferBuilder createVectorOfUInt8WithCArray:count:] : 724 -> 716
~ -[AFBBufferBuilder createVectorOfInt16WithArray:] : 924 -> 920
~ -[AFBBufferBuilder createVectorOfInt16WithCArray:count:] : 724 -> 716
~ -[AFBBufferBuilder createVectorOfUInt16WithArray:] : 924 -> 920
~ -[AFBBufferBuilder createVectorOfUInt16WithCArray:count:] : 724 -> 716
~ -[AFBBufferBuilder createVectorOfInt32WithArray:] : 924 -> 920
~ -[AFBBufferBuilder createVectorOfInt32WithCArray:count:] : 724 -> 716
~ -[AFBBufferBuilder createVectorOfUInt32WithArray:] : 924 -> 920
~ -[AFBBufferBuilder createVectorOfUInt32WithCArray:count:] : 724 -> 716
~ -[AFBBufferBuilder createVectorOfInt64WithArray:] : 924 -> 920
~ -[AFBBufferBuilder createVectorOfInt64WithCArray:count:] : 724 -> 716
~ -[AFBBufferBuilder createVectorOfUInt64WithArray:] : 924 -> 920
~ -[AFBBufferBuilder createVectorOfUInt64WithCArray:count:] : 724 -> 716
~ -[AFBBufferBuilder createVectorOfFloat32WithArray:] : 920 -> 916
~ -[AFBBufferBuilder createVectorOfFloat32WithCArray:count:] : 724 -> 716
~ -[AFBBufferBuilder createVectorOfFloat64WithArray:] : 920 -> 916
~ -[AFBBufferBuilder createVectorOfFloat64WithCArray:count:] : 724 -> 716
~ -[AFBBufferBuilder createVectorOfStringWithArray:alignment:] : 1220 -> 1228
~ -[AFBBufferBuilder createVectorOfStringWithCount:alignment:block:] : 1212 -> 1220
~ -[AFBBufferBuilder createVectorOfStringWithOffsets:] : 1108 -> 1116
~ __ZN5apple4aiml12flatbuffers215vector_downward4fillEm : 88 -> 84
~ __ZN5apple4aiml12flatbuffers217FlatBufferBuilder12CreateVectorINS1_6StringEEENS1_6OffsetINS1_6VectorINS5_IT_EEEEEEPKS8_m : 136 -> 124
~ _AFBIsValidUTF8 : 256 -> 252
```
