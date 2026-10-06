## CoreSpotlight

> `/System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x169f84` | `0x17467c` | **`+0xa6f8`** |
| `__AUTH_CONST.__objc_const` | `0x1db38` | `0x1f248` | **`+0x1710`** |
| `__TEXT.__objc_methlist` | `0x13460` | `0x14190` | **`+0xd30`** |
| `__AUTH.__objc_data` | `0x4f88` | `0x5af0` | **`+0xb68`** |
| `__DATA_DIRTY.__objc_data` | `0x12e8` | `0xe10` | **`-0x4d8`** |
| `__AUTH_CONST.__cfstring` | `0x2d7a0` | `0x2dae0` | **`+0x340`** |
| `__TEXT.__cstring` | `0x2b3d9` | `0x2b714` | **`+0x33b`** |
| `__DATA_CONST.__objc_selrefs` | `0xa058` | `0xa388` | **`+0x330`** |
| `__TEXT.__unwind_info` | `0x5a30` | `0x5d38` | **`+0x308`** |
| `__AUTH_CONST.__const` | `0x1ff0` | `0x2270` | **`+0x280`** |
| `__TEXT.__gcc_except_tab` | `0x8eb0` | `0x90d4` | **`+0x224`** |
| `__DATA_CONST.__const` | `0x6308` | `0x6478` | **`+0x170`** |
| `__DATA.__bss` | `0x17b0` | `0x18f0` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0xb1f9` | `0xb312` | **`+0x119`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x39a8` | `0x3ab0` | **`+0x108`** |
| `__DATA.__objc_ivar` | `0x12f4` | `0x13ac` | **`+0xb8`** |
| `__DATA_CONST.__objc_classlist` | `0x9d8` | `0xa80` | **`+0xa8`** |
| `__DATA_CONST.__got` | `0xda0` | `0xe40` | **`+0xa0`** |
| `__DATA_CONST.__objc_arraydata` | `0x111c0` | `0x11250` | **`+0x90`** |
| `__DATA_CONST.__objc_superrefs` | `0x680` | `0x710` | **`+0x90`** |
| `__AUTH_CONST.__objc_intobj` | `0xdb0` | `0xdf8` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x1060` | `0x1070` | **`+0x10`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x160` | `0x170` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0xa7e8` | `0xa7f8` | **`+0x10`** |
| `__TEXT.__const` | `0xe98` | `0xea8` | **`+0x10`** |

### Other Changes

```diff

-2448.100.0.0.0
+2451.1.101.0.0

