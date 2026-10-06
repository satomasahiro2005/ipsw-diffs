## CallIntelligence

> `/System/Library/PrivateFrameworks/CallIntelligence.framework/CallIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc028` | `0xdfa8c` | **`+0x3a64`** |
| `__AUTH_CONST.__const` | `0x7888` | `0x7d08` | **`+0x480`** |
| `__DATA.__bss` | `0x13350` | `0x13650` | **`+0x300`** |
| `__TEXT.__const` | `0xe290` | `0xe590` | **`+0x300`** |
| `__TEXT.__oslogstring` | `0x3473` | `0x3753` | **`+0x2e0`** |
| `__AUTH_CONST.__objc_const` | `0x8050` | `0x8218` | **`+0x1c8`** |
| `__TEXT.__swift5_capture` | `0x99c` | `0xafc` | **`+0x160`** |
| `__TEXT.__swift5_reflstr` | `0x2a68` | `0x2bc8` | **`+0x160`** |
| `__AUTH.__data` | `0x2200` | `0x2328` | **`+0x128`** |
| `__TEXT.__cstring` | `0x2461` | `0x2571` | **`+0x110`** |
| `__TEXT.__constg_swiftt` | `0x2e34` | `0x2f34` | **`+0x100`** |
| `__TEXT.__swift5_fieldmd` | `0x3480` | `0x3580` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0x7ef8` | `0x7fb0` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x3898` | `0x3950` | **`+0xb8`** |
| `__TEXT.__swift5_typeref` | `0x3a23` | `0x3ab5` | **`+0x92`** |
| `__AUTH_CONST.__auth_got` | `0x1320` | `0x1388` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0xe18` | `0xe70` | **`+0x58`** |
| `__DATA.__data` | `0x2678` | `0x26c8` | **`+0x50`** |
| `__DATA_CONST.__got` | `0xa28` | `0xa48` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xecc` | `0xee4` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xb60` | `0xb78` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x1340` | `0x1350` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x3ec` | `0x3fc` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x298` | `0x2a4` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x118` | `0x120` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x4a4` | `0x4ac` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x284` | `0x280` | **`-0x4`** |

### Other Changes

```diff

-139.100.27.2.9
+143.100.11.2.1

+  - /System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary

+  - /System/Library/PrivateFrameworks/ModelCatalog.framework/ModelCatalog

+  - /System/Library/PrivateFrameworks/TextUnderstanding.framework/TextUnderstanding

