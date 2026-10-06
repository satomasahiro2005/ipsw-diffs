## TextToSpeech

> `/System/Library/PrivateFrameworks/TextToSpeech.framework/TextToSpeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x324974` | `0x343580` | **`+0x1ec0c`** |
| `__DATA.__bss` | `0x256f8` | `0x26998` | **`+0x12a0`** |
| `__AUTH_CONST.__const` | `0x165d8` | `0x17608` | **`+0x1030`** |
| `__TEXT.__cstring` | `0x796e` | `0x846e` | **`+0xb00`** |
| `__TEXT.__const` | `0x3ede9` | `0x3f829` | **`+0xa40`** |
| `__TEXT.__constg_swiftt` | `0x7d30` | `0x8370` | **`+0x640`** |
| `__AUTH_CONST.__objc_const` | `0xa570` | `0xaa20` | **`+0x4b0`** |
| `__TEXT.__swift5_reflstr` | `0x4960` | `0x4df0` | **`+0x490`** |
| `__TEXT.__eh_frame` | `0x16c00` | `0x17028` | **`+0x428`** |
| `__DATA_DIRTY.__data` | `0xd40` | `0x10f0` | **`+0x3b0`** |
| `__TEXT.__unwind_info` | `0xc5d0` | `0xc978` | **`+0x3a8`** |
| `__TEXT.__swift5_typeref` | `0x73c2` | `0x7742` | **`+0x380`** |
| `__TEXT.__swift5_fieldmd` | `0x5ec0` | `0x6190` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x2a64` | `0x2d24` | **`+0x2c0`** |
| `__AUTH.__objc_data` | `0x2e28` | `0x3070` | **`+0x248`** |
| `__TEXT.__swift5_capture` | `0x30a8` | `0x32f0` | **`+0x248`** |
| `__DATA.__data` | `0x3b10` | `0x3ca8` | **`+0x198`** |
| `__AUTH_CONST.__auth_got` | `0x29b0` | `0x2aa0` | **`+0xf0`** |
| `__TEXT.__swift5_proto` | `0x1290` | `0x1338` | **`+0xa8`** |
| `__DATA_CONST.__const` | `0x1910` | `0x19a0` | **`+0x90`** |
| `__TEXT.__swift_as_ret` | `0xd6c` | `0xdcc` | **`+0x60`** |
| `__AUTH.__data` | `0x42f0` | `0x4348` | **`+0x58`** |
| `__DATA_CONST.__got` | `0xd10` | `0xd68` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x28c8` | `0x2910` | **`+0x48`** |
| `__TEXT.__swift5_types` | `0x75c` | `0x790` | **`+0x34`** |
| `__TEXT.__swift_as_entry` | `0xc80` | `0xca8` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x125c` | `0x1268` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x360` | `0x368` | **`+0x8`** |

### Other Changes

