## akd

> `/System/Library/PrivateFrameworks/AuthKit.framework/akd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0x2f3c8` | `0x2f8e0` | **`+0x518`** |
| `__TEXT.__text` | `0x310d8c` | `0x311120` | **`+0x394`** |
| `__DATA_CONST.__cfstring` | `0x84c0` | `0x8620` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0x28a95` | `0x28b95` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x14a00` | `0x14ad0` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0x12088` | `0x12140` | **`+0xb8`** |
| `__TEXT.__cstring` | `0xbb34` | `0xbbe4` | **`+0xb0`** |
| `__DATA.__data` | `0x5b30` | `0x5b90` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x1d300` | `0x1d360` | **`+0x60`** |
| `__DATA.__objc_data` | `0x7298` | `0x72e8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xcc8c` | `0xccdc` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x8091` | `0x80e1` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x2f22` | `0x2f62` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x83a8` | `0x83e0` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x87d0` | `0x87e8` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x7d8` | `0x7ec` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0xb8c` | `0xb9c` | **`+0x10`** |
| `__TEXT.__const` | `0x7f90` | `0x7fa0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1bc0` | `0x1bc8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8f8` | `0x900` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x438` | `0x440` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x450` | `0x458` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x63c` | `0x640` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dlopen_cstrs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-550.0.0.0.0
+552.0.0.0.0

-  Functions: 10273
-  Symbols:   1689
-  CStrings:  11311
+  Functions: 10275
+  Symbols:   1690
+  CStrings:  11328
Symbols:
+ _AKCredentialCollectionIsLoud
+ _AKLastEventTimestampKey
- _OBJC_CLASS_$_AKAttestationSigner
CStrings:
+ "@\"<AKShieldUIPresenting>\""
+ "@\"<RemoteViewServiceControllerProtocol>\""
+ "AKShieldUIPresentationService"
+ "AKShieldUIPresenting"
+ "B24@0:8@\"AKAppleIDAuthenticationContext\"16"
+ "Failed to sync passkey credential name after fetchUserInfo: %{private}@"
+ "Invalid type for userAgeRange value: %@"
+ "T@\"<RemoteViewServiceControllerProtocol>\",&,N,V_viewServiceController"
+ "_didCollectUserCredentials"
+ "_lastEventTimestampChangedForAccount:userInformation:"
+ "_processShieldUIResults:context:error:completionHandler:"
+ "_shieldUIPresenter"
+ "_signAppropriateBAAForProvisioningRequest:completion:"
+ "_viewServiceController"
+ "application/x-buddyml"
+ "connectionIndex"
+ "dataMode"
+ "groupSessionID"
+ "groupSessionIDAlias"
+ "initWithAccountManager:trafficController:client:"
+ "lastEventTimestamp"
+ "lastEventTimestampForAccount:"
+ "listeningPort"
+ "localParticipantID"
+ "participantIDAlias"
+ "postNotificationName:object:userInfo:audience:entitlement:options:error:"
+ "presentShieldWithContext:completion:"
+ "psk"
+ "remoteParticipantID"
+ "setLastEventTimestamp:"
+ "setLastEventTimestamp:forAccount:"
+ "setViewServiceController:"
+ "set_didCollectUserCredentials:"
+ "shouldPresentShieldForContext:"
+ "syncPasskeyCredentialNameForAccount:userHandle:expectedName:completion:"
+ "v48@0:8@\"ACAccount\"16@\"NSString\"24@\"NSString\"32@?<v@?B@\"NSError\">40"
+ "viewServiceController"
- "@\"AKAttestationSigner\""
- "Failed to get signing headers, error: %@"
- "Presenting shield UI for context: %@"
- "Signing with BAA headers for urlKey: %@"
- "T@\"AKAttestationSigner\",&,N,V_attestationSigner"
- "_attestationSigner"
- "_presentShieldWithContext:completionHandler:"
- "_shouldPresentShieldForContext:"
- "_signAppropriateBAAForProvisioningRequest:urlKey:completion:"
- "_signWithBAAHeadersIfNeededForKey:withRequest:completion:"
- "attestationSigner"
- "isAuthenticationTelemetryEnabled"
- "isBaaEnabledForKey:"
- "isServerBackoffEnabled"
- "postNotificationName:object:userInfo:audience:entitlement:error:"
- "setAttestationSigner:"
- "signWithBAAHeaders:completion:"
- "signaturesForData:options:completion:"
- "updatePasskeyCredentialsWithAltDSID:username:"
- "v40@0:8@\"NSDictionary\"16@\"NSDictionary\"24@?<v@?@\"NSDictionary\"@\"NSData\"@\"NSError\">32"
```
