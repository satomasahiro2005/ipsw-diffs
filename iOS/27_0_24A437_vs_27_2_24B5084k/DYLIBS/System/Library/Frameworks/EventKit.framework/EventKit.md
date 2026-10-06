## EventKit

> `/System/Library/Frameworks/EventKit.framework/EventKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a30bc` | `0x1a3eb8` | **`+0xdfc`** |
| `__TEXT.__oslogstring` | `0xefd8` | `0xf1b4` | **`+0x1dc`** |
| `__AUTH_CONST.__objc_const` | `0x18628` | `0x187c8` | **`+0x1a0`** |
| `__TEXT.__objc_methlist` | `0x15ac4` | `0x15b9c` | **`+0xd8`** |
| `__TEXT.__cstring` | `0xbe6f` | `0xbdbf` | **`-0xb0`** |
| `__AUTH.__objc_data` | `0x34d0` | `0x3520` | **`+0x50`** |
| `__DATA.__data` | `0x2890` | `0x28e0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xae98` | `0xaee8` | **`+0x50`** |
| `__TEXT.__const` | `0x4820` | `0x4870` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x6780` | `0x67c0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x48e0` | `0x4908` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x3978` | `0x3950` | **`-0x28`** |
| `__TEXT.__swift5_reflstr` | `0x1261` | `0x1271` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xd7c` | `0xd88` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x7b0` | `0x7b8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x250` | `0x258` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x530` | `0x538` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x2618` | `0x2614` | **`-0x4`** |

### Other Changes

