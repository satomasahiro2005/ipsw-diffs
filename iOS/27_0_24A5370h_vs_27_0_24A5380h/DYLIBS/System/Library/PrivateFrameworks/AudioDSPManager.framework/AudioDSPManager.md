## AudioDSPManager

> `/System/Library/PrivateFrameworks/AudioDSPManager.framework/AudioDSPManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__bss` | `0x1e70` | `0x23a0` | **`+0x530`** |
| `__DATA.__bss` | `0x8280` | `0x7d60` | **`-0x520`** |
| `__AUTH.__objc_data` | `0x698` | `0x410` | **`-0x288`** |
| `__DATA_DIRTY.__objc_data` | `0x5a8` | `0x830` | **`+0x288`** |
| `__DATA_DIRTY.__data` | `0xf90` | `0x1118` | **`+0x188`** |
| `__TEXT.__text` | `0xbbd50` | `0xbbe2c` | **`+0xdc`** |
| `__AUTH.__data` | `0x5d0` | `0x4f8` | **`-0xd8`** |
| `__DATA.__data` | `0x1550` | `0x14a0` | **`-0xb0`** |
| `__TEXT.__const` | `0xe9a8` | `0xe9c8` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x3968` | `0x3982` | **`+0x1a`** |
| `__TEXT.__cstring` | `0x60e4` | `0x60ee` | **`+0xa`** |
| `__DATA.__common` | `0x38` | `0x30` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x58` | `0x60` | **`+0x8`** |

### Other Changes

