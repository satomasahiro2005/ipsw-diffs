## com.apple.driver.AppleAOPAudio

> `com.apple.driver.AppleAOPAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x630` | **`+0x630`** |
| `__TEXT_EXEC.__text` | `0x2eee8` | `0x2efa0` | **`+0xb8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ __ZN23AppleAOPAudioPDM2Device22getMicTuningParametersEP9IOServiceRN21AppleAOPAudioFirmware19MicTuningParametersE : 1572 -> 1680
~ __ZN34AppleAOPAudioPCMAssetManagerDevice28processResourceUpdateRequestEP12OSDictionary : 1504 -> 1528
~ __ZN34AppleAOPAudioPCMAssetManagerDevice15checkDataPacketEPKvj : 600 -> 604
~ __ZN20AppleAOPAudioService25performCommandWithAddressEjN21AppleAOPAudioFirmware17ControllerCommand4TypeEPKvmPvPm : 752 -> 756
~ sub_fffffff008566964 -> sub_fffffff008572f80 : 420 -> 416
~ sub_fffffff008568d60 -> sub_fffffff008575378 : 456 -> 452
~ sub_fffffff0085744dc -> sub_fffffff008580af0 : 128 -> 136
~ sub_fffffff0085750e4 -> sub_fffffff008581700 : 48 -> 44
~ __ZN27AppleAOPAudioRingBufferImpl10FillBufferEPKhjyyb : 684 -> 688
~ sub_fffffff008575c50 -> sub_fffffff00858226c : 352 -> 348
~ __ZN29AppleAOPAudioAmpManagerDevice15getStatusReportEP12OSDictionary : 1736 -> 1732
~ __ZN35AppleAOPAudioFWdtAssetManagerDevice28processResourceUpdateRequestEP12OSDictionary : 1080 -> 1104
~ __ZN23AppleAOPAudioIOReporter14addIOReportersEP12OSDictionary : 1584 -> 1580
~ __ZN13AppleAOPAudio12PanicHandler26unRegisterMemoryForZeroOutEPh : 204 -> 224
~ sub_fffffff00857ba2c -> sub_fffffff008588068 : 100 -> 132
~ __ZN23AppleAOPAudioDeviceNode28_getIdentifersFromDeviceTreeEv : 700 -> 712
~ __ZN26AppleAOPAudioLPMicInDevice28initCodecConfigurationHandleEP9IOService : 416 -> 424
~ __ZN26AppleAOPAudioLPMicInDevice15getStatusReportEP12OSDictionary : 2880 -> 2828
~ __ZN26AppleAOPAudioLPMicInDevice17handleMailboxDataEPKhmyyy : 700 -> 704
~ __ZN38AppleAOPAudioPCMAssetManagerUserClient19UpdatePCMAudioAssetEP8OSObjectPvP25IOExternalMethodArguments : 316 -> 324
CStrings:
+ "19:34:03"
+ "19:34:04"
+ "Jun 18 2026"
- "21:03:49"
- "21:03:52"
- "Jun  3 2026"
```
