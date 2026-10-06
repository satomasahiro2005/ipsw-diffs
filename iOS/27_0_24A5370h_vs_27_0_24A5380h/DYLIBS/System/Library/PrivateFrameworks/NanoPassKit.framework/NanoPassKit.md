## NanoPassKit

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NanoPassKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e7c00` | `0x1e8dd4` | **`+0x11d4`** |
| `__TEXT.__oslogstring` | `0x21f6b` | `0x22469` | **`+0x4fe`** |
| `__AUTH.__objc_data` | `0x8e80` | `0x8cf0` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `0xb90` | `0xd20` | **`+0x190`** |
| `__AUTH_CONST.__objc_const` | `0x36c10` | `0x36c98` | **`+0x88`** |
| `__DATA_CONST.__const` | `0x3fc0` | `0x4018` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x1fd98` | `0x1fdf0` | **`+0x58`** |
| `__TEXT.__cstring` | `0x12c74` | `0x12c44` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x7400` | `0x7430` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xa980` | `0xa960` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e78` | `0x8e98` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x16a4` | `0x16ac` | **`+0x8`** |

### Other Changes

```diff

-1334.0.0.0.0
+1338.0.0.0.0

-  Functions: 11863
-  Symbols:   18572
-  CStrings:  3732
+  Functions: 11877
+  Symbols:   18585
+  CStrings:  3745
Symbols:
+ -[NPKIDVRemoteDeviceProtoPrearmStatusUpdate hasReason]
+ -[NPKIDVRemoteDeviceProtoPrearmStatusUpdate reason]
+ -[NPKIDVRemoteDeviceProtoPrearmStatusUpdate setHasReason:]
+ -[NPKIDVRemoteDeviceProtoPrearmStatusUpdate setReason:]
+ -[NPKIDVRemoteDeviceSession fetchRemoteBiometricSuspensionReasonForCredentialType:completion:]
+ -[NPKIDVRemoteDeviceSessionServer fetchRemoteBiometricSuspensionReasonForCredentialType:completion:]
+ -[NPKPaymentWebServiceCompanionTargetDevice(Capabilities) _isCheckingProvisioningRequirementsSupported]
+ GCC_except_table158
+ GCC_except_table159
+ GCC_except_table160
+ GCC_except_table198
+ _NPKGetRemoteBiometricAuthenticationStatusSuspensionReason
+ _NPKPresentPriorityUserNotification
+ _NPKPriorityAlertServiceName
+ _NPKSetRemoteBiometricAuthenticationStatusSuspensionReason
+ _OBJC_IVAR_$_NPKIDVRemoteDeviceProtoPrearmStatusUpdate._has
+ _OBJC_IVAR_$_NPKIDVRemoteDeviceProtoPrearmStatusUpdate._reason
+ ___100-[NPKIDVRemoteDeviceSessionServer fetchRemoteBiometricSuspensionReasonForCredentialType:completion:]_block_invoke
+ ___104-[NPKIDVRemoteDeviceSessionServer fetchRemoteBiometricAuthenticationStatusForCredentialType:completion:]_block_invoke
+ ___94-[NPKIDVRemoteDeviceSession fetchRemoteBiometricSuspensionReasonForCredentialType:completion:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e11_v20?0B8q12ls32l8
+ ___block_descriptor_40_e8_32bs_e23_v28?0B8q12"NSError"20ls32l8
+ ___block_descriptor_41_e8_32bs_e28_v24?0"NSData"8"NSError"16ls32l8
+ ___block_descriptor_56_e8_32s40bs_e20_v24?0q8"NSError"16ls40l8s32l8
- GCC_except_table154
- GCC_except_table155
- GCC_except_table190
- GCC_except_table222
- GCC_except_table78
- _NPKAnalyticsReportErrorTypeUnlockIPhone
- _NPKAnalyticsReportEventTypeBarcodePaymentTransactionLocalExtensionFailed
- _NPKAnalyticsReportEventTypeBarcodePaymentTransactionLocalExtensionSucceeded
- _NPKAnalyticsReportEventTypeBarcodePaymentTransactionRemoteExtensionFailed
- _NPKAnalyticsReportEventTypeBarcodePaymentTransactionRemoteExtensionSucceeded
- ___block_descriptor_40_e8_32bs_e28_v24?0"NSData"8"NSError"16ls32l8
CStrings:
+ "%d"
+ "-"
+ "Error: NPKIDVRemoteDeviceService: Error during remote biometric suspension reason request of type %@: %@"
+ "Error: NPKIDVRemoteDeviceService: Finished request for remote biometric suspension reason of type:%@. Suspension reason:%@ error:%@"
+ "Error: Unable to read NPKRemoteBiometricAuthenticationStatusSuspensionReasonKey in NPS; domain accessor not found"
+ "Error: Unable to update NPKRemoteBiometricAuthenticationStatusSuspensionReasonKey in NPS; domain accessor not found"
+ "NPKRemoteBiometricAuthenticationStatusCoordinatorSuspensionReason"
+ "Notice: Marking remote biometric authentication status suspension reason: %ld"
+ "Notice: NPKIDVRemoteDeviceService: Finished request for remote biometric suspension reason of type:%@. Suspension reason:%@"
+ "Notice: NPKIDVRemoteDeviceService: Prearm status update received: prearmStatus=%d hasReason=%d reason=%s dataLength=%lu"
+ "Notice: NPKIDVRemoteDeviceService: Received request for remote biometric suspension reason of type: %@"
+ "Notice: NPKPresentPriorityUserNotification: priority alert service is watchOS-only; presenting with default priority."
+ "Notice: Target device - not sending meetsProvisioningRequirements request; paired device does not support checkingProvisioningRequirements"
+ "Warning: NPKIDVRemoteDeviceService: Unrecognized reason value %d from paired watch — falling back to legacy prearmStatus field"
+ "com.apple.nanopassbook.priorityAlert"
+ "data"
+ "v20@?0B8q12"
+ "v28@?0B8q12@\"NSError\"20"
- "barcodePaymentTransactionLocalExtensionFailed"
- "barcodePaymentTransactionLocalExtensionSucceeded"
- "barcodePaymentTransactionRemoteExtensionFailed"
- "barcodePaymentTransactionRemoteExtensionSucceeded"
- "unlockIPhone"
```