-  Functions: 8412
-  Symbols:   13743
-  CStrings:  7955
+  Functions: 8713
+  Symbols:   14278
+  CStrings:  8002
Symbols:
+ +[CSAbsoluteDatePredicate supportsSecureCoding]
+ +[CSAuthorPredicate personWithName:]
+ +[CSAuthorPredicate personWithPerson:]
+ +[CSBooleanPredicate supportsSecureCoding]
+ +[CSComponentDatePredicate initialize]
+ +[CSComponentDatePredicate lastMonthPredicate]
+ +[CSComponentDatePredicate lastWeekPredicate]
+ +[CSComponentDatePredicate lastYearPredicate]
+ +[CSComponentDatePredicate nextMonthPredicate]
+ +[CSComponentDatePredicate nextWeekPredicate]
+ +[CSComponentDatePredicate nextYearPredicate]
+ +[CSComponentDatePredicate nowPredicate]
+ +[CSComponentDatePredicate supportsSecureCoding]
+ +[CSComponentDatePredicate thisMonthPredicate]
+ +[CSComponentDatePredicate thisWeekPredicate]
+ +[CSComponentDatePredicate thisYearPredicate]
+ +[CSComponentDatePredicate todayPredicate]
+ +[CSComponentDatePredicate tomorrowPredicate]
+ +[CSComponentDatePredicate yesterdayPredicate]
+ +[CSContactsWrapper CNContactBirthdayKey]
+ +[CSContactsWrapper CNContactDepartmentNameKey]
+ +[CSContactsWrapper CNContactEmailAddressesKey]
+ +[CSContactsWrapper CNContactFamilyNameKey]
+ +[CSContactsWrapper CNContactGivenNameKey]
+ +[CSContactsWrapper CNContactInstantMessageAddressesKey]
+ +[CSContactsWrapper CNContactJobTitleKey]
+ +[CSContactsWrapper CNContactNoteKey]
+ +[CSContactsWrapper CNContactOrganizationNameKey]
+ +[CSContactsWrapper CNContactPhoneNumbersKey]
+ +[CSContactsWrapper CNContactSocialProfilesKey]
+ +[CSContactsWrapper CNContactUrlAddressesKey]
+ +[CSContactsWrapper CNLabeledValue]
+ +[CSDatePredicate dateFormatter]
+ +[CSDatePredicate supportsSecureCoding]
+ +[CSNumberPredicate supportsSecureCoding]
+ +[CSPersonPredicate personWithName:]
+ +[CSPersonPredicate personWithPerson:]
+ +[CSPersonPredicate queryNodeForPerson:attribute:]
+ +[CSPersonPredicate queryNodesForName:attributes:]
+ +[CSQueryNode supportsSecureCoding]
+ +[CSQueryPredicate supportsSecureCoding]
+ +[CSRangeDatePredicate supportsSecureCoding]
+ +[CSRecipientPredicate personWithName:]
+ +[CSRecipientPredicate personWithPerson:]
+ +[CSSenderPredicate personWithName:]
+ +[CSSenderPredicate personWithPerson:]
+ +[CSSimilarityPredicate supportsSecureCoding]
+ +[CSStringPredicate supportsSecureCoding]
+ +[CSStructuredQuery preheat:]
+ +[CSStructuredQuery prepareLocalResources]
+ +[CSStructuredQuery prepareWithProtectionClasses:]
+ +[CSStructuredQuery prepare]
+ +[CSWindowDatePredicate initialize]
+ +[CSWindowDatePredicate pastMonthPredicate]
+ +[CSWindowDatePredicate pastWeekPredicate]
+ +[CSWindowDatePredicate pastYearPredicate]
+ +[CSWindowDatePredicate supportsSecureCoding]
+ +[CSWindowDatePredicate upcomingMonthPredicate]
+ +[CSWindowDatePredicate upcomingWeekPredicate]
+ +[CSWindowDatePredicate upcomingYearPredicate]
+ -[CSAbsoluteDatePredicate .cxx_destruct]
+ -[CSAbsoluteDatePredicate compileToMDQueryStringWithConfiguration:]
+ -[CSAbsoluteDatePredicate copyWithZone:]
+ -[CSAbsoluteDatePredicate date]
+ -[CSAbsoluteDatePredicate encodeWithCoder:]
+ -[CSAbsoluteDatePredicate hash]
+ -[CSAbsoluteDatePredicate initWithAttribute:predicateOperator:date:]
+ -[CSAbsoluteDatePredicate initWithCoder:]
+ -[CSAbsoluteDatePredicate isEqual:]
+ -[CSBooleanPredicate copyWithZone:]
+ -[CSBooleanPredicate encodeWithCoder:]
+ -[CSBooleanPredicate flag]
+ -[CSBooleanPredicate hash]
+ -[CSBooleanPredicate initWithAttribute:flag:]
+ -[CSBooleanPredicate initWithCoder:]
+ -[CSBooleanPredicate isEqual:]
+ -[CSComponentDatePredicate .cxx_destruct]
+ -[CSComponentDatePredicate compileToMDQueryStringWithConfiguration:]
+ -[CSComponentDatePredicate copyWithZone:]
+ -[CSComponentDatePredicate encodeWithCoder:]
+ -[CSComponentDatePredicate hash]
+ -[CSComponentDatePredicate initWithAttribute:referenceDate:unit:offset:]
+ -[CSComponentDatePredicate initWithAttribute:unit:offset:]
+ -[CSComponentDatePredicate initWithCoder:]
+ -[CSComponentDatePredicate isEqual:]
+ -[CSComponentDatePredicate offset]
+ -[CSComponentDatePredicate referenceDate]
+ -[CSComponentDatePredicate unit]
+ -[CSCompoundPredicate .cxx_destruct]
+ -[CSCompoundPredicate _combineChildren:withLogic:]
+ -[CSCompoundPredicate children]
+ -[CSCompoundPredicate compileToMDQueryStringWithConfiguration:]
+ -[CSCompoundPredicate copyWithZone:]
+ -[CSCompoundPredicate encodeWithCoder:]
+ -[CSCompoundPredicate hash]
+ -[CSCompoundPredicate initWithCoder:]
+ -[CSCompoundPredicate initWithLogicalType:children:]
+ -[CSCompoundPredicate isEqual:]
+ -[CSCompoundPredicate logicalType]
+ -[CSContentTypePredicate .cxx_destruct]
+ -[CSContentTypePredicate contentTypes]
+ -[CSContentTypePredicate copyWithZone:]
+ -[CSContentTypePredicate encodeWithCoder:]
+ -[CSContentTypePredicate hash]
+ -[CSContentTypePredicate initWithCoder:]
+ -[CSContentTypePredicate initWithContentType:]
+ -[CSContentTypePredicate initWithContentTypes:]
+ -[CSContentTypePredicate isEqual:]
+ -[CSDatePredicate compileToMDQueryStringWithConfiguration:]
+ -[CSDatePredicate copyWithZone:]
+ -[CSDatePredicate isEqual:]
+ -[CSDonationProgress allKnownItemsIsPartial]
+ -[CSDonationProgress initWithAllKnownItems:itemsNeedingDonation:donatedItems:partiallyDonatedItems:itemsNeedingDonationForRedonationRequests:dateOfNewestUndonatedItem:allKnownItemsIsPartial:]
+ -[CSKeywordsPredicate .cxx_destruct]
+ -[CSKeywordsPredicate compileToMDQueryStringWithConfiguration:]
+ -[CSKeywordsPredicate escapeString:]
+ -[CSKeywordsPredicate initWithKeywords:]
+ -[CSKeywordsPredicate keywords]
+ -[CSNumberPredicate .cxx_destruct]
+ -[CSNumberPredicate compileToMDQueryStringWithConfiguration:]
+ -[CSNumberPredicate copyWithZone:]
+ -[CSNumberPredicate encodeWithCoder:]
+ -[CSNumberPredicate hash]
+ -[CSNumberPredicate initWithAttribute:minValue:maxValue:]
+ -[CSNumberPredicate initWithAttribute:predicateOperator:value:]
+ -[CSNumberPredicate initWithCoder:]
+ -[CSNumberPredicate isEqual:]
+ -[CSNumberPredicate maxValue]
+ -[CSNumberPredicate minValue]
+ -[CSNumberPredicate setMaxValue:]
+ -[CSNumberPredicate setMinValue:]
+ -[CSNumberPredicate setValue:]
+ -[CSNumberPredicate value]
+ -[CSPersonPredicate .cxx_destruct]
+ -[CSPersonPredicate attributes]
+ -[CSPersonPredicate initWithName:attributes:]
+ -[CSPersonPredicate initWithPerson:attributes:]
+ -[CSPersonPredicate name]
+ -[CSPersonPredicate person]
+ -[CSQueryNode compileToMDQueryStringWithConfiguration:]
+ -[CSQueryNode copyWithZone:]
+ -[CSQueryNode encodeWithCoder:]
+ -[CSQueryNode hash]
+ -[CSQueryNode initWithCoder:]
+ -[CSQueryNode isEqual:]
+ -[CSQueryNodeConfiguration .cxx_destruct]
+ -[CSQueryNodeConfiguration embedding]
+ -[CSQueryNodeConfiguration initWithQueryID:keyboardLanguage:]
+ -[CSQueryNodeConfiguration maxSimilarityResults]
+ -[CSQueryNodeConfiguration maxSimilarityThreshold]
+ -[CSQueryNodeConfiguration parseOptions]
+ -[CSQueryNodeConfiguration queryUnderstandingDict]
+ -[CSQueryNodeConfiguration setEmbedding:]
+ -[CSQueryNodeConfiguration setMaxSimilarityResults:]
+ -[CSQueryNodeConfiguration setMaxSimilarityThreshold:]
+ -[CSQueryNodeConfiguration setQueryUnderstandingDict:]
+ -[CSQueryPredicate .cxx_destruct]
+ -[CSQueryPredicate attribute]
+ -[CSQueryPredicate compileToMDQueryStringWithConfiguration:]
+ -[CSQueryPredicate copyWithZone:]
+ -[CSQueryPredicate encodeWithCoder:]
+ -[CSQueryPredicate hash]
+ -[CSQueryPredicate initWithAttribute:predicateOperator:]
+ -[CSQueryPredicate initWithCoder:]
+ -[CSQueryPredicate init]
+ -[CSQueryPredicate isEqual:]
+ -[CSQueryPredicate predicateOperator]
+ -[CSRangeDatePredicate .cxx_destruct]
+ -[CSRangeDatePredicate compileToMDQueryStringWithConfiguration:]
+ -[CSRangeDatePredicate copyWithZone:]
+ -[CSRangeDatePredicate encodeWithCoder:]
+ -[CSRangeDatePredicate hash]
+ -[CSRangeDatePredicate initWithAttribute:minDate:maxDate:]
+ -[CSRangeDatePredicate initWithCoder:]
+ -[CSRangeDatePredicate isEqual:]
+ -[CSRangeDatePredicate maxDate]
+ -[CSRangeDatePredicate minDate]
+ -[CSSearchableItemAttributeSet(CSPrivateAttributes) eventEndTimeIsUnknown]
+ -[CSSearchableItemAttributeSet(CSPrivateAttributes) eventStartTimeIsUnknown]
+ -[CSSearchableItemAttributeSet(CSPrivateAttributes) setEventEndTimeIsUnknown:]
+ -[CSSearchableItemAttributeSet(CSPrivateAttributes) setEventStartTimeIsUnknown:]
+ -[CSSimilarityPredicate .cxx_destruct]
+ -[CSSimilarityPredicate compileToMDQueryStringWithConfiguration:]
+ -[CSSimilarityPredicate copyWithZone:]
+ -[CSSimilarityPredicate encodeWithCoder:]
+ -[CSSimilarityPredicate hash]
+ -[CSSimilarityPredicate initWithCoder:]
+ -[CSSimilarityPredicate initWithText:]
+ -[CSSimilarityPredicate initWithText:matchOptions:]
+ -[CSSimilarityPredicate isEqual:]
+ -[CSSimilarityPredicate matchOptions]
+ -[CSSimilarityPredicate text]
+ -[CSStringPredicate .cxx_destruct]
+ -[CSStringPredicate _compileAsORSequence:values:]
+ -[CSStringPredicate _compileInOperator:values:]
+ -[CSStringPredicate _compileInOperatorForAttribute:values:]
+ -[CSStringPredicate compileToMDQueryStringWithConfiguration:]
+ -[CSStringPredicate copyWithZone:]
+ -[CSStringPredicate encodeWithCoder:]
+ -[CSStringPredicate hash]
+ -[CSStringPredicate initWithAttribute:value:matchOptions:]
+ -[CSStringPredicate initWithAttribute:values:matchOptions:]
+ -[CSStringPredicate initWithCoder:]
+ -[CSStringPredicate init]
+ -[CSStringPredicate isCaseInsensitive]
+ -[CSStringPredicate isDiacriticInsensitive]
+ -[CSStringPredicate isEqual:]
+ -[CSStringPredicate isExactMatch]
+ -[CSStringPredicate isPrefixMatch]
+ -[CSStringPredicate isSubstringMatch]
+ -[CSStringPredicate isTokenized]
+ -[CSStringPredicate isWordBased]
+ -[CSStringPredicate matchOptions]
+ -[CSStringPredicate values]
+ -[CSStructuredQuery .cxx_destruct]
+ -[CSStructuredQuery cancel]
+ -[CSStructuredQuery clientContext]
+ -[CSStructuredQuery commonInit]
+ -[CSStructuredQuery completeQuery:error:]
+ -[CSStructuredQuery executeSchemaQuery:]
+ -[CSStructuredQuery foundItemCount]
+ -[CSStructuredQuery initWithQueryContext:]
+ -[CSStructuredQuery initWithQueryString:context:]
+ -[CSStructuredQuery initWithQueryString:queryContext:]
+ -[CSStructuredQuery isCancelled]
+ -[CSStructuredQuery poll]
+ -[CSStructuredQuery queryContext]
+ -[CSStructuredQuery queryNode]
+ -[CSStructuredQuery start]
+ -[CSStructuredQuery userEngagedWithResult:interactionType:]
+ -[CSStructuredQueryContext .cxx_destruct]
+ -[CSStructuredQueryContext initWithQueryNode:]
+ -[CSStructuredQueryContext maxResultCount]
+ -[CSStructuredQueryContext queryNode]
+ -[CSStructuredQueryContext setMaxResultCount:]
+ -[CSStructuredQueryContext setSource:]
+ -[CSStructuredQueryContext source]
+ -[CSUserQueryParser _CSQueryInputDictionaryWithInput:queryReference:options:]
+ -[CSWindowDatePredicate .cxx_destruct]
+ -[CSWindowDatePredicate compileToMDQueryStringWithConfiguration:]
+ -[CSWindowDatePredicate copyWithZone:]
+ -[CSWindowDatePredicate direction]
+ -[CSWindowDatePredicate encodeWithCoder:]
+ -[CSWindowDatePredicate hash]
+ -[CSWindowDatePredicate initWithAttribute:referenceDate:unit:offset:direction:]
+ -[CSWindowDatePredicate initWithAttribute:unit:offset:direction:]
+ -[CSWindowDatePredicate initWithCoder:]
+ -[CSWindowDatePredicate isEqual:]
+ -[CSWindowDatePredicate offset]
+ -[CSWindowDatePredicate referenceDate]
+ -[CSWindowDatePredicate unit]
+ GCC_except_table1072
+ GCC_except_table14
+ GCC_except_table1648
+ GCC_except_table1654
+ _MDItemEventEndTimeIsUnknown
+ _MDItemEventStartTimeIsUnknown
+ _MDUHash32
+ _OBJC_CLASS_$_CSAbsoluteDatePredicate
+ _OBJC_CLASS_$_CSAuthorPredicate
+ _OBJC_CLASS_$_CSBooleanPredicate
+ _OBJC_CLASS_$_CSComponentDatePredicate
+ _OBJC_CLASS_$_CSCompoundPredicate
+ _OBJC_CLASS_$_CSContentTypePredicate
+ _OBJC_CLASS_$_CSDatePredicate
+ _OBJC_CLASS_$_CSKeywordsPredicate
+ _OBJC_CLASS_$_CSNumberPredicate
+ _OBJC_CLASS_$_CSPersonPredicate
+ _OBJC_CLASS_$_CSQueryNode
+ _OBJC_CLASS_$_CSQueryNodeConfiguration
+ _OBJC_CLASS_$_CSQueryPredicate
+ _OBJC_CLASS_$_CSRangeDatePredicate
+ _OBJC_CLASS_$_CSRecipientPredicate
+ _OBJC_CLASS_$_CSSenderPredicate
+ _OBJC_CLASS_$_CSSimilarityPredicate
+ _OBJC_CLASS_$_CSStringPredicate
+ _OBJC_CLASS_$_CSStructuredQuery
+ _OBJC_CLASS_$_CSStructuredQueryContext
+ _OBJC_CLASS_$_CSWindowDatePredicate
+ _OBJC_IVAR_$_CSAbsoluteDatePredicate._date
+ _OBJC_IVAR_$_CSBooleanPredicate._flag
+ _OBJC_IVAR_$_CSComponentDatePredicate._offset
+ _OBJC_IVAR_$_CSComponentDatePredicate._referenceDate
+ _OBJC_IVAR_$_CSComponentDatePredicate._unit
+ _OBJC_IVAR_$_CSCompoundPredicate._children
+ _OBJC_IVAR_$_CSCompoundPredicate._logic
+ _OBJC_IVAR_$_CSContentTypePredicate._contentTypes
+ _OBJC_IVAR_$_CSDonationProgress._allKnownItemsIsPartial
+ _OBJC_IVAR_$_CSKeywordsPredicate._keywords
+ _OBJC_IVAR_$_CSNumberPredicate._maxValue
+ _OBJC_IVAR_$_CSNumberPredicate._minValue
+ _OBJC_IVAR_$_CSNumberPredicate._value
+ _OBJC_IVAR_$_CSPersonPredicate._attributes
+ _OBJC_IVAR_$_CSPersonPredicate._name
+ _OBJC_IVAR_$_CSPersonPredicate._person
+ _OBJC_IVAR_$_CSQueryNodeConfiguration._additionalFetchAttributes
+ _OBJC_IVAR_$_CSQueryNodeConfiguration._embedding
+ _OBJC_IVAR_$_CSQueryNodeConfiguration._enableSemanticSearch
+ _OBJC_IVAR_$_CSQueryNodeConfiguration._maxSimilarityResults
+ _OBJC_IVAR_$_CSQueryNodeConfiguration._maxSimilarityThreshold
+ _OBJC_IVAR_$_CSQueryNodeConfiguration._parseOptions
+ _OBJC_IVAR_$_CSQueryNodeConfiguration._queryUnderstandingDict
+ _OBJC_IVAR_$_CSQueryPredicate._attribute
+ _OBJC_IVAR_$_CSQueryPredicate._operator
+ _OBJC_IVAR_$_CSRangeDatePredicate._maxDate
+ _OBJC_IVAR_$_CSRangeDatePredicate._minDate
+ _OBJC_IVAR_$_CSSimilarityPredicate._matchOptions
+ _OBJC_IVAR_$_CSSimilarityPredicate._text
+ _OBJC_IVAR_$_CSStringPredicate._matchOptions
+ _OBJC_IVAR_$_CSStringPredicate._values
+ _OBJC_IVAR_$_CSStructuredQuery._activeQueries
+ _OBJC_IVAR_$_CSStructuredQuery._canceled
+ _OBJC_IVAR_$_CSStructuredQuery._clientQueryContext
+ _OBJC_IVAR_$_CSStructuredQuery._completedQueries
+ _OBJC_IVAR_$_CSStructuredQuery._error
+ _OBJC_IVAR_$_CSStructuredQuery._lock
+ _OBJC_IVAR_$_CSStructuredQuery._seenIdentifiers
+ _OBJC_IVAR_$_CSStructuredQuery._started
+ _OBJC_IVAR_$_CSStructuredQueryContext._maxResultCount
+ _OBJC_IVAR_$_CSStructuredQueryContext._queryNode
+ _OBJC_IVAR_$_CSStructuredQueryContext._source
+ _OBJC_IVAR_$_CSWindowDatePredicate._direction
+ _OBJC_IVAR_$_CSWindowDatePredicate._offset
+ _OBJC_IVAR_$_CSWindowDatePredicate._referenceDate
+ _OBJC_IVAR_$_CSWindowDatePredicate._unit
+ _OBJC_METACLASS_$_CSAbsoluteDatePredicate
+ _OBJC_METACLASS_$_CSAuthorPredicate
+ _OBJC_METACLASS_$_CSBooleanPredicate
+ _OBJC_METACLASS_$_CSComponentDatePredicate
+ _OBJC_METACLASS_$_CSCompoundPredicate
+ _OBJC_METACLASS_$_CSContentTypePredicate
+ _OBJC_METACLASS_$_CSDatePredicate
+ _OBJC_METACLASS_$_CSKeywordsPredicate
+ _OBJC_METACLASS_$_CSNumberPredicate
+ _OBJC_METACLASS_$_CSPersonPredicate
+ _OBJC_METACLASS_$_CSQueryNode
+ _OBJC_METACLASS_$_CSQueryNodeConfiguration
+ _OBJC_METACLASS_$_CSQueryPredicate
+ _OBJC_METACLASS_$_CSRangeDatePredicate
+ _OBJC_METACLASS_$_CSRecipientPredicate
+ _OBJC_METACLASS_$_CSSenderPredicate
+ _OBJC_METACLASS_$_CSSimilarityPredicate
+ _OBJC_METACLASS_$_CSStringPredicate
+ _OBJC_METACLASS_$_CSStructuredQuery
+ _OBJC_METACLASS_$_CSStructuredQueryContext
+ _OBJC_METACLASS_$_CSWindowDatePredicate
+ _UTTypeContact
+ __OBJC_$_CLASS_METHODS_CSAbsoluteDatePredicate
+ __OBJC_$_CLASS_METHODS_CSAuthorPredicate
+ __OBJC_$_CLASS_METHODS_CSBooleanPredicate
+ __OBJC_$_CLASS_METHODS_CSComponentDatePredicate
+ __OBJC_$_CLASS_METHODS_CSDatePredicate
+ __OBJC_$_CLASS_METHODS_CSNumberPredicate
+ __OBJC_$_CLASS_METHODS_CSPersonPredicate
+ __OBJC_$_CLASS_METHODS_CSQueryNode
+ __OBJC_$_CLASS_METHODS_CSQueryPredicate
+ __OBJC_$_CLASS_METHODS_CSRangeDatePredicate
+ __OBJC_$_CLASS_METHODS_CSRecipientPredicate
+ __OBJC_$_CLASS_METHODS_CSSenderPredicate
+ __OBJC_$_CLASS_METHODS_CSSimilarityPredicate
+ __OBJC_$_CLASS_METHODS_CSStringPredicate
+ __OBJC_$_CLASS_METHODS_CSStructuredQuery
+ __OBJC_$_CLASS_METHODS_CSWindowDatePredicate
+ __OBJC_$_CLASS_PROP_LIST_CSComponentDatePredicate
+ __OBJC_$_CLASS_PROP_LIST_CSQueryNode
+ __OBJC_$_CLASS_PROP_LIST_CSWindowDatePredicate
+ __OBJC_$_INSTANCE_METHODS_CSAbsoluteDatePredicate
+ __OBJC_$_INSTANCE_METHODS_CSBooleanPredicate
+ __OBJC_$_INSTANCE_METHODS_CSComponentDatePredicate
+ __OBJC_$_INSTANCE_METHODS_CSCompoundPredicate
+ __OBJC_$_INSTANCE_METHODS_CSContentTypePredicate
+ __OBJC_$_INSTANCE_METHODS_CSDatePredicate
+ __OBJC_$_INSTANCE_METHODS_CSKeywordsPredicate
+ __OBJC_$_INSTANCE_METHODS_CSNumberPredicate
+ __OBJC_$_INSTANCE_METHODS_CSPersonPredicate
+ __OBJC_$_INSTANCE_METHODS_CSQueryNode
+ __OBJC_$_INSTANCE_METHODS_CSQueryNodeConfiguration
+ __OBJC_$_INSTANCE_METHODS_CSQueryPredicate
+ __OBJC_$_INSTANCE_METHODS_CSRangeDatePredicate
+ __OBJC_$_INSTANCE_METHODS_CSSimilarityPredicate
+ __OBJC_$_INSTANCE_METHODS_CSStringPredicate
+ __OBJC_$_INSTANCE_METHODS_CSStructuredQuery
+ __OBJC_$_INSTANCE_METHODS_CSStructuredQueryContext
+ __OBJC_$_INSTANCE_METHODS_CSWindowDatePredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSAbsoluteDatePredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSBooleanPredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSComponentDatePredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSCompoundPredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSContentTypePredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSKeywordsPredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSNumberPredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSPersonPredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSQueryNodeConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_CSQueryPredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSRangeDatePredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSSimilarityPredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSStringPredicate
+ __OBJC_$_INSTANCE_VARIABLES_CSStructuredQuery
+ __OBJC_$_INSTANCE_VARIABLES_CSStructuredQueryContext
+ __OBJC_$_INSTANCE_VARIABLES_CSWindowDatePredicate
+ __OBJC_$_PROP_LIST_CSAbsoluteDatePredicate
+ __OBJC_$_PROP_LIST_CSBooleanPredicate
+ __OBJC_$_PROP_LIST_CSComponentDatePredicate
+ __OBJC_$_PROP_LIST_CSCompoundPredicate
+ __OBJC_$_PROP_LIST_CSContentTypePredicate
+ __OBJC_$_PROP_LIST_CSKeywordsPredicate
+ __OBJC_$_PROP_LIST_CSNumberPredicate
+ __OBJC_$_PROP_LIST_CSPersonPredicate
+ __OBJC_$_PROP_LIST_CSQueryNodeConfiguration
+ __OBJC_$_PROP_LIST_CSQueryPredicate
+ __OBJC_$_PROP_LIST_CSRangeDatePredicate
+ __OBJC_$_PROP_LIST_CSSimilarityPredicate
+ __OBJC_$_PROP_LIST_CSStringPredicate
+ __OBJC_$_PROP_LIST_CSStructuredQueryContext
+ __OBJC_$_PROP_LIST_CSWindowDatePredicate
+ __OBJC_CLASS_PROTOCOLS_$_CSQueryNode
+ __OBJC_CLASS_RO_$_CSAbsoluteDatePredicate
+ __OBJC_CLASS_RO_$_CSAuthorPredicate
+ __OBJC_CLASS_RO_$_CSBooleanPredicate
+ __OBJC_CLASS_RO_$_CSComponentDatePredicate
+ __OBJC_CLASS_RO_$_CSCompoundPredicate
+ __OBJC_CLASS_RO_$_CSContentTypePredicate
+ __OBJC_CLASS_RO_$_CSDatePredicate
+ __OBJC_CLASS_RO_$_CSKeywordsPredicate
+ __OBJC_CLASS_RO_$_CSNumberPredicate
+ __OBJC_CLASS_RO_$_CSPersonPredicate
+ __OBJC_CLASS_RO_$_CSQueryNode
+ __OBJC_CLASS_RO_$_CSQueryNodeConfiguration
+ __OBJC_CLASS_RO_$_CSQueryPredicate
+ __OBJC_CLASS_RO_$_CSRangeDatePredicate
+ __OBJC_CLASS_RO_$_CSRecipientPredicate
+ __OBJC_CLASS_RO_$_CSSenderPredicate
+ __OBJC_CLASS_RO_$_CSSimilarityPredicate
+ __OBJC_CLASS_RO_$_CSStringPredicate
+ __OBJC_CLASS_RO_$_CSStructuredQuery
+ __OBJC_CLASS_RO_$_CSStructuredQueryContext
+ __OBJC_CLASS_RO_$_CSWindowDatePredicate
+ __OBJC_METACLASS_RO_$_CSAbsoluteDatePredicate
+ __OBJC_METACLASS_RO_$_CSAuthorPredicate
+ __OBJC_METACLASS_RO_$_CSBooleanPredicate
+ __OBJC_METACLASS_RO_$_CSComponentDatePredicate
+ __OBJC_METACLASS_RO_$_CSCompoundPredicate
+ __OBJC_METACLASS_RO_$_CSContentTypePredicate
+ __OBJC_METACLASS_RO_$_CSDatePredicate
+ __OBJC_METACLASS_RO_$_CSKeywordsPredicate
+ __OBJC_METACLASS_RO_$_CSNumberPredicate
+ __OBJC_METACLASS_RO_$_CSPersonPredicate
+ __OBJC_METACLASS_RO_$_CSQueryNode
+ __OBJC_METACLASS_RO_$_CSQueryNodeConfiguration
+ __OBJC_METACLASS_RO_$_CSQueryPredicate
+ __OBJC_METACLASS_RO_$_CSRangeDatePredicate
+ __OBJC_METACLASS_RO_$_CSRecipientPredicate
+ __OBJC_METACLASS_RO_$_CSSenderPredicate
+ __OBJC_METACLASS_RO_$_CSSimilarityPredicate
+ __OBJC_METACLASS_RO_$_CSStringPredicate
+ __OBJC_METACLASS_RO_$_CSStructuredQuery
+ __OBJC_METACLASS_RO_$_CSStructuredQueryContext
+ __OBJC_METACLASS_RO_$_CSWindowDatePredicate
+ ___26-[CSStructuredQuery start]_block_invoke
+ ___26-[CSStructuredQuery start]_block_invoke_10
+ ___26-[CSStructuredQuery start]_block_invoke_11
+ ___26-[CSStructuredQuery start]_block_invoke_12
+ ___26-[CSStructuredQuery start]_block_invoke_13
+ ___26-[CSStructuredQuery start]_block_invoke_14
+ ___26-[CSStructuredQuery start]_block_invoke_15
+ ___26-[CSStructuredQuery start]_block_invoke_16
+ ___26-[CSStructuredQuery start]_block_invoke_17
+ ___26-[CSStructuredQuery start]_block_invoke_2
+ ___26-[CSStructuredQuery start]_block_invoke_3
+ ___26-[CSStructuredQuery start]_block_invoke_4
+ ___26-[CSStructuredQuery start]_block_invoke_5
+ ___26-[CSStructuredQuery start]_block_invoke_6
+ ___26-[CSStructuredQuery start]_block_invoke_7
+ ___26-[CSStructuredQuery start]_block_invoke_8
+ ___26-[CSStructuredQuery start]_block_invoke_9
+ ___29+[CSStructuredQuery preheat:]_block_invoke
+ ___32+[CSDatePredicate dateFormatter]_block_invoke
+ ___35+[CSWindowDatePredicate initialize]_block_invoke
+ ___37-[CSCompoundPredicate initWithCoder:]_block_invoke
+ ___38+[CSComponentDatePredicate initialize]_block_invoke
+ ___42+[CSStructuredQuery prepareLocalResources]_block_invoke
+ ___50+[CSStructuredQuery prepareWithProtectionClasses:]_block_invoke
+ ___61-[CSQueryNodeConfiguration initWithQueryID:keyboardLanguage:]_block_invoke
+ ___MDQueryCopyInputDictionaryWithOptionsDict
+ ___block_descriptor_32_e17_v16?0"NSArray"8l
+ ___block_descriptor_32_e19_v40?0q8Q16^24^B32l
+ ___block_descriptor_32_e22_v16?0"NSDictionary"8l
+ ___block_descriptor_32_e30_v24?0"NSString"8"NSArray"16l
+ ___block_descriptor_32_e42_v32?0"NSString"8"NSArray"16"NSArray"24l
+ ___block_descriptor_32_e8_v16?0q8l
+ ___block_descriptor_48_e8_32w40w_e17_v16?0"NSError"8lw32l8w40l8
+ ___block_descriptor_53_e8_32s40w_e33_v16?0"NSObject<OS_xpc_object>"8ls32l8w40l8
+ ___block_descriptor_61_e8_32s40s48w_e5_v8?0ls32l8s40l8w48l8
+ ___getCNContactBirthdayKeySymbolLoc_block_invoke
+ ___getCNContactDepartmentNameKeySymbolLoc_block_invoke
+ ___getCNContactInstantMessageAddressesKeySymbolLoc_block_invoke
+ ___getCNContactJobTitleKeySymbolLoc_block_invoke
+ ___getCNContactNoteKeySymbolLoc_block_invoke
+ ___getCNContactOrganizationNameKeySymbolLoc_block_invoke
+ ___getCNContactSocialProfilesKeySymbolLoc_block_invoke
+ ___getCNContactUrlAddressesKeySymbolLoc_block_invoke
+ ___getCNLabeledValueClass_block_invoke
+ _dateFormatter.onceToken
+ _dateFormatter.sDateFormatter
+ _getCNContactBirthdayKeySymbolLoc.ptr
+ _getCNContactDepartmentNameKeySymbolLoc.ptr
+ _getCNContactEmailAddressesKey
+ _getCNContactInstantMessageAddressesKeySymbolLoc.ptr
+ _getCNContactJobTitleKeySymbolLoc.ptr
+ _getCNContactNoteKeySymbolLoc.ptr
+ _getCNContactOrganizationNameKeySymbolLoc.ptr
+ _getCNContactSocialProfilesKeySymbolLoc.ptr
+ _getCNContactUrlAddressesKeySymbolLoc.ptr
+ _getCNLabeledValueClass.softClass
+ _initWithCoder:.onceToken
+ _initWithCoder:.sChildClasses
+ _initWithQueryID:keyboardLanguage:.gSemanticSearchEnabled
+ _initWithQueryID:keyboardLanguage:.onceToken
+ _initialize.onceWindowToken
+ _prepareWithProtectionClasses:.onceToken
+ _queryForPredicateOperator
+ _sLastMonthPredicate
+ _sLastWeekPredicate
+ _sLastYearPredicate
+ _sNextMonthPredicate
+ _sNextWeekPredicate
+ _sNextYearPredicate
+ _sNowPredicate
+ _sPastMonthPredicate
+ _sPastWeekPredicate
+ _sPastYearPredicate
+ _sThisMonthPredicate
+ _sThisWeekPredicate
+ _sThisYearPredicate
+ _sTodayPredicate
+ _sTomorrowPredicate
+ _sUpcomingMonthPredicate
+ _sUpcomingWeekPredicate
+ _sUpcomingYearPredicate
+ _sYesterdayPredicate
- GCC_except_table1068
- GCC_except_table1644
- GCC_except_table1650
- ___53-[CSSearchableIndex _issueCommand:completionHandler:]_block_invoke_2
- ___53-[CSSearchableIndex _issueCommand:completionHandler:]_block_invoke_3
CStrings:
+ "\"%@%@%@\""
+ "%@%@$time.iso(%@)"
+ "%@%@%@"
+ "%@%@*"
+ "%@Addresses"
+ "%@EmailAddresses"
+ "%@Names"
+ "%@PhoneNumbers"
+ "**=*"
+ "<%@: All Known: %lu; Needing Donation: %lu; Donated: %@; Partially Donated: %@; Pending Redonation: %@; Newest Undonated Date: %@; Partial: %@>"
+ "CNContactBirthdayKey"
+ "CNContactDepartmentNameKey"
+ "CNContactInstantMessageAddressesKey"
+ "CNContactJobTitleKey"
+ "CNContactNoteKey"
+ "CNContactOrganizationNameKey"
+ "CNContactSocialProfilesKey"
+ "CNContactUrlAddressesKey"
+ "CNLabeledValue"
+ "CSStructuredQueryErrorDomain"
+ "Corrupt operation matches none"
+ "DEBUG CSStructuredQuery: compiled queryString = '%s'\n"
+ "Empty operation matches all"
+ "InRange(%@,$time.iso(%@),$time.iso(%@))"
+ "_issueCommand id=%u cmd=%@ critical=%d (qos=%d optionsCritical=%d options=0x%lx)"
+ "_issueCommand id=%u cmd=%@ critical=%d qos=%d sending xpc msg"
+ "_issueCommand id=%u cmd=%@ reply ERROR: %@"
+ "_issueCommand id=%u cmd=%@ reply OK"
+ "allKnownItemsIsPartial"
+ "com.apple.FaceTime"
+ "direction"
+ "eventEndTimeIsUnknown"
+ "eventStartTimeIsUnknown"
+ "flag"
+ "kMDItemEventEndTimeIsUnknown"
+ "kMDItemEventStartTimeIsUnknown"
+ "logicalType"
+ "matchOptions"
+ "maxDate"
+ "minDate"
+ "minValue"
+ "predicateOperator"
+ "referenceDate"
+ "v16@?0q8"
+ "v24@?0@\"NSString\"8@\"NSArray\"16"
+ "v32@?0@\"NSString\"8@\"NSArray\"16@\"NSArray\"24"
+ "v40@?0q8Q16^@24^B32"
+ "validateIndexers"
+ "validateVectors"
+ "||"
- " source=%u"
- "<%@: All Known: %lu; Needing Donation: %lu; Donated: %@; Partially Donated: %@; Pending Redonation: %@; Newest Undonated Date: %@>"
- "so"
```