-  Functions: 4385
-  Symbols:   1984
-  CStrings:  459
+  Functions: 4453
+  Symbols:   2005
+  CStrings:  471
Symbols:
+ _BiomeLibrary
+ _MDItemEventIsAllDay
+ _OBJC_CLASS_$_BMCommAppsCallContextCardsFedStats
+ __DATA__TtC16CallIntelligence27CallContextCardsBiomeStream
+ __IVARS__TtC16CallIntelligence27CallContextCardsBiomeStream
+ __METACLASS_DATA__TtC16CallIntelligence27CallContextCardsBiomeStream
+ ___swift_closure_destructor.114Tm
+ ___swift_closure_destructor.14Tm
+ ___swift_closure_destructor.65Tm
+ _associated conformance 16CallIntelligence0A23ContextCardsBiomeStreamC14EngagementTypeOSHAASQ
+ _associated conformance 16CallIntelligence12ABCRuleErrorOSHAASQ
+ _notify_cancel
+ _notify_register_dispatch
+ _swift_isEscapingClosureAtFileLocation
+ _symbolic Say_____G So17OS_dispatch_queueC8DispatchE10AttributesV
+ _symbolic So17OS_dispatch_queueC
+ _symbolic So8BMStreamCySo34BMCommAppsCallContextCardsFedStatsCG
+ _symbolic _____ 16CallIntelligence0A23ContextCardsBiomeStreamC
+ _symbolic _____ 16CallIntelligence0A23ContextCardsBiomeStreamC14EngagementTypeO
+ _symbolic _____ 16CallIntelligence12ABCRuleErrorO
+ _symbolic _____ 16CallIntelligence8ABCMatchV
+ _symbolic _____SgXw 16CallIntelligence0A23ContextCardsBiomeStreamC
+ _symbolic _____y__________G s6ResultOsRi_zRi0_zrlE 16CallIntelligence8ABCMatchV AC12ABCRuleErrorO
+ _type_layout_string 16CallIntelligence8ABCMatchV
- ___swift_closure_destructor.67Tm
- ___swift_closure_destructor.9Tm
- _symbolic Say_____G 16CallIntelligence0A22ContextSearchQueryTypeO
CStrings:
+ "CallContextCardsBiomeStream: already registered for call history pruning, skipping"
+ "CallContextCardsBiomeStream: donating filtered event, filteredReason=%s"
+ "CallContextCardsBiomeStream: donating shown event, engagementType=%s"
+ "CallContextCardsBiomeStream: failed to register for all-calls-cleared notification, status: %u"
+ "CallContextCardsBiomeStream: failed to register for some-calls-cleared notification, status: %u"
+ "CallContextCardsBiomeStream: skipping filtered event donation, cardTitle is nil or empty"
+ "CallContextCardsBiomeStream: skipping shown event donation, cardTitle is nil or empty"
+ "Spotlight error: "
+ "Text field represents spoken utterance during a phone call. The text might contain information on the expected wait time for the caller or the callers position in the queue. Your task is to extract this information. Utterance may mention queue position, wait time, or neither.\nOutput must be a JSON with 4 fields:\nisWaitTimeAvailable: This is a boolean flag to indicate if utterance mentions wait time in minutes\nisQueuePositionAvailable: This is a boolean flag to indicate if utterance mentions queue position or number of callers\nwaitTimeLowerBound: The estimated wait time in minutes.\nwaitTimeUpperBound: If the utterance gives a time range, then populate this field with the upper bound in minutes. Otherwise populate field as None.\nqueuePosition: The number of callers in the queue at the moment\nAnalyze each text independently.\n\nText: \"Your estimated wait time is five minutes.\"\nAnswer: { isWaitTimeAvailable: True, isQueuePositionAvailable: False, waitTimeLowerBound: 5, waitTimeUpperBound: None, queuePosition: None}\n\nText: \"There are 6 customers in the queue\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: True, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: 6}\n\nText: \"There are 2 callers ahead of you.\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: True, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: 2}\n\nText: \"Your expected hold time is between 24 minutes to 30 minutes.\"\nAnswer: { isWaitTimeAvailable: True, isQueuePositionAvailable: False, waitTimeLowerBound: 24, waitTimeUpperBound: 30, queuePosition: None}\n\nText: \"We will answer your call in a few minutes.\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: False, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: None}\n\nText: \"Please remain on the line, and a representative will be with you shortly.\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: False, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: None}\n\nText: \"To hold your place in the queue and receive a callback from the next available specialist, please press 9.\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: False, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: None}\n\nText: \"The survey should only take two or three minutes;\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: False, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: None}"
+ "WaitTimeProvider: wait time bounds (lower=%ld, upper=%ld) exceed plausible range"
+ "com.apple.callhistory.RecentDeletedNotification"
+ "com.apple.callhistory.RecentsClearedNotification"
+ "com.apple.callintelligence.CallContextCardsBiomeStream.notify"
+ "com.apple.fm.language.instruct_3b.holdassistwaittime"
+ "runQuery(queryString:atTime:disableMinimumFieldRequirements:queryContainsName:)"
- "SmartActions_EngDB3.sqlitedb"
- "Text field represents spoken utterance during a phone call. The text might contain information on the expected wait time for the caller or the callers position in the queue. Your task is to extract this information. Utterance will mention a queue position or wait time but not both.\nOutput must be a JSON with 4 fields:\nisWaitTimeAvailable: This is a boolean flag to indicate if utterance mentions wait time in minutes\nisQueuePositionAvailable: This is a boolean flag to indicate if utterance mentions queue position or number of callers\nwaitTimeLowerBound: The estimated wait time in minutes.\nwaitTimeUpperBound: If the utterance gives a time range, then populate this field with the upper bound in minutes. Otherwise populate field as None.\nqueuePosition: The number of callers in the queue at the moment\nAnalyze each text independently.\n\nText: \"Your estimated wait time is five minutes.\"\nAnswer: { isWaitTimeAvailable: True, isQueuePositionAvailable: False, waitTimeLowerBound: 5, waitTimeUpperBound: None, queuePosition: None}\n\nText: \"There are 6 customers in the queue\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: True, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: 6}\n\nText: \"There are 2 callers ahead of you.\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: True, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: 2}\n\nText: \"Your expected hold time is between 24 minutes to 30 minutes.\"\nAnswer: { isWaitTimeAvailable: True, isQueuePositionAvailable: False, waitTimeLowerBound: 24, waitTimeUpperBound: 30, queuePosition: None}\n\nText: \"We will answer your call in a few minutes.\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: False, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: None}\n\nText: \"Please remain on the line, and a representative will be with you shortly.\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: False, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: None}\n\nText: \"To hold your place in the queue and receive a callback from the next available specialist, please press 9.\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: False, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: None}\n\nText: \"The survey should only take two or three minutes;\"\nAnswer: { isWaitTimeAvailable: False, isQueuePositionAvailable: False, waitTimeLowerBound: None, waitTimeUpperBound: None, queuePosition: None}"
- "runQuery(queryString:atTime:disableMinimumFieldRequirements:)"
```
