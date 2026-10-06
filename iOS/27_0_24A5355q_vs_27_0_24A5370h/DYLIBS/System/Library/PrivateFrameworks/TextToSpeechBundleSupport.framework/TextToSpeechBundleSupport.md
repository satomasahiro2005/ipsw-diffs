## TextToSpeechBundleSupport

> `/System/Library/PrivateFrameworks/TextToSpeechBundleSupport.framework/TextToSpeechBundleSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cdb4` | `0x1d070` | **`+0x2bc`** |
| `__TEXT.__oslogstring` | `0xbfd` | `0xc37` | **`+0x3a`** |
| `__TEXT.__gcc_except_tab` | `0xa84` | `0xab4` | **`+0x30`** |

### Other Changes

```diff

-713.1.0.0.0
+716.0.0.0.0

-  CStrings:  111
+  CStrings:  112
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__110shared_ptrI22TTSSynthesizerEventBusED2B9fqe220106Ev
+ __ZNSt3__110shared_ptrIN7SiriTTS13VoiceResourceEED1B9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorI13SiriTTSMarkerNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN14TTSSynthesizer13SpeakingStyleENS_9allocatorIS2_EEED2B9fqe220106Ev
+ __ZNSt3__16vectorIN14TTSSynthesizer6MarkerENS_9allocatorIS2_EEED2B9fqe220106Ev
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEED2B9fqe220106Ev
+ __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ _swift_release_x21
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__110shared_ptrI22TTSSynthesizerEventBusED2B9fqe220100Ev
- __ZNSt3__110shared_ptrIN7SiriTTS13VoiceResourceEED1B9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorI13SiriTTSMarkerNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN14TTSSynthesizer13SpeakingStyleENS_9allocatorIS2_EEED2B9fqe220100Ev
- __ZNSt3__16vectorIN14TTSSynthesizer6MarkerENS_9allocatorIS2_EEED2B9fqe220100Ev
- __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEED2B9fqe220100Ev
- __ZNSt3__16vectorIfNS_9allocatorIfEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- _objc_retain_x27
Functions:
~ -[TTSSiriSynthWrapper initWithVoicePath:language:dynamicStylePrompt:censorPlainText:delegate:feResourcePath:] : 2320 -> 2940
~ -[TTSSiriSynthWrapper unloadAllVoiceResources] : 280 -> 276
~ __ZNSt3__16vectorIfNS_9allocatorIfEEE24__emplace_back_slow_pathIJfEEEPfDpOT_ : 232 -> 228
~ __Z4joinINSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEES6_ET_RKNS0_6vectorIT0_NS4_IS9_EEEERKS7_ : 772 -> 764
~ __ZNSt3__110__function6__funcIZZ40-[TTSSiriSynthWrapper synthesizeString:]EUb_E3$_1FiN14TTSSynthesizer15CallbackMessageEEEclEOS4_ : 1720 -> 1732
~ __ZNSt3__16vectorI13SiriTTSMarkerNS_9allocatorIS1_EEE24__emplace_back_slow_pathIJRKS1_EEEPS1_DpOT_ : 228 -> 224
~ sub_2a70834e0 -> sub_2a8ae4744 : 816 -> 856
~ sub_2a708712c -> sub_2a8ae83b8 : 1644 -> 1648
~ sub_2a708bed8 -> sub_2a8aed168 : 1276 -> 1268
~ sub_2a708d1c4 -> sub_2a8aee44c : 480 -> 484
~ sub_2a708d470 -> sub_2a8aee6fc : 280 -> 276
~ sub_2a708e0c4 -> sub_2a8aef34c : 264 -> 268
~ sub_2a708ece8 -> sub_2a8aeff74 : 2752 -> 2772
~ sub_2a7093ea4 -> sub_2a8af5144 : 7016 -> 7036
~ sub_2a7095f64 -> sub_2a8af7218 : 2820 -> 2824
~ sub_2a7099880 -> sub_2a8afab38 : 228 -> 232
CStrings:
+ "Failed to set dynamic prompt on TTSSynthesizer. prompt=%@"
```
