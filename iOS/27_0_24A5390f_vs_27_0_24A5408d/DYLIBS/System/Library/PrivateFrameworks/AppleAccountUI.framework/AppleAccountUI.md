## AppleAccountUI

> `/System/Library/PrivateFrameworks/AppleAccountUI.framework/AppleAccountUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x385f1c` | `0x38735c` | **`+0x1440`** |
| `__DATA.__bss` | `0x10878` | `0x106c8` | **`-0x1b0`** |
| `__AUTH.__data` | `0x5158` | `0x4fb8` | **`-0x1a0`** |
| `__AUTH_CONST.__const` | `0x14ae8` | `0x14c68` | **`+0x180`** |
| `__TEXT.__const` | `0x140b4` | `0x13f84` | **`-0x130`** |
| `__TEXT.__constg_swiftt` | `0x7a2c` | `0x7904` | **`-0x128`** |
| `__TEXT.__swift5_typeref` | `0x15464` | `0x15576` | **`+0x112`** |
| `__AUTH_CONST.__objc_const` | `0x44038` | `0x43f68` | **`-0xd0`** |
| `__TEXT.__swift5_capture` | `0x6410` | `0x6494` | **`+0x84`** |
| `__TEXT.__eh_frame` | `0x325c` | `0x31f8` | **`-0x64`** |
| `__AUTH.__objc_data` | `0x8108` | `0x80b8` | **`-0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2590` | `0x25c0` | **`+0x30`** |
| `__DATA.__data` | `0x7440` | `0x7470` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x11f5c` | `0x11f8c` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x12c0` | `0x12a8` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x6f18` | `0x6f08` | **`-0x10`** |
| `__TEXT.__cstring` | `0xb6f1` | `0xb6e1` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0xc34c` | `0xc33c` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x4016` | `0x4006` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x7d08` | `0x7cf8` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3b54` | `0x3b48` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x2ec` | `0x2e0` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x1e00` | `0x1e08` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x930` | `0x928` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x7c0` | `0x7b8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x448` | `0x450` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xcd8` | `0xcdc` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x744` | `0x740` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x2a4` | `0x2a0` | **`-0x4`** |

### Other Changes

