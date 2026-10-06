## com.apple.driver.AppleFirmwareUpdateKext

> `com.apple.driver.AppleFirmwareUpdateKext`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x2500` | `0x25bc` | **`+0xbc`** |

### Other Changes

```text
Functions:
~ sub_fffffff008baa320 -> sub_fffffff008bfb8c0 : 72 -> 76
~ sub_fffffff008baa370 -> sub_fffffff008bfb914 : 52 -> 56
~ sub_fffffff008baa3a4 -> sub_fffffff008bfb94c : 52 -> 56
~ sub_fffffff008baa3e8 -> sub_fffffff008bfb994 : 68 -> 72
~ sub_fffffff008baa454 -> sub_fffffff008bfba04 : 72 -> 76
~ sub_fffffff008baa49c -> sub_fffffff008bfba50 : 104 -> 108
~ sub_fffffff008baa518 -> sub_fffffff008bfbad0 : 88 -> 92
~ sub_fffffff008baa570 -> sub_fffffff008bfbb2c : 88 -> 92
~ sub_fffffff008baa5c8 -> sub_fffffff008bfbb88 : 164 -> 168
~ __ZN23AppleFirmwareUpdateKext12initWithDataEP12OSDictionaryjPFiPv18FWValidationStatusjP6OSDataES2_b : 192 -> 196
~ sub_fffffff008baa72c -> sub_fffffff008bfbcf4 : 168 -> 172
~ __ZN23AppleFirmwareUpdateKext12loadFirmwareEP18IOMemoryDescriptor15FWSignatureTypej : 1212 -> 1216
~ __ZN23AppleFirmwareUpdateKext21validateFirmwareGatedEv : 668 -> 672
~ __ZN23AppleFirmwareUpdateKext18validationCompleteEP6OSData14Image4Return_t : 244 -> 248
~ sub_fffffff008bab0b4 -> sub_fffffff008bfc68c : 84 -> 88
~ sub_fffffff008bab108 -> sub_fffffff008bfc6e4 : 80 -> 84
~ __ZN23AppleFirmwareUpdateKext18registerForFDRDataEPvP7OSArrayPFiS0_18FWValidationStatusjP8OSStringP6OSDataE : 92 -> 96
~ __ZN23AppleFirmwareUpdateKext11loadFDRDataEP8OSStringP6OSData15FWSignatureTypej : 144 -> 148
~ sub_fffffff008bab30c -> sub_fffffff008bfc8f4 : 80 -> 84
~ sub_fffffff008bab3a4 -> sub_fffffff008bfc990 : 72 -> 76
~ sub_fffffff008bab3f4 -> sub_fffffff008bfc9e4 : 52 -> 56
~ sub_fffffff008bab428 -> sub_fffffff008bfca1c : 52 -> 56
~ sub_fffffff008bab46c -> sub_fffffff008bfca64 : 68 -> 72
~ sub_fffffff008bab4d8 -> sub_fffffff008bfcad4 : 72 -> 76
~ sub_fffffff008bab520 -> sub_fffffff008bfcb20 : 104 -> 108
~ sub_fffffff008bab59c -> sub_fffffff008bfcba0 : 88 -> 92
~ sub_fffffff008bab5f4 -> sub_fffffff008bfcbfc : 88 -> 92
~ __ZN29AppleFirmwareUpdateUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 328 -> 332
~ sub_fffffff008bab7a8 -> sub_fffffff008bfcdb8 : 124 -> 128
~ sub_fffffff008bab824 -> sub_fffffff008bfce38 : 76 -> 80
~ sub_fffffff008bab8ac -> sub_fffffff008bfcec4 : 80 -> 84
~ __ZN23AppleFirmwareUpdateKext5startEP9IOService : 428 -> 432
~ __ZN23AppleFirmwareUpdateKext14validateImage4Ev : 152 -> 156
~ __ZN23AppleFirmwareUpdateKext16validateFirmwareE15FWSignatureType : 292 -> 296
~ __ZN23AppleFirmwareUpdateKext23performCustomValidationEjPK12Img4Propertyj : 296 -> 300
~ __ZN23AppleFirmwareUpdateKext12loadFirmwareEP18IOMemoryDescriptor15FWSignatureTypej.cold.1 : 88 -> 92
~ __ZN23AppleFirmwareUpdateKext12loadFirmwareEP18IOMemoryDescriptor15FWSignatureTypej.cold.2 : 88 -> 92
~ __ZN23AppleFirmwareUpdateKext12loadFirmwareEP18IOMemoryDescriptor15FWSignatureTypej.cold.3 : 88 -> 92
~ __ZN23AppleFirmwareUpdateKext11loadFDRDataEP8OSStringP6OSData15FWSignatureTypej.cold.1 : 88 -> 92
~ __ZN23AppleFirmwareUpdateKext11loadFDRDataEP8OSStringP6OSData15FWSignatureTypej.cold.2 : 88 -> 92
~ __ZN23AppleFirmwareUpdateKext11loadFDRDataEP8OSStringP6OSData15FWSignatureTypej.cold.3 : 88 -> 92
~ __ZN23AppleFirmwareUpdateKext11loadFDRDataEP8OSStringP6OSData15FWSignatureTypej.cold.4 : 88 -> 92
~ __ZN23AppleFirmwareUpdateKext19loadFDRDataCompleteEv.cold.1 : 100 -> 104
~ __Z25AppleFirmwareDecodeImage4P6OSDatajP23AppleFirmwareUpdateKext : 408 -> 412
~ __ZN29AppleFirmwareUpdateUserClient6loadFWEyy15FWSignatureTypej : 144 -> 148
~ __ZN29AppleFirmwareUpdateUserClient11loadFDRDataEyyy15FWSignatureTypej : 1076 -> 1080
~ sub_fffffff008bac7d8 -> sub_fffffff008bfde30 : 72 -> 76
```
