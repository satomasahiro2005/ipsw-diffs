## SiriMessagesUICommon

> `/System/Library/PrivateFrameworks/SiriMessagesUICommon.framework/SiriMessagesUICommon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9f578` | `0xa3c3c` | **`+0x46c4`** |
| `__TEXT.__oslogstring` | `0x1d4a` | `0x215a` | **`+0x410`** |
| `__TEXT.__eh_frame` | `0x4c60` | `0x4e40` | **`+0x1e0`** |
| `__TEXT.__unwind_info` | `0x36f8` | `0x3878` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0x7150` | `0x7270` | **`+0x120`** |
| `__TEXT.__const` | `0xb784` | `0xb8a4` | **`+0x120`** |
| `__AUTH_CONST.__auth_got` | `0x1018` | `0x1110` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x2f74` | `0x3044` | **`+0xd0`** |
| `__DATA.__data` | `0x1658` | `0x16f0` | **`+0x98`** |
| `__TEXT.__swift5_typeref` | `0x20c4` | `0x2154` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x2bf0` | `0x2c58` | **`+0x68`** |
| `__TEXT.__swift5_reflstr` | `0x1f9e` | `0x1ffe` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x21b0` | `0x2200` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x6e8` | `0x718` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x468` | `0x478` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x14c` | `0x158` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0xf0` | `0xfc` | **`+0xc`** |
| `__AUTH.__data` | `0x8a8` | `0x8b0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x308` | `0x310` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xd4` | `0xdc` | **`+0x8`** |

### Other Changes

```diff

-3600.47.13.0.0
+3600.47.22.11.2

+  - /System/Library/PrivateFrameworks/AppIntentsServices.framework/AppIntentsServices

+  - /System/Library/PrivateFrameworks/_AppIntentsServices_AppIntents.framework/_AppIntentsServices_AppIntents

-  Functions: 5818
-  Symbols:   1491
-  CStrings:  472
+  Functions: 5895
+  Symbols:   1507
+  CStrings:  492
Symbols:
+ _INIntentSlotValueTransformToContactValue
+ _OBJC_CLASS_$_SABaseClientBoundCommand
+ _OBJC_CLASS_$_SAUIAppIntentData
+ _OBJC_CLASS_$_SAUIPerformAppIntent
+ _symbolic Say_____G 10AppIntents12IntentPersonV
+ _symbolic _____ 20SiriMessagesUICommon23PerformAppIntentFactoryO
+ _symbolic _____ 20SiriMessagesUICommon36SendOnDismissPerformAppIntentBuilderO
+ _symbolic _____Sg 10AppIntents12IntentPersonV
+ _symbolic _____Sg 10AppIntents12IntentPersonV6HandleV
+ _symbolic _____Sg 10AppIntents21DisplayRepresentationV5ImageV
+ _symbolic _____Sg 10Foundation16AttributedStringV
+ _symbolic _____Sg 18AppIntentsServices0A16InstanceLocationV
+ _symbolic _____Sg 18AppIntentsServices13SchemaVersionV
+ _symbolic _____Sg 7ToolKit0A10DefinitionV
+ _symbolic _____ySo24SABaseClientBoundCommandCG 20SiriMessagesUICommon12ModelCodableV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10AppIntents12IntentPersonV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 18AppIntentsServices13NamedPropertyV
- _OUTLINED_FUNCTION_185
CStrings:
+ "#INPerson displayName %s"
+ "#INPerson email handle type %s"
+ "#INPerson nameComponents %s"
+ "#INPerson neither email or phone handle type, return nil"
+ "#INPerson no personHandle, value, or type"
+ "#INPerson phonenumber handle type %s"
+ "#INPerson unknown name"
+ "#SendOnDismissPerformAppIntentBuilder built spec bundleId=%{public}s actionId=%{public}s parameters count=%ld"
+ "#SendOnDismissPerformAppIntentBuilder failed to encode AppIntentSpecification: %@"
+ "#SendOnDismissPerformAppIntentBuilder made SAUIPerformAppIntent aceId=%{public}s"
+ "#SendOnDismissPerformAppIntentBuilder make begin bundleId=%{public}s mapped intentPersons=%ld"
+ "#SendOnDismissPerformAppIntentBuilder no messages.sendMessage AppIntent for %{public}s; aborting"
+ "#SendOnDismissPerformAppIntentBuilder no recipients to send to; aborting"
+ "#SendOnDismissPerformAppIntentBuilder tool %{public}s has no .appIntent system protocol; app does not conform to the sendMessage AppIntent schema, aborting"
+ "Messages#MessageRetrievalUnavailable"
+ "SendMessage#ConfirmTapbackType"
+ "contactHandle://"
+ "doneAssociatedEntitiesData"
+ "sendOnDismissCommand"
+ "shouldMentionLast"
```