```diff

-584.0.0.0.0
+588.0.0.0.0

-  Functions: 17291
-  Symbols:   10463
-  CStrings:  2822
+  Functions: 17300
+  Symbols:   10460
+  CStrings:  2823
Symbols:
+ -[AAUIMyCustodianActionHandler _displayCustodianDeleteNotAllowedAlertOnViewController:]
+ GCC_except_table68
+ GCC_except_table80
+ GCC_except_table96
+ _OBJC_IVAR_$_AAUISignInViewController._isReloadingInputViews
+ _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE22presentationBackgroundyQrqd__AA10ShapeStyleRd__lFQOyAA15NavigationStackVyAA0H4PathVAcAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQOyAA08ModifiedN0VyAcAE0L7Margins__3forQrAA4EdgeO3SetV_12CoreGraphics7CGFloatVSgAA0N15MarginPlacementVtFQOyAA4FormVyAA05TupleN0VyAA7SectionVyAA05EmptyC0V012AppleAccountB017BirthdayPickerRowVA6_G_A4_yA6_AcAE010datePickerG0yQrqd__AA010DatePickerG0Rd__lFQOyAA10DatePickerVyAA4TextVG_AA019GraphicalDatePickerG0VQo_A6_GQPGG_Qo_AA23_GeometryActionModifierVyAWGG_A2_yAA0M4ItemVySSANyAA6ButtonVyAA18DefaultButtonLabelVGAA32_EnvironmentKeyTransformModifierVySbGGG_A40_QPGQo_G_AA5ColorVQo_HO
+ _symbolic _____ 14AppleAccountUI28InteractivePasskeyControllerV
+ _symbolic _____Sg 12CoreGraphics7CGFloatV
+ _symbolic _____y_____G 7SwiftUI23_GeometryActionModifierV 12CoreGraphics7CGFloatV
+ _symbolic _____y_____SgG 7SwiftUI5StateV 12CoreGraphics7CGFloatV
+ _symbolic _____y_____SgG 7SwiftUI9LazyStateV 12CoreGraphics7CGFloatV
+ _symbolic _____y_____Sg_G 7SwiftUI9LazyStateV7StorageO 12CoreGraphics7CGFloatV
+ _symbolic _____y__________y_____y_____y_____y_____y_____y__________AGG_AFyAG_____y_____y_____G______Qo_AGGQPGG_Qo______y_____GG_AEy_____ySSACy_____y_____G_____ySbGGG_A2_QPGQo_G 7SwiftUI15NavigationStackV AA0C4PathV AA4ViewPAAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQO AA08ModifiedJ0V AgAE0H7Margins__3forQrAA4EdgeO3SetV_12CoreGraphics7CGFloatVSgAA0J15MarginPlacementVtFQO AA4FormV AA05TupleJ0V AA7SectionV AA05EmptyF0V 012AppleAccountB017BirthdayPickerRowV AgAE15datePickerStyleyQrqd__AA15DatePickerStyleRd__lFQO AA10DatePickerV AA4TextV AA24GraphicalDatePickerStyleV AA23_GeometryActionModifierV AU AA0I4ItemV AA6ButtonV AA18DefaultButtonLabelV AA32_EnvironmentKeyTransformModifierV
+ _symbolic _____y_____y__________y_____y_____y_____y_____y_____y__________AGG_AFyAG_____y_____y_____G______Qo_AGGQPGG_Qo______y_____GG_AEy_____ySSACy_____y_____G_____ySbGGG_A2_QPGQo_G______Qo_ 7SwiftUI4ViewPAAE22presentationBackgroundyQrqd__AA10ShapeStyleRd__lFQO AA15NavigationStackV AA0H4PathV AcAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQO AA08ModifiedN0V AcAE0L7Margins__3forQrAA4EdgeO3SetV_12CoreGraphics7CGFloatVSgAA0N15MarginPlacementVtFQO AA4FormV AA05TupleN0V AA7SectionV AA05EmptyC0V 012AppleAccountB017BirthdayPickerRowV AcAE010datePickerG0yQrqd__AA010DatePickerG0Rd__lFQO AA10DatePickerV AA4TextV AA019GraphicalDatePickerG0V AA23_GeometryActionModifierV AW AA0M4ItemV AA6ButtonV AA18DefaultButtonLabelV AA32_EnvironmentKeyTransformModifierV AA5ColorV
+ _symbolic _____y_____y_____y_____y__________ADG_ACyAD_____y_____y_____G______Qo_ADGQPGG_Qo_ 7SwiftUI4ViewPAAE14contentMargins__3forQrAA4EdgeO3SetV_12CoreGraphics7CGFloatVSgAA22ContentMarginPlacementVtFQO AA4FormV AA05TupleL0V AA7SectionV AA05EmptyC0V 012AppleAccountB017BirthdayPickerRowV AcAE04dateV5StyleyQrqd__AA04DatevY0Rd__lFQO AA0zV0V AA4TextV AA09GraphicalzvY0V
+ _symbolic _____y_____y_____y_____y_____y__________AEG_ADyAE_____y_____y_____G______Qo_AEGQPGG_Qo______y_____GG 7SwiftUI15ModifiedContentV AA4ViewPAAE14contentMargins__3forQrAA4EdgeO3SetV_12CoreGraphics7CGFloatVSgAA0D15MarginPlacementVtFQO AA4FormV AA05TupleD0V AA7SectionV AA05EmptyE0V 012AppleAccountB017BirthdayPickerRowV AeAE04dateW5StyleyQrqd__AA04DatewZ0Rd__lFQO AA04DateW0V AA4TextV AA013GraphicalDatewZ0V AA23_GeometryActionModifierV AN
+ _symbolic _____y_____y_____y_____y_____y_____y__________AEG_ADyAE_____y_____y_____G______Qo_AEGQPGG_Qo______y_____GG_ACy_____ySSAAy_____y_____G_____ySbGGG_A0_QPGQo_ 7SwiftUI4ViewPAAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQO AA08ModifiedG0V AcAE0E7Margins__3forQrAA4EdgeO3SetV_12CoreGraphics7CGFloatVSgAA0G15MarginPlacementVtFQO AA4FormV AA05TupleG0V AA7SectionV AA05EmptyC0V 012AppleAccountB017BirthdayPickerRowV AcAE04dateY5StyleyQrqd__AA04DateY5StyleRd__lFQO AA04DateY0V AA4TextV AA013GraphicalDateY5StyleV AA23_GeometryActionModifierV AQ AA0F4ItemV AA6ButtonV AA18DefaultButtonLabelV AA32_EnvironmentKeyTransformModifierV
- -[AAUICustodianSetupFlowController isUpsellInSettings]
- -[AAUIMyCustodianActionHandler _displayCustodianDeleteNotAllowedAlert]
- GCC_except_table69
- GCC_except_table76
- GCC_except_table81
- GCC_except_table97
- _OBJC_CLASS_$_AKAppleIDPasskeyController
- __DATA__TtC14AppleAccountUI35CustodianOwnerRecoveryCodeViewModel
- __IVARS__TtC14AppleAccountUI35CustodianOwnerRecoveryCodeViewModel
- __METACLASS_DATA__TtC14AppleAccountUI35CustodianOwnerRecoveryCodeViewModel
- _associated conformance 14AppleAccountUI35CustodianOwnerRecoveryCodeViewModelCAA017OnboardingContentH0AA06CustomH0AaDP_05SwiftC00H0
- _get_witness_table 7SwiftUI15ModifiedContentVy012AppleAccountB014OnboardingViewVyAD026CustodianOwnerRecoveryCodeH5ModelCGAA30_SafeAreaRegionsIgnoringLayoutVGAA0H0HPAiaMHPyHC_AkA0H8ModifierHPyHCHC
- _get_witness_table 7SwiftUI6VStackVyAA12TupleContentVyAA08ModifiedE0VyAGyAA6HStackVyAA7ForEachVySaySi6offset_SJ7elementtGSiAA4TextVGGAA16_FlexFrameLayoutVGAA31AccessibilityAttachmentModifierVG_AA6SpacerVQPGGAA4ViewHPyHC
- _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE22presentationBackgroundyQrqd__AA10ShapeStyleRd__lFQOyAA15NavigationStackVyAA0H4PathVAcAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQOyAA4FormVyAA05TupleN0VyAA7SectionVyAA05EmptyC0V012AppleAccountB017BirthdayPickerRowVATG_ARyAtcAE04datevG0yQrqd__AA04DatevG0Rd__lFQOyAA0yV0VyAA4TextVG_AA09GraphicalyvG0VQo_ATGQPGG_APyAA0M4ItemVySSAA08ModifiedN0VyAA6ButtonVyAA18DefaultButtonLabelVGAA32_EnvironmentKeyTransformModifierVySbGGG_A23_QPGQo_G_AA5ColorVQo_HO
- _symbolic _____ 14AppleAccountUI35CustodianOwnerRecoveryCodeViewModelC
- _symbolic _____y_____G 14AppleAccountUI14OnboardingViewV AA026CustodianOwnerRecoveryCodeE5ModelC
- _symbolic _____y__________y_____y_____y_____y__________AFG_AEyAF_____y_____y_____G______Qo_AFGQPGG_ADy_____ySS_____y_____y_____G_____ySbGGG_AYQPGQo_G 7SwiftUI15NavigationStackV AA0C4PathV AA4ViewPAAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQO AA4FormV AA05TupleJ0V AA7SectionV AA05EmptyF0V 012AppleAccountB017BirthdayPickerRowV AgAE04dateR5StyleyQrqd__AA04DaterU0Rd__lFQO AA0vR0V AA4TextV AA09GraphicalvrU0V AA0I4ItemV AA08ModifiedJ0V AA6ButtonV AA18DefaultButtonLabelV AA32_EnvironmentKeyTransformModifierV
- _symbolic _____y_____y_____G_____G 7SwiftUI15ModifiedContentV 012AppleAccountB014OnboardingViewV AD026CustodianOwnerRecoveryCodeH5ModelC AA30_SafeAreaRegionsIgnoringLayoutV
- _symbolic _____y_____y__________y_____y_____y_____y__________AFG_AEyAF_____y_____y_____G______Qo_AFGQPGG_ADy_____ySS_____y_____y_____G_____ySbGGG_AYQPGQo_G______Qo_ 7SwiftUI4ViewPAAE22presentationBackgroundyQrqd__AA10ShapeStyleRd__lFQO AA15NavigationStackV AA0H4PathV AcAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQO AA4FormV AA05TupleN0V AA7SectionV AA05EmptyC0V 012AppleAccountB017BirthdayPickerRowV AcAE04datevG0yQrqd__AA04DatevG0Rd__lFQO AA0yV0V AA4TextV AA09GraphicalyvG0V AA0M4ItemV AA08ModifiedN0V AA6ButtonV AA18DefaultButtonLabelV AA32_EnvironmentKeyTransformModifierV AA5ColorV
- _symbolic _____y_____y_____y_____y__________ADG_ACyAD_____y_____y_____G______Qo_ADGQPGG_ABy_____ySS_____y_____y_____G_____ySbGGG_AWQPGQo_ 7SwiftUI4ViewPAAE7toolbar7contentQrqd__yXE_tAA14ToolbarContentRd__lFQO AA4FormV AA05TupleG0V AA7SectionV AA05EmptyC0V 012AppleAccountB017BirthdayPickerRowV AcAE04dateO5StyleyQrqd__AA04DateoR0Rd__lFQO AA0sO0V AA4TextV AA09GraphicalsoR0V AA0F4ItemV AA08ModifiedG0V AA6ButtonV AA07DefaultX5LabelV AA32_EnvironmentKeyTransformModifierV
CStrings:
+ "State observation already running for %s"
+ "\xf0A\xa1b"
- "\xf01\xa1b"
```
