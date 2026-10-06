## AutoFillUI

> `/System/Library/PrivateFrameworks/AutoFillUI.framework/AutoFillUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ac20` | `0x2abe4` | **`-0x3c`** |

### Other Changes

```diff

-110.100.0.0.0
+111.0.0.0.0
Functions:
~ +[AFUIAdapter gatherRespondersFromResponder:] : 796 -> 792
~ ___86-[AFUITargetDetectionController textContentTypeForResponder:traits:contentTypesFound:]_block_invoke_2 : 500 -> 496
~ ___58-[AFUIAutoFillPasswordController _loadAccountSuggestions:]_block_invoke : 1152 -> 1148
~ ___62-[AFUIAutoFillPasswordController _loadOneTimeCodeSuggestions:]_block_invoke : 1032 -> 1028
~ +[AFUIAdapter enumerateSignUpSignalsFromButton:block:] : 696 -> 692
~ +[AFUIAdapter enumerateSignUpSignalsFromViewController:block:] : 488 -> 484
~ -[AFUIAutoFillContextAnalyzer getFormConfidenceForGivenHierarchy:imageSize:locale:] : 1160 -> 1152
~ -[AFUITargetDetectionController containsIndicationInText:withAccessibilityHints:] : 540 -> 532
~ ___AFUITextSignalsFoundInKeywordsList_block_invoke : 300 -> 296
~ -[AFUIContactInfo subtitleTextForAutoFillContext:] : 964 -> 956
~ ___73-[AFUIAutoFillCreditCardController _performTextOperationsWithSuggestion:]_block_invoke_3 : 636 -> 632
~ -[AFUIServiceDelegate _tearDownPanelsExceptForSessionUUID:] : 616 -> 608
~ -[AFUIServiceDelegate _sessionForUUID:] : 340 -> 336
~ -[AFUIContactsController _meContactInfosForTextContentType:meContact:] : 3476 -> 3448
~ ___56-[AFUIAutoCompleteMappingController _cachePlistMappings]_block_invoke : 324 -> 320
~ -[AFUIAutoCompleteMappingController heuristicStringsForTextContentTypes:] : 584 -> 576
~ ___93-[AFUIAutoCompleteMappingController heuristicTextContentTypeForHints:textContentTypesToSkip:]_block_invoke : 500 -> 496
~ sub_1d6810b00 -> sub_1d71a0a90 : 1980 -> 2032
```
