## CoreIDVShared

> `/System/Library/PrivateFrameworks/CoreIDVShared.framework/CoreIDVShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x240d10` | `0x241430` | **`+0x720`** |
| `__TEXT.__cstring` | `0x16727` | `0x169fe` | **`+0x2d7`** |
| `__DATA_DIRTY.__data` | `0x3120` | `0x33b0` | **`+0x290`** |
| `__DATA_CONST.__objc_arraydata` | `0x250` | `0x10` | **`-0x240`** |
| `__AUTH_CONST.__objc_dictobj` | `0x230` | `0x28` | **`-0x208`** |
| `__TEXT.__swift5_reflstr` | `0x14506` | `0x14706` | **`+0x200`** |
| `__AUTH_CONST.__const` | `0x16c90` | `0x16e78` | **`+0x1e8`** |
| `__DATA_DIRTY.__bss` | `0x1380` | `0x1500` | **`+0x180`** |
| `__DATA.__data` | `0x6ff0` | `0x6e88` | **`-0x168`** |
| `__TEXT.__const` | `0x2d644` | `0x2d7a4` | **`+0x160`** |
| `__AUTH.__data` | `0x1748` | `0x1618` | **`-0x130`** |
| `__TEXT.__oslogstring` | `0x4800` | `0x4930` | **`+0x130`** |
| `__TEXT.__swift_as_cont` | `0xa3c` | `0x944` | **`-0xf8`** |
| `__TEXT.__swift5_fieldmd` | `0xce18` | `0xced0` | **`+0xb8`** |
| `__TEXT.__constg_swiftt` | `0x6b6c` | `0x6bd8` | **`+0x6c`** |
| `__TEXT.__eh_frame` | `0xf120` | `0xf188` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x6a00` | `0x6a60` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xdb0` | `0xe10` | **`+0x60`** |
| `__DATA_DIRTY.__objc_data` | `0x2c48` | `0x2ca8` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x2018` | `0x2050` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x6f06` | `0x6ed6` | **`-0x30`** |
| `__TEXT.__unwind_info` | `0x93a0` | `0x9378` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x2240` | `0x2220` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0xee8` | `0xf00` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xa78` | `0xa68` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x193c` | `0x1948` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xb28` | `0xb20` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x9c0` | `0x9c4` | **`+0x4`** |

### Other Changes

```diff

-9.34.0.0.0
+9.36.0.0.0

-  Symbols:   4065
-  CStrings:  2607
+  Symbols:   4070
+  CStrings:  2625
Symbols:
+ _associated conformance 13CoreIDVShared13IDCSAnalyticsC26PIIReconciliationEventTypeOSHAASQ
+ _kAKSKeyOpAttest
+ _kAKSKeyOpComputeKey
+ _kAKSKeyOpDecrypt
+ _kAKSKeyOpDelete
+ _kAKSKeyOpEncrypt
+ _kAKSKeyOpSign
+ _keypath_get.102Tm
+ _keypath_get.108Tm
+ _keypath_get.116Tm
+ _keypath_get.136Tm
+ _keypath_get.98Tm
+ _keypath_set.103Tm
+ _keypath_set.109Tm
+ _keypath_set.173Tm
+ _symbolic _____ 13CoreIDVShared13IDCSAnalyticsC26PIIReconciliationEventTypeO
- ___kCFBooleanFalse
- _keypath_get.100Tm
- _keypath_get.106Tm
- _keypath_get.114Tm
- _keypath_get.96Tm
- _keypath_set.101Tm
- _keypath_set.107Tm
- _keypath_set.165Tm
- _symbolic _____ySSSaySSGG s18_DictionaryStorageC
- _symbolic yp3key_yp5valuet
- _symbolic yp3key_yp5valuetSg
CStrings:
+ "\ntextUnderstandingDuration: "
+ "\ntextUnderstandingErrorCode: "
+ "\ntextUnderstandingFuzzyMatch: "
+ "%s timesUsed = %{public}ld, selectionReasonRawValue = %{public}ld, totalUsableKeysCount = %{public}ld, documentType = %{public}s, issuingJurisdiction = %{public}s, issuingAuthority = %{public}s"
+ "ACL does not contain valid cbio constraint dictionary"
+ "addBiometricStockholmAppRequiredConstraint(toACL:)"
+ "com.apple.idcredd.piiReconciliation"
+ "com.apple.idcredd.presentment.deviceKeyReuse"
+ "debug.enable-text-understanding-verbose-logging"
+ "modifySigningOperationConstraints(_:)"
+ "orphanedPIIBackup"
+ "restoredPIIHash"
+ "restoredPIIToken"
+ "sendDeviceKeyReuseEvent(timesUsed:selectionReasonRawValue:totalUsableKeysCount:documentType:issuingJurisdiction:issuingAuthority:)"
+ "sendPIIReconciliationEvent eventType = %s, count = %ld"
+ "sendPIIReconciliationEvent not recording event because count is zero"
+ "strandedPIIHash"
+ "totalUsableKeysCount"
+ "unrecoverablePIIHash"
+ "unrecoverablePIIToken"
- "Dictionary entitlement %s has an invalid value"
- "addCredentialMaxAge(_:toACL:)"
```
