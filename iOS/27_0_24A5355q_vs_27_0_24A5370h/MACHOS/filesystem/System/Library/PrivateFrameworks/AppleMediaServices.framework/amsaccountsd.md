## amsaccountsd

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/amsaccountsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25a25c` | `0x25e1fc` | **`+0x3fa0`** |
| `__TEXT.__unwind_info` | `0xa190` | `0xa838` | **`+0x6a8`** |
| `__TEXT.__eh_frame` | `0x12f00` | `0x131b8` | **`+0x2b8`** |
| `__DATA.__bss` | `0x35980` | `0x35bf8` | **`+0x278`** |
| `__TEXT.__const` | `0x23324` | `0x23570` | **`+0x24c`** |
| `__TEXT.__oslogstring` | `0xee81` | `0xf059` | **`+0x1d8`** |
| `__DATA.__objc_const` | `0xc660` | `0xc4c0` | **`-0x1a0`** |
| `__DATA_CONST.__const` | `0x13280` | `0x13410` | **`+0x190`** |
| `__TEXT.__cstring` | `0xc377` | `0xc44c` | **`+0xd5`** |
| `__DATA.__objc_data` | `0x2e28` | `0x2d58` | **`-0xd0`** |
| `__TEXT.__objc_methname` | `0x1114b` | `0x1108b` | **`-0xc0`** |
| `__TEXT.__objc_stubs` | `0xb760` | `0xb820` | **`+0xc0`** |
| `__DATA.__data` | `0xbea8` | `0xbe08` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x5e8c` | `0x5dfc` | **`-0x90`** |
| `__DATA_CONST.__cfstring` | `0x4a60` | `0x4ac0` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x7ad4` | `0x7b34` | **`+0x60`** |
| `__DATA_CONST.__auth_ptr` | `0x2cd8` | `0x2c80` | **`-0x58`** |
| `__TEXT.__objc_classname` | `0x19c5` | `0x196f` | **`-0x56`** |
| `__TEXT.__swift5_fieldmd` | `0x7574` | `0x75c4` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x8b0` | `0x8f0` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x41c` | `0x444` | **`+0x28`** |
| `__DATA_CONST.__objc_protolist` | `0x280` | `0x260` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0xc00` | `0xc1c` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0xa30` | `0xa48` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0xfc0` | `0xfd8` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x348` | `0x360` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x190` | `0x17c` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0x1b24` | `0x1b38` | **`+0x14`** |
| `__DATA_CONST.__objc_protorefs` | `0x60` | `0x50` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x4590` | `0x4580` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x3a4` | `0x39c` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x3e48` | `0x3e50` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x22d8` | `0x22d0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x13c0` | `0x13c8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x408` | `0x400` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x4bfa` | `0x4bfb` | **`+0x1`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-10.0.40.4.1
+10.0.45.0.0

-  - /System/Library/Frameworks/CryptoTokenKit.framework/CryptoTokenKit

-  - /System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication

-  - /System/Library/Frameworks/UserNotifications.framework/UserNotifications

-  - /System/Library/PrivateFrameworks/BaseBoard.framework/BaseBoard
-  - /System/Library/PrivateFrameworks/CryptoKitCBridging.framework/CryptoKitCBridging

-  - /System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices

-  Functions: 15882
+  Functions: 15962

