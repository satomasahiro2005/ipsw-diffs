## AppleAccount

> `/System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a99cc` | `0x1aa0e4` | **`+0x718`** |
| `__AUTH_CONST.__objc_const` | `0x26ad0` | `0x26c18` | **`+0x148`** |
| `__TEXT.__oslogstring` | `0x1397d` | `0x13aad` | **`+0x130`** |
| `__AUTH_CONST.__cfstring` | `0xd640` | `0xd760` | **`+0x120`** |
| `__TEXT.__cstring` | `0x11472` | `0x11532` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x1130` | `0x11d0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0xb5ec` | `0xb5a4` | **`-0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x52a0` | `0x5260` | **`-0x40`** |
| `__DATA.__objc_ivar` | `0xbd4` | `0xbf4` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x3f90` | `0x3fb0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1150` | `0x1168` | **`+0x18`** |
| `__DATA.__bss` | `0x176c0` | `0x176d0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x8a8` | `0x8b8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x588` | `0x590` | **`+0x8`** |

### Other Changes

```diff

-1067.0.0.0.0
+1069.125.4.0.0

-  Functions: 9165
-  Symbols:   10009
-  CStrings:  3735
+  Functions: 9163
+  Symbols:   10033
+  CStrings:  3750
Symbols:
+ +[AACloudKitDevicesListRequest urlBagKey]
+ +[AACloudKitMigrationStateRequest urlBagKey]
+ +[AACloudKitStartMigrationRequest urlBagKey]
+ +[AAFMIPAuthenticateRequest urlBagKey]
+ +[AAFamilyDetailsRequest urlBagKey]
+ +[AAFamilyEligibilityRequest urlBagKey]
+ +[AAFeatureFlags isAAAFoundationBackoffEnabled]
+ +[AAGenericTermsUIRequest urlBagKey]
+ +[AALoginDelegatesRequest urlBagKey]
+ +[AAMyPhotoRequest urlBagKey]
+ +[AAPasswordSecurityUIRequest urlBagKey]
+ +[AAPaymentSummaryRequest urlBagKey]
+ +[AAPaymentUIRequest urlBagKey]
+ +[AAPersonalInfoUIRequest urlBagKey]
+ +[AAPreferences isForceServerBackoffEnabled]
+ +[AAPreferences setForceServerBackoffEnabled:]
+ +[AARequest urlBagKey]
+ +[AASecondaryAuthenticationRequest urlBagKey]
+ +[AAServerBackoffHelper sharedHelper]
+ +[AAUpdateAccountUIRequest urlBagKey]
+ +[AAUpdateMyPhotoRequest urlBagKey]
+ +[AAUpdateNameRequest urlBagKey]
+ +[ATVHighSecurityAccountDeviceList urlBagKey]
+ +[ATVHighSecurityAccountSendCode urlBagKey]
+ +[ATVHighSecurityAccountVerifyCode urlBagKey]
+ +[_AAURLSessionOperation operationWithURLBagKey:completion:]
+ -[AACustodianUpdateRequestContext isSyncAction]
+ -[AACustodianUpdateRequestContext setIsSyncAction:]
+ -[AADataclassManager _appStateForDataclass:bundleID:]
+ -[AALocalContactInfo initWithHandle:contact:source:]
+ -[AALocalContactInfo intelligenceScore]
+ -[AALocalContactInfo setIntelligenceScore:]
+ -[AALocalContactInfo setSource:]
+ -[AALocalContactInfo source]
+ -[AALoginDelegatesRequest initWithAccount:proxiedAppBundleID:parameters:]
+ -[AARequest clientBundleID]
+ -[AARequest proxiedAppBundleID]
+ -[AARequest setClientBundleID:]
+ -[AARequest setProxiedAppBundleID:]
+ -[AAServerBackoffHelper .cxx_destruct]
+ -[AAServerBackoffHelper appendBackoffHeadersToRequest:]
+ -[AAServerBackoffHelper initWithBackoffController:]
+ -[AAServerBackoffHelper init]
+ -[AAServerBackoffHelper processBackoffInfoFromHeaderFields:]
+ -[AAServerBackoffHelper shouldBackoffRequest:urlBagKey:]
+ -[AAURLConfiguration urlStringForKey:]
+ -[AAURLSession _enqueueRequest:withFlowID:urlBagKey:completion:]
+ -[AAURLSession _sessionQueue_enqueueTask:urlBagKey:completion:]
+ -[AAURLSession dataTaskWithRequest:withFlowID:urlBagKey:completion:]
+ -[AAURLSession serverBackoffHelper]
+ -[AAURLSession setServerBackoffHelper:]
+ -[_AAServerBackoffThrottledTask cancel]
+ -[_AAServerBackoffThrottledTask copyWithZone:]
+ -[_AAServerBackoffThrottledTask resume]
+ -[_AAServerBackoffThrottledTask suspend]
+ -[_AAURLSessionOperation initWithURLBagKey:completion:]
+ -[_AAURLSessionOperation urlBagKey]
+ GCC_except_table119
+ _AAServerBackoffClientBundleIDHeaderKey
+ _AAServerBackoffForceHeaderKey
+ _AAServerBackoffProxiedAppBundleIDHeaderKey
+ _OBJC_CLASS_$_AAFServerBackoffController
+ _OBJC_CLASS_$_AAServerBackoffHelper
+ _OBJC_CLASS_$__AAServerBackoffThrottledTask
+ _OBJC_IVAR_$_AACustodianUpdateRequestContext._isSyncAction
+ _OBJC_IVAR_$_AALocalContactInfo._intelligenceScore
+ _OBJC_IVAR_$_AALocalContactInfo._source
+ _OBJC_IVAR_$_AARequest._clientBundleID
+ _OBJC_IVAR_$_AARequest._proxiedAppBundleID
+ _OBJC_IVAR_$_AAServerBackoffHelper._backoffController
+ _OBJC_IVAR_$_AAURLSession._serverBackoffHelper
+ _OBJC_IVAR_$__AAURLSessionOperation._urlBagKey
+ _OBJC_METACLASS_$_AAServerBackoffHelper
+ _OBJC_METACLASS_$__AAServerBackoffThrottledTask
+ __OBJC_$_CLASS_METHODS_AAPasswordSecurityUIRequest
+ __OBJC_$_CLASS_METHODS_AAPaymentUIRequest
+ __OBJC_$_CLASS_METHODS_AAPersonalInfoUIRequest
+ __OBJC_$_CLASS_METHODS_AAServerBackoffHelper
+ __OBJC_$_CLASS_METHODS_AAUpdateAccountUIRequest
+ __OBJC_$_CLASS_METHODS_AAUpdateMyPhotoRequest
+ __OBJC_$_INSTANCE_METHODS_AAServerBackoffHelper
+ __OBJC_$_INSTANCE_METHODS__AAServerBackoffThrottledTask
+ __OBJC_$_INSTANCE_VARIABLES_AAServerBackoffHelper
+ __OBJC_$_PROP_LIST__AAServerBackoffThrottledTask
+ __OBJC_CLASS_PROTOCOLS_$__AAServerBackoffThrottledTask
+ __OBJC_CLASS_RO_$_AAServerBackoffHelper
+ __OBJC_CLASS_RO_$__AAServerBackoffThrottledTask
+ __OBJC_METACLASS_RO_$_AAServerBackoffHelper
+ __OBJC_METACLASS_RO_$__AAServerBackoffThrottledTask
+ ___37+[AAServerBackoffHelper sharedHelper]_block_invoke
+ ___64-[AAURLSession _enqueueRequest:withFlowID:urlBagKey:completion:]_block_invoke
+ ___64-[AAURLSession _enqueueRequest:withFlowID:urlBagKey:completion:]_block_invoke_2
+ _kAAProtocolPrefForceServerBackoffKey
+ _sharedHelper.onceToken
+ _sharedHelper.sharedHelper
- +[_AAURLSessionOperation operationWithCompletion:]
- -[AACloudKitDevicesListRequest urlString]
- -[AACloudKitMigrationStateRequest urlString]
- -[AACloudKitStartMigrationRequest urlString]
- -[AAFMIPAuthenticateRequest urlString]
- -[AAFamilyDetailsRequest urlString]
- -[AAFamilyEligibilityRequest urlString]
- -[AAGenericTermsUIRequest urlString]
- -[AALoginDelegatesRequest urlString]
- -[AAMyPhotoRequest urlString]
- -[AAPasswordSecurityUIRequest urlString]
- -[AAPaymentSummaryRequest urlString]
- -[AAPaymentUIRequest urlString]
- -[AAPersonalInfoUIRequest urlString]
- -[AASecondaryAuthenticationRequest urlString]
- -[AAURLConfiguration(Deprecated) _urlStringForKey:]
- -[AAURLConfiguration(Deprecated) acceptFamilyInviteV2URL]
- -[AAURLConfiguration(Deprecated) accountCreationUIURL]
- -[AAURLConfiguration(Deprecated) accountCreationURL]
- -[AAURLConfiguration(Deprecated) accountManagementUIURL]
- -[AAURLConfiguration(Deprecated) addFamilyMemberUIURL]
- -[AAURLConfiguration(Deprecated) checkiCloudMembershipURL]
- -[AAURLConfiguration(Deprecated) childAccountCreationUIURL]
- -[AAURLConfiguration(Deprecated) cloudKitDevicesListURL]
- -[AAURLConfiguration(Deprecated) cloudKitMigrationStateURL]
- -[AAURLConfiguration(Deprecated) cloudKitStartMigrationURL]
- -[AAURLConfiguration(Deprecated) deviceListURL]
- -[AAURLConfiguration(Deprecated) devicesUIURL]
- -[AAURLConfiguration(Deprecated) emailLookupURL]
- -[AAURLConfiguration(Deprecated) familyEligibilityURL]
- -[AAURLConfiguration(Deprecated) familyInviteSentV2URL]
- -[AAURLConfiguration(Deprecated) familyUIURL]
- -[AAURLConfiguration(Deprecated) fetchFamilyInviteV2URL]
- -[AAURLConfiguration(Deprecated) fmipAuthenticate]
- -[AAURLConfiguration(Deprecated) getFamilyDetailsURL]
- -[AAURLConfiguration(Deprecated) getMyPhotoURL]
- -[AAURLConfiguration(Deprecated) grandslamURL]
- -[AAURLConfiguration(Deprecated) initiateFamilyV2URL]
- -[AAURLConfiguration(Deprecated) loginDelegatesURL]
- -[AAURLConfiguration(Deprecated) mobileMeOfferAlertURL]
- -[AAURLConfiguration(Deprecated) passwordSecurityUIURL]
- -[AAURLConfiguration(Deprecated) paymentInfoUIURL]
- -[AAURLConfiguration(Deprecated) paymentSummaryURL]
- -[AAURLConfiguration(Deprecated) pendingFamilyInvitesUIURL]
- -[AAURLConfiguration(Deprecated) personalInfoUIURL]
- -[AAURLConfiguration(Deprecated) registerURL]
- -[AAURLConfiguration(Deprecated) secondaryAuthenticationURL]
- -[AAURLConfiguration(Deprecated) sendCodeURL]
- -[AAURLConfiguration(Deprecated) startFamilyInviteV2URL]
- -[AAURLConfiguration(Deprecated) updateAccountUIURL]
- -[AAURLConfiguration(Deprecated) updateAccountURL]
- -[AAURLConfiguration(Deprecated) updateNameURL]
- -[AAURLConfiguration(Deprecated) validateURL]
- -[AAURLConfiguration(Deprecated) verifyCodeURL]
- -[AAURLSession _enqueueRequest:withFlowID:completion:]
- -[AAURLSession _sessionQueue_enqueueTask:completion:]
- -[AAUpdateAccountUIRequest urlString]
- -[AAUpdateMyPhotoRequest urlString]
- -[AAUpdateNameRequest urlString]
- -[ATVHighSecurityAccountDeviceList urlString]
- -[ATVHighSecurityAccountSendCode urlString]
- -[ATVHighSecurityAccountVerifyCode urlString]
- -[_AAURLSessionOperation initWithCompletion:]
- GCC_except_table113
- GCC_except_table32
- __OBJC_$_INSTANCE_METHODS_AACloudKitDevicesListRequest
- __OBJC_$_INSTANCE_METHODS_AACloudKitMigrationStateRequest
- __OBJC_$_INSTANCE_METHODS_AACloudKitStartMigrationRequest
- __OBJC_$_INSTANCE_METHODS_AAPaymentUIRequest
- __OBJC_$_INSTANCE_METHODS_AAPersonalInfoUIRequest
- ___54-[AAURLSession _enqueueRequest:withFlowID:completion:]_block_invoke
CStrings:
+ "AAAFoundationBackoff"
+ "AAForceServerBackoff"
+ "AAServerBackoffHelper: asking the server for a backoff directive via %{public}@"
+ "AAServerBackoffHelper: processed backoff info from response headers"
+ "AAServerBackoffHelper: suppressing request for urlBagKey=%{public}@"
+ "Setting client bundle ID header: %@"
+ "Setting proxied app bundle ID header: %@"
+ "X-Apple-I-Client-Bundle-Id"
+ "X-Apple-I-Force-Backoff"
+ "X-Apple-I-Proxied-Bundle-Id"
+ "_intelligenceScore"
+ "_isSyncAction"
+ "_source"
+ "com.apple.campo"
+ "icss"
```
