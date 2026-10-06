## SoundAnalysis

> `/System/Library/Frameworks/SoundAnalysis.framework/SoundAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34d26c` | `0x357738` | **`+0xa4cc`** |
| `__DATA.__bss` | `0x62b40` | `0x61ee0` | **`-0xc60`** |
| `__AUTH_CONST.__const` | `0x2d800` | `0x2df58` | **`+0x758`** |
| `__TEXT.__const` | `0x429e0` | `0x42440` | **`-0x5a0`** |
| `__TEXT.__eh_frame` | `0x276e8` | `0x27b30` | **`+0x448`** |
| `__TEXT.__cstring` | `0xf655` | `0xfa79` | **`+0x424`** |
| `__TEXT.__swift5_capture` | `0x59b0` | `0x5d40` | **`+0x390`** |
| `__DATA_DIRTY.__data` | `0x8d68` | `0x8b28` | **`-0x240`** |
| `__TEXT.__constg_swiftt` | `0x10038` | `0xfe64` | **`-0x1d4`** |
| `__AUTH_CONST.__objc_const` | `0x11a50` | `0x11c08` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x3e1e` | `0x3f4e` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x13e98` | `0x13fa8` | **`+0x110`** |
| `__DATA_DIRTY.__bss` | `0x2f90` | `0x2e90` | **`-0x100`** |
| `__TEXT.__swift5_typeref` | `0x1a7df` | `0x1a8df` | **`+0x100`** |
| `__DATA.__data` | `0xdfa0` | `0xe060` | **`+0xc0`** |
| `__TEXT.__swift5_assocty` | `0x1f60` | `0x1ec8` | **`-0x98`** |
| `__AUTH.__data` | `0x2c28` | `0x2cb8` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x414c` | `0x41dc` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0xd678` | `0xd5ec` | **`-0x8c`** |
| `__TEXT.__swift5_reflstr` | `0x8a12` | `0x8992` | **`-0x80`** |
| `__TEXT.__swift5_proto` | `0x39f0` | `0x3988` | **`-0x68`** |
| `__TEXT.__swift5_builtin` | `0x4d8` | `0x500` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x2648` | `0x2668` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xf70` | `0xf80` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x13f0` | `0x13e0` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x938` | `0x940` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b90` | `0x1b88` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x100` | `0xfc` | **`-0x4`** |
| `__TEXT.__swift5_protos` | `0x1f8` | `0x1f4` | **`-0x4`** |

### Other Changes

