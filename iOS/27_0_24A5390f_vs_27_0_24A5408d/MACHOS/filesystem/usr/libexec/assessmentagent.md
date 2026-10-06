## assessmentagent

> `/usr/libexec/assessmentagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x96250` | `0x9ccf0` | **`+0x6aa0`** |
| `__DATA_CONST.__const` | `0x79e8` | `0x8098` | **`+0x6b0`** |
| `__TEXT.__const` | `0x7f40` | `0x83c0` | **`+0x480`** |
| `__TEXT.__eh_frame` | `0x3bb4` | `0x3fa4` | **`+0x3f0`** |
| `__TEXT.__swift5_reflstr` | `0x379d` | `0x3a4d` | **`+0x2b0`** |
| `__DATA.__objc_const` | `0x54a0` | `0x5710` | **`+0x270`** |
| `__TEXT.__swift5_fieldmd` | `0x325c` | `0x34ac` | **`+0x250`** |
| `__DATA.__data` | `0x6b88` | `0x6db8` | **`+0x230`** |
| `__TEXT.__cstring` | `0x1c38` | `0x1e08` | **`+0x1d0`** |
| `__TEXT.__constg_swiftt` | `0x45d4` | `0x47a0` | **`+0x1cc`** |
| `__TEXT.__unwind_info` | `0x2230` | `0x23c0` | **`+0x190`** |
| `__DATA.__bss` | `0x54d0` | `0x5650` | **`+0x180`** |
| `__TEXT.__swift5_typeref` | `0x38fe` | `0x3a28` | **`+0x12a`** |
| `__TEXT.__objc_methname` | `0x36c9` | `0x37e9` | **`+0x120`** |
| `__TEXT.__swift5_capture` | `0xe24` | `0xf2c` | **`+0x108`** |
| `__TEXT.__objc_stubs` | `0x2440` | `0x2540` | **`+0x100`** |
| `__TEXT.__objc_classname` | `0x185b` | `0x18eb` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x1cc4` | `0x1d54` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x20d0` | `0x2140` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0xa90` | `0xac8` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x1078` | `0x10b0` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x880` | `0x8b8` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x2a8` | `0x2dc` | **`+0x34`** |
| `__DATA_CONST.__auth_ptr` | `0x9c0` | `0x9e8` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x1b0` | `0x1d8` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x158` | `0x180` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x324` | `0x348` | **`+0x24`** |
| `__TEXT.__swift5_proto` | `0x438` | `0x458` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x300` | `0x318` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x268` | `0x278` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0xc74` | `0xc84` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x14c` | `0x154` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0xcc` | `0xd0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-56.0.0.0.0
+56.0.3.0.0

+  - /System/Library/PrivateFrameworks/DeviceConfiguration.framework/DeviceConfiguration

-  Functions: 2876
-  Symbols:   946
-  CStrings:  1081
+  Functions: 2982
+  Symbols:   959
+  CStrings:  1107
Symbols:
+ _$s19DeviceConfiguration12UserProviderV6commit6storesySayAA5StoreVG_tYaKFZ
+ _$s19DeviceConfiguration12UserProviderV6commit6storesySayAA5StoreVG_tYaKFZTu
+ _$s19DeviceConfiguration12UserProviderV6delete8storeIDsySayAA15StoreIdentifierCG_tYaKFZ
+ _$s19DeviceConfiguration12UserProviderV6delete8storeIDsySayAA15StoreIdentifierCG_tYaKFZTu
+ _$s19DeviceConfiguration15StoreIdentifierC4name10providerIDACSS_SStcfc
+ _$s19DeviceConfiguration15StoreIdentifierCMa
+ _$s19DeviceConfiguration5StoreV09valuesForB2IDSDySSSDySSs8Sendable_pGGvs
+ _$s19DeviceConfiguration5StoreV7storeIDAcA0C10IdentifierC_tcfC
+ _$s19DeviceConfiguration5StoreV8isActiveSbvs
+ _$s19DeviceConfiguration5StoreVMa
+ _$s19DeviceConfiguration5StoreVMn
+ _$s7Combine10PublishersO6FilterVMa
+ _$s7Combine10PublishersO6FilterVy_xGAA9PublisherAAMc
+ _$s7Combine9PublisherPAAE6filteryAA10PublishersO6FilterVy_xGSb6OutputQzcF
+ _$s8Catalyst18CATAsyncSerializerC16PreEnqueueActionO14cancelAllTasksyA2EmFWC
+ _$s8Catalyst18CATAsyncSerializerC3run19respectingCancelAll10preEnqueue4name8priority_xSb_AC03PreI6ActionOSgSSSgScPSgxyYaKYAcntYaKs8SendableRzlF
+ _$s8Catalyst18CATAsyncSerializerC3run19respectingCancelAll10preEnqueue4name8priority_xSb_AC03PreI6ActionOSgSSSgScPSgxyYaKYAcntYaKs8SendableRzlFTu
+ _$sSS14_fromSubstringySSSshFZ
+ _$sSS5index5afterSS5IndexVAD_tF
+ _$sSSySJSS5IndexVcig
+ _$sSSySsSnySS5IndexVGcig
+ _$ss17__CocoaDictionaryV8IteratorC4nextyXl3key_yXl5valuetSgyF
+ _MCFeatureLiveVoicemailAllowed
+ _SecTaskCopyValueForEntitlement
+ _swift_projectBox
- _$sSD5IndexV8_asCocoas02__C10DictionaryVAAVvM
- _$sSD5IndexVMn
- _$ss10_HashTableV14occupiedBucket5afterAB0D0VAF_tF
- _$ss17__CocoaDictionaryV10startIndexAB0D0Vvg
- _$ss17__CocoaDictionaryV5IndexV10dictionaryABvg
- _$ss17__CocoaDictionaryV5IndexV16handleBitPatternSuvg
- _$ss17__CocoaDictionaryV5IndexV3ages5Int32Vvg
- _$ss17__CocoaDictionaryV5IndexV3keyyXlvg
- _$ss17__CocoaDictionaryV5countSivg
- _$ss17__CocoaDictionaryV5index5afterAB5IndexVAF_tF
- _$ss17__CocoaDictionaryV6lookupyyXl3key_yXl5valuetAB5IndexVF
- _$ss17__CocoaDictionaryV9formIndex5after8isUniqueyAB0D0Vz_SbtF
CStrings:
+ "$__lazy_storage_$_teamIdentifier"
+ "@\"<AEACancelable>\"40@0:8d16@\"NSObject<OS_dispatch_queue>\"24@?<v@?>32"
+ "AAC Accessibility Intelligence Store"
+ "AAC Visual Intelligence Store"
+ "Failed to commit device configuration store with error: %{public}s"
+ "Missing participants (unavailable executables): %{public}s"
+ "_TtC15assessmentagent40AEAConcreteDeviceConfigurationPrimitives"
+ "_TtC15assessmentagentP33_C9A2D2BFC7AE02E87E2ECAF32C861AFA31AEADeviceConfigurationAssertion"
+ "_allowsAccessibilityIntelligence"
+ "_allowsVisualIntelligence"
+ "allowAccessibilityAsk"
+ "allowVirtualMachine"
+ "allowVisualIntelligence"
+ "allowsForceQuit"
+ "application-identifier"
+ "com.apple.Accessibility"
+ "com.apple.AutomaticAssessmentConfiguration"
+ "com.apple.assessment.deviceConfiguration.commit"
+ "com.apple.assessment.deviceConfiguration.delete"
+ "com.apple.developer.team-identifier"
+ "com.apple.modelcatalog"
+ "configurationNetworkStateAntiphony"
+ "deviceConfiguration"
+ "executablePath"
+ "isAppleSigned"
+ "keyForValue"
+ "lastCommittedValuesByStore"
+ "shouldDeleteStores"
+ "signingIdentifier"
+ "useDeviceConfigurationProvider"
- "@\"<AEACancelable>\"40@0:8d16@\"OS_dispatch_queue\"24@?<v@?>32"
- "allowsNetworkAntiphony"
- "allowsNetworkSubscription"
- "codeDirectoryHash"
```
