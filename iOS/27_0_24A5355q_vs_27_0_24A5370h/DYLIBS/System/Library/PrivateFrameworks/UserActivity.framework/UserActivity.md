## UserActivity

> `/System/Library/PrivateFrameworks/UserActivity.framework/UserActivity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x412a0` | `0x411a4` | **`-0xfc`** |
| `__TEXT.__unwind_info` | `0x1788` | `0x1790` | **`+0x8`** |

### Other Changes

```diff

-625.0.0.0.0
+626.0.0.0.0
Functions:
~ -[UAUserActivity setParentUserActivity:] : 460 -> 456
~ -[UAUserActivity setDirty:] : 1460 -> 1456
~ __ZL7recurseP11objc_objectU13block_pointerFbS0_E : 1188 -> 1176
~ __ZL36objectIsOfAcceptableClassForUserInfoP11objc_object : 800 -> 780
~ -[UAUserActivity dealloc] : 696 -> 692
~ -[UAUserActivity invalidate] : 1144 -> 1140
~ -[UAUserActivity resignCurrent] : 1176 -> 1172
~ -[UAUserActivityInfo initWithCoder:] : 1976 -> 1972
~ ___91-[UAUserActivity(Internal) callWillSaveDelegateIfDirtyAndPackageUpData:options:clearDirty:]_block_invoke : 2736 -> 2724
~ -[UAUserActivity becomeCurrent] : 1276 -> 1272
~ -[UAUserActivityManager makeActive:] : 1644 -> 1636
~ -[UAUserActivity setTargetContentIdentifier:] : 560 -> 556
~ -[UAUserActivity(Internal) copyWithNewUUID:] : 2252 -> 2248
~ -[UAUserActivity synchronouslyEncodeUserInfo:options:completionHandler:] : 2676 -> 2672
~ -[UAUserActivity(Internal) userActivityInfoForSelfWithPayload:options:] : 1980 -> 1976
~ __ZL19deepMutableCopyOnceP11objc_objectP19NSMutableDictionary : 1236 -> 1224
~ __ZN13UAMessagePack11writeObjectEP11objc_object : 1828 -> 1816
~ _trimmedHexStringForData : 512 -> 508
~ ___71-[UAUserActivity(Internal) userActivityInfoForSelfWithPayload:options:]_block_invoke : 704 -> 700
~ ___39+[UAUserActivityManager defaultManager]_block_invoke_2 : 768 -> 764
~ _userActivityInfoOptionsDictionaryString : 904 -> 900
~ ___97-[UAUserActivityManager fetchUUID:intervalToWaitForDocumentSynchonization:withCompletionHandler:]_block_invoke.37 : 1980 -> 1992
~ -[UAUserActivity(UAUserActivityAppLinksEncoding) initWithUserActivityStrings:optionalString:tertiaryData:options:] : 2964 -> 2960
~ -[UAUserActivity setWebpageURL:] : 712 -> 708
~ -[UAUserActivityInfo description] : 1532 -> 1528
~ -[UAUserActivity(UAUserActivityPayloadServicesSupport) setPayload:object:identifier:dirty:] : 780 -> 776
~ -[UAUserActivityInfo _createUserActivityStrings:secondaryString:optionalData:] : 2236 -> 2228
~ +[UAUserActivity(UAUserActivityAppLinksEncoding) _encodeToString:] : 2064 -> 2052
~ _sortedArrayOfNSStringValues : 364 -> 360
~ -[UAUserActivity decodeUserInfo:options:] : 2984 -> 2980
~ -[UAUserActivity(UAUserActivitySiriActions) setPersistentIdentifier:] : 504 -> 500
~ ___57+[UAUserActivity userActivityFromUUID:timeout:withError:]_block_invoke : 136 -> 132
~ -[UAUserActivity _setWebpageURL:throwOnFailure:] : 796 -> 792
~ -[UAUserActivity unarchiveURL:error:] : 1144 -> 1140
~ __ZL17recurseAndReplaceP11objc_objectU13block_pointerFbS0_EU13block_pointerFS0_S0_E : 2200 -> 2188
~ ___109-[UAUserActivity(Internal) callWillSaveDelegateIfDirtyAndPackageUpData:options:clearDirty:completionHandler:]_block_invoke : 2736 -> 2724
~ __ZL22sortedArrayIfSameClassP7NSArray : 476 -> 472
~ _copyHexStringForData : 252 -> 264
~ _cmp_strerror : 48 -> 44
~ _cmp_read_str : 212 -> 208
~ -[UASharedPasteboardInfo description] : 412 -> 408
~ -[UASharedPasteboardManager typeIsDisallowedForSending:] : 428 -> 424
~ -[UASharedPasteboardManager typeIsDisallowedForReceiving:] : 428 -> 424
~ -[UASharedPasteboardManager sendUpdateToServer:] : 2036 -> 2032
~ ___79-[UASharedPasteboardManager writeLocalPasteboardToFile:itemDir:withCompletion:]_block_invoke : 984 -> 980
~ -[UASharedPasteboardManager pickupLocalChanges:iterNumber:cloneDir:completionHandler:] : 2336 -> 2332
~ -[UASharedPasteboardManager serializeItem:intoInfo:withFile:intoDir:] : 1244 -> 1240
~ ___61-[UASharedPasteboardManager serializeType:intoInfo:withFile:]_block_invoke_2 : 2864 -> 2860
~ ___83-[UASharedPasteboardManager requestRemotePasteboardTypesForProcess:withCompletion:]_block_invoke.192 : 1752 -> 1748
~ ___82-[UASharedPasteboardManager requestRemotePasteboardDataForProcess:withCompletion:]_block_invoke.204 : 2908 -> 2904
~ +[UAUserActivityManager _determineMatchingApplicationBundleIdentfierWithOptionsForActivityType:dynamicType:kind:teamIdentifier:] : 928 -> 924
~ -[UAPasteboardGeneration addItem:] : 428 -> 424
~ ___49-[UABestAppSuggestionManager bestAppSuggestions:]_block_invoke.21 : 856 -> 852
~ -[UABestAppSuggestionManager queueFetchOfPayloadForBestAppSuggestion:] : 536 -> 548
~ +[UASharedPasteboard localPasteboardDidAddItems:forGeneration:] : 476 -> 472
```
