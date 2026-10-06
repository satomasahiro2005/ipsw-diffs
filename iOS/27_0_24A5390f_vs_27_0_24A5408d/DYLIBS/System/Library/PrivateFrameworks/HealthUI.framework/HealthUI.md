## HealthUI

> `/System/Library/PrivateFrameworks/HealthUI.framework/HealthUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44e804` | `0x44cc58` | **`-0x1bac`** |
| `__AUTH_CONST.__objc_const` | `0x662d0` | `0x66650` | **`+0x380`** |
| `__TEXT.__objc_methlist` | `0x3b41c` | `0x3b5dc` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x233af` | `0x2355f` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x34e8` | `0x3340` | **`-0x1a8`** |
| `__AUTH.__objc_data` | `0x183e8` | `0x18548` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x74e5` | `0x7635` | **`+0x150`** |
| `__DATA_CONST.__objc_selrefs` | `0x18ae0` | `0x18b90` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x1e9c0` | `0x1ea40` | **`+0x80`** |
| `__DATA.__data` | `0x8308` | `0x8378` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x3858` | `0x38b0` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0x31a6` | `0x31f6` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x8c58` | `0x8c10` | **`-0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x30d8` | `0x3118` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x4eac` | `0x4ee8` | **`+0x3c`** |
| `__TEXT.__swift5_capture` | `0x1510` | `0x14d4` | **`-0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x3120` | `0x3158` | **`+0x38`** |
| `__AUTH.__data` | `0x2640` | `0x2670` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x79b8` | `0x79e0` | **`+0x28`** |
| `__DATA.__bss` | `0x7030` | `0x7050` | **`+0x20`** |
| `__TEXT.__const` | `0x8d74` | `0x8d94` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x164` | `0x144` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x4060` | `0x407c` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x21b0` | `0x21c8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xf420` | `0xf430` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x8c` | `0x80` | **`-0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x6c8` | `0x6d0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x188` | `0x190` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1870` | `0x1878` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x9c` | `0x94` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x3f0` | `0x3f4` | **`+0x4`** |
| `__TEXT.__swift5_typeref` | `0x3542` | `0x3544` | **`+0x2`** |

### Other Changes

