## OpenAL

> `/System/Library/Frameworks/OpenAL.framework/OpenAL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x240b0` | `0x240f8` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0xa08` | `0xa00` | **`-0x8`** |

### Other Changes

```diff
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__113__tree_removeB9fqe220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__127__tree_balance_after_insertB9fqe220106IPNS_16__tree_node_baseIPvEEEEvT_S5_
+ __ZNSt3__16__treeINS_12__value_typeIjP9OALSourceEENS_19__map_value_compareIjNS_4pairIKjS3_EENS_4lessIjEEEENS_9allocatorIS8_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS4_PvEE
+ __ZNSt3__16__treeINS_12__value_typeImP16OALCaptureDeviceEENS_19__map_value_compareImNS_4pairIKmS3_EENS_4lessImEEEENS_9allocatorIS8_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS4_PvEE
+ __ZNSt3__16vectorI10BufferInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI16SourceNotifyInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI18SourceAttachedInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__113__tree_removeB9fqe220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__127__tree_balance_after_insertB9fqe220100IPNS_16__tree_node_baseIPvEEEEvT_S5_
- __ZNSt3__16__treeINS_12__value_typeIjP9OALSourceEENS_19__map_value_compareIjNS_4pairIKjS3_EENS_4lessIjEEEENS_9allocatorIS8_EEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeIS4_PvEE
- __ZNSt3__16__treeINS_12__value_typeImP16OALCaptureDeviceEENS_19__map_value_compareImNS_4pairIKmS3_EENS_4lessImEEEENS_9allocatorIS8_EEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeIS4_PvEE
- __ZNSt3__16vectorI10BufferInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI16SourceNotifyInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI18SourceAttachedInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ __ZN9OALBuffer13ReleaseBufferEP9OALSource : 264 -> 276
~ __ZNSt3__16vectorI18SourceAttachedInfoNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJS1_EEEPS1_DpOT_ : 228 -> 224
~ __ZN10OALContextC2EmP9OALDevicePKiRjRd : 792 -> 796
~ __ZN10OALContext15InitializeMixerEj : 856 -> 844
~ __ZN10OALContext9AddSourceEj : 416 -> 412
~ __ZN10OALContext12RemoveSourceEj : 568 -> 564
~ __ZN10OALContext19GetAvailableMonoBusEj : 512 -> 516
~ __ZN10OALContext21GetAvailableStereoBusEj : 492 -> 496
~ __ZNSt3__113__tree_removeB9fqe220100IPNS_16__tree_node_baseIPvEEEEvT_S5_ -> __ZNSt3__113__tree_removeB9fqe220106IPNS_16__tree_node_baseIPvEEEEvT_S5_ : 1060 -> 1056
~ __ZN9OALDevice28GetDesiredRenderChannelCountEv : 680 -> 704
~ __ZN9OALDevice21GetLayoutTagForLayoutEP18AudioChannelLayoutj : 168 -> 180
~ __Z19InitializeBufferMapv : 484 -> 480
~ _alcCaptureOpenDevice : 832 -> 828
~ _alcOpenDevice : 812 -> 808
~ _alcCreateContext : 1188 -> 1160
~ _alcIsExtensionPresent : 592 -> 584
~ _alGenBuffers : 960 -> 952
~ _alDeleteBuffers : 1372 -> 1368
~ _alGenSources : 736 -> 744
~ _alDeleteSources : 708 -> 716
~ _alSourcePlayv : 168 -> 184
~ _alSourcePausev : 168 -> 184
~ _alSourceStopv : 168 -> 184
~ _alSourceRewindv : 168 -> 184
~ _alIsExtensionPresent : 496 -> 488
~ _alcASAGetSource : 672 -> 664
~ __ZN9OALSource10GetQLengthEv : 32 -> 28
~ __ZN9OALSource22RemoveBuffersFromQueueEjPj : 1304 -> 1268
~ __ZN9OALSource26PrepBufferQueueForPlaybackEv : 380 -> 392
~ __ZN9OALSource6RewindEv : 892 -> 916
~ __ZN9OALSource14GetQueueOffsetEj : 1348 -> 1292
~ __ZN9OALSource26GetQueueOffsetSecondsFloatEv : 556 -> 536
~ __ZN9OALSource8DoRenderEP15AudioBufferListj : 2768 -> 2792
~ __ZN9OALSource12DoPostRenderEv : 2168 -> 2192
~ __ZNK2CA17StreamDescription8AsStringEv : 1936 -> 1932
~ __ZNSt3__16vectorI16SourceNotifyInfoNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 268 -> 264
~ __ZNSt3__16vectorI10BufferInfoNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJS1_EEEPS1_DpOT_ : 228 -> 224
~ __ZN16OALCaptureDeviceC2EPKcmjjj : 760 -> 780
~ __ZN16OALCaptureDevice9InputProcEPvPjPK14AudioTimeStampjjP15AudioBufferList : 368 -> 396
~ __ZN15OALCaptureMixerC2EP28OpaqueAudioComponentInstancedjj : 792 -> 812
~ __ZN15OALCaptureMixer13ConverterProcEP20OpaqueAudioConverterPjP15AudioBufferListPP28AudioStreamPacketDescriptionPv : 56 -> 64
~ __ZN12CABufferList15AllocateBuffersEj : 268 -> 272
```
