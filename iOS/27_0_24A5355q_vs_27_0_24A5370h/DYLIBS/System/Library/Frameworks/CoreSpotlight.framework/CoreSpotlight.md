## CoreSpotlight

> `/System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1680a4` | `0x169f84` | **`+0x1ee0`** |
| `__AUTH_CONST.__objc_const` | `0x1c8c0` | `0x1db38` | **`+0x1278`** |
| `__DATA_CONST.__objc_arraydata` | `0x12260` | `0x111c0` | **`-0x10a0`** |
| `__AUTH_CONST.__objc_dictobj` | `0xb978` | `0xaf78` | **`-0xa00`** |
| `__TEXT.__objc_methlist` | `0x12ba8` | `0x13460` | **`+0x8b8`** |
| `__AUTH.__objc_data` | `0x4c68` | `0x4f88` | **`+0x320`** |
| `__TEXT.__cstring` | `0x2b172` | `0x2b3d9` | **`+0x267`** |
| `__DATA_CONST.__objc_selrefs` | `0x9e60` | `0xa058` | **`+0x1f8`** |
| `__TEXT.__unwind_info` | `0x5850` | `0x5a30` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0x61a0` | `0x6308` | **`+0x168`** |
| `__AUTH_CONST.__cfstring` | `0x2d660` | `0x2d7a0` | **`+0x140`** |
| `__TEXT.__gcc_except_tab` | `0x8dbc` | `0x8eb0` | **`+0xf4`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3a98` | `0x39a8` | **`-0xf0`** |
| `__TEXT.__oslogstring` | `0xb168` | `0xb1f9` | **`+0x91`** |
| `__DATA.__data` | `0x1b98` | `0x1bf8` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x1298` | `0x12f4` | **`+0x5c`** |
| `__DATA_CONST.__objc_classlist` | `0x988` | `0x9d8` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x1fb0` | `0x1ff0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xd68` | `0xda0` | **`+0x38`** |
| `__DATA.__bss` | `0x1790` | `0x17b0` | **`+0x20`** |
| `__DATA_CONST.__objc_catlist` | `0x48` | `0x60` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x668` | `0x680` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x98` | `0xa0` | **`+0x8`** |

### Other Changes

