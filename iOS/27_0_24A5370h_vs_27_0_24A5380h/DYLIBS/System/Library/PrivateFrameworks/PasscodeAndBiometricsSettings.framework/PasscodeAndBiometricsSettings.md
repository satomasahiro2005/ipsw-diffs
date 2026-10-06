## PasscodeAndBiometricsSettings

> `/System/Library/PrivateFrameworks/PasscodeAndBiometricsSettings.framework/PasscodeAndBiometricsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `—` | `0x648` | **`+0x648`** |
| `__TEXT.__text` | `0x3b340` | `0x3b8c0` | **`+0x580`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0x578` | **`+0x528`** |
| `__AUTH.__objc_data` | `0x9e0` | `0x508` | **`-0x4d8`** |
| `__DATA.__bss` | `0xa70` | `0x700` | **`-0x370`** |
| `__DATA_DIRTY.__bss` | `0x78` | `0x3e0` | **`+0x368`** |
| `__AUTH.__data` | `0x3f0` | `0xe8` | **`-0x308`** |
| `__DATA.__data` | `0x924` | `0x674` | **`-0x2b0`** |
| `__AUTH_CONST.__objc_const` | `0x2098` | `0x2128` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x1de8` | `0x1e30` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x20ec` | `0x212c` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x50d5` | `0x5115` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x2e80` | `0x2ea0` | **`+0x20`** |
| `__DATA.__common` | `0x20` | `—` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x6f8` | `0x718` | **`+0x20`** |
| `__DATA_DIRTY.__common` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3678` | `0x3698` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x69c` | `0x6b0` | **`+0x14`** |
| `__TEXT.__const` | `0xc24` | `0xc34` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa68` | `0xa70` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1048` | `0x1050` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xd0` | `0xd8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x78` | `0x80` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1088` | `0x1090` | **`+0x8`** |

### Other Changes

```diff

-32.0.0.0.0
+34.0.0.0.0

-  Functions: 1310
-  Symbols:   1828
-  CStrings:  881
+  Functions: 1317
+  Symbols:   1837
+  CStrings:  884
Symbols:
+ -[PABSPasscodeLockController setAutoUnlockSpecifierLoading:forSpecifier:]
+ -[PABSPearlPasscodeController foregrounded:]
+ -[PABSSwitchTableCell layoutSubviews]
+ -[PABSSwitchTableCell refreshCellContentsWithSpecifier:]
+ -[PSEnrollContainerViewController _preferredContentSizeDidChangeForChildViewController:]
+ -[PSEnrollmentNavigationController _preferredContentSizeDidChangeForChildViewController:]
+ GCC_except_table105
+ GCC_except_table11
+ GCC_except_table150
+ GCC_except_table16
+ GCC_except_table18
+ GCC_except_table59
+ GCC_except_table82
+ OBJC_IVAR_$_PSSwitchTableCell._activityIndicator
+ _OBJC_CLASS_$_PABSSwitchTableCell
+ _OBJC_CLASS_$_PSSwitchTableCell
+ _OBJC_METACLASS_$_PABSSwitchTableCell
+ _OBJC_METACLASS_$_PSSwitchTableCell
+ _PABSSwitchTableCellLoadingKey
+ _UIApplicationWillEnterForegroundNotification
+ __OBJC_$_INSTANCE_METHODS_PABSSwitchTableCell
+ __OBJC_CLASS_RO_$_PABSSwitchTableCell
+ __OBJC_METACLASS_RO_$_PABSSwitchTableCell
+ ___block_descriptor_64_e8_32s40s48s56w_e19_v16?0"ACAccount"8ls32l8s40l8w56l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56w_e20_v20?0B8"NSError"12ls32l8s40l8s48l8w56l8
+ ___block_descriptor_73_e8_32s40s48s56s64w_e5_v8?0ls32l8s40l8s48l8s56l8w64l8
+ _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAA15ModifiedContentVyAcAE29navigationBarBackButtonHiddenyQrSbFQOyAA5GroupVyAA012_ConditionalI0Vy29PasscodeAndBiometricsSettings012PABSUnlockedC033_3802A58DA4E1D8E56B33C7255C8E20F1LLVAN010PABSLockedC0APLLVGG_Qo_AA19_BackgroundModifierVyAHyAN07HostingC17ControllerCaptureVAA12_FrameLayoutVGGG_SbQo_HO
+ _symbolic _____y_____y_____y_____y__________GG_Qo______yAAy__________GGG 7SwiftUI15ModifiedContentV AA4ViewPAAE29navigationBarBackButtonHiddenyQrSbFQO AA5GroupV AA012_ConditionalD0V 29PasscodeAndBiometricsSettings012PABSUnlockedE033_3802A58DA4E1D8E56B33C7255C8E20F1LLV AK010PABSLockedE0AMLLV AA19_BackgroundModifierV AK07HostingE17ControllerCaptureV AA12_FrameLayoutV
+ _symbolic _____y_____y_____y_____y_____y__________GG_Qo______yAAy__________GGG_SbQo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA15ModifiedContentV AcAE29navigationBarBackButtonHiddenyQrSbFQO AA5GroupV AA012_ConditionalI0V 29PasscodeAndBiometricsSettings012PABSUnlockedC033_3802A58DA4E1D8E56B33C7255C8E20F1LLV AN010PABSLockedC0APLLV AA19_BackgroundModifierV AN07HostingC17ControllerCaptureV AA12_FrameLayoutV
- GCC_except_table10
- GCC_except_table103
- GCC_except_table12
- GCC_except_table149
- GCC_except_table15
- GCC_except_table24
- GCC_except_table25
- GCC_except_table36
- GCC_except_table39
- GCC_except_table57
- GCC_except_table78
- GCC_except_table81
- GCC_except_table83
- _OBJC_CLASS_$_OBBaseWelcomeController
- ___block_descriptor_56_e8_32s40s48w_e19_v16?0"ACAccount"8lw48l8s32l8s40l8
- ___block_descriptor_56_e8_32s40s48w_e20_v20?0B8"NSError"12ls32l8s40l8w48l8
- ___block_descriptor_65_e8_32s40s48s56w_e5_v8?0ls32l8s40l8s48l8w56l8
- _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAA15ModifiedContentVyAA5GroupVyAA012_ConditionalI0Vy29PasscodeAndBiometricsSettings012PABSUnlockedC033_3802A58DA4E1D8E56B33C7255C8E20F1LLVAM010PABSLockedC0AOLLVGGAA19_BackgroundModifierVyAHyAM07HostingC17ControllerCaptureVAA12_FrameLayoutVGGG_SbQo_HO
- _symbolic _____y_____y_____y__________GG_____yAAy__________GGG 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V 29PasscodeAndBiometricsSettings16PABSUnlockedView33_3802A58DA4E1D8E56B33C7255C8E20F1LLV AH010PABSLockedL0AJLLV AA19_BackgroundModifierV AH07HostingL17ControllerCaptureV AA12_FrameLayoutV
- _symbolic _____y_____y_____y_____y__________GG_____yAAy__________GGG_SbQo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA15ModifiedContentV AA5GroupV AA012_ConditionalI0V 29PasscodeAndBiometricsSettings012PABSUnlockedC033_3802A58DA4E1D8E56B33C7255C8E20F1LLV AM010PABSLockedC0AOLLV AA19_BackgroundModifierV AM07HostingC17ControllerCaptureV AA12_FrameLayoutV
CStrings:
+ "Foregrounded — reloading specifiers"
+ "PABSSwitchTableCellLoadingKey"
+ "Reset Face ID: - Reloading Pane -"
```
