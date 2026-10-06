## AccessibilityReaderServices

> `/System/Library/PrivateFrameworks/AccessibilityReaderServices.framework/AccessibilityReaderServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7b58` | `0xaff8` | **`+0x34a0`** |
| `__DATA.__bss` | `0xa80` | `0x1800` | **`+0xd80`** |
| `__AUTH_CONST.__const` | `0xad0` | `0x1628` | **`+0xb58`** |
| `__TEXT.__const` | `0x7b0` | `0x1110` | **`+0x960`** |
| `__TEXT.__swift5_fieldmd` | `0x238` | `0x6ac` | **`+0x474`** |
| `__TEXT.__swift5_reflstr` | `0x221` | `0x551` | **`+0x330`** |
| `__TEXT.__cstring` | `0x32c` | `0x5cc` | **`+0x2a0`** |
| `__TEXT.__constg_swiftt` | `0x260` | `0x404` | **`+0x1a4`** |
| `__TEXT.__unwind_info` | `0x2a0` | `0x3e0` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x4e9` | `0x3e9` | **`-0x100`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0x150` | **`+0xd8`** |
| `__TEXT.__swift5_typeref` | `0x23c` | `0x2d6` | **`+0x9a`** |
| `__TEXT.__swift5_capture` | `0xf0` | `0x80` | **`-0x70`** |
| `__TEXT.__swift5_proto` | `0x58` | `0xc4` | **`+0x6c`** |
| `__DATA.__data` | `0x1a8` | `0x1e8` | **`+0x40`** |
| `__TEXT.__swift5_types` | `0x2c` | `0x68` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x428` | `0x3f8` | **`-0x30`** |

### Other Changes

```diff

-3232.3.0.0.0
+3234.5.0.0.0

-  Functions: 240
-  Symbols:   235
-  CStrings:  53
+  Functions: 494
+  Symbols:   264
+  CStrings:  90
Symbols:
+ ___swift_memcpy48_8
+ ___swift_memcpy56_8
+ ___swift_memcpy72_8
+ ___swift_memcpy80_8
+ _associated conformance 27AccessibilityReaderServices0B9AnalyticsV015CleanupBehaviorD0OSHAASQ
+ _associated conformance 27AccessibilityReaderServices0B9AnalyticsV11ThemeFamilyOSHAASQ
+ _associated conformance 27AccessibilityReaderServices0B9AnalyticsV14AppearanceModeOSHAASQ
+ _associated conformance 27AccessibilityReaderServices0B9AnalyticsV15SpeechEndReasonOSHAASQ
+ _associated conformance 27AccessibilityReaderServices0B9AnalyticsV17DynamicTypeBucketOSHAASQ
+ _associated conformance 27AccessibilityReaderServices0B9AnalyticsV19ContentLengthBucketOSHAASQ
+ _associated conformance 27AccessibilityReaderServices0B9AnalyticsV19PlaybackSpeedBucketOSHAASQ
+ _associated conformance 27AccessibilityReaderServices0B9AnalyticsV19RuntimeFetchOutcomeOSHAASQ
+ _associated conformance 27AccessibilityReaderServices0B9AnalyticsV20SummarizationTriggerOSHAASQ
+ _symbolic SSSg
+ _symbolic Sd
+ _symbolic SiSg
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV015CleanupBehaviorD0O
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV11ThemeFamilyO
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV14AppearanceModeO
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV15SpeechEndReasonO
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV17DynamicTypeBucketO
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV19ContentLengthBucketO
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV19PlaybackSpeedBucketO
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV19RuntimeFetchOutcomeO
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV20SessionTokensMetricsV
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV20SpeechSessionMetricsV
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV20SummarizationMetricsV
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV20SummarizationTriggerO
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV21ContentCleanupMetricsV
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV21FormatSnapshotMetricsV
+ _symbolic _____ 27AccessibilityReaderServices0B9AnalyticsV26RuntimeFetchContentMetricsV
+ _type_layout_string 27AccessibilityReaderServices0B9AnalyticsV20SessionTokensMetricsV
+ _type_layout_string 27AccessibilityReaderServices0B9AnalyticsV20SpeechSessionMetricsV
+ _type_layout_string 27AccessibilityReaderServices0B9AnalyticsV20SummarizationMetricsV
+ _type_layout_string 27AccessibilityReaderServices0B9AnalyticsV21ContentCleanupMetricsV
+ _type_layout_string 27AccessibilityReaderServices0B9AnalyticsV21FormatSnapshotMetricsV
+ _type_layout_string 27AccessibilityReaderServices0B9AnalyticsV26RuntimeFetchContentMetricsV
- ___swift__destructor
- _objc_release_x26
- _objc_retain_x24
- _swift_release_n
- _swift_release_x19
- _swift_retain_n
- _swift_retain_x19
- _symbolic SDySSSo8NSObjectCGIego_
CStrings:
+ "Sending analytic: %{public}s. %{sensitive}s"
+ "accessibility1To5"
+ "always"
+ "articleClosed"
+ "autoOnContentUpdate"
+ "characterCountDelta"
+ "com.apple.accessibility.reader.format.snapshot"
+ "com.apple.accessibility.reader.session.tokens"
+ "com.apple.accessibility.reader.speech.session"
+ "completed"
+ "contentLengthBucket"
+ "custom"
+ "dark"
+ "durationSpokenSec"
+ "dynamicTypeBucket"
+ "empty"
+ "error"
+ "fast"
+ "firstPageMaxChars"
+ "hostTerminated"
+ "interrupted"
+ "light"
+ "mToL"
+ "never"
+ "normal"
+ "over20k"
+ "playbackSpeedBucket"
+ "skipBackwardCount"
+ "skipForwardCount"
+ "slow"
+ "timeout"
+ "totalInputTokens"
+ "totalOutputTokens"
+ "ultraFast"
+ "under1k"
+ "under20k"
+ "under5k"
+ "userStopped"
+ "userTapped"
+ "veryFast"
+ "xlToXxl"
+ "xsToS"
- "'com.apple.accessibility.reader.readerinvoked'. "
- "Sending analytic: %{sensitive}s"
- "Sending analytic: 'com.apple.accessibility.reader.content.cleanup'. %{sensitive}s"
- "Sending analytic: 'com.apple.accessibility.reader.runtime.fetch.content'. %{sensitive}s"
- "Sending analytic: 'com.apple.accessibility.reader.summarization'. %{sensitive}s"
```