```diff

-2444.104.0.0.0
+2448.100.0.0.0

-  Functions: 8237
-  Symbols:   13420
-  CStrings:  7930
+  Functions: 8412
+  Symbols:   13743
+  CStrings:  7955
Symbols:
+ +[_CSAgenticQueryTypeMappings fetchAttributesForExplicitList:]
+ +[_CSAgenticQueryTypeMappings fetchAttributesForMode:contentType:]
+ +[_CSForthValue initialize]
+ +[_CSForthValue nullValue]
+ +[_CSForthValue valueWithArray:]
+ +[_CSForthValue valueWithDate:]
+ +[_CSForthValue valueWithNumber:]
+ +[_CSForthValue valueWithString:]
+ +[_CSPipelineArrayResult resultWithItems:metadata:]
+ +[_CSPipelineCountResult resultWithCount:metadata:]
+ +[_CSPipelineGroupResult resultWithGroups:metadata:]
+ +[_CSPipelineLegacyDictResult resultWithDictionary:]
+ +[_CSQueryHelp _convertPayloadToHelpContent:]
+ +[_CSQueryHelp _payloadFromDictionary:]
+ +[_CSSearchPipelineExecutor executePipeline:typedCompletion:]
+ +[_CSSubPipelineResult emptyResult]
+ +[_CSSubPipelineResult resultWithDictionary:]
+ +[_CSSubPipelineResult resultWithError:]
+ -[CSGenericContent dictionaryRepresentation]
+ -[CSGenericContent(CSJSONSerializable) cs_toJSONObject]
+ -[CSHelpContent dictionaryRepresentation]
+ -[CSHelpContent(CSJSONSerializable) cs_toJSONObject]
+ -[CSHelpNextStep(CSJSONSerializable) cs_toJSONObject]
+ -[CSHelpSection(CSJSONSerializable) cs_toJSONObject]
+ -[CSHelpSectionContent dictionaryRepresentation]
+ -[CSInlineDonation _removeItemsForDomainIdentifier:donation:error:]
+ -[CSSearchQuery _endQuerySignpostWithError:]
+ -[CSSearchQuery isUserQuery]
+ -[CSSearchableIndex fetchCompletenessReportsForPipeline:completionHandler:]
+ -[CSSearchableIndex fetchLastLinkedTimestampForBundleID:blockOnPendingWrites:completionHandler:]
+ -[CSSearchableIndex fetchLastLinkedTimestampWithProtectionClass:forBundleID:blockOnPendingWrites:completionHandler:]
+ -[CSSearchableItem(CSJSONSerializable) cs_toJSONObject]
+ -[CSSearchableItemAttributeSet(CSPhotos_Private) homeL2Features]
+ -[CSSearchableItemAttributeSet(CSPhotos_Private) setHomeL2Features:]
+ -[CSStructuredAttributeInfo(CSJSONSerializable) cs_toJSONObject]
+ -[CSStructuredHelpExample(CSJSONSerializable) cs_toJSONObject]
+ -[CSStructuredHelpResult(CSJSONSerializable) cs_toJSONObject]
+ -[CSStructuredSchemaResult(CSJSONSerializable) cs_toJSONObject]
+ -[CSUserQuery isUserQuery]
+ -[NSArray(CSJSONSerializable) cs_toJSONObject]
+ -[NSData(CSJSONSerializable) cs_toJSONObject]
+ -[NSDate(CSJSONSerializable) cs_toJSONObject]
+ -[NSDictionary(CSJSONSerializable) cs_toJSONObject]
+ -[NSNull(CSJSONSerializable) cs_toJSONObject]
+ -[NSNumber(CSJSONSerializable) cs_toJSONObject]
+ -[NSString(CSJSONSerializable) cs_toJSONObject]
+ -[_CSBooleanPredicate acceptVisitor:]
+ -[_CSBooleanPredicate evaluateAgainstValue:]
+ -[_CSContentTypeFilter .cxx_destruct]
+ -[_CSContentTypeFilter attribute]
+ -[_CSContentTypeFilter exclusions]
+ -[_CSContentTypeFilter initWithAttribute:op:values:exclusions:]
+ -[_CSContentTypeFilter op]
+ -[_CSContentTypeFilter values]
+ -[_CSCountStage isAggregationStage]
+ -[_CSCountStage isBarrierStage]
+ -[_CSCountStage resolvedOutputTypeForInputType:error:]
+ -[_CSDatePredicate acceptVisitor:]
+ -[_CSDatePredicate evaluateAgainstValue:]
+ -[_CSDatePredicate isDatePredicate]
+ -[_CSExtractGroupItemsStage resolvedOutputTypeForInputType:error:]
+ -[_CSFilterStage isBarrierStage]
+ -[_CSFilterStage makeAttributeExtractorBlockForInputType:context:]
+ -[_CSForthValue .cxx_destruct]
+ -[_CSForthValue _initWithKind:number:string:date:array:]
+ -[_CSForthValue arrayValue]
+ -[_CSForthValue dateValue]
+ -[_CSForthValue description]
+ -[_CSForthValue hash]
+ -[_CSForthValue isEqual:]
+ -[_CSForthValue kind]
+ -[_CSForthValue numberValue]
+ -[_CSForthValue stringValue]
+ -[_CSGroupByStage fusedStageWithSuccessor:]
+ -[_CSGroupByStage isAggregationStage]
+ -[_CSGroupByStage isBarrierStage]
+ -[_CSGroupByStage isGroupByStage]
+ -[_CSGroupByStage mergePartitionResults:]
+ -[_CSGroupByStage resolvedOutputTypeForInputType:error:]
+ -[_CSHelpResponse cs_toJSONObject]
+ -[_CSHelpTopicPayload .cxx_destruct]
+ -[_CSHelpTopicPayload content]
+ -[_CSHelpTopicPayload helpTopic]
+ -[_CSHelpTopicPayload nextSteps]
+ -[_CSHelpTopicPayload setContent:]
+ -[_CSHelpTopicPayload setHelpTopic:]
+ -[_CSHelpTopicPayload setNextSteps:]
+ -[_CSHydrationStage resolvedOutputTypeForInputType:error:]
+ -[_CSLimitStage isBarrierStage]
+ -[_CSMergeStage allInputStageIds]
+ -[_CSNextStepSpec .cxx_destruct]
+ -[_CSNextStepSpec queryDict]
+ -[_CSNextStepSpec setQueryDict:]
+ -[_CSNextStepSpec setStepDescription:]
+ -[_CSNextStepSpec stepDescription]
+ -[_CSNumberPredicate acceptVisitor:]
+ -[_CSNumberPredicate evaluateAgainstValue:]
+ -[_CSNumberPredicate isNumericPredicate]
+ -[_CSNumberPredicate predicateByResolvingVariables:stageResults:stageMap:error:]
+ -[_CSNumberPredicate variableName]
+ -[_CSOneOfPredicate acceptVisitor:]
+ -[_CSOneOfPredicate evaluateAgainstValue:]
+ -[_CSOneOfPredicate isCompound]
+ -[_CSOneOfPredicate isLeaf]
+ -[_CSOneOfPredicate isOneOfPredicate]
+ -[_CSPipelineArrayResult .cxx_destruct]
+ -[_CSPipelineArrayResult description]
+ -[_CSPipelineArrayResult flatItemsPreservingGroups:]
+ -[_CSPipelineArrayResult items]
+ -[_CSPipelineArrayResult setItems:]
+ -[_CSPipelineCountResult count]
+ -[_CSPipelineCountResult description]
+ -[_CSPipelineCountResult flatItemsPreservingGroups:]
+ -[_CSPipelineCountResult setCount:]
+ -[_CSPipelineGroupResult .cxx_destruct]
+ -[_CSPipelineGroupResult description]
+ -[_CSPipelineGroupResult flatItemsPreservingGroups:]
+ -[_CSPipelineGroupResult groups]
+ -[_CSPipelineGroupResult setGroups:]
+ -[_CSPipelineLegacyDictResult .cxx_destruct]
+ -[_CSPipelineLegacyDictResult description]
+ -[_CSPipelineLegacyDictResult flatItemsPreservingGroups:]
+ -[_CSPipelineLegacyDictResult raw]
+ -[_CSPipelineLegacyDictResult setRaw:]
+ -[_CSPipelineResponse cs_toJSONObject]
+ -[_CSPipelineStageResult .cxx_destruct]
+ -[_CSPipelineStageResult description]
+ -[_CSPipelineStageResult flatItemsPreservingGroups:]
+ -[_CSPipelineStageResult initWithMetadata:]
+ -[_CSPipelineStageResult metadata]
+ -[_CSPipelineStageResult setMetadata:]
+ -[_CSPredicate acceptVisitor:]
+ -[_CSPredicate asNSPredicate]
+ -[_CSPredicate collectReferencedAttributes:]
+ -[_CSPredicate evaluateAgainstValue:]
+ -[_CSPredicate isANNPredicate]
+ -[_CSPredicate isCompound]
+ -[_CSPredicate isDatePredicate]
+ -[_CSPredicate isLeaf]
+ -[_CSPredicate isNumericPredicate]
+ -[_CSPredicate isOneOfPredicate]
+ -[_CSPredicate isStringPredicate]
+ -[_CSPredicate predicateByResolvingVariables:stageResults:stageMap:error:]
+ -[_CSPredicate predicateDebugDescription]
+ -[_CSPredicate variableName]
+ -[_CSPredicateNode(VariableResolution) cleanedCopyWasChanged:usingCleaner:]
+ -[_CSPredicateNode(VariableResolution) evaluateAgainstValueExtractor:]
+ -[_CSPredicateNode(VariableResolution) resolveVariablesWithVariables:stageResults:stageMap:error:]
+ -[_CSQueryNode cleanedCopyWasChanged:usingCleaner:]
+ -[_CSQueryNode evaluateAgainstValueExtractor:]
+ -[_CSQueryNode resolveVariablesWithVariables:stageResults:stageMap:error:]
+ -[_CSQueryOperation cleanedCopyWasChanged:usingCleaner:]
+ -[_CSQueryOperation evaluateAgainstValueExtractor:]
+ -[_CSQueryOperation resolveVariablesWithVariables:stageResults:stageMap:error:]
+ -[_CSQueryResponse cs_toJSONObject]
+ -[_CSQueryStage acceptsLiftedAttributes]
+ -[_CSQueryStage resolvedOutputTypeForInputType:error:]
+ -[_CSRankingFactDatePredicate convertFieldValueToString:]
+ -[_CSRankingFactNumberPredicate convertFieldValueToString:]
+ -[_CSRankingFactPredicate convertFieldValueToString:]
+ -[_CSRankingFactStringPredicate convertFieldValueToString:]
+ -[_CSRankingLinearModel mergeIntoLinearModel:]
+ -[_CSRankingModel mergeIntoLinearModel:]
+ -[_CSSamplingStage isBarrierStage]
+ -[_CSSchemaResponse cs_toJSONObject]
+ -[_CSSearchPipelineStage acceptsLiftedAttributes]
+ -[_CSSearchPipelineStage addLiftedAttributes:]
+ -[_CSSearchPipelineStage allInputStageIds]
+ -[_CSSearchPipelineStage fusedStageWithSuccessor:]
+ -[_CSSearchPipelineStage isAggregationStage]
+ -[_CSSearchPipelineStage isBarrierStage]
+ -[_CSSearchPipelineStage isGroupByStage]
+ -[_CSSearchPipelineStage mergePartitionResults:]
+ -[_CSSearchPipelineStage resolvedOutputTypeForInputType:error:]
+ -[_CSStringPredicate acceptVisitor:]
+ -[_CSStringPredicate evaluateAgainstValue:]
+ -[_CSStringPredicate isStringPredicate]
+ -[_CSStringPredicate predicateByResolvingVariables:stageResults:stageMap:error:]
+ -[_CSStringPredicate variableName]
+ -[_CSSubPipelineResult .cxx_destruct]
+ -[_CSSubPipelineResult error]
+ -[_CSSubPipelineResult isEmpty]
+ -[_CSSubPipelineResult result]
+ GCC_except_table103
+ GCC_except_table104
+ GCC_except_table105
+ GCC_except_table106
+ GCC_except_table1068
+ GCC_except_table118
+ GCC_except_table120
+ GCC_except_table123
+ GCC_except_table124
+ GCC_except_table127
+ GCC_except_table135
+ GCC_except_table164
+ GCC_except_table1644
+ GCC_except_table165
+ GCC_except_table1650
+ GCC_except_table168
+ GCC_except_table190
+ GCC_except_table191
+ GCC_except_table192
+ GCC_except_table212
+ GCC_except_table216
+ GCC_except_table217
+ GCC_except_table223
+ GCC_except_table224
+ GCC_except_table225
+ GCC_except_table226
+ GCC_except_table228
+ GCC_except_table234
+ GCC_except_table245
+ GCC_except_table263
+ GCC_except_table264
+ GCC_except_table265
+ GCC_except_table274
+ GCC_except_table283
+ GCC_except_table291
+ GCC_except_table292
+ GCC_except_table295
+ GCC_except_table296
+ GCC_except_table297
+ GCC_except_table299
+ GCC_except_table300
+ GCC_except_table301
+ GCC_except_table314
+ GCC_except_table321
+ GCC_except_table322
+ GCC_except_table323
+ GCC_except_table328
+ GCC_except_table329
+ GCC_except_table330
+ GCC_except_table331
+ GCC_except_table332
+ GCC_except_table333
+ GCC_except_table335
+ GCC_except_table337
+ GCC_except_table343
+ GCC_except_table346
+ GCC_except_table355
+ GCC_except_table359
+ GCC_except_table366
+ GCC_except_table368
+ GCC_except_table372
+ GCC_except_table376
+ GCC_except_table378
+ GCC_except_table455
+ GCC_except_table456
+ GCC_except_table457
+ GCC_except_table464
+ GCC_except_table501
+ GCC_except_table61
+ GCC_except_table71
+ GCC_except_table75
+ GCC_except_table90
+ GCC_except_table97
+ GCC_except_table98
+ GCC_except_table99
+ _MDItemHomeL2Features
+ _OBJC_CLASS_$__CSContentTypeFilter
+ _OBJC_CLASS_$__CSForthValue
+ _OBJC_CLASS_$__CSHelpTopicPayload
+ _OBJC_CLASS_$__CSNextStepSpec
+ _OBJC_CLASS_$__CSPipelineArrayResult
+ _OBJC_CLASS_$__CSPipelineCountResult
+ _OBJC_CLASS_$__CSPipelineGroupResult
+ _OBJC_CLASS_$__CSPipelineLegacyDictResult
+ _OBJC_CLASS_$__CSPipelineStageResult
+ _OBJC_CLASS_$__CSSubPipelineResult
+ _OBJC_IVAR_$_CSSearchQuery._querySignpostEnded
+ _OBJC_IVAR_$__CSContentTypeFilter._attribute
+ _OBJC_IVAR_$__CSContentTypeFilter._exclusions
+ _OBJC_IVAR_$__CSContentTypeFilter._op
+ _OBJC_IVAR_$__CSContentTypeFilter._values
+ _OBJC_IVAR_$__CSForthValue._array
+ _OBJC_IVAR_$__CSForthValue._date
+ _OBJC_IVAR_$__CSForthValue._kind
+ _OBJC_IVAR_$__CSForthValue._number
+ _OBJC_IVAR_$__CSForthValue._string
+ _OBJC_IVAR_$__CSHelpTopicPayload._content
+ _OBJC_IVAR_$__CSHelpTopicPayload._helpTopic
+ _OBJC_IVAR_$__CSHelpTopicPayload._nextSteps
+ _OBJC_IVAR_$__CSNextStepSpec._queryDict
+ _OBJC_IVAR_$__CSNextStepSpec._stepDescription
+ _OBJC_IVAR_$__CSPipelineArrayResult._items
+ _OBJC_IVAR_$__CSPipelineCountResult._count
+ _OBJC_IVAR_$__CSPipelineGroupResult._groups
+ _OBJC_IVAR_$__CSPipelineLegacyDictResult._raw
+ _OBJC_IVAR_$__CSPipelineStageResult._metadata
+ _OBJC_IVAR_$__CSSubPipelineResult._error
+ _OBJC_IVAR_$__CSSubPipelineResult._isEmpty
+ _OBJC_IVAR_$__CSSubPipelineResult._result
+ _OBJC_METACLASS_$__CSContentTypeFilter
+ _OBJC_METACLASS_$__CSForthValue
+ _OBJC_METACLASS_$__CSHelpTopicPayload
+ _OBJC_METACLASS_$__CSNextStepSpec
+ _OBJC_METACLASS_$__CSPipelineArrayResult
+ _OBJC_METACLASS_$__CSPipelineCountResult
+ _OBJC_METACLASS_$__CSPipelineGroupResult
+ _OBJC_METACLASS_$__CSPipelineLegacyDictResult
+ _OBJC_METACLASS_$__CSPipelineStageResult
+ _OBJC_METACLASS_$__CSSubPipelineResult
+ __CSSignpostRemapQueryErrorCode
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSData_$_CSJSONSerializable
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSDate_$_CSJSONSerializable
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSNumber_$_CSJSONSerializable
+ __OBJC_$_CATEGORY_NSArray_$_CSJSONSerializable
+ __OBJC_$_CATEGORY_NSData_$_CSJSONSerializable
+ __OBJC_$_CATEGORY_NSDate_$_CSJSONSerializable
+ __OBJC_$_CATEGORY_NSDictionary_$_CSJSONSerializable
+ __OBJC_$_CATEGORY_NSNull_$_CSJSONSerializable
+ __OBJC_$_CATEGORY_NSNumber_$_CSJSONSerializable
+ __OBJC_$_CATEGORY_NSString_$_CSJSONSerializable
+ __OBJC_$_CLASS_METHODS_CSSearchableItem(CSJSONSerializable|CSIndexQueueableItemAdditions|Internal)
+ __OBJC_$_CLASS_METHODS__CSForthValue
+ __OBJC_$_CLASS_METHODS__CSPipelineArrayResult
+ __OBJC_$_CLASS_METHODS__CSPipelineCountResult
+ __OBJC_$_CLASS_METHODS__CSPipelineGroupResult
+ __OBJC_$_CLASS_METHODS__CSPipelineLegacyDictResult
+ __OBJC_$_CLASS_METHODS__CSSubPipelineResult
+ __OBJC_$_INSTANCE_METHODS_CSGenericContent(CSJSONSerializable)
+ __OBJC_$_INSTANCE_METHODS_CSHelpContent(CSJSONSerializable)
+ __OBJC_$_INSTANCE_METHODS_CSHelpNextStep(CSJSONSerializable)
+ __OBJC_$_INSTANCE_METHODS_CSHelpSection(CSJSONSerializable)
+ __OBJC_$_INSTANCE_METHODS_CSSearchableItem(CSJSONSerializable|CSIndexQueueableItemAdditions|Internal)
+ __OBJC_$_INSTANCE_METHODS_CSStructuredAttributeInfo(CSJSONSerializable)
+ __OBJC_$_INSTANCE_METHODS_CSStructuredHelpExample(CSJSONSerializable)
+ __OBJC_$_INSTANCE_METHODS_CSStructuredHelpResult(CSJSONSerializable)
+ __OBJC_$_INSTANCE_METHODS_CSStructuredSchemaResult(CSJSONSerializable)
+ __OBJC_$_INSTANCE_METHODS_NSArray(CSJSONSerializable|CSCoderAdditions)
+ __OBJC_$_INSTANCE_METHODS_NSDictionary(CSJSONSerializable|CSCoderAdditions)
+ __OBJC_$_INSTANCE_METHODS_NSNull(CSJSONSerializable|CSCoderAdditions)
+ __OBJC_$_INSTANCE_METHODS_NSString(CSJSONSerializable|CSCoderAdditions|CSAdditions|CSBundles|CSUserQuery)
+ __OBJC_$_INSTANCE_METHODS__CSContentTypeFilter
+ __OBJC_$_INSTANCE_METHODS__CSForthValue
+ __OBJC_$_INSTANCE_METHODS__CSHelpTopicPayload
+ __OBJC_$_INSTANCE_METHODS__CSNextStepSpec
+ __OBJC_$_INSTANCE_METHODS__CSPipelineArrayResult
+ __OBJC_$_INSTANCE_METHODS__CSPipelineCountResult
+ __OBJC_$_INSTANCE_METHODS__CSPipelineGroupResult
+ __OBJC_$_INSTANCE_METHODS__CSPipelineLegacyDictResult
+ __OBJC_$_INSTANCE_METHODS__CSPipelineStageResult
+ __OBJC_$_INSTANCE_METHODS__CSPredicateNode(VariableResolution)
+ __OBJC_$_INSTANCE_METHODS__CSSubPipelineResult
+ __OBJC_$_INSTANCE_VARIABLES__CSContentTypeFilter
+ __OBJC_$_INSTANCE_VARIABLES__CSForthValue
+ __OBJC_$_INSTANCE_VARIABLES__CSHelpTopicPayload
+ __OBJC_$_INSTANCE_VARIABLES__CSNextStepSpec
+ __OBJC_$_INSTANCE_VARIABLES__CSPipelineArrayResult
+ __OBJC_$_INSTANCE_VARIABLES__CSPipelineCountResult
+ __OBJC_$_INSTANCE_VARIABLES__CSPipelineGroupResult
+ __OBJC_$_INSTANCE_VARIABLES__CSPipelineLegacyDictResult
+ __OBJC_$_INSTANCE_VARIABLES__CSPipelineStageResult
+ __OBJC_$_INSTANCE_VARIABLES__CSSubPipelineResult
+ __OBJC_$_PROP_LIST_NSArray_$_CSJSONSerializable
+ __OBJC_$_PROP_LIST_NSData_$_CSJSONSerializable
+ __OBJC_$_PROP_LIST_NSDate_$_CSJSONSerializable
+ __OBJC_$_PROP_LIST_NSDictionary_$_CSJSONSerializable
+ __OBJC_$_PROP_LIST_NSNull_$_CSJSONSerializable
+ __OBJC_$_PROP_LIST_NSNumber_$_CSJSONSerializable
+ __OBJC_$_PROP_LIST_NSString_$_CSJSONSerializable
+ __OBJC_$_PROP_LIST__CSContentTypeFilter
+ __OBJC_$_PROP_LIST__CSForthValue
+ __OBJC_$_PROP_LIST__CSHelpResponse
+ __OBJC_$_PROP_LIST__CSHelpTopicPayload
+ __OBJC_$_PROP_LIST__CSNextStepSpec
+ __OBJC_$_PROP_LIST__CSPipelineArrayResult
+ __OBJC_$_PROP_LIST__CSPipelineCountResult
+ __OBJC_$_PROP_LIST__CSPipelineGroupResult
+ __OBJC_$_PROP_LIST__CSPipelineLegacyDictResult
+ __OBJC_$_PROP_LIST__CSPipelineResponse
+ __OBJC_$_PROP_LIST__CSPipelineStageResult
+ __OBJC_$_PROP_LIST__CSQueryResponse
+ __OBJC_$_PROP_LIST__CSSchemaResponse
+ __OBJC_$_PROP_LIST__CSSubPipelineResult
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSJSONSerializable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSJSONSerializable
+ __OBJC_$_PROTOCOL_REFS_CSJSONSerializable
+ __OBJC_CATEGORY_PROTOCOLS_$_NSData_$_CSJSONSerializable
+ __OBJC_CATEGORY_PROTOCOLS_$_NSDate_$_CSJSONSerializable
+ __OBJC_CATEGORY_PROTOCOLS_$_NSNumber_$_CSJSONSerializable
+ __OBJC_CLASS_PROTOCOLS_$_CSGenericContent(CSJSONSerializable)
+ __OBJC_CLASS_PROTOCOLS_$_CSHelpContent(CSJSONSerializable)
+ __OBJC_CLASS_PROTOCOLS_$_CSHelpNextStep(CSJSONSerializable)
+ __OBJC_CLASS_PROTOCOLS_$_CSHelpSection(CSJSONSerializable)
+ __OBJC_CLASS_PROTOCOLS_$_CSSearchableItem(CSJSONSerializable|CSIndexQueueableItemAdditions|Internal)
+ __OBJC_CLASS_PROTOCOLS_$_CSStructuredAttributeInfo(CSJSONSerializable)
+ __OBJC_CLASS_PROTOCOLS_$_CSStructuredHelpExample(CSJSONSerializable)
+ __OBJC_CLASS_PROTOCOLS_$_CSStructuredHelpResult(CSJSONSerializable)
+ __OBJC_CLASS_PROTOCOLS_$_CSStructuredSchemaResult(CSJSONSerializable)
+ __OBJC_CLASS_PROTOCOLS_$_NSArray(CSJSONSerializable|CSCoderAdditions)
+ __OBJC_CLASS_PROTOCOLS_$_NSDictionary(CSJSONSerializable|CSCoderAdditions)
+ __OBJC_CLASS_PROTOCOLS_$_NSNull(CSJSONSerializable|CSCoderAdditions)
+ __OBJC_CLASS_PROTOCOLS_$_NSString(CSJSONSerializable|CSCoderAdditions|CSAdditions|CSBundles|CSUserQuery)
+ __OBJC_CLASS_PROTOCOLS_$__CSHelpResponse
+ __OBJC_CLASS_PROTOCOLS_$__CSPipelineResponse
+ __OBJC_CLASS_PROTOCOLS_$__CSQueryResponse
+ __OBJC_CLASS_PROTOCOLS_$__CSSchemaResponse
+ __OBJC_CLASS_RO_$__CSContentTypeFilter
+ __OBJC_CLASS_RO_$__CSForthValue
+ __OBJC_CLASS_RO_$__CSHelpTopicPayload
+ __OBJC_CLASS_RO_$__CSNextStepSpec
+ __OBJC_CLASS_RO_$__CSPipelineArrayResult
+ __OBJC_CLASS_RO_$__CSPipelineCountResult
+ __OBJC_CLASS_RO_$__CSPipelineGroupResult
+ __OBJC_CLASS_RO_$__CSPipelineLegacyDictResult
+ __OBJC_CLASS_RO_$__CSPipelineStageResult
+ __OBJC_CLASS_RO_$__CSSubPipelineResult
+ __OBJC_LABEL_PROTOCOL_$_CSJSONSerializable
+ __OBJC_METACLASS_RO_$__CSContentTypeFilter
+ __OBJC_METACLASS_RO_$__CSForthValue
+ __OBJC_METACLASS_RO_$__CSHelpTopicPayload
+ __OBJC_METACLASS_RO_$__CSNextStepSpec
+ __OBJC_METACLASS_RO_$__CSPipelineArrayResult
+ __OBJC_METACLASS_RO_$__CSPipelineCountResult
+ __OBJC_METACLASS_RO_$__CSPipelineGroupResult
+ __OBJC_METACLASS_RO_$__CSPipelineLegacyDictResult
+ __OBJC_METACLASS_RO_$__CSPipelineStageResult
+ __OBJC_METACLASS_RO_$__CSSubPipelineResult
+ __OBJC_PROTOCOL_$_CSJSONSerializable
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__111nth_elementB9fqe220106INS_11__wrap_iterIPP12NSDictionaryEEZL24executeSelectAggregationP14_CSSelectIndexP8NSStringP7NSArraybSA_E3$_0EEvT_SE_SE_T0_
+ __ZNSt3__111nth_elementB9fqe220106INS_11__wrap_iterIPP12NSDictionaryEEZL24executeSelectAggregationP14_CSSelectIndexP8NSStringP7NSArraybSA_E3$_1EEvT_SE_SE_T0_
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIP12NSDictionaryEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorIN12_GLOBAL__N_18WorkItemENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIP12NSDictionaryNS_9allocatorIS3_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__19__sift_upB9fqe220106INS_17_ClassicAlgPolicyERN12_GLOBAL__N_118WorkItemComparatorENS_11__wrap_iterIPNS2_8WorkItemEEEEEvT1_S9_OT0_NS_15iterator_traitsIS9_E15difference_typeE
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___116-[CSSearchableIndex fetchLastLinkedTimestampWithProtectionClass:forBundleID:blockOnPendingWrites:completionHandler:]_block_invoke
+ ___116-[CSSearchableIndex fetchLastLinkedTimestampWithProtectionClass:forBundleID:blockOnPendingWrites:completionHandler:]_block_invoke_2
+ ___116-[CSSearchableIndex fetchLastLinkedTimestampWithProtectionClass:forBundleID:blockOnPendingWrites:completionHandler:]_block_invoke_3
+ ___116-[CSSearchableIndex fetchLastLinkedTimestampWithProtectionClass:forBundleID:blockOnPendingWrites:completionHandler:]_block_invoke_4
+ ___41-[_CSDatePredicate evaluateAgainstValue:]_block_invoke
+ ___45-[NSDate(CSJSONSerializable) cs_toJSONObject]_block_invoke
+ ___51-[NSDictionary(CSJSONSerializable) cs_toJSONObject]_block_invoke
+ ___53-[CSFileProviderContainerCache dumpAppContainerCache]_block_invoke
+ ___54-[_CSFilterStage evaluatePredicate:againstDictionary:]_block_invoke
+ ___55-[CSSearchableItem(CSJSONSerializable) cs_toJSONObject]_block_invoke
+ ___56-[_CSFilterStage evaluatePredicate:againstItem:context:]_block_invoke
+ ___61+[_CSSearchPipelineExecutor executePipeline:typedCompletion:]_block_invoke
+ ___61+[_CSSearchPipelineExecutor executePipeline:typedCompletion:]_block_invoke_2
+ ___66-[_CSFilterStage makeAttributeExtractorBlockForInputType:context:]_block_invoke
+ ___66-[_CSFilterStage makeAttributeExtractorBlockForInputType:context:]_block_invoke_2
+ ___75-[CSSearchableIndex fetchCompletenessReportsForPipeline:completionHandler:]_block_invoke
+ ___75-[CSSearchableIndex fetchCompletenessReportsForPipeline:completionHandler:]_block_invoke_2
+ ___75-[CSSearchableIndex fetchCompletenessReportsForPipeline:completionHandler:]_block_invoke_3
+ ___block_descriptor_40_e8_32bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32s_e25_v32?0"NSString"816^B24ls32l8
+ ___block_descriptor_40_e8_32s_e46_v32?0"NSString"8"NSMutableDictionary"16^B24ls32l8
+ ___block_descriptor_40_ea8_32bs_e21_24?08"NSString"16ls32l8
+ ___block_descriptor_40_ea8_32s_e21_24?08"NSString"16ls32l8
+ ___block_descriptor_48_ea8_32bs40bs_e21_24?08"NSString"16ls32l8s40l8
+ ___block_descriptor_48_ea8_32s40s_e21_24?08"NSString"16ls32l8s40l8
+ ___block_descriptor_73_e8_32s40s48s56bs64w_e5_v8?0ls32l8s40l8s48l8w64l8s56l8
+ ___buildTypeMap_block_invoke
+ ___cs_predicate_node_log_block_invoke
+ ___destructor_8_s0_s8_S_s24
+ _convertItemArrayToSearchableItems
+ _cs_predicate_node_log
+ _cs_predicate_node_log.log
+ _cs_predicate_node_log.onceToken
+ _cs_toJSONObject.formatter
+ _cs_toJSONObject.onceToken
+ _evaluateAgainstValue:.iso
+ _evaluateAgainstValue:.once
+ _makeEqualsFilter
+ _makeFilter
+ _predicateNode_inferVariableFromStageResults
+ _sNullValue
+ _sTypeMap
+ _sTypeMapOnce
- +[_CSAgenticQueryParser dictionaryFromGenericContent:]
- +[_CSAgenticQueryParser dictionaryFromHelpContent:]
- +[_CSAgenticQueryParser dictionaryFromHelpSection:]
- +[_CSAgenticQueryTypeMappings fetchAttributesForShow:contentType:]
- +[_CSPartitioningPipelineExecutor mergeGroupByPartitionResults:]
- +[_CSQueryPipeline resolveOutputType:inputType:error:]
- +[_CSSearchPipelineStage(Utilities) _resolveVariablesInOperation:variables:stageResults:stageMap:error:]
- +[_CSSearchPipelineStage(Utilities) _resolveVariablesInPredicateNode:variables:stageResults:stageMap:error:]
- -[CSSearchableIndex fetchLastLinkedTimestampWithProtectionClass:forBundleID:completionHandler:]
- -[_CSFilterStage evaluateBooleanPredicate:againstValue:]
- -[_CSFilterStage evaluateDatePredicate:againstValue:]
- -[_CSFilterStage evaluateNumberPredicate:againstValue:]
- -[_CSFilterStage evaluateOperation:againstDictionary:]
- -[_CSFilterStage evaluatePredicateNode:againstDictionary:]
- -[_CSFilterStage evaluateStringPredicate:againstValue:]
- -[_CSQueryOperation _cleanedNodeCopy:wasChanged:]
- -[_CSQueryOperation _cleanedTemporalPredicateCopy:wasChanged:]
- GCC_except_table1066
- GCC_except_table107
- GCC_except_table109
- GCC_except_table111
- GCC_except_table114
- GCC_except_table115
- GCC_except_table116
- GCC_except_table129
- GCC_except_table140
- GCC_except_table141
- GCC_except_table142
- GCC_except_table145
- GCC_except_table147
- GCC_except_table148
- GCC_except_table152
- GCC_except_table1642
- GCC_except_table1648
- GCC_except_table182
- GCC_except_table183
- GCC_except_table197
- GCC_except_table202
- GCC_except_table205
- GCC_except_table206
- GCC_except_table207
- GCC_except_table208
- GCC_except_table210
- GCC_except_table214
- GCC_except_table233
- GCC_except_table241
- GCC_except_table243
- GCC_except_table244
- GCC_except_table246
- GCC_except_table251
- GCC_except_table256
- GCC_except_table259
- GCC_except_table260
- GCC_except_table261
- GCC_except_table271
- GCC_except_table282
- GCC_except_table287
- GCC_except_table289
- GCC_except_table298
- GCC_except_table303
- GCC_except_table304
- GCC_except_table307
- GCC_except_table309
- GCC_except_table311
- GCC_except_table316
- GCC_except_table320
- GCC_except_table341
- GCC_except_table352
- GCC_except_table356
- GCC_except_table365
- GCC_except_table369
- GCC_except_table370
- GCC_except_table375
- GCC_except_table451
- GCC_except_table452
- GCC_except_table453
- GCC_except_table461
- GCC_except_table498
- GCC_except_table65
- GCC_except_table73
- GCC_except_table80
- GCC_except_table83
- GCC_except_table85
- GCC_except_table86
- GCC_except_table93
- GCC_except_table95
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSArray_$_CSCoderAdditions
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSDictionary_$_CSCoderAdditions
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSNull_$_CSCoderAdditions
- __OBJC_$_CATEGORY_NSArray_$_CSCoderAdditions
- __OBJC_$_CATEGORY_NSDictionary_$_CSCoderAdditions
- __OBJC_$_CATEGORY_NSNull_$_CSCoderAdditions
- __OBJC_$_CATEGORY_NSString_$_CSCoderAdditions
- __OBJC_$_CLASS_METHODS_CSSearchableItem(CSIndexQueueableItemAdditions|Internal)
- __OBJC_$_INSTANCE_METHODS_CSGenericContent
- __OBJC_$_INSTANCE_METHODS_CSHelpContent
- __OBJC_$_INSTANCE_METHODS_CSHelpNextStep
- __OBJC_$_INSTANCE_METHODS_CSHelpSection
- __OBJC_$_INSTANCE_METHODS_CSSearchableItem(CSIndexQueueableItemAdditions|Internal)
- __OBJC_$_INSTANCE_METHODS_CSStructuredAttributeInfo
- __OBJC_$_INSTANCE_METHODS_CSStructuredHelpExample
- __OBJC_$_INSTANCE_METHODS_CSStructuredHelpResult
- __OBJC_$_INSTANCE_METHODS_CSStructuredSchemaResult
- __OBJC_$_INSTANCE_METHODS_NSString(CSCoderAdditions|CSAdditions|CSBundles|CSUserQuery)
- __OBJC_$_INSTANCE_METHODS__CSPredicateNode
- __OBJC_$_PROP_LIST_CSGenericContent
- __OBJC_$_PROP_LIST_CSHelpContent
- __OBJC_$_PROP_LIST_CSHelpNextStep
- __OBJC_$_PROP_LIST_CSHelpSection
- __OBJC_$_PROP_LIST_CSSearchableItem
- __OBJC_$_PROP_LIST_CSStructuredAttributeInfo
- __OBJC_$_PROP_LIST_CSStructuredHelpExample
- __OBJC_$_PROP_LIST_CSStructuredHelpResult
- __OBJC_$_PROP_LIST_CSStructuredSchemaResult
- __OBJC_CATEGORY_PROTOCOLS_$_NSArray_$_CSCoderAdditions
- __OBJC_CATEGORY_PROTOCOLS_$_NSDictionary_$_CSCoderAdditions
- __OBJC_CATEGORY_PROTOCOLS_$_NSNull_$_CSCoderAdditions
- __OBJC_CATEGORY_PROTOCOLS_$_NSString_$_CSCoderAdditions
- __OBJC_CLASS_PROTOCOLS_$_CSSearchableItem(CSIndexQueueableItemAdditions|Internal)
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__111nth_elementB9fqe220100INS_11__wrap_iterIPP12NSDictionaryEEZL24executeSelectAggregationP14_CSSelectIndexP8NSStringP7NSArraybSA_E3$_0EEvT_SE_SE_T0_
- __ZNSt3__111nth_elementB9fqe220100INS_11__wrap_iterIPP12NSDictionaryEEZL24executeSelectAggregationP14_CSSelectIndexP8NSStringP7NSArraybSA_E3$_1EEvT_SE_SE_T0_
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIP12NSDictionaryEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorIN12_GLOBAL__N_18WorkItemENS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIP12NSDictionaryNS_9allocatorIS3_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__19__sift_upB9fqe220100INS_17_ClassicAlgPolicyERN12_GLOBAL__N_118WorkItemComparatorENS_11__wrap_iterIPNS2_8WorkItemEEEEEvT1_S9_OT0_NS_15iterator_traitsIS9_E15difference_typeE
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- ___52+[_CSAgenticQueryTypeMappings filterForContentType:]_block_invoke
- ___56+[_CSSearchPipelineExecutor executePipeline:completion:]_block_invoke
- ___95-[CSSearchableIndex fetchLastLinkedTimestampWithProtectionClass:forBundleID:completionHandler:]_block_invoke
- ___95-[CSSearchableIndex fetchLastLinkedTimestampWithProtectionClass:forBundleID:completionHandler:]_block_invoke_2
- ___95-[CSSearchableIndex fetchLastLinkedTimestampWithProtectionClass:forBundleID:completionHandler:]_block_invoke_3
- ___95-[CSSearchableIndex fetchLastLinkedTimestampWithProtectionClass:forBundleID:completionHandler:]_block_invoke_4
- ___block_descriptor_72_e8_32s40s48s56bs64w_e5_v8?0ls32l8s40l8s48l8w64l8s56l8
- ___destructor_8_s0_s8_s16
- ___makeValueJSONSafe_block_invoke
- ___makeValueJSONSafe_block_invoke_2
- ___makeValueJSONSafe_block_invoke_3
- _convertDictionaryToCSSearchableItem
- _filterForContentType:.onceToken
- _filterForContentType:.typeMap
- _inferVariableFromStageResults
- _makeValueJSONSafe
- _makeValueJSONSafe.formatter
- _makeValueJSONSafe.onceToken
- _stageIsAggregation
- _stageIsBarrier
- _typeError
CStrings:
+ " typed=%@ attr=%@ count=%lu"
+ "(null)"
+ "99"
+ "<%@: %p count=%ld metadata=%@>"
+ "<%@: %p count=%lu metadata=%@>"
+ "<%@: %p groupCount=%lu metadata=%@>"
+ "<%@: %p metadata=%@>"
+ "<%@: %p raw=%@>"
+ "<no compile>"
+ "@24@?0@8@\"NSString\"16"
+ "Array"
+ "CSQueryFirstResult"
+ "CSSearchQuery"
+ "ErrorCode=%{public,signpost.telemetry:string1}s, QueryLength=%{public,signpost.telemetry:number1}lu, FoundCount=%{public,signpost.telemetry:number2}lu  enableTelemetry=YES "
+ "ExtractGroupItemsStage requires RecordArray input"
+ "HydrationStage requires ItemArray input"
+ "Null"
+ "QueryClass=%{signpost.description:attribute}s, qid=%{signpost.description:attribute}lu"
+ "Resolved variable: %@"
+ "Type error: 'day' expects a date"
+ "Type error: 'dayOfWeek' expects a date"
+ "Type error: 'hour' expects a date"
+ "Type error: 'minute' expects a date"
+ "Type error: 'month' expects a date"
+ "Type error: 'quarter' expects a date"
+ "Type error: 'year' expects a date"
+ "[kind:%@ value:%@]"
+ "[qid=%ld] Not targeting any specific indexes"
+ "[qid=%ld] Targeting indexes: %@"
+ "_CSQueryOperation.cleanedCopyWithSchema: child returned nil, skipping [%s:%d %s]"
+ "__unknown__"
+ "_kMDItemHomeL2Features"
+ "block-on-pending-writes"
+ "crash-report"
+ "crash-reports"
+ "crashreports"
+ "diagnostic"
+ "diagnostics"
+ "fetch-pipeline-completeness-reports"
+ "fetchCompletenessReportsForPipeline"
+ "fused"
+ "homeL2Features plist serialization failed: %@"
+ "pipeline-completeness-reports-data"
+ "pipeline-completeness-reports-data-size"
+ "pipeline-completeness-reports-pipeline"
+ "🔧 [QueryStage]       inner-pred[%lu.%lu.%lu] class=%s compiled=%s\n"
+ "🔧 [QueryStage]     grandchild[%lu.%lu] class=%s compiled=%s%s\n"
+ "🔧 [QueryStage]   child[%lu] class=%s desc=%s compiled=%s\n"
+ "🔧 [QueryStage] Compiled query string: %s\n"
+ "🔧 [QueryStage] resolved QueryNode: %s\n"
- "ExtractGroupItems"
- "FieldMatch(%@,%@)"
- "Hydration"
- "Invalid child type (must be predicate or operation)"
- "Merging GroupBy partition results"
- "Output stage '%@' not found in results"
- "Resolved variable: %@ -> %@"
- "Stage '%@' (%@) requires %@ input but received %ld"
- "Type error: 'day' expects NSDate, got %@"
- "Type error: 'dayOfWeek' expects NSDate, got %@"
- "Type error: 'hour' expects NSDate, got %@"
- "Type error: 'minute' expects NSDate, got %@"
- "Type error: 'month' expects NSDate, got %@"
- "Type error: 'quarter' expects NSDate, got %@"
- "Type error: 'year' expects NSDate, got %@"
- "Unknown predicate node type: %@"
- "Variable '%{public}@' not found in variables dictionary"
- "[_CSStringPredicate] Non-string attribute or value in predicate (attribute class: %@, value class: %@) — predicate cannot be compiled"
- "_CSGroupByStage"
- "_metadata"
- "exclusions"
- "itemArray"
- "recordArray"
- "section"
- "⚠️ _CSQueryOperation.cleanedCopyWithSchema: child returned nil, skipping [%s:%d %s]"
```
