## CascadeSets

> `/System/Library/PrivateFrameworks/CascadeSets.framework/CascadeSets`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa88f4` | `0xa96ac` | **`+0xdb8`** |
| `__AUTH_CONST.__objc_const` | `0x120c8` | `0x12270` | **`+0x1a8`** |
| `__TEXT.__cstring` | `0x880f` | `0x891f` | **`+0x110`** |
| `__DATA.__data` | `0x1ba0` | `0x1ae0` | **`-0xc0`** |
| `__AUTH.__objc_data` | `0x1370` | `0x1410` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x3130` | `0x31c0` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x5264` | `0x52d4` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x5980` | `0x59e0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x6544` | `0x6594` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x1798` | `0x17dc` | **`+0x44`** |
| `__TEXT.__unwind_info` | `0x3268` | `0x3290` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1bb0` | `0x1bc8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x6b8` | `0x6d0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x674` | `0x688` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x510` | `0x520` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x1f8` | `0x1e8` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0xc8` | `0xb8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xd60` | `0xd68` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x350` | `0x358` | **`+0x8`** |

### Other Changes

```diff

-236.0.2.0.0
+239.0.2.0.0

-  Functions: 4633
-  Symbols:   5096
-  CStrings:  1304
+  Functions: 4648
+  Symbols:   5115
+  CStrings:  1308
Symbols:
+ +[CCCachedDocumentUtilities cacheMetaContentFromAssociatedItemContent:associatedItemMetaContent:priorCacheMetaContent:associatedSetKey:error:]
+ +[CCCachedDocumentUtilities cacheMetaContentFromStoredMetaContent:evictedDate:error:]
+ +[CCCachedDocumentUtilities validateAssociatedItemMetaContent:outHasCacheContentHash:error:]
+ +[CCSQLCommandCriterion criterionWithColumnName:beginsWithStringValue:]
+ -[CCDaemon initWithQueue:setBookkeeping:registerScheduledTasks:]
+ -[CCDataResourceReadAccess storageFootprintForSet:error:]
+ -[CCDataResourceWriteAccess _performMaintenanceForSet:withResource:accessAssertion:shouldDefer:options:detectedCorruption:]
+ -[CCDatabaseItemRetriever _selectForEnumeratingSourceItemIdHashesMatchingPredicate:error:]
+ -[CCDatabaseWriter startDate]
+ -[CCIncrementalSetDonation evictCacheContentWithStorageReductionPercentageTarget:evictionCandidateBatchProvider:error:]
+ -[CCSet storageFootprintWithUseCase:error:]
+ -[CCSetDistribution initWithSet:sharedItemCount:localInstanceCount:sizeInBytes:]
+ -[CCSetDonation finishReturningResult:]
+ -[CCSetDonationCacheEvictionResult finalStorageFootprintBytes]
+ -[CCSetDonationCacheEvictionResult initWithInitialStorageFootprintBytes:finalStorageFootprintBytes:]
+ -[CCSetDonationCacheEvictionResult initialStorageFootprintBytes]
+ -[CCSetsAccessDaemonDelegate _atomicallyCreateDataResource:inContainer:error:]
+ -[CCSetsAccessDaemonDelegate prepareResource:withMode:inContainer:error:]
+ GCC_except_table52
+ GCC_except_table8
+ _CCDatabaseErrorIsCorruption
+ _CCSetErrorForWriterDatabaseError
+ _NSURLFileSizeKey
+ _NSURLIsRegularFileKey
+ _OBJC_CLASS_$_BMDataProtection
+ _OBJC_CLASS_$_CCSetDonationCacheEvictionResult
+ _OBJC_CLASS_$_CCSetDonationResult
+ _OBJC_IVAR_$_CCDaemon._registerScheduledTasks
+ _OBJC_IVAR_$_CCDatabaseWriter._startDate
+ _OBJC_IVAR_$_CCSetDistribution._sizeInBytes
+ _OBJC_IVAR_$_CCSetDonationCacheEvictionResult._finalStorageFootprintBytes
+ _OBJC_IVAR_$_CCSetDonationCacheEvictionResult._initialStorageFootprintBytes
+ _OBJC_METACLASS_$_CCSetDonationCacheEvictionResult
+ _OBJC_METACLASS_$_CCSetDonationResult
+ __OBJC_$_INSTANCE_METHODS_CCSetDonationCacheEvictionResult
+ __OBJC_$_INSTANCE_VARIABLES_CCSetDonationCacheEvictionResult
+ __OBJC_$_PROP_LIST_CCSetDonationCacheEvictionResult
+ __OBJC_CLASS_RO_$_CCSetDonationCacheEvictionResult
+ __OBJC_CLASS_RO_$_CCSetDonationResult
+ __OBJC_METACLASS_RO_$_CCSetDonationCacheEvictionResult
+ __OBJC_METACLASS_RO_$_CCSetDonationResult
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220106Ev
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___123-[CCDataResourceWriteAccess _performMaintenanceForSet:withResource:accessAssertion:shouldDefer:options:detectedCorruption:]_block_invoke
+ ___57-[CCDataResourceReadAccess storageFootprintForSet:error:]_block_invoke
+ _objc_opt_respondsToSelector
- +[CCCachedDocumentUtilities cacheMetaContentFromAssociatedItemContent:associatedItemMetaContent:associatedSetKey:error:]
- +[CCSQLCommandCriterion escapedLikeString:]
- -[CCDaemon initWithQueue:setBookkeeping:]
- -[CCDataResourceWriteAccess _performMaintenanceForSet:withResource:accessAssertion:shouldDefer:options:]
- -[CCSetDistribution _sanitizedEncodedDescriptors]
- -[CCSetDistribution initWithSet:sharedItemCount:localInstanceCount:]
- -[CCSetsAccessDaemonDelegate _atomicallyCreateDataResource:inContainer:]
- -[CCSetsAccessDaemonDelegate prepareResource:withMode:inContainer:]
- GCC_except_table51
- GCC_except_table55
- _OUTLINED_FUNCTION_43
- __OBJC_$_PROP_LIST_CCCacheKeyAssociated
- __OBJC_$_PROP_LIST_CCExpirable
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_CCCacheKeyAssociated
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_CCExpirable
- __OBJC_$_PROTOCOL_METHOD_TYPES_CCCacheKeyAssociated
- __OBJC_$_PROTOCOL_METHOD_TYPES_CCExpirable
- __OBJC_$_PROTOCOL_REFS_CCExpirable
- __OBJC_LABEL_PROTOCOL_$_CCCacheKeyAssociated
- __OBJC_LABEL_PROTOCOL_$_CCExpirable
- __OBJC_PROTOCOL_$_CCCacheKeyAssociated
- __OBJC_PROTOCOL_$_CCExpirable
- __OBJC_PROTOCOL_REFERENCE_$_CCCacheKeyAssociated
- __OBJC_PROTOCOL_REFERENCE_$_CCExpirable
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220100Ev
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- ___104-[CCDataResourceWriteAccess _performMaintenanceForSet:withResource:accessAssertion:shouldDefer:options:]_block_invoke
CStrings:
+ "(%@ >= %@ AND %@ < %@)"
+ "Associated item metacontent %@ for cache content does not respond to @selector(hasCacheContentHash)"
+ "CCSQLCommandCriterion.m"
+ "Data protection restricted"
+ "Detected unrecoverable database corruption during maintenance for set: %@ (%@) error: %@. Resource will be removed."
+ "Failed to commit maintenance for set: %@ (%@) error: %@"
+ "Failed to get sizeOfSetInBytes for set: %@ error: %@"
+ "Invalid argument"
+ "Missing cacheContentHash"
+ "percentage must be in (0, 1]; got %f"
+ "priorCacheMetaContent"
+ "sizeInBytes"
+ "storedMetaContent"
+ "stringPrefix != nil"
- "%"
- "%@ LIKE %@ ESCAPE '\\'"
- "Failed to encode sanitized descriptors for set: %@ error: %@"
- "Filtering out descriptor with key: %@ for set: %@"
- "\\"
- "\\%"
- "\\\\"
- "\\_"
- "_"
- "isSynchronized"
```
