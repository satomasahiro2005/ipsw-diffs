## WebUI

> `/System/Library/PrivateFrameworks/WebUI.framework/WebUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33094` | `0x33438` | **`+0x3a4`** |
| `__DATA_CONST.__const` | `0xfc0` | `0xfe8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x1f68` | `0x1f88` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x5a0` | `0x5b0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xe30` | `0xe40` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x118` | `0x11c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-625.1.24.10.1
+625.1.29.10.3

-  Functions: 994
-  Symbols:   1331
+  Functions: 999
+  Symbols:   1338
Symbols:
+ GCC_except_table109
+ GCC_except_table113
+ GCC_except_table127
+ GCC_except_table148
+ GCC_except_table151
+ GCC_except_table166
+ GCC_except_table167
+ GCC_except_table168
+ GCC_except_table189
+ GCC_except_table20
+ _OBJC_IVAR_$_WBUFormDataController._passwordSavingManagerLock
+ ___118-[WBUFormDataController _continueUpdatingCredentialsForForm:inWebView:frame:newUsername:newGeneratedPassword:context:]_block_invoke_3
+ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke_9
+ ___194-[WBUFormDataController _webView:saveUsernameAndPasswordForURL:formType:formUniqueID:inFrame:username:password:isGeneratedPassword:confirmOverwritingCurrentPassword:inContext:submissionHandler:]_block_invoke_2
+ ___262-[WBUGeneratedPasswordCredentialUpdater updateCredentialWithNewUsername:newGeneratedPassword:lastGeneratedPassword:credentialURL:protectionSpace:savedAccountContext:shouldSaveNewCredential:shouldSaveExistingCredential:associatedDomainsManager:completionHandler:]_block_invoke_6
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
- GCC_except_table108
- GCC_except_table112
- GCC_except_table125
- GCC_except_table146
- GCC_except_table149
- GCC_except_table163
- GCC_except_table164
- GCC_except_table165
- GCC_except_table185
Functions:
~ -[WBUFormDataController passwordSavingManager] : 268 -> 324
~ ___194-[WBUFormDataController _webView:saveUsernameAndPasswordForURL:formType:formUniqueID:inFrame:username:password:isGeneratedPassword:confirmOverwritingCurrentPassword:inContext:submissionHandler:]_block_invoke : 88 -> 184
+ ___194-[WBUFormDataController _webView:saveUsernameAndPasswordForURL:formType:formUniqueID:inFrame:username:password:isGeneratedPassword:confirmOverwritingCurrentPassword:inContext:submissionHandler:]_block_invoke_2
~ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke : 88 -> 184
~ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke_2 : 120 -> 88
~ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke_3 : 4 -> 120
~ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke_4 : 232 -> 4
~ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke_5 : 860 -> 232
~ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke_6 : 620 -> 860
~ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke_7 : 8 -> 620
~ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke_8 : 180 -> 8
+ ___145-[WBUFormDataController _saveUser:password:isGeneratedPassword:forURL:inContext:formType:formUniqueID:promptingPolicy:webView:completionHandler:]_block_invoke_9
~ ___144-[WBUFormDataController _webView:saveCredentialsForURL:formSubmission:formWithMetadata:fromFrame:username:password:inContext:submissionHandler:]_block_invoke : 96 -> 192
+ ___144-[WBUFormDataController _webView:saveCredentialsForURL:formSubmission:formWithMetadata:fromFrame:username:password:inContext:submissionHandler:]_block_invoke_2
~ ___118-[WBUFormDataController _continueUpdatingCredentialsForForm:inWebView:frame:newUsername:newGeneratedPassword:context:]_block_invoke : 20 -> 156
~ ___118-[WBUFormDataController _continueUpdatingCredentialsForForm:inWebView:frame:newUsername:newGeneratedPassword:context:]_block_invoke_2 : 120 -> 20
+ ___118-[WBUFormDataController _continueUpdatingCredentialsForForm:inWebView:frame:newUsername:newGeneratedPassword:context:]_block_invoke_3
~ ___262-[WBUGeneratedPasswordCredentialUpdater updateCredentialWithNewUsername:newGeneratedPassword:lastGeneratedPassword:credentialURL:protectionSpace:savedAccountContext:shouldSaveNewCredential:shouldSaveExistingCredential:associatedDomainsManager:completionHandler:]_block_invoke_5 : 128 -> 204
+ ___262-[WBUGeneratedPasswordCredentialUpdater updateCredentialWithNewUsername:newGeneratedPassword:lastGeneratedPassword:credentialURL:protectionSpace:savedAccountContext:shouldSaveNewCredential:shouldSaveExistingCredential:associatedDomainsManager:completionHandler:]_block_invoke_6
```
