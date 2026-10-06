## libSavageUpdater_iOS.dylib

> `/usr/lib/updaters/libSavageUpdater_iOS.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dc18` | `0x1dddc` | **`+0x1c4`** |
| `__TEXT.__cstring` | `0x481c` | `0x4842` | **`+0x26`** |
| `__TEXT.__oslogstring` | `0xa3a` | `0xa60` | **`+0x26`** |
| `__TEXT.__unwind_info` | `0x4d8` | `0x4d0` | **`-0x8`** |

### Other Changes

```diff

-7.113.1.0.0
+7.114.0.0.0

-  Functions: 486
+  Functions: 485

-  CStrings:  631
+  CStrings:  632
Functions:
~ __ZN16YonkersIRxDevice11SetupDeviceEv : 440 -> 448
~ __ZN16YonkersIRxDevice20CreateDeviceInfoDictEP14__CFDictionaryj : 1736 -> 1748
~ __ZN26YonkersIRxUpdateControllerC2Ev : 220 -> 240
~ __ZN26YonkersIRxUpdateController29eventCmdQueryInfoPreflightingEv : 760 -> 752
~ __ZN26YonkersIRxUpdateController24eventCmdPerformNextStageEv : 3168 -> 3068
~ _OUTLINED_FUNCTION_0 : 12 -> 48
~ _OUTLINED_FUNCTION_1 : 48 -> 12
+ _OUTLINED_FUNCTION_5
- _OUTLINED_FUNCTION_5
~ _OUTLINED_FUNCTION_8 : 36 -> 32
- _OUTLINED_FUNCTION_9
~ __ZN13YonkersDevice11SetupDeviceEv : 448 -> 464
~ __ZN23YonkersUpdateController20getSignedCertificateEPhj : 2284 -> 2292
~ __ZN15JasmineIRDevice11SetupDeviceEv : 444 -> 440
~ __ZN25JasmineIRUpdateController14libFDRCallbackE18AMFDRCryptoVersionPK8__CFDataPS3_Pv : 380 -> 376
~ __ZN25JasmineIRUpdateController20formatAndStitchFilesEv : 1552 -> 1568
~ __ZN12SavageDevice11SetupDeviceEv : 448 -> 464
~ _GetYonkersFabRevisionTags : 308 -> 332
~ _GetYonkersIRFabRevisionTags : 140 -> 148
~ __ZN22SavageUpdateController14libFDRCallbackE18AMFDRCryptoVersionPK8__CFDataPS3_Pv : 380 -> 376
~ __ZN22SavageUpdateController17getFirmwareDigestEv : 332 -> 336
~ __ZN22SavageUpdateController20getSignedCertificateEPKhj : 1768 -> 1748
~ _decompressReferenceFrames : 5480 -> 5616
~ _checkSecureStreamingAndVerifySignatures : 488 -> 500
~ __ZN26YonkersIRxUpdateController5startEPK14__CFDictionary : 1624 -> 1700
~ __ZN26YonkersIRxUpdateController11execCommandEPK10__CFStringPK14__CFDictionaryPS5_ : 1016 -> 1156
~ __ZN26YonkersIRxUpdateController20formatAndStitchFilesEv : 1320 -> 1328
~ __ZN13YonkersDevice23CheckProvisioningStatusEv : 572 -> 580
~ __ZN13YonkersDevice20CreateDeviceInfoDictEP14__CFDictionary : 716 -> 724
~ __ZN23YonkersUpdateController20formatAndStitchFilesEv : 920 -> 924
~ __ZN15JasmineIRDevice20CreateDeviceInfoDictEP14__CFDictionary : 972 -> 996
~ __ZN25JasmineIRUpdateController20getSignedCertificateEPhj : 364 -> 360
~ _GetJasmineIRMeasurementTags : 512 -> 536
~ _GetYonkersIRxMeasurementTags : 628 -> 656
~ _GetYonkersIRMeasurementTags : 428 -> 432
~ __hexStringToBytes : 240 -> 252
~ __ZN22SavageUpdateController5startEPK14__CFDictionary : 1480 -> 1476
CStrings:
+ "Generating reference frames files...\n"
```
