## HealthRecordsExtraction

> `/System/Library/PrivateFrameworks/HealthRecordsExtraction.framework/HealthRecordsExtraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x148020` | `0x156770` | **`+0xe750`** |
| `__DATA.__bss` | `0x199d0` | `0x1b950` | **`+0x1f80`** |
| `__TEXT.__const` | `0xd7a0` | `0xe550` | **`+0xdb0`** |
| `__TEXT.__eh_frame` | `0x71d4` | `0x7734` | **`+0x560`** |
| `__AUTH_CONST.__const` | `0xf720` | `0xfc68` | **`+0x548`** |
| `__TEXT.__swift5_fieldmd` | `0x3c78` | `0x40f8` | **`+0x480`** |
| `__TEXT.__unwind_info` | `0x4468` | `0x48d0` | **`+0x468`** |
| `__DATA.__data` | `0x2bf0` | `0x2ed0` | **`+0x2e0`** |
| `__AUTH.__data` | `0x1f58` | `0x21c0` | **`+0x268`** |
| `__TEXT.__constg_swiftt` | `0x22c0` | `0x2498` | **`+0x1d8`** |
| `__TEXT.__swift5_reflstr` | `0x1fec` | `0x215c` | **`+0x170`** |
| `__TEXT.__swift5_typeref` | `0x1b70` | `0x1cc0` | **`+0x150`** |
| `__AUTH_CONST.__auth_got` | `0x12f8` | `0x1428` | **`+0x130`** |
| `__TEXT.__swift5_proto` | `0xd54` | `0xe58` | **`+0x104`** |
| `__TEXT.__swift5_capture` | `0x618` | `0x528` | **`-0xf0`** |
| `__TEXT.__oslogstring` | `0x2761` | `0x2841` | **`+0xe0`** |
| `__DATA_CONST.__got` | `0xb20` | `0xba0` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x1918` | `0x1980` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x17dc` | `0x1824` | **`+0x48`** |
| `__TEXT.__cstring` | `0xc93c` | `0xc97c` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x5b8` | `0x5e8` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x4e0` | `0x510` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x330` | `0x360` | **`+0x30`** |
| `__AUTH.__objc_data` | `0xd38` | `0xd58` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x3f40` | `0x3f60` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x30d8` | `0x30f8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x2600` | `0x2618` | **`+0x18`** |
| `__DATA.__common` | `0x78` | `0x68` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x2f4` | `0x2f8` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x184` | `0x188` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x20c` | `0x210` | **`+0x4`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/Frameworks/UniformTypeIdentifiers.framework/UniformTypeIdentifiers

+  - /System/Library/PrivateFrameworks/HealthContent.framework/HealthContent

+  - /usr/lib/swift/libswiftIntents.dylib

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

+  - /usr/lib/swift/libswift_StringProcessing.dylib

