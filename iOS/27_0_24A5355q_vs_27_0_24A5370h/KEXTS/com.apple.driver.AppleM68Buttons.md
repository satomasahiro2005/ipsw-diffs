## com.apple.driver.AppleM68Buttons

> `com.apple.driver.AppleM68Buttons`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x4d0` | **`+0x4d0`** |
| `__TEXT_EXEC.__text` | `0x1d22c` | `0x1d09c` | **`-0x190`** |
| `__TEXT.__cstring` | `0x4ffc` | `0x4e79` | **`-0x183`** |
| `__DATA_CONST.__kalloc_var` | `0x15e0` | `0x14a0` | **`-0x140`** |

### Other Changes

```diff

-  CStrings:  634
+  CStrings:  628
Functions:
~ _panic : 6064 -> 6060
~ __ZN15AppleM68Buttons23_initDiagnosticKeychordEP9IOService : 536 -> 512
~ __ZN15AppleM68Buttons15_updateTrumpMapEv : 424 -> 416
~ sub_fffffff009187e7c -> sub_fffffff0091bb678 : 60 -> 56
~ __ZN15AppleM68Buttons13setPowerStateEmP9IOService : 872 -> 868
~ __ZN15AppleM68Buttons24_forcedShutdownDebugInitEv : 1632 -> 1616
~ sub_fffffff009189040 -> sub_fffffff0091bc824 : 68 -> 64
~ sub_fffffff009189334 -> sub_fffffff0091bcb14 : 224 -> 244
~ __ZN15AppleM68Buttons14_reportButtonsEyb : 424 -> 464
~ sub_fffffff009189b6c -> sub_fffffff0091bd388 : 120 -> 116
~ __ZN15AppleM68Buttons20_dispatchButtonEventEyibbb : 2060 -> 2056
~ __ZN15AppleM68Buttons29_shutdownNVRAMSyncTimerActionEP18IOTimerEventSource : 328 -> 340
~ _LibCall_ACMContextVerifyPolicyAndCopyRequirementEx : 1488 -> 1512
~ _LibCall_ACMCredentialSetProperty : 2748 -> 2684
~ _LibCall_ACMCredentialGetPropertyData : 1908 -> 1876
~ _processAclCommandInternal : 2536 -> 2528
~ _getLengthOfParameters : 372 -> 416
~ sub_fffffff009195db8 -> sub_fffffff0091c95b4 : 752 -> 740
~ _serializeParameters : 452 -> 484
~ _deserializeParameters : 1020 -> 1016
~ sub_fffffff009196c14 -> sub_fffffff0091ca420 : 744 -> 728
~ sub_fffffff009197ee4 -> sub_fffffff0091cb6e0 : 588 -> 580
~ _SerializeRequirement : 836 -> 828
~ _DeserializeCredential : 1476 -> 1380
~ sub_fffffff00919925c -> sub_fffffff0091cc9e8 : 100 -> 92
~ sub_fffffff009199744 -> sub_fffffff0091ccec8 : 100 -> 92
~ _SerializeCredentialList : 416 -> 432
~ _LibSer_SEPControl_Deserialize : 352 -> 356
~ _Util_hexDumpToStrHelper : 76 -> 88
~ sub_fffffff00919da34 -> sub_fffffff0091d11d0 : 264 -> 288
~ _Util_AllocCredential : 1416 -> 1280
~ sub_fffffff00919e0c4 -> sub_fffffff0091d17f0 : 100 -> 92
~ sub_fffffff00919e128 -> sub_fffffff0091d184c : 1340 -> 1212
~ sub_fffffff00919e664 -> sub_fffffff0091d1d08 : 100 -> 92
~ _Util_AllocRequirement : 2008 -> 2004
~ sub_fffffff00919eff4 -> sub_fffffff0091d268c : 2064 -> 2048
~ __ZN15AppleM68Buttons17_updatePropertiesEP8OSObject : 656 -> 664
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
