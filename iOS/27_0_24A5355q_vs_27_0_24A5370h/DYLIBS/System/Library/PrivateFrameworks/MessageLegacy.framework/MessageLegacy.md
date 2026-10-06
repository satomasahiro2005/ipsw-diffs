## MessageLegacy

> `/System/Library/PrivateFrameworks/MessageLegacy.framework/MessageLegacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63b5c` | `0x63998` | **`-0x1c4`** |
| `__TEXT.__unwind_info` | `0x2008` | `0x2010` | **`+0x8`** |

### Other Changes

```text
Functions:
~ -[MFStream openToHostName:port:] : 856 -> 852
~ +[MFAccount _newPersistentAccount] : 352 -> 348
~ -[MFAccount _setAccountProperties:] : 540 -> 536
~ -[MFAccountValidator _validateAccount:] : 1856 -> 1852
~ __openConnectionForAccount : 724 -> 720
~ -[MFAccountValidator error] : 80 -> 76
~ -[MFActivityMonitor addActivityTargets:] : 380 -> 376
~ +[MFAuthScheme authSchemesForAccount:connection:] : 428 -> 424
~ +[MFConnection logConnection:type:data:] : 616 -> 620
~ __logEvent : 532 -> 528
~ -[MFConnection authenticationMechanisms] : 368 -> 364
~ -[MFConnection readLineIntoData:] : 272 -> 268
~ -[MFCRAM_MD5Authenticator responseForServerData:] : 436 -> 440
~ +[DeliveryAccount existingAccountForUniqueID:] : 292 -> 288
~ +[DeliveryAccount accountWithUniqueId:] : 276 -> 272
~ +[DeliveryAccount accountWithIdentifier:] : 272 -> 268
~ +[DeliveryAccount existingAccountWithIdentifier:] : 292 -> 288
~ -[DeliveryAccount hasNoReferences] : 276 -> 272
~ -[_MFDigestMD5Authenticator responseForServerData:] : 3908 -> 3904
~ __createResponseData : 1392 -> 1412
~ -[_MFFormatFlowedWriter _findLineBreakInRange:maxCharWidthCount:endIsURL:] : 740 -> 724
~ -[_MFFormatFlowedWriter _outputQuotedParagraph:range:withQuoteLevel:] : 1744 -> 1740
~ ___57-[MFInvocationQueue _adjustThreadPrioritiesIsForeground:]_block_invoke : 256 -> 252
~ -[MFInvocationQueue copyDiagnosticInformation] : 460 -> 456
~ -[MFLibraryMessage preferredEmailAddressToReplyWith] : 608 -> 604
~ ___44-[MFLibraryMessage setMetadataValue:forKey:]_block_invoke : 376 -> 372
~ -[MFLibraryStore copyOfMessagesInRange:options:generation:] : 564 -> 560
~ -[MFLibraryStore copyOfAllMessagesForBodyLoadingFromRowID:limit:] : 336 -> 332
~ -[MFLibraryStore filterMessagesByMembership:] : 336 -> 332
~ -[MFLibraryStore _handleFlagsChangedForMessages:flags:oldFlagsByMessage:] : 632 -> 624
~ -[MFLibraryStore _memberMessagesWithCompactionNotification:] : 424 -> 420
~ -[MFLibraryStore deleteMessages:moveToTrash:] : 1128 -> 1120
~ +[MailAccount _setupSortedPathsForAccounts:] : 264 -> 260
~ +[MailAccount existingAccountForUniqueID:] : 292 -> 288
~ +[MailAccount _loadAllAccountsWithOptions:error:] : 496 -> 492
~ +[MailAccount _setMailAccounts:saveIfChanged:alreadyLocked:] : 952 -> 940
~ +[MailAccount existingAccountWithType:hostname:username:] : 292 -> 288
~ +[MailAccount resetMailboxTimers] : 232 -> 228
~ __allEmailAddressesIncludingFullName : 1588 -> 1584
~ +[MailAccount _accountContainingEmailAddress:matchingAddress:fullUserName:includingInactive:] : 872 -> 868
~ +[MailAccount accountForHeaders:message:includingInactive:] : 364 -> 360
~ +[MailAccount addressesThatReceivedMessage:] : 388 -> 384
~ +[MailAccount allMailboxUids] : 364 -> 360
~ +[MailAccount _defaultMailAccountForDeliveryIncludingRestricted:] : 512 -> 508
~ -[MailAccount deliveryAccountAlternates] : 308 -> 304
~ -[MailAccount setDeliveryAccountAlternates:] : 364 -> 360
~ -[MailAccount _invalidateAndDeleteAccountData:] : 908 -> 900
~ -[MailAccount deliveryAccountInUseByOtherAccounts:] : 528 -> 524
~ +[MailAccount synchronouslyEmptyMailboxUidType:inAccounts:] : 296 -> 292
~ -[MailAccount _resetSpecialMailboxes] : 560 -> 568
~ -[MailAccount _renameMailbox:newName:parent:] : 1156 -> 1152
~ -[MailAccount _resetAllMailboxURLs:] : 456 -> 452
~ +[MailAccount accountWithURL:] : 700 -> 692
~ +[MailAccount updateEmailAliasesForActiveAccounts] : 296 -> 292
~ +[MailAccount standardAccountClass:valueForKey:] : 536 -> 532
~ -[MailAccount cachePolicy] : 104 -> 100
~ +[MailAccount _accountWithPath:] : 356 -> 352
~ -[MailAccount isActiveWithPersistentAccount:] : 328 -> 324
~ -[MailAccount _loadEntriesFromFileSystemPath:parent:] : 776 -> 772
~ -[MailAccount _writeMailboxCacheWithPrejudice:] : 620 -> 616
~ -[MailAccount allLocalMailboxUids] : 160 -> 168
~ -[MailAccount iconString] : 364 -> 360
~ -[MFMailboxUid _dictionaryRepresentation] : 464 -> 460
~ -[MFMailboxUid numberOfDescendants] : 280 -> 276
~ __MFChildWithPredicate : 292 -> 288
~ -[MFMailboxUid setChildren:] : 752 -> 748
~ -[MFMailboxUid addToPostOrderTraversal:] : 276 -> 272
~ -[MFMailMessage bestAlternativePart:] : 536 -> 532
~ _MFMessageFlagsByApplyingDictionary : 284 -> 280
~ -[NSArray(StoreEnumeration) mf_enumerateByStoreUsingBlock:] : 320 -> 316
~ -[MFMailMessageStore hasMessageForAccount:] : 312 -> 308
~ -[MFMailMessageStore deleteMessages:moveToTrash:] : 576 -> 572
~ ___83+[MFMailMessageStore copyMessages:toMailbox:markAsRead:deleteOriginals:isDeletion:]_block_invoke : 852 -> 848
~ -[MFMailMessageStore setFlagsFromDictionary:forMessages:] : 544 -> 536
~ -[MFMailMimePart contentToOffset:resultOffset:downloadIfNecessary:asHTML:isComplete:] : 512 -> 508
~ +[MFMessageCriterion criteriaFromDefaultsArray:removingRecognizedKeys:] : 352 -> 348
~ +[MFMessageCriterion defaultsArrayFromCriteria:] : 312 -> 308
~ -[MFMessageCriterion initWithDictionary:andRemoveRecognizedKeysIfMutable:] : 900 -> 896
~ -[MFMessageCriterion dictionaryRepresentation] : 824 -> 820
~ -[MFMessageCriterion _headersRequiredForEvaluation] : 616 -> 612
~ +[MFMessageCriterion _updateAddressComments:] : 332 -> 328
~ -[MFMessageCriterion _evaluateCompoundCriterion:] : 288 -> 284
~ -[MFMessageCriterion _evaluateFullNameCriterion:] : 736 -> 732
~ -[MFMessageCriterion _evaluateAttachmentCriterion:] : 536 -> 532
~ _MFMessageFlagsFontSizeDelta : 24 -> 20
~ _MFComparatorFunctionForSortOrder : 152 -> 168
~ -[MFMessageWriter createMessageWithPlainTextDocumentsAndAttachments:headers:] : 880 -> 876
~ -[MFMessageWriter createMessageWithHtmlString:plainTextAlternative:otherHtmlStringsAndAttachments:charsets:headers:] : 1680 -> 1676
~ -[MFMessageWriter createMessageWithHtmlString:attachments:headers:] : 700 -> 696
~ -[_MFOutgoingMessageBody appendData:] : 144 -> 140
~ __appendHeadersToMessageHeaders : 1576 -> 1568
~ __makeMimeHeadersConsistent : 1744 -> 1740
~ ___52+[MFAccountLoader _bundlePathForAccountClassString:]_block_invoke : 728 -> 724
~ -[MFAccountStore accountsWithTypeIdentifiers:error:] : 420 -> 416
~ -[MFAttachmentComposeManager _callProgressBlockForAttachmentURL:withBytes:expectedSize:] : 868 -> 864
~ -[MFAttachmentComposeManager attachmentsForContext:] : 372 -> 368
~ -[MFAttachmentCompositionContext dealloc] : 368 -> 364
~ -[MFAttachmentLibraryManager _messageAttachmentStorageLocationsDidChangeNotification:] : 460 -> 456
~ -[MFAttachmentLibraryManager attachmentsForMessage:withSchemes:] : 440 -> 436
~ -[MFAttachmentManager removeProvider:] : 300 -> 296
~ -[MFAttachmentManager attachmentsForURLs:error:] : 328 -> 324
~ -[MFAttachmentManager attachmentForContentID:preferredSchemes:] : 456 -> 452
~ ___58-[MFAttachmentManager _fetchCompletedForAttachment:error:]_block_invoke : 664 -> 660
~ ___58-[MFAttachmentManager _fetchCompletedForAttachment:error:]_block_invoke_3 : 252 -> 248
~ -[MFComposeAttachmentDataProvider recordPasteboardDataForAttachments:] : 324 -> 320
~ -[MFComposeAttachmentDataProvider recordUndoDataForAttachments:] : 324 -> 320
~ __NotifyObserversWithContentProtectionState : 816 -> 812
~ ___MFContentProtectionDumpDiagnosticState_block_invoke : 684 -> 680
~ -[MFLocalizedMessageHeaders markupString] : 512 -> 508
~ +[MFLocalizedMessageHeaders localizedHeadersFromEnglishHeaders:] : 344 -> 340
~ +[MFLocalizedMessageHeaders englishHeadersFromLocalizedHeaders:] : 368 -> 364
~ -[MFNetworkController _updateActiveCalls] : 360 -> 356
~ -[MFNetworkController copyDiagnosticInformation] : 672 -> 668
~ -[MFOutgoingMessageDelivery deliverSynchronouslyWithCompletion:] : 1028 -> 1024
~ ___46-[MFPowerController copyDiagnosticInformation]_block_invoke : 400 -> 396
~ -[MFSecureMIMECompositionManager _determineEncryptionStatusWithNewRecipients:] : 756 -> 748
~ +[MFSecureMIMECompositionManager copyEncryptionCertificatesForAccount:recipientAddress:error:] : 980 -> 976
~ -[MFSparseMutable64IndexSet indexGreaterThanIndex:] : 108 -> 104
~ -[MFSparseMutable64IndexSet description] : 208 -> 204
~ -[MFMimeEnrichedReader nowWouldBeAGoodTimeToAppendToTheAttributedString] : 1528 -> 1524
~ __copyNextToken : 780 -> 760
~ -[MFMimeEnrichedReader beginCommand:] : 352 -> 360
~ -[MFMimeEnrichedReader endCommand:] : 244 -> 252
~ -[MFMimeEnrichedReader readTokenInto:] : 1020 -> 1048
~ -[NSMutableIndexSet(Additions) mf_intersectIndexes:] : 348 -> 344
~ -[NSNotificationCenter(MessageAdditions) mf_removeObservers:] : 240 -> 236
~ -[NSCountedSet(Additions) mf_debugDescription] : 384 -> 380
~ -[NSString(NSStringUtils) mf_uniqueFilenameWithRespectToFilenames:] : 424 -> 420
~ -[NSString(NSStringUtils) mf_stringByEscapingHTMLCodes] : 476 -> 472
~ _MFCreateStringByCondensingWhitespace : 524 -> 520
~ -[NSString(MFSharedResourcesDirectoryPathUtils) mf_stringByExpandingTildeWithSharedResourcesDirectoryInPath] : 312 -> 324
~ -[NSString(MFSharedResourcesDirectoryPathUtils) mf_stringByAbbreviatingSharedResourcesDirectoryWithTildeInPath] : 696 -> 692
~ -[MFProgressiveMimeParser _initializeTopLevelPartWithHeaders:] : 488 -> 484
~ -[MFProgressiveMimeParser _continueParsingStartOfPart] : 312 -> 316
~ -[MFProgressiveMimeParser _continueParsingHeaders] : 792 -> 796
~ -[MFMimePart(SMIMEDecoding) decodeApplicationPkcs7_mime] : 1784 -> 1780
~ -[_MFSecCMSEncoder initForEncryptionWithCompositionSpecification:error:] : 1228 -> 1232
~ -[SMTPAccount connectionSettingsForAuthentication:secure:insecure:] : 520 -> 516
~ -[MFSMTPConnection maximumMessageBytes] : 376 -> 372
~ -[MFSMTPConnection mailFrom:recipients:withData:host:errorTitle:errorMessage:serverResponse:displayError:errorCode:errorUserInfo:] : 3108 -> 3100
~ -[MFWebMessageDocument attachmentsInDocument] : 368 -> 364
```