```diff

-500.195.0.0.0
+510.13.0.0.0

-  Functions: 28618
-  Symbols:   929
-  CStrings:  1653
+  Functions: 28681
+  Symbols:   925
+  CStrings:  1675
Symbols:
+ __swift_stdlib_strtof_clocale
- _CFDictionaryGetValueIfPresent
- _CFGetTypeID
- _CFNumberGetTypeID
- _CFNumberGetValue
- _swift_dynamicCastUnknownClassUnconditional
CStrings:
+ " has no E5RT encoder"
+ " must be a positive multiple of chunk "
+ " selectKey stages"
+ "' not recognized"
+ "' produced empty output"
+ "' recipe expected exactly 1 assignKey and 1 selectKey, "
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks/AudioToolboxCore.framework/PrivateHeaders/DSPGraph_Box.h"
+ "AudioCapturerCreateForPCMAudioData"
+ "AudioCapturerFilePath"
+ "AudioCapturerFlush"
+ "AudioCapturerWriteBufferList"
+ "AudioCapturer_t *SNAudioCapturerCreateForPCMAudioData(AudioCaptureOptions, const char *, const char *, AudioFileTypeID, const char * _Nullable, const AudioStreamBasicDescription * _Nullable, const AudioStreamBasicDescription *)"
+ "Could not read detector head metadata, missing or unparsable key "
+ "Created audioCapturer filePath="
+ "Detector head base model '"
+ "Detector head declares no base model; assuming micro2sStreamifiedNoProjection"
+ "Detector head expected exactly 1 non-state input, found "
+ "Detector head missing state input geometry"
+ "Detector head recipe missing streaming chunk/cache geometry"
+ "Dumping ring buffer"
+ "E5RT detector head '"
+ "Encoder recipe missing slice stage"
+ "Failed to create audio capture: %s"
+ "Initialized audio capture"
+ "Initialized µCLAP detector head '%s' (CoreML) with activation threshold: %f, version: %s, base model: %s"
+ "Initialized µCLAP detector head '%s' (E5RT) with activation threshold: %f, version: %s, base model: %s"
+ "Invalid detector head geometry: cache "
+ "Invalid result count: "
+ "SNULanguageAlignedDetectorHeadAXBabyCryModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXBeepModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXBuzzerModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXCarHornModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXCatMeowModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXCoughModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXDingBellModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXDogBarkModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXDoorKnockModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXDoorbellModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXFireAlarmModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXGlassBreakModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXKettleWhistlingModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXShoutModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXSirenModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXSmokeAlarmModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadAXWaterRunningModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadBabbleModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadIntelligibleSpeechModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadMusicModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadSpeechModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadWaterArtifactModel.snmodelc"
+ "SNULanguageAlignedDetectorHeadWindArtifactModel.snmodelc"
+ "SNULanguageAlignedStreamifiedEncoderModel.snmodelc"
+ "SNUSoundPrintHomeModel.snmodelc"
+ "Unsupported metadata value type"
+ "[PIPELINE] Loaded E5RT context for asset: %s (cache miss)"
+ "[PUB] shared CLAP embedding CoreML "
+ "[PUB] shared CLAP embedding E5RT "
+ "[PUB] shared uSP smoke alarm / window glass breaking "
+ "[PUB] uSP smoke alarm / window glass breaking model "
+ "[PUB] uSP smoke alarm / window glass breaking model (%s) %s: %s"
+ "[SNAudioCapturer] Failed to create audio capturer"
+ "[SNAudioCapturer] Failed to dump ring buffer"
+ "[SNAudioCapturer] Failed to write audio buffer list"
+ "[SNAudioCapturer] Failed to write audio capture: %s"
+ "bool SNAudioCapturerFlush(AudioCapturer_t *)"
+ "bool SNAudioCapturerWriteBufferList(AudioCapturer_t *, const AudioBufferList *, uint32_t, int64_t, const AudioCaptureTrace * _Nullable)"
+ "const char * _Nullable SNAudioCapturerFilePath(AudioCapturer_t *)"
+ "micro2sStreamifiedNoProjection uses E5RT, not CoreML featurePrint"
+ "streaming_cache_size"
+ "streaming_chunk_size"
+ "uLanguageAlignedBabbleDetectorE5RT"
+ "uLanguageAlignedBabyCryAXDetectorE5RT"
+ "uLanguageAlignedBeepAXDetectorE5RT"
+ "uLanguageAlignedBuzzerAXDetectorE5RT"
+ "uLanguageAlignedCarHornAXDetectorE5RT"
+ "uLanguageAlignedCatMeowAXDetectorE5RT"
+ "uLanguageAlignedCoughAXDetectorE5RT"
+ "uLanguageAlignedDingBellAXDetectorE5RT"
+ "uLanguageAlignedDogBarkAXDetectorE5RT"
+ "uLanguageAlignedDoorKnockAXDetectorE5RT"
+ "uLanguageAlignedDoorbellAXDetectorE5RT"
+ "uLanguageAlignedFireAlarmAXDetectorE5RT"
+ "uLanguageAlignedGlassBreakAXDetectorE5RT"
+ "uLanguageAlignedIntelligibleSpeechDetectorE5RT"
+ "uLanguageAlignedKettleWhistlingAXDetectorE5RT"
+ "uLanguageAlignedMusicDetectorE5RT"
+ "uLanguageAlignedShoutAXDetectorE5RT"
+ "uLanguageAlignedSirenAXDetectorE5RT"
+ "uLanguageAlignedSmokeAlarmAXDetectorE5RT"
+ "uLanguageAlignedSpeechDetectorE5RT"
+ "uLanguageAlignedStreamifiedEncoderE5RT"
+ "uLanguageAlignedWaterArtifactDetectorE5RT"
+ "uLanguageAlignedWaterRunningAXDetectorE5RT"
+ "uLanguageAlignedWindArtifactDetectorE5RT"
+ "uSP smoke alarm / window glass breaking model pipeline "
+ "useUSoundPrintSmokeAlarmInHome"
- ") must be a multiple of base model temporal dimension ("
- ", but baseModel is "
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks/AudioToolboxCore.framework/PrivateHeaders/DSPGraph_Box.h"
- "Base model embedding temporal dimension must be > 0"
- "Could not infer receptive field length from model input shape"
- "Could not read detector head metadata, missing key "
- "Detector '%s' in warmup: %ld/%ld"
- "Detector Head requires baseModel "
- "Detector head missing state input description"
- "Initialized uLanguageAligned detector head '%s' with activation threshold: %f, version: %s, base model: %s"
- "Movie Remix: Invalid type for key '%s' in dictionary."
- "Movie Remix: Missing expected key '%s' in dictionary."
- "SNULanguageAlignedAudioEncoder2sStreamifiedV3.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXBabyCry.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXBeep.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXBuzzer.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXCarHorn.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXCatMeow.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXCough.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXDingBell.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXDogBark.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXDoorKnock.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXDoorbell.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXFireAlarm.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXGlassBreak.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXKettleWhistling.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXShout.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXSiren.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXSmokeAlarm.mlmodelc"
- "SNULanguageAlignedDetectorHeadAXWaterRunning.mlmodelc"
- "SNULanguageAlignedDetectorHeadBabble.mlmodelc"
- "SNULanguageAlignedDetectorHeadIntelligibleSpeech.mlmodelc"
- "SNULanguageAlignedDetectorHeadMusic.mlmodelc"
- "SNULanguageAlignedDetectorHeadSpeech.mlmodelc"
- "SNULanguageAlignedDetectorHeadWaterArtifact.mlmodelc"
- "SNULanguageAlignedDetectorHeadWindArtifact.mlmodelc"
- "SNUSoundPrintSmokeAlarmWindowGlassBreakingModel.snmodelc"
- "State input shape has insufficient dimensions"
- "State temporal dimension ("
- "[PUB] shared CLAP embedding "
- "[PUB] shared CLAP embedding buffer "
- "_cos_state_input"
- "_sin_state_input"
- "audiomix_music"
- "buffer reachedMax "
- "languageAlignedAudioEncoderCoreMLMicro2sStreamified"
- "layers_2_time_transformers_0_attn_rope_cos_state_input.bin"
- "layers_2_time_transformers_0_attn_rope_sin_state_input.bin"
- "streamifiedULanguageAlignedLayer2CosInitialState"
- "streamifiedULanguageAlignedLayer2SinInitialState"
- "uLanguageAlignedBabbleDetectorCoreML"
- "uLanguageAlignedBabyCryAXDetectorCoreML"
- "uLanguageAlignedBeepAXDetectorCoreML"
- "uLanguageAlignedBuzzerAXDetectorCoreML"
- "uLanguageAlignedCarHornAXDetectorCoreML"
- "uLanguageAlignedCatMeowAXDetectorCoreML"
- "uLanguageAlignedCoughAXDetectorCoreML"
- "uLanguageAlignedDingBellAXDetectorCoreML"
- "uLanguageAlignedDogBarkAXDetectorCoreML"
- "uLanguageAlignedDoorKnockAXDetectorCoreML"
- "uLanguageAlignedDoorbellAXDetectorCoreML"
- "uLanguageAlignedFireAlarmAXDetectorCoreML"
- "uLanguageAlignedGlassBreakAXDetectorCoreML"
- "uLanguageAlignedIntelligibleSpeechDetectorCoreML"
- "uLanguageAlignedKettleWhistlingAXDetectorCoreML"
- "uLanguageAlignedMusicDetectorCoreML"
- "uLanguageAlignedShoutAXDetectorCoreML"
- "uLanguageAlignedSirenAXDetectorCoreML"
- "uLanguageAlignedSmokeAlarmAXDetectorCoreML"
- "uLanguageAlignedSpeechDetectorCoreML"
- "uLanguageAlignedWaterArtifactDetectorCoreML"
- "uLanguageAlignedWaterRunningAXDetectorCoreML"
- "uLanguageAlignedWindArtifactDetectorCoreML"
- "uSoundPrint Smoke Alarm and Window Glass Breaking Model E5RT not available"
```