```diff

-241.103.0.0.0
+241.105.0.0.0

-  CStrings:  1195
+  CStrings:  1196
Functions:
~ __ZN3adm8exclaves9tightbeam10convert_toINSt3__18optionalINS1_11ParameterIDEEEjJEEET_T0_DpT1_ : 632 -> 688
~ __ZN3adm8exclaves9tightbeam19AudioDSPControlImpl12getParameterENS1_11ParameterIDE : 3704 -> 3780
~ __ZN3adm8exclaves9tightbeam13tb_convert_asI29audiodsputility_parameterid_sNS1_11ParameterIDEJEEENSt3__18optionalIT_EET0_DpT1_ : 56 -> 172
~ _audiodsputility_parameterid__raw_encode : 664 -> 712
~ sub_224b53df0 -> sub_229419f18 : 72 -> 80
~ __ZNKSt3__111__copy_implclB9fqe220106IPN3adm26DSPGraphBasicConfiguration22AUPresetOverrideConfigES5_S5_Li0EEENS_4pairIT_T1_EES7_T0_S8_ : 112 -> 108
~ __ZNSt3__16vectorIN3adm25HardwareStreamDescriptionENS_9allocatorIS2_EEE16__destroy_vectorclB9fqe220106Ev : 128 -> 116
~ __ZN3adm5graph14DSPGraphKernel9configureEv : 11180 -> 11196
~ __ZNSt3__111__formatter32__write_using_decimal_separatorsB9fqe220106INS_20back_insert_iteratorINS_8__format15__output_bufferIcEEEEPccEET_S8_T0_S9_S9_ONS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEET1_NS_13__format_spec23__parsed_specificationsISH_EE : 468 -> 464
~ __ZNSt3__111__formatter29__format_locale_specific_formB9fqe220106INS_20back_insert_iteratorINS_8__format15__output_bufferIcEEEEdcEET_S7_RKNS0_14__float_bufferIT0_EERKNS0_14__float_resultENS_6localeENS_13__format_spec23__parsed_specificationsIT1_EE : 1108 -> 1104
~ __ZNSt3__16vectorIN2CA22AudioBuffersDeprecatedENS_9allocatorIS2_EEE16__destroy_vectorclB9fqe220106Ev : 128 -> 116
~ __ZNK3adm5graph19KernelConfigurationeqERKS1_ : 780 -> 768
~ __ZNSt3__16vectorIN10applesauce2CF11TypeRefPairENS_9allocatorIS3_EEE16__destroy_vectorclB9fqe220106Ev : 128 -> 116
~ __ZNSt3__134__uninitialized_allocator_relocateB9fqe220106INS_9allocatorIN3adm5graph19TerminalDescriptionEEEPS4_EEvRT_T0_S9_S9_ : 236 -> 216
~ __ZNKSt3__113__string_hashIcNS_9allocatorIcEEEclB9fqe220106ERKNS_12basic_stringIcNS_11char_traitsIcEES2_EE : 1092 -> 1080
~ __ZN8nlohmann10basic_jsonINSt3__13mapENS1_6vectorENS1_12basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEbxydS7_NS_14adl_serializerENS3_IhNS7_IhEEEEEC2ESt16initializer_listINS_6detail8json_refISD_EEEbNSF_7value_tE : 856 -> 840
~ __ZN3adm5grapheqERKNS0_27DSPGraphKernelConfigurationES3_ : 260 -> 244
~ __ZNSt3__16vectorINS_5tupleIJjNS_8functionIFvjEEEEEENS_9allocatorIS5_EEE24__emplace_back_slow_pathIJRjS4_EEEPS5_DpOT_ : 408 -> 360
~ __ZNSt3__16vectorINS_5tupleIJjNS_8functionIFvjRKN4AMCP15Proc_Cycle_InfoEmPNS3_11Proc_StreamEmS8_EEEEEENS_9allocatorISB_EEE24__emplace_back_slow_pathIJRjSA_EEEPSB_DpOT_ : 408 -> 360
~ __ZN3adm5graph11NodeManager10createNodeERKNS0_15NodeDescriptionERKNSt3__16vectorINS0_19TerminalDescriptionENS5_9allocatorIS7_EEEERKNS_2vp13ConfigurationE : 784 -> 792
~ __ZN3adm5graph11NodeManager10createNodeERKNS0_15NodeDescriptionERKNSt3__16vectorINS0_19TerminalDescriptionENS5_9allocatorIS7_EEEERKNS0_24ExclaveNodeConfigurationE : 5172 -> 5260
~ __ZN3adm8exclaves9tightbeam19AudioDSPControlImpl12setParameterENS1_11ParameterIDEf : 3800 -> 3940
~ __ZNK3adm2vp26ImmutableNodeConfigurationINS0_21DownlinkConfigurationEE3hasINS0_25DownlinkNodeConfiguration9InputTypeEEEbT_ : 100 -> 88
~ __ZNK3adm2vp26ImmutableNodeConfigurationINS0_19UplinkConfigurationEE3hasINS0_23UplinkNodeConfiguration10OutputTypeEEEbT_ : 100 -> 88
~ __ZNK3adm2vp26ImmutableNodeConfigurationINS0_21DownlinkConfigurationEE3hasINS0_25DownlinkNodeConfiguration10OutputTypeEEEbT_ : 104 -> 88
~ sub_224bd96e0 -> sub_22949f808 : 864 -> 848
~ sub_224bdc0d0 -> sub_2294a21e8 : 632 -> 612
~ sub_224bdc348 -> sub_2294a244c : 792 -> 772
~ sub_224bdc660 -> sub_2294a2750 : 652 -> 632
CStrings:
+ "unhandled ParameterID: %u"
+ "v32@?0{audiodspcontroller_audiodspcontrol_getparameter__result_s=C(?={audiodsputility_parametererror_s=Q}{audiodsputility_parametervalue_s=Q(?={?={audiodsputility_orientationparametervalue_s=Q}}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=I}{?=B}{?=C}{?=C}{?=B}{?=B}{?=I}{?={audiodsputility_deviceanglecategory_s=Q}}{?={audiodsputility_deviceposecategory_s=Q}}{?=I}{?=B}{?=B})})}8"
- "v32@?0{audiodspcontroller_audiodspcontrol_getparameter__result_s=C(?={audiodsputility_parametererror_s=Q}{audiodsputility_parametervalue_s=Q(?={?={audiodsputility_orientationparametervalue_s=Q}}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=B}{?=I}{?=B}{?=C}{?=C}{?=B}{?=B}{?=I}{?={audiodsputility_deviceanglecategory_s=Q}}{?={audiodsputility_deviceposecategory_s=Q}}{?=I})})}8"
```
