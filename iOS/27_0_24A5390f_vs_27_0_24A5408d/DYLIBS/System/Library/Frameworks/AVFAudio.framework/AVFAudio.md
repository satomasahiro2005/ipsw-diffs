## AVFAudio

> `/System/Library/Frameworks/AVFAudio.framework/AVFAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x113af0` | `0x113d98` | **`+0x2a8`** |
| `__TEXT.__oslogstring` | `0x180ed` | `0x18210` | **`+0x123`** |
| `__TEXT.__cstring` | `0xfe95` | `0xfe65` | **`-0x30`** |
| `__TEXT.__gcc_except_tab` | `0x12560` | `0x12568` | **`+0x8`** |

### Other Changes

```diff

-794.0.0.0.0
+794.106.0.0.0

-  CStrings:  3368
+  CStrings:  3370
Functions:
~ -[AVVCSessionManager setSessionCategoryModeOptionsForActivationMode:withOptions:] : 3844 -> 3852
~ -[AVVCSessionManager setSessionAudioHWControlFlagsForActivationMode:withOptions:] : 3228 -> 3232
~ -[AVAudioBuffer initWithFormat:byteCapacity:] : 492 -> 588
~ -[AVVCSessionManager setDuckOthers:mixWithOthers:error:] : 1216 -> 1224
~ -[AVAudioBuffer mutableCopyWithZone:] : 212 -> 216
~ -[AVAudioPCMBuffer mutableCopyWithZone:] : 232 -> 236
~ ___68-[AVVoiceTriggerClient enableSpeakerStateListening:completionBlock:]_block_invoke.205 : 364 -> 368
~ __ZN17AVAudioEngineImpl5PauseEPP7NSError : 364 -> 640
~ __ZN17AVAudioEngineImpl4StopEPP7NSError : 592 -> 868
CStrings:
+ "%25s:%-5d AVVCSessionManager::setSessionAudioHWControlFlags: HW control flags will be set implicitly as per MX policy on ATV"
+ "%25s:%-5d Engine@%p: error pausing engine, was running %d, is running %d, error = %d"
+ "%25s:%-5d Engine@%p: error stopping engine, was running %d, is running %d, error = %d"
+ "%25s:%-5d failed to allocate ExtendedAudioBufferList (numBuffers=%d, byteCapacity=%u)"
+ "false == isDeviceIORunning"
- "%25s:%-5d AVVCSessionManager::setSessionAudioHWControlFlags: Take Audio HW control on tvOS"
- "ExtendedAudioBufferList_CreateWithFormat failed"
- "false == AUI().IsRunning()"
```