```diff

-720.0.0.0.0
+723.1.0.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 15616
-  Symbols:   1360
-  CStrings:  1575
+  Functions: 16011
+  Symbols:   1368
+  CStrings:  1646
Symbols:
+ _AVAudioSessionRouteChangeNotification
+ _AnalyticsSendEventLazy
+ _NSFileSystemFreeSize
+ _NSHomeDirectory
+ _NSLocaleCurrencySymbol
+ _NSLocaleDecimalSeparator
+ _NSLocaleGroupingSeparator
+ __os_signpost_emit_with_name_impl
CStrings:
+ "#(?:[0-9A-Fa-f]{6}|[0-9A-Fa-f]{3})"
+ "$additionalLanguageScripts"
+ "$appliedVoicePredownloadGeneration"
+ "$audioQueueBufferPoolCapacity"
+ "$audioQueueBufferPoolEnabled"
+ "$audioQueueDiagnosticsEnabled"
+ "$highLatencyRouteThreshold"
+ "$maxRouteLatencyHeadroom"
+ "$preferredIOBufferDuration"
+ "$seamFadeDuration"
+ "(?:[0-9A-Fa-f]{1,4}:){2,7}[0-9A-Fa-f]{1,4}|(?:[0-9A-Fa-f]{1,4}:)+:(?:[0-9A-Fa-f]{1,4}:?)*[0-9A-Fa-f]{0,4}|::(?:[0-9A-Fa-f]{1,4}:?)+[0-9A-Fa-f]{0,4}"
+ "(?:[0-9A-Fa-f]{2}[:-]){5}[0-9A-Fa-f]{2}"
+ "(?:\\(\\d{3}\\)\\s?|\\d{3}[-. ])\\d{3}[-. ]?\\d{4}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?|\\d{10}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?|\\d{3}[-. ]\\d{4}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?|\\d{7}(?:\\s?(?:x|ext\\.?)\\s?\\d+)?"
+ "(?:\\d{1,3}(?:[,. \u202f ]\\d{3})+|\\d+)(?:[.,]\\d+)?|\\.\\d+"
+ "(?:\\d{1,3}(?:[,.\u00a0\u202f ]\\d{3})+|\\d+)(?:[.,]\\d+)?"
+ "(?:\\d{1,3}\\.){3}\\d{1,3}"
+ "(?<![\\p{L}\\p{N}])(-)?("
+ "(?<![\\p{L}\\p{N}])(?<![\\d.,])(-)?("
+ "(?<![\\p{L}\\p{N}])(["
+ "(?<![\\p{L}\\p{N}])\\(("
+ "(?<![\\p{L}\\p{N}])\\((US\\$|CA\\$|A\\$|HK\\$|NZ\\$|S\\$|NT\\$|R\\$|Mex\\$|[$€£¥₹₩₽₺₪₫฿₦₨₴₡₱])\\s?((?:\\d{1,3}(?:[,. \u202f ]\\d{3})+|\\d+)(?:[.,]\\d+)?|\\.\\d+)\\)(?![\\p{L}\\p{N}])"
+ "(?i)(?:x|ext\\.?)\\s?\\d+$"
+ ")(?![\\p{L}\\p{N}])"
+ ")(?![\\p{L}\\p{N}])/"
+ ")\\s?([A-Z]{3})(?![\\p{L}\\p{N}])"
+ ")\\s?([A-Z]{3})\\)(?![\\p{L}\\p{N}])"
+ "/(?<![\\p{L}\\p{N}])(?:"
+ "AudioQueue diag [%ld refills, %.*fHz]: dispatchLatency avg=%.*fms max=%.*fms, maxWork=%.*fms, minInFlight=%ld, underflows=%ld, genSkips=%ld, poolReuse=%ld alloc=%ld sizeMiss=%ld freeDepth=%ld"
+ "AudioQueue underflow #%ld: injecting silence. maxDispatchLatency=%.*fms, maxWork=%.*fms, minInFlight=%ld, sizeMisses=%ld, refills=%ld"
+ "AudioQueueRefill"
+ "Could not acquire RunningBoard assertion for regex cache flush: %{public}s"
+ "Error performing on boot voice upgrade."
+ "Failed to acquire silence buffer"
+ "Failed to start VoiceDatabaseXPC server: %@"
+ "Localizable-Currency"
+ "Localizable-DigitalCodes"
+ "RegexCompilationCache"
+ "SQLite regex cache flush"
+ "Skipping voice predownload: requires %lld bytes free on device."
+ "TTSSettingsAdditionalLanguageScripts"
+ "TTSSettingsAppliedVoicePredownloadGeneration"
+ "TTSSettingsAudioQueueBufferPoolCapacity"
+ "TTSSettingsAudioQueueBufferPoolEnabled"
+ "TTSSettingsAudioQueueDiagnosticsEnabled"
+ "TTSSettingsHighLatencyRouteThreshold"
+ "TTSSettingsMaxRouteLatencyHeadroom"
+ "TTSSettingsPreferredIOBufferDuration"
+ "TTSSettingsSeamFadeDuration"
+ "US\\$|CA\\$|A\\$|HK\\$|NZ\\$|S\\$|NT\\$|R\\$|Mex\\$|[$€£¥₹₩₽₺₪₫฿₦₨₴₡₱]"
+ "VoicePredownloader unable to determine available free space."
+ "[0-9A-Fa-f]{8}-[0-9A-Fa-f]{4}-[0-9A-Fa-f]{4}-[0-9A-Fa-f]{4}-[0-9A-Fa-f]{12}"
+ "[Error] Interval already ended"
+ "])(?![\\p{L}\\p{N}])"
+ "code.separator.colon"
+ "code.separator.dash"
+ "code.separator.dot"
+ "code.separator.doubleColon"
+ "code.separator.hash"
+ "code.separator.slash"
+ "com.apple.Accessibility.TextToSpeech.AudioQueueRefill"
+ "com.apple.voiceover.speechsnapshot"
+ "currency.formal."
+ "currency.format.majorMinor"
+ "currency.format.negative"
+ "customizedPerVoiceSettings"
+ "dispatchLatency: %fms"
+ "nonPrimaryLanguageRotorCount"
+ "primarySpeechLocale"
+ "primaryVoiceType"
+ "refill"
+ "telephone.extension"
+ "usingDefaultVoice"
+ "workDuration: %fms"
- "Failed to allocate silence buffer: %d"
- "TextToSpeech/Server.swift"
```
