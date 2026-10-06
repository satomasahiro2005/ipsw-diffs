## CallAudioServiceClient

> `/System/Library/PrivateFrameworks/CallAudioServiceClient.framework/CallAudioServiceClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x10c2` | `0x11d0` | **`+0x10e`** |
| `__DATA_CONST.__const` | `0x360` | `0x3f0` | **`+0x90`** |
| `__TEXT.__text` | `0xe674` | `0xe6d8` | **`+0x64`** |
| `__TEXT.__gcc_except_tab` | `0x1348` | `0x1344` | **`-0x4`** |

### Other Changes

```diff

-2750.1.0.0.0
+2756.0.0.0.0

-  Functions: 394
-  Symbols:   875
-  CStrings:  301
+  Functions: 398
+  Symbols:   879
+  CStrings:  323
Symbols:
+ GCC_except_table22
+ __ZN3ims8asStringENS_11DeviceEvent9EventTypeE
+ __ZN3ims8asStringENS_13FlowDirectionE
+ __ZN3ims8asStringENS_15SipVerstatLevelE
+ __ZN3ims8asStringENS_16RegFailureReasonE
+ __ZN3ims8asStringENS_25RegistrationIdentityStateE
+ __ZN3ims8asStringENS_9MediaTypeE
+ __ZNSt12length_errorC1B9sqe220106EPKc
+ __ZNSt12out_of_rangeC1B9sqe220106EPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9sqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_out_of_rangeB9sqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9sqe220106Em
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6appendEPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9sqe220106ILi0EEEPKc
+ __ZNSt3__116__if_likely_elseB9sqe220106IZNS_6vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS5_IS7_EEE12emplace_backIJS7_EEERS7_DpOT_EUlvE_ZNSA_IJS7_EEESB_SE_EUlvE0_EEvbT_T0_
+ __ZNSt3__119__allocate_at_leastB9sqe220106INS_9allocatorINS_12basic_stringIcNS_11char_traitsIcEENS1_IcEEEEEENS_16allocator_traitsIS7_EEEENS_19__allocation_resultINT0_7pointerENSB_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9sqe220106EPKc
+ __ZNSt3__120__throw_out_of_rangeB9sqe220106EPKc
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9sqe220106Ev
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE20__throw_length_errorB9sqe220106Ev
+ __ZNSt3__1eqB9sqe220106IcNS_11char_traitsIcEENS_9allocatorIcEEEEbRKNS_12basic_stringIT_T0_T1_EEPKS6_
+ __ZSt28__throw_bad_array_new_lengthB9sqe220106v
- GCC_except_table13
- __ZN3ims11DeviceEvent12nameForEventENS0_9EventTypeE
- __ZN3ims28RegistrationIdentityStateStrERKNS_25RegistrationIdentityStateE
- __ZNSt12length_errorC1B9sqe220100EPKc
- __ZNSt12out_of_rangeC1B9sqe220100EPKc
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9sqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_out_of_rangeB9sqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9sqe220100Em
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6insertEmPKcm
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9sqe220100ILi0EEEPKc
- __ZNSt3__116__if_likely_elseB9sqe220100IZNS_6vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS5_IS7_EEE12emplace_backIJS7_EEERS7_DpOT_EUlvE_ZNSA_IJS7_EEESB_SE_EUlvE0_EEvbT_T0_
- __ZNSt3__119__allocate_at_leastB9sqe220100INS_9allocatorINS_12basic_stringIcNS_11char_traitsIcEENS1_IcEEEEEENS_16allocator_traitsIS7_EEEENS_19__allocation_resultINT0_7pointerENSB_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9sqe220100EPKc
- __ZNSt3__120__throw_out_of_rangeB9sqe220100EPKc
- __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9sqe220100Ev
- __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE20__throw_length_errorB9sqe220100Ev
- __ZNSt3__1eqB9sqe220100IcNS_11char_traitsIcEENS_9allocatorIcEEEEbRKNS_12basic_stringIT_T0_T1_EEPKS6_
- __ZSt28__throw_bad_array_new_lengthB9sqe220100v
CStrings:
+ "Audio"
+ "Authentication Failed"
+ "Bidirectional"
+ "Call Failure"
+ "Disabled"
+ "DisabledCountry"
+ "Fail"
+ "Limited Access"
+ "Media Request Timed Out"
+ "None"
+ "Normal"
+ "One-way"
+ "Other"
+ "Pass"
+ "Provisioning expired"
+ "Proxy Redirect"
+ "Push URL expired"
+ "Registration Expired"
+ "Service Unavailable"
+ "Sip Error"
+ "Text"
+ "Video"
```
