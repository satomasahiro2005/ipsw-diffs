## HealthKit

> `/System/Library/Frameworks/HealthKit.framework/HealthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x174bbc` | `0xd491c` | **`-0xa02a0`** |
| `__TEXT.__text` | `0x428120` | `0x42bdbc` | **`+0x3c9c`** |
| `__TEXT.__cstring` | `0x396a2` | `0x38892` | **`-0xe10`** |
| `__DATA_CONST.__const` | `0x109a8` | `0xffc0` | **`-0x9e8`** |
| `__DATA.__bss` | `0x341b0` | `0x347a0` | **`+0x5f0`** |
| `__TEXT.__eh_frame` | `0x8820` | `0x8be8` | **`+0x3c8`** |
| `__AUTH_CONST.__const` | `0x14c29` | `0x14d81` | **`+0x158`** |
| `__TEXT.__unwind_info` | `0x140d0` | `0x14228` | **`+0x158`** |
| `__TEXT.__oslogstring` | `0xdc23` | `0xdb53` | **`-0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x344e0` | `0x345a0` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x6144` | `0x61f0` | **`+0xac`** |
| `__TEXT.__swift5_typeref` | `0x58db` | `0x595b` | **`+0x80`** |
| `__AUTH.__objc_data` | `0xfea8` | `0xfe30` | **`-0x78`** |
| `__DATA_DIRTY.__objc_data` | `0x2798` | `0x2810` | **`+0x78`** |
| `__AUTH.__data` | `0x3928` | `0x3990` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x5888` | `0x58e8` | **`+0x60`** |
| `__DATA.__data` | `0x102e0` | `0x10330` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x16a8` | `0x16f0` | **`+0x48`** |
| `__DATA_DIRTY.__data` | `0x2d8` | `0x318` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x2070` | `0x20a8` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x567c0` | `0x567f0` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x1a38` | `0x1a68` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x3c4b` | `0x3c7b` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x32f94` | `0x32fb4` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x40bc` | `0x40d8` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x124e8` | `0x124f8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0xd68` | `0xd78` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x794` | `0x79c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3168` | `0x316c` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0xe0` | `0xe4` | **`+0x4`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 30777
-  Symbols:   37007
-  CStrings:  9339
+  Functions: 30859
+  Symbols:   37030
+  CStrings:  9024
Symbols:
+ +[HKFHIRIdentifier scopedResourceID:inHealthLinkNamespace:fullURL:]
+ -[HKImportExclusionDeviceDataSource isHKFeatureIdentifierOxygenSaturationRecordingCompanionAnalysisImportAllowedForActiveWatchWithDeviceType:serialNumber:]
+ -[_HKFeatureFlags medicalIdFollowUp]
+ -[_HKFeatureFlags setMedicalIdFollowUp:]
+ GCC_except_table124
+ GCC_except_table204
+ GCC_except_table209
+ _OBJC_IVAR_$__HKFeatureFlags._medicalIdFollowUp
+ __IsUsableHealthLinkResourceKey
+ __OBJC_$_CLASS_METHODS_HKImportExclusionDeviceDataSource(HKFeatureIdentifierOxygenSaturationRecordingAllowedDeviceSerialNumbers|HKFeatureIdentifierOxygenSaturationRecordingAllowedDeviceSerialNumbersTIB|HKFeatureIdentifierOxygenSaturationRecordingAllowedDeviceTypes)
+ ___36-[_HKFeatureFlags medicalIdFollowUp]_block_invoke
+ ___swift_memcpy457_8
+ ___swift_memcpy497_8
+ _associated conformance 9HealthKit12SleepMetricsV11PercentagesV10CodingKeys33_65F69B7C94FF40D3BED69B12AEA8F33FLLOSHAASQ
+ _associated conformance 9HealthKit12SleepMetricsV11PercentagesV10CodingKeys33_65F69B7C94FF40D3BED69B12AEA8F33FLLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 9HealthKit12SleepMetricsV11PercentagesV10CodingKeys33_65F69B7C94FF40D3BED69B12AEA8F33FLLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9HealthKit12SleepMetricsV11PercentagesVAA0C19PercentageProvidingAA16DurationProviderAaFP_AA0chG0
+ _associated conformance 9HealthKit12SleepMetricsV11PercentagesVSHAASQ
+ _associated conformance 9HealthKit12SleepMetricsVAA0C19PercentageProvidingAA16DurationProviderAaDP_AA0cgF0
+ _associated conformance 9HealthKit15SleepDaySummaryV7MetricsVAA0C19PercentageProvidingAA16DurationProviderAaFP_AA0ciH0
+ _kHKConnectedGymPreferencesNFCDetectionMode
+ _kHKMedicalIDFollowUpClientIdentifier
+ _kHKMedicalIDFollowUpReviewActionIdentifier
+ _kHKMedicalIDFollowUpUniqueIdentifier
+ _symbolic $s9HealthKit24SleepPercentageProvidingP
+ _symbolic 16DurationProvider_____Qz 9HealthKit24SleepPercentageProvidingP
+ _symbolic _____ 9HealthKit12SleepMetricsV11PercentagesV
+ _symbolic _____ 9HealthKit12SleepMetricsV11PercentagesV10CodingKeys33_65F69B7C94FF40D3BED69B12AEA8F33FLLO
+ _type_layout_string 9HealthKit12SleepMetricsV11PercentagesV
- +[HKImportExclusionDeviceDataSource(HKFeatureIdentifierOxygenSaturationRecordingCompanionAnalysisAllowedDeviceSerialNumbers) isDeviceSerialNumberOnAllowedListForHKFeatureIdentifierOxygenSaturationRecordingCompanionAnalysis:]
- -[HKImportExclusionDeviceDataSource isHKFeatureIdentifierOxygenSaturationRecordingCompanionAnalysisImportAllowedForActiveWatchWithSerialNumber:]
- GCC_except_table203
- __OBJC_$_CLASS_METHODS_HKImportExclusionDeviceDataSource(HKFeatureIdentifierOxygenSaturationRecordingAllowedDeviceSerialNumbers|HKFeatureIdentifierOxygenSaturationRecordingAllowedDeviceSerialNumbersTIB|HKFeatureIdentifierOxygenSaturationRecordingAllowedDeviceTypes|HKFeatureIdentifierOxygenSaturationRecordingCompanionAnalysisAllowedDeviceSerialNumbers)
- ___swift_memcpy449_8
- ___swift_memcpy489_8
CStrings:
+ "%@%@%@%@"
+ "ConnectedGymNFCDetectionMode"
+ "HealthKit/DiagnosticOutputEnvironment+Obfuscation.swift"
+ "Localizable-Assessments"
+ "com.apple.Health.MedicalID.FollowUp.ReviewAction"
+ "com.apple.Health.MedicalID.MedicalIDFollowUpExtension"
+ "com.apple.Health.MedicalID.reviewFollowUp"
+ "medical_id_follow_up"
+ "shl:"
- "230BOCKB0001"
- "230BOCKB0002"
- "230BOCKB0003"
- "230BOCKB0004"
- "230BOCKB0005"
- "230BOCKB0006"
- "230BOCKB0007"
- "230BOCKB0008"
- "230BOCKB0009"
- "230BOCKB0010"
- "230BOCKB0011"
- "230BOCKB0012"
- "230BOCKB0013"
- "230BOCKB0014"
- "230BOCKB0015"
- "230BOCKB0016"
- "230BOCKB0017"
- "230BOCKB0018"
- "230BOCKB0019"
- "230BOCKB0020"
- "230BOCKB0021"
- "230BOCKB0022"
- "230BOCKB0023"
- "230BOCKB0024"
- "230BOCKB0025"
- "230BOCKB0026"
- "230BOCKB0027"
- "230BOCKB0028"
- "230BOCKB0029"
- "230BOCKB0030"
- "230BOCKB0031"
- "230BOCKB0032"
- "230BOCKB0033"
- "230BOCKB0034"
- "230BOCKB0036"
- "230BOCKB0037"
- "230BOCKB0038"
- "230BOCKB0039"
- "230BOCKB0040"
- "230BOCKB0041"
- "230BOCKB0042"
- "230BOCKB0043"
- "230BOCKB0044"
- "230BOCKB0045"
- "230BOCKB0046"
- "230BOCKB0047"
- "230BOCKB0048"
- "230BOCKB0049"
- "230BOCKB0050"
- "230BOCKB0051"
- "230BOCKB0052"
- "230BOCKB0053"
- "230BOCKB0054"
- "230BOCKB0055"
- "230BOCKB0056"
- "230BOCKB0057"
- "230BOCKB0058"
- "230BOCKB0059"
- "230BOCKB0060"
- "230BOCKB0061"
- "230BOCKB0062"
- "230BOCKB0063"
- "230BOCKB0064"
- "230BOCKB0065"
- "230BOCKB0066"
- "230BOCKB0067"
- "230BOCKB0068"
- "230BOCKB0069"
- "230BOCKB0070"
- "230BOCKB0071"
- "230BOCKB0072"
- "230BOCKB0073"
- "230BOCKB0074"
- "230BOCKB0075"
- "230BOCKB0076"
- "230BOCKB0077"
- "230BOCKB0078"
- "230BOCKB0079"
- "230BOCKB0080"
- "230BOCKB0081"
- "230BOCKB0082"
- "230BOCKB0083"
- "230BOCKB0084"
- "230BOCKB0085"
- "230BOCKB0086"
- "230BOCKB0087"
- "230BOCKB0088"
- "230BOCKB0089"
- "230BOCKB0090"
- "230BOCKB0091"
- "230BOCKB0092"
- "230BOCKB0093"
- "230BOCKB0094"
- "230BOCKB0095"
- "230BOCKB0096"
- "230BOCKB0097"
- "230BOCKB0098"
- "230BOCKB0099"
- "230BOCKB0100"
- "230BOCKB0101"
- "230BOCKB0102"
- "230BOCKB0103"
- "230BOCKB0104"
- "230BOCKB0105"
- "230BOCKB0106"
- "230BOCKB0107"
- "230BOCKB0108"
- "230BOCKB0109"
- "230BOCKB0110"
- "230BOCKB0111"
- "230BOCKB0112"
- "230BOCKB0113"
- "230BOCKB0114"
- "230BOCKB0115"
- "230BOCKB0116"
- "230BOCKB0117"
- "230BOCKB0118"
- "230BOCKB0119"
- "230BOCKB0120"
- "230BOCKB0121"
- "230BOCKB0122"
- "230BOCKB0123"
- "230BOCKB0124"
- "230BOCKB0125"
- "230BOCKB0126"
- "230BOCKB0127"
- "230BOCKB0128"
- "230BOCKB0129"
- "230BOCKB0130"
- "230BOCKB0131"
- "230BOCKB0132"
- "230BOCKB0133"
- "230BOCKB0134"
- "230BOCKB0135"
- "230BOCKB0136"
- "230BOCKB0137"
- "230BOCKB0138"
- "230BOCKB0139"
- "230BOCKB0140"
- "230BOCKB0141"
- "230BOCKB0142"
- "230BOCKB0143"
- "230BOCKB0144"
- "230BOCKB0145"
- "230BOCKB0146"
- "230BOCKB0149"
- "230BOCKB0151"
- "230BOCKB0152"
- "230BOCKB0154"
- "230BOCKB0156"
- "230BOCKB0162"
- "230BOCKB0165"
- "230BOCKB0167"
- "230BOCKB0168"
- "230BOCKB0179"
- "230BOCKB0183"
- "230BOCKB0185"
- "230BOCKB0192"
- "230BOCKB0194"
- "230BOCKB0195"
- "230BOCKB0196"
- "230BOCKB0198"
- "230BOCKB0199"
- "230BOCKB0200"
- "230BOCKB0201"
- "230BOCKB0205"
- "230BOCKB0208"
- "230BOCKB0211"
- "230BOCKB0212"
- "230BOCKB0213"
- "230BOCKB0215"
- "230BOCKB0217"
- "230BOCKB0218"
- "230BOCKB0219"
- "230BOCKB0220"
- "230DCB0001"
- "230DCB0002"
- "230DCB0003"
- "230DCB0004"
- "230DCB0005"
- "230DCB0006"
- "230DCB0007"
- "230DCB0008"
- "230DCB0009"
- "230DCB0010"
- "230DCB0011"
- "230DCB0012"
- "230DCB0013"
- "230DCB0014"
- "230DCB0015"
- "230DCB0016"
- "230DCB0017"
- "230DCB0018"
- "230DCB0019"
- "230DCB0020"
- "230DCB0021"
- "230DCB0022"
- "230DCB0023"
- "230DCB0024"
- "230DCB0025"
- "230DCB0026"
- "230DCB0027"
- "230DCB0028"
- "230DCB0029"
- "230DCB0030"
- "230DCB0031"
- "230DCB0032"
- "230DCB0033"
- "230DCB0034"
- "230DCB0035"
- "230DCB0036"
- "230DCB0037"
- "230DCB0038"
- "230DCB0039"
- "230DCB0040"
- "230DCB0041"
- "230DCB0042"
- "230DCB0043"
- "230DCB0044"
- "230DCB0045"
- "230DCB0046"
- "230DCB0047"
- "230DCB0048"
- "230DCB0049"
- "230DCB0050"
- "230DCB0051"
- "230DCB0052"
- "230DCB0053"
- "230DCB0054"
- "230DCB0055"
- "230DCB0056"
- "230DCB0057"
- "230DCB0058"
- "230DCB0059"
- "230DCB0060"
- "230DCB0061"
- "230DCB0062"
- "230DCB0063"
- "230DCB0064"
- "230DCB0065"
- "230DCB0066"
- "230DCB0067"
- "230DCB0068"
- "230DCB0069"
- "230DCB0070"
- "230DCB0071"
- "230DCB0072"
- "230DCB0074"
- "230DCB0076"
- "230DCB0078"
- "230DCB0079"
- "230DCB0080"
- "230DCB0081"
- "230DCB0083"
- "230DCB0087"
- "230DCB0089"
- "230DCB0090"
- "230DCB0094"
- "230DCB0095"
- "230DCB0096"
- "230DCB0099"
- "230DCB0101"
- "230DCB0103"
- "230DCB0104"
- "230DCB0105"
- "230DCB0106"
- "230DCB0107"
- "230DCB0109"
- "230DCB0112"
- "230DCB0113"
- "230DCB0114"
- "230DCB0115"
- "230DCB0116"
- "230DCB0117"
- "230DCB0121"
- "230DCB0123"
- "230DCB0124"
- "230DCB0127"
- "230DCB0128"
- "230DCB0129"
- "230DCB0131"
- "230DCB0132"
- "230DCB0133"
- "230DCB0136"
- "230DCB0139"
- "230DCB0140"
- "230DCB0141"
- "230DCB0142"
- "230DCB0143"
- "230DCB0145"
- "230DCB0146"
- "230DCB0147"
- "230DCB0149"
- "230DCB0150"
- "230DCB0151"
- "230DCB0152"
- "230DCB0154"
- "230DCB0155"
- "230DCB0156"
- "230DCB0157"
- "230DCB0158"
- "230DCB0159"
- "230DCB0160"
- "230DCB0161"
- "230DCB0162"
- "230DCB0163"
- "230DCB0164"
- "230DCB0165"
- "230DCB0166"
- "230DCB0167"
- "230DCB0168"
- "230DCB0169"
- "230DCB0170"
- "230DCB0171"
- "230DCB0172"
- "230DCB0173"
- "230DCB0176"
- "230DCB0177"
- "230DCB0178"
- "230DCB0179"
- "230DCB0180"
- "Localizable-Mulberry"
- "[%{public}@] Active watch is not on the %{public}@ import allow list (serial number length %{public}lu)"
- "[%{public}@] Active watch serial number could not be read, so %{public}@ import is not allowed"
```
