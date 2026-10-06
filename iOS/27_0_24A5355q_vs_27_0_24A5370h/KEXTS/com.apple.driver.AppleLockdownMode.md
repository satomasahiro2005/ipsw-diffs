## com.apple.driver.AppleLockdownMode

> `com.apple.driver.AppleLockdownMode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x220` | **`+0x220`** |
| `__TEXT_EXEC.__text` | `0x15204` | `0x1506c` | **`-0x198`** |
| `__TEXT.__cstring` | `0x4a15` | `0x4892` | **`-0x183`** |
| `__DATA_CONST.__kalloc_var` | `0x15e0` | `0x14a0` | **`-0x140`** |

### Other Changes

```diff

-122.0.0.0.0
+128.0.3.0.0

-  CStrings:  500
+  CStrings:  494
Functions:
~ _LibCall_ACMContextVerifyPolicyAndCopyRequirementEx : 1488 -> 1512
~ _LibCall_ACMCredentialSetProperty : 2748 -> 2684
~ _LibCall_ACMCredentialGetPropertyData : 1908 -> 1876
~ _processAclCommandInternal : 2536 -> 2528
~ _getLengthOfParameters : 372 -> 416
~ sub_fffffff009043914 -> sub_fffffff009072630 : 752 -> 740
~ _serializeParameters : 452 -> 484
~ _deserializeParameters : 1020 -> 1016
~ sub_fffffff009044770 -> sub_fffffff00907349c : 744 -> 728
~ sub_fffffff009045a40 -> sub_fffffff00907475c : 588 -> 580
~ _SerializeRequirement : 836 -> 828
~ _DeserializeCredential : 1476 -> 1380
~ sub_fffffff009046db8 -> sub_fffffff009075a64 : 100 -> 92
~ sub_fffffff0090472a0 -> sub_fffffff009075f44 : 100 -> 92
~ _SerializeCredentialList : 416 -> 432
~ _LibSer_SEPControl_Deserialize : 352 -> 356
~ _Util_hexDumpToStrHelper : 76 -> 88
~ sub_fffffff00904b590 -> sub_fffffff00907a24c : 264 -> 288
~ _Util_AllocCredential : 1416 -> 1280
~ sub_fffffff00904bc20 -> sub_fffffff00907a86c : 100 -> 92
~ sub_fffffff00904bc84 -> sub_fffffff00907a8c8 : 1340 -> 1212
~ sub_fffffff00904c1c0 -> sub_fffffff00907ad84 : 100 -> 92
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
