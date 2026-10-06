## MIME

> `/System/Library/PrivateFrameworks/MIME.framework/MIME`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34660` | `0x343fc` | **`-0x264`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f58` | `0x1f60` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x41b8` | `0x41b4` | **`-0x4`** |

### Other Changes

```diff

-3891.100.17.2.4
+3893.100.7.0.0
Symbols:
+ __ZNKSt9type_infoeqB9fqn220106ERKS_
+ __ZNSt3__110__function12__value_funcIFvRK12LineOfOutputEEC2B9fqn220106ERKS6_
+ __ZNSt3__110__function12__value_funcIFvRK12LineOfOutputEED2B9fqn220106Ev
+ __ZNSt3__110__function12__value_funcIFvhEEC2B9fqn220106ERKS3_
+ __ZNSt3__110__function12__value_funcIFvhEED2B9fqn220106Ev
+ __ZNSt3__125__throw_bad_function_callB9fqn220106Ev
- __ZNKSt9type_infoeqB9fqn220100ERKS_
- __ZNSt3__110__function12__value_funcIFvRK12LineOfOutputEEC2B9fqn220100ERKS6_
- __ZNSt3__110__function12__value_funcIFvRK12LineOfOutputEED2B9fqn220100Ev
- __ZNSt3__110__function12__value_funcIFvhEEC2B9fqn220100ERKS3_
- __ZNSt3__110__function12__value_funcIFvhEED2B9fqn220100Ev
- __ZNSt3__125__throw_bad_function_callB9fqn220100Ev
Functions:
~ -[NSObject(LockingAdditions) _mf_checkToAllowExclusiveLocksWithLock:] : 356 -> 352
~ -[NSObject(LockingAdditions) _mf_lockOrderingForType:] : 312 -> 308
~ -[NSString(NSEmailAddressString) mf_emailAddressesWithEquivalentDomains] : 460 -> 456
~ -[MFMessage uniqueArray:withStore:] : 412 -> 408
~ -[MFWeakSet _copyAllItems] : 304 -> 296
~ -[MFMimePart(MessageSupport) parseMimeBodyFromHeaderData:bodyData:isPartial:] : 588 -> 584
~ _MFMimePartParseContentTypeHeader : 560 -> 568
~ __MFCreateStringFromHeaderBytes : 1348 -> 1340
~ __parseHeaders : 4032 -> 3980
~ __copyNextMimeToken : 872 -> 880
~ _MFCreateStringWithBytes : 1084 -> 1104
~ __createUnfoldedData : 276 -> 256
~ __UniqueString : 648 -> 640
~ -[NSMutableDictionary(RFC2231Support) mf_fixupRFC2231Values] : 2520 -> 2548
~ -[NSString(MimeCharsetSupport) _mf_bestMimeCharset:] : 436 -> 432
~ +[MFMessageHeaders encodedDataForAddressList:splittingAtLength:firstLineBuffer:] : 2996 -> 2952
~ -[NSString(MimeCharsetSupport) mf_bestMimeCharsetUsingHint:] : 848 -> 844
~ -[MFMutableMessageHeaders encodedHeaders] : 1452 -> 1444
~ -[MFMutableMessageHeaders _appendAddedHeaderKey:value:toData:] : 416 -> 412
~ __filter_utf8_trailingSplitCodePoints : 376 -> 372
~ -[MFMessage setSender:] : 508 -> 504
~ -[MFMessage setTo:] : 508 -> 504
~ -[MFBase64Decoder appendData:] : 1376 -> 1372
~ -[MFMessage setCc:] : 508 -> 504
~ -[MFBase64Decoder _decodeBytes:end:into:length:startingAt:outEncodedOffset:] : 472 -> 476
~ -[MFMessage setBcc:] : 508 -> 504
~ -[MFBase64Decoder done] : 556 -> 548
~ -[MFMessage _copyDateFromReceivedHeadersInHeaders:] : 476 -> 472
~ +[NSDate(MFDateUtils) mf_copyDateInCommonFormatsWithString:] : 2528 -> 2504
~ -[MFDataHolder data] : 812 -> 808
~ -[MFDataHolder enumerateByteRangesUsingBlock:] : 296 -> 292
~ -[MFMimeBody hasEncryptedDescendantPart] : 1160 -> 1156
~ -[MFMessageHeaders _commaSeparatedValuesForKey:includeAngleBracket:] : 680 -> 676
~ _copyMutablePlainTextFromPoint : 4184 -> 4040
~ _MFGetTypeInfo : 492 -> 480
~ -[MFMutableMessageHeaders _copyHeaderValueForKey:] : 712 -> 708
~ __MFGuessEncodingForBytes : 436 -> 452
~ _MFMimePartParseContentDispositionHeader : 228 -> 236
~ -[MFQuotedPrintableDecoder appendData:] : 1092 -> 1072
~ -[MFBase64Encoder appendData:] : 1092 -> 1052
~ -[MFBase64Encoder done] : 872 -> 836
~ -[NSArray(NSEmailAddressArray) mf_uncommentedAddressList] : 288 -> 284
~ -[MFMessageHeaders appendHeaderData:andRecipients:] : 1864 -> 1860
~ -[MFMessageStore _downloadHeadersForMessages:] : 416 -> 412
~ -[MFBaseFilterDataConsumer done] : 284 -> 280
~ +[NSDate(MFDateUtils_Private) mf_copyLenientDateInCommonFormatsWithString:] : 716 -> 712
~ -[MFDiagnostics copyDiagnosticInformation] : 428 -> 424
~ +[MFHTMLParser plainTextFromHTML:limit:preserveNewlines:] : 768 -> 772
~ -[MFMessageStoreObjectCache debugDescription] : 708 -> 704
~ -[MFMessageStoreObjectCache removeAllObjectsForMessage:] : 296 -> 304
~ -[MFMessageStoreObjectCache flushObjectsOfKind:] : 384 -> 380
~ -[MFStringTransform initWithSoftBankHexData:] : 1320 -> 1316
~ ___MFCanUseSoftBankCodePoints_block_invoke : 768 -> 764
~ ___softBankTransform_block_invoke : 1376 -> 1372
~ -[MFMimePart setSubparts:] : 400 -> 396
~ __appendToDescriptionWithIndent : 1644 -> 1632
~ -[MFMimePart _partThatIsAttachment] : 380 -> 376
~ -[MFMimePart attachmentURLs] : 556 -> 552
~ -[MFMimePart(IMAPSupport) parseIMAPPropertyList:] : 2068 -> 2072
~ -[MFMutableMessageHeaders headersDictionary] : 484 -> 480
~ -[MFMutableMessageHeaders stripInternalHeaders] : 412 -> 380
~ -[MFMutableMessageHeaders description] : 680 -> 672
~ -[NSArray(MessagesFromMixedStoresConvenience) mf_dictionaryWithMessagesSortedByStore] : 512 -> 508
~ -[MFDataMessageStore bodyDataForMessage:isComplete:isPartial:downloadIfNecessary:] : 368 -> 372
~ -[NSFileManager(NSFileManagerAdditions) mf_pathsAtDirectory:beginningWithString:] : 476 -> 472
~ -[NSFileManager(NSFileManagerAdditions) mf_verifyProtectionClassesForFilesInDirectory:usingBlock:] : 764 -> 760
~ -[MFQuotedPrintableEncoder appendData:] : 1508 -> 1464
~ -[MFQuotedPrintableEncoder done] : 564 -> 552
~ __ZN12DecodeBuffer11parseHeaderEv : 228 -> 240
~ -[MFWeakSet anyObject] : 276 -> 268
~ -[MFWeakSet intersectsSet:] : 272 -> 268
~ -[MFWeakSet isEqualToSet:] : 288 -> 284
~ -[MFWeakSet isSubsetOfSet:] : 252 -> 248
~ -[MFWeakSet makeObjectsPerformSelector:withObject:] : 252 -> 248
~ -[MFWeakSet enumerateObjectsWithOptions:usingBlock:] : 276 -> 272
~ -[MFWeakSet objectsWithOptions:passingTest:] : 336 -> 332
~ +[MFWeakSet setWithObjects:] : 244 -> 248
~ -[MFWeakSet initWithObjects:] : 236 -> 240
~ -[MFWeakSet addObjectsFromArray:] : 344 -> 340
~ -[MFWeakSet intersectSet:] : 284 -> 280
~ -[MFWeakSet minusSet:] : 316 -> 312
~ -[MFWeakSet unionSet:] : 248 -> 244
~ -[MFWeakSet setSet:] : 252 -> 248
```