```diff

-7027.0.67.2.1
+7027.0.72.2.5

-  Functions: 26382
-  Symbols:   35651
-  CStrings:  5320
+  Functions: 26414
+  Symbols:   35724
+  CStrings:  5334
Symbols:
+ +[HKExternalImageProvider _sharedProvider]
+ +[HKExternalImageProvider imageReferenceForKind:]
+ +[HKInteractiveChartViewController _heightDesignationForViewController:]
+ +[HKInteractiveChartViewController shouldUseNavigationBarLayoutForViewController:]
+ -[HKAuthorizationPresentationController presentationDidFailHandler]
+ -[HKAuthorizationPresentationController setPresentationDidFailHandler:]
+ -[HKAxis omitsOverlappingLabels]
+ -[HKAxisConfiguration omitsOverlappingLabels]
+ -[HKAxisConfiguration setOmitsOverlappingLabels:]
+ -[HKExternalImageReference .cxx_destruct]
+ -[HKExternalImageReference bundle]
+ -[HKExternalImageReference initWithName:bundle:]
+ -[HKExternalImageReference name]
+ -[HKNanoHostAuthorizationController beginSettingsReauthorizationForSource:readTypes:writeTypes:]
+ -[HKNanoHostAuthorizationController didFinish]
+ -[HKNanoHostAuthorizationController setDidFinish:]
+ -[HKOverlayRoomViewController overlayZeroHeightConstraint]
+ -[HKOverlayRoomViewController setOverlayZeroHeightConstraint:]
+ -[HKSourceAuthorizationController commonHistoryWindowForReadTypes:]
+ -[HKSourceAuthorizationController presentSettingsReauthorizationWithCompletion:]
+ GCC_except_table141
+ GCC_except_table62
+ GCC_except_table75
+ GCC_except_table78
+ _HKCategoryTypeIdentifierBleedingAfterMenopause
+ _HKCategoryTypeIdentifierBleedingAfterPregnancy
+ _HKCategoryTypeIdentifierBleedingDuringPregnancy
+ _HKCategoryTypeIdentifierLactation
+ _HKCategoryTypeIdentifierMenopausalState
+ _HKCategoryTypeIdentifierPregnancy
+ _HKErrorDomain
+ _HKQuantityTypeIdentifierAtrialFibrillationBurden
+ _OBJC_CLASS_$_HKExternalImageProvider
+ _OBJC_CLASS_$_HKExternalImageReference
+ _OBJC_IVAR_$_HKAuthorizationPresentationController._presentationDidFailHandler
+ _OBJC_IVAR_$_HKAxis._omitsOverlappingLabels
+ _OBJC_IVAR_$_HKAxisConfiguration._omitsOverlappingLabels
+ _OBJC_IVAR_$_HKExternalImageReference._bundle
+ _OBJC_IVAR_$_HKExternalImageReference._name
+ _OBJC_IVAR_$_HKNanoHostAuthorizationController._didFinish
+ _OBJC_IVAR_$_HKOverlayRoomViewController._overlayZeroHeightConstraint
+ _OBJC_METACLASS_$_HKExternalImageProvider
+ _OBJC_METACLASS_$_HKExternalImageReference
+ _OBJC_METACLASS_$__TtC8HealthUIP33_6437C8397BE458390DCCD81C27D63EDE27AuthorizationFooterTextView
+ __DATA__TtC8HealthUIP33_6437C8397BE458390DCCD81C27D63EDE27AuthorizationFooterTextView
+ __HKCategoryTypeIdentifierIsSensitiveForLogging.onceToken
+ __HKCategoryTypeIdentifierIsSensitiveForLogging.sensitiveIdentifiers
+ __HKQuantityTypeIdentifierIsSensitiveForLogging.onceToken
+ __HKQuantityTypeIdentifierIsSensitiveForLogging.sensitiveIdentifiers
+ __INSTANCE_METHODS__TtC8HealthUIP33_6437C8397BE458390DCCD81C27D63EDE27AuthorizationFooterTextView
+ __IVARS__TtC8HealthUIP33_6437C8397BE458390DCCD81C27D63EDE27AuthorizationFooterTextView
+ __METACLASS_DATA__TtC8HealthUIP33_6437C8397BE458390DCCD81C27D63EDE27AuthorizationFooterTextView
+ __OBJC_$_CLASS_METHODS_HKExternalImageProvider
+ __OBJC_$_INSTANCE_METHODS_HKExternalImageReference
+ __OBJC_$_INSTANCE_VARIABLES_HKExternalImageReference
+ __OBJC_$_PROP_LIST_HKExternalImageReference
+ __OBJC_$_PROP_LIST__HKAuthorizationPresentationController
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HealthAssetBundleImageProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HKHealthPrivacyServiceRemoteAuthorizationViewController
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HealthAssetBundleImageProviding
+ __OBJC_$_PROTOCOL_REFS_HealthAssetBundleImageProviding
+ __OBJC_CLASS_RO_$_HKExternalImageProvider
+ __OBJC_CLASS_RO_$_HKExternalImageReference
+ __OBJC_LABEL_PROTOCOL_$_HealthAssetBundleImageProviding
+ __OBJC_METACLASS_RO_$_HKExternalImageProvider
+ __OBJC_METACLASS_RO_$_HKExternalImageReference
+ __OBJC_PROTOCOL_$_HealthAssetBundleImageProviding
+ __OBJC_PROTOCOL_REFERENCE_$_HealthAssetBundleImageProviding
+ ___42+[HKExternalImageProvider _sharedProvider]_block_invoke
+ ___96-[HKNanoHostAuthorizationController beginSettingsReauthorizationForSource:readTypes:writeTypes:]_block_invoke
+ ____HKCategoryTypeIdentifierIsSensitiveForLogging_block_invoke
+ ____HKQuantityTypeIdentifierIsSensitiveForLogging_block_invoke
+ ___block_descriptor_56_e8_32s40s48s_e67_v16?0"<HKHealthPrivacyServiceRemoteAuthorizationViewController>"8ls32l8s40l8s48l8
+ __sharedProvider.onceToken
+ __sharedProvider.provider
+ _symbolic SDyS2SG
+ _symbolic _____ 10Foundation6LocaleV
+ _symbolic _____ 8HealthUI27AuthorizationFooterTextView33_6437C8397BE458390DCCD81C27D63EDELLC
+ _symbolic _____y_____G 7SwiftUI11EnvironmentV 10Foundation6LocaleV
- GCC_except_table139
- GCC_except_table60
- GCC_except_table73
- _swift_release_x12
- _symbolic So11UIStackViewC
- _symbolic So8UIButtonC
CStrings:
+ "/System/Library/Health/ImageBundles/HealthAssetBundle.bundle"
+ "AUTHORIZATION_PROMPT_ACCESS_BODY_SHARE"
+ "AUTHORIZATION_PROMPT_ACCESS_BODY_WRITE_ONLY"
+ "AUTHORIZATION_PROMPT_ACCESS_TITLE_%@"
+ "AUTHORIZATION_READ_ACCESS_HEADER"
+ "AUTHORIZATION_WRITE_ACCESS_HEADER"
+ "AuthorizationFooterTextViewIdentifier"
+ "CLINICAL_DOCUMENTS_REQUEST_AUTH_DESCRIPTION_THIS_APP"
+ "DISABLE_ALL_%ld_CATEGORIES"
+ "HKExternalImageProvider: failed to load %{public}@: %{public}@"
+ "HKExternalImageProvider: principal class %{public}@ does not conform to HealthAssetBundleImageProviding"
+ "HKLevelCategory(<redacted>)"
+ "HKNanoHostAuthorizationController: Failed to begin settings reauthorization with error: %{public}@"
+ "HKNanoHostAuthorizationController: begin settings reauthorization for %{public}@"
+ "HKQuantityType(<redacted>)"
+ "MMMdjmm"
+ "TIME_BOUNDED_AUTH_SELECT_DATA_BODY"
+ "The authorization prompt could not be presented from this process."
- "MMMdjj"
- "TIME_BOUNDED_AUTH_TOPICS_SELECTED_%ld"
- "queryDayDatesWithData(for:since:healthStore:)"
- "queryEarliestSampleDate(for:healthStore:)"
```