-  Functions: 5792
-  Symbols:   2185
-  CStrings:  1319
+  Functions: 6160
+  Symbols:   2242
+  CStrings:  1325
Symbols:
+ -[HDHRSignedClinicalDataHandler decodeManifestOnContext:error:]
+ -[HDHRSignedClinicalDataHandler preprocessSMARTHealthLinkInSource:options:error:]
+ -[HDHRSignedClinicalDataHandler processJWEManifestFilesOnContext:error:]
+ _HKCoverageRecordTypeIdentifierCoverageRecord
+ _OBJC_CLASS_$_HDFHIRResourceData
+ ___79+[HKDiagnosticTestResult(ModelConversion) medicalRecordFromClinicalItem:error:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e25_16?0"HKMedicalCoding"8ls32l8s40l8
+ ___swift_closure_destructor.17Tm
+ ___swift_memcpy176_8
+ ___swift_project_boxed_opaque_existential_0Tm
+ ___swift_project_boxed_opaque_existential_2Tm
+ __objc_autoreleasePoolPop
+ __objc_autoreleasePoolPush
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_HealthRecordsExtraction
+ _associated conformance 23HealthRecordsExtraction15SMARTHealthLinkV10CodingKeys33_CBC9AE4A6B60D0FD0E2E09657BF3C420LLOSHAASQ
+ _associated conformance 23HealthRecordsExtraction15SMARTHealthLinkV10CodingKeys33_CBC9AE4A6B60D0FD0E2E09657BF3C420LLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 23HealthRecordsExtraction15SMARTHealthLinkV10CodingKeys33_CBC9AE4A6B60D0FD0E2E09657BF3C420LLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 23HealthRecordsExtraction19IndexableRecordType33_E1BA825B78A75045722E492A667BDC37LLOSHAASQ
+ _associated conformance 23HealthRecordsExtraction19IndexableRecordType33_E1BA825B78A75045722E492A667BDC37LLOs12CaseIterableAA8AllCasessAEP_Sl
+ _associated conformance 23HealthRecordsExtraction5MoneyV10CodingKeys33_A32A1D6789EE48168C8AC7E4A0AF34AELLOSHAASQ
+ _associated conformance 23HealthRecordsExtraction5MoneyV10CodingKeys33_A32A1D6789EE48168C8AC7E4A0AF34AELLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 23HealthRecordsExtraction5MoneyV10CodingKeys33_A32A1D6789EE48168C8AC7E4A0AF34AELLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 23HealthRecordsExtraction5MoneyVSHAASQ
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV0F5ClassV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOSHAASQ
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV0F5ClassV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV0F5ClassV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV0F5ClassVSHAASQ
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOSHAASQ
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOSHAASQ
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV9ExceptionV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOSHAASQ
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV9ExceptionV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOs0K3KeyAAs23CustomStringConvertible
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV9ExceptionV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLOs0K3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV9ExceptionVSHAASQ
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryVSHAASQ
+ _associated conformance 23HealthRecordsExtraction8ModelsR4V8CoverageVSHAASQ
+ _symbolic Say_____G 23HealthRecordsExtraction19IndexableRecordType33_E1BA825B78A75045722E492A667BDC37LLO
+ _symbolic Say_____G 23HealthRecordsExtraction9ReferenceV
+ _symbolic Say_____GSg 23HealthRecordsExtraction8ModelsR4V8CoverageV0F5ClassV
+ _symbolic Say_____GSg 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV
+ _symbolic Say_____GSg 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV9ExceptionV
+ _symbolic _____ 23HealthRecordsExtraction15SMARTHealthLinkV
+ _symbolic _____ 23HealthRecordsExtraction15SMARTHealthLinkV10CodingKeys33_CBC9AE4A6B60D0FD0E2E09657BF3C420LLO
+ _symbolic _____ 23HealthRecordsExtraction19IndexableRecordType33_E1BA825B78A75045722E492A667BDC37LLO
+ _symbolic _____ 23HealthRecordsExtraction29ClinicalDocumentTextExtractorV
+ _symbolic _____ 23HealthRecordsExtraction5MoneyV
+ _symbolic _____ 23HealthRecordsExtraction5MoneyV10CodingKeys33_A32A1D6789EE48168C8AC7E4A0AF34AELLO
+ _symbolic _____ 23HealthRecordsExtraction8ModelsR4V8CoverageV
+ _symbolic _____ 23HealthRecordsExtraction8ModelsR4V8CoverageV0F5ClassV
+ _symbolic _____ 23HealthRecordsExtraction8ModelsR4V8CoverageV0F5ClassV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLO
+ _symbolic _____ 23HealthRecordsExtraction8ModelsR4V8CoverageV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLO
+ _symbolic _____ 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV
+ _symbolic _____ 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLO
+ _symbolic _____ 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV9ExceptionV
+ _symbolic _____ 23HealthRecordsExtraction8ModelsR4V8CoverageV17CostToBeneficiaryV9ExceptionV10CodingKeys33_BCCFBB13C9A3B5346E48FA1DDA517FB6LLO
+ _symbolic _____Sg 23HealthRecordsExtraction5MoneyV
+ _type_layout_string 23HealthRecordsExtraction29ClinicalDocumentTextExtractorV
+ _type_layout_string 23HealthRecordsExtraction5MoneyV
+ _type_layout_string 23HealthRecordsExtraction8ModelsR4V8CoverageV0F5ClassV
- ___swift_closure_destructor.16Tm
- ___swift_memcpy168_8
- ___swift_project_boxed_opaque_existential_1Tm
- _symbolic _____ 23HealthRecordsExtraction14Base64URLErrorO
- _symbolic _____ 23HealthRecordsExtraction9Base64URLV
- _type_layout_string 23HealthRecordsExtraction14Base64URLErrorO
CStrings:
+ "*"
+ "@16@?0@\"HKMedicalCoding\"8"
+ "Ignoring ServiceRequest resource as they are unsupported"
+ "Manifest state should have been `.retrieved`. Returning context without processing."
+ "No version received for manifest file. Defaulting to R4"
+ "costToBeneficiary"
```
