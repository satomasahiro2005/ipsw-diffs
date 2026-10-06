## SiriNotebookFlowTools

> `/System/Library/FlowTools/Tools/SiriNotebookFlowTools.flowtool/SiriNotebookFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bf68` | `0x50d14` | **`+0x4dac`** |
| `__DATA_CONST.__const` | `0xb70` | `0xf30` | **`+0x3c0`** |
| `__TEXT.__objc_stubs` | `0x120` | `0x3e0` | **`+0x2c0`** |
| `__TEXT.__objc_methname` | `0x1e1` | `0x3f9` | **`+0x218`** |
| `__TEXT.__swift5_capture` | `0xc4` | `0x244` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x15c8` | `0x1690` | **`+0xc8`** |
| `__DATA.__objc_selrefs` | `0x48` | `0xf8` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x3cf8` | `0x3d80` | **`+0x88`** |
| `__TEXT.__auth_stubs` | `0x13f0` | `0x1470` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0xb02` | `0xb7e` | **`+0x7c`** |
| `__DATA_CONST.__got` | `0x398` | `0x410` | **`+0x78`** |
| `__DATA.__data` | `0xba8` | `0xbe8` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xa00` | `0xa40` | **`+0x40`** |
| `__TEXT.__const` | `0x2598` | `0x25d8` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x7c3` | `0x803` | **`+0x40`** |
| `__DATA.__objc_const` | `0x860` | `0x880` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0xe38` | `0xe58` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x508` | `0x528` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x654` | `0x660` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x3ac` | `0x3b4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.22.7.0.0
+3600.28.3.0.0

+  - /System/Library/PrivateFrameworks/SiriAnalytics.framework/SiriAnalytics
+  - /System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation

-  Functions: 1662
-  Symbols:   134
-  CStrings:  96
+  Functions: 1797
+  Symbols:   146
+  CStrings:  120
Symbols:
+ _OBJC_CLASS_$_AssistantSiriAnalytics
+ _OBJC_CLASS_$_FTDReminderSchemaFTDReminderAttributes
+ _OBJC_CLASS_$_FTDReminderSchemaFTDReminderCreateListAddReminderInvoked
+ _OBJC_CLASS_$_FTDReminderSchemaFTDReminderCreateReminderInvoked
+ _OBJC_CLASS_$_FTDReminderSchemaFTDReminderPrepareReadRemindersInvoked
+ _OBJC_CLASS_$_FTDReminderSchemaFTDReminderToolInvoked
+ _OBJC_CLASS_$_FTDReminderSchemaFTDReminderUpdateReminderInvoked
+ _OBJC_CLASS_$_FTDSchemaFTDClientEvent
+ _OBJC_CLASS_$_FTDSchemaFTDClientEventMetadata
+ _OBJC_CLASS_$_SISchemaUUID
+ _objc_release
+ _swift_retain_x21
CStrings:
+ "FTDReminderMetricsSubmitter: Could not create SELF event"
+ "defaultMessageStream"
+ "emitMessage:isolatedStreamUUID:"
+ "initWithNSUUID:"
+ "setAttributes:"
+ "setBundleId:"
+ "setEventMetadata:"
+ "setFlowToolClientInteractionId:"
+ "setHasDueDate:"
+ "setHasLocationTrigger:"
+ "setHasRecurrence:"
+ "setHasTargetList:"
+ "setInvoked:"
+ "setIsCompleted:"
+ "setIsFlagged:"
+ "setListType:"
+ "setReminderCount:"
+ "setReminderCreateListAddReminderInvoked:"
+ "setReminderCreateReminderInvoked:"
+ "setReminderPrepareReadRemindersInvoked:"
+ "setReminderUpdateReminderInvoked:"
+ "setSpotlightSearchLatencyMs:"
+ "sharedAnalytics"
+ "spotlightSearchLatencyMs"
```
