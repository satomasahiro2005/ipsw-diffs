## AppleMediaServicesUI

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/AppleMediaServicesUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23a820` | `0x23b8a0` | **`+0x1080`** |
| `__DATA.__bss` | `0xc6f0` | `0xc870` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0xb058` | `0xb1a0` | **`+0x148`** |
| `__TEXT.__const` | `0x10714` | `0x107e4` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x1130c` | `0x113a4` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0xb240` | `0xb2c0` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x9290` | `0x92f8` | **`+0x68`** |
| `__TEXT.__cstring` | `0xff87` | `0xffe7` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x2df8` | `0x2e50` | **`+0x58`** |
| `__DATA.__data` | `0x7d7c` | `0x7dcc` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x8cb0` | `0x8c60` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x3f60` | `0x3fa8` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x16734` | `0x16778` | **`+0x44`** |
| `__TEXT.__unwind_info` | `0x97d8` | `0x9818` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x228f8` | `0x22930` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x39e5` | `0x3a15` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x1e0c` | `0x1e2c` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x6db8` | `0x6dd4` | **`+0x1c`** |
| `__TEXT.__gcc_except_tab` | `0x1518` | `0x1504` | **`-0x14`** |
| `__AUTH.__data` | `0x6940` | `0x6950` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x90c0` | `0x90b0` | **`-0x10`** |
| `__DATA.__common` | `0x42a` | `0x41a` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3f90` | `0x3fa0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x5f8` | `0x604` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x1104` | `0x1108` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x504` | `0x508` | **`+0x4`** |

### Other Changes

```diff

