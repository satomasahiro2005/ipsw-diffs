## WebUI

> `/System/Library/PrivateFrameworks/WebUI.framework/WebUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x58d` | `0x5ad` | **`+0x20`** |
| `__TEXT.__text` | `0x33028` | `0x33048` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x958` | `0x960` | **`+0x8`** |

### Other Changes

```diff

-625.1.18.10.4
+625.1.20.10.3

-  Symbols:   1328
-  CStrings:  184
+  Symbols:   1329
+  CStrings:  185
Symbols:
+ _WBSOSLogHistory
Functions:
~ -[WebUIAlert setIdentities:] : 380 -> 376
~ ___38-[_WBUDynamicMeCard performWhenReady:]_block_invoke_4 : 296 -> 292
~ -[WBUFormDataController savedAccountFromMatches:completingPartialUserInLoginForm:] : 600 -> 592
~ -[WBUFormDataController _continueSaveUnsubmittedGeneratedPasswordInFrame:form:context:closingWebView:username:password:] : 1112 -> 1108
~ -[WBUFormDataController _credentialMatchesEligibleForUpdateForURL:username:oldPassword:] : 700 -> 696
~ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke_5 : 868 -> 860
~ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke_6 : 624 -> 620
~ ___161-[WBUFormDataController _handleSavingAutoFillCredentialsAfterManuallyEnteringUsername:newPassword:atURL:inContext:isGeneratedPassword:webView:completionHandler:]_block_invoke_4 : 604 -> 596
~ ___207-[WBUFormDataController _relatedCredentialMatchesToUpdateForUser:protectionSpace:oldSavedAccount:matchesForCurrentHost:matchesForAssociatedDomains:haveExistingCredentialWithSameUsernameAndDifferentPassword:]_block_invoke : 632 -> 624
~ ___144-[WBUFormDataController _webView:saveCredentialsForURL:formSubmission:formWithMetadata:fromFrame:username:password:inContext:submissionHandler:]_block_invoke.436 : 356 -> 352
~ _getUserAndPasswordAreAutoFilledInForm : 424 -> 420
~ ___144-[WBUFormDataController _webView:saveCredentialsForURL:formSubmission:formWithMetadata:fromFrame:username:password:inContext:submissionHandler:]_block_invoke_5 : 408 -> 404
~ -[WBUHistory initWithDatabaseID:profileIdentifier:] : 212 -> 272
~ sub_20ffaf03c -> sub_217524038 : 260 -> 280
~ sub_20ffb8e24 -> sub_21752de34 : 968 -> 972
~ sub_20ffb9520 -> sub_21752e534 : 764 -> 760
~ sub_20ffbbb20 -> sub_217530b30 : 172 -> 176
~ sub_20ffbc700 -> sub_217531714 : 280 -> 276
~ sub_20ffbdf64 -> sub_217532f74 : 392 -> 384
~ sub_20ffc15dc -> sub_2175365e4 : 1060 -> 1056
~ sub_20ffc35b0 -> sub_2175385b4 : 368 -> 372
~ sub_20ffc3ddc -> sub_217538de4 : 248 -> 252
~ sub_20ffc406c -> sub_217539078 : 396 -> 400
~ sub_20ffc4754 -> sub_217539764 : 164 -> 168
~ sub_20ffc49e4 -> sub_2175399f8 : 260 -> 264
~ ___swift_closure_destructor.151Tm : 124 -> 132
CStrings:
+ "Endless history enabled"
```
