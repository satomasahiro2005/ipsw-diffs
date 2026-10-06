## ProactiveSupport

> `/System/Library/PrivateFrameworks/ProactiveSupport.framework/ProactiveSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5f9fc` | `0x5f8e0` | **`-0x11c`** |

### Other Changes

```diff
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__110unique_ptrIN9proactive3pas18SynchronizedObjectIN12_GLOBAL__N_113HDGuardedDataENS2_6detail14RecursiveMutexEEENS_14default_deleteIS8_EEE5resetB9fqe220106EPS8_
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16__treeIN12_GLOBAL__N_114BuddyAllocator10BlockRangeENS_4lessIS3_EENS_9allocatorIS3_EEE14__tree_deleterclB9fqe220106EPNS_11__tree_nodeIS3_PvEE
+ __ZNSt3__16vectorIDv8_fN12_GLOBAL__N_120SimdAlignedAllocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIDv8_iN12_GLOBAL__N_120SimdAlignedAllocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE18__insert_with_sizeB9fqe220106INS_17_ClassicAlgPolicyEPKhS7_EENS_11__wrap_iterIPhEENS8_IS7_EET0_T1_l
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220106Ev
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__110unique_ptrIN9proactive3pas18SynchronizedObjectIN12_GLOBAL__N_113HDGuardedDataENS2_6detail14RecursiveMutexEEENS_14default_deleteIS8_EEE5resetB9fqe220100EPS8_
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16__treeIN12_GLOBAL__N_114BuddyAllocator10BlockRangeENS_4lessIS3_EENS_9allocatorIS3_EEE14__tree_deleterclB9fqe220100EPNS_11__tree_nodeIS3_PvEE
- __ZNSt3__16vectorIDv8_fN12_GLOBAL__N_120SimdAlignedAllocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIDv8_iN12_GLOBAL__N_120SimdAlignedAllocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIhNS_9allocatorIhEEE18__insert_with_sizeB9fqe220100INS_17_ClassicAlgPolicyEPKhS7_EENS_11__wrap_iterIPhEENS8_IS7_EET0_T1_l
- __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220100Ev
Functions:
~ -[NSArray(_PASAdditions) _pas_filteredArrayWithIndexedTest:] : 484 -> 480
~ +[_PASDeviceState isClassCLocked] : 1112 -> 1108
~ -[_PASSqliteDatabase withDbLockExecuteBlock:] : 472 -> 488
~ ___47-[_PASSqliteDatabase prepQuery:onPrep:onError:]_block_invoke : 1384 -> 1368
~ -[NSArray(_PASAdditions) _pas_mappedArrayWithIndexedTransform:] : 496 -> 492
~ -[_PASSqliteStatementCache evictCachedStatementForScoreSlot:] : 156 -> 160
~ -[_PASSqliteStatementCache checkOutStatement:associatedObject:withSQL:] : 192 -> 184
~ -[_PASLPReaderBinaryPlist initWithData:sourcedFromPath:needsValidation:error:] : 1564 -> 1568
~ -[_PASLPReaderBinaryPlist _offsetForRecord:] : 84 -> 96
~ -[_PASLPReaderBinaryPlist _decodeOffset:decodedObject:ifEqualToReferenceObject:validationDepth:unlazyCopyCache:] : 3372 -> 3380
~ -[_PASLPReaderBinaryPlist _validateCollectionMembers:validationDepth:count:] : 248 -> 272
~ -[_PASLPReaderBinaryPlist _decodeUnsignedIntegerValue:usingCursor:] : 164 -> 172
~ ___32-[_PASLPArray getObjects:range:]_block_invoke : 412 -> 404
~ -[_PASLPReaderV1 _decodeValue:errMsg:handleBoolean:handleTaggedInt:handleBoxedInt:handleTaggedFloat:handleBoxedFloat:handleDate:handleData:handleString:handleDict:handleArray:] : 2152 -> 2128
~ ___88-[_PASLPReaderV1 _validateObjectGraphWithFilename:rootValue:recursionDepth:stats:error:]_block_invoke_11 : 184 -> 192
~ ___88-[_PASLPReaderV1 _validateObjectGraphWithFilename:rootValue:recursionDepth:stats:error:]_block_invoke_9 : 708 -> 724
~ +[_PASSecureCodingHelper robustDecodeObjectOfClasses:forKey:withCoder:expectNonNull:errorDomain:errorCode:logHandle:] : 1216 -> 1212
~ __PASTryToConvertPhoneNumberToASCII : 816 -> 812
~ -[NSString(_PASDistilledString) _pas_distilledString] : 920 -> 932
~ _xBestIndex : 2252 -> 2232
~ -[_PASLPReaderBinaryPlist objectForKey:usingDictionaryContext:] : 360 -> 372
~ -[_PASLPReaderBinaryPlist objectAtIndex:usingDictionaryContext:] : 372 -> 384
~ sub_1a73254c8 -> sub_1a76734f0 : 252 -> 256
~ __PASRepairString : 1144 -> 1128
~ -[_PASAsset2 _maFilesystemPathsForAssetDataRelativePaths:guardedData:isMissingData:assetVersion:] : 1136 -> 1132
~ -[_PASAsset2 _defaultBundleFilesystemPathsForAssetDataRelativePaths:guardedData:assetVersion:] : 860 -> 856
~ -[NSArray(_PASAdditions) _pas_leftFoldWithInitialObject:indexedAccumulate:] : 468 -> 464
~ __PASFullwidthLatinToHalfwidth : 784 -> 772
~ +[_PASLPWriterV1 _mappedDataWithPlist:fd:ofs:error:] : 5428 -> 5416
~ __PASMurmur3_x86_32 : 276 -> 280
~ ___71+[_PASLPWriterV1 _valueWordForObjectGraph:allocContext:recursionDepth:]_block_invoke_2 : 148 -> 144
~ ___71+[_PASLPWriterV1 _valueWordForObjectGraph:allocContext:recursionDepth:]_block_invoke_7 : 160 -> 164
~ __PASCollapseWhitespaceAndStrip : 1020 -> 1016
~ __PASIterateLongChars : 668 -> 652
~ __pas_registerSqliteCollections : 492 -> 488
~ _computeHashes_MURMUR3_X86_32 : 188 -> 184
~ __PAS_MurmurHash3_x86_32 : 280 -> 284
~ -[_PASBloomFilter getWithHashes:] : 212 -> 208
~ -[_PASBloomFilterForWriting setWithHashes:] : 240 -> 236
~ ___73-[_PASSqliteDatabase selectColumns:fromTable:whereClause:onPrep:onError:]_block_invoke : 756 -> 752
~ -[_PASBigEndianUTF16String _implGetCharacters:range:] : 272 -> 280
~ -[_PASLPReaderBinaryPlist _unlazyCopyForArrayWithCount:storage:unlazyCopyCache:] : 788 -> 812
~ -[_PASLPReaderBinaryPlist _unlazyCopyForDictionaryWithCount:storage:unlazyCopyCache:] : 800 -> 824
~ -[_PASLPReaderBinaryPlist keyAtIndex:usingDictionaryContext:] : 344 -> 356
~ -[_PASLPReaderBinaryPlist objectAtIndex:usingArrayContext:] : 344 -> 356
~ __PASEnumerateSimpleLinesInString : 660 -> 652
~ __PASEnumerateSimpleLinesInUTF8Data : 336 -> 332
~ __PASBytesToHex : 456 -> 472
~ __PASHexToBytes : 224 -> 228
~ __PASIsAllDigits : 436 -> 428
~ __PASIsAllUppercase : 464 -> 460
~ __PASLooksLikeNumber : 460 -> 456
~ __PASRemoveCharacterSet : 600 -> 596
~ __PASKeepOnlyCharacterSet : 600 -> 596
~ __PASRemoveWhitespace : 752 -> 748
~ __PASTrimTrailingWhitespace : 712 -> 708
~ __PASUtfNCursorAdvance : 524 -> 508
~ __destroyIcuTransformCache : 268 -> 264
~ ____PASSimpleICUTransform_block_invoke : 376 -> 372
~ _fastNormalizeUnicodeString : 2268 -> 2308
~ _fastNormalizeUnicodeStringMinimally : 2260 -> 2236
~ ___CFStringReplaceableCharAt : 248 -> 240
~ ___CFStringReplaceableChar32At : 460 -> 444
~ +[NSIndexPath(_PASAdditions) _pas_fromVersionString:withExceptions:] : 1108 -> 1112
~ -[NSSet(_PASAdditions) _pas_mappedSetWithTransform:] : 484 -> 480
~ -[NSSet(_PASAdditions) _pas_filteredSetWithTest:] : 472 -> 468
~ -[NSSet(_PASAdditions) _pas_setByRemovingObjectsFromSet:] : 664 -> 660
~ -[_PASLowValueCardinalityMutableDictionary initWithObjects:forKeys:count:] : 128 -> 144
~ -[_PASLowValueCardinalityMutableDictionary allKeysForObject:] : 416 -> 412
~ -[_PASLowValueCardinalityMutableDictionaryEnumerator allObjects] : 500 -> 496
~ -[NSArray(_PASAdditions) _pas_rightFoldWithInitialObject:indexedAccumulate:] : 468 -> 464
~ __PASMurmur3_x86_128 : 1696 -> 1676
~ __PASMurmur3_x64_128 : 2256 -> 2260
~ __PAS_MurmurHash3_x86_128 : 2144 -> 2116
~ __PAS_MurmurHash3_x64_128 : 2176 -> 2180
~ -[_PASDatabaseMigrator initWithMigrationObjects:] : 528 -> 524
~ ___35-[_PASDatabaseMigrator description]_block_invoke : 312 -> 308
~ -[_PASDatabaseMigrator _migrateDatabasesWithContexts:toVersion:] : 1336 -> 1332
~ -[_PASDatabaseMigrator _unmigrateDatabasesWithContexts:] : 420 -> 416
~ -[_PASDatabaseMigrator _migrationNeededWithContexts:toVersion:] : 432 -> 428
~ -[_PASDatabaseMigrator _canContinueMigratingWithContexts:] : 656 -> 648
~ -[_PASDatabaseMigrator _skipFromZeroSchemaWithContexts:] : 636 -> 632
~ -[_PASDatabaseMigrator _anyContextHasFutureVersionWithContexts:] : 400 -> 396
~ -[_PASDatabaseMigrator _anyContextHasMismatchedVersionWithContexts:] : 432 -> 428
~ -[_PASDatabaseMigrator _allContextsAtVersionZeroWithContexts:] : 272 -> 268
~ -[_PASDatabaseMigrator _migrateOneStepToVersion:contexts:] : 892 -> 884
~ ___56-[_PASDatabaseMigrator _runQueries:nextVersion:context:]_block_invoke : 336 -> 332
~ -[_PASDatabaseMigrator _prepareContexts:] : 276 -> 272
~ ___39-[_PASDatabaseMigrator _clearDatabase:]_block_invoke : 884 -> 880
~ +[_PASZoneSupport deepCopyObject:toZone:strategy:] : 1340 -> 1332
~ -[_PASHistogramData add:a:b:] : 300 -> 296
~ -[_PASHistogramData lookupUnsmoothedA:b:] : 292 -> 308
~ __ZL7entropyRKN9proactive3pas15SynchronizedPtrIN12_GLOBAL__N_113HDGuardedDataENS0_6detail14RecursiveMutexEEEtt : 964 -> 972
~ -[_PASHistogramData deleteWhereA:b:] : 288 -> 280
~ -[_PASHistogramData initWithCoder:] : 752 -> 756
~ __ZN12_GLOBAL__N_114BuddyAllocator4freeEPKv : 1348 -> 1380
~ __ZN12_GLOBAL__N_114BuddyAllocator17allocBlock_lockedERN9proactive3pas15SynchronizedPtrINS2_10buddyalloc11GuardedDataENS2_6detail8SpinLockEEEj : 896 -> 888
~ -[_PASArgSubcommand description] : 356 -> 352
~ _makeOptionShortHelp : 536 -> 532
~ _makeOptionLongHelp : 660 -> 656
~ -[_PASArgParser description] : 540 -> 532
~ -[_PASArgParser subcommandLongHelp] : 384 -> 380
~ -[_PASArgParser _argumentParseTemplate:longArgs:] : 648 -> 644
~ __PASEvaluateLogFaultAndProbCrashCriteria : 420 -> 416
~ -[_PASUTF8String initWithUTF8Data:asciiPrefixLength:nullTerminated:] : 932 -> 928
~ -[_PASUTF8String getCharacters:range:] : 544 -> 536
~ -[_PASProxyConcatenatedString _initWithComponents:] : 752 -> 716
~ ___44+[_PASDatabaseJournal _binderForDictionary:]_block_invoke_2 : 632 -> 628
~ -[_PASKVOHandler dealloc] : 468 -> 464
~ _computeHashes_MURMUR3_X64_128 : 260 -> 252
~ -[_PASBloomFilter combineHashesWithSeed:hashA:hashB:reuse:] : 288 -> 276
~ __ZL11levenshteinIcEjPKT_S2_jj : 716 -> 704
~ __ZL11levenshteinIjEjPKT_S2_jj : 720 -> 704
~ ___46-[_PASCoalescingTimer cancelPendingOperations]_block_invoke : 324 -> 320
~ -[_PASLRUCache enumerateKeysAndObjectsUsingBlock:] : 636 -> 632
~ -[_PASDomainSelection globPatterns] : 1108 -> 1100
~ -[_PASDomainSelection initWithCoder:] : 596 -> 592
~ -[_PASMutableDomainSelection _addDomainsFrom:] : 780 -> 776
~ -[_PASMutableDomainSelection addDomainsFromSelection:] : 388 -> 384
~ -[_PASPosixDataCollector allData] : 308 -> 304
~ -[_PASLPDictionary countByEnumeratingWithState:objects:count:] : 448 -> 444
~ ___45-[_PASLPDictionary getObjects:andKeys:count:]_block_invoke : 556 -> 544
~ __PASQMarksSeparatedByCommas : 364 -> 384
~ _sqliteBlockFunction : 392 -> 400
~ -[_PASSqliteDatabase prepAndRunNonDataQueries:onError:] : 312 -> 308
~ _runDebugCommandCallback : 300 -> 292
~ ___71+[_PASLPWriterV1 _valueWordForObjectGraph:allocContext:recursionDepth:]_block_invoke_5.111 : 668 -> 660
~ ___51-[_PASAsset2 updateAssetMetadataUsingQueryResults:]_block_invoke_2 : 1452 -> 1448
~ -[_PASAsset2 _purgeObsoleteInstalledAssetsFromCandidates:guardedData:] : 768 -> 764
~ +[_PASXPCServer description] : 496 -> 492
~ -[_PASXPCServer registerXPCListeners] : 316 -> 312
```