```diff

-1976.0.100.0.0
+1976.1.3.0.0

-  Functions: 10688
-  Symbols:   13255
-  CStrings:  2669
+  Functions: 10703
+  Symbols:   13284
+  CStrings:  2672
Symbols:
+ +[EKAutocompletePendingSearch _shouldReturnResultForEvent:considerReadonlyEvents:enforceRecencyCutoff:ignoreScheduledEvents:initialEvent:]
+ +[EKAutocompleteSearch pasteboardResultsFromProvider:ignoreScheduledEvents:]
+ +[EKEventStore _isSuggestedEvent:confirmed:uniqueKey:]
+ +[EKEventSuggestionGenerator eventSuggestionsFromPasteboardItemProvider:referenceDate:]
+ -[EKEventStore _suggestionsService]
+ -[EKEventStore gatherConfirmedSuggestions:rejectedSuggestions:deletedSuggestions:fromInsertedObjects:deletedObjects:]
+ -[EKEventStore lastDatabaseCommitTimestamp]
+ -[EKEventStore notifySuggestionsOfConfirmedSuggestions:rejectedSuggestions:deletedSuggestions:]
+ -[EKEventStore setSuggestionsServiceOverride:]
+ -[EKEventStore shouldNotifySuggestionsOfChangesToSuggestedEvents]
+ -[EKEventStore suggestionsServiceOverride]
+ -[EKWeakLinkedSuggestionsService .cxx_destruct]
+ -[EKWeakLinkedSuggestionsService confirmEventByRecordId:withCompletion:]
+ -[EKWeakLinkedSuggestionsService deleteEventByRecordId:withCompletion:]
+ -[EKWeakLinkedSuggestionsService eventFromUniqueId:withCompletion:]
+ -[EKWeakLinkedSuggestionsService init]
+ -[EKWeakLinkedSuggestionsService rejectEventByRecordId:withCompletion:]
+ GCC_except_table438
+ GCC_except_table447
+ GCC_except_table449
+ GCC_except_table459
+ GCC_except_table463
+ GCC_except_table466
+ GCC_except_table469
+ GCC_except_table473
+ GCC_except_table476
+ GCC_except_table502
+ GCC_except_table504
+ GCC_except_table536
+ GCC_except_table550
+ GCC_except_table573
+ GCC_except_table587
+ GCC_except_table590
+ GCC_except_table594
+ GCC_except_table609
+ GCC_except_table645
+ GCC_except_table687
+ GCC_except_table693
+ GCC_except_table711
+ GCC_except_table716
+ GCC_except_table719
+ GCC_except_table726
+ GCC_except_table733
+ GCC_except_table741
+ GCC_except_table749
+ GCC_except_table759
+ GCC_except_table768
+ GCC_except_table772
+ _OBJC_CLASS_$_EKWeakLinkedSuggestionsService
+ _OBJC_IVAR_$_EKEventStore._lastDatabaseCommitTimestamp
+ _OBJC_IVAR_$_EKEventStore._suggestionsServiceOverride
+ _OBJC_IVAR_$_EKWeakLinkedSuggestionsService._service
+ _OBJC_METACLASS_$_EKWeakLinkedSuggestionsService
+ __OBJC_$_INSTANCE_METHODS_EKWeakLinkedSuggestionsService
+ __OBJC_$_INSTANCE_VARIABLES_EKWeakLinkedSuggestionsService
+ __OBJC_$_PROP_LIST_EKWeakLinkedSuggestionsService
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_EKSuggestionsServiceEventsProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_EKSuggestionsServiceEventsProtocol
+ __OBJC_$_PROTOCOL_REFS_EKSuggestionsServiceEventsProtocol
+ __OBJC_CLASS_PROTOCOLS_$_EKWeakLinkedSuggestionsService
+ __OBJC_CLASS_RO_$_EKWeakLinkedSuggestionsService
+ __OBJC_LABEL_PROTOCOL_$_EKSuggestionsServiceEventsProtocol
+ __OBJC_METACLASS_RO_$_EKWeakLinkedSuggestionsService
+ __OBJC_PROTOCOL_$_EKSuggestionsServiceEventsProtocol
+ ___43-[EKEventStore lastDatabaseCommitTimestamp]_block_invoke
+ ___95-[EKEventStore notifySuggestionsOfConfirmedSuggestions:rejectedSuggestions:deletedSuggestions:]_block_invoke
+ ___95-[EKEventStore notifySuggestionsOfConfirmedSuggestions:rejectedSuggestions:deletedSuggestions:]_block_invoke_2
+ ___block_descriptor_120_e8_32s40s48s56r64r72r80r88r96r104r112r_e124_v56?0i8"NSDictionary"12"NSDictionary"20"NSDictionary"28"CADInMemoryChangeTimestamp"36"CADInMemoryChangeTimestamp"44B52lr56l8r64l8s32l8s40l8r72l8r80l8r88l8r96l8r104l8r112l8s48l8
+ ___block_descriptor_40_e8_32s_e61_q24?0"CalSpotlightQueryResult"8"CalSpotlightQueryResult"16ls32l8
+ ___block_descriptor_72_e8_32s40s48r56r64r_e23_v32?0"NSDate"8Q16^B24ls32l8r48l8r56l8s40l8r64l8
- +[EKEventStore _isConfirmedSuggestedEvent:uniqueKey:]
- -[EKEventStore _SGSuggestionsServiceClass]
- -[EKEventStore confirmSuggestedEvent:]
- -[EKEventStore lastDatabaseTimestamp]
- GCC_except_table448
- GCC_except_table452
- GCC_except_table454
- GCC_except_table464
- GCC_except_table468
- GCC_except_table474
- GCC_except_table478
- GCC_except_table481
- GCC_except_table507
- GCC_except_table509
- GCC_except_table541
- GCC_except_table562
- GCC_except_table571
- GCC_except_table585
- GCC_except_table588
- GCC_except_table592
- GCC_except_table607
- GCC_except_table639
- GCC_except_table685
- GCC_except_table689
- GCC_except_table707
- GCC_except_table714
- GCC_except_table717
- GCC_except_table724
- GCC_except_table731
- GCC_except_table739
- GCC_except_table743
- GCC_except_table753
- GCC_except_table766
- GCC_except_table770
- ___37-[EKEventStore deleteSuggestedEvent:]_block_invoke
- ___37-[EKEventStore deleteSuggestedEvent:]_block_invoke_2
- ___37-[EKEventStore lastDatabaseTimestamp]_block_invoke
- ___38-[EKEventStore confirmSuggestedEvent:]_block_invoke
- ___38-[EKEventStore confirmSuggestedEvent:]_block_invoke_2
- ___block_descriptor_112_e8_32s40s48r56r64r72r80r88r96r104r_e93_v48?0i8"NSDictionary"12"NSDictionary"20"NSDictionary"28"CADInMemoryChangeTimestamp"36B44lr48l8r56l8s32l8s40l8r64l8r72l8r80l8r88l8r96l8r104l8
- ___block_descriptor_80_e8_32s40s48s56r64r72r_e23_v32?0"NSDate"8Q16^B24ls32l8s40l8r56l8r64l8s48l8r72l8
CStrings:
+ "Found a deleted suggested event - notifying suggestions."
+ "Found a newly-confirmed suggested event - notifying suggestions."
+ "Found a rejected suggested event - notifying suggestions."
+ "Ignoring added suggested event that does not have a unique key"
+ "Ignoring removed suggested event that did not have a unique key"
+ "Invalidating new conference because event was deleted"
+ "Invalidating new conference because event was rolled back"
+ "Invalidating old conference because it is being replaced and was never committed"
+ "Not checking whether URL %@ needs invalidating because eventStore is nil"
+ "Not notifying suggestions about a confirmed event that moved from one account to another"
+ "confirmEventByRecordId failed with error %@"
+ "deleteEventByRecordId failed with error %@"
+ "q24@?0@\"CalSpotlightQueryResult\"8@\"CalSpotlightQueryResult\"16"
+ "rejectEventByRecordId failed with error %@"
+ "v56@?0i8@\"NSDictionary\"12@\"NSDictionary\"20@\"NSDictionary\"28@\"CADInMemoryChangeTimestamp\"36@\"CADInMemoryChangeTimestamp\"44B52"
- "%s - Notifying suggestions we have deleted previously confirmed event %@"
- "%s - Notifying suggestions we have ignored event %@"
- "%s - confirmEventByRecordId failed with error %@"
- "%s - deleteEventByRecordId failed with error %@"
- "%s - event has no suggestions key"
- "%s - rejectEventByRecordId failed with error %@"
- "-[EKEventStore _commitObjectsWithIdentifiers:error:]"
- "-[EKEventStore _commitObjectsWithIdentifiers:error:]_block_invoke_2"
- "-[EKEventStore confirmSuggestedEvent:]"
- "-[EKEventStore confirmSuggestedEvent:]_block_invoke_2"
- "-[EKEventStore deleteSuggestedEvent:]_block_invoke_2"
- "v48@?0i8@\"NSDictionary\"12@\"NSDictionary\"20@\"NSDictionary\"28@\"CADInMemoryChangeTimestamp\"36B44"
```
