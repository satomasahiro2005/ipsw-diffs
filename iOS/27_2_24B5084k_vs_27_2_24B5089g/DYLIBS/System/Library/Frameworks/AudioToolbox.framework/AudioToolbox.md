## AudioToolbox

> `/System/Library/Frameworks/AudioToolbox.framework/AudioToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x275e08` | `0x276490` | **`+0x688`** |
| `__TEXT.__oslogstring` | `0x396f4` | `0x398a1` | **`+0x1ad`** |
| `__AUTH_CONST.__cfstring` | `0x6040` | `0x6060` | **`+0x20`** |
| `__TEXT.__cstring` | `0x25758` | `0x2576e` | **`+0x16`** |
| `__DATA_CONST.__got` | `0xde0` | `0xdf0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2327c` | `0x2328c` | **`+0x10`** |

### Other Changes

```diff

-1638.208.0.0.0
+1638.209.1.0.0

-  Symbols:   16470
-  CStrings:  7570
+  Symbols:   16472
+  CStrings:  7576
Symbols:
+ _kLoudnessInfoDictionary_ContentTypeKey
+ _kLoudnessInfoDictionary_LibraryLoudnessKey
Functions:
~ ____ZN20AudioCapturerManager10InitializeEv_block_invoke : 2060 -> 2044
~ __ZNK20AudioCapturerManager11GetFilePathEv : 280 -> 400
~ __ZN14MEMixerChannel28DisconnectReconfigureAddNodeEP11MCAudioUnitRKN2CA17StreamDescriptionERNSt3__16vectorIP15XProcessingBaseNS6_9allocatorIS9_EEEE : 13356 -> 13928
~ __ZN17AQMECaptureInsert12StartCaptureEONSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE8TapPoint : 528 -> 568
~ __ZN18AQOfflineMixerBase16EncoderInputProcEP20OpaqueAudioConverterPjP15AudioBufferListPP28AudioStreamPacketDescriptionPv : 7768 -> 7828
~ __ZN15LoudnessManager11GetSettingsEjP18AQConverterOrCodecjjjjbPiPNS_8SettingsE : 8440 -> 8472
~ __ZN28AudioQueuePropertyMarshaller13GetMarshallerEj : 2908 -> 2924
~ __ZN16AudioQueueObject23SetDecoderChannelLayoutEj : 352 -> 348
~ __ZN16AudioQueueObject19GetProposedIOFormatERKN2CA17StreamDescriptionEb : 3652 -> 3648
~ __ZN16AudioQueueObject19ConverterConnection14BuildConverterERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE : 6800 -> 6792
~ __ZN16AudioQueueObject19ConverterConnection14AdaptToFormatsEv : 5356 -> 5384
~ __ZN16AudioQueueObject17SetLoudnessFromLMEPNS_19ConverterConnectionEPK14__CFDictionary : 13236 -> 13632
~ __ZN16AudioQueueObject11GetPropertyEjR12CASerializer : 4952 -> 5008
~ __ZN16AudioQueueObject11SetPropertyEjR14CADeserializer : 13548 -> 13644
~ __ZN16AudioQueueObject22SetOfflineRenderFormatEPK27AudioStreamBasicDescriptionPK18AudioChannelLayoutP18AQOfflineMixerBase : 1704 -> 1744
~ __ZN20MEDeviceStreamClient24StartStopInternalCaptureEb : 1656 -> 1736
~ __ZN20AudioQueueXPC_Server8NewQueueEb27AudioStreamBasicDescriptionjj : 7676 -> 7724
~ __ZN20AudioQueueXPC_Server13EnqueueBufferEjNSt3__14spanIK26AQBufferCreateDestroyEventLm18446744073709551615EEEjjjNS1_IK28AudioStreamPacketDescriptionLm18446744073709551615EEEjjNS1_IK24AudioQueueParameterEventLm18446744073709551615EEE19XAudioTimeStampBaseb : 6284 -> 6280
~ __ZN20AudioQueueXPC_Server15GetPropertySizeEjj : 1836 -> 1876
~ __ZN20AudioQueueXPC_Server8MixerNewE27AudioStreamBasicDescriptionN2CA13ChannelLayoutE : 3912 -> 3996
CStrings:
+ "%25s:%-5d %.*s@%p %s: no content type found in LID content type dictionary"
+ "%25s:%-5d %.*s@%p %s: offline queue, mLMProcessOfflineQueue is on, continuing"
+ "%25s:%-5d AQOfflineMixer(%p)::RenderPCM: queue 0x%x is connected but has never started and has no scheduled start; ignoring it"
+ "%25s:%-5d Object channel layout detected: setting mLMLoudnessNormalizerUnit channel layout to %s"
+ "%25s:%-5d ObjectMix18 layout detected: setting mLMLoudnessNormalizerUnit channel layout to %s"
+ "%25s:%-5d ObjectMix28 layout detected: setting mLMLoudnessNormalizerUnit channel layout to %s"
+ "com.apple.WebKit.GPU"
- "%25s:%-5d AQOfflineMixer(%p)::RenderPCM: queue 0x%x is connected but has never startedand has no scheduled start; withholding rendering"
```
