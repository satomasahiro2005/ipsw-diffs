## EventKit

> `/System/Library/Frameworks/EventKit.framework/EventKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a1644` | `0x1a3040` | **`+0x19fc`** |
| `__DATA_CONST.__const` | `0x47f8` | `0x48e0` | **`+0xe8`** |
| `__AUTH_CONST.__objc_const` | `0x18548` | `0x18628` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0x4470` | `0x4500` | **`+0x90`** |
| `__TEXT.__cstring` | `0xbddf` | `0xbe6f` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x25a8` | `0x2618` | **`+0x70`** |
| `__DATA.__data` | `0x2830` | `0x2890` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xef78` | `0xefd8` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x3928` | `0x3978` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x15a74` | `0x15ac4` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x6730` | `0x6780` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x1a08` | `0x1a50` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x1942` | `0x1988` | **`+0x46`** |
| `__DATA_CONST.__objc_selrefs` | `0xae60` | `0xae98` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x1400` | `0x1430` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0xd64` | `0xd7c` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x264` | `0x278` | **`+0x14`** |
| `__TEXT.__const` | `0x4810` | `0x4820` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x1a4` | `0x1a8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xe8` | `0xec` | **`+0x4`** |

### Other Changes

```diff

-1973.0.0.0.0
+1976.0.0.0.0

-  Functions: 10666
-  Symbols:   13231
-  CStrings:  2666
+  Functions: 10688
+  Symbols:   13256
+  CStrings:  2669
Symbols:
+ -[EKAutocompleter _filterBlockedResults:completion:]
+ -[EKLocationSearchModel _handleAvailabilityResults:addressToRoomMap:availabilityCache:notifyType:forOperation:]
+ -[EKLocationSearchModel _requestAvailabilityForConferenceRooms:eventID:source:dateRange:addressToRoomMap:availabilityCache:operationQueue:operationDomain:notifyType:]
+ -[EKLocationSearchModel _requestAvailabilityForRecentsConferenceRooms:]
+ -[EKLocationSearchModel _updateAvailabilityForRecentsConferenceRooms]
+ -[EKObject(Shared) _setCachedMeltedObject:forKey:]
+ -[EKObject(Shared) _setCachedValue:forKey:]
+ -[EKObject(Shared) emptyValueCache]
+ -[EKRecentContactSearchResult resolvedConferenceRoom]
+ -[EKRecentContactSearchResult setResolvedConferenceRoom:]
+ -[EKVirtualConference textRepresentation]
+ GCC_except_table115
+ GCC_except_table131
+ GCC_except_table149
+ GCC_except_table169
+ GCC_except_table203
+ GCC_except_table210
+ GCC_except_table43
+ GCC_except_table52
+ GCC_except_table55
+ GCC_except_table77
+ GCC_except_table78
+ GCC_except_table93
+ _OBJC_CLASS_$_CalBlockListFilter
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _OBJC_IVAR_$_EKAutocompleter._pendingBlockedResultFilterCount
+ _OBJC_IVAR_$_EKAutocompleter._pendingBlockedResultFilterLock
+ _OBJC_IVAR_$_EKLocationSearchModel._conferenceRoomAvailabilityByAddress
+ _OBJC_IVAR_$_EKLocationSearchModel._recentsConferenceRoomAddressesToConferenceRooms
+ _OBJC_IVAR_$_EKLocationSearchModel._recentsConferenceRoomOperationQueue
+ _OBJC_IVAR_$_EKRecentContactSearchResult._resolvedConferenceRoom
+ ___111-[EKLocationSearchModel _handleAvailabilityResults:addressToRoomMap:availabilityCache:notifyType:forOperation:]_block_invoke
+ ___111-[EKLocationSearchModel _handleAvailabilityResults:addressToRoomMap:availabilityCache:notifyType:forOperation:]_block_invoke_2
+ ___166-[EKLocationSearchModel _requestAvailabilityForConferenceRooms:eventID:source:dateRange:addressToRoomMap:availabilityCache:operationQueue:operationDomain:notifyType:]_block_invoke
+ ___166-[EKLocationSearchModel _requestAvailabilityForConferenceRooms:eventID:source:dateRange:addressToRoomMap:availabilityCache:operationQueue:operationDomain:notifyType:]_block_invoke_2
+ ___166-[EKLocationSearchModel _requestAvailabilityForConferenceRooms:eventID:source:dateRange:addressToRoomMap:availabilityCache:operationQueue:operationDomain:notifyType:]_block_invoke_3
+ ___166-[EKLocationSearchModel _requestAvailabilityForConferenceRooms:eventID:source:dateRange:addressToRoomMap:availabilityCache:operationQueue:operationDomain:notifyType:]_block_invoke_4
+ ___166-[EKLocationSearchModel _requestAvailabilityForConferenceRooms:eventID:source:dateRange:addressToRoomMap:availabilityCache:operationQueue:operationDomain:notifyType:]_block_invoke_5
+ ___35-[EKObject(Shared) emptyValueCache]_block_invoke
+ ___52-[EKAutocompleter _filterBlockedResults:completion:]_block_invoke
+ ___52-[EKAutocompleter _filterBlockedResults:completion:]_block_invoke_2
+ ___55-[EKAutocompleter autocompleteFetch:didReceiveResults:]_block_invoke
+ ___block_descriptor_120_e8_32s40s48s56s64s72s80s88s96s104s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8
+ ___block_descriptor_32_e40_"NSString"16?0"CNAutocompleteResult"8l
+ ___block_descriptor_56_e8_32s40s48s_e33_v32?0"EKConferenceRoom"8Q16^B24ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_72_e8_32s40s48s56w_e22_v16?0"NSDictionary"8lw56l8s32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48w56w_e5_v8?0lw48l8w56l8s32l8s40l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72r_e5_v8?0ls32l8s40l8s48l8s56l8r72l8s64l8
+ ___block_descriptor_80_e8_32s40s48s56s64s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ _symbolic SDySS_____G 10Foundation20PersonNameComponentsV
+ _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
+ _symbolic Say_____G So17OS_dispatch_queueC8DispatchE10AttributesV
+ _symbolic ScCySDySS_____G_____G 10Foundation20PersonNameComponentsV s5NeverO
+ _symbolic _____ySS_____G s18_DictionaryStorageC 10Foundation20PersonNameComponentsV
- +[EKFeatureSet _currentSplashScreenVersion]
- +[EKFeatureSet mustDisplaySplashScreenToUser]
- +[EKFeatureSet userAcknowledgedSplashScreen]
- -[EKLocationSearchModel _handleAvailabilityResults:forOperation:]
- -[EKObject(Shared) _sharedInit]
- GCC_except_table118
- GCC_except_table134
- GCC_except_table138
- GCC_except_table166
- GCC_except_table171
- GCC_except_table200
- GCC_except_table207
- GCC_except_table22
- GCC_except_table27
- GCC_except_table28
- GCC_except_table50
- GCC_except_table53
- GCC_except_table58
- GCC_except_table75
- GCC_except_table86
- _CFNotificationCenterGetDarwinNotifyCenter
- _CFNotificationCenterPostNotification
- ___55-[EKLocationSearchModel _addDiscoveredConferenceRooms:]_block_invoke_2
- ___55-[EKLocationSearchModel _addDiscoveredConferenceRooms:]_block_invoke_3
- ___55-[EKLocationSearchModel _addDiscoveredConferenceRooms:]_block_invoke_4
- ___55-[EKLocationSearchModel _addDiscoveredConferenceRooms:]_block_invoke_5
- ___65-[EKLocationSearchModel _handleAvailabilityResults:forOperation:]_block_invoke
- ___65-[EKLocationSearchModel _handleAvailabilityResults:forOperation:]_block_invoke_2
- ___block_descriptor_48_e8_32s40s_e33_v32?0"EKConferenceRoom"8Q16^B24ls32l8s40l8
- ___block_descriptor_56_e8_32s40w48w_e5_v8?0lw40l8w48l8s32l8
- ___block_descriptor_80_e8_32s40s48s56s64s72r_e5_v8?0ls32l8s40l8s48l8s56l8s64l8r72l8
CStrings:
+ "@\"NSString\"16@?0@\"CNAutocompleteResult\"8"
+ "Not issuing recents availability request because the source does not support it: [%@]"
+ "com.apple.calendar.intelligentScheduler.contactsLookup"
+ "suggestedAttendees(for:source:limit:)"
+ "\xf0\xf0\x81"
- "1"
- "\xf0\xf0Q"
```
