## NanoPassKit

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NanoPassKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e8dd4` | `0x1e9d88` | **`+0xfb4`** |
| `__TEXT.__oslogstring` | `0x22469` | `0x22813` | **`+0x3aa`** |
| `__AUTH_CONST.__objc_const` | `0x36c98` | `0x36e88` | **`+0x1f0`** |
| `__TEXT.__objc_methlist` | `0x1fdf0` | `0x1ff28` | **`+0x138`** |
| `__AUTH.__objc_data` | `0x8cf0` | `0x8d90` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x7430` | `0x7480` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xa960` | `0xa9a0` | **`+0x40`** |
| `__TEXT.__const` | `0x2b0` | `0x2f0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x12c44` | `0x12c84` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x37d0` | `0x3808` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e98` | `0x8eb8` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0xf68` | `0xf78` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0xf10` | `0xf20` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x4018` | `0x4020` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1608` | `0x1610` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x16ac` | `0x16b0` | **`+0x4`** |

### Other Changes

```diff

-1338.0.0.0.0
+1341.0.0.0.0

-  Functions: 11877
-  Symbols:   18585
-  CStrings:  3745
+  Functions: 11907
+  Symbols:   18633
+  CStrings:  3749
Symbols:
+ -[NPKPaymentWebServiceCompanionTargetDevice handleUpdateReviewStateForProfileWithResponse:]
+ -[NPKPaymentWebServiceCompanionTargetDevice updateReviewStateForProfile:withCompletionHandler:]
+ -[NPKProtoUpdateReviewStateForProfileRequest .cxx_destruct]
+ -[NPKProtoUpdateReviewStateForProfileRequest copyTo:]
+ -[NPKProtoUpdateReviewStateForProfileRequest copyWithZone:]
+ -[NPKProtoUpdateReviewStateForProfileRequest description]
+ -[NPKProtoUpdateReviewStateForProfileRequest dictionaryRepresentation]
+ -[NPKProtoUpdateReviewStateForProfileRequest hasRawReviewState]
+ -[NPKProtoUpdateReviewStateForProfileRequest hash]
+ -[NPKProtoUpdateReviewStateForProfileRequest isEqual:]
+ -[NPKProtoUpdateReviewStateForProfileRequest mergeFrom:]
+ -[NPKProtoUpdateReviewStateForProfileRequest rawReviewState]
+ -[NPKProtoUpdateReviewStateForProfileRequest readFrom:]
+ -[NPKProtoUpdateReviewStateForProfileRequest setRawReviewState:]
+ -[NPKProtoUpdateReviewStateForProfileRequest writeTo:]
+ -[NPKProtoUpdateReviewStateForProfileResponse copyTo:]
+ -[NPKProtoUpdateReviewStateForProfileResponse copyWithZone:]
+ -[NPKProtoUpdateReviewStateForProfileResponse description]
+ -[NPKProtoUpdateReviewStateForProfileResponse dictionaryRepresentation]
+ -[NPKProtoUpdateReviewStateForProfileResponse hash]
+ -[NPKProtoUpdateReviewStateForProfileResponse isEqual:]
+ -[NPKProtoUpdateReviewStateForProfileResponse mergeFrom:]
+ -[NPKProtoUpdateReviewStateForProfileResponse readFrom:]
+ -[NPKProtoUpdateReviewStateForProfileResponse writeTo:]
+ GCC_except_table891
+ GCC_except_table902
+ _NPKAutomaticNotificationDismissalOnTapDisabled
+ _NPKDisableNotificationAutoDismissOnTapDefault
+ _NPKProtoUpdateReviewStateForProfileRequestReadFrom
+ _NPKProtoUpdateReviewStateForProfileResponseReadFrom
+ _OBJC_CLASS_$_NPKProtoUpdateReviewStateForProfileRequest
+ _OBJC_CLASS_$_NPKProtoUpdateReviewStateForProfileResponse
+ _OBJC_IVAR_$_NPKProtoUpdateReviewStateForProfileRequest._rawReviewState
+ _OBJC_METACLASS_$_NPKProtoUpdateReviewStateForProfileRequest
+ _OBJC_METACLASS_$_NPKProtoUpdateReviewStateForProfileResponse
+ _PKRestrictionsRecoveryOptionReviewStateToString
+ __OBJC_$_INSTANCE_METHODS_NPKProtoUpdateReviewStateForProfileRequest
+ __OBJC_$_INSTANCE_METHODS_NPKProtoUpdateReviewStateForProfileResponse
+ __OBJC_$_INSTANCE_VARIABLES_NPKProtoUpdateReviewStateForProfileRequest
+ __OBJC_$_PROP_LIST_NPKProtoUpdateReviewStateForProfileRequest
+ __OBJC_CLASS_PROTOCOLS_$_NPKProtoUpdateReviewStateForProfileRequest
+ __OBJC_CLASS_PROTOCOLS_$_NPKProtoUpdateReviewStateForProfileResponse
+ __OBJC_CLASS_RO_$_NPKProtoUpdateReviewStateForProfileRequest
+ __OBJC_CLASS_RO_$_NPKProtoUpdateReviewStateForProfileResponse
+ __OBJC_METACLASS_RO_$_NPKProtoUpdateReviewStateForProfileRequest
+ __OBJC_METACLASS_RO_$_NPKProtoUpdateReviewStateForProfileResponse
+ ___91-[NPKPaymentWebServiceCompanionTargetDevice handleUpdateReviewStateForProfileWithResponse:]_block_invoke
+ ___95-[NPKPaymentWebServiceCompanionTargetDevice updateReviewStateForProfile:withCompletionHandler:]_block_invoke
+ ___95-[NPKPaymentWebServiceCompanionTargetDevice updateReviewStateForProfile:withCompletionHandler:]_block_invoke_2
- GCC_except_table897
CStrings:
+ "Error: Incoming unhandled protobuf: %@ %@ %{private}@ %{private}@ %@"
+ "Error: NPKIDVRemoteDeviceService: Current deviceID: %{private}@ doesn't match expectedID:%{private}@."
+ "Error: NPKIDVRemoteDeviceService: Error during deviceID:%{private}@ check"
+ "Error: NPKIDVRemoteDeviceService: Finish request confirmation DeviceID:%{private}@, error:%@"
+ "Error: NPKIDVRemoteDeviceService: Request for device SEID: %{private}@ deviceSEID complete with error: %@"
+ "NPKDisableNotificationAutoDismissOnTapDefault"
+ "Notice: %s Balance associated identifiers. Balance ID %{private}@, found associated balance IDs %{private}@"
+ "Notice: %s Complete list of mutated balances: %{private}@, including the associated applet balances: %{private}@."
+ "Notice: %{public}@: Received handle provisioning request with invitation: %{private}@ metadata: %{private}@"
+ "Notice: %{public}@: Requesting subcredential invitation: %{private}@"
+ "Notice: %{public}@: Sending subcredential provisioning request for invitation: %{private}@"
+ "Notice: %{public}@: Starting provisioning for provisioning controller: %{private}@ with configuration: %{private}@"
+ "Notice: %{public}@: Subcredential provisioning for invitation: %{private}@ completed with pass: %@ error %@"
+ "Notice: (PKPaymentBalance restore) archiving old balances for pass %@ %{private}@ returned nil"
+ "Notice: (PKPaymentBalance restore) restoring old balances for pass %@ %{private}@"
+ "Notice: (apple-balance-pass-provisioning) Invalid account identifier: %{private}@"
+ "Notice: Can provision payment pass with primary account identifier %{private}@"
+ "Notice: Device Metadata: Phone number %{private}@ to be added"
+ "Notice: Did complete credentials update %{private}@ for unique ID %@ paymentApplicationIdentifier %{private}@. Error: %@"
+ "Notice: Got iCloud info: %{private}@ %@"
+ "Notice: Handling balance reminder update %@ for balance %{private}@ unique ID %@"
+ "Notice: Handling balance update %{private}@ for unique ID %@"
+ "Notice: Handling credentials update %{private}@ for unique ID %@ paymentApplicationIdentifier %{private}@"
+ "Notice: Incoming update push token protobuf: %{private}@"
+ "Notice: NPKCompanionAgentConnection (%@): Payment pass did update balance reminder: %@, reminder %@, balance %{private}@"
+ "Notice: NPKCompanionAgentConnection (%@): Payment pass did update balances: %@, balances %{private}@"
+ "Notice: NPKCompanionAgentConnection (account-pass-provisioning) (%@): provisionPassForAccountIdentifier %{private}@ makeDefault %@"
+ "Notice: NPKCompanionAgentConnection (apple-balance-pass-provisioning) (%@): provisionPassForRemoteCredentialType %ld identifier: %{private}@"
+ "Notice: NPKIDVRemoteDeviceService: Did tear down service context for deviceID:%{private}@ reason:%@"
+ "Notice: NPKIDVRemoteDeviceService: Finish request confirmation DeviceID:%{private}@"
+ "Notice: NPKIDVRemoteDeviceService: Found remote process with service Names:%@ event:%@ for deviceID:%{private}@"
+ "Notice: NPKIDVRemoteDeviceService: Request for device SEID: %{private}@ deviceSEID complete"
+ "Notice: NPKIDVRemoteDeviceService: Setup biometric authentication token reminder for deviceID:%{private}@"
+ "Notice: NPKIDVRemoteDeviceService: Will tear down service context:%@ at path:%@ for deviceID:%{private}@ reason:%@"
+ "Notice: NPKIDVRemoteDeviceService: initialized context:%@ at path:%@ for device with ParingID:%{private}@ and deviceID:%{private}@"
+ "Notice: NPKIDVRemoteDeviceService: requested confirm DeviceID:%{private}@"
+ "Notice: NPKIDVRemoteDeviceService: tear down biometric authentication token reminder for deviceID:%{private}@"
+ "Notice: Paired or pairing device has advertised name %{private}@"
+ "Notice: Person ID: %{private}@ Local account: %{private}@"
+ "Notice: Push token from gizmo is %{private}@"
+ "Notice: Service sent with success: %@ %@ %{private}@ %d %@"
+ "Notice: Successfully wrote balances in database: %p, balance: %{private}@, uniqueID: %@"
+ "Notice: Target check fido key presence for relayingParty %@ accountHash %{private}@ fidoKeyHash %{private}@ completion %@"
+ "Notice: Target checkFidoKeyResponse: incoming protobuf %{private}@"
+ "Notice: Target create fido key for relying party %@ accountHash %{private}@ challenge %{private}@ externalizedauth %{private}@ with completion %@"
+ "Notice: Target createFidoKeyResponse: incoming protobuf %{private}@"
+ "Notice: Target device - accept subcredential invitation request with identifier: %{private}@ metadata: %{private}@"
+ "Notice: Target device - accept subcredential invitation request with invitation: %{private}@"
+ "Notice: Target device - can accept invitation request with invitation: %{private}@ completion: %@"
+ "Notice: Target device - provision home key pass for serial numbers: %{private}@ completion: %@"
+ "Notice: Target device - register credentials with identifiers %{private}@"
+ "Notice: Target device - request subcredential invitation %{private}@ with completion %@"
+ "Notice: Target device - revoke credentials with identifiers %{private}@ completion %@"
+ "Notice: Target device - update metadata on pass %{private}@ with credential %{private}@ completion %@"
+ "Notice: Target device does not support updateReviewStateForProfile:withCompletionHandler: message."
+ "Notice: Target device: getting balance reminder for balance %{private}@ with passInfo %@"
+ "Notice: Target device: setting balance reminder %@ for balance %{private}@ with passInfo %@"
+ "Notice: Target familyMembersResponse: child altDSID:%{private}@"
+ "Notice: Target handleUpdateReviewStateForProfileWithResponse: incoming protobuf %@"
+ "Notice: Target sign with fido key for relaying party %@ accountHash %{private}@ fidoKeyHash %{private}@ challenge %{private}@ publicKeyIdentifier %{private}@ externalizedAuth %{private}@ completion %@"
+ "Notice: Target signWithFidoKeyResponse: incoming protobuf %{private}@"
+ "Notice: added Manually mutated transit Applet Balance:%{private}@"
+ "Notice: identifier %{private}@ request %@ error handler %@"
+ "Notice: watchProvisioningURLForPaymentPasses returning URL: %{private}@"
+ "Warning: NPKIDVRemoteDeviceService: It seem we didn't teardown deviceID:%{private}@. Lets make sure we start from a clean state"
+ "Warning: Web service context (%{private}@) is invalid because the device ID (%{private}@) does not match the watch's SEIDs (%{private}@)"
+ "rawReviewState"
- "Error: Incoming unhandled protobuf: %@ %@ %@ %@ %@"
- "Error: NPKIDVRemoteDeviceService: Current deviceID: %@ doesn't match expectedID:%@."
- "Error: NPKIDVRemoteDeviceService: Error during deviceID:%@ check"
- "Error: NPKIDVRemoteDeviceService: Finish request confirmation DeviceID:%@, error:%@"
- "Error: NPKIDVRemoteDeviceService: Request for device SEID: %@ deviceSEID complete with error: %@"
- "Notice: %s Balance associated identifiers. Balance ID %@, found associated balance IDs %@"
- "Notice: %s Complete list of mutated balances: %@, including the associated applet balances: %@."
- "Notice: %{public}@: Received handle provisioning request with invitation: %@ metadata: %@"
- "Notice: %{public}@: Requesting subcredential invitation: %@"
- "Notice: %{public}@: Sending subcredential provisioning request for invitation: %@"
- "Notice: %{public}@: Starting provisioning for provisioning controller: %@ with configuration: %@"
- "Notice: %{public}@: Subcredential provisioning for invitation: %@ completed with pass: %@ error %@"
- "Notice: (PKPaymentBalance restore) archiving old balances for pass %@ %@ returned nil"
- "Notice: (PKPaymentBalance restore) restoring old balances for pass %@ %@"
- "Notice: (apple-balance-pass-provisioning) Invalid account identifier: %@"
- "Notice: Can provision payment pass with primary account identifier %@"
- "Notice: Device Metadata: Phone number %@ to be added"
- "Notice: Did complete credentials update %@ for unique ID %@ paymentApplicationIdentifier %@. Error: %@"
- "Notice: Got iCloud info: %@ %@"
- "Notice: Handling balance reminder update %@ for balance %@ unique ID %@"
- "Notice: Handling balance update %@ for unique ID %@"
- "Notice: Handling credentials update %@ for unique ID %@ paymentApplicationIdentifier %@"
- "Notice: Incoming update push token protobuf: %@"
- "Notice: NPKCompanionAgentConnection (%@): Payment pass did update balance reminder: %@, reminder %@, balance %@"
- "Notice: NPKCompanionAgentConnection (%@): Payment pass did update balances: %@, balances %@"
- "Notice: NPKCompanionAgentConnection (account-pass-provisioning) (%@): provisionPassForAccountIdentifier %@ makeDefault %@"
- "Notice: NPKCompanionAgentConnection (apple-balance-pass-provisioning) (%@): provisionPassForRemoteCredentialType %ld identifier: %@"
- "Notice: NPKIDVRemoteDeviceService: Did tear down service context for deviceID:%@ reason:%@"
- "Notice: NPKIDVRemoteDeviceService: Finish request confirmation DeviceID:%@"
- "Notice: NPKIDVRemoteDeviceService: Found remote process with service Names:%@ event:%@ for deviceID:%@"
- "Notice: NPKIDVRemoteDeviceService: Request for device SEID: %@ deviceSEID complete"
- "Notice: NPKIDVRemoteDeviceService: Setup biometric authentication token reminder for deviceID:%@"
- "Notice: NPKIDVRemoteDeviceService: Will tear down service context:%@ at path:%@ for deviceID:%@ reason:%@"
- "Notice: NPKIDVRemoteDeviceService: initialized context:%@ at path:%@ for device with ParingID:%@ and deviceID:%@"
- "Notice: NPKIDVRemoteDeviceService: requested confirm DeviceID:%@"
- "Notice: NPKIDVRemoteDeviceService: tear down biometric authentication token reminder for deviceID:%@"
- "Notice: Paired or pairing device has advertised name %@"
- "Notice: Person ID: %@ Local account: %@"
- "Notice: Push token from gizmo is %@"
- "Notice: Service sent with success: %@ %@ %@ %d %@"
- "Notice: Successfully wrote balances in database: %p, balance: %@, uniqueID: %@"
- "Notice: Target check fido key presence for relayingParty %@ accountHash %@ fidoKeyHash %@ completion %@"
- "Notice: Target checkFidoKeyResponse: incoming protobuf %@"
- "Notice: Target create fido key for relying party %@ accountHash %@ challenge %@ externalizedauth %@ with completion %@"
- "Notice: Target createFidoKeyResponse: incoming protobuf %@"
- "Notice: Target device - accept subcredential invitation request with identifier: %@ metadata: %@"
- "Notice: Target device - accept subcredential invitation request with invitation: %@"
- "Notice: Target device - can accept invitation request with invitation: %@ completion: %@"
- "Notice: Target device - provision home key pass for serial numbers: %@ completion: %@"
- "Notice: Target device - register credentials with identifiers %@"
- "Notice: Target device - request subcredential invitation %@ with completion %@"
- "Notice: Target device - revoke credentials with identifiers %@ completion %@"
- "Notice: Target device - update metadata on pass %@ with credential %@ completion %@"
- "Notice: Target device: getting balance reminder for balance %@ with passInfo %@"
- "Notice: Target device: setting balance reminder %@ for balance %@ with passInfo %@"
- "Notice: Target familyMembersResponse: child altDSID:%@"
- "Notice: Target sign with fido key for relaying party %@ accountHash %@ fidoKeyHash %@ challenge %@ publicKeyIdentifier %@ externalizedAuth %@ completion %@"
- "Notice: Target signWithFidoKeyResponse: incoming protobuf %@"
- "Notice: added Manually mutated transit Applet Balance:%@"
- "Notice: identifier %@ request %@ error handler %@"
- "Notice: watchProvisioningURLForPaymentPasses returning URL: %@"
- "Warning: NPKIDVRemoteDeviceService: It seem we didn't teardown deviceID:%@. Lets make sure we start from a clean state"
- "Warning: Web service context (%@) is invalid because the device ID (%@) does not match the watch's SEIDs (%@)"
```
