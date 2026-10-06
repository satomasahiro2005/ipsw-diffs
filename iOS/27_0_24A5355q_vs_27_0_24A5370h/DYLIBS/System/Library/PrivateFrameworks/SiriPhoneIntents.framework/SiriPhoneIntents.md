## SiriPhoneIntents

> `/System/Library/PrivateFrameworks/SiriPhoneIntents.framework/SiriPhoneIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbedc` | `0xbea0` | **`-0x3c`** |

### Other Changes

```diff

-3600.32.7.0.0
+3600.38.6.0.0
Functions:
~ +[CallHistoryDataSourcePredicate predicateForCallToCallBackWithAnyOfTheseRemoteParticipantHandles:isoCountryCodes:] : 696 -> 692
~ +[CallHistoryDataSourcePredicate predicateForCallsWithAnyOfTheseRemoteParticipantHandles:isoCountryCodes:] : 724 -> 720
~ +[CallHistoryDataSourcePredicate predicateForRemoteParticipantsWithValuesCaseInsensitive:] : 364 -> 360
~ -[CallRecordConverter callRecordsForRecentCalls:withContactsDataSource:withCallProviderManager:withCurrentISOCountryCodes:] : 648 -> 644
~ -[CallRecordConverter callRecordForRecentCall:withContactsDataSource:withCallProviderManager:withCurrentISOCountryCodes:] : 1548 -> 1544
~ +[CHHandle(TUIntentHandler) tu_normalizedCHHandlesFromTUHandle:isoCountryCodes:] : 616 -> 612
~ -[CNContact(TUIntentHandler) tu_phoneNumbersMatchingPersonHandleLabel:] : 368 -> 364
~ -[CNContact(TUIntentHandler) tu_emailAddressesMatchingPersonHandleLabel:] : 368 -> 364
~ -[CNContact(TUIntentHandler) tu_personHandleMatchingHandle:isoCountryCodes:] : 820 -> 812
~ -[INPerson(TelephonyUtilities) tu_allContactIdentifiers] : 444 -> 440
~ -[INPerson(TelephonyUtilities) tu_matchingINPersonHandlesByContactIdentifier] : 496 -> 492
~ -[INPerson(TelephonyUtilities) tu_handlesMatchingPersonWithContactsDataSource:identifierToContactCache:] : 1360 -> 1352
~ -[INPerson(TelephonyUtilities) tu_contactsMatchingIdentifiers:contactsDataSource:identifierToContactCache:] : 1144 -> 1136
~ _$sSp6assign9repeating5countyx_SitFs13_UnsafeBitsetV4WordV_Tgq5 : 28 -> 36
~ _$ss26DefaultStringInterpolationV16SiriPhoneIntentsE06appendC04type4tags8functionyypXp_SayAC6LogTagOGSSSgtF : 420 -> 428
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 268 -> 264
~ _$s16SiriPhoneIntents13SPHCallCenterPAAE12onQueueAsyncyyyxcF : 836 -> 828
```
