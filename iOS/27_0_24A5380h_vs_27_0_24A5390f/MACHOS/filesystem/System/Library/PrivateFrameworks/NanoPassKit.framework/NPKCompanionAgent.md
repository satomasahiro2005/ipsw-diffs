## NPKCompanionAgent

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NPKCompanionAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x9ae7` | `0x9bb6` | **`+0xcf`** |
| `__TEXT.__text` | `0x423f0` | `0x42384` | **`-0x6c`** |
| `__TEXT.__const` | `0xf8` | `0x128` | **`+0x30`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1338.0.0.0.0
+1341.0.0.0.0
Functions:
~ sub_1000108d4 : 368 -> 372
~ sub_100010b10 -> sub_100010b14 : 936 -> 940
~ sub_100023490 -> sub_100023498 : 1696 -> 1700
~ sub_100029a8c -> sub_100029a98 : 916 -> 788
~ sub_100029e20 -> sub_100029dac : 228 -> 232
~ sub_10003dd1c -> sub_10003dcac : 396 -> 400
CStrings:
+ "Error: Failed to fetch balance reminder for pass %{private}@ due to %@"
+ "Error: Watch fails to set balance reminder %@ for balance %{private}@ of pass %@"
+ "Notice: (PKPaymentBalance get) Request for balances for unique ID %@; returning %{private}@"
+ "Notice: (PKPaymentBalance set) Got updated balances %{private}@ for pass with unique ID %@. Processing subject to first unlock and paired sync."
+ "Notice: (PKPaymentBalanceReminder set) Got updated balance reminder %@ for balance %{private}@ and pass with unique ID %@. Processing subject to first unlock and paired sync."
+ "Notice: (account-pass-provisioning) companion no longer has pass for accountIdentifier %{private}@ will not reprovision"
+ "Notice: (account-pass-provisioning) companion still has pass for accountIdentifier %{private}@ will attempt reprovision"
+ "Notice: (account-pass-provisioning) handleDeviceUnlockedForPendingProvisioningRequestFromGizmo %{private}@ completion %@ %@"
+ "Notice: (account-pass-provisioning) handleDeviceUnlockedForPendingProvisioningRequestFromGizmo accountIdentifier %{private}@ makeDefault %@"
+ "Notice: (account-pass-provisioning) handleProvisioningErrorForAccountIdentifier %{private}@"
+ "Notice: (account-pass-provisioning) provisionCompletion for %{private}@ success %@"
+ "Notice: (account-pass-provisioning) provisionPassForAccountIdentifier %{private}@ makeDefault %@"
+ "Notice: (apple-balance-pass-provisioning) provisionPassForRemoteCredentialType %ld identifier: %{private}@ "
+ "Notice: Applied subcredentials %{private}@\n to pass with unique id %@\n applet %{private}@\n"
+ "Notice: Companion pass library submit verification code %{private}@ %{private}@ %@"
+ "Notice: Got balance reminder: %@ for balance %{private}@ and pass with unique ID %@; sending to %@"
+ "Notice: Got balances: %{private}@ for pass with unique ID %@; sending to %@"
+ "Notice: Handle push token: %{private}@ (current %{private}@)"
+ "Notice: Re-registering with push token %{private}@"
+ "Notice: Request to set balance reminder %@ for balance %{private}@ of pass %@"
- "Error: Failed to fetch balance reminder for pass %@ due to %@"
- "Error: Watch fails to set balance reminder %@ for balance %@ of pass %@"
- "Notice: (PKPaymentBalance get) Request for balances for unique ID %@; returning %@"
- "Notice: (PKPaymentBalance set) Got updated balances %@ for pass with unique ID %@. Processing subject to first unlock and paired sync."
- "Notice: (PKPaymentBalanceReminder set) Got updated balance reminder %@ for balance %@ and pass with unique ID %@. Processing subject to first unlock and paired sync."
- "Notice: (account-pass-provisioning) companion no longer has pass for accountIdentifier %@ will not reprovision"
- "Notice: (account-pass-provisioning) companion still has pass for accountIdentifier %@ will attempt reprovision"
- "Notice: (account-pass-provisioning) handleDeviceUnlockedForPendingProvisioningRequestFromGizmo %@ completion %@ %@"
- "Notice: (account-pass-provisioning) handleDeviceUnlockedForPendingProvisioningRequestFromGizmo accountIdentifier %@ makeDefault %@"
- "Notice: (account-pass-provisioning) handleProvisioningErrorForAccountIdentifier %@"
- "Notice: (account-pass-provisioning) provisionCompletion for %@ success %@"
- "Notice: (account-pass-provisioning) provisionPassForAccountIdentifier %@ makeDefault %@"
- "Notice: (apple-balance-pass-provisioning) provisionPassForRemoteCredentialType %ld identifier: %@ "
- "Notice: Applied subcredentials %@\n to pass with unique id %@\n applet %@\n"
- "Notice: Companion pass library submit verification code %@ %@ %@"
- "Notice: Got balance reminder: %@ for balance %@ and pass with unique ID %@; sending to %@"
- "Notice: Got balances: %@ for pass with unique ID %@; sending to %@"
- "Notice: Handle push token: %@ (current %@)"
- "Notice: Re-registering with push token %@"
- "Notice: Request to set balance reminder %@ for balance %@ of pass %@"
```
