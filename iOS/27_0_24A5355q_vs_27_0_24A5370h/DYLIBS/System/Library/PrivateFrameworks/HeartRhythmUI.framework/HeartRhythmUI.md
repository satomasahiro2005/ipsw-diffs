## HeartRhythmUI

> `/System/Library/PrivateFrameworks/HeartRhythmUI.framework/HeartRhythmUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x350e8` | `0x33fc0` | **`-0x1128`** |
| `__AUTH_CONST.__objc_const` | `0x6b98` | `0x6c90` | **`+0xf8`** |
| `__TEXT.__objc_methlist` | `0x4d40` | `0x4c80` | **`-0xc0`** |
| `__TEXT.__cstring` | `0x3bc3` | `0x3b16` | **`-0xad`** |
| `__AUTH_CONST.__cfstring` | `0x3220` | `0x3180` | **`-0xa0`** |
| `__DATA.__data` | `0x6c8` | `0x668` | **`-0x60`** |
| `__AUTH.__objc_data` | `0xbe0` | `0xc30` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xce8` | `0xcb0` | **`-0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x2fb8` | `0x2fe8` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x1e4` | `0x1bc` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x430` | `0x428` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x668` | `0x660` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x90` | `0x88` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x190` | `0x198` | **`+0x8`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 1523
-  Symbols:   2698
-  CStrings:  496
+  Functions: 1507
+  Symbols:   2678
+  CStrings:  491
Symbols:
+ -[HRAtrialFibrillationIntroViewController init]
+ -[HRAtrialFibrillationOnboardingManager onboardingManager:viewControllerForPage:]
+ -[HRElectrocardiogramOnboardingManager initWithOnboardingType:isFirstTimeOnboarding:healthStore:dateCache:provenance:delegate:isSampleInteractive:isRecordingSkippable:]
+ -[HRElectrocardiogramOnboardingManager isRecordingSkippable]
+ -[HRElectrocardiogramOnboardingManager onboardingManager:viewControllerForPage:]
+ -[HROnboardingAtrialFibrillationGateViewController cardLeadingConstraints]
+ -[HROnboardingAtrialFibrillationGateViewController cardTrailingConstraints]
+ -[HROnboardingAtrialFibrillationGateViewController setCardLeadingConstraints:]
+ -[HROnboardingAtrialFibrillationGateViewController setCardTrailingConstraints:]
+ -[HROnboardingAtrialFibrillationGateViewController viewDidLayoutSubviews]
+ -[HROnboardingAtrialFibrillationIntroViewController viewDidLayoutSubviews]
+ -[HROnboardingECG2PossibleResultsViewController _updateEdgeEffectVisibility]
+ -[HROnboardingElectrocardiogramAvailabilityViewController _updateIsValidAgeDisplay]
+ -[HROnboardingElectrocardiogramAvailabilityViewController _validAgeFooterLastBaselineToContinueButton]
+ -[HROnboardingElectrocardiogramAvailabilityViewController ageQuestionLeadingConstraint]
+ -[HROnboardingElectrocardiogramAvailabilityViewController ageQuestionTrailingConstraint]
+ -[HROnboardingElectrocardiogramAvailabilityViewController setAgeQuestionLeadingConstraint:]
+ -[HROnboardingElectrocardiogramAvailabilityViewController setAgeQuestionTrailingConstraint:]
+ -[HROnboardingElectrocardiogramAvailabilityViewController viewDidLayoutSubviews]
+ -[HROnboardingElectrocardiogramTakeRecordingViewController _dismissButtonTapped:]
+ -[HROnboardingElectrocardiogramTakeRecordingViewController initForOnboarding:isRecordingSkippable:]
+ -[HROnboardingElectrocardiogramTakeRecordingViewController isRecordingSkippable]
+ -[HROnboardingElectrocardiogramTakeRecordingViewController setIsRecordingSkippable:]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _didTapContinueButton:]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _setUpButtonTray]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController closeButtonTapped:]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController continueButton]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController createHeroView]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController delegate]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController isOnboarding]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController presentAlertWithMessage:]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController presentLearnMoreAlertWithMessage:learnMoreTapped:]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController setContinueButton:]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController setDelegate:]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController setOnboarding:]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController setUpgradingFromAlgorithmVersion:]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController upgradingFromAlgorithmVersion]
+ -[HROnboardingElectrocardiogramUpdateAvailabilityViewController viewDidLoad]
+ -[HROnboardingElectrocardiogramUpdateCompleteViewController _didTapDoneButton:]
+ -[HROnboardingElectrocardiogramUpdateCompleteViewController delegate]
+ -[HROnboardingElectrocardiogramUpdateCompleteViewController isOnboarding]
+ -[HROnboardingElectrocardiogramUpdateCompleteViewController setDelegate:]
+ -[HROnboardingElectrocardiogramUpdateCompleteViewController setOnboarding:]
+ -[HROnboardingElectrocardiogramUpdateCompleteViewController setUpgradingFromAlgorithmVersion:]
+ -[HROnboardingElectrocardiogramUpdateCompleteViewController upgradingFromAlgorithmVersion]
+ -[HRQuestionSelectionHeaderView .cxx_destruct]
+ -[HRQuestionSelectionHeaderView initWithReuseIdentifier:]
+ -[HRQuestionSelectionHeaderView layoutSubviews]
+ -[HRQuestionSelectionHeaderView setTitleLabel:]
+ -[HRQuestionSelectionHeaderView setTitleLeadingConstraint:]
+ -[HRQuestionSelectionHeaderView setTitleTrailingConstraint:]
+ -[HRQuestionSelectionHeaderView titleLabel]
+ -[HRQuestionSelectionHeaderView titleLeadingConstraint]
+ -[HRQuestionSelectionHeaderView titleTrailingConstraint]
+ -[HRQuestionSelectionView cardHorizontalInset]
+ _OBJC_CLASS_$_HRQuestionSelectionHeaderView
+ _OBJC_CLASS_$_UITableViewHeaderFooterView
+ _OBJC_CLASS_$_UITraitPreferredContentSizeCategory
+ _OBJC_IVAR_$_HRElectrocardiogramOnboardingManager._isRecordingSkippable
+ _OBJC_IVAR_$_HROnboardingAtrialFibrillationGateViewController._cardLeadingConstraints
+ _OBJC_IVAR_$_HROnboardingAtrialFibrillationGateViewController._cardTrailingConstraints
+ _OBJC_IVAR_$_HROnboardingElectrocardiogramAvailabilityViewController._ageQuestionLeadingConstraint
+ _OBJC_IVAR_$_HROnboardingElectrocardiogramAvailabilityViewController._ageQuestionTrailingConstraint
+ _OBJC_IVAR_$_HROnboardingElectrocardiogramTakeRecordingViewController._isRecordingSkippable
+ _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateAvailabilityViewController._continueButton
+ _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateAvailabilityViewController._upgradingFromAlgorithmVersion
+ _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateAvailabilityViewController.delegate
+ _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateAvailabilityViewController.onboarding
+ _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateCompleteViewController._upgradingFromAlgorithmVersion
+ _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateCompleteViewController.delegate
+ _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateCompleteViewController.onboarding
+ _OBJC_IVAR_$_HRQuestionSelectionHeaderView._titleLabel
+ _OBJC_IVAR_$_HRQuestionSelectionHeaderView._titleLeadingConstraint
+ _OBJC_IVAR_$_HRQuestionSelectionHeaderView._titleTrailingConstraint
+ _OBJC_METACLASS_$_HRQuestionSelectionHeaderView
+ _OBJC_METACLASS_$_UITableViewHeaderFooterView
+ __OBJC_$_INSTANCE_METHODS_HRQuestionSelectionHeaderView
+ __OBJC_$_INSTANCE_VARIABLES_HRQuestionSelectionHeaderView
+ __OBJC_$_PROP_LIST_HRQuestionSelectionHeaderView
+ __OBJC_CLASS_RO_$_HRQuestionSelectionHeaderView
+ __OBJC_METACLASS_RO_$_HRQuestionSelectionHeaderView
+ ___114-[HROnboardingElectrocardiogramUpdateAvailabilityViewController presentLearnMoreAlertWithMessage:learnMoreTapped:]_block_invoke
- -[HRAtrialFibrillationIntroViewController .cxx_destruct]
- -[HRAtrialFibrillationIntroViewController _assetImageBottomToTitleFirstBaseline]
- -[HRAtrialFibrillationIntroViewController _bodyFontTextStyle]
- -[HRAtrialFibrillationIntroViewController _bodyFont]
- -[HRAtrialFibrillationIntroViewController _bodyLastBaselineToContentBottom]
- -[HRAtrialFibrillationIntroViewController _createHeroView]
- -[HRAtrialFibrillationIntroViewController _titleFontTextStyle]
- -[HRAtrialFibrillationIntroViewController _titleFont]
- -[HRAtrialFibrillationIntroViewController _titleLastBaselineToBodyFirstBaseline]
- -[HRAtrialFibrillationIntroViewController bodyLabel]
- -[HRAtrialFibrillationIntroViewController contentView]
- -[HRAtrialFibrillationIntroViewController heroView]
- -[HRAtrialFibrillationIntroViewController learnMoreContentView]
- -[HRAtrialFibrillationIntroViewController scrollView]
- -[HRAtrialFibrillationIntroViewController setBodyLabel:]
- -[HRAtrialFibrillationIntroViewController setContentView:]
- -[HRAtrialFibrillationIntroViewController setHeroView:]
- -[HRAtrialFibrillationIntroViewController setLearnMoreContentView:]
- -[HRAtrialFibrillationIntroViewController setScrollView:]
- -[HRAtrialFibrillationIntroViewController setTitleLabel:]
- -[HRAtrialFibrillationIntroViewController setUpConstraints]
- -[HRAtrialFibrillationIntroViewController setUpUI]
- -[HRAtrialFibrillationIntroViewController titleLabel]
- -[HRAtrialFibrillationIntroViewController viewDidLoad]
- -[HRAtrialFibrillationOnboardingManager onboardingManager:customViewControllerForPage:]
- -[HRElectrocardiogramOnboardingManager onboardingManager:customViewControllerForPage:]
- -[HROnboardingElectrocardiogramAvailabilityViewController _ageEntryTitleFont]
- -[HROnboardingElectrocardiogramAvailabilityViewController _birthdayFooterLastBaselineToContinueButton]
- -[HROnboardingElectrocardiogramAvailabilityViewController _birthdayPromptFont]
- -[HROnboardingElectrocardiogramAvailabilityViewController _defaultDOB]
- -[HROnboardingElectrocardiogramAvailabilityViewController _setupBirthdayEntryView]
- -[HROnboardingElectrocardiogramAvailabilityViewController _updateDateOfBirthDisplay]
- -[HROnboardingElectrocardiogramAvailabilityViewController ageWithDate:]
- -[HROnboardingElectrocardiogramAvailabilityViewController birthdayEntryView]
- -[HROnboardingElectrocardiogramAvailabilityViewController birthdayFooterString]
- -[HROnboardingElectrocardiogramAvailabilityViewController compactDatePickerView:didChangeValue:]
- -[HROnboardingElectrocardiogramAvailabilityViewController dateOfBirth]
- -[HROnboardingElectrocardiogramAvailabilityViewController setBirthdayEntryView:]
- -[HROnboardingElectrocardiogramAvailabilityViewController setDateOfBirth:]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _bodyBottomToLocationTop]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _bodyFontTextStyle]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _bodyFont]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _footnoteFont]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _footnoteTextStyle]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _locationFooterLastBaselineToContinueButton]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _setUpStackedButtonView]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _titleBottomToBodyTop]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _titleFontTextStyle]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController _titleFont]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController bodyLabel]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController locationFooterLabel]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController setBodyLabel:]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController setLocationFooterLabel:]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController setStackedButtonView:]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController setTitleLabel:]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController stackedButtonView:didTapButtonAtIndex:]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController stackedButtonView]
- -[HROnboardingElectrocardiogramUpdateAvailabilityViewController titleLabel]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController _bodyFontTextStyle]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController _bodyFont]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController _titleFontTextStyle]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController _titleFont]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController bodyLabel]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController contentViewBottomConstraint]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController setBodyLabel:]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController setContentViewBottomConstraint:]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController setStackedButtonView:]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController setTitleLabel:]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController stackedButtonView:didTapButtonAtIndex:]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController stackedButtonView]
- -[HROnboardingElectrocardiogramUpdateCompleteViewController titleLabel]
- GCC_except_table11
- GCC_except_table13
- _HKUIApplicationIsUsingAccessibilityContentSizeCategory
- _OBJC_CLASS_$_HKOnboardingCompactDatePickerView
- _OBJC_CLASS_$_HKViewController
- _OBJC_IVAR_$_HRAtrialFibrillationIntroViewController._bodyLabel
- _OBJC_IVAR_$_HRAtrialFibrillationIntroViewController._contentView
- _OBJC_IVAR_$_HRAtrialFibrillationIntroViewController._heroView
- _OBJC_IVAR_$_HRAtrialFibrillationIntroViewController._learnMoreContentView
- _OBJC_IVAR_$_HRAtrialFibrillationIntroViewController._scrollView
- _OBJC_IVAR_$_HRAtrialFibrillationIntroViewController._titleLabel
- _OBJC_IVAR_$_HROnboardingElectrocardiogramAvailabilityViewController._birthdayEntryView
- _OBJC_IVAR_$_HROnboardingElectrocardiogramAvailabilityViewController._dateOfBirth
- _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateAvailabilityViewController._bodyLabel
- _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateAvailabilityViewController._locationFooterLabel
- _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateAvailabilityViewController._stackedButtonView
- _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateAvailabilityViewController._titleLabel
- _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateCompleteViewController._bodyLabel
- _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateCompleteViewController._contentViewBottomConstraint
- _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateCompleteViewController._stackedButtonView
- _OBJC_IVAR_$_HROnboardingElectrocardiogramUpdateCompleteViewController._titleLabel
- _OBJC_METACLASS_$_HKViewController
- _UIFontTextStyleHeadline
- __OBJC_$_INSTANCE_VARIABLES_HRAtrialFibrillationIntroViewController
- __OBJC_$_PROP_LIST_HRAtrialFibrillationIntroViewController
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_HKOnboardingCompactDatePickerViewDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_HKOnboardingCompactDatePickerViewDelegate
- __OBJC_$_PROTOCOL_REFS_HKOnboardingCompactDatePickerViewDelegate
- __OBJC_LABEL_PROTOCOL_$_HKOnboardingCompactDatePickerViewDelegate
- __OBJC_PROTOCOL_$_HKOnboardingCompactDatePickerViewDelegate
- ___79-[HRAtrialFibrillationIntroViewController viewControllerWillEnterAdaptiveModal]_block_invoke
CStrings:
+ "Header"
- "AGE_GATE_DATE_OF_BIRTH_TITLE"
- "AGE_GATE_FIELD_REQUIRED_PLACEHOLDER"
- "AppleWatchCanLookforAtrialFibrillation.EntireView"
- "BirthDate.Picker"
- "BirthDate.Title"
- "ECG_ONBOARDING_1_BIRTHDAY_FOOTNOTE"
```
