## SiriMessageBus

> `/System/Library/PrivateFrameworks/SiriMessageBus.framework/SiriMessageBus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x3f20` | `0x3a60` | **`-0x4c0`** |
| `__TEXT.__eh_frame` | `0x9960` | `0x96b8` | **`-0x2a8`** |
| `__TEXT.__text` | `0x1080d8` | `0x107f10` | **`-0x1c8`** |
| `__TEXT.__cstring` | `0x399a` | `0x3a9a` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x8c23` | `0x8d13` | **`+0xf0`** |
| `__AUTH_CONST.__const` | `0x6420` | `0x63c8` | **`-0x58`** |
| `__TEXT.__const` | `0x5470` | `0x5420` | **`-0x50`** |
| `__TEXT.__swift_as_ret` | `0x480` | `0x44c` | **`-0x34`** |
| `__DATA_CONST.__objc_selrefs` | `0xeb0` | `0xee0` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x25f0` | `0x2618` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x1328` | `0x134c` | **`+0x24`** |
| `__TEXT.__swift5_typeref` | `0x2259` | `0x2235` | **`-0x24`** |
| `__DATA_CONST.__got` | `0x1548` | `0x1568` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x26f8` | `0x26d8` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x18af` | `0x18cf` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x764` | `0x750` | **`-0x14`** |
| `__AUTH.__data` | `0x9f8` | `0xa08` | **`+0x10`** |
| `__DATA.__data` | `0x1388` | `0x1398` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x232c` | `0x231c` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x1900` | `0x18f0` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x2d0` | `0x2c4` | **`-0xc`** |
| `__TEXT.__objc_methlist` | `0x1484` | `0x148c` | **`+0x8`** |

### Other Changes

```diff

-3600.48.10.1.3
+3600.54.6.0.0

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 5888
-  Symbols:   1820
-  CStrings:  765
+  Functions: 5901
+  Symbols:   1843
+  CStrings:  775
Symbols:
+ _OBJC_CLASS_$_SAPerson
+ _OUTLINED_FUNCTION_512
+ _OUTLINED_FUNCTION_513
+ _OUTLINED_FUNCTION_514
+ _OUTLINED_FUNCTION_515
+ _OUTLINED_FUNCTION_516
+ _OUTLINED_FUNCTION_517
+ _OUTLINED_FUNCTION_518
+ _OUTLINED_FUNCTION_519
+ _OUTLINED_FUNCTION_520
+ _OUTLINED_FUNCTION_521
+ _OUTLINED_FUNCTION_522
+ _OUTLINED_FUNCTION_523
+ _OUTLINED_FUNCTION_524
+ _OUTLINED_FUNCTION_525
+ _OUTLINED_FUNCTION_526
+ _OUTLINED_FUNCTION_527
+ _OUTLINED_FUNCTION_528
+ _OUTLINED_FUNCTION_529
+ _OUTLINED_FUNCTION_530
+ _OUTLINED_FUNCTION_531
+ _OUTLINED_FUNCTION_532
+ _OUTLINED_FUNCTION_533
+ _OUTLINED_FUNCTION_534
+ _symbolic SdSg
- _symbolic ScCySo8SAPersonCSg_____G s5NeverO
- _symbolic So8SAPersonCSg
CStrings:
+ "Generating SASRecognition with input text: %s"
+ "IntelligenceFlowProxy: received SessionServerMessage type: %s, id: %s, content: %{sensitive}s"
+ "Skipping SiriXAgent aceId dedup: command %s has nil aceId"
+ "Unable to generate AFSpeechUtterance with input text: %s"
+ "User turn finalized with mitigated decision; notifying MAF that detected speech was undirected."
+ "com.apple.siri.enhanced"
+ "sessionRetrieved"
+ "siriActivationRequested"
+ "speechDetectionUpdate"
+ "speechPartialResult"
+ "systemTurnInterruptionEnded"
+ "systemTurnInterruptionStarted"
+ "userTurnFinalized"
- "Fetched mecard"
- "IntelligenceFlowProxy: received SessionServerMessage with id: %s, content: %{sensitive}s"
- "No mecard found"
```