-  CStrings:  5472
+  CStrings:  5469
Symbols:
+ _$s18AppleMediaServices23SimpleProfileUpdateTaskV14sponsorAccount18authenticateResult12accountStoreACyxq_Gq__So015AMSAuthenticateK0CSgxtcfC
+ _$sSo9ACAccountC18AppleMediaServicesE8isActive3forSbSo010AMSAccountC4Typea_tF
+ _OBJC_CLASS_$_AMSLocalAuthTokenUpdateOptions
- _$s18AppleMediaServices23SimpleProfileUpdateTaskV14sponsorAccount18authenticateResult12accountStoreACyxq_Gq__So015AMSAuthenticateK0CxtcfC
- _$ss6HasherV8finalizeSiyF
- _$ss6HasherVABycfC
CStrings:
+ "%{public}@: [%{public}@] Error running silent-auth lazy data sync for accountID = %{public}@ error = %{public}@"
+ "%{public}@: [%{public}@] Passcode confirmation dialog accepted"
+ "%{public}@: [%{public}@] Passcode confirmation dialog declined"
+ "%{public}@: [%{public}@]Token update failed for no Biometrics, error: %{public}@"
+ "%{public}@: [%{public}@]Token update failed for no Passcode, error: %{public}@"
+ "%{public}@All identifier attempts failed for account. error = %{public}@"
+ "%{public}@Identifier resolution failed for account. error = %{public}@"
+ "%{public}@No identifiers and no errors produced for account. error = %{public}@"
+ "%{public}@Retry token update request with state marker = %ld"
+ "@\"AMSLocalAuthTokenUpdateOptions\""
+ "@40@0:8q16^@24^@32"
+ "AMSDBiometricsTokenUpdateTask post-update authenticate"
+ "External sync rejected reason: "
+ "Failed to clean up profiles for inactive sponsor:"
+ "PASSCODE_AUTHENTICATION_DIALOG_OPT_IN"
+ "PASSCODE_AUTHENTICATION_DIALOG_OPT_OUT"
+ "PASSCODE_AUTHENTICATION_DIALOG_TITLE"
+ "PasscodePurchase"
+ "Performing loud auth sync (objc) for account:"
+ "T@\"AMSLocalAuthTokenUpdateOptions\",&,N,V_updateOptions"
+ "User declined passcode dialog"
+ "_buildRequestBodyWithPrimaryCerts:extendedCerts:"
+ "_buildRequestWithBody:bag:"
+ "_confirmationBOPDialogRequestForBiometricsType:acceptActionIdentifier:declineActionIdentifier:"
+ "_confirmationTIDDialogRequestForBiometricsType:clientInfo:acceptActionIdentifier:declineActionIdentifier:"
+ "_performBOPProtocolUpdate"
+ "_performTIDProtocolUpdate"
+ "_presentBOPConfirmationDialog"
+ "_presentBOPConfirmationDialogWithCurrentPasscodeState:"
+ "_presentTIDConfirmationDialog"
+ "_presentTIDConfirmationDialogWithCurrentBiometricsState:"
+ "_runUpdateRequestWithPrimaryCerts:extendedCerts:"
+ "_updateOptions"
+ "_updateTokensWithCurrentStateMarker:retryCount:"
+ "ams_iTunesAccounts"
+ "isPasscodePurchaseEnabled"
+ "loudAuthSync"
+ "loudAuthSyncFor:completionHandler:"
+ "loudAuthSyncForAccountID:reply:"
+ "performLocalAuthTokenUpdateWithAccount:clientInfo:additionalDialogMetrics:accountSaveOptions:updateOptions:completion:"
+ "setDevicePasscodeState:"
+ "setUpdateOptions:"
+ "updateOptions"
+ "usesBOPTokenProtocol"
+ "v32@0:8@\"AMSAccountIdentity\"16@?<v@?B@\"NSError\">24"
+ "v64@0:8@\"ACAccount\"16@\"AMSProcessInfo\"24@\"NSDictionary\"32q40@\"AMSLocalAuthTokenUpdateOptions\"48@?<v@?B@\"NSError\">56"
+ "v64@0:8@16@24@32q40@48@?56"
- "%{public}@: [%{public}@] Error running account data sync for accountID = %{public}@"
- "%{public}@: [%{public}@]Biometrics Update Failed with error: %{public}@"
- "%{public}@Retry token update request biometrics state = %ld"
- "<LocalAuthTokenUpdateTaskConfiguration protocol="
- "@24@0:8@\"NSCoder\"16"
- "@32@0:8Q16q24"
- "@40@0:8Q16@24@32"
- "AMSLocalAuthTokenUpdateTaskConfiguration"
- "External sync (objc) reason: "
- "NSCoding"
- "NSSecureCoding"
- "T@\"NSString\",N,R"
- "TB,N,GisUserInitiated,V_userInitiated"
- "TB,N,R"
- "TB,N,V_shouldGenerateKeysOnly"
- "TB,N,V_shouldRequestConfirmation"
- "TB,R"
- "Tq,N,R"
- "Tq,N,R,VtokenProtocol"
- "Tq,N,R,Vtrigger"
- "_buildRequestBodyWithStyle:primaryCerts:extendedCerts:"
- "_buildRequestWithBody:bag:style:"
- "_confirmationDialogRequestForBiometricsType:clientInfo:acceptActionIdentifier:declineActionIdentifier:"
- "_presentConfirmationDialog"
- "_presentConfirmationDialogWithCurrentBiometricsState:"
- "_runUpdateRequestWithStyle:primaryCerts:extendedCerts:"
- "_shouldGenerateKeysOnly"
- "_shouldRequestConfirmation"
- "_updateTokensWithCurrentBiometricsState:retryCount:"
- "_userInitiated"
- "biometricState"
- "biometricsButton"
- "containsValueForKey:"
- "decodeIntegerForKey:"
- "encodeInteger:forKey:"
- "encodeWithCoder:"
- "extendedAttestation"
- "initWithAttestationStyle:trigger:"
- "initWithTokenProtocol:trigger:"
- "isUserInitiated"
- "performBiometricTokenUpdateWithAccount:clientInfo:additionalDialogMetrics:shouldGenerateKeysOnly:shouldRequestConfirmation:userInitiated:accountSaveOptions:protocolConfiguration:completion:"
- "setShouldGenerateKeysOnly:"
- "setShouldRequestConfirmation:"
- "setUserInitiated:"
- "supportsSecureCoding"
- "touchIdAttestation"
- "trigger"
- "v24@0:8@\"NSCoder\"16"
- "v76@0:8@\"ACAccount\"16@\"AMSProcessInfo\"24@\"NSDictionary\"32B40B44B48q52@\"AMSLocalAuthTokenUpdateTaskConfiguration\"60@?<v@?B@\"NSError\">68"
- "v76@0:8@16@24@32B40B44B48q52@60@?68"
```
