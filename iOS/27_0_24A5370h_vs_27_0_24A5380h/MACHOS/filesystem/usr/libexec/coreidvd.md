## coreidvd

> `/usr/libexec/coreidvd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e7e0c` | `0x6f45cc` | **`+0xc7c0`** |
| `__TEXT.__oslogstring` | `0x2dbd9` | `0x2e979` | **`+0xda0`** |
| `__DATA_CONST.__const` | `0x24490` | `0x24f00` | **`+0xa70`** |
| `__DATA.__bss` | `0x37db0` | `0x38530` | **`+0x780`** |
| `__TEXT.__eh_frame` | `0x475c0` | `0x47c28` | **`+0x668`** |
| `__TEXT.__const` | `0x32460` | `0x32a00` | **`+0x5a0`** |
| `__TEXT.__cstring` | `0x2a480` | `0x2a7c0` | **`+0x340`** |
| `__DATA.__data` | `0x17fe0` | `0x182c8` | **`+0x2e8`** |
| `__TEXT.__swift5_fieldmd` | `0xe3ac` | `0xe5b8` | **`+0x20c`** |
| `__TEXT.__swift5_reflstr` | `0xbf1e` | `0xc11e` | **`+0x200`** |
| `__TEXT.__unwind_info` | `0x15f20` | `0x16098` | **`+0x178`** |
| `__DATA.__objc_const` | `0x115b8` | `0x11710` | **`+0x158`** |
| `__TEXT.__swift5_typeref` | `0xbfcc` | `0xc10a` | **`+0x13e`** |
| `__TEXT.__auth_stubs` | `0xd1f0` | `0xd320` | **`+0x130`** |
| `__TEXT.__constg_swiftt` | `0xd944` | `0xda68` | **`+0x124`** |
| `__TEXT.__objc_methname` | `0xda56` | `0xdb36` | **`+0xe0`** |
| `__DATA_CONST.__got` | `0x4208` | `0x42b8` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x6fc0` | `0x7060` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x6384` | `0x6424` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x6908` | `0x69a0` | **`+0x98`** |
| `__DATA_CONST.__auth_ptr` | `0x2388` | `0x2410` | **`+0x88`** |
| `__TEXT.__swift5_assocty` | `0xbe0` | `0xc58` | **`+0x78`** |
| `__TEXT.__objc_classname` | `0x368e` | `0x36ce` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x1df0` | `0x1e30` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x2570` | `0x2598` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x2bc` | `0x2e4` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x1c1c` | `0x1c40` | **`+0x24`** |
| `__TEXT.__swift_as_entry` | `0x12f8` | `0x1314` | **`+0x1c`** |
| `__TEXT.__swift5_types` | `0xc14` | `0xc2c` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x37c8` | `0x37e0` | **`+0x18`** |
| `__DATA.__common` | `0x732` | `0x722` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x728` | `0x730` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-9.34.0.0.0
+9.36.0.0.0

+  - /System/Library/Frameworks/IOSurface.framework/IOSurface

+  - /System/Library/PrivateFrameworks/CoreUtils.framework/CoreUtils

+  - /System/Library/PrivateFrameworks/TextUnderstanding.framework/TextUnderstanding

-  Functions: 18756
-  Symbols:   5919
-  CStrings:  8476
+  Functions: 18844
+  Symbols:   5967
+  CStrings:  8542
Symbols:
+ _$s10Foundation14DateComponentsV5monthSiSgvg
+ _$s13CoreIDVShared19ImageQualityMetricsC25textUnderstandingDurationSdSgvgTj
+ _$s13CoreIDVShared19ImageQualityMetricsC25textUnderstandingDurationSdSgvsTj
+ _$s13CoreIDVShared19ImageQualityMetricsC26textUnderstandingErrorCodeSiSgvgTj
+ _$s13CoreIDVShared19ImageQualityMetricsC26textUnderstandingErrorCodeSiSgvsTj
+ _$s13CoreIDVShared19ImageQualityMetricsC27textUnderstandingFuzzyMatchAA0hI10AssessmentCSgvgTj
+ _$s13CoreIDVShared19ImageQualityMetricsC27textUnderstandingFuzzyMatchAA0hI10AssessmentCSgvsTj
+ _$s13CoreIDVShared20FuzzyMatchAssessmentC9firstName04lastG05state11houseNumber6street3dob10postalCodeACSiSg_A6Ktcfc
+ _$s13CoreIDVShared20FuzzyMatchAssessmentCMa
+ _$s13CoreIDVShared20FuzzyMatchAssessmentCMn
+ _$s13CoreIDVShared23NSXPCConnectionProtocolP5value17forEntitlementKeyypSgSS_tFTj
+ _$s13CoreIDVShared26DaemonInternalDefaultsKeysO37enableTextUnderstandingVerboseLoggingSSvgZ
+ _$s13CoreIDVShared36IdentityProofingPrecursorPassMessageCMn
+ _$s13CoreIDVShared8DIPErrorV4CodeO31failedToGenerateKeyAttestationsyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO33failedToGenerateKAKAuthorizationsyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO36watchSessionPairingIDMismatchAtSetupyA2EmFWC
+ _$s13CoreIDVShared8DIPErrorV4CodeO37watchSessionPairingIDMismatchAtPrearmyA2EmFWC
+ _$s17TextUnderstanding0A17ProcessingServiceC7process8document8requests7optionsAA0C6ResultVAA8DocumentO_ShyAA7RequestOGAA7OptionsVtYaKFTjTu
+ _$s17TextUnderstanding0A17ProcessingServiceCACycfc
+ _$s17TextUnderstanding0A17ProcessingServiceCMa
+ _$s17TextUnderstanding13DocumentFlagsVMa
+ _$s17TextUnderstanding13DocumentFlagsVMn
+ _$s17TextUnderstanding13DocumentFlagsVs10SetAlgebraAAMc
+ _$s17TextUnderstanding16ProcessingResultV23identificationDocumentsSayAA22IdentificationDocumentVGvg
+ _$s17TextUnderstanding16ProcessingResultVMa
+ _$s17TextUnderstanding19DocumentIdentifiersV16bundleIdentifier06domainF006uniqueF0ACSS_SSSgSStcfC
+ _$s17TextUnderstanding19DocumentIdentifiersVMa
+ _$s17TextUnderstanding22IdentificationDocumentV10cardNumberSSSgvg
+ _$s17TextUnderstanding22IdentificationDocumentV14expirationDate10Foundation0F10ComponentsVSgvg
+ _$s17TextUnderstanding22IdentificationDocumentV4KindOMa
+ _$s17TextUnderstanding22IdentificationDocumentV4KindOMn
+ _$s17TextUnderstanding22IdentificationDocumentV6regionSSSgvg
+ _$s17TextUnderstanding22IdentificationDocumentV7countrySSSgvg
+ _$s17TextUnderstanding22IdentificationDocumentV7subjectAA7ContactVSgvg
+ _$s17TextUnderstanding22IdentificationDocumentV9issueDate10Foundation0F10ComponentsVSgvg
+ _$s17TextUnderstanding22IdentificationDocumentVMa
+ _$s17TextUnderstanding5ImageV14RepresentationO7surfaceyAESo9IOSurfaceCcAEmFWC
+ _$s17TextUnderstanding5ImageV14RepresentationOMa
+ _$s17TextUnderstanding5ImageV19documentIdentifiers0D5Flags14representation03ocrA0AcA08DocumentE0V_AA0iF0VAC14RepresentationOSSSgtcfC
+ _$s17TextUnderstanding5ImageVMa
+ _$s17TextUnderstanding7ContactV12LabeledValueV5valuexvg
+ _$s17TextUnderstanding7ContactV12LabeledValueVMn
+ _$s17TextUnderstanding7ContactV15postalAddressesSayAC12LabeledValueVy_AA8LocationV7AddressVGGvg
+ _$s17TextUnderstanding7ContactV4nameSSSgvg
+ _$s17TextUnderstanding7ContactVMa
+ _$s17TextUnderstanding7ContactVMn
+ _$s17TextUnderstanding7OptionsV27onBehalfOfProcessIdentifier9persistTo8useCacheACs5Int32VSg_ShyAA22PersistenceDestinationOGSbtcfC
+ _$s17TextUnderstanding7OptionsVMa
+ _$s17TextUnderstanding7RequestO23identificationDocumentsyA2C014IdentificationE7OptionsVcACmFWC
+ _$s17TextUnderstanding7RequestO30IdentificationDocumentsOptionsV26identificationDocumentKindAeA0dH0V0I0OSg_tcfC
+ _$s17TextUnderstanding7RequestOMa
+ _$s17TextUnderstanding7RequestOMn
+ _$s17TextUnderstanding7RequestOSHAAMc
+ _$s17TextUnderstanding7RequestOSQAAMc
+ _$s17TextUnderstanding8DocumentO5imageyAcA5ImageVcACmFWC
+ _$s17TextUnderstanding8DocumentOMa
+ _$s17TextUnderstanding8LocationV7AddressV04fullD0SSSgvg
+ _$s17TextUnderstanding8LocationV7AddressV6regionSSSgvg
+ _$s17TextUnderstanding8LocationV7AddressVMa
+ _$s17TextUnderstanding8LocationV7AddressVMn
+ _$s7Network10NWListenerC7ServiceV5ScopeV8personalAGvgZ
+ _$s7Network10NWListenerC7ServiceV5ScopeVMa
+ _$s7Network10NWListenerC7ServiceV5ScopeVMn
+ _$s7Network10NWListenerC7ServiceV5ScopeVs10SetAlgebraAAMc
+ _$s7Network10NWListenerC7ServiceV5scopeAE5ScopeVvs
+ _$sSDyxq_GSlsMc
+ _$sSis7CVarArgsWP
+ _$ss6UInt32VN
+ _CFAbsoluteTimeGetCurrent
+ _CGAffineTransformMakeScale
+ _CGColorSpaceCreateWithName
+ _CGRectGetHeight
+ _CGRectGetWidth
+ _IOSurfacePropertyKeyBytesPerElement
+ _IOSurfacePropertyKeyHeight
+ _IOSurfacePropertyKeyPixelFormat
+ _IOSurfacePropertyKeyWidth
+ _LevenshteinDistance
+ _OBJC_CLASS_$_IOSurface
+ _kCGColorSpaceSRGB
+ _kCIContextWorkingColorSpace
+ _swift_task_localValuePop
+ _swift_task_localValuePush
- _$s11Distributed0A5ActorP15unownedExecutorScevgTj
- _$s13CoreIDVShared23NSXPCConnectionProtocolP10isEntitledySbSSFTj
- _$s13CoreIDVShared30ISO18013_5_1_ElementIdentifierO12ageBirthYearyA2CmFWC
- _$s13CoreIDVShared30ISO18013_5_1_ElementIdentifierO8rawValueACSgSS_tcfC
- _$s13CoreIDVShared32ISO18013_AAMVA_ElementIdentifierO13raceEthnicityyA2CmFWC
- _$s13CoreIDVShared32ISO18013_AAMVA_ElementIdentifierO8rawValueACSgSS_tcfC
- _$s7CoreIDV27IdentityElementRawValueKeysC11dateOfBirthSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC11nationalitySSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC12placeOfBirthSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC13veteranStatusSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC14documentNumberSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC16issuingAuthoritySSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC16organDonorStatusSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC17documentIssueDateSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC17drivingPrivilegesSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC18signatureUsualMarkSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC22documentExpirationDateSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC24dhsTemporaryLawfulStatusSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC27documentDHSComplianceStatusSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC3ageSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC3sexSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC6heightSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC6weightSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC7addressSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC8eyeColorSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC8portraitSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC9ageIsOverySSSiFZ
- _$s7CoreIDV27IdentityElementRawValueKeysC9givenNameSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysC9hairColorSSvgZ
- _$s7CoreIDV27IdentityElementRawValueKeysCMa
- _$sSo15NSXPCConnectionC13CoreIDVSharedE10isEntitledySbSSF
- _$sSo15NSXPCConnectionC13CoreIDVSharedE19getArrayEntitlement4nameSaySSGSgSS_tF
- _$sSo15NSXPCConnectionC13CoreIDVSharedE38getDictionaryOfStringArraysEntitlement4nameSDySSSaySSGGSgSS_tF
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlF
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlFTu
CStrings:
+ "ADD_DEVICE"
+ "Error pairingID mismatch"
+ "FULL"
+ "Failed to convert image data to IOSurface for TextUnderstanding"
+ "Failed to fetch device confidence assessment"
+ "Failed to generate KAK authorizations"
+ "Failed to generate device attestations"
+ "IdentityProofingDatabaseProvider failed to set precursorPass message with error: %@"
+ "IdentityProofingDatabaseProvider no proofing session exists for: %{public}s"
+ "IdentityProofingDatabaseProvider set proofing error message to associated session: %{public}s"
+ "IdentityProofingRequestManager+TextUnderstanding: Comparison complete in %ss"
+ "IdentityProofingRequestManager+TextUnderstanding: Comparison failed (%ss): domain=%s code=%ld %s"
+ "IdentityProofingRequestManager+TextUnderstanding: FuzzyMatch scores\n- firstName: %{public}s\n- lastName: %{public}s\n- state: %{public}s\n- street: %{public}s\n- postalCode: %{public}s\n- duration: %{public}ss\n- errorCode: 0"
+ "IdentityProofingRequestManager+TextUnderstanding: No comparable data extracted (%ss)"
+ "IdentityProofingRequestManager+TextUnderstanding: No front ID image available for comparison"
+ "IdentityProofingRequestManager+TextUnderstanding: Starting TextUnderstanding comparison coordination"
+ "IdentityProofingRequestManager: Cancelled previous Text Understanding task"
+ "IdentityProofingRequestManager: PDF417 decode failed for Text Understanding: %s"
+ "IdentityProofingRequestManager: Scheduled Text Understanding comparison from prepare (runs parallel with review)"
+ "IdentityProofingRequestManager: Skipping TextUnderstanding comparison — disabled or no workflow"
+ "IdentityProofingRequestManager: Skipping TextUnderstanding comparison — missing front or back ID"
+ "IdentityProofingRequestManager: Skipping TextUnderstanding comparison — no parsed PDF417 data available"
+ "IdentityProofingRequestManager: Skipping TextUnderstanding comparison — not mDL category"
+ "IdentityProofingRequestManager: Text Understanding (prepare path) timed out or failed: %s. Continuing without result."
+ "IdentityProofingRequestManager: TextUnderstanding (prepare path) finished with no metric to record"
+ "IdentityWatchProvisioningManager failed to update precursor pass message"
+ "LIVENESS_STEPUP"
+ "Missing Unordered UI key for errorPageFailed"
+ "No matching identity pass for %{public}s, but consent exists for this credential."
+ "PARTIAL"
+ "TextUnderstanding: enabled=%{bool}d (isInternalBuild=%{bool}d, serverFlag=%s)"
+ "TextUnderstandingDocumentExtractor: Extracted %ld fields from IdentificationDocument (basic: 5, name: 3, address: 4)"
+ "TextUnderstandingDocumentExtractor: Fallback parse result - components found: first=%{bool}d, middle=%{bool}d, last=%{bool}d"
+ "TextUnderstandingDocumentExtractor: Formatter failed, using fallback parsing"
+ "TextUnderstandingDocumentExtractor: No identification documents found"
+ "TextUnderstandingDocumentExtractor: No name found in subject"
+ "TextUnderstandingDocumentExtractor: Parsed with formatter"
+ "TextUnderstandingDocumentExtractor: Subject name present: %{bool}d"
+ "TextUnderstandingDocumentExtractor: name present"
+ "TextUnderstandingIDComparator: Complete"
+ "TextUnderstandingIDComparator: No ID data extracted"
+ "TextUnderstandingIDComparator: Raw values before comparison\n- TU firstName: %{private}s\n- PDF417 firstName: %{private}s\n- TU lastName: %{private}s\n- PDF417 lastName: %{private}s\n- TU state: %{private}s\n- PDF417 state: %{private}s\n- TU address (fullAddress): %{private}s\n- PDF417 street1: %{private}s\n- TU postalCode: %{private}s\n- PDF417 postalCode: %{private}s"
+ "TextUnderstandingIDDocumentProcessor: Comparison complete, fuzzyMatch produced"
+ "TextUnderstandingService: CGColorSpace is not available"
+ "TextUnderstandingService: Failed to create CIImage from JPEG data"
+ "TextUnderstandingService: IOSurface is not available"
+ "TextUnderstandingService: Image conversion took %ss"
+ "TextUnderstandingService: Image has invalid dimensions"
+ "TextUnderstandingService: Processing image..."
+ "TextUnderstandingService: TU inference took %ss"
+ "_TtC8coreidvd34IdentityProvisioningStreamListener"
+ "coreidvd/TextUnderstandingService.swift"
+ "districtofcolumbia"
+ "extent"
+ "generateDeviceAttestationsV2(configuration:supplementalDataFetcher:)"
+ "imageByApplyingTransform:"
+ "initWithOptions:"
+ "initWithProperties:"
+ "markProofingSessionAsTerminal(for:)"
+ "processImage(imageData:)"
+ "proofingRequestType"
+ "provisioningCompletionManager"
+ "provisioningStreamIdentifier"
+ "render:toIOSurface:bounds:colorSpace:"
+ "resetAppleAccount()"
+ "set(precursorPassMessage:for:targeting:)"
+ "textUnderstandingComparisonTask"
+ "textUnderstandingDuration"
+ "textUnderstandingErrorCode"
+ "textUnderstandingFuzzyMatch"
+ "textUnderstandingMatch"
+ "textUnderstandingTimeoutInSeconds"
- "Fallback: Device confidence assessment for Passport - ODI error"
- "Fallback: Device confidence assessment for mDL - ODN error"
- "Matching pass exists for %s. Returning the consent as share"
- "Pass doesn't exist with the given credential identifier: "
- "V2 proofing will continue without KAK authorizations"
- "V2 proofing will continue without device attestations"
```
