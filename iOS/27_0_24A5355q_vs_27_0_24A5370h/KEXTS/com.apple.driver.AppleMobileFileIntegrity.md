## com.apple.driver.AppleMobileFileIntegrity

> `com.apple.driver.AppleMobileFileIntegrity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x10d0` | **`+0x10d0`** |
| `__DATA_CONST.__kalloc_var` | `0x1540` | `0x1400` | **`-0x140`** |
| `__TEXT_EXEC.__text` | `0x29a04` | `0x29aa8` | **`+0xa4`** |
| `__TEXT.__cstring` | `0xb803` | `0xb796` | **`-0x6d`** |

### Other Changes

```diff

-1166.0.0.0.0
+1171.0.3.0.0

-  CStrings:  1164
+  CStrings:  1162
Functions:
~ sub_fffffff0091e3b30 -> sub_fffffff009219310 : 104 -> 120
~ sub_fffffff0091e4d78 -> sub_fffffff00921a568 : 188 -> 184
~ sub_fffffff0091e4e34 -> sub_fffffff00921a620 : 184 -> 180
~ sub_fffffff0091e4eec -> sub_fffffff00921a6d4 : 164 -> 160
~ sub_fffffff0091e6870 -> sub_fffffff00921c054 : 140 -> 172
~ __ZN24AppleMobileFileIntegrity27submitAuxiliaryInfoAnalyticEP5vnodeP7cs_blob : 2044 -> 2036
~ __Z31entitlementAllowedByConstraintsPK24entitlement_constraint_tPKcP8OSObjectS3_ : 456 -> 488
~ __ZL25contextForConstraintArrayPKhm : 188 -> 184
~ sub_fffffff0091e9484 -> sub_fffffff00921ec9c : 176 -> 220
~ sub_fffffff0091ed570 -> sub_fffffff009222db4 : 104 -> 120
~ __Z26validateAndRegisterProfileR21ProfileValidationData : 536 -> 548
~ sub_fffffff0091f06f8 -> sub_fffffff009225f58 : 96 -> 108
~ sub_fffffff0091f1fd0 -> sub_fffffff00922783c : 152 -> 148
~ sub_fffffff0091f5384 -> sub_fffffff00922abec : 432 -> 428
~ __ZN11SystemFacts20resolveFactIfPresentE8CEBufferPb : 340 -> 336
~ __ZN22OSDetachedCertificates17withDetachedCertsEym11OSSharedPtrI6OSDataE : 380 -> 388
~ __ZN21AbstractVnodeAccessor20resolveFactIfPresentE8CEBufferPb : 296 -> 292
~ __Z16ValidateDenylistP16MISDenylistEntrym : 204 -> 228
~ sub_fffffff0091fbe30 -> sub_fffffff0092316ac : 676 -> 680
~ sub_fffffff0091fc24c -> sub_fffffff009231acc : 336 -> 332
~ sub_fffffff0091fc3a8 -> sub_fffffff009231c24 : 36 -> 32
~ sub_fffffff0091fc3cc -> sub_fffffff009231c44 : 36 -> 32
~ sub_fffffff0091fc444 -> sub_fffffff009231cb8 : 140 -> 168
~ sub_fffffff0091fcf54 -> sub_fffffff0092327e4 : 156 -> 160
~ sub_fffffff0091fde4c -> sub_fffffff0092336e0 : 448 -> 452
~ sub_fffffff0091fe954 -> sub_fffffff0092341ec : 492 -> 488
~ sub_fffffff009201960 -> sub_fffffff0092371f4 : 340 -> 336
~ __ZN3TLE21opArrayOpDeserializerERNS_8ExecutorER14der_vm_contextRKNS_14FactDefinitionE : 628 -> 636
~ sub_fffffff009201d28 -> sub_fffffff0092375c0 : 124 -> 140
~ ____ZN3TLE21opArrayOpDeserializerERNS_8ExecutorER14der_vm_contextRKNS_14FactDefinitionE_block_invoke : 1160 -> 1156
~ __ZN3TLE13keyForContextER14der_vm_context : 240 -> 236
~ __ZN3TLE15andDeserializerERNS_8ExecutorER14der_vm_contextRKNS_14FactDefinitionE : 424 -> 420
~ __ZN3TLE14orDeserializerERNS_8ExecutorER14der_vm_contextRKNS_14FactDefinitionE : 424 -> 420
~ __ZN3TLE22optionalOpDeserializerERNS_8ExecutorER14der_vm_contextRKNS_14FactDefinitionE : 372 -> 368
~ sub_fffffff0092029b4 -> sub_fffffff009238248 : 340 -> 336
~ __ZN3TLE8Executor29getDependentOpsFromDictionaryE14der_vm_contextRKNS_14FactDefinitionEbmPK8CEBuffer : 708 -> 724
~ ____ZN3TLE8Executor29getDependentOpsFromDictionaryE14der_vm_contextRKNS_14FactDefinitionEbmPK8CEBuffer_block_invoke : 2412 -> 2408
~ __ZN3TLE18factOpDeserializerERNS_8ExecutorER14der_vm_contextRKNS_14FactDefinitionE : 316 -> 312
~ __ZN3TLE8Executor19getOperationsFromCEEP14CEQueryContext : 428 -> 424
~ __ZN9os_detail21panic_trapping_policy4trapEPKc : 436 -> 432
~ sub_fffffff0092056e8 -> sub_fffffff00923af78 : 108 -> 124
~ sub_fffffff0092058d8 -> sub_fffffff00923b178 : 484 -> 480
~ sub_fffffff0092068a0 -> sub_fffffff00923c13c : 220 -> 216
~ _CESerializeXML : 2028 -> 2040
~ _string_value_allowed_iterate : 3104 -> 3088
~ _CEBuildIndexForContext : 680 -> 672
~ ___copy_keys_to_accelerator_block_invoke : 280 -> 276
~ _der_vm_execute_match_string : 260 -> 256
~ _der_vm_execute_match_string_prefix : 240 -> 236
~ _string_value_allowed_iterate : 356 -> 352
~ _string_prefix_allowed_iterate : 280 -> 276
~ ____ZN14OSEntitlements13createXMLBlobEv_block_invoke.cold.2 : 476 -> 488
CStrings:
+ "19:34:38"
+ "Jun 18 2026"
- "22:46:17"
- "May 27 2026"
- "site.ACMCredential.ACMCredentialDataPKITokenValidated"
- "site.ACMCredential.ACMCredentialDataPKITokenValidated2"
```
