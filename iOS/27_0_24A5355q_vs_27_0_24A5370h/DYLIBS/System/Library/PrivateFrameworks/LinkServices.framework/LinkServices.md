## LinkServices

> `/System/Library/PrivateFrameworks/LinkServices.framework/LinkServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x145208` | `0x14cc04` | **`+0x79fc`** |
| `__TEXT.__cstring` | `0xaea9` | `0xbaf7` | **`+0xc4e`** |
| `__TEXT.__oslogstring` | `0x6908` | `0x71a2` | **`+0x89a`** |
| `__AUTH_CONST.__objc_const` | `0x14d88` | `0x15258` | **`+0x4d0`** |
| `__TEXT.__objc_methlist` | `0xa438` | `0xa820` | **`+0x3e8`** |
| `__AUTH_CONST.__cfstring` | `0x8120` | `0x83e0` | **`+0x2c0`** |
| `__AUTH_CONST.__const` | `0x6a10` | `0x6be8` | **`+0x1d8`** |
| `__AUTH.__objc_data` | `0x3210` | `0x33d0` | **`+0x1c0`** |
| `__TEXT.__unwind_info` | `0x6330` | `0x64b0` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x24d0` | `0x2620` | **`+0x150`** |
| `__DATA_CONST.__objc_selrefs` | `0x4c78` | `0x4d90` | **`+0x118`** |
| `__TEXT.__constg_swiftt` | `0x1998` | `0x1a4c` | **`+0xb4`** |
| `__TEXT.__const` | `0x7de8` | `0x7e88` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x11b8` | `0x1248` | **`+0x90`** |
| `__DATA.__bss` | `0x4bb8` | `0x4c38` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x1d94` | `0x1e08` | **`+0x74`** |
| `__TEXT.__lazy_helpers` | `—` | `0x54` | **`+0x54`** |
| `__TEXT.__swift5_reflstr` | `0xde1` | `0xe31` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x68c8` | `0x6910` | **`+0x48`** |
| `__TEXT.__dlopen_cstrs` | `0x548` | `0x507` | **`-0x41`** |
| `__TEXT.__swift5_fieldmd` | `0x1238` | `0x126c` | **`+0x34`** |
| `__AUTH.__data` | `0xc88` | `0xcb8` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0xa84` | `0xaac` | **`+0x28`** |
| `__DATA.__data` | `0x2fc0` | `0x2fe4` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x1810` | `0x1830` | **`+0x20`** |
| `__DATA.__common` | `0x628` | `0x640` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x780` | `0x798` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x1cc` | `0x1e0` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x1640` | `0x1650` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x5d0` | `0x5e0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x338` | `0x328` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x2d1e` | `0x2d2a` | **`+0xc`** |
| `__AUTH_CONST.__lazy_load_got` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x190` | `0x198` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x330` | `0x334` | **`+0x4`** |

### Other Changes

```diff

-301.0.41.16.106
+301.0.42.7.0

