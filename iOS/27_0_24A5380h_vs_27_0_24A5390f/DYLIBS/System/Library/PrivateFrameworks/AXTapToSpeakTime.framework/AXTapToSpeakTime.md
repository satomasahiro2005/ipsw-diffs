## AXTapToSpeakTime

> `/System/Library/PrivateFrameworks/AXTapToSpeakTime.framework/AXTapToSpeakTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6cd8` | `0x6be8` | **`-0xf0`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1e0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x258` | `0x270` | **`+0x18`** |

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

-  Symbols:   474
+  Symbols:   477
Symbols:
+ _kAXSTapToSpeakTimeAvailabilityPreference
+ _kAXSTapToSpeakTimeEnabledPreference
+ _kAXSVoiceOverTapticTimeEncoding
Functions:
~ -[AXTimeOutputPreferences tapToSpeakTimeEnabled] : 88 -> 28
~ -[AXTimeOutputPreferences setTapToSpeakTimeEnabled:] : 124 -> 104
~ -[AXTimeOutputPreferences tapToSpeakTimeAvailability] : 88 -> 28
~ -[AXTimeOutputPreferences setTapToSpeakTimeAvailability:] : 124 -> 104
~ -[AXTimeOutputPreferences voiceOverTapticTimeEncoding] : 88 -> 28
~ -[AXTimeOutputPreferences setVoiceOverTapticTimeEncoding:] : 124 -> 104
```
