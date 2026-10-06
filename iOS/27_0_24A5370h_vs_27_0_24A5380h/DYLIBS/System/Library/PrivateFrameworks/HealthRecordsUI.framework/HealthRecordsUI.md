## HealthRecordsUI

> `/System/Library/PrivateFrameworks/HealthRecordsUI.framework/HealthRecordsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3aa5d0` | `0x3a76a4` | **`-0x2f2c`** |
| `__DATA_DIRTY.__data` | `0x2aa0` | `0x4c68` | **`+0x21c8`** |
| `__AUTH.__objc_data` | `0xf848` | `0xd7e8` | **`-0x2060`** |
| `__DATA_DIRTY.__objc_data` | `0x1090` | `0x30a0` | **`+0x2010`** |
| `__AUTH.__data` | `0xb578` | `0x9d58` | **`-0x1820`** |
| `__DATA.__bss` | `0x1f408` | `0x1e468` | **`-0xfa0`** |
| `__DATA_DIRTY.__bss` | `0x1ea0` | `0x2e40` | **`+0xfa0`** |
| `__DATA.__data` | `0x86d0` | `0x7c90` | **`-0xa40`** |
| `__AUTH_CONST.__objc_const` | `0x1e0f8` | `0x1de38` | **`-0x2c0`** |
| `__TEXT.__objc_methlist` | `0x9394` | `0x91dc` | **`-0x1b8`** |
| `__DATA.__common` | `0x738` | `0x5c8` | **`-0x170`** |
| `__DATA_DIRTY.__common` | `0x50` | `0x1c0` | **`+0x170`** |
| `__TEXT.__swift5_typeref` | `0x7dda` | `0x7d7e` | **`-0x5c`** |
| `__AUTH_CONST.__const` | `0x148d0` | `0x14878` | **`-0x58`** |
| `__TEXT.__eh_frame` | `0xf7f0` | `0xf848` | **`+0x58`** |
| `__TEXT.__const` | `0x19924` | `0x19974` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x78c8` | `0x7915` | **`+0x4d`** |
| `__DATA_CONST.__got` | `0x1ec0` | `0x1f08` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e98` | `0x5e58` | **`-0x40`** |
| `__TEXT.__swift5_capture` | `0x45f0` | `0x45b8` | **`-0x38`** |
| `__TEXT.__cstring` | `0x10aa7` | `0x10a77` | **`-0x30`** |
| `__DATA.__objc_ivar` | `0x608` | `0x5dc` | **`-0x2c`** |
| `__DATA_CONST.__const` | `0x19a8` | `0x19c8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xce88` | `0xcea8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x3210` | `0x3218` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xbd8` | `0xbd0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x200` | `0x1f8` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x10410` | `0x10408` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x870` | `0x874` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x338` | `0x33c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x360` | `0x364` | **`+0x4`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 18468
-  Symbols:   8226
+  Functions: 18453
+  Symbols:   8171
Symbols:
+ -[WDClinicalOnboardingViewController _setState:]
+ -[WDClinicalOnboardingViewController _updateStateForSearchResults]
+ GCC_except_table77
+ GCC_except_table79
+ GCC_except_table85
+ GCC_except_table95
+ _OBJC_IVAR_$_WDClinicalOnboardingViewController._currentState
+ ___86-[WDClinicalOnboardingViewController updateContentUnavailableConfigurationUsingState:]_block_invoke
+ ___block_descriptor_32_e18_v16?0"UIAction"8l
- -[WDClinicalOnboardingNoGeoView .cxx_destruct]
- -[WDClinicalOnboardingNoGeoView _setupConstraints]
- -[WDClinicalOnboardingNoGeoView _setupSubviews]
- -[WDClinicalOnboardingNoGeoView _tappedLocationServices:]
- -[WDClinicalOnboardingNoGeoView _updateForCurrentSizeCategory]
- -[WDClinicalOnboardingNoGeoView containerCenterYConstraint]
- -[WDClinicalOnboardingNoGeoView containerView]
- -[WDClinicalOnboardingNoGeoView init]
- -[WDClinicalOnboardingNoGeoView layoutSubviews]
- -[WDClinicalOnboardingNoGeoView locationServicesButtonBaselineConstraint]
- -[WDClinicalOnboardingNoGeoView locationServicesButton]
- -[WDClinicalOnboardingNoGeoView setContainerCenterYConstraint:]
- -[WDClinicalOnboardingNoGeoView setContainerView:]
- -[WDClinicalOnboardingNoGeoView setLocationServicesButton:]
- -[WDClinicalOnboardingNoGeoView setLocationServicesButtonBaselineConstraint:]
- -[WDClinicalOnboardingNoGeoView setSubtitleBaselineConstraint:]
- -[WDClinicalOnboardingNoGeoView setSubtitleLabel:]
- -[WDClinicalOnboardingNoGeoView setTitleLabel:]
- -[WDClinicalOnboardingNoGeoView subtitleBaselineConstraint]
- -[WDClinicalOnboardingNoGeoView subtitleLabel]
- -[WDClinicalOnboardingNoGeoView titleLabel]
- -[WDClinicalOnboardingNoGeoView traitCollectionDidChange:]
- -[WDClinicalOnboardingViewController _createNoContentParentView]
- -[WDClinicalOnboardingViewController _createNoGeoView]
- -[WDClinicalOnboardingViewController _createSpinnerView]
- -[WDClinicalOnboardingViewController _showNoContentView:]
- -[WDClinicalOnboardingViewController _updateNoContentViewConstraints]
- -[WDClinicalOnboardingViewController noContentBottomConstraint]
- -[WDClinicalOnboardingViewController noContentParentView]
- -[WDClinicalOnboardingViewController noContentTopConstraint]
- -[WDClinicalOnboardingViewController noGeoView]
- -[WDClinicalOnboardingViewController scrollViewDidChangeAdjustedContentInset:]
- -[WDClinicalOnboardingViewController setNoContentBottomConstraint:]
- -[WDClinicalOnboardingViewController setNoContentParentView:]
- -[WDClinicalOnboardingViewController setNoContentTopConstraint:]
- -[WDClinicalOnboardingViewController setNoGeoView:]
- -[WDClinicalOnboardingViewController setSpinnerView:]
- -[WDClinicalOnboardingViewController spinnerView]
- GCC_except_table80
- GCC_except_table82
- GCC_except_table88
- GCC_except_table98
- _OBJC_CLASS_$_HKCalendarCache
- _OBJC_CLASS_$_WDClinicalOnboardingNoGeoView
- _OBJC_IVAR_$_WDClinicalOnboardingNoGeoView._containerCenterYConstraint
- _OBJC_IVAR_$_WDClinicalOnboardingNoGeoView._containerView
- _OBJC_IVAR_$_WDClinicalOnboardingNoGeoView._locationServicesButton
- _OBJC_IVAR_$_WDClinicalOnboardingNoGeoView._locationServicesButtonBaselineConstraint
- _OBJC_IVAR_$_WDClinicalOnboardingNoGeoView._subtitleBaselineConstraint
- _OBJC_IVAR_$_WDClinicalOnboardingNoGeoView._subtitleLabel
- _OBJC_IVAR_$_WDClinicalOnboardingNoGeoView._titleLabel
- _OBJC_IVAR_$_WDClinicalOnboardingViewController._noContentBottomConstraint
- _OBJC_IVAR_$_WDClinicalOnboardingViewController._noContentParentView
- _OBJC_IVAR_$_WDClinicalOnboardingViewController._noContentTopConstraint
- _OBJC_IVAR_$_WDClinicalOnboardingViewController._noGeoView
- _OBJC_IVAR_$_WDClinicalOnboardingViewController._spinnerView
- _OBJC_METACLASS_$_WDClinicalOnboardingNoGeoView
- __OBJC_$_INSTANCE_METHODS_WDClinicalOnboardingNoGeoView
- __OBJC_$_INSTANCE_VARIABLES_WDClinicalOnboardingNoGeoView
- __OBJC_$_PROP_LIST_WDClinicalOnboardingNoGeoView
- __OBJC_CLASS_RO_$_WDClinicalOnboardingNoGeoView
- __OBJC_METACLASS_RO_$_WDClinicalOnboardingNoGeoView
- _symbolic _____ySaySS___________tG______pGIegg_ s6ResultOsRi_zRi0_zrlE 10Foundation4DateV AC4UUIDV s5ErrorP
- _symbolic _____ySaySS___________tG______pGIegn_ s6ResultOsRi_zRi0_zrlE 10Foundation4DateV AC4UUIDV s5ErrorP
CStrings:
+ "No cached concept name for concept ID: %{public}s, falling back to: %{public}s"
+ "\xf0\x91"
- "ClinicalPublisherFactory.lastLabNamesPublisher"
- "\xf0r!"
```
