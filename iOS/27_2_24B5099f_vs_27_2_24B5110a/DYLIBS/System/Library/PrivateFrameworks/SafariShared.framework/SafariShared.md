## SafariShared

> `/System/Library/PrivateFrameworks/SafariShared.framework/SafariShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b76b0` | `0x2ba020` | **`+0x2970`** |
| `__TEXT.__gcc_except_tab` | `0x1ec3c` | `0x1ef64` | **`+0x328`** |
| `__AUTH_CONST.__objc_const` | `0x28638` | `0x288c0` | **`+0x288`** |
| `__TEXT.__cstring` | `0x23847` | `0x23a07` | **`+0x1c0`** |
| `__TEXT.__objc_methlist` | `0x16184` | `0x162e4` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0xeff8` | `0xf140` | **`+0x148`** |
| `__AUTH_CONST.__cfstring` | `0x1b0e0` | `0x1b1e0` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x16630` | `0x166f8` | **`+0xc8`** |
| `__AUTH.__data` | `0x17b0` | `0x1860` | **`+0xb0`** |
| `__AUTH.__objc_data` | `0x7c78` | `0x7d18` | **`+0xa0`** |
| `__DATA.__data` | `0x5848` | `0x58d8` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x15cb2` | `0x15d42` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0xb4f0` | `0xb560` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0xc1a0` | `0xc1f8` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x21c8` | `0x2218` | **`+0x50`** |
| `__TEXT.__const` | `0xa3a94` | `0xa3ad4` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x18c4` | `0x18f8` | **`+0x34`** |
| `__TEXT.__swift5_capture` | `0x1154` | `0x1178` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x2120` | `0x2140` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1648` | `0x1668` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x374a` | `0x376a` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x768` | `0x780` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1944` | `0x1958` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0xcb8` | `0xcc8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x960` | `0x968` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1a0` | `0x1a4` | **`+0x4`** |

### Other Changes

