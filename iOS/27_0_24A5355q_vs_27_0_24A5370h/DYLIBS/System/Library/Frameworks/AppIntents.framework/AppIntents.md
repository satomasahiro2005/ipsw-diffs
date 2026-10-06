## AppIntents

> `/System/Library/Frameworks/AppIntents.framework/AppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bf3a0` | `0x4d67dc` | **`+0x1743c`** |
| `__AUTH_CONST.__const` | `0x25d08` | `0x27f88` | **`+0x2280`** |
| `__TEXT.__eh_frame` | `0x2d3d4` | `0x2e568` | **`+0x1194`** |
| `__TEXT.__swift5_capture` | `0x5e10` | `0x6cc4` | **`+0xeb4`** |
| `__TEXT.__unwind_info` | `0x16108` | `0x16708` | **`+0x600`** |
| `__TEXT.__constg_swiftt` | `0x139c0` | `0x136e8` | **`-0x2d8`** |
| `__TEXT.__oslogstring` | `0x6a39` | `0x6b89` | **`+0x150`** |
| `__DATA.__data` | `0xf460` | `0xf318` | **`-0x148`** |
| `__DATA_DIRTY.__data` | `0x4940` | `0x4870` | **`-0xd0`** |
| `__TEXT.__swift5_typeref` | `0x1318b` | `0x13235` | **`+0xaa`** |
| `__TEXT.__swift_as_cont` | `0x25e8` | `0x268c` | **`+0xa4`** |
| `__TEXT.__const` | `0x35220` | `0x352c0` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2418` | `0x2498` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x89ec` | `0x8a6c` | **`+0x80`** |
| `__TEXT.__swift_as_ret` | `0x1850` | `0x18d0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x6e1e` | `0x6e8d` | **`+0x6f`** |
| `__TEXT.__swift_as_entry` | `0x167c` | `0x16e4` | **`+0x68`** |
| `__TEXT.__dlopen_cstrs` | `0x9a` | `0xf7` | **`+0x5d`** |
| `__AUTH_CONST.__objc_const` | `0x5378` | `0x53c0` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x2330` | `0x2370` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1740` | `0x1768` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x16fc` | `0x171c` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x5c8` | `0x5dc` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x29a4` | `0x2990` | **`-0x14`** |
| `__TEXT.__swift5_protos` | `0x4ec` | `0x4d8` | **`-0x14`** |
| `__DATA.__bss` | `0x3fbb0` | `0x3fbc0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xb7b4` | `0xb7a4` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x168` | `0x174` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0xe3c` | `0xe34` | **`-0x8`** |
| `__DATA.__common` | `0x310` | `0x309` | **`-0x7`** |

### Other Changes

```diff

-301.0.41.16.106
+301.0.42.7.0

