## ContactsAutocompleteUI

> `/System/Library/PrivateFrameworks/ContactsAutocompleteUI.framework/ContactsAutocompleteUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0xa108` | `0xa138` | **`+0x30`** |
| `__TEXT.__text` | `0x46c54` | `0x46c38` | **`-0x1c`** |
| `__TEXT.__objc_methlist` | `0x714c` | `0x7164` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4ea0` | `0x4eb0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x590` | `0x598` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x900` | `0x908` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x14a0` | `0x14a8` | **`+0x8`** |

### Other Changes

```diff

-836.100.1.0.0
+838.100.1.0.0

-  Symbols:   3681
+  Symbols:   3683
Symbols:
+ _UIAccessibilityLayoutChangedNotification
+ _UIAccessibilityPostNotification
Functions:
~ -[CNAtomView _preferredIconVariant] : 584 -> 580
~ +[CNAtomView _badgeImagesForPresentationOptions:iconOrder:orderingLength:tintColor:large:variant:selected:] : 184 -> 192
~ -[CNComposeRecipientTextView addRecipient:index:animate:] : 1256 -> 1248
~ -[CNComposeRecipientTextView setAddresses:] : 512 -> 508
~ -[CNComposeRecipientTextView layoutManager:didCompleteLayoutForTextContainer:atEnd:] : 776 -> 772
~ -[CNComposeRecipient uncommentedAddress] : 732 -> 724
~ -[CNAutocompleteResultsTableViewController _updateTableViewModelAnimated:] : 1436 -> 1432
~ -[CNAutocompleteResultsTableViewController updateRecipients:disambiguatingRecipient:] : 1448 -> 1444
~ -[CNAutocompleteResultsTableViewController _selectSearchResultsRecipientAtIndexPath:] : 1816 -> 1812
~ -[CNAutocompleteResultsTableViewController endDisplayOfVisibleCellsExcludingIndexPath:] : 352 -> 348
~ -[CNAutocompleteResultsTableViewController viewLayoutMarginsDidChange] : 368 -> 364
~ -[CNAutocompleteResultsTableViewController invalidateAddressTintColors] : 268 -> 264
~ -[CNAutocompleteResultsTableViewController invalidatePreferredRecipients] : 272 -> 268
~ -[CNAutocompleteResultsTableViewController updateCell:withPreferredRecipient:isInvalidation:] : 840 -> 836
~ -[CNAutocompleteSuggestionsViewController fetchRecipients] : 800 -> 792
~ -[CNAutocompleteSuggestionsViewController avatarSize] : 188 -> 200
~ -[CNAutocompleteSuggestionsViewController imageForRecipient:imageUpdateBlock:] : 988 -> 1028
~ -[CNAutocompleteSuggestionsViewController selectedRecipientHandles] : 348 -> 344
~ -[CNAtomTextView _setDrawsDebugBaselines:] : 408 -> 404
~ -[CNAtomTextView _setEnabled:animated:] : 364 -> 360
~ -[CNAtomTextView currentEditingString:] : 576 -> 572
~ -[CNAtomTextView _deleteCharactersInStorage:ranges:rangeToAdjust:] : 376 -> 372
~ -[CNAtomTextView setRepresentedObjects:] : 456 -> 452
~ -[CNAtomTextView _storeRepresentedObjects:onPasteboard:] : 484 -> 480
~ -[CNAtomTextView _insertRepresentedObjects:atCharacterRange:] : 1064 -> 1056
~ -[CNAtomTextView edgeInsets] : 592 -> 588
~ ___28-[CNAtomTextView edgeInsets]_block_invoke : 172 -> 168
~ -[CNAtomTextView _updateAtomMasksInRect:] : 368 -> 364
~ -[CNAtomTextView _tapRecognized:] : 452 -> 448
~ -[CNAtomTextView layoutManager:didCompleteLayoutForTextContainer:atEnd:] : 756 -> 752
~ _copyClosestMatchingExistingUnifiedContactUsingAddressesAndDisplayName : 992 -> 988
~ -[_CNCountableMatchesContext countInstances:usingPredicate:] : 504 -> 500
~ __fastCountOfCompleteMatches : 804 -> 800
~ -[CNComposeRecipientGroup _populateSortedChildren] : 732 -> 728
~ -[CNComposeRecipientGroup address] : 392 -> 388
~ -[CNComposeRecipientGroup addRecipientToPasteboard:] : 264 -> 260
~ ____getDisplayNameMatches_block_invoke : 480 -> 468
~ -[CNAutocompleteSearchController unhideResultsController] : 336 -> 436
~ -[CNAutocompleteSearchController hideResultsController] : 316 -> 416
~ -[CNAutocompleteSearchController composeRecipientView:textDidChange:] : 752 -> 748
~ -[CRRecentContactsLibrary(CloudRecentsExtensions) recordContactEventsForHeaders:recentsDomain:] : 708 -> 704
~ +[CNComposeRecipientTableViewCell _attributedStringForGroupMembersOfRecipient:matchedStrings:constrainedToWidth:font:] : 664 -> 660
~ +[CNComposeRecipientTableViewCell _attributedStringForListOfGroupMemberNames:numberTruncated:] : 1356 -> 1336
~ -[CNComposeRecipientTableViewCell updateLabelsContrainedToWidth:] : 1744 -> 1736
~ -[CNComposeRecipientTableViewCell assembleContactAvatarsForRecipient:] : 1036 -> 1032
~ -[CNAtomView setupOverlayLabelTextForEmojiRanges:] : 524 -> 520
~ -[CNAtomView _updateCompositingFilters] : 420 -> 412
~ -[CNComposeHeaderView handleTouchesEnded] : 384 -> 380
~ -[CNContactsAutocompleteSearchOperation main] : 1876 -> 1872
~ ___119-[CNContactsAutocompleteSearchOperation autocompleteFetch:shouldExpectSupplementalResultsForRequest:completionHandler:]_block_invoke : 556 -> 552
~ ___119-[CNContactsAutocompleteSearchOperation autocompleteFetch:shouldExpectSupplementalResultsForRequest:completionHandler:]_block_invoke_2 : 632 -> 628
~ -[CNContactsAutocompleteSearchOperation autocompleteFetch:didReceiveResults:] : 1352 -> 1344
~ -[CNContactsAutocompleteSearchOperation unifyRecipientsIfNeccesary:] : 904 -> 896
~ -[CNContactsAutocompleteSearchOperation defaultChildForUnifiedEmailRecipients:] : 796 -> 792
~ -[CNComposeRecipientTextView removeRecipient:] : 304 -> 300
~ ___39-[CNComposeRecipientTextView clearText]_block_invoke : 320 -> 316
~ -[CNComposeRecipientTextView atomViewForRecipient:] : 348 -> 344
~ -[CNComposeRecipientTextView textViewDidChange:] : 456 -> 452
~ -[CNComposeRecipientTextView dropItems:] : 708 -> 704
~ -[_CNAtomTextView paste:] : 1416 -> 1400
```
