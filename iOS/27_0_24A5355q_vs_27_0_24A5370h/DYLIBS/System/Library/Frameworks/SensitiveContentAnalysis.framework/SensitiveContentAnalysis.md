## SensitiveContentAnalysis

> `/System/Library/Frameworks/SensitiveContentAnalysis.framework/SensitiveContentAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__const` | `0x7a08` | `0x7b88` | **`+0x180`** |
| `__AUTH.__data` | `0xba8` | `0xb08` | **`-0xa0`** |
| `__DATA.__bss` | `0x10650` | `0x106f0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x27c7` | `0x2867` | **`+0xa0`** |
| `__TEXT.__text` | `0xd7718` | `0xd77a8` | **`+0x90`** |
| `__TEXT.__const` | `0xb648` | `0xb6a8` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x1cbb` | `0x1ceb` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1670` | `0x1658` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0x798` | `0x7b0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x4010` | `0x4028` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x2c70` | `0x2c5c` | **`-0x14`** |
| `__DATA.__data` | `0x17b0` | `0x17c0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x930` | `0x920` | **`-0x10`** |
| `__TEXT.__eh_frame` | `0x7acc` | `0x7abc` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0xa88` | `0xa8c` | **`+0x4`** |

### Other Changes

```diff

-145.0.0.0.0
+146.1.0.0.0

-  Functions: 5062
-  Symbols:   2305
-  CStrings:  460
+  Functions: 5073
+  Symbols:   2307
+  CStrings:  466
Symbols:
+ ___swift_memcpy240_8
+ _associated conformance 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeysOSHAASQ
+ _associated conformance 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeysOs0K3KeyAAs23CustomStringConvertible
+ _associated conformance 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeysOs0K3KeyAAs28CustomDebugStringConvertible
+ _symbolic _____ 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeysO
+ _type_layout_string 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV
- _associated conformance 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeys33_3AA529E5F8C65F2D956B874786034A8ALLOSHAASQ
- _associated conformance 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeys33_3AA529E5F8C65F2D956B874786034A8ALLOs0K3KeyAAs23CustomStringConvertible
- _associated conformance 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeys33_3AA529E5F8C65F2D956B874786034A8ALLOs0K3KeyAAs28CustomDebugStringConvertible
- _symbolic _____ 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeys33_3AA529E5F8C65F2D956B874786034A8ALLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeys33_3AA529E5F8C65F2D956B874786034A8ALLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 24SensitiveContentAnalysis20CoreAnalyticsManagerC11StreamStatsC9AllFramesV10CodingKeys33_3AA529E5F8C65F2D956B874786034A8ALLO
CStrings:
+ "Failed to encode analytics data: "
+ "age_verification_fallback_text"
+ "com.apple.SensitiveContentAnalysis.VSADispatcher"
+ "framesTotal"
+ "lastContributingTimestamp: "
+ "latestTimestamp"
+ "resolutionArea"
+ "sampleRate"
- "lastContributingTime"
- "lastContributingTime: "
```
