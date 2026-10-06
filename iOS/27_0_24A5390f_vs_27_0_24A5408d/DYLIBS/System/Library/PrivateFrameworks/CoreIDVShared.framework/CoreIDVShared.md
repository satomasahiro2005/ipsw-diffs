## CoreIDVShared

> `/System/Library/PrivateFrameworks/CoreIDVShared.framework/CoreIDVShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x241db4` | `0x243208` | **`+0x1454`** |
| `__DATA.__bss` | `0x30970` | `0x30e70` | **`+0x500`** |
| `__TEXT.__cstring` | `0x169de` | `0x16d5e` | **`+0x380`** |
| `__TEXT.__const` | `0x2d7a4` | `0x2daf4` | **`+0x350`** |
| `__TEXT.__swift5_reflstr` | `0x14706` | `0x14a36` | **`+0x330`** |
| `__AUTH_CONST.__const` | `0x16e78` | `0x17158` | **`+0x2e0`** |
| `__AUTH_CONST.__objc_const` | `0x6a60` | `0x6bf8` | **`+0x198`** |
| `__TEXT.__swift5_fieldmd` | `0xced0` | `0xd010` | **`+0x140`** |
| `__AUTH.__objc_data` | `0xd80` | `0xea0` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x9370` | `0x9410` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x6bd8` | `0x6c64` | **`+0x8c`** |
| `__DATA.__data` | `0x6e78` | `0x6ed8` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0xf188` | `0xf1e0` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x1ae4` | `0x1b34` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0xf00` | `0xf48` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x6ed6` | `0x6f10` | **`+0x3a`** |
| `__AUTH.__data` | `0x1618` | `0x1648` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x1948` | `0x1970` | **`+0x28`** |
| `__DATA_CONST.__const` | `0xe10` | `0xe28` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x26c` | `0x280` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xb20` | `0xb30` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2c0` | `0x2d0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xa68` | `0xa78` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x33b0` | `0x33c0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x9c4` | `0x9d0` | **`+0xc`** |
| `__DATA_DIRTY.__objc_data` | `0x2ca8` | `0x2cb0` | **`+0x8`** |

### Other Changes

```diff

-9.38.0.0.0
+9.42.0.0.0

+  - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration

-  Functions: 13943
-  Symbols:   4069
-  CStrings:  2629
+  Functions: 14012
+  Symbols:   4092
+  CStrings:  2655
Symbols:
+ _MCFeatureFingerprintForContactlessPaymentAllowed
+ _OBJC_CLASS_$_DIPDeviceDetection
+ _OBJC_CLASS_$_MCProfileConnection
+ _OBJC_CLASS_$__TtC13CoreIDVShared29IdentityProofingAnalyticsInfo
+ _OBJC_METACLASS_$_DIPDeviceDetection
+ _OBJC_METACLASS_$__TtC13CoreIDVShared29IdentityProofingAnalyticsInfo
+ __CLASS_METHODS__TtC13CoreIDVShared29IdentityProofingAnalyticsInfo
+ __CLASS_PROPERTIES__TtC13CoreIDVShared29IdentityProofingAnalyticsInfo
+ __DATA__TtC13CoreIDVShared29IdentityProofingAnalyticsInfo
+ __INSTANCE_METHODS__TtC13CoreIDVShared29IdentityProofingAnalyticsInfo
+ __IVARS__TtC13CoreIDVShared29IdentityProofingAnalyticsInfo
+ __METACLASS_DATA__TtC13CoreIDVShared29IdentityProofingAnalyticsInfo
+ __OBJC_CLASS_RO_$_DIPDeviceDetection
+ __OBJC_METACLASS_RO_$_DIPDeviceDetection
+ __PROTOCOLS__TtC13CoreIDVShared29IdentityProofingAnalyticsInfo
+ _associated conformance 13CoreIDVShared25CredentialOperationReasonOSHAASQ
+ _associated conformance 13CoreIDVShared25CredentialOperationReasonOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 13CoreIDVShared30IdentityProofingReferralSourceOSHAASQ
+ _symbolic Say_____G 13CoreIDVShared25CredentialOperationReasonO
+ _symbolic ScCy_____Sg_____G 13CoreIDVShared29IdentityProofingAnalyticsInfoC s5NeverO
+ _symbolic ScCy_____Sg______pG 13CoreIDVShared29IdentityProofingAnalyticsInfoC s5ErrorP
+ _symbolic _____ 13CoreIDVShared25CredentialOperationReasonO
+ _symbolic _____ 13CoreIDVShared29IdentityProofingAnalyticsInfoC
+ _symbolic _____ 13CoreIDVShared30IdentityProofingReferralSourceO
+ _symbolic _____Sg 13CoreIDVShared29IdentityProofingAnalyticsInfoC
+ _symbolic _____SgIeyBy_ 13CoreIDVShared29IdentityProofingAnalyticsInfoC
+ _symbolic ______p_____Sg______pIeghHnrzo_ 13CoreIDVShared28IdentityManagementUIProtocolP AA0C21ProofingAnalyticsInfoC s5ErrorP
- _symbolic ScCySSSg_____G s5NeverO
- _symbolic ScCySSSg______pG s5ErrorP
- _symbolic So8NSStringCSgIeyBy_
- _symbolic ______pSSSg______pIeghHnrzo_ 13CoreIDVShared28IdentityManagementUIProtocolP s5ErrorP
CStrings:
+ "CoreIDVShared.IdentityProofingAnalyticsInfo"
+ "account-logout"
+ "debug.inject-biome-fedstats-optin-age-days"
+ "debug.tap-to-radar-override-rate-limit"
+ "developer-test-mdl-deletion"
+ "fullProofingMigration"
+ "gc-incomplete-credential"
+ "gc-invalid-credential"
+ "identity-proofing-cleanup"
+ "idvtool-manual-deletion"
+ "nfc-payload-ingest"
+ "payload-replacement"
+ "pending-actions-hash-refresh"
+ "pii-reconciliation-orphan-cleanup"
+ "pii-reconciliation-restore"
+ "pii-reconciliation-stranded-hash-cleanup"
+ "precursorPassMigration"
+ "previousCardsMigration"
+ "proofing-session-expiry"
+ "proofing-session-user-cancelled"
+ "proofingReferralSource"
+ "provisioning-failure-phone"
+ "provisioning-failure-watch"
+ "provisioning-success-phone"
+ "provisioning-success-watch"
+ "wallet-user-delete"
```
