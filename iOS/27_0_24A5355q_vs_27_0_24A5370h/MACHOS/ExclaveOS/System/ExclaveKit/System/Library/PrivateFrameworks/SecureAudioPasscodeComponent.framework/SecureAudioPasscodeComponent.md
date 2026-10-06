## SecureAudioPasscodeComponent

> `/System/ExclaveKit/System/Library/PrivateFrameworks/SecureAudioPasscodeComponent.framework/SecureAudioPasscodeComponent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb738` | `0xb624` | **`-0x114`** |
| `__TEXT.__cstring` | `0x290a` | `0x2919` | **`+0xf`** |
| `__TEXT.__unwind_info` | `0x488` | `0x490` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-  Functions: 268
-  Symbols:   466
+  Functions: 269
+  Symbols:   467
Symbols:
+ __ZNKSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE4viewB9fqe220106Ev
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt12out_of_rangeC1B9fqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__115allocate_sharedB9fqe220106IN4sapc8exclaves12sharedmemory2v212MappedRegionENS_9allocatorIS5_EEJRP24sharedmemory_segaccess_sRyRmR26sharedmem_permissions_ttagELi0EEENS_10shared_ptrIT_EERKT0_DpOT1_
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9fqe220106Ev
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9fqe220106Ej
+ __ZNSt3__116__pad_and_outputB9fqe220106IcNS_11char_traitsIcEEEENS_19ostreambuf_iteratorIT_T0_EES6_PKS4_S8_S8_RNS_8ios_baseES4_
+ __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106Ev
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220106Ev
+ __ZNSt3__120__shared_ptr_emplaceIN4sapc8exclaves12sharedmemory2v212MappedRegionENS_9allocatorIS5_EEEC2B9fqe220106IJRP24sharedmemory_segaccess_sRyRmR26sharedmem_permissions_ttagES7_Li0EEES7_DpOT_
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__124__put_character_sequenceB9fqe220106IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
+ __ZNSt3__133__allocate_shared_unbounded_arrayB9fqe220106IA_St4byteNS_9allocatorIS2_EEJEEENS_10shared_ptrIT_EERKT0_mDpOT1_
+ __ZNSt3__16vectorI29audiodsputility_parameterid_sNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIPKvNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorISt4byteNS_9allocatorIS1_EEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorISt4byteNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__19allocatorI29audiodsputility_parameterid_sE17allocate_at_leastB9fqe220106Em
+ __ZNSt3__19allocatorIN4sapc8exclaves11ParameterIDEE17allocate_at_leastB9fqe220106Em
+ __ZNSt3__19allocatorIPKvE17allocate_at_leastB9fqe220106Em
+ __ZNSt3__19allocatorIfE17allocate_at_leastB9fqe220106Em
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ _audiodsputility_parameterid__encode
- __ZNKSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE4viewB9fqe220100Ev
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt12out_of_rangeC1B9fqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__115allocate_sharedB9fqe220100IN4sapc8exclaves12sharedmemory2v212MappedRegionENS_9allocatorIS5_EEJRP24sharedmemory_segaccess_sRyRmR26sharedmem_permissions_ttagELi0EEENS_10shared_ptrIT_EERKT0_DpOT1_
- __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEE15__init_buf_ptrsB9fqe220100Ev
- __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9fqe220100Ej
- __ZNSt3__116__pad_and_outputB9fqe220100IcNS_11char_traitsIcEEEENS_19ostreambuf_iteratorIT_T0_EES6_PKS4_S8_S8_RNS_8ios_baseES4_
- __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220100Ev
- __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220100Ev
- __ZNSt3__120__shared_ptr_emplaceIN4sapc8exclaves12sharedmemory2v212MappedRegionENS_9allocatorIS5_EEEC2B9fqe220100IJRP24sharedmemory_segaccess_sRyRmR26sharedmem_permissions_ttagES7_Li0EEES7_DpOT_
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__124__put_character_sequenceB9fqe220100IcNS_11char_traitsIcEEEERNS_13basic_ostreamIT_T0_EES7_PKS4_m
- __ZNSt3__133__allocate_shared_unbounded_arrayB9fqe220100IA_St4byteNS_9allocatorIS2_EEJEEENS_10shared_ptrIT_EERKT0_mDpOT1_
- __ZNSt3__16vectorI29audiodsputility_parameterid_sNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIPKvNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorISt4byteNS_9allocatorIS1_EEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorISt4byteNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__19allocatorI29audiodsputility_parameterid_sE17allocate_at_leastB9fqe220100Em
- __ZNSt3__19allocatorIN4sapc8exclaves11ParameterIDEE17allocate_at_leastB9fqe220100Em
- __ZNSt3__19allocatorIPKvE17allocate_at_leastB9fqe220100Em
- __ZNSt3__19allocatorIfE17allocate_at_leastB9fqe220100Em
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
CStrings:
+ "I32@?0^{secureaudiopasscodecomponent_secureaudiopasscodecomponent__context_s=^^v^^v}8r^{audiodsputility_parameterid_s=Q}16@?<I@?{audiodspprocessor_audiodsp_getparameter__result_s=C(?={audiodsputility_parametererror_s=Q}{audiodsputility_parametervalue_s=Q(?={?={audiodsputility_orientationparametervalue_s=Q}}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=I}{?=B}{?=C}{?=C}{?=B}{?=B}{?=I}{?={audiodsputility_deviceanglecategory_s=Q}}{?={audiodsputility_deviceposecategory_s=Q}}{?=I})})}>24"
+ "I32@?0{audiodspprocessor_audiodsp_getparameter__result_s=C(?={audiodsputility_parametererror_s=Q}{audiodsputility_parametervalue_s=Q(?={?={audiodsputility_orientationparametervalue_s=Q}}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=I}{?=B}{?=C}{?=C}{?=B}{?=B}{?=I}{?={audiodsputility_deviceanglecategory_s=Q}}{?={audiodsputility_deviceposecategory_s=Q}}{?=I})})}8"
+ "I40@?0^{secureaudiopasscodecomponent_secureaudiopasscodecomponent__context_s=^^v^^v}8r^{audiodsputility_parameterid_s=Q}16r^{audiodsputility_parametervalue_s=Q(?={?={audiodsputility_orientationparametervalue_s=Q}}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=I}{?=B}{?=C}{?=C}{?=B}{?=B}{?=I}{?={audiodsputility_deviceanglecategory_s=Q}}{?={audiodsputility_deviceposecategory_s=Q}}{?=I})}24@?<I@?{audiodspprocessor_audiodsp_setparameter__result_s=C(?={audiodsputility_parametererror_s=Q})}>32"
- "I32@?0^{secureaudiopasscodecomponent_secureaudiopasscodecomponent__context_s=^^v^^v}8r^{audiodsputility_parameterid_s=Q}16@?<I@?{audiodspprocessor_audiodsp_getparameter__result_s=C(?={audiodsputility_parametererror_s=Q}{audiodsputility_parametervalue_s=Q(?={?={audiodsputility_orientationparametervalue_s=Q}}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=I}{?=B}{?=C}{?=C}{?=B}{?=B}{?=I}{?={audiodsputility_deviceanglecategory_s=Q}}{?={audiodsputility_deviceposecategory_s=Q}})})}>24"
- "I32@?0{audiodspprocessor_audiodsp_getparameter__result_s=C(?={audiodsputility_parametererror_s=Q}{audiodsputility_parametervalue_s=Q(?={?={audiodsputility_orientationparametervalue_s=Q}}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=I}{?=B}{?=C}{?=C}{?=B}{?=B}{?=I}{?={audiodsputility_deviceanglecategory_s=Q}}{?={audiodsputility_deviceposecategory_s=Q}})})}8"
- "I40@?0^{secureaudiopasscodecomponent_secureaudiopasscodecomponent__context_s=^^v^^v}8r^{audiodsputility_parameterid_s=Q}16r^{audiodsputility_parametervalue_s=Q(?={?={audiodsputility_orientationparametervalue_s=Q}}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=I}{?=B}{?=C}{?=C}{?=B}{?=B}{?=I}{?={audiodsputility_deviceanglecategory_s=Q}}{?={audiodsputility_deviceposecategory_s=Q}})}24@?<I@?{audiodspprocessor_audiodsp_setparameter__result_s=C(?={audiodsputility_parametererror_s=Q})}>32"
```
