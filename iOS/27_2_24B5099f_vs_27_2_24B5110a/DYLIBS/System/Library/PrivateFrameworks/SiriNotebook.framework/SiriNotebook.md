## SiriNotebook

> `/System/Library/PrivateFrameworks/SiriNotebook.framework/SiriNotebook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b98a8` | `0x2cdd28` | **`+0x14480`** |
| `__TEXT.__eh_frame` | `0x14c10` | `0x15410` | **`+0x800`** |
| `__TEXT.__const` | `0x29794` | `0x29ac4` | **`+0x330`** |
| `__DATA.__bss` | `0x283d0` | `0x28650` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x834e` | `0x856e` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0x10b18` | `0x10d28` | **`+0x210`** |
| `__AUTH_CONST.__const` | `0x16f88` | `0x170f0` | **`+0x168`** |
| `__AUTH_CONST.__auth_got` | `0x3240` | `0x3330` | **`+0xf0`** |
| `__DATA.__data` | `0x8130` | `0x8220` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x8a18` | `0x8aec` | **`+0xd4`** |
| `__TEXT.__swift5_typeref` | `0xaa4c` | `0xab1a` | **`+0xce`** |
| `__TEXT.__swift5_fieldmd` | `0x8c78` | `0x8d24` | **`+0xac`** |
| `__TEXT.__swift_as_cont` | `0x10e0` | `0x115c` | **`+0x7c`** |
| `__TEXT.__swift5_assocty` | `0x19d0` | `0x1a48` | **`+0x78`** |
| `__DATA_CONST.__got` | `0x3230` | `0x3278` | **`+0x48`** |
| `__TEXT.__swift_as_ret` | `0x1004` | `0x104c` | **`+0x48`** |
| `__DATA.__common` | `0x798` | `0x7c8` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x5ab1` | `0x5ae1` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x2ebc` | `0x2ee4` | **`+0x28`** |
| `__TEXT.__cstring` | `0x6586` | `0x65a6` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x15b0` | `0x15c4` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x8b8` | `0x8cc` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0xde8` | `0xdfc` | **`+0x14`** |

### Other Changes

```diff

+  - /System/Library/Frameworks/AppIntents.framework/AppIntents

-  Functions: 25334
-  Symbols:   4893
-  CStrings:  1246
+  Functions: 25561
+  Symbols:   4916
+  CStrings:  1253
Symbols:
+ ___swift_closure_destructor.10Tm
+ ___swift_closure_destructor.127Tm
+ ___swift_closure_destructor.161Tm
+ ___swift_closure_destructor.165Tm
+ ___swift_closure_destructor.38Tm
+ ___swift_closure_destructor.41Tm
+ ___swift_closure_destructor.45Tm
+ ___swift_closure_destructor.49Tm
+ ___swift_closure_destructor.78Tm
+ _symbolic $s18AppIntentsServices0A20IntentRepresentationP
+ _symbolic _____ 12SiriNotebook09SearchForB5ItemsO15ReadingStrategyV14emphasisIntent023_B51E1E0278BCAF449843C0N8AF4B8870LL18AppIntentsServices0qI14Representation_pSgvg08EmphasisI0L_V
+ _symbolic _____ 12SiriNotebook15AppIntentHelperV
+ _symbolic _____ 12SiriNotebook15AppIntentHelperV15RepresentationsO
+ _symbolic _____ 12SiriNotebook15AppIntentHelperV15RepresentationsO012OpenReminderD0V
+ _symbolic _____ 12SiriNotebook15AppIntentHelperV15RepresentationsO013OpenSmartListD0V
+ _symbolic _____ 12SiriNotebook15AppIntentHelperV15RepresentationsO08OpenListD0V
+ _symbolic _____ 12SiriNotebook23NavigateToListsRootFlowV
+ _symbolic _____ s5NeverO
+ _symbolic _____Sg 13SiriUtilities11DeviceIdiomO
+ _symbolic _____Sg 18AppIntentsServices0A20IntentPerformOptionsV
+ _symbolic _____Sg 18AppIntentsServices18SnippetEnvironmentV
+ _symbolic _____Sg 22UniformTypeIdentifiers6UTTypeV
+ _symbolic _____Sg_ABt 13SiriUtilities11DeviceIdiomO
+ _symbolic ______p 18AppIntentsServices0A20IntentRepresentationP
+ _symbolic _____ySSSgG s11_SetStorageC
+ _symbolic _____y_____G 18AppIntentsServices15IntentParameterC 09RemindersaB024ListEntityRepresentationC
+ _symbolic _____y_____G 18AppIntentsServices15IntentParameterC 09RemindersaB027SmartListTypeRepresentationO
+ _symbolic _____y_____G 18AppIntentsServices15IntentParameterC 09RemindersaB028ReminderEntityRepresentationC
+ _type_layout_string 12SiriNotebook15AppIntentHelperV15RepresentationsO012OpenReminderD0V
+ _type_layout_string 12SiriNotebook15AppIntentHelperV15RepresentationsO013OpenSmartListD0V
+ _type_layout_string 12SiriNotebook15AppIntentHelperV15RepresentationsO08OpenListD0V
+ _type_layout_string 12SiriNotebook23NavigateToListsRootFlowV
- ___swift_closure_destructor.125Tm
- ___swift_closure_destructor.157Tm
- ___swift_closure_destructor.163Tm
- ___swift_closure_destructor.33Tm
- ___swift_closure_destructor.37Tm
- ___swift_closure_destructor.40Tm
- ___swift_closure_destructor.44Tm
- ___swift_closure_destructor.48Tm
- ___swift_closure_destructor.9Tm
CStrings:
+ "Couldn't make reminder entity due to invalid UUID string: %s"
+ "Failed to produce output with app intent. %s - %s."
+ "Sending dialog with app intent instead of snippet: %s"
+ "SiriEmphasisAppIntent"
+ "[AddTasks NeedsValueStrategy] Skipping needs value snippet for parameter %s"
+ "[SetTaskAttribute NeedsValueStrategy] Either parameter is not title or no task on intent. Skippping snippet"
+ "[makeOpenCreatedReminder] Cannot make app intent response - invalid task identifier: %s"
+ "[makeReminderUpdated] Cannot make app intent response - invalid task identifier: %s"
- "NoOp AppIntentHelper called"
```
