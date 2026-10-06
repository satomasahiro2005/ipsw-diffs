## idcredd

> `/usr/libexec/idcredd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cd444` | `0x1cce70` | **`-0x5d4`** |
| `__TEXT.__eh_frame` | `0x15170` | `0x14c28` | **`-0x548`** |
| `__TEXT.__oslogstring` | `0xad99` | `0xa939` | **`-0x460`** |
| `__DATA.__bss` | `0x25d0` | `0x2950` | **`+0x380`** |
| `__TEXT.__const` | `0x5e28` | `0x6044` | **`+0x21c`** |
| `__DATA.__data` | `0x4470` | `0x45a8` | **`+0x138`** |
| `__TEXT.__swift5_typeref` | `0x2910` | `0x2a35` | **`+0x125`** |
| `__TEXT.__cstring` | `0xe80a` | `0xe6fa` | **`-0x110`** |
| `__DATA_CONST.__const` | `0x6e40` | `0x6d80` | **`-0xc0`** |
| `__TEXT.__swift5_capture` | `0x2b9c` | `0x2ae0` | **`-0xbc`** |
| `__TEXT.__swift5_fieldmd` | `0x1944` | `0x19c0` | **`+0x7c`** |
| `__TEXT.__auth_stubs` | `0x43d0` | `0x4370` | **`-0x60`** |
| `__TEXT.__objc_methname` | `0x31e5` | `0x3185` | **`-0x60`** |
| `__TEXT.__objc_methtype` | `0x10f3` | `0x1093` | **`-0x60`** |
| `__TEXT.__swift_as_cont` | `0xf34` | `0xee4` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0x2434` | `0x2480` | **`+0x4c`** |
| `__DATA_CONST.__auth_got` | `0x21f0` | `0x21c0` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1947` | `0x1976` | **`+0x2f`** |
| `__TEXT.__swift_as_ret` | `0x7e8` | `0x7bc` | **`-0x2c`** |
| `__TEXT.__objc_stubs` | `0x2280` | `0x22a0` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x18c` | `0x1a8` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x95c` | `0x944` | **`-0x18`** |
| `__TEXT.__swift_as_entry` | `0x664` | `0x650` | **`-0x14`** |
| `__TEXT.__swift5_types` | `0x20c` | `0x218` | **`+0xc`** |
| `__DATA.__common` | `0xf8` | `0x100` | **`+0x8`** |
| `__DATA.__objc_const` | `0x28c0` | `0x28b8` | **`-0x8`** |
| `__DATA.__objc_data` | `0xcb8` | `0xcb0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-9.42.0.0.0
+9.104.0.0.0

-  Functions: 4352
-  Symbols:   2026
-  CStrings:  2257
+  Functions: 4363
+  Symbols:   2021
+  CStrings:  2223
Symbols:
+ _$s13CoreIDVShared25CredentialOperationReasonO32mustPreserveTokenWhilePassExistsSbvg
+ _$s13CoreIDVShared25CredentialOperationReasonO8rawValueACSgSS_tcfC
+ _$s13CoreIDVShared25CredentialOperationReasonOMn
+ _$s13CoreIDVShared28ISO23220_1_ElementIdentifierO16givenNameUnicodeyA2CmFWC
+ _$s13CoreIDVShared28ISO23220_1_ElementIdentifierO17familyNameUnicodeyA2CmFWC
+ _$s13CoreIDVShared28ISO23220_1_ElementIdentifierO23issuingAuthorityUnicodeyA2CmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO18isUnrecoverableACLSbvg
+ _$s13CoreIDVShared8DIPErrorV4CodeO40skippedPIITokenDeletionWalletPassPresentyA2EmFWC
+ _$sSiSEsWP
+ _$sSiSesWP
+ _$ss17_assertionFailure__4file4line5flagss5NeverOs12StaticStringV_SSAHSus6UInt32VtF
- _$s13CoreIDVShared16AppleIDVManagingP22persistModifiedACLBlob_09referenceG021externalizedLAContext10Foundation4DataV12encryptedACL_SaySSGSg5uuidstAI_A2ItKFTj
- _$s13CoreIDVShared16BiometricsHelperC13biometricTypeAA017EnrolledBiometricF0OSgvgTj
- _$s13CoreIDVShared21EnrolledBiometricTypeO7touchIDyA2CmFWC
- _$s13CoreIDVShared21EnrolledBiometricTypeOMa
- _$s13CoreIDVShared21EnrolledBiometricTypeOMn
- _$s13CoreIDVShared21EnrolledBiometricTypeOSQAAMc
- _$s13CoreIDVShared8DIPErrorV4CodeO36secAccessControlCannotGetConstraintsyA2EmFWC
- _$s20CoreIDVDaemonSupport11SESKeystoreC9changeACL2of2to20authorizingLAContext10Foundation4DataVAJ_So19SecAccessControlRefaAJtKFTj
- _$sSD10FoundationE34_conditionallyBridgeFromObjectiveC_6resultSbSo12NSDictionaryC_SDyxq_GSgztFZ
- _$sSo10CFErrorRefas5Error10FoundationMc
- _$sSo19SecAccessControlRefa13CoreIDVSharedE11isOSGNChildSbvg
- _DCCredentialAuthACLTypeToString
- _OBJC_CLASS_$_NSDictionary
- _SecAccessControlCopyData
- _SecAccessControlCreate
- _SecAccessControlGetConstraints
CStrings:
+ "\nDeletion reason: "
+ "A credential payload was deleted, but the pass itself is still present in Wallet. Credential identifier: "
+ "A credential's entry was removed from the shared PII token credential list, so it no longer has a PII token, but the pass itself is still present in Wallet. Credential identifier: "
+ "A proofing or provisioning teardown tried to delete a credential's PII token, but a personalized pass for that credential is still present in Wallet, so the deletion stood down and the credential's entry in the shared PII token credential list was left in place. Nothing later releases that entry, so the token is retained indefinitely.\n\nCredential identifier: "
+ "Duplicate values for key: '"
+ "Failed to persist Tap-to-Radar filing record: %{public}@"
+ "Failed to read Tap-to-Radar filing record, resetting it: %{public}@"
+ "Fatal error"
+ "Not drafting Tap-to-Radar '%{public}s': already filed the maximum number of times for this credential"
+ "PII token retained after teardown found a Wallet pass"
+ "Skipped PII token deletion: a personalized pass is still using this token"
+ "Skipping PII token deletion for credential %{public}s (reason: %{public}s): a personalized pass is still using this token"
+ "Swift/NativeDictionary.swift"
+ "Unrecoverable ACL"
+ "Wallet pass not deleted after PII token removal"
+ "Wallet pass still present after removing the PII token tie for credential %{public}s, filing Tap-to-Radar"
+ "a PII token was kept for a Wallet pass"
+ "a Wallet pass was not deleted with its PII token"
+ "account-key-generation"
+ "dataForKey:"
+ "deletePIITokenFromSyncableKeyStore(forIdentifier:credentialIdentifier:keystoreType:reason:)"
+ "device-encryption-key-generation"
+ "key-signing-key-generation"
+ "missing-pii-token"
+ "orphaned-wallet-pass-credential"
+ "orphaned-wallet-pass-pii-token"
+ "payload-ingestion"
+ "pii-hash-mismatch"
+ "presentment-key-generation"
+ "proofing-pii-hash-mismatch"
+ "removeObjectForKey:"
+ "retained-pii-token-with-wallet-pass"
+ "tap-to-radar.filing-limit-record"
- "A credential payload was deleted, but the pass itself is still present in Wallet."
- "ACL contains oacl dictionary, no migration needed"
- "ACL does not contain oacl dictionary, no migration needed"
- "ACLMigrator migrateOACLOperation shouldHaveOACL? %{bool}d"
- "Adding oacl operation to acl"
- "BiometricStoreSessionProxy setModifiedGlobalAuthACL, modifiedAuthACL = %s"
- "Calling migrateOACLOperation with shouldHaveOACL = %{bool}d, acl type = %s, biometric type = %s"
- "Cannot find global auth acl type"
- "Cannot set modified ACL, no global ACL set."
- "Cannot set modified ACL, required stored data is missing"
- "Cannot set modified ACL, required stored data is missing sidv encryptedACL"
- "Checking global auth oacl for migration"
- "Forcing shouldHaveOACL to false due to internal defaults setting"
- "Forcing shouldHaveOACL to true due to internal defaults setting"
- "Global auth acl already migrated, nothing to do"
- "Global auth acl is v1, no migration necessary"
- "Global auth acl requires migration"
- "Modified ACL: %s"
- "New ACL uuids are %s"
- "New acl is %s = %s"
- "Presentment key %s is a child key; skipping ACL change"
- "Removing oacl operation from acl"
- "Setting OACL to true due to internal defaults setting"
- "Skipping ACL update to presentment keys due to internal defaults setting"
- "Skipping error during global auth oacl migration"
- "Unable to create empty ACL"
- "Unable to create empty ACL due to error: %{public}s"
- "Unable to create empty ACL."
- "Unable to deserialize ACL but no error provided"
- "Updating ACL for presentment key %s"
- "Updating acl for progenitor key %s"
- "Updating global progenitor key"
- "Updating global third party progenitor key"
- "Wallet pass still present after deleting PII token, filing Tap-to-Radar"
- "acl does not contain osgn operation"
- "changeACL(of:to:authorizingLAContext:)"
- "changeSESKeyACL error getting new constraints "
- "changeSESKeyACL error getting old constraints "
- "changeSESKeyACL new ACL: "
- "changeSESKeyACL old ACL: "
- "changeSESKeyACL(keyBlob:to:authorizingLAContext:)"
- "debug.biometrics.force-adding-oacl-to-acls"
- "debug.biometrics.set-oacl-to-true"
- "debug.biometrics.skip-adding-oacl-to-acls"
- "debug.biometrics.update-acl-skip-presentment-keys"
- "deletePIITokenFromSyncableKeyStore(forIdentifier:credentialIdentifier:keystoreType:)"
- "evaluateAccessControl:operation:options:error:"
- "evaluateWithAlwaysTrueACL(laContext:)"
- "generateAlwaysTrueACL()"
- "idcredd/ACLMigrator.swift"
- "migrateGlobalAuthOACLOperation()"
- "migrateOACLOperation(for:aclType:)"
- "migrateOACLOperation(for:shouldHaveOACL:)"
- "missing key info in stored presentment key"
- "no bound credential present skip returning uuids"
- "set new sidv encrypedACL"
- "setModifiedAuthACLV1(storedACL:newACLData:context:externalizedLAContext:)"
- "setModifiedAuthACLV2PresentmentKeys(newACL:context:externalizedLAContext:)"
- "setModifiedAuthACLV2ProgentiorKey(storedACL:newACL:newACLData:context:externalizedLAContext:)"
- "setModifiedGlobalAuthACL(_:externalizedLAContext:)"
- "setModifiedGlobalAuthACL(data:externalizedLAContext:)"
- "setModifiedGlobalAuthACL:externalizedLAContext:completion:"
- "skip manipulating legacy sidv encryptedACL because there isn't one"
- "unable to get acl constraints"
- "unknown auth acl version"
- "unknown auth acl version for third party auth acl"
- "v40@0:8@\"NSData\"16@\"NSData\"24@?<v@?@\"NSArray\"@\"NSError\">32"
```
