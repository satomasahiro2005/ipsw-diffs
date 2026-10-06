## PhoneKit

> `/System/Library/PrivateFrameworks/PhoneKit.framework/PhoneKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19c2c` | `0x19b80` | **`-0xac`** |

### Other Changes

```diff

-139.100.27.2.9
+143.100.11.2.1
Functions:
~ -[PKRecentsController recentCallsChangedFromCachedRecentCalls:callHistoryControllerRecentCalls:] : 580 -> 572
~ -[PKRecentsController recentCallsDeletedFromCachedRecentCall:callHistoryControllerRecentCalls:] : 584 -> 576
~ -[PKRecentsController contactHandlesForRecentCalls:] : 492 -> 488
~ -[PKRecentsController localizedSubtitleForRecentCall:] : 2140 -> 2136
~ -[PKRecentsController fetchMutableItemForRecentCall:numberOfOccurences:] : 5184 -> 5176
~ -[PKRecentsController fetchContactsForHandles:] : 988 -> 980
~ ___67-[PKRecentsController contactByHandleForRecentCall:keyDescriptors:]_block_invoke : 388 -> 384
~ -[TUDialRequest(PhoneKit) dialRequestByResolvingDialTypeUsingSenderIdentityClient:] : 740 -> 736
~ -[CHRecentCall(PhoneKit) ph_uniqueIDs] : 388 -> 384
~ +[CNMutableContact(PhoneKit) suggestedContactForHandle:isoCountryCode:metadataCache:] : 596 -> 592
~ -[CNContact(PhoneKit) labeledValueForEmailAddress:] : 392 -> 388
~ -[CNContact(PhoneKit) labeledValueForPhoneNumber:] : 392 -> 388
~ -[CNContact(PhoneKit) labeledValueForSocialProfileWithUsername:] : 400 -> 396
~ -[NSString(MobilePhoneAdditions) _encodedDialerStringSkippingUnmappedCharacters:] : 948 -> 944
~ -[NSString(MobilePhoneAdditions) processNumberInLatin:] : 520 -> 516
~ -[NSString(MobilePhoneAdditions) attributedStringToHighlightText:primaryColour:secondaryColour:style:] : 832 -> 828
~ -[NSString(MobilePhoneAdditions) _indexSetToHighlightDigitsInText:] : 856 -> 840
~ -[NSString(MobilePhoneAdditions) _stringForLastFourDigitMatch] : 460 -> 456
~ -[CNContactStore(PhoneKit) contactsForHandles:keyDescriptors:alwaysUnifyLabeledValues:] : 1216 -> 1212
~ -[CNContactStore(PhoneKit) __contactsForHandles:keyDescriptors:alwaysUnifyLabeledValues:] : 656 -> 652
~ -[PKRecentsController performJoinRequestForRecentCall:overrideProvider:] : 1028 -> 1024
~ -[PKRecentsController notifyDelegatesRecentsController:didUpdateCalls:] : 668 -> 664
~ ___81-[PKRecentsController notifyDelegatesRecentsControllerDidUpdateAcceptedContacts:]_block_invoke : 424 -> 420
~ -[PKRecentsController notifyDelegatesRecentsController:didChangeCalls:] : 472 -> 468
~ -[PKRecentsController notifyDelegatesRecentsController:didChangeUnreadCallCount:] : 444 -> 440
~ -[PKRecentsController notifyDelegatesRecentsControllerDidChangeMessages:] : 440 -> 436
~ -[PKRecentsController contactForHandle:] : 476 -> 472
~ -[PKRecentsController contactsByHandleForRecentCall:keyDescriptors:] : 1420 -> 1412
~ ___51-[PKRecentsController fetchMetadataForRecentCalls:]_block_invoke_2 : 464 -> 460
~ ___56-[PKRecentsController fetchBlockedStatusForRecentCalls:]_block_invoke_2 : 668 -> 664
~ -[PKRecentsController populateItemCacheForRecentCalls:] : 420 -> 416
~ -[PKRecentsController metadataItemsForRecentCall:] : 388 -> 384
~ ___74-[PKRecentsController handleTUMetadataCacheDidFinishUpdatingNotification:]_block_invoke : 488 -> 484
~ -[PKRecentsController localizedSubtitleForRecentEmergencyCall:] : 992 -> 988
~ sub_28fe88d14 -> sub_291673c6c : 116 -> 132
~ sub_28fe890d4 -> sub_29167403c : 1568 -> 1564
~ sub_28fe8a04c -> sub_291674fb0 : 1240 -> 1236
~ sub_28fe8a8cc -> sub_29167582c : 1484 -> 1468
~ sub_28fe8eac8 -> sub_291679a18 : 244 -> 252
~ sub_28fe8f304 -> sub_29167a25c : 428 -> 424
```
