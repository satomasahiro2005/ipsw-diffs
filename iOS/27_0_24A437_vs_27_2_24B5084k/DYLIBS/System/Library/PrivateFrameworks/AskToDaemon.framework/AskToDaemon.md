## AskToDaemon

> `/System/Library/PrivateFrameworks/AskToDaemon.framework/AskToDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x89178` | `0x8c624` | **`+0x34ac`** |
| `__TEXT.__eh_frame` | `0x44c8` | `0x48cc` | **`+0x404`** |
| `__AUTH_CONST.__const` | `0x2ad8` | `0x2cf0` | **`+0x218`** |
| `__TEXT.__oslogstring` | `0x52e2` | `0x54f2` | **`+0x210`** |
| `__TEXT.__const` | `0x3248` | `0x33dc` | **`+0x194`** |
| `__TEXT.__swift5_typeref` | `0x19e4` | `0x1b29` | **`+0x145`** |
| `__TEXT.__unwind_info` | `0x16f0` | `0x1820` | **`+0x130`** |
| `__TEXT.__cstring` | `0x1fc7` | `0x2099` | **`+0xd2`** |
| `__TEXT.__swift5_capture` | `0x75c` | `0x82c` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x1014` | `0x10cd` | **`+0xb9`** |
| `__TEXT.__constg_swiftt` | `0x11d4` | `0x1284` | **`+0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0xe78` | `0xf1c` | **`+0xa4`** |
| `__AUTH.__data` | `0xcf8` | `0xd98` | **`+0xa0`** |
| `__TEXT.__swift_as_cont` | `0x414` | `0x464` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x1598` | `0x15d8` | **`+0x40`** |
| `__DATA.__data` | `0xf78` | `0xfb8` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x1f0` | `0x210` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x198` | `0x1a8` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x114` | `0x120` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x12a0` | `0x12a8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1b4` | `0x1bc` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x8c` | `0x94` | **`+0x8`** |

### Other Changes

```diff

-96.0.0.0.0
+97.125.4.0.0

-  Functions: 1546
-  Symbols:   935
-  CStrings:  529
+  Functions: 1616
+  Symbols:   954
+  CStrings:  540
Symbols:
+ ___swift_closure_destructor.130Tm
+ ___swift_closure_destructor.26Tm
+ ___swift_closure_destructor.34Tm
+ ___swift_closure_destructor.42Tm
+ ___swift_closure_destructor.60Tm
+ _flat unique So8NSObject_p
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _symbolic $s11AskToDaemon0aB22BalloonMessageScanningP
+ _symbolic $s11AskToDaemon37LegacyScreenTimeMessagesLookupCapableP
+ _symbolic SS11messageGUID______7payload_____6sourcet 9AskToCore9ATPayloadC 0aB6Daemon23ScreenTimeAnswerHandlerV13MessageSourceO
+ _symbolic SS11messageGUID______7payloadt 9AskToCore9ATPayloadC
+ _symbolic ScCySaySS11messageGUID______10payloadURL_____0C0tG______pG 10Foundation3URLV 9AskToCore9ATPayloadC s5ErrorP
+ _symbolic _____ 11AskToDaemon08IMSPIAskB21BalloonMessageScannerV
+ _symbolic _____ 11AskToDaemon23ScreenTimeAnswerHandlerV13MessageSourceO
+ _symbolic _____ 11AskToDaemon30LegacyScreenTimeMessagesLookupV
+ _symbolic _____ s8DurationV
+ _symbolic _____10payloadURL_t 10Foundation3URLV
+ _symbolic _____SbIeggd_ 9AskToCore9ATPayloadC
+ _symbolic ______p 11AskToDaemon0aB22BalloonMessageScanningP
+ _symbolic ______p 11AskToDaemon37LegacyScreenTimeMessagesLookupCapableP
+ _symbolic ______p So8NSObjectP
+ _symbolic _____ySS11messageGUID______7payload_____6sourcetG s23_ContiguousArrayStorageC 9AskToCore9ATPayloadC 0dE6Daemon23ScreenTimeAnswerHandlerV13MessageSourceO
+ _symbolic _____ySS11messageGUID______7payloadtG s23_ContiguousArrayStorageC 9AskToCore9ATPayloadC
+ _type_layout_string 11AskToDaemon14MessagesLookupV
- ___swift_closure_destructor.16Tm
- ___swift_closure_destructor.38Tm
- ___swift_closure_destructor.56Tm
- ___swift_closure_destructor.65Tm
- _symbolic ScCySaySS11messageGUID______10payloadURL_____0C0tG_____G 10Foundation3URLV 9AskToCore9ATPayloadC s5NeverO
- _symbolic So7NSErrorCSgIeyBy_
- _symbolic ______pSgIegg_ s5ErrorP
CStrings:
+ "%s called with question identifier: %s"
+ "AskTo balloon lookup failed for request ID %s. error: %@"
+ "Every matched message for request ID %s failed to parse"
+ "Failed to get the new Messages payload from the extension. error: %@"
+ "Found %ld matches for request ID %s in the AskTo balloon"
+ "Found %ld matches for request ID %s in the legacy ScreenTime balloon"
+ "Found matching AskTo balloon message with GUID %s"
+ "No legacy ScreenTime balloon match for request ID %s; returning the AskTo balloon match. error: %@"
+ "Notifying clients that message compose finished"
+ "Skipping message GUID %s for request ID %s; failed to parse payload. error: %@"
+ "The data for the messages payload obtained from the extension was nil."
+ "Timed out waiting for messagesComposeDidFinish on client with id %s: %@"
+ "findAllMessages(matchingLegacyRequestID:)"
+ "findAllMessages(matchingQuestionIdentifier:)"
+ "findMessagesInAskToBalloon(matching:)"
+ "init(requestID:responderDSID:answer:messagesLookup:legacyMessagesLookup:)"
+ "parsePayload(from:)"
- "Failed to get the new Messages payload from the People extension. error: %@"
- "Found matching question with ID %s in message GUID %s"
- "Inspecting AskTo message with GUID %s for question ID %s"
- "The data for the messages paylaod obtained from the People extension was nil."
- "findAllMessagesInMessagesDatabase(matching:)"
- "init(requestID:responderDSID:answer:)"
```