```diff

-625.2.7.1.0
+625.2.8.10.4

-  Functions: 14802
-  Symbols:   19359
-  CStrings:  6159
+  Functions: 14868
+  Symbols:   19429
+  CStrings:  6173
Symbols:
+ +[WBSHistoryServiceURLCompletionMatchData supportsSecureCoding]
+ +[WBSHistoryVisitsMatchingOriginsPredicate supportsSecureCoding]
+ -[WBSHistory getAllPebbleItemsWithCompletionHandler:]
+ -[WBSHistory getAllPebbleVisitHostsWithCompletionHandler:]
+ -[WBSHistory pebbleItemVisitedAtURLString:title:date:wasFailure:httpNonGet:statusCode:]
+ -[WBSHistoryActivityThrottler initWithLimitPerSecond:windowLength:]
+ -[WBSHistoryServiceStore getVisitsWithOrigin:completionHandler:]
+ -[WBSHistoryServiceURLCompletionMatchData _initWithLastVisitWasFailure:visitWasFromThisDevice:visitWasClientError:visitCount:vistCountScore:lastVisitTime:autocompleteTriggersData:autocompleteTriggersDataLength:visitWasFromPebble:]
+ -[WBSHistoryServiceURLCompletionMatchData encodeWithCoder:]
+ -[WBSHistoryServiceURLCompletionMatchData initWithCoder:]
+ -[WBSHistoryServiceURLCompletionMatchData initWithLastVisitWasFailure:visitWasFromThisDevice:visitWasClientError:visitWasFromPebble:]
+ -[WBSHistoryServiceURLCompletionMatchData visitWasFromPebble]
+ -[WBSHistoryServiceURLCompletionMatchEntry visitWasFromPebble]
+ -[WBSHistoryURLCompletionMatchData visitWasFromPebble]
+ -[WBSHistoryURLCompletionSession getMatchDataForTypedString:filterResultsUsingProfileIdentifier:options:completionHandler:]
+ -[WBSHistoryVisitsMatchingOriginsPredicate .cxx_destruct]
+ -[WBSHistoryVisitsMatchingOriginsPredicate description]
+ -[WBSHistoryVisitsMatchingOriginsPredicate encodeWithCoder:]
+ -[WBSHistoryVisitsMatchingOriginsPredicate evaluateServiceVisit:]
+ -[WBSHistoryVisitsMatchingOriginsPredicate evaluateVisit:]
+ -[WBSHistoryVisitsMatchingOriginsPredicate initWithCoder:]
+ -[WBSHistoryVisitsMatchingOriginsPredicate initWithOrigins:]
+ -[WBSHistoryVisitsMatchingOriginsPredicate statementForDatabase:cache:fetchOptions:error:]
+ -[WBSTrialSearchParameters setShouldBoostPebbleItems:]
+ -[WBSTrialSearchParameters shouldBoostPebbleItems]
+ -[WBSURLCompletionSessionProxy getMatchDataForTypedString:filterResultsUsingProfileIdentifier:options:completionHandler:]
+ GCC_except_table207
+ _OBJC_CLASS_$_WBSHistoryVisitsMatchingOriginsPredicate
+ _OBJC_IVAR_$_WBSHistory._pebbleEntryCreationThrottler
+ _OBJC_IVAR_$_WBSHistoryActivityThrottler._activityLimitPerWindow
+ _OBJC_IVAR_$_WBSHistoryActivityThrottler._windowLength
+ _OBJC_IVAR_$_WBSHistoryVisitsMatchingOriginsPredicate._origins
+ _OBJC_IVAR_$_WBSTrialSearchParameters._shouldBoostPebbleItems
+ _OBJC_METACLASS_$_WBSHistoryVisitsMatchingOriginsPredicate
+ _WBSCloudBookmarkListRecordNamePinnedSuggestions
+ __DATA__TtC12SafariSharedP33_11F4C4CAE45695932A6D2A3FF44DA9F329WBSForegroundDonationThrottle
+ __IVARS__TtC12SafariSharedP33_11F4C4CAE45695932A6D2A3FF44DA9F329WBSForegroundDonationThrottle
+ __METACLASS_DATA__TtC12SafariSharedP33_11F4C4CAE45695932A6D2A3FF44DA9F329WBSForegroundDonationThrottle
+ __OBJC_$_CLASS_METHODS_WBSHistoryServiceURLCompletionMatchData
+ __OBJC_$_CLASS_METHODS_WBSHistoryVisitsMatchingOriginsPredicate
+ __OBJC_$_CLASS_PROP_LIST_WBSHistoryServiceURLCompletionMatchData
+ __OBJC_$_CLASS_PROP_LIST_WBSHistoryVisitsMatchingOriginsPredicate
+ __OBJC_$_INSTANCE_METHODS_WBSHistoryVisitsMatchingOriginsPredicate
+ __OBJC_$_INSTANCE_VARIABLES_WBSHistoryVisitsMatchingOriginsPredicate
+ __OBJC_$_PROP_LIST_WBSHistoryVisitsMatchingOriginsPredicate
+ __OBJC_CLASS_PROTOCOLS_$_WBSHistoryVisitsMatchingOriginsPredicate
+ __OBJC_CLASS_RO_$_WBSHistoryVisitsMatchingOriginsPredicate
+ __OBJC_METACLASS_RO_$_WBSHistoryVisitsMatchingOriginsPredicate
+ __ZL43compareCompletionMatchesAndBoostPebbleItemsRKN3WTF6RefPtrIN12SafariShared33BookmarkAndHistoryCompletionMatchENS_12RawPtrTraitsIS2_EENS_21DefaultRefDerefTraitsIS2_EEEES9_
+ __ZN12SafariShared18URLCompletionEntry6updateEP8NSStringdbbbb
+ __ZNK12SafariShared33BookmarkAndHistoryCompletionMatch7compareEPS0_b
+ ___121-[WBSURLCompletionSessionProxy getMatchDataForTypedString:filterResultsUsingProfileIdentifier:options:completionHandler:]_block_invoke
+ ___123-[WBSHistoryURLCompletionSession getMatchDataForTypedString:filterResultsUsingProfileIdentifier:options:completionHandler:]_block_invoke
+ ___123-[WBSHistoryURLCompletionSession getMatchDataForTypedString:filterResultsUsingProfileIdentifier:options:completionHandler:]_block_invoke_2
+ ___123-[WBSHistoryURLCompletionSession getMatchDataForTypedString:filterResultsUsingProfileIdentifier:options:completionHandler:]_block_invoke_3
+ ___123-[WBSHistoryURLCompletionSession getMatchDataForTypedString:filterResultsUsingProfileIdentifier:options:completionHandler:]_block_invoke_4
+ ___123-[WBSHistoryURLCompletionSession getMatchDataForTypedString:filterResultsUsingProfileIdentifier:options:completionHandler:]_block_invoke_5
+ ___53-[WBSHistory getAllPebbleItemsWithCompletionHandler:]_block_invoke
+ ___53-[WBSHistory getAllPebbleItemsWithCompletionHandler:]_block_invoke_2
+ ___53-[WBSHistory getAllPebbleItemsWithCompletionHandler:]_block_invoke_3
+ ___53-[WBSHistory getAllPebbleItemsWithCompletionHandler:]_block_invoke_4
+ ___53-[WBSHistory getAllPebbleItemsWithCompletionHandler:]_block_invoke_5
+ ___53-[WBSHistory getAllPebbleItemsWithCompletionHandler:]_block_invoke_6
+ ___58-[WBSHistory getAllPebbleVisitHostsWithCompletionHandler:]_block_invoke
+ ___58-[WBSHistory getAllPebbleVisitHostsWithCompletionHandler:]_block_invoke_2
+ ___64-[WBSHistoryServiceStore getVisitsWithOrigin:completionHandler:]_block_invoke
+ ___block_descriptor_40_ea8_32bs_e15_v16?0"NSSet"8ls32l8
+ ___block_descriptor_40_ea8_32s_e40_"WBSHistoryItem"16?0"WBSHistoryItem"8ls32l8
+ ___block_descriptor_48_ea8_32s40s_e49_v16?0"WBSHistoryServiceURLCompletionMatchData"8ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48bs_e55_v24?0"<WBSURLCompletionSessionProtocol>"8"NSError"16ls48l8s32l8s40l8
+ ___block_descriptor_72_ea8_32s40s48bs56r_e5_v8?0lr56l8s32l8s40l8s48l8
+ ___swift_closure_destructor.253Tm
+ _symbolic So6NSLockC
+ _symbolic _____ 12SafariShared29WBSForegroundDonationThrottle33_11F4C4CAE45695932A6D2A3FF44DA9F3LLC
- -[WBSHistoryServiceURLCompletionMatchData initWithLastVisitWasFailure:visitWasFromThisDevice:visitWasClientError:]
- __ZN12SafariShared18URLCompletionEntry6updateEP8NSStringdbbb
- __ZNK12SafariShared33BookmarkAndHistoryCompletionMatch7compareEPS0_
- ___swift_closure_destructor.246Tm
CStrings:
+ "-[WBSHistoryVisitsMatchingOriginsPredicate statementForDatabase:cache:fetchOptions:error:]"
+ "8625.2.8.10.4"
+ "<%@: %p; origins.count = %zu>"
+ "@\"WBSHistoryItem\"16@?0@\"WBSHistoryItem\"8"
+ "Did not create Pebble history item for %{sensitive}@ because of excessive history activity requests"
+ "Failed to get visits with origin: %{public}@"
+ "SELECT * FROM history_visits WHERE history_visits.origin IN (%@) ORDER BY visit_time DESC LIMIT 100"
+ "Skipping %{public}s donation: last donation was %{public}s ago, which is within the %{public}ld-minute throttle window."
+ "WBSHistoryURLCompletionSession.enumerationQueue"
+ "autocompleteTriggers"
+ "entries"
+ "origins"
+ "private-browsing-foreground"
+ "visitWasClientError"
+ "visitWasFromPebble"
+ "visitWasFromThisDevice"
- "8625.2.7.1"
- "Skipping app-foreground donation: last donation was %{public}s ago, which is within the %{public}ld-minute throttle window."
```
