## HealthRecordsUI

> `/System/Library/PrivateFrameworks/HealthRecordsUI.framework/HealthRecordsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a5380` | `0x3aa5d0` | **`+0x5250`** |
| `__TEXT.__eh_frame` | `0xf478` | `0xf7f0` | **`+0x378`** |
| `__AUTH_CONST.__const` | `0x14650` | `0x148d0` | **`+0x280`** |
| `__TEXT.__unwind_info` | `0xccf8` | `0xce88` | **`+0x190`** |
| `__TEXT.__swift5_capture` | `0x4474` | `0x45f0` | **`+0x17c`** |
| `__DATA_DIRTY.__data` | `0x29c8` | `0x2aa0` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x77f5` | `0x78c8` | **`+0xd3`** |
| `__DATA.__data` | `0x8628` | `0x86d0` | **`+0xa8`** |
| `__TEXT.__const` | `0x19884` | `0x19924` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x10b3c` | `0x10aa7` | **`-0x95`** |
| `__TEXT.__swift5_typeref` | `0x7d48` | `0x7dda` | **`+0x92`** |
| `__TEXT.__swift_as_cont` | `0x810` | `0x870` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x1e0b8` | `0x1e0f8` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x8dd5` | `0x8e07` | **`+0x32`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e68` | `0x5e98` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x310` | `0x338` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x340` | `0x360` | **`+0x20`** |
| `__AUTH.__data` | `0xb560` | `0xb578` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x937c` | `0x9394` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x8dfc` | `0x8e14` | **`+0x18`** |
| `__AUTH.__objc_data` | `0xf838` | `0xf848` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1eb0` | `0x1ec0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x10400` | `0x10410` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x3208` | `0x3210` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x19a0` | `0x19a8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x60c` | `0x608` | **`-0x4`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 18386
-  Symbols:   8220
-  CStrings:  2079
+  Functions: 18468
+  Symbols:   8226
+  CStrings:  2078
Symbols:
+ -[WDClinicalOnboardingViewController _updateSearchClearButtonForText:]
+ -[WDClinicalOnboardingViewController searchBar:textDidChange:]
+ -[WDClinicalOnboardingViewController searchBarTextDidBeginEditing:]
+ -[WDClinicalOnboardingViewController updateContentUnavailableConfigurationUsingState:]
+ GCC_except_table80
+ GCC_except_table82
+ GCC_except_table88
+ GCC_except_table98
+ ___swift_closure_destructor.18Tm
+ ___swift_closure_destructor.31Tm
+ _associated conformance 15HealthRecordsUI24LabsListViewDataProviderV13makePublisher7Combine03AnyJ0VySayAA017UserDomainConceptfG0VG_AJts5NeverOGyFAJ_AJtAJcfU1_9ItemStateL_OSHAASQ
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get_throwing
+ _swift_release_x13
+ _symbolic Say______pG 15HealthRecordsUI24MedicalRecordDisplayableP
+ _symbolic So20NSNotificationCenterC
+ _symbolic _____ 15HealthRecordsUI24LabsListViewDataProviderV13makePublisher7Combine03AnyJ0VySayAA017UserDomainConceptfG0VG_AJts5NeverOGyFAJ_AJtAJcfU1_9ItemStateL_O
+ _symbolic _____XDXMT 15HealthRecordsUI27ClinicalAccountLoginSessionC
+ _symbolic ______p 15HealthRecordsUI24MedicalRecordDisplayableP
+ _symbolic _____ySay______pG_____GIegg_ s6ResultOsRi_zRi0_zrlE 15HealthRecordsUI04TestA13RepresentableP s5NeverO
+ _symbolic _____ySay______pG_____GIegn_ s6ResultOsRi_zRi0_zrlE 15HealthRecordsUI04TestA13RepresentableP s5NeverO
+ _symbolic _____y__________GIegn_ s6ResultOsRi_zRi0_zrlE 15HealthRecordsUI25UserDomainConceptViewDataV s5NeverO
- -[WDClinicalOnboardingViewController _createNoLocationsView]
- -[WDClinicalOnboardingViewController _hideNoLocationsView]
- -[WDClinicalOnboardingViewController _showNoLocationsViewIfNeeded]
- -[WDClinicalOnboardingViewController noLocationsView]
- -[WDClinicalOnboardingViewController setNoLocationsView:]
- GCC_except_table79
- GCC_except_table81
- GCC_except_table87
- GCC_except_table97
- _HKStringFromListUserDomainType
- _OBJC_IVAR_$_WDClinicalOnboardingViewController._noLocationsView
- ___swift_closure_destructor.34Tm
- ___swift_closure_destructor.7Tm
- __swift_FORCE_LOAD_$_swiftNaturalLanguage
- __swift_FORCE_LOAD_$_swiftNaturalLanguage_$_HealthRecordsUI
- _associated conformance 15HealthRecordsUI24LabsListViewDataProviderV20makeCHROnlyPublisher33_B5203A1F600B3D025DA652A0F2A9A5CELL7Combine03AnyK0VySayAA017UserDomainConceptfG0VG_AKts5NeverOGyFAK_AKtAKcfU1_9ItemStateL_OSHAASQ
- _symbolic _____ 15HealthRecordsUI24LabsListViewDataProviderV20makeCHROnlyPublisher33_B5203A1F600B3D025DA652A0F2A9A5CELL7Combine03AnyK0VySayAA017UserDomainConceptfG0VG_AKts5NeverOGyFAK_AKtAKcfU1_9ItemStateL_O
CStrings:
+ "%s.%s failed to start login session: %s"
+ "%s.%s failed to start relogin session: %s"
+ "Medical Concept ("
+ "Medical Concept (no identifier)"
+ "SignedClinicalDataQRCodeGenerator: failed to create QR code image data from CIContext.pngRepresentation"
+ "SignedClinicalDataQRCodeGenerator: failed to create UIImage from PNG data"
+ "startLogin(with:additionalLoginComponents:loginCancelledHandler:callbackErrorHandler:)"
+ "startRelogin(to:from:profile:loginCancelledHandler:callbackErrorHandler:)"
+ "\xf0r!"
- "%s: failed to create QR code image data"
- "%s: failed to create UIImage from PNG data"
- "HealthRecordsUI/AccountStateChangeListener.swift"
- "HealthRecordsUI/DownloadableAttachmentStateChangeListener.swift"
- "HealthRecordsUI/HealthRecordsSupportedStateChangeListener.swift"
- "HealthRecordsUI/IndexManagerStateChangeListener.swift"
- "HealthRecordsUI/IngestionStateChangeListener.swift"
- "MHR Concept (no identifier)"
- "MHR Lab Concept ("
- "\xf0\x82!"
```
