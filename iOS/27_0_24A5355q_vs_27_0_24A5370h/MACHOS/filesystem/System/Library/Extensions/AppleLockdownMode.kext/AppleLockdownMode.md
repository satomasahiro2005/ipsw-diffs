## AppleLockdownMode

> `/System/Library/Extensions/AppleLockdownMode.kext/AppleLockdownMode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x15204` | `0x1506c` | **`-0x198`** |
| `__TEXT.__cstring` | `0x4a15` | `0x4892` | **`-0x183`** |
| `__DATA_CONST.__kalloc_var` | `0x15e0` | `0x14a0` | **`-0x140`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__kalloc_type`

### Other Changes

```diff

-122.0.0.0.0
+128.0.3.0.0

-  Symbols:   520
-  CStrings:  500
+  Symbols:   516
+  CStrings:  494
Symbols:
+ DeallocCredentialList.kalloc_type_view_1943
+ DeserializeCredentialList.kalloc_type_view_1905
+ LibCall_ACMContextLoadFromImage.kalloc_type_view_1570
+ LibCall_ACMContextLoadFromImage.kalloc_type_view_1631
+ Util_AllocCredential.kalloc_type_view_215
+ Util_AllocCredential.kalloc_type_view_221
+ Util_AllocCredential.kalloc_type_view_226
+ Util_AllocCredential.kalloc_type_view_231
+ Util_AllocCredential.kalloc_type_view_236
+ Util_AllocCredential.kalloc_type_view_242
+ Util_AllocCredential.kalloc_type_view_247
+ Util_AllocCredential.kalloc_type_view_268
+ Util_AllocCredential.kalloc_type_view_273
+ Util_AllocCredential.kalloc_type_view_286
+ Util_AllocRequirement.kalloc_type_view_338
+ Util_AllocRequirement.kalloc_type_view_343
+ Util_AllocRequirement.kalloc_type_view_348
+ Util_AllocRequirement.kalloc_type_view_353
+ Util_AllocRequirement.kalloc_type_view_358
+ Util_AllocRequirement.kalloc_type_view_363
+ Util_AllocRequirement.kalloc_type_view_368
+ Util_AllocRequirement.kalloc_type_view_373
+ Util_AllocRequirement.kalloc_type_view_378
+ Util_AllocRequirement.kalloc_type_view_383
+ Util_AllocRequirement.kalloc_type_view_388
+ Util_AllocRequirement.kalloc_type_view_401
+ Util_AllocRequirement.kalloc_type_view_408
+ Util_AllocRequirement.kalloc_type_view_416
+ Util_AllocRequirement.kalloc_type_view_429
+ Util_AllocRequirement.kalloc_type_view_434
+ Util_AllocRequirement.kalloc_type_view_439
+ Util_AllocRequirement.kalloc_type_view_444
+ Util_DeallocCredential.kalloc_type_view_155
+ Util_DeallocCredential.kalloc_type_view_159
+ Util_DeallocCredential.kalloc_type_view_164
+ Util_DeallocCredential.kalloc_type_view_168
+ Util_DeallocCredential.kalloc_type_view_172
+ Util_DeallocCredential.kalloc_type_view_176
+ Util_DeallocCredential.kalloc_type_view_180
+ Util_DeallocCredential.kalloc_type_view_192
+ Util_DeallocRequirement.kalloc_type_view_547
+ Util_DeallocRequirement.kalloc_type_view_551
+ Util_DeallocRequirement.kalloc_type_view_555
+ Util_DeallocRequirement.kalloc_type_view_559
+ Util_DeallocRequirement.kalloc_type_view_592
+ Util_DeallocRequirement.kalloc_type_view_597
+ Util_DeallocRequirement.kalloc_type_view_602
+ Util_DeallocRequirement.kalloc_type_view_614
+ Util_DeallocRequirement.kalloc_type_view_622
+ Util_DeallocRequirement.kalloc_type_view_626
- DeallocCredentialList.kalloc_type_view_1959
- DeserializeCredentialList.kalloc_type_view_1921
- LibCall_ACMContextLoadFromImage.kalloc_type_view_1619
- LibCall_ACMContextLoadFromImage.kalloc_type_view_1680
- Util_AllocCredential.kalloc_type_view_222
- Util_AllocCredential.kalloc_type_view_228
- Util_AllocCredential.kalloc_type_view_233
- Util_AllocCredential.kalloc_type_view_238
- Util_AllocCredential.kalloc_type_view_243
- Util_AllocCredential.kalloc_type_view_248
- Util_AllocCredential.kalloc_type_view_269
- Util_AllocCredential.kalloc_type_view_274
- Util_AllocCredential.kalloc_type_view_279
- Util_AllocCredential.kalloc_type_view_284
- Util_AllocCredential.kalloc_type_view_289
- Util_AllocCredential.kalloc_type_view_302
- Util_AllocRequirement.kalloc_type_view_354
- Util_AllocRequirement.kalloc_type_view_359
- Util_AllocRequirement.kalloc_type_view_364
- Util_AllocRequirement.kalloc_type_view_369
- Util_AllocRequirement.kalloc_type_view_374
- Util_AllocRequirement.kalloc_type_view_379
- Util_AllocRequirement.kalloc_type_view_384
- Util_AllocRequirement.kalloc_type_view_389
- Util_AllocRequirement.kalloc_type_view_399
- Util_AllocRequirement.kalloc_type_view_404
- Util_AllocRequirement.kalloc_type_view_410
- Util_AllocRequirement.kalloc_type_view_417
- Util_AllocRequirement.kalloc_type_view_432
- Util_AllocRequirement.kalloc_type_view_440
- Util_AllocRequirement.kalloc_type_view_445
- Util_AllocRequirement.kalloc_type_view_450
- Util_AllocRequirement.kalloc_type_view_455
- Util_AllocRequirement.kalloc_type_view_460
- Util_DeallocCredential.kalloc_type_view_154
- Util_DeallocCredential.kalloc_type_view_158
- Util_DeallocCredential.kalloc_type_view_162
- Util_DeallocCredential.kalloc_type_view_166
- Util_DeallocCredential.kalloc_type_view_171
- Util_DeallocCredential.kalloc_type_view_175
- Util_DeallocCredential.kalloc_type_view_179
- Util_DeallocCredential.kalloc_type_view_183
- Util_DeallocCredential.kalloc_type_view_187
- Util_DeallocCredential.kalloc_type_view_199
- Util_DeallocRequirement.kalloc_type_view_591
- Util_DeallocRequirement.kalloc_type_view_595
- Util_DeallocRequirement.kalloc_type_view_599
- Util_DeallocRequirement.kalloc_type_view_603
- Util_DeallocRequirement.kalloc_type_view_613
- Util_DeallocRequirement.kalloc_type_view_624
- Util_DeallocRequirement.kalloc_type_view_634
- Util_DeallocRequirement.kalloc_type_view_638
- Util_DeallocRequirement.kalloc_type_view_642
- Util_DeallocRequirement.kalloc_type_view_646
Functions:
~ _LibCall_ACMContextVerifyPolicyAndCopyRequirementEx : 1488 -> 1512
~ _LibCall_ACMCredentialSetProperty : 2748 -> 2684
~ _LibCall_ACMCredentialGetPropertyData : 1908 -> 1876
~ _processAclCommandInternal : 2536 -> 2528
~ _getLengthOfParameters : 372 -> 416
~ _SerializeVerifyPolicy : 752 -> 740
~ _serializeParameters : 452 -> 484
~ _deserializeParameters : 1020 -> 1016
~ _SerializeVerifyAclConstraint : 744 -> 728
~ _GetSerializedRequirementSize : 588 -> 580
~ _SerializeRequirement : 836 -> 828
~ _DeserializeCredential : 1476 -> 1380
~ sub_153b8 -> sub_15324 : 100 -> 92
~ sub_158a0 -> sub_15804 : 100 -> 92
~ _SerializeCredentialList : 416 -> 432
~ _LibSer_SEPControl_Deserialize : 352 -> 356
~ _Util_hexDumpToStrHelper : 76 -> 88
~ _Util_SafeDeallocParameters : 264 -> 288
~ _Util_DeallocCredential : 1416 -> 1280
~ sub_1a220 -> sub_1a12c : 100 -> 92
~ _Util_AllocCredential : 1340 -> 1212
~ sub_1a7c0 -> sub_1a644 : 100 -> 92
~ _Util_AllocRequirement : 2008 -> 2004
~ _Util_DeallocRequirement : 2064 -> 2048
CStrings:
+ "credential->type == kACMCredentialTypePasscodeValidated2"
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
- "credential->type == kACMCredentialTypePasscodeValidated2 || credential->type == kACMCredentialTypePKITokenValidated2"
- "dataLength == sizeof(ACMCredentialDataPKITokenValidated)"
- "dataLength == sizeof(ACMCredentialDataPKITokenValidated2)"
- "site.ACMCredential.ACMCredentialDataPKITokenValidated"
- "site.ACMCredential.ACMCredentialDataPKITokenValidated2"
```
