## AXTapToSpeakTime

> `/System/Library/PrivateFrameworks/AXTapToSpeakTime.framework/AXTapToSpeakTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e68` | `0x6cd8` | **`-0x190`** |
| `__DATA_CONST.__got` | `0x1a0` | `0x1c8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x240` | `0x258` | **`+0x18`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Symbols:   469
+  Symbols:   474
Symbols:
+ _kAXSVoiceOverTapticChimesEnabled
+ _kAXSVoiceOverTapticChimesFrequencyEncoding
+ _kAXSVoiceOverTapticChimesSoundType
+ _kAXSVoiceOverTapticChimesUnity25Active
+ _kAXSVoiceOverTapticChimesUnity25SoundType
Functions:
~ -[AXTimeOutputPreferences voiceOverTapticChimesEnabled] : 88 -> 28
~ -[AXTimeOutputPreferences setVoiceOverTapticChimesEnabled:] : 124 -> 104
~ -[AXTimeOutputPreferences voiceOverTapticChimesFrequencyEncoding] : 88 -> 28
~ -[AXTimeOutputPreferences setVoiceOverTapticChimesFrequencyEncoding:] : 124 -> 104
~ -[AXTimeOutputPreferences voiceOverTapticChimesSoundType] : 132 -> 116
~ -[AXTimeOutputPreferences setVoiceOverTapticChimesSoundType:] : 188 -> 168
~ -[AXTimeOutputPreferences voiceOverTapticChimesUnity25Active] : 80 -> 20
~ -[AXTimeOutputPreferences setVoiceOverTapticChimesUnity25Active:] : 124 -> 104
~ -[AXTimeOutputPreferences _voiceOverTapticChimesUnity25SoundType] : 88 -> 28
~ -[AXTimeOutputPreferences _setVoiceOverTapticChimesUnity25SoundType:] : 136 -> 116
~ -[AXTimeOutputPreferences _syncWithStandardVoiceOverTapticChimesSoundType:] : 140 -> 120
~ -[AXTimeOutputPreferences _syncWithUnity25VoiceOverTapticChimesSoundType:] : 140 -> 120
~ -[AXTapticChimeAsset createSystemSoundIDForStartTime:] : 656 -> 652
```