-8.0.43.0.0
+8.0.45.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 16236
-  Symbols:   13387
-  CStrings:  3069
+  Functions: 16278
+  Symbols:   13412
+  CStrings:  3074
Symbols:
+ +[AMSUIWebView _runAction:context:depth:completion:]
+ +[AMSUIWebView runAction:context:completion:]
+ -[AMSUIToastPresentationController _accessibilityElement:isWithinView:]
+ -[AMSUIToastPresentationController _beginObservingVoiceOverFocus]
+ -[AMSUIToastPresentationController _endObservingVoiceOverFocus]
+ -[AMSUIToastPresentationController _isVoiceOverFocusedOnToast]
+ -[AMSUIToastPresentationController _voiceOverFocusDidChange:]
+ -[AMSUIToastPresentationController _voiceOverStatusDidChange:]
+ -[AMSUIToastPresentationController dealloc]
+ -[AMSUIToastPresentationController isDismissalPausedForVoiceOver]
+ -[AMSUIToastPresentationController setDismissalPausedForVoiceOver:]
+ GCC_except_table39
+ GCC_except_table51
+ _AudioServicesCreateSystemSoundID
+ _AudioServicesDisposeSystemSoundID
+ _OBJC_IVAR_$_AMSUIToastPresentationController._dismissalPausedForVoiceOver
+ _UIAccessibilityElementFocusedNotification
+ _UIAccessibilityFocusedElement
+ _UIAccessibilityFocusedElementKey
+ _UIAccessibilityNotificationVoiceOverIdentifier
+ ___46-[AMSUIWebFetchTreatmentAreasAction runAction]_block_invoke_5
+ ___52+[AMSUIWebView _runAction:context:depth:completion:]_block_invoke
+ ___block_descriptor_32_e15_16?0"NSSet"8l
+ ___block_descriptor_72_e8_32s40s48bs_e20_v24?08"NSError"16ls32l8s48l8s40l8
+ ___swift_closure_destructor.136Tm
+ ___swift_closure_destructor.56Tm
+ _associated conformance 20AppleMediaServicesUI26ReviewExtensionHostServiceC0G5Error33_18C8CE08C0219173CFCAE077BAD3B917LLOSHAASQ
+ _get_witness_table qd__7SwiftUI4ViewHD2_AaBPAAE29navigationBarTitleDisplayModeyQrAA010NavigationE4ItemV0fgH0OFQOyAcAE0dF0yQrqd__SyRd__lFQOyAA15ModifiedContentVyAcAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQOyAKyAcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAA5GroupVyAA012_ConditionalL0VyAXyAKyAKyAA08ProgressC0VyAA05EmptyC0VA0_GAA30_EnvironmentKeyWritingModifierVyAA11ControlSizeOGGAA16_FlexFrameLayoutVGAA0l11UnavailableC0VyAA5LabelVyAA4TextVAA5ImageVGA16_AA6ButtonVyA16_GGGAA4FormVyAA05TupleL0VyAA7SectionVyA0_A22_A16_GSg_AA7ForEachVySay018AppleMediaServicesB019NotificationSectionVG10Foundation4UUIDVA30_yA16_SgA34_ySayA35_012NotificationJ0CGA41_AA6ToggleVyA16_GGA42_GGQPGGGG_AA10ScenePhaseOQo_A35_017AuthenticateSheetC8ModifierVG_Qo_AA25_AppearanceActionModifierVG_SSQo__Qo_HO
+ _symbolic Say_____G s6UInt32V
+ _symbolic _____ 18AppleMediaServices24AMSPaymentExpandableInfoC
+ _symbolic _____ 20AppleMediaServicesUI26ReviewExtensionHostServiceC0G5Error33_18C8CE08C0219173CFCAE077BAD3B917LLO
+ _symbolic _____SgXw 20AppleMediaServicesUI26ReviewExtensionHostServiceC
+ _symbolic _____yAAy_____y_____y_____yACyAAyAAy_____y_____AEG_____y_____GG_____G_____y_____y__________GAO_____yAOGGG_____y_____y_____yAesOGSg______ySay_____G_____AXyAOSgA_ySay_____GA2______yAOGGA3_GGQPGGGG______Qo______G_____G 7SwiftUI15ModifiedContentV AA4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA5GroupV AA012_ConditionalD0V AA08ProgressE0V AA05EmptyE0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA16_FlexFrameLayoutV AA0d11UnavailableE0V AA5LabelV AA4TextV AA5ImageV AA6ButtonV AA4FormV AA05TupleD0V AA7SectionV AA7ForEachV 018AppleMediaServicesB019NotificationSectionV 10Foundation4UUIDV A13_16NotificationItemC AA6ToggleV AA10ScenePhaseO A13_017AuthenticateSheeteQ0V AA14_TaskModifier2V
+ _symbolic _____yScCy___________pGSgG 15Synchronization5MutexVAARi_zrlE 20AppleMediaServicesUI12ReviewResultO s5ErrorP
+ _symbolic _____yScCy___________pGSgG 15Synchronization5_CellVAARi_zrlE 20AppleMediaServicesUI12ReviewResultO s5ErrorP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s6UInt32V
+ _symbolic _____y_____yAAy_____y_____y_____yACyAAyAAy_____y_____AEG_____y_____GG_____G_____y_____y__________GAO_____yAOGGG_____y_____y_____yAesOGSg______ySay_____G_____AXyAOSgA_ySay_____GA2______yAOGGA3_GGQPGGGG______Qo______G_Qo______G 7SwiftUI15ModifiedContentV AA4ViewPAAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQO AeAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA5GroupV AA012_ConditionalD0V AA08ProgressE0V AA05EmptyE0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA16_FlexFrameLayoutV AA0d11UnavailableE0V AA5LabelV AA4TextV AA5ImageV AA6ButtonV AA4FormV AA05TupleD0V AA7SectionV AA7ForEachV 018AppleMediaServicesB019NotificationSectionV 10Foundation4UUIDV A19_16NotificationItemC AA6ToggleV AA10ScenePhaseO A19_017AuthenticateSheeteV0V AA017_AppearanceActionV0V
+ _symbolic _____y_____y_____yAAy_____y_____y_____yACyAAyAAy_____y_____AEG_____y_____GG_____G_____y_____y__________GAO_____yAOGGG_____y_____y_____yAesOGSg______ySay_____G_____AXyAOSgA_ySay_____GA2______yAOGGA3_GGQPGGGG______Qo______G_Qo______G_SSQo_ 7SwiftUI4ViewPAAE15navigationTitleyQrqd__SyRd__lFQO AA15ModifiedContentV AcAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQO AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA5GroupV AA012_ConditionalG0V AA08ProgressC0V AA05EmptyC0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA16_FlexFrameLayoutV AA0g11UnavailableC0V AA5LabelV AA4TextV AA5ImageV AA6ButtonV AA4FormV AA05TupleG0V AA7SectionV AA7ForEachV 018AppleMediaServicesB019NotificationSectionV 10Foundation4UUIDV A20_16NotificationItemC AA6ToggleV AA10ScenePhaseO A20_017AuthenticateSheetcX0V AA017_AppearanceActionX0V
+ _symbolic _____y_____y_____y_____yAAy_____y_____y_____yACyAAyAAy_____y_____AEG_____y_____GG_____G_____y_____y__________GAO_____yAOGGG_____y_____y_____yAesOGSg______ySay_____G_____AXyAOSgA_ySay_____GA2______yAOGGA3_GGQPGGGG______Qo______G_Qo______G_SSQo__Qo_ 7SwiftUI4ViewPAAE29navigationBarTitleDisplayModeyQrAA010NavigationE4ItemV0fgH0OFQO AcAE0dF0yQrqd__SyRd__lFQO AA15ModifiedContentV AcAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQO AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA5GroupV AA012_ConditionalL0V AA08ProgressC0V AA05EmptyC0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA16_FlexFrameLayoutV AA0l11UnavailableC0V AA5LabelV AA4TextV AA5ImageV AA6ButtonV AA4FormV AA05TupleL0V AA7SectionV AA7ForEachV 018AppleMediaServicesB019NotificationSectionV 10Foundation4UUIDV A25_012NotificationJ0C AA6ToggleV AA10ScenePhaseO A25_017AuthenticateSheetC8ModifierV AA25_AppearanceActionModifierV
+ _symbolic _____y_____y_____y_____yACyAAyAAy_____y_____AEG_____y_____GG_____G_____y_____y__________GAO_____yAOGGG_____y_____y_____yAesOGSg______ySay_____G_____AXyAOSgA_ySay_____GA2______yAOGGA3_GGQPGGGG______Qo______G 7SwiftUI15ModifiedContentV AA4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA5GroupV AA012_ConditionalD0V AA08ProgressE0V AA05EmptyE0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA16_FlexFrameLayoutV AA0d11UnavailableE0V AA5LabelV AA4TextV AA5ImageV AA6ButtonV AA4FormV AA05TupleD0V AA7SectionV AA7ForEachV 018AppleMediaServicesB019NotificationSectionV 10Foundation4UUIDV A13_16NotificationItemC AA6ToggleV AA10ScenePhaseO A13_017AuthenticateSheeteQ0V
- GCC_except_table36
- GCC_except_table45
- _OBJC_CLASS_$_AVAudioPlayer
- _OBJC_CLASS_$_NSDataAsset
- ___swift_closure_destructor.10Tm
- ___swift_closure_destructor.69Tm
- _get_witness_table 7SwiftUI15ModifiedContentVyAA4ViewPAAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQOyACyAeAE29navigationBarTitleDisplayModeyQrAA010NavigationL4ItemV0mnO0OFQOyAeAE0kM0yQrqd__SyRd__lFQOyAeAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAA5GroupVyAA012_ConditionalD0VyAXyACyACyAA08ProgressE0VyAA05EmptyE0VA0_GAA30_EnvironmentKeyWritingModifierVyAA11ControlSizeOGGAA16_FlexFrameLayoutVGAA0d11UnavailableE0VyAA5LabelVyAA4TextVAA5ImageVGA16_AA6ButtonVyA16_GGGAA4FormVyAA05TupleD0VyAA7SectionVyA0_A22_A16_GSg_AA7ForEachVySay018AppleMediaServicesB019NotificationSectionVG10Foundation4UUIDVA30_yA16_SgA34_ySayA35_012NotificationQ0CGA41_AA6ToggleVyA16_GGA42_GGQPGGGG_AA10ScenePhaseOQo__SSQo__Qo_A35_017AuthenticateSheetE8ModifierVG_Qo_AA25_AppearanceActionModifierVGAaDHPqd__AaDHD2_A64_HO_A66_AA0E8ModifierHPyHCHC
- _symbolic SaySo13AVAudioPlayerCG
- _symbolic Say_____G 18AppleMediaServices31AMSPaymentExpandableInfoDetailsC
- _symbolic So13AVAudioPlayerC
- _symbolic _____yAAy_____y_____y_____y_____y_____yACyAAyAAy_____y_____AEG_____y_____GG_____G_____y_____y__________GAO_____yAOGGG_____y_____y_____yAesOGSg______ySay_____G_____AXyAOSgA_ySay_____GA2______yAOGGA3_GGQPGGGG______Qo__SSQo__Qo______G_____G 7SwiftUI15ModifiedContentV AA4ViewPAAE29navigationBarTitleDisplayModeyQrAA010NavigationG4ItemV0hiJ0OFQO AeAE0fH0yQrqd__SyRd__lFQO AeAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA5GroupV AA012_ConditionalD0V AA08ProgressE0V AA05EmptyE0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA16_FlexFrameLayoutV AA0d11UnavailableE0V AA5LabelV AA4TextV AA5ImageV AA6ButtonV AA4FormV AA05TupleD0V AA7SectionV AA7ForEachV 018AppleMediaServicesB019NotificationSectionV 10Foundation4UUIDV A19_012NotificationL0C AA6ToggleV AA10ScenePhaseO A19_017AuthenticateSheeteX0V AA14_TaskModifier2V
- _symbolic _____y_____yAAy_____y_____y_____y_____y_____yACyAAyAAy_____y_____AEG_____y_____GG_____G_____y_____y__________GAO_____yAOGGG_____y_____y_____yAesOGSg______ySay_____G_____AXyAOSgA_ySay_____GA2______yAOGGA3_GGQPGGGG______Qo__SSQo__Qo______G_Qo______G 7SwiftUI15ModifiedContentV AA4ViewPAAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQO AeAE29navigationBarTitleDisplayModeyQrAA010NavigationL4ItemV0mnO0OFQO AeAE0kM0yQrqd__SyRd__lFQO AeAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA5GroupV AA012_ConditionalD0V AA08ProgressE0V AA05EmptyE0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA16_FlexFrameLayoutV AA0d11UnavailableE0V AA5LabelV AA4TextV AA5ImageV AA6ButtonV AA4FormV AA05TupleD0V AA7SectionV AA7ForEachV 018AppleMediaServicesB019NotificationSectionV 10Foundation4UUIDV A25_012NotificationQ0C AA6ToggleV AA10ScenePhaseO A25_017AuthenticateSheetE8ModifierV AA25_AppearanceActionModifierV
- _symbolic _____y_____y_____yABy_____yACy_____y_____AEG_____y_____GG_____G_____y_____y__________GAO_____yAOGGG_____y_____y_____yAesOGSg______ySay_____G_____AXyAOSgA_ySay_____GA2______yAOGGA3_GGQPGGGG______Qo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA5GroupV AA19_ConditionalContentV AA08ModifiedJ0V AA08ProgressC0V AA05EmptyC0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA16_FlexFrameLayoutV AA0j11UnavailableC0V AA5LabelV AA4TextV AA5ImageV AA6ButtonV AA4FormV AA05TupleJ0V AA7SectionV AA7ForEachV 018AppleMediaServicesB019NotificationSectionV 10Foundation4UUIDV A13_16NotificationItemC AA6ToggleV AA10ScenePhaseO
- _symbolic _____y_____y_____y_____yABy_____yACy_____y_____AEG_____y_____GG_____G_____y_____y__________GAO_____yAOGGG_____y_____y_____yAesOGSg______ySay_____G_____AXyAOSgA_ySay_____GA2______yAOGGA3_GGQPGGGG______Qo__SSQo_ 7SwiftUI4ViewPAAE15navigationTitleyQrqd__SyRd__lFQO AcAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA5GroupV AA19_ConditionalContentV AA08ModifiedL0V AA08ProgressC0V AA05EmptyC0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA16_FlexFrameLayoutV AA0l11UnavailableC0V AA5LabelV AA4TextV AA5ImageV AA6ButtonV AA4FormV AA05TupleL0V AA7SectionV AA7ForEachV 018AppleMediaServicesB019NotificationSectionV 10Foundation4UUIDV A14_16NotificationItemC AA6ToggleV AA10ScenePhaseO
- _symbolic _____y_____y_____y_____y_____y_____yACyAAyAAy_____y_____AEG_____y_____GG_____G_____y_____y__________GAO_____yAOGGG_____y_____y_____yAesOGSg______ySay_____G_____AXyAOSgA_ySay_____GA2______yAOGGA3_GGQPGGGG______Qo__SSQo__Qo______G 7SwiftUI15ModifiedContentV AA4ViewPAAE29navigationBarTitleDisplayModeyQrAA010NavigationG4ItemV0hiJ0OFQO AeAE0fH0yQrqd__SyRd__lFQO AeAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA5GroupV AA012_ConditionalD0V AA08ProgressE0V AA05EmptyE0V AA30_EnvironmentKeyWritingModifierV AA11ControlSizeO AA16_FlexFrameLayoutV AA0d11UnavailableE0V AA5LabelV AA4TextV AA5ImageV AA6ButtonV AA4FormV AA05TupleD0V AA7SectionV AA7ForEachV 018AppleMediaServicesB019NotificationSectionV 10Foundation4UUIDV A19_012NotificationL0C AA6ToggleV AA10ScenePhaseO A19_017AuthenticateSheeteX0V
CStrings:
+ "Could not create system sound. Status: "
+ "Could not find sound in bundle. Sound Name: "
+ "Maximum chain depth exceeded"
+ "failureAction"
+ "loadTerms: clientInfo="
+ "nextAction"
+ "successAction"
- "Could not create AVAudioPlayer with error: "
- "Could not load sound from bundle. Sound Name: "
```
