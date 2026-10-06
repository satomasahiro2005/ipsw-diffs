## idcredd

> `/usr/libexec/idcredd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1add94` | `0x1b6914` | **`+0x8b80`** |
| `__TEXT.__cstring` | `0xdb1b` | `0xe1f9` | **`+0x6de`** |
| `__TEXT.__eh_frame` | `0x14024` | `0x1466c` | **`+0x648`** |
| `__TEXT.__oslogstring` | `0xa849` | `0xad28` | **`+0x4df`** |
| `__DATA_CONST.__const` | `0x5e48` | `0x6238` | **`+0x3f0`** |
| `__TEXT.__unwind_info` | `0x5480` | `0x57b8` | **`+0x338`** |
| `__TEXT.__const` | `0x55c8` | `0x5828` | **`+0x260`** |
| `__TEXT.__swift5_reflstr` | `0x1727` | `0x1867` | **`+0x140`** |
| `__TEXT.__swift5_fieldmd` | `0x163c` | `0x1758` | **`+0x11c`** |
| `__DATA.__bss` | `0x20d0` | `0x21d0` | **`+0x100`** |
| `__DATA_CONST.__got` | `0x16e0` | `0x17c0` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x225c` | `0x22f8` | **`+0x9c`** |
| `__TEXT.__swift5_capture` | `0x2174` | `0x2204` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x276e` | `0x27e8` | **`+0x7a`** |
| `__TEXT.__objc_stubs` | `0x1e60` | `0x1ec0` | **`+0x60`** |
| `__TEXT.__swift_as_cont` | `0xeac` | `0xf00` | **`+0x54`** |
| `__TEXT.__auth_stubs` | `0x4130` | `0x4160` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x2e35` | `0x2e05` | **`-0x30`** |
| `__TEXT.__swift_as_ret` | `0x79c` | `0x7bc` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xa68` | `0xa80` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x20a0` | `0x20b8` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x9c8` | `0x9e0` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x1e0` | `0x1f4` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x620` | `0x634` | **`+0x14`** |
| `__TEXT.__objc_classname` | `0x7a4` | `0x7b4` | **`+0x10`** |
| `__DATA.__objc_data` | `0xc70` | `0xc78` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x164` | `0x16c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-9.34.0.0.0
+9.36.0.0.0