-  Functions: 9610
-  Symbols:   8754
-  CStrings:  1930
+  Functions: 9744
+  Symbols:   8910
+  CStrings:  2018
Symbols:
+ +[LNConnection connectionDescription]
+ +[LNConnectionPolicy _policyWithBundleIdentifier:]
+ +[LNDaemonConnection connectionDescription]
+ +[LNEmbeddedApplicationConnection connectionDescription]
+ +[LNExtensionConnection connectionDescription]
+ +[LNFeatureFlags isContinueInAppWithoutConfirmationDelegateEnabled]
+ +[LNFeatureFlags isDaemonOwnedMacAppConnectionEnabled]
+ +[LNFeatureFlags resetContinueInAppWithoutConfirmationDelegateOverride]
+ +[LNFeatureFlags setIsContinueInAppWithoutConfirmationDelegateEnabled:]
+ +[LNFrameworkConnection connectionDescription]
+ +[LNInProcessConnection connectionDescription]
+ +[LNQueryEntityOptions supportsSecureCoding]
+ +[LNQueryPropertyResolution additionalDeferredProperties:]
+ +[LNQueryPropertyResolution includedProperties:]
+ +[LNQueryPropertyResolution supportsSecureCoding]
+ +[LNXPCListenerEndpointConnection connectionDescription]
+ -[LNAutoShortcutsProvider appShortcutBundles:]
+ -[LNAutoShortcutsProvider autoShortcutsForBundleIdentifier:localeIdentifier:error:]
+ -[LNContinueInAppRequest continueWithoutConfirmationReason]
+ -[LNContinueInAppRequest initWithIdentifier:dialog:throwing:requestConfirmation:type:sceneOptions:bundleIdentifier:options:continueWithoutConfirmationReason:]
+ -[LNContinueInAppRequest requestWithConfirmation]
+ -[LNContinueInAppRequest requestWithoutConfirmationWithReason:]
+ -[LNQueryEntityOptions .cxx_destruct]
+ -[LNQueryEntityOptions componentKindConfiguration]
+ -[LNQueryEntityOptions copyWithZone:]
+ -[LNQueryEntityOptions deferredPropertyResolutionConcurrencyLimit]
+ -[LNQueryEntityOptions deferredPropertyResolutionTimeout]
+ -[LNQueryEntityOptions description]
+ -[LNQueryEntityOptions encodeWithCoder:]
+ -[LNQueryEntityOptions hash]
+ -[LNQueryEntityOptions initWithCoder:]
+ -[LNQueryEntityOptions init]
+ -[LNQueryEntityOptions isEqual:]
+ -[LNQueryEntityOptions levelOfDetailConfiguration]
+ -[LNQueryEntityOptions maximumArrayPropertyItemCount]
+ -[LNQueryEntityOptions maximumEntityDepth]
+ -[LNQueryEntityOptions propertyResolution]
+ -[LNQueryEntityOptions requiresStableEntityIdentifiers]
+ -[LNQueryEntityOptions setComponentKindConfiguration:]
+ -[LNQueryEntityOptions setDeferredPropertyResolutionConcurrencyLimit:]
+ -[LNQueryEntityOptions setDeferredPropertyResolutionTimeout:]
+ -[LNQueryEntityOptions setLevelOfDetailConfiguration:]
+ -[LNQueryEntityOptions setMaximumArrayPropertyItemCount:]
+ -[LNQueryEntityOptions setMaximumEntityDepth:]
+ -[LNQueryEntityOptions setPropertyResolution:]
+ -[LNQueryEntityOptions setRequiresStableEntityIdentifiers:]
+ -[LNQueryPropertyResolution .cxx_destruct]
+ -[LNQueryPropertyResolution _initWithMode:identifiers:]
+ -[LNQueryPropertyResolution copyWithZone:]
+ -[LNQueryPropertyResolution description]
+ -[LNQueryPropertyResolution encodeWithCoder:]
+ -[LNQueryPropertyResolution hash]
+ -[LNQueryPropertyResolution identifiers]
+ -[LNQueryPropertyResolution initWithCoder:]
+ -[LNQueryPropertyResolution isEqual:]
+ -[LNQueryPropertyResolution isIncluded]
+ -[LNQueryPropertyResolution mode]
+ -[LNQueryPropertyResolution setMode:]
+ -[LNQueryRequestOptions entityOptions]
+ -[LNQueryRequestOptions setEntityOptions:]
+ -[LNQueryRequestOptions(Deprecated) componentKindConfiguration]
+ -[LNQueryRequestOptions(Deprecated) levelOfDetailConfiguration]
+ -[LNQueryRequestOptions(Deprecated) requiresStableEntityIdentifiers]
+ -[LNQueryRequestOptions(Deprecated) resolvePropertyIdentifiers]
+ -[LNQueryRequestOptions(Deprecated) setComponentKindConfiguration:]
+ -[LNQueryRequestOptions(Deprecated) setLevelOfDetailConfiguration:]
+ -[LNQueryRequestOptions(Deprecated) setRequiresStableEntityIdentifiers:]
+ -[LNQueryRequestOptions(Deprecated) setResolvePropertyIdentifiers:]
+ -[_LNAutoShortcutsProviderXPC appShortcutBundles:]
+ -[_LNAutoShortcutsProviderXPC autoShortcutsForBundleIdentifier:localeIdentifier:error:]
+ GCC_except_table1002
+ GCC_except_table1060
+ GCC_except_table1064
+ GCC_except_table1074
+ GCC_except_table1075
+ GCC_except_table1085
+ GCC_except_table1110
+ GCC_except_table1126
+ GCC_except_table1128
+ GCC_except_table1129
+ GCC_except_table1130
+ GCC_except_table1181
+ GCC_except_table1192
+ GCC_except_table1196
+ GCC_except_table1203
+ GCC_except_table1208
+ GCC_except_table1220
+ GCC_except_table1221
+ GCC_except_table1222
+ GCC_except_table1236
+ GCC_except_table1256
+ GCC_except_table1268
+ GCC_except_table1289
+ GCC_except_table1293
+ GCC_except_table1559
+ GCC_except_table1570
+ GCC_except_table1591
+ GCC_except_table1601
+ GCC_except_table1604
+ GCC_except_table1606
+ GCC_except_table1619
+ GCC_except_table1620
+ GCC_except_table170
+ GCC_except_table173
+ GCC_except_table1744
+ GCC_except_table176
+ GCC_except_table1765
+ GCC_except_table1776
+ GCC_except_table1785
+ GCC_except_table1803
+ GCC_except_table1825
+ GCC_except_table183
+ GCC_except_table1837
+ GCC_except_table1853
+ GCC_except_table1911
+ GCC_except_table1916
+ GCC_except_table1943
+ GCC_except_table1949
+ GCC_except_table1951
+ GCC_except_table1953
+ GCC_except_table1965
+ GCC_except_table1977
+ GCC_except_table1989
+ GCC_except_table2029
+ GCC_except_table2041
+ GCC_except_table2052
+ GCC_except_table2064
+ GCC_except_table2076
+ GCC_except_table2088
+ GCC_except_table2098
+ GCC_except_table2112
+ GCC_except_table2134
+ GCC_except_table2173
+ GCC_except_table2184
+ GCC_except_table2195
+ GCC_except_table2209
+ GCC_except_table2210
+ GCC_except_table2221
+ GCC_except_table2222
+ GCC_except_table223
+ GCC_except_table2233
+ GCC_except_table227
+ GCC_except_table236
+ GCC_except_table2508
+ GCC_except_table251
+ GCC_except_table260
+ GCC_except_table280
+ GCC_except_table284
+ GCC_except_table286
+ GCC_except_table2959
+ GCC_except_table2962
+ GCC_except_table3012
+ GCC_except_table3108
+ GCC_except_table3120
+ GCC_except_table3170
+ GCC_except_table3175
+ GCC_except_table3179
+ GCC_except_table3192
+ GCC_except_table3210
+ GCC_except_table3215
+ GCC_except_table3224
+ GCC_except_table3228
+ GCC_except_table3337
+ GCC_except_table3339
+ GCC_except_table354
+ GCC_except_table355
+ GCC_except_table356
+ GCC_except_table357
+ GCC_except_table358
+ GCC_except_table359
+ GCC_except_table360
+ GCC_except_table361
+ GCC_except_table362
+ GCC_except_table363
+ GCC_except_table364
+ GCC_except_table365
+ GCC_except_table415
+ GCC_except_table584
+ GCC_except_table612
+ GCC_except_table623
+ GCC_except_table627
+ GCC_except_table631
+ GCC_except_table634
+ GCC_except_table638
+ GCC_except_table646
+ GCC_except_table652
+ GCC_except_table656
+ GCC_except_table660
+ GCC_except_table668
+ GCC_except_table672
+ GCC_except_table680
+ GCC_except_table684
+ GCC_except_table692
+ GCC_except_table696
+ GCC_except_table704
+ GCC_except_table708
+ GCC_except_table712
+ GCC_except_table728
+ GCC_except_table732
+ GCC_except_table736
+ GCC_except_table740
+ GCC_except_table744
+ GCC_except_table748
+ GCC_except_table752
+ GCC_except_table761
+ GCC_except_table763
+ GCC_except_table771
+ GCC_except_table776
+ GCC_except_table778
+ GCC_except_table780
+ GCC_except_table782
+ GCC_except_table784
+ GCC_except_table786
+ GCC_except_table790
+ GCC_except_table805
+ GCC_except_table812
+ GCC_except_table814
+ GCC_except_table816
+ GCC_except_table820
+ GCC_except_table822
+ GCC_except_table824
+ GCC_except_table826
+ GCC_except_table828
+ GCC_except_table830
+ GCC_except_table832
+ GCC_except_table834
+ GCC_except_table836
+ GCC_except_table838
+ GCC_except_table840
+ GCC_except_table842
+ GCC_except_table844
+ GCC_except_table846
+ GCC_except_table848
+ GCC_except_table976
+ GCC_except_table982
+ GCC_except_table984
+ _LNContinueInAppWithoutConfirmationReasonAsString
+ _LNLogCategoryGeneral
+ _LNMetadataReadRunWithRetry
+ _LNMetadataReadShouldRetryAfterError
+ _OBJC_CLASS_$_CSLocalizedString
+ _OBJC_CLASS_$_LNQueryEntityOptions
+ _OBJC_CLASS_$_LNQueryPropertyResolution
+ _OBJC_CLASS_$_UILinkConnectionAction
+ _OBJC_CLASS_$_UILinkConnectionAction$lazyGOT
+ _OBJC_CLASS_$_UILinkConnectionAction$lazyGOT$loadHelper_x8
+ _OBJC_IVAR_$_LNConnection._activeSignpost
+ _OBJC_IVAR_$_LNContinueInAppRequest._continueWithoutConfirmationReason
+ _OBJC_IVAR_$_LNQueryEntityOptions._componentKindConfiguration
+ _OBJC_IVAR_$_LNQueryEntityOptions._deferredPropertyResolutionConcurrencyLimit
+ _OBJC_IVAR_$_LNQueryEntityOptions._deferredPropertyResolutionTimeout
+ _OBJC_IVAR_$_LNQueryEntityOptions._levelOfDetailConfiguration
+ _OBJC_IVAR_$_LNQueryEntityOptions._maximumArrayPropertyItemCount
+ _OBJC_IVAR_$_LNQueryEntityOptions._maximumEntityDepth
+ _OBJC_IVAR_$_LNQueryEntityOptions._propertyResolution
+ _OBJC_IVAR_$_LNQueryEntityOptions._requiresStableEntityIdentifiers
+ _OBJC_IVAR_$_LNQueryPropertyResolution._identifiers
+ _OBJC_IVAR_$_LNQueryPropertyResolution._mode
+ _OBJC_IVAR_$_LNQueryRequestOptions._entityOptions
+ _OBJC_METACLASS_$_LNQueryEntityOptions
+ _OBJC_METACLASS_$_LNQueryPropertyResolution
+ _OBJC_METACLASS_$__TtC12LinkServicesP33_2F0A97DEF09105C7A1532988C82F400B36LNFetchEntityPropertyValuesOperation
+ __DATA__TtC12LinkServicesP33_2F0A97DEF09105C7A1532988C82F400B36LNFetchEntityPropertyValuesOperation
+ __INSTANCE_METHODS__TtC12LinkServicesP33_2F0A97DEF09105C7A1532988C82F400B36LNFetchEntityPropertyValuesOperation
+ __IVARS__TtC12LinkServicesP33_2F0A97DEF09105C7A1532988C82F400B36LNFetchEntityPropertyValuesOperation
+ __METACLASS_DATA__TtC12LinkServicesP33_2F0A97DEF09105C7A1532988C82F400B36LNFetchEntityPropertyValuesOperation
+ __OBJC_$_CLASS_METHODS_LNConnection(FetchEntityPropertyValue|FetchEntityPropertyValues|FetchEntitySnippet|FetchEntityURL|FetchEnumURL|LinkUndoManagers|ModelRepresentation|Prewarm|ResolveParameter|ResolveValue|StageContext|Transferable|UpdateProperties|Deprecated|AsyncSequence|AppShortcutParameters|FetchActionAppContext|FetchActionForAutoShortcutPhrase|FetchActionOutputValue|FetchAppIntentState|FetchAppShortcutParameters|FetchDisplayRepresentation|FetchListenerEndpoint|FetchMDMProperties|FetchOptions|FetchOptions_Deprecated|FetchOptionsDefaultValue|FetchOptionsDefaultValue_Deprecated|FetchSuggestedActions|FetchSuggestedFocusActions|FetchViewObjects|PerformQuery|PerformQuery_Deprecated)
+ __OBJC_$_CLASS_METHODS_LNDaemonConnection
+ __OBJC_$_CLASS_METHODS_LNExtensionConnection
+ __OBJC_$_CLASS_METHODS_LNFrameworkConnection
+ __OBJC_$_CLASS_METHODS_LNInProcessConnection
+ __OBJC_$_CLASS_METHODS_LNQueryEntityOptions
+ __OBJC_$_CLASS_METHODS_LNQueryPropertyResolution
+ __OBJC_$_CLASS_METHODS_LNXPCListenerEndpointConnection
+ __OBJC_$_CLASS_PROP_LIST_LNQueryEntityOptions
+ __OBJC_$_CLASS_PROP_LIST_LNQueryPropertyResolution
+ __OBJC_$_INSTANCE_METHODS_LNConnection(FetchEntityPropertyValue|FetchEntityPropertyValues|FetchEntitySnippet|FetchEntityURL|FetchEnumURL|LinkUndoManagers|ModelRepresentation|Prewarm|ResolveParameter|ResolveValue|StageContext|Transferable|UpdateProperties|Deprecated|AsyncSequence|AppShortcutParameters|FetchActionAppContext|FetchActionForAutoShortcutPhrase|FetchActionOutputValue|FetchAppIntentState|FetchAppShortcutParameters|FetchDisplayRepresentation|FetchListenerEndpoint|FetchMDMProperties|FetchOptions|FetchOptions_Deprecated|FetchOptionsDefaultValue|FetchOptionsDefaultValue_Deprecated|FetchSuggestedActions|FetchSuggestedFocusActions|FetchViewObjects|PerformQuery|PerformQuery_Deprecated)
+ __OBJC_$_INSTANCE_METHODS_LNQueryEntityOptions
+ __OBJC_$_INSTANCE_METHODS_LNQueryPropertyResolution
+ __OBJC_$_INSTANCE_METHODS_LNQueryRequestOptions(Deprecated)
+ __OBJC_$_INSTANCE_VARIABLES_LNQueryEntityOptions
+ __OBJC_$_INSTANCE_VARIABLES_LNQueryPropertyResolution
+ __OBJC_$_PROP_LIST_LNQueryEntityOptions
+ __OBJC_$_PROP_LIST_LNQueryPropertyResolution
+ __OBJC_CLASS_PROTOCOLS_$_LNQueryEntityOptions
+ __OBJC_CLASS_PROTOCOLS_$_LNQueryPropertyResolution
+ __OBJC_CLASS_RO_$_LNQueryEntityOptions
+ __OBJC_CLASS_RO_$_LNQueryPropertyResolution
+ __OBJC_METACLASS_RO_$_LNQueryEntityOptions
+ __OBJC_METACLASS_RO_$_LNQueryPropertyResolution
+ ___105-[_LNMetadataProviderXPC actionsConformingToSystemProtocol:withParametersOfTypes:bundleIdentifier:error:]_block_invoke_3
+ ___107-[_LNMetadataProviderXPC openCollectionActionsForEntityTypeIdentifier:capabilities:bundleIdentifier:error:]_block_invoke_3
+ ___107-[_LNMetadataProviderXPC queriesForBundleIdentifier:withCapabilities:inputValueType:resultValueType:error:]_block_invoke_3
+ ___41-[_LNMetadataProviderXPC enumsWithError:]_block_invoke_3
+ ___43-[_LNMetadataProviderXPC actionsWithError:]_block_invoke_3
+ ___43-[_LNMetadataProviderXPC bundlesWithError:]_block_invoke_3
+ ___43-[_LNMetadataProviderXPC queriesWithError:]_block_invoke_3
+ ___44-[_LNMetadataProviderXPC entitiesWithError:]_block_invoke_3
+ ___46-[LNAutoShortcutsProvider appShortcutBundles:]_block_invoke
+ ___50-[_LNAutoShortcutsProviderXPC appShortcutBundles:]_block_invoke
+ ___50-[_LNAutoShortcutsProviderXPC appShortcutBundles:]_block_invoke_2
+ ___55-[_LNMetadataProviderXPC bundleRegistrationsWithError:]_block_invoke_3
+ ___57-[_LNMetadataProviderXPC enumsForBundleIdentifier:error:]_block_invoke_3
+ ___57-[_LNMetadataProviderXPC enumsForSchemaIdentifier:error:]_block_invoke_3
+ ___59-[_LNMetadataProviderXPC actionsForBundleIdentifier:error:]_block_invoke_3
+ ___59-[_LNMetadataProviderXPC actionsForSchemaIdentifier:error:]_block_invoke_3
+ ___59-[_LNMetadataProviderXPC queriesForSchemaIdentifier:error:]_block_invoke_3
+ ___60-[_LNMetadataProviderXPC entitiesForBundleIdentifier:error:]_block_invoke_3
+ ___60-[_LNMetadataProviderXPC entitiesForSchemaIdentifier:error:]_block_invoke_3
+ ___60-[_LNMetadataProviderXPC suggestionPhrasesForQueries:error:]_block_invoke_3
+ ___64-[_LNMetadataProviderXPC queryForBundleIdentifier:ofType:error:]_block_invoke_3
+ ___66-[_LNMetadataProviderXPC examplePhrasesForBundleIdentifier:error:]_block_invoke_3
+ ___66-[_LNMetadataProviderXPC queriesForBundleIdentifier:ofType:error:]_block_invoke_3
+ ___69-[_LNMetadataProviderXPC actionIdentifiersForBundleIdentifier:error:]_block_invoke_3
+ ___69-[_LNMetadataProviderXPC actionsWithFullyQualifiedIdentifiers:error:]_block_invoke_3
+ ___69-[_LNMetadataProviderXPC entityIdentifiersForBundleIdentifier:error:]_block_invoke_3
+ ___78-[_LNMetadataProviderXPC actionForBundleIdentifier:andActionIdentifier:error:]_block_invoke_3
+ ___78-[_LNMetadataProviderXPC openActionsForTypeIdentifier:bundleIdentifier:error:]_block_invoke_3
+ ___79-[_LNMetadataProviderXPC actionsForBundleIdentifier:andActionIdentifier:error:]_block_invoke_3
+ ___79-[_LNMetadataProviderXPC entityForBundleIdentifier:withEntityIdentifier:error:]_block_invoke_3
+ ___81-[LNConnection fetchListenerEndpointFromApplicationServiceWithCompletionHandler:]_block_invoke_2
+ ___83-[LNAutoShortcutsProvider autoShortcutsForBundleIdentifier:localeIdentifier:error:]_block_invoke
+ ___83-[LNAutoShortcutsProvider autoShortcutsForBundleIdentifier:localeIdentifier:error:]_block_invoke_2
+ ___84-[_LNMetadataProviderXPC actionsAndSystemProtocolDefaultsForBundleIdentifier:error:]_block_invoke_3
+ ___86-[_LNMetadataProviderXPC queryForBundleIdentifier:withFullyQualifiedIdentifier:error:]_block_invoke_3
+ ___87-[_LNAutoShortcutsProviderXPC autoShortcutsForBundleIdentifier:localeIdentifier:error:]_block_invoke
+ ___87-[_LNAutoShortcutsProviderXPC autoShortcutsForBundleIdentifier:localeIdentifier:error:]_block_invoke_2
+ ___87-[_LNMetadataProviderXPC appShortcutsProviderMangledTypeNameForBundleIdentifier:error:]_block_invoke_3
+ ___87-[_LNMetadataProviderXPC queriesWithCapabilities:inputValueType:resultValueType:error:]_block_invoke_3
+ ___94-[_LNMetadataProviderXPC actionForBundleIdentifier:andActionIdentifier:waitForIndexing:error:]_block_invoke_3
+ ___96-[_LNMetadataProviderXPC actionsConformingToSystemProtocols:logicalType:bundleIdentifier:error:]_block_invoke_3
+ ___block_descriptor_48_e8_32bs40r_e50_v24?0"LNConnectionListenerEndpoint"8"NSError"16lr40l8s32l8
+ ___block_descriptor_56_e8_32s40r48r_e9_16?0^8lr40l8r48l8s32l8
+ ___block_descriptor_64_e8_32s40s48r56r_e9_16?0^8lr48l8r56l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56r64r_e9_16?0^8lr56l8r64l8s32l8s40l8s48l8
+ ___block_descriptor_73_e8_32s40s48s56r64r_e9_16?0^8lr56l8r64l8s32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56bs64r72r_e5_v8?0ls32l8r64l8s40l8s48l8r72l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56r64r_e9_16?0^8lr56l8r64l8s32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56s64r72r_e9_16?0^8lr64l8r72l8s32l8s40l8s48l8s56l8
+ ___block_descriptor_88_e8_32s40s48s56s64r72r_e9_16?0^8lr64l8r72l8s32l8s40l8s48l8s56l8
+ __dyld_lazy_load
+ __requireArrayOfNonEmptyStrings
+ _bzero
+ _isContinueInAppWithoutConfirmationDelegateOverride
+ _lazyLoadFlag$UIKit
+ _symbolic _____ 12LinkServices36LNFetchEntityPropertyValuesOperation33_2F0A97DEF09105C7A1532988C82F400BLLC
+ _symbolic _____ So24LNTranscriptActionSourceV
- -[LNContinueInAppRequest initWithIdentifier:dialog:throwing:requestConfirmation:type:sceneOptions:bundleIdentifier:options:]
- -[LNQueryRequestOptions componentKindConfiguration]
- -[LNQueryRequestOptions levelOfDetailConfiguration]
- -[LNQueryRequestOptions requiresStableEntityIdentifiers]
- -[LNQueryRequestOptions setComponentKindConfiguration:]
- -[LNQueryRequestOptions setLevelOfDetailConfiguration:]
- -[LNQueryRequestOptions setRequiresStableEntityIdentifiers:]
- -[LNXPCListenerEndpointConnection acquireAssertionsForConnectionOperation:]
- GCC_except_table1013
- GCC_except_table1015
- GCC_except_table1017
- GCC_except_table1027
- GCC_except_table1028
- GCC_except_table1037
- GCC_except_table1080
- GCC_except_table1081
- GCC_except_table1082
- GCC_except_table1123
- GCC_except_table1124
- GCC_except_table1125
- GCC_except_table1131
- GCC_except_table1141
- GCC_except_table1143
- GCC_except_table1144
- GCC_except_table1150
- GCC_except_table1157
- GCC_except_table1162
- GCC_except_table1175
- GCC_except_table1188
- GCC_except_table1207
- GCC_except_table1239
- GCC_except_table1243
- GCC_except_table1508
- GCC_except_table1519
- GCC_except_table1540
- GCC_except_table1550
- GCC_except_table1553
- GCC_except_table1555
- GCC_except_table1568
- GCC_except_table1569
- GCC_except_table165
- GCC_except_table168
- GCC_except_table1693
- GCC_except_table1714
- GCC_except_table1725
- GCC_except_table1734
- GCC_except_table1752
- GCC_except_table1774
- GCC_except_table1786
- GCC_except_table1802
- GCC_except_table1860
- GCC_except_table1865
- GCC_except_table1892
- GCC_except_table1898
- GCC_except_table1900
- GCC_except_table1902
- GCC_except_table1914
- GCC_except_table1926
- GCC_except_table1938
- GCC_except_table1950
- GCC_except_table1962
- GCC_except_table1978
- GCC_except_table1990
- GCC_except_table2025
- GCC_except_table2037
- GCC_except_table2047
- GCC_except_table2061
- GCC_except_table2071
- GCC_except_table2083
- GCC_except_table2108
- GCC_except_table212
- GCC_except_table2133
- GCC_except_table2144
- GCC_except_table2158
- GCC_except_table216
- GCC_except_table2170
- GCC_except_table2171
- GCC_except_table2182
- GCC_except_table225
- GCC_except_table229
- GCC_except_table2453
- GCC_except_table249
- GCC_except_table258
- GCC_except_table273
- GCC_except_table275
- GCC_except_table2860
- GCC_except_table2863
- GCC_except_table2913
- GCC_except_table3009
- GCC_except_table3021
- GCC_except_table3071
- GCC_except_table3076
- GCC_except_table3080
- GCC_except_table3093
- GCC_except_table3111
- GCC_except_table3116
- GCC_except_table3125
- GCC_except_table3129
- GCC_except_table3234
- GCC_except_table3236
- GCC_except_table328
- GCC_except_table338
- GCC_except_table339
- GCC_except_table341
- GCC_except_table342
- GCC_except_table343
- GCC_except_table344
- GCC_except_table345
- GCC_except_table346
- GCC_except_table347
- GCC_except_table348
- GCC_except_table349
- GCC_except_table403
- GCC_except_table572
- GCC_except_table595
- GCC_except_table600
- GCC_except_table604
- GCC_except_table610
- GCC_except_table613
- GCC_except_table619
- GCC_except_table622
- GCC_except_table625
- GCC_except_table630
- GCC_except_table633
- GCC_except_table636
- GCC_except_table639
- GCC_except_table645
- GCC_except_table648
- GCC_except_table651
- GCC_except_table655
- GCC_except_table658
- GCC_except_table661
- GCC_except_table667
- GCC_except_table670
- GCC_except_table673
- GCC_except_table679
- GCC_except_table682
- GCC_except_table685
- GCC_except_table691
- GCC_except_table694
- GCC_except_table697
- GCC_except_table703
- GCC_except_table706
- GCC_except_table714
- GCC_except_table722
- GCC_except_table726
- GCC_except_table729
- GCC_except_table731
- GCC_except_table733
- GCC_except_table735
- GCC_except_table737
- GCC_except_table739
- GCC_except_table743
- GCC_except_table758
- GCC_except_table765
- GCC_except_table775
- GCC_except_table777
- GCC_except_table779
- GCC_except_table781
- GCC_except_table783
- GCC_except_table785
- GCC_except_table787
- GCC_except_table789
- GCC_except_table791
- GCC_except_table793
- GCC_except_table795
- GCC_except_table797
- GCC_except_table799
- GCC_except_table801
- GCC_except_table929
- GCC_except_table935
- GCC_except_table937
- GCC_except_table955
- _OBJC_IVAR_$_LNQueryRequestOptions._componentKindConfiguration
- _OBJC_IVAR_$_LNQueryRequestOptions._levelOfDetailConfiguration
- _OBJC_IVAR_$_LNQueryRequestOptions._requiresStableEntityIdentifiers
- _OUTLINED_FUNCTION_201
- _OUTLINED_FUNCTION_202
- _OUTLINED_FUNCTION_203
- _OUTLINED_FUNCTION_204
- _OUTLINED_FUNCTION_205
- _UIKitLibraryCore.frameworkLibrary
- __OBJC_$_CLASS_METHODS_LNConnection(FetchEntityPropertyValue|FetchEntitySnippet|FetchEntityURL|FetchEnumURL|LinkUndoManagers|ModelRepresentation|Prewarm|ResolveParameter|ResolveValue|StageContext|Transferable|UpdateProperties|Deprecated|AsyncSequence|AppShortcutParameters|FetchActionAppContext|FetchActionForAutoShortcutPhrase|FetchActionOutputValue|FetchAppIntentState|FetchAppShortcutParameters|FetchDisplayRepresentation|FetchListenerEndpoint|FetchMDMProperties|FetchOptions|FetchOptions_Deprecated|FetchOptionsDefaultValue|FetchOptionsDefaultValue_Deprecated|FetchSuggestedActions|FetchSuggestedFocusActions|FetchViewObjects|PerformQuery|PerformQuery_Deprecated)
- __OBJC_$_INSTANCE_METHODS_LNConnection(FetchEntityPropertyValue|FetchEntitySnippet|FetchEntityURL|FetchEnumURL|LinkUndoManagers|ModelRepresentation|Prewarm|ResolveParameter|ResolveValue|StageContext|Transferable|UpdateProperties|Deprecated|AsyncSequence|AppShortcutParameters|FetchActionAppContext|FetchActionForAutoShortcutPhrase|FetchActionOutputValue|FetchAppIntentState|FetchAppShortcutParameters|FetchDisplayRepresentation|FetchListenerEndpoint|FetchMDMProperties|FetchOptions|FetchOptions_Deprecated|FetchOptionsDefaultValue|FetchOptionsDefaultValue_Deprecated|FetchSuggestedActions|FetchSuggestedFocusActions|FetchViewObjects|PerformQuery|PerformQuery_Deprecated)
- __OBJC_$_INSTANCE_METHODS_LNQueryRequestOptions
- __OBJC_$_PROP_LIST_LNQueryRequestOptions
- ___75-[LNConnection performGetConnectionInterfaceWithOptions:completionHandler:]_block_invoke_2
- ___UIKitLibraryCore_block_invoke
- ___getUILinkConnectionActionClass_block_invoke
- _audit_stringUIKit
- _getUILinkConnectionActionClass.softClass
CStrings:
+ "%{public}@ Already %{public}@, waiting for in-flight connection to complete"
+ "%{public}@ Closing connection with %lu outstanding operations"
+ "%{public}@ Connection disconnected (was %{public}@, error: %{public}@)"
+ "%{public}@ Connection established successfully (was %{public}@)"
+ "%{public}@ Connection operation finished: %{public}@ (error: %{public}@)"
+ "%{public}@ Connection operation starting: %{public}@ (priority: %ld)"
+ "%{public}@ Enqueuing connection operation %{public}@ (active operations: %lu)"
+ "%{public}@ Enqueuing getConnectionInterface request (pending operations: %ld, suspended: %d)"
+ "%{public}@ Failed to fetch listener endpoint for processInstanceIdentifier %{public}@: %{public}@"
+ "%{public}@ Initiating connection with options: %{public}@"
+ "%{public}@ No processInstanceIdentifier set, skipping process-based connection"
+ "%{public}@ Refresh needed: framework bundle identifier may have changed"
+ "%{public}@ Refresh needed: options changed from %{public}@ to %{public}@"
+ "%{public}@ Refresh needed: userIdentity is set"
+ "%{public}@ Refresh not needed, completing immediately"
+ "%{public}@ Refreshing connection with options: %{public}@"
+ "%{public}@ Removed connection operation %{public}@ (remaining operations: %lu)"
+ "%{public}@ Resuming the getConnectionInterface queue (pending operations: %ld)"
+ "%{public}@ Successfully fetched listener endpoint for processInstanceIdentifier %{public}@, establishing direct connection"
+ "%{public}@ Suspending getConnectionInterface queue (state: %{public}@)"
+ "%{public}@ completeWithError: called with no pending completion handler (state: %{public}@, error: %{public}@) — queue will NOT be resumed"
+ "%{public}s: XPC interrupted, retrying"
+ "%{public}s: XPC retry failed"
+ "-[_LNMetadataProviderXPC actionForBundleIdentifier:andActionIdentifier:error:]"
+ "-[_LNMetadataProviderXPC actionForBundleIdentifier:andActionIdentifier:waitForIndexing:error:]"
+ "-[_LNMetadataProviderXPC actionIdentifiersForBundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC actionsAndSystemProtocolDefaultsForBundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC actionsConformingToSystemProtocol:withParametersOfTypes:bundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC actionsConformingToSystemProtocols:logicalType:bundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC actionsForBundleIdentifier:andActionIdentifier:error:]"
+ "-[_LNMetadataProviderXPC actionsForBundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC actionsForSchemaIdentifier:error:]"
+ "-[_LNMetadataProviderXPC actionsWithError:]"
+ "-[_LNMetadataProviderXPC actionsWithFullyQualifiedIdentifiers:error:]"
+ "-[_LNMetadataProviderXPC appShortcutsProviderMangledTypeNameForBundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC bundleRegistrationsWithError:]"
+ "-[_LNMetadataProviderXPC bundlesWithError:]"
+ "-[_LNMetadataProviderXPC entitiesForBundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC entitiesForSchemaIdentifier:error:]"
+ "-[_LNMetadataProviderXPC entitiesWithError:]"
+ "-[_LNMetadataProviderXPC entityForBundleIdentifier:withEntityIdentifier:error:]"
+ "-[_LNMetadataProviderXPC entityIdentifiersForBundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC enumsForBundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC enumsForSchemaIdentifier:error:]"
+ "-[_LNMetadataProviderXPC enumsWithError:]"
+ "-[_LNMetadataProviderXPC examplePhrasesForBundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC openActionsForTypeIdentifier:bundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC openCollectionActionsForEntityTypeIdentifier:capabilities:bundleIdentifier:error:]"
+ "-[_LNMetadataProviderXPC queriesForBundleIdentifier:ofType:error:]"
+ "-[_LNMetadataProviderXPC queriesForBundleIdentifier:withCapabilities:inputValueType:resultValueType:error:]"
+ "-[_LNMetadataProviderXPC queriesForSchemaIdentifier:error:]"
+ "-[_LNMetadataProviderXPC queriesWithCapabilities:inputValueType:resultValueType:error:]"
+ "-[_LNMetadataProviderXPC queriesWithError:]"
+ "-[_LNMetadataProviderXPC queryForBundleIdentifier:ofType:error:]"
+ "-[_LNMetadataProviderXPC queryForBundleIdentifier:withFullyQualifiedIdentifier:error:]"
+ "-[_LNMetadataProviderXPC suggestionPhrasesForQueries:error:]"
+ "<%@ asyncSequenceThreshold: %ld, convertArrayResultToAsyncSequence: %@, exportConfiguration: %@, entityOptions: %@>"
+ "<%@: %p, identifier: %@, dialog: %@, isThrowing: %@, requestConfirmation: %@, type: %@, sceneOptions: %@, bundleIdentifier: %@, dismissSiri: %@, continueWithoutConfirmationReason: %@>"
+ "<LNQueryEntityOptions levelOfDetail: %@, componentKinds: %@, requiresStableEntityIdentifiers: %@, propertyResolution: %@, maximumArrayPropertyItemCount: %ld, maximumEntityDepth: %ld, deferredPropertyResolutionTimeout: %g, deferredPropertyResolutionConcurrencyLimit: %ld>"
+ "<LNQueryPropertyResolution mode: %@, identifiers: %@>"
+ "@16@?0^@8"
+ "Continue In App Without Confirmation Delegate"
+ "Continuing without confirmation (reason: %{public}@), skipping delegate"
+ "DELEGATE DOES NOT IMPLEMENT SELECTOR -executor:needsContinueInAppWithRequest:, THIS WILL BECOME A FATAL ERROR IN A FUTURE RELEASE"
+ "Daemon-Owned macOS App Connection"
+ "Entitlement"
+ "Failed to fetch app shortcut bundles: %{public}@"
+ "Framework"
+ "InProcess"
+ "LNConnection subclasses must provide connectionDescription"
+ "LinkServices.LNFetchEntityPropertyValuesOperation"
+ "ListenerEndpoint"
+ "RecentInteraction"
+ "Unexpected direct call for app shortcut bundles"
+ "[%@] %@"
+ "additionalDeferred"
+ "appintent:fetch entity property values"
+ "appintents:fetch app shortcut bundles"
+ "appintents:fetch app shortcut for bundle"
+ "appintents:fetch app shortcuts for bundle"
+ "appintents:fetch app shortcuts for record"
+ "connected"
+ "continueInAppWithoutConfirmationDelegate"
+ "continueWithoutConfirmationReason"
+ "deferredPropertyResolutionConcurrencyLimit"
+ "deferredPropertyResolutionTimeout"
+ "disconnected"
+ "entityOptions"
+ "included"
+ "kMDItemIsPartiallyDownloaded"
+ "maximumArrayPropertyItemCount"
+ "maximumEntityDepth"
+ "mode"
+ "none"
+ "policyWithBundleIdentifier: is deprecated"
+ "policyWithBundleIdentifier: is deprecated. Migrate to LNConnectionPolicy factory methods that accept metadata instead (e.g. policyWithActionMetadata:, policyWithEntityMetadata:, policyWithEntityQueryMetadata:, policyWithEnumMetadata:)."
+ "propertyResolution"
+ "refreshing"
- "%{public}@ Assertion is not required for XPC listener endpoint connection"
- "%{public}@ Resuming the getConnectionInterface queue"
- "%{public}@ [%{public}@]: Received UILinkConnectionActionResponse callback with action response: %{public}@"
- "<%@ asyncSequenceThreshold: %ld, convertArrayResultToAsyncSequence: %@, exportConfiguration: %@, levelOfDetailConfiguration: %@, componentKindConfiguration: %@, requiresStableEntityIdentifiers: %@>"
- "<%@: %p, identifier: %@, dialog: %@, isThrowing: %@, requestConfirmation: %@, type: %@, sceneOptions: %@, bundleIdentifier: %@, dismissSiri: %@>"
- "Class getUILinkConnectionActionClass(void)_block_invoke"
- "UILinkConnectionAction"
- "appintents:fetch app shortcuts"
- "softlink:r:path:/System/Library/Frameworks/UIKit.framework/UIKit"
- "void *UIKitLibrary(void)"
```