-  Functions: 35534
-  Symbols:   7917
-  CStrings:  1217
+  Functions: 36234
+  Symbols:   8051
+  CStrings:  1223
Symbols:
+ -[LNClientConnection fetchValuesForProperties:entities:completionHandler:]
+ GCC_except_table356
+ GCC_except_table360
+ GCC_except_table362
+ GCC_except_table366
+ GCC_except_table377
+ GCC_except_table380
+ GCC_except_table382
+ __AppIntents_SwiftUILibraryCore.frameworkLibrary
+ __OBJC_$_INSTANCE_METHODS_LNAppContext(AppIntents|AppIntents1|AppIntents2|AppIntents3|AppIntents4|AppIntents5|AppIntents6|AppIntents7|AppIntents8|AppIntents9|AppIntents10|AppIntents11|AppIntents12|AppIntents13|AppIntents14|AppIntents15|AppIntents16|AppIntents17|AppIntents18|AppIntents19|AppIntents20|AppIntents21|AppIntents22|AppIntents23|AppIntents24|AppIntents25|AppIntents26|AppIntents27|AppIntents28|AppIntents29)
+ ___102-[LNClientConnection fetchSuggestedFocusActionsForActionMetadata:suggestionContext:completionHandler:]_block_invoke_4
+ ___102-[LNClientConnection fetchSuggestedFocusActionsForActionMetadata:suggestionContext:completionHandler:]_block_invoke_5
+ ___117-[LNClientConnection fetchParameterOptionDefaultValueForAction:actionMetadata:parameterIdentifier:completionHandler:]_block_invoke_4
+ ___117-[LNClientConnection fetchParameterOptionDefaultValueForAction:actionMetadata:parameterIdentifier:completionHandler:]_block_invoke_5
+ ___132-[LNClientConnection deriveModelRepresentationsForEntities:levelOfDetailConfiguration:componentKindConfiguration:completionHandler:]_block_invoke_4
+ ___132-[LNClientConnection deriveModelRepresentationsForEntities:levelOfDetailConfiguration:componentKindConfiguration:completionHandler:]_block_invoke_5
+ ___148-[LNClientConnection fetchOptionsForAction:actionMetadata:parameterMetadata:optionsProviderReference:searchTerm:localeIdentifier:completionHandler:]_block_invoke_4
+ ___148-[LNClientConnection fetchOptionsForAction:actionMetadata:parameterMetadata:optionsProviderReference:searchTerm:localeIdentifier:completionHandler:]_block_invoke_5
+ ___55-[LNClientConnection fetchEntityURL:completionHandler:]_block_invoke_4
+ ___55-[LNClientConnection fetchEntityURL:completionHandler:]_block_invoke_5
+ ___59-[LNClientConnection cancelOperationWithIdentifier:reason:]_block_invoke_2
+ ___59-[LNClientConnection linkAppUndoManager:completionHandler:]_block_invoke_4
+ ___59-[LNClientConnection linkAppUndoManager:completionHandler:]_block_invoke_5
+ ___60-[LNClientConnection fetchViewActionsWithCompletionHandler:]_block_invoke_4
+ ___60-[LNClientConnection fetchViewActionsWithCompletionHandler:]_block_invoke_5
+ ___61-[LNClientConnection performPropertyQuery:completionHandler:]_block_invoke_4
+ ___61-[LNClientConnection performPropertyQuery:completionHandler:]_block_invoke_5
+ ___61-[LNClientConnection releaseAsyncSequence:completionHandler:]_block_invoke_4
+ ___61-[LNClientConnection releaseAsyncSequence:completionHandler:]_block_invoke_5
+ ___63-[LNClientConnection getListenerEndpointWithCompletionHandler:]_block_invoke_2
+ ___64-[LNClientConnection stageContextWithRequest:completionHandler:]_block_invoke_4
+ ___64-[LNClientConnection stageContextWithRequest:completionHandler:]_block_invoke_5
+ ___64-[LNClientConnection updateConnectionContext:completionHandler:]_block_invoke_4
+ ___64-[LNClientConnection updateConnectionContext:completionHandler:]_block_invoke_5
+ ___65-[LNClientConnection nextAsyncIteratorResults:completionHandler:]_block_invoke_4
+ ___65-[LNClientConnection nextAsyncIteratorResults:completionHandler:]_block_invoke_5
+ ___65-[LNClientConnection performConfigurableQuery:completionHandler:]_block_invoke_4
+ ___65-[LNClientConnection performConfigurableQuery:completionHandler:]_block_invoke_5
+ ___65-[LNClientConnection resolveValue:toValueType:completionHandler:]_block_invoke_4
+ ___65-[LNClientConnection resolveValue:toValueType:completionHandler:]_block_invoke_5
+ ___67-[LNClientConnection updateProperties:withQuery:completionHandler:]_block_invoke_4
+ ___67-[LNClientConnection updateProperties:withQuery:completionHandler:]_block_invoke_5
+ ___71-[LNClientConnection fetchURLsForEnumWithIdentifier:completionHandler:]_block_invoke_4
+ ___71-[LNClientConnection fetchURLsForEnumWithIdentifier:completionHandler:]_block_invoke_5
+ ___71-[LNClientConnection performAction:options:executor:completionHandler:]_block_invoke_4
+ ___71-[LNClientConnection performAction:options:executor:completionHandler:]_block_invoke_5
+ ___71-[LNClientConnection performActionOperation:didFinishWithResult:error:]_block_invoke_2
+ ___71-[LNClientConnection updateAppShortcutParametersWithCompletionHandler:]_block_invoke_4
+ ___71-[LNClientConnection updateAppShortcutParametersWithCompletionHandler:]_block_invoke_5
+ ___72-[LNClientConnection fetchActionAppContextFromAction:completionHandler:]_block_invoke_4
+ ___72-[LNClientConnection fetchActionAppContextFromAction:completionHandler:]_block_invoke_5
+ ___73-[LNClientConnection fetchActionForAutoShortcutPhrase:completionHandler:]_block_invoke_4
+ ___73-[LNClientConnection fetchActionForAutoShortcutPhrase:completionHandler:]_block_invoke_5
+ ___73-[LNClientConnection fetchSuggestedActionsFromViewWithCompletionHandler:]_block_invoke_4
+ ___73-[LNClientConnection fetchSuggestedActionsFromViewWithCompletionHandler:]_block_invoke_5
+ ___74-[LNClientConnection fetchStateForAppIntentIdentifiers:completionHandler:]_block_invoke_4
+ ___74-[LNClientConnection fetchStateForAppIntentIdentifiers:completionHandler:]_block_invoke_5
+ ___74-[LNClientConnection fetchValuesForProperties:entities:completionHandler:]_block_invoke
+ ___74-[LNClientConnection fetchValuesForProperties:entities:completionHandler:]_block_invoke_2
+ ___74-[LNClientConnection fetchValuesForProperties:entities:completionHandler:]_block_invoke_3
+ ___74-[LNClientConnection fetchValuesForProperties:entities:completionHandler:]_block_invoke_4
+ ___74-[LNClientConnection fetchValuesForProperties:entities:completionHandler:]_block_invoke_5
+ ___75-[LNClientConnection fetchOptionsDefaultValuesForAction:completionHandler:]_block_invoke_4
+ ___75-[LNClientConnection fetchOptionsDefaultValuesForAction:completionHandler:]_block_invoke_5
+ ___76-[LNClientConnection fetchActionForAppShortcutIdentifier:completionHandler:]_block_invoke_4
+ ___76-[LNClientConnection fetchActionForAppShortcutIdentifier:completionHandler:]_block_invoke_5
+ ___76-[LNClientConnection fetchViewEntitiesWithInteractionIDs:completionHandler:]_block_invoke_4
+ ___76-[LNClientConnection fetchViewEntitiesWithInteractionIDs:completionHandler:]_block_invoke_5
+ ___77-[LNClientConnection fetchActionOutputValueWithIdentifier:completionHandler:]_block_invoke_4
+ ___77-[LNClientConnection fetchActionOutputValueWithIdentifier:completionHandler:]_block_invoke_5
+ ___77-[LNClientConnection fetchDisplayRepresentationForActions:completionHandler:]_block_invoke_4
+ ___77-[LNClientConnection fetchDisplayRepresentationForActions:completionHandler:]_block_invoke_5
+ ___78-[LNClientConnection resolveParameterWithIdentifier:action:completionHandler:]_block_invoke_4
+ ___78-[LNClientConnection resolveParameterWithIdentifier:action:completionHandler:]_block_invoke_5
+ ___79-[LNClientConnection createAsyncIteratorForSequence:options:completionHandler:]_block_invoke_4
+ ___79-[LNClientConnection createAsyncIteratorForSequence:options:completionHandler:]_block_invoke_5
+ ___79-[LNClientConnection fetchEntitySnippetForValue:snippetType:completionHandler:]_block_invoke_4
+ ___79-[LNClientConnection fetchEntitySnippetForValue:snippetType:completionHandler:]_block_invoke_5
+ ___82-[LNClientConnection exportTransientEntities:withConfiguration:completionHandler:]_block_invoke_4
+ ___82-[LNClientConnection exportTransientEntities:withConfiguration:completionHandler:]_block_invoke_5
+ ___82-[LNClientConnection fetchSuggestedActionsWithSiriLanguageCode:completionHandler:]_block_invoke_4
+ ___82-[LNClientConnection fetchSuggestedActionsWithSiriLanguageCode:completionHandler:]_block_invoke_5
+ ___83-[LNClientConnection fetchSuggestedActionsForStartWorkoutAction:completionHandler:]_block_invoke_4
+ ___83-[LNClientConnection fetchSuggestedActionsForStartWorkoutAction:completionHandler:]_block_invoke_5
+ ___83-[LNClientConnection fetchValueForPropertyWithIdentifier:entity:completionHandler:]_block_invoke_4
+ ___83-[LNClientConnection fetchValueForPropertyWithIdentifier:entity:completionHandler:]_block_invoke_5
+ ___83-[LNClientConnection performSuggestedResultsQueryWithEntityType:completionHandler:]_block_invoke_4
+ ___83-[LNClientConnection performSuggestedResultsQueryWithEntityType:completionHandler:]_block_invoke_5
+ ___85-[LNClientConnection fetchAppShortcutParametersForMangledName:withCompletionHandler:]_block_invoke_4
+ ___85-[LNClientConnection fetchAppShortcutParametersForMangledName:withCompletionHandler:]_block_invoke_5
+ ___85-[LNClientConnection fetchURLForEnumWithIdentifier:caseIdentifier:completionHandler:]_block_invoke_4
+ ___85-[LNClientConnection fetchURLForEnumWithIdentifier:caseIdentifier:completionHandler:]_block_invoke_5
+ ___86-[LNClientConnection fetchDestinationMDMAccountIdentifierForAction:completionHandler:]_block_invoke_4
+ ___86-[LNClientConnection fetchDestinationMDMAccountIdentifierForAction:completionHandler:]_block_invoke_5
+ ___86-[LNClientConnection getListenerEndpointForBundleIdentifier:action:completionHandler:]_block_invoke_10
+ ___86-[LNClientConnection getListenerEndpointForBundleIdentifier:action:completionHandler:]_block_invoke_7
+ ___86-[LNClientConnection getListenerEndpointForBundleIdentifier:action:completionHandler:]_block_invoke_8
+ ___86-[LNClientConnection getListenerEndpointForBundleIdentifier:action:completionHandler:]_block_invoke_9
+ ___89-[LNClientConnection performAllEntitiesQueryWithEntityMangledTypeName:completionHandler:]_block_invoke_4
+ ___89-[LNClientConnection performAllEntitiesQueryWithEntityMangledTypeName:completionHandler:]_block_invoke_5
+ ___95-[LNClientConnection performSuggestedEntitiesQueryWithEntityMangledTypeName:completionHandler:]_block_invoke_4
+ ___95-[LNClientConnection performSuggestedEntitiesQueryWithEntityMangledTypeName:completionHandler:]_block_invoke_5
+ ___99-[LNClientConnection fetchStructuredDataWithTypeIdentifier:forEntityIdentifiers:completionHandler:]_block_invoke_4
+ ___99-[LNClientConnection fetchStructuredDataWithTypeIdentifier:forEntityIdentifiers:completionHandler:]_block_invoke_5
+ ____AppIntents_SwiftUILibraryCore_block_invoke
+ ___get_AppIntentsSwiftUIBridgeLoaderClass_block_invoke
+ ___swift_closure_destructor.28Tm
+ ___swift_closure_destructor.3Tm
+ __swift_isClassOrObjCExistentialType
+ _audit_string_AppIntents_SwiftUI
+ _get_AppIntentsSwiftUIBridgeLoaderClass.softClass
+ _objc_retain_x5
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
+ _symbolic S2S_So7LNValueCtSgIeghHnr_
+ _symbolic SS_So7LNValueCt
+ _symbolic SS_So7LNValueCtSg
+ _symbolic SS_So7LNValueCtSgIeAgHr_
+ _symbolic SaySS_So7LNValueCtG
+ _symbolic SaySi_So10LNPropertyCtG
+ _symbolic SaySo7LNValueCGSg
+ _symbolic Say_____G 10AppIntents10ShowReasonO
+ _symbolic Say_____G 10AppIntents10SkipReasonO
+ _symbolic ScCy______pSg_____G 10AppIntents12_IntentValueP s5NeverO
+ _symbolic ScTyyt_____GSg s5NeverO
+ _symbolic ShySSGSg
+ _symbolic Si_So10LNPropertyCt
+ _symbolic Si_So10LNPropertyCtSg
+ _symbolic Si_So10LNPropertyCtSgIeAgHr_
+ _symbolic SixSo7LNValueC______pIeghHynozo_ s5ErrorP
+ _symbolic Sixqd________pIeghHynrzo_ s5ErrorP
+ _symbolic So11LNParameterC
+ _symbolic So20LNQueryEntityOptionsC
+ _symbolic _____ 10AppIntents14TimeoutControl33_3554016BAB8E29824EBCC9835B0D50B3LLV
+ _symbolic _____ 10AppIntents23ResolvedEncodingOptionsV
+ _symbolic _____ 10AppIntents25DeferredPropertyToResolve33_3554016BAB8E29824EBCC9835B0D50B3LLV
+ _symbolic _____ So18CSMailCategoryTypeV
+ _symbolic _____Sg 10AppIntents23ResolvedEncodingOptionsV
+ _symbolic _____Si_So10LNPropertyCtSgIeghHnr_ 10AppIntents25DeferredPropertyToResolve33_3554016BAB8E29824EBCC9835B0D50B3LLV
+ _symbolic ______p 10AppIntents0A23ManagerMetadataProviderP
+ _symbolic ______pSgIeghHr_ 10AppIntents12_IntentValueP
+ _symbolic _____m 10AppIntents11IntentColorV
+ _symbolic _____m 10AppIntents12IntentPromptV
+ _symbolic _____m 10AppIntents14SystemShortcutV
+ _symbolic _____m 10AppIntents17IntentPersonGroupV
+ _symbolic _____m 10AppIntents22_ModelDelegationResultV
+ _symbolic _____m 10AppIntents29_ModelDelegationConfigurationO
+ _symbolic _____ySSSo7LNValueCG s17_NativeDictionaryV
+ _symbolic _____ySS_So7LNValueCtSg_G ScG8IteratorV
+ _symbolic _____ySi_So10LNPropertyCtG s23_ContiguousArrayStorageC
+ _symbolic _____ySi_So10LNPropertyCtSg_G ScG8IteratorV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 10AppIntents14TimeoutControl33_3554016BAB8E29824EBCC9835B0D50B3LLV
+ _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE 10AppIntents14TimeoutControl33_3554016BAB8E29824EBCC9835B0D50B3LLV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10AppIntents25DeferredPropertyToResolve33_3554016BAB8E29824EBCC9835B0D50B3LLV
+ _symbolic _____y_____G_Xx 15Synchronization5MutexVAARi_zrlE 10AppIntents14TimeoutControl33_3554016BAB8E29824EBCC9835B0D50B3LLV
+ _tcc_authorization_preflight
+ _type_layout_string 10AppIntents14TimeoutControl33_3554016BAB8E29824EBCC9835B0D50B3LLV
+ _type_layout_string 10AppIntents25DeferredPropertyToResolve33_3554016BAB8E29824EBCC9835B0D50B3LLV
- GCC_except_table261
- GCC_except_table265
- GCC_except_table267
- GCC_except_table271
- GCC_except_table280
- GCC_except_table283
- GCC_except_table285
- _TCCAccessPreflight
- __OBJC_$_INSTANCE_METHODS_LNAppContext(AppIntents|AppIntents1|AppIntents2|AppIntents3|AppIntents4|AppIntents5|AppIntents6|AppIntents7|AppIntents8|AppIntents9|AppIntents10|AppIntents11|AppIntents12|AppIntents13|AppIntents14|AppIntents15|AppIntents16|AppIntents17|AppIntents18|AppIntents19|AppIntents20|AppIntents21|AppIntents22|AppIntents23|AppIntents24|AppIntents25|AppIntents26|AppIntents27|AppIntents28)
- _get_type_metadata 15Synchronization5MutexVy10AppIntents0C23ManagerMetadataProvider_pG noncopyable
- _swift_retain_x10
- _symbolic $s10AppIntents01_A22IntentBoxRepresentable33_F75533C432556413B266B08AC4DBFBD5LLP
- _symbolic $s10AppIntents01_A37IntentSystemProtocolsBoxRepresentable33_915E4B3A30AB1A412A7F4651338B7520LLP
- _symbolic $s10AppIntents35_FrameworkProvidedSystemIntentCheck33_3DB48B4B18F4759A1FB4FEC0B15761E1LLP
- _symbolic $s10AppIntents39_URLRepresentableEntityBoxRepresentable027_F90955F1A42BC52AFF2F4311D2H4BF76LLP
- _symbolic $s10AppIntents39_URLRepresentableIntentBoxRepresentable33_F75533C432556413B266B08AC4DBFBD5LLP
- _symbolic SS______tSg So15LNQueryMetadataC10AppIntentsE5QueryO
- _symbolic Say______pG 10AppIntents15_AnyIntentValueP
- _symbolic _____ 10AppIntents01_A24IntentSystemProtocolsBox33_915E4B3A30AB1A412A7F4651338B7520LLV
- _symbolic _____ 10AppIntents01_A9IntentBox33_F75533C432556413B266B08AC4DBFBD5LLV
- _symbolic _____ 10AppIntents26_URLRepresentableEntityBox027_F90955F1A42BC52AFF2F4311D2G4BF76LLV
- _symbolic _____ 10AppIntents26_URLRepresentableIntentBox33_F75533C432556413B266B08AC4DBFBD5LLV
- _symbolic _____ 10AppIntents33_FrameworkProvidedSystemIntentBox33_3DB48B4B18F4759A1FB4FEC0B15761E1LLV
- _symbolic _____y______pG 15Synchronization5MutexVAARi_zrlE 10AppIntents0C23ManagerMetadataProviderP
CStrings:
+ "Deferred property resolution timed out%{public}s after %{public}fs"
+ "Failed to resolve deferred property '%{public}s': %{public}s"
+ "TransientAppEntityConvertibleIntentValue.valueType: PrebuiltValueType lookup failed — persistentIdentifier='%{public}s' type=%{public}s"
+ "[%{public}s %{public}s] Skipping side effect confirmation because execution was dispatched programmatically (origin: .remote, source: .app)"
+ "_AppIntentsSwiftUIBridgeLoader"
+ "softlink:r:path:/System/Library/Frameworks/_AppIntents_SwiftUI.framework/_AppIntents_SwiftUI"
+ "withTimeout(_:propertyIdentifier:fallback:operation:)"
- "[%{public}s %{public}s] Skipping side effect confirmation because execution is remote"
```
