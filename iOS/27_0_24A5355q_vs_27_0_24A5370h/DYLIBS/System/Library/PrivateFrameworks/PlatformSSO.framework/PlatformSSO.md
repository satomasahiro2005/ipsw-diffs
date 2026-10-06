## PlatformSSO

> `/System/Library/PrivateFrameworks/PlatformSSO.framework/PlatformSSO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59b34` | `0x5ac90` | **`+0x115c`** |
| `__TEXT.__oslogstring` | `0x2411` | `0x2531` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x348c` | `0x3534` | **`+0xa8`** |
| `__AUTH_CONST.__objc_const` | `0x8590` | `0x8608` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x2330` | `0x2398` | **`+0x68`** |
| `__TEXT.__gcc_except_tab` | `0x1210` | `0x126c` | **`+0x5c`** |
| `__TEXT.__unwind_info` | `0x1548` | `0x1578` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xf38` | `0xf60` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x418` | `0x438` | **`+0x20`** |
| `__TEXT.__const` | `0x312` | `0x322` | **`+0x10`** |
| `__TEXT.__cstring` | `0x8246` | `0x8256` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x388` | `0x38c` | **`+0x4`** |

### Other Changes

```diff

-635.0.0.0.0
+643.0.12.0.0

-  Functions: 2108
-  Symbols:   2627
-  CStrings:  1031
+  Functions: 2126
+  Symbols:   2648
+  CStrings:  1034
Symbols:
+ -[POAgentAuthenticationProcess _doLoginWithPasswordContext:tokenId:authorizationContextScope:]
+ -[POAgentAuthenticationProcess clearPlatformSSONotifications]
+ -[POAgentAuthenticationProcess currentAuthorizationContextScope]
+ -[POAgentAuthenticationProcess performLoginForCurrentUserWithPasswordContext:tokenId:forceLogin:authorizationContextScope:]
+ -[POAgentAuthenticationProcess setCurrentAuthorizationContextScope:]
+ -[POAgentProcess performOpenIDLogin:loginUserName:callbackResponse:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]
+ -[POAgentProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]
+ -[POAuthPluginProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:additionalScopes:]
+ -[POAuthPluginProcess performPasswordLogin:passwordContext:updateLocalAccountPassword:additionalScopes:]
+ -[PODaemonConnection updatePasswordHint:forUsername:completion:]
+ -[POServiceConnection performOpenIDLogin:loginUserName:callbackResponse:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]
+ -[POServiceConnection performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]
+ -[POServiceConnection retrieveOpenIDAuthorizationRequestForLoginUserName:additionalScopes:completion:]
+ -[POServiceConnection verifyOpenIDUser:loginUserName:callbackResponse:passwordContext:additionalScopes:completion:]
+ -[POServiceConnection verifyUserAccount:passwordContext:smartCardContext:tokenId:additionalScopes:completion:]
+ GCC_except_table113
+ GCC_except_table117
+ GCC_except_table121
+ GCC_except_table127
+ GCC_except_table176
+ GCC_except_table72
+ GCC_except_table99
+ _OBJC_IVAR_$_POAgentAuthenticationProcess._currentAuthorizationContextScope
+ ___102-[POServiceConnection retrieveOpenIDAuthorizationRequestForLoginUserName:additionalScopes:completion:]_block_invoke
+ ___110-[POServiceConnection verifyUserAccount:passwordContext:smartCardContext:tokenId:additionalScopes:completion:]_block_invoke
+ ___115-[POServiceConnection verifyOpenIDUser:loginUserName:callbackResponse:passwordContext:additionalScopes:completion:]_block_invoke
+ ___118-[POAuthPluginProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:additionalScopes:]_block_invoke
+ ___118-[POAuthPluginProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:additionalScopes:]_block_invoke_2
+ ___123-[POAgentAuthenticationProcess performLoginForCurrentUserWithPasswordContext:tokenId:forceLogin:authorizationContextScope:]_block_invoke
+ ___124-[POAgentProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]_block_invoke
+ ___129-[POServiceConnection performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]_block_invoke
+ ___139-[POAgentProcess performOpenIDLogin:loginUserName:callbackResponse:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]_block_invoke
+ ___139-[POAgentProcess performOpenIDLogin:loginUserName:callbackResponse:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]_block_invoke_2
+ ___144-[POServiceConnection performOpenIDLogin:loginUserName:callbackResponse:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]_block_invoke
+ ___64-[PODaemonConnection updatePasswordHint:forUsername:completion:]_block_invoke
+ ___94-[POAgentAuthenticationProcess _doLoginWithPasswordContext:tokenId:authorizationContextScope:]_block_invoke
+ ___94-[POAgentAuthenticationProcess _doLoginWithPasswordContext:tokenId:authorizationContextScope:]_block_invoke_2
+ ___94-[POAgentAuthenticationProcess _doLoginWithPasswordContext:tokenId:authorizationContextScope:]_block_invoke_3
+ ___block_descriptor_49_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_57_e8_32s40s48s_e20_v24?0Q8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_57_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_81_e8_32s40s48s56s64s72r_e5_v8?0ls32l8s40l8s48l8s56l8s64l8r72l8
+ _kPOAuthorizationScopeAuthPrompt
+ _kPOAuthorizationScopeLogin
+ _kPOAuthorizationScopeRefresh
+ _kPOAuthorizationScopeUnlock
- -[POAgentAuthenticationProcess _doLoginWithPasswordContext:tokenId:]
- GCC_except_table111
- GCC_except_table115
- GCC_except_table119
- GCC_except_table125
- GCC_except_table173
- GCC_except_table54
- GCC_except_table71
- GCC_except_table97
- ___101-[POAuthPluginProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:]_block_invoke
- ___101-[POAuthPluginProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:]_block_invoke_2
- ___107-[POAgentProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:completion:]_block_invoke
- ___108-[POAgentAuthenticationProcess userNotificationCenter:didReceiveNotificationResponse:withCompletionHandler:]_block_invoke_4
- ___108-[POAgentAuthenticationProcess userNotificationCenter:didReceiveNotificationResponse:withCompletionHandler:]_block_invoke_5
- ___122-[POAgentProcess performOpenIDLogin:loginUserName:callbackResponse:passwordContext:updateLocalAccountPassword:completion:]_block_invoke
- ___122-[POAgentProcess performOpenIDLogin:loginUserName:callbackResponse:passwordContext:updateLocalAccountPassword:completion:]_block_invoke_2
- ___68-[POAgentAuthenticationProcess _doLoginWithPasswordContext:tokenId:]_block_invoke
- ___68-[POAgentAuthenticationProcess _doLoginWithPasswordContext:tokenId:]_block_invoke_2
- ___68-[POAgentAuthenticationProcess _doLoginWithPasswordContext:tokenId:]_block_invoke_3
- ___87-[POAuthPluginProcess performPasswordLogin:passwordContext:updateLocalAccountPassword:]_block_invoke
- ___87-[POAuthPluginProcess performPasswordLogin:passwordContext:updateLocalAccountPassword:]_block_invoke_2
- ___97-[POAgentAuthenticationProcess performLoginForCurrentUserWithPasswordContext:tokenId:forceLogin:]_block_invoke
- ___block_descriptor_56_e8_32s40s48s_e20_v24?0Q8"NSError"16ls32l8s40l8s48l8
- ___block_descriptor_65_e8_32s40s48s56r_e5_v8?0ls32l8s40l8s48l8r56l8
- ___block_descriptor_73_e8_32s40s48s56s64r_e5_v8?0ls32l8s40l8s48l8s56l8r64l8
CStrings:
+ "%s authorizationContextScope = %{public}@ on %@"
+ "%s userName = %{public}@, additionalScopes = %{public}@ on %@"
+ "%s userName = %{public}@, passwordContext = %{public}@, updateLocalAccountPassword = %{public}@, additionalScopes = %{public}@ on %@"
+ "-[POAgentAuthenticationProcess _doLoginWithPasswordContext:tokenId:authorizationContextScope:]"
+ "-[POAgentAuthenticationProcess performLoginForCurrentUserWithPasswordContext:tokenId:forceLogin:authorizationContextScope:]"
+ "-[POAgentProcess performOpenIDLogin:loginUserName:callbackResponse:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]"
+ "-[POAgentProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:additionalScopes:completion:]"
+ "-[POAuthPluginProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:additionalScopes:]"
+ "Authentication permanent failure for key-based user - deferring repair"
+ "Skipping registration re-prompt on dismiss; PSSO is no longer active"
+ "\xf0\xc1"
- "%s userName = %{public}@, passwordContext = %{public}@, updateLocalAccountPassword = %{public}@ on %@"
- "-[POAgentAuthenticationProcess _doLoginWithPasswordContext:tokenId:]"
- "-[POAgentAuthenticationProcess performLoginForCurrentUserWithPasswordContext:tokenId:forceLogin:]"
- "-[POAgentProcess performOpenIDLogin:loginUserName:callbackResponse:passwordContext:updateLocalAccountPassword:completion:]"
- "-[POAgentProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:completion:]"
- "-[POAuthPluginProcess performPasswordLogin:loginUserName:passwordContext:updateLocalAccountPassword:]"
- "-[POAuthPluginProcess performPasswordLogin:passwordContext:updateLocalAccountPassword:]"
- "\xf0\xb1"
```