-  Functions: 4071
-  Symbols:   1912
-  CStrings:  2124
+  Functions: 4145
+  Symbols:   1943
+  CStrings:  2184
Symbols:
+ _$s13CoreIDVShared13IDCSAnalyticsC23sendDeviceKeyReuseEvent9timesUsed23selectionReasonRawValue20totalUsableKeysCount12documentType19issuingJurisdiction0U9AuthorityySi_S2iS2SSgAKtFZ
+ _$s13CoreIDVShared13IDCSAnalyticsC26PIIReconciliationEventTypeO15restoredPIIHashyA2EmFWC
+ _$s13CoreIDVShared13IDCSAnalyticsC26PIIReconciliationEventTypeO15strandedPIIHashyA2EmFWC
+ _$s13CoreIDVShared13IDCSAnalyticsC26PIIReconciliationEventTypeO16restoredPIITokenyA2EmFWC
+ _$s13CoreIDVShared13IDCSAnalyticsC26PIIReconciliationEventTypeO17orphanedPIIBackupyA2EmFWC
+ _$s13CoreIDVShared13IDCSAnalyticsC26PIIReconciliationEventTypeO20unrecoverablePIIHashyA2EmFWC
+ _$s13CoreIDVShared13IDCSAnalyticsC26PIIReconciliationEventTypeO21unrecoverablePIITokenyA2EmFWC
+ _$s13CoreIDVShared13IDCSAnalyticsC26PIIReconciliationEventTypeOMa
+ _$s13CoreIDVShared13IDCSAnalyticsC26sendPIIReconciliationEvent9eventType5countyAC0efH0O_SitFZ
+ _$s13CoreIDVShared16AppleIDVManagingP42addBiometricStockholmAppRequiredConstraint5toACLySo19SecAccessControlRefa_tKFTj
+ _$s13CoreIDVShared8DIPErrorV4CodeO020unableToStorePIIHashG14NotInitializedyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO025watchSessionForKeySigningH16GenerationFailedyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO026unableToGenerateKeySigningH0yA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO20xpcConnectionFailureyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO23createRandomBytesFailedyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO23invalidSignatureDetailsyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO23invalidSigningAlgorithmyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO25unableToGenerateCOSESign1yA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO26provisioningIdentityFailedyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO27keychainFailureDuplicateKeyyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO27provisioningRequestTimedOutyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO30unableToGeneratePresentmentKeyyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO35keySigningKeyAttestationUnavailableyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO35provisioningAttestationsUnavailableyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO35unableToGenerateDeviceEncryptionKeyyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO38identityProvisioningMissingEntitlementyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO40unableToDeletePIIHashStoreNotInitializedyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO40watchSessionForDeviceEncryptionKeyFailedyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO42unableToRetrievePIIHashStoreNotInitializedyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO43provisioningCredentialIdentifierUnavailableyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO45watchSessionForPresentmentKeyGenerationFailedyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO46watchSessionForPresentmentKeysGenerationFailedyA2EmFWC
+ _$sSS9hasSuffixySbSSF
- _$sSo15NSXPCConnectionC13CoreIDVSharedE10isEntitledySbSSF
- _swift_willThrowTypedImpl
CStrings:
+ "Applying 'Payments & Contactless' switch constraint"
+ "Credential store not initialized"
+ "Error deleting stranded keychain hash during reconciliation"
+ "Error during PII inconsistency restore"
+ "Error during PII orphan cleanup"
+ "Error during stranded keychain hash cleanup"
+ "Error processing keychain backup during reconciliation"
+ "Error reconciling PII hash during PII reconciliation"
+ "Error reconciling PII token during PII reconciliation"
+ "Failed to encode keychain PII token"
+ "Failed to generate COSE_Sign1"
+ "Failed to generate device encryption key"
+ "Failed to generate key signing key"
+ "Failed to generate presentment key"
+ "Failed to generate random bytes"
+ "Finished PII data reconciliation"
+ "Invalid device encryption key"
+ "Invalid device encryption key type"
+ "Invalid public key"
+ "Invalid signature details"
+ "Invalid signing algorithm"
+ "Key signing key attestation unavailable"
+ "Keychain operation failed"
+ "Minimum number of times a presentment key is used is %lld for credentialIdentifier %{public}s (docType: %{public}s), needs key refresh"
+ "Missing device encryption key"
+ "Missing identity provisioning entitlement"
+ "Missing key signing key"
+ "Missing presentment key"
+ "PII data not found"
+ "PII reconciler: deleting fully orphaned keychain backup"
+ "PII reconciler: deleting stranded keychain hash with no parent token"
+ "PII reconciler: local hash missing for credential, restoring from keychain backup"
+ "PII reconciler: local token missing for credential, restoring from keychain backup"
+ "PII reconciler: no credential list for keychain backup, deleting"
+ "PII reconciler: no keychain hash to delete for orphan cleanup"
+ "PII reconciler: pruning credential list from %ld to %ld entries"
+ "PII reconciler: restoring keychain PII hash from local copy"
+ "PII reconciler: restoring keychain PII token from local copy"
+ "PII reconciler: scanning credentials for inconsistent backups"
+ "PII reconciler: scanning keychain for orphaned backups"
+ "PII reconciler: scanning keychain for stranded hash backups"
+ "PII reconciler: unrecoverable - credential has no local or keychain PII hash"
+ "PII reconciler: unrecoverable - credential has no local or keychain PII token"
+ "Provisioning attestations unavailable"
+ "Provisioning credential identifier unavailable"
+ "Provisioning identity failed"
+ "Provisioning request timed out"
+ "Starting PII data reconciliation"
+ "Unknown device encryption scenario"
+ "Unknown keystore type"
+ "Watch session for device encryption key failed"
+ "Watch session for key signing key generation failed"
+ "Watch session for presentment key generation failed"
+ "Watch session for presentment keys generation failed"
+ "XPC connection failure"
+ "com.apple.idcredd.piidatareconciler"
+ "idcredd/PIIDataReconciler.swift"
+ "piiTokenIdentifier"
+ "restoreLocalToken(for:keyManager:)"
+ "setPiiTokenIdentifier:"
+ "valueForEntitlement:"
- "Minimum number of times a presentment key is used is %lld, needs key refresh"
```
