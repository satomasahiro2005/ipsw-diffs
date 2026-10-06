## IMAP

> `/System/Library/PrivateFrameworks/MessageLegacy.framework/MailServices/IMAP.framework/IMAP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c620` | `0x3c4ac` | **`-0x174`** |

### Other Changes

```text
Functions:
~ +[CastleIMAPAccount newChildAccountWithParentAccount:error:] : 976 -> 972
~ -[CastleIMAPAccount _fromEmailAddressesIncludingDisabled:] : 488 -> 480
~ -[CastleIMAPAccount _aliasesFromData:] : 748 -> 744
~ -[CastleIMAPAccount _aliasesFromOldData:] : 412 -> 408
~ -[CastleIMAPAccount _emailsFromData:] : 504 -> 500
~ -[CastleIMAPAccount _prepareAliasData] : 548 -> 544
~ -[MFIMAPConnection(CondStore) sendResponsesForCondStoreFlagFetchForUIDs:withSequenceIdentifier:toQueue:] : 692 -> 688
~ -[MFIMAPConnection(ESearch) eSearchIDSet:areMessageSequenceNumbers:forTerms:success:returning:] : 372 -> 368
~ -[GmailAccount _removeCredential:] : 316 -> 312
~ -[MFGmailSMTPAccount _urlFromResponse:] : 668 -> 664
~ -[IMAPAccount messagesAdded:] : 408 -> 404
~ -[IMAPAccount storeMailboxTypeOnServer:] : 40 -> 52
~ -[IMAPAccount setStoreMailboxType:onServer:] : 208 -> 224
~ -[IMAPAccount _newMailboxWithParent:name:attributes:dictionary:withCreationOption:] : 812 -> 808
~ -[IMAPAccount _mailboxUidForName:] : 464 -> 460
~ -[IMAPAccount flagChangesForMailboxPath:UID:connectTime:] : 632 -> 628
~ -[IMAPAccount removeFlagChanges:forMessages:] : 504 -> 500
~ -[IMAPAccount setCommitTime:forConnectionTag:] : 448 -> 444
~ -[IMAPAccount setConnectionTag:forFlagChanges:forMessages:] : 604 -> 600
~ -[IMAPAccount updatePushRegisteredMailboxes:] : 532 -> 528
~ -[IMAPAccount notificationNamesForPrefix:mailboxUids:] : 304 -> 300
~ -[IMAPAccount registerPushNotificationPrefix:forMailboxUids:] : 404 -> 400
~ -[IMAPAccount _copyMailboxListForNames:] : 312 -> 308
~ -[IMAPAccount changePushedMailboxUidsAdded:deleted:] : 600 -> 592
~ -[IMAPAccount mailboxNamesForPushRegistration] : 536 -> 532
~ -[IMAPAccount handlePushNotificationOnMailboxes:missedNotifications:] : 1272 -> 1260
~ -[MFIMAPCommandPipeline failureResponsesFromSendingCommandsWithConnection:] : 1380 -> 1376
~ -[_MFIMAPFetchUnit matchesFetchResponse:] : 432 -> 428
~ _IMAPNextUidFromSet : 600 -> 584
~ _IMAPScanUid : 280 -> 272
~ -[MFIMAPConnection _addCapabilities:] : 236 -> 232
~ -[MFIMAPConnection _sendApplePushForAccountIfSupported:] : 2460 -> 2452
~ __IMAPCreateQuotedString : 856 -> 840
~ -[MFIMAPConnection _errorForResponse:commandParams:] : 640 -> 636
~ -[MFIMAPConnection _doNamespaceCommand] : 416 -> 412
~ -[MFIMAPConnection fetchStatusForMailboxes:args:] : 488 -> 472
~ __processSelectCommand : 648 -> 644
~ -[MFIMAPConnection quotaPercentagesForMailbox:] : 832 -> 828
~ __doUidSearch : 640 -> 636
~ -[MFIMAPConnection searchUidSet:forNewMessageIDs:] : 880 -> 876
~ -[MFIMAPConnection fetchHeadersForUid:] : 404 -> 400
~ -[MFIMAPConnection fetchMessageIdsForUids:] : 628 -> 624
~ -[MFIMAPConnection fetchUniqueRemoteIDsForUids:] : 452 -> 448
~ -[MFIMAPConnection description] : 232 -> 228
~ -[MFIMAPConnection _readDataOfLength:] : 316 -> 324
~ -[MFIMAPConnection _responseFromSendingCommands:count:] : 180 -> 184
~ -[MFIMAPConnection searchUIDs:withFlagRequests:] : 456 -> 452
~ -[MFIMAPConnection sendResponsesForUIDs:fields:flagSearchResults:toQueue:] : 368 -> 364
~ -[MFIMAPConnectionFlagSearchResults description] : 524 -> 516
~ -[MFIMAPConnectionFlagSearchResults _flagsForUID:] : 512 -> 504
~ -[MFIMAPConnectionFlagSearchResults _indexSetFromUIDs:] : 264 -> 260
~ -[MFIMAPCompoundDownload addCommandsToPipeline:withCache:] : 308 -> 304
~ -[MFIMAPCompoundDownload isComplete] : 284 -> 280
~ -[MFIMAPCompoundDownload expectedLength] : 320 -> 316
~ -[MFIMAPCompoundDownload bytesFetched] : 292 -> 288
~ -[MFIMAPCompoundDownload lengthOfDataBeforeLineConversion] : 256 -> 252
~ -[MFIMAPDownloadCache handleFetchResponses:] : 372 -> 368
~ -[MFIMAPFetchResult dealloc] : 168 -> 164
~ -[MFIMAPFetchResult encoding] : 316 -> 312
~ -[NSString(IMAPNameEncoding) mf_encodedIMAPMailboxName] : 1016 -> 1000
~ __serializeStringArrayToData : 264 -> 260
~ -[MFIMAPOperation actsOnTemporaryUid:] : 144 -> 140
~ -[MFIMAPOfflineCopyOnStupidServerOperation _deserializeOpSpecificValuesFromData:cursor:] : 356 -> 352
~ -[MFIMAPOperationCache _queueDeferredOperation:] : 900 -> 896
~ -[MFIMAPOperationCache setFlags:andClearFlags:forMessages:] : 420 -> 416
~ -[MFIMAPOperationCache firstUidForCopyingMessages:fromMailbox:toMailbox:] : 960 -> 964
~ __saveChanges : 408 -> 404
~ -[MFIMAPOperationCache hasOperationsForMailbox:] : 288 -> 284
~ -[MFIMAPOperationCache _performCopyOperation:withContext:] : 1192 -> 1188
~ -[MFIMAPOperationCache performDeferredOperationsWithConnection:] : 1124 -> 1120
~ -[MFIMAPConnection(ReferenceSearching) _messageIDsFromFetchResultData:] : 772 -> 768
~ -[MFIMAPConnection(ReferenceSearching) _getReferencesForMessageSet:] : 684 -> 680
~ -[MFIMAPConnection(ReferenceSearching) _uidsForMessageIDs:excludeDeleted:] : 336 -> 332
~ -[MFIMAPConnection(ReferenceSearching) uidsReferencedBy:] : 324 -> 320
~ -[MFIMAPResponse dealloc] : 200 -> 196
~ -[MFIMAPResponse fetchResultWithType:] : 264 -> 260
~ -[MFIMAPResponse description] : 2292 -> 2296
~ ___29-[MFIMAPResponse description]_block_invoke : 608 -> 604
~ _MFCreateArrayForMessageFlags : 260 -> 280
~ _MFMessageFlagsFromArray : 332 -> 348
~ _status_response : 624 -> 620
~ _list_response : 472 -> 484
~ _fetch_response : 2772 -> 2780
~ _flags_array : 468 -> 464
~ _matchResponseTableEntry : 228 -> 236
~ -[MFFetchResponseQueue handleItems:] : 436 -> 432
~ -[MFFetchResponseQueue addItem:] : 1324 -> 1320
~ _uidFromFetchResults : 260 -> 256
~ _flagsFromFetchResults : 252 -> 248
~ -[MFBaseSyncResponseQueue sequenceIdentifierForItem:] : 336 -> 332
~ -[MFSearchResponseQueue addItem:] : 372 -> 368
~ _tokenizeCriterionWithHandler : 1008 -> 1000
~ ___80-[MFLibraryIMAPStore _fetchMessagesMatchingCriterion:limit:withOptions:handler:]_block_invoke : 576 -> 572
~ _fetchArgumentsForCriterion : 2316 -> 2300
~ -[MFLibraryIMAPStore _updateLibraryForTransferedMessages:toDestinationMailbox:newMessageInfo:flagsToSet:] : 1264 -> 1260
~ ___56-[MFLibraryIMAPStore moveMessages:toMailbox:markAsRead:]_block_invoke : 504 -> 500
~ __flagsToSetAndClearFromDictionary : 1380 -> 1376
~ -[MFLibraryIMAPStore addFlagChanges:forMessages:] : 308 -> 304
~ -[MFLibraryIMAPStore setFlagsFromDictionary:forMessages:] : 708 -> 700
~ ___51-[MFLibraryIMAPStore remoteIDsFromUniqueRemoteIDs:]_block_invoke : 480 -> 476
~ -[MFLibraryIMAPStore connection:didReceiveResponse:forCommand:] : 1600 -> 1596
~ -[MFLibraryIMAPStore _uidsForMessages:] : 284 -> 280
~ -[MFLibraryIMAPStore addMessages:newMessagesByOldMessage:] : 424 -> 420
~ -[MFLibraryIMAPStore _handleFlagsChangedForMessages:flags:oldFlagsByMessage:] : 480 -> 476
~ -[MFLibraryIMAPStore uniqueRemoteIDsForMessages:] : 508 -> 504
~ _needUTF8ForCriterion : 292 -> 288
~ +[MFOSXServerIMAPAccount newChildAccountWithParentAccount:error:] : 1052 -> 1048
```
