## AuthKitUI

> `/System/Library/PrivateFrameworks/AuthKitUI.framework/AuthKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd2024` | `0xd578c` | **`+0x3768`** |
| `__AUTH_CONST.__objc_const` | `0x170f8` | `0x17b18` | **`+0xa20`** |
| `__TEXT.__swift5_typeref` | `0x5a2` | `0xb44` | **`+0x5a2`** |
| `__DATA_CONST.__const` | `0x2bb0` | `0x2eb8` | **`+0x308`** |
| `__DATA.__bss` | `0x11f8` | `0x14f8` | **`+0x300`** |
| `__TEXT.__const` | `0xc44` | `0xf34` | **`+0x2f0`** |
| `__TEXT.__objc_methlist` | `0x843c` | `0x865c` | **`+0x220`** |
| `__DATA.__data` | `0x1bb0` | `0x1db8` | **`+0x208`** |
| `__AUTH.__objc_data` | `0x1fe0` | `0x2160` | **`+0x180`** |
| `__TEXT.__cstring` | `0x54bd` | `0x563d` | **`+0x180`** |
| `__AUTH_CONST.__auth_got` | `0xa58` | `0xbb8` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x18f0` | `0x1a28` | **`+0x138`** |
| `__DATA_CONST.__objc_selrefs` | `0x5db8` | `0x5ec8` | **`+0x110`** |
| `__AUTH.__data` | `0x128` | `0x228` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0x84` | `0x182` | **`+0xfe`** |
| `__AUTH_CONST.__cfstring` | `0x4fc0` | `0x5080` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x510` | `0x5d0` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x538` | `0x5f0` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0x13c` | `0x1d0` | **`+0x94`** |
| `__TEXT.__oslogstring` | `0x53ff` | `0x547f` | **`+0x80`** |
| `__TEXT.__swift5_assocty` | `0xd8` | `0x150` | **`+0x78`** |
| `__TEXT.__constg_swiftt` | `0x2a8` | `0x300` | **`+0x58`** |
| `__DATA_CONST.__got` | `0xe08` | `0xe50` | **`+0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x3a0` | `0x3c0` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x208` | `0x220` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x80` | `0x98` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `0x28` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1028` | `0x1038` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x48` | `0x58` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x73c` | `0x744` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2c` | `0x34` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x14` | `0x1c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x4` | `—` | **`-0x4`** |

### Other Changes

```diff

-550.0.0.0.0
+552.0.0.0.0

-  Functions: 3031
-  Symbols:   5512
-  CStrings:  1265
+  Functions: 3171
+  Symbols:   5634
+  CStrings:  1283
Symbols:
+ +[AKAppleLogoMicaView animatedView]
+ +[AKAppleLogoMicaView staticView]
+ +[AKDisplayNameFormatter displayNameForAccount:]
+ +[AKDisplayNameFormatter displayNameWithGivenName:familyName:]
+ +[AKUIAvatarImageProvider fetchAvatarImageForContext:completion:]
+ -[AKAppleLogoMicaView _initWithAnimation:]
+ -[AKAppleLogoMicaView setShouldAnimate:]
+ -[AKAppleLogoMicaView shouldAnimate]
+ -[AKAuthorizationPaneViewController _safeContentTrayOffsetAdjustedForScrollInset:]
+ -[AKBasicLoginViewController _initializeAppleLogo]
+ -[AKBasicLoginViewController appleLogoMicaView]
+ -[AKBasicLoginViewController setAppleLogoMicaView:]
+ -[AKModalSignInViewController _setupAccountRowView]
+ -[AKModalSignInViewController accountRowView]
+ -[AKModalSignInViewController isAnimating]
+ -[AKModalSignInViewController setAccountRowView:]
+ -[AKModalSignInViewController setIsAnimating:]
+ GCC_except_table83
+ GCC_except_table94
+ _AKSafeCGFloatMax
+ _OBJC_CLASS_$_AKDisplayNameFormatter
+ _OBJC_CLASS_$_AKUIAccountAvatarConfiguration
+ _OBJC_CLASS_$_AKUIAvatarImageProvider
+ _OBJC_CLASS_$_AKUIUserAvatarView
+ _OBJC_CLASS_$_NSAttributedString
+ _OBJC_IVAR_$_AKAppleLogoMicaView._shouldAnimate
+ _OBJC_IVAR_$_AKBasicLoginViewController._appleLogoMicaView
+ _OBJC_IVAR_$_AKModalSignInViewController._accountRowView
+ _OBJC_IVAR_$_AKModalSignInViewController._isAnimating
+ _OBJC_METACLASS_$_AKDisplayNameFormatter
+ _OBJC_METACLASS_$_AKUIAccountAvatarConfiguration
+ _OBJC_METACLASS_$_AKUIAvatarImageProvider
+ _OBJC_METACLASS_$_AKUIUserAvatarView
+ __DATA_AKUIAccountAvatarConfiguration
+ __DATA_AKUIUserAvatarView
+ __INSTANCE_METHODS_AKUIAccountAvatarConfiguration
+ __INSTANCE_METHODS_AKUIUserAvatarView
+ __IVARS_AKUIAccountAvatarConfiguration
+ __IVARS_AKUIUserAvatarView
+ __METACLASS_DATA_AKUIAccountAvatarConfiguration
+ __METACLASS_DATA_AKUIUserAvatarView
+ __OBJC_$_CLASS_METHODS_AKAppleLogoMicaView
+ __OBJC_$_CLASS_METHODS_AKDisplayNameFormatter
+ __OBJC_$_CLASS_METHODS_AKUIAvatarImageProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AKApprovalFlowCodeRequestDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AKApprovalFlowCodeRequestDelegate
+ __OBJC_$_PROTOCOL_REFS_AKApprovalFlowCodeRequestDelegate
+ __OBJC_CLASS_RO_$_AKDisplayNameFormatter
+ __OBJC_CLASS_RO_$_AKUIAvatarImageProvider
+ __OBJC_LABEL_PROTOCOL_$_AKApprovalFlowCodeRequestDelegate
+ __OBJC_METACLASS_RO_$_AKDisplayNameFormatter
+ __OBJC_METACLASS_RO_$_AKUIAvatarImageProvider
+ __OBJC_PROTOCOL_$_AKApprovalFlowCodeRequestDelegate
+ __PROPERTIES_AKUIAccountAvatarConfiguration
+ __PROPERTIES_AKUIUserAvatarView
+ ___43-[AKModalSignInViewController _createViews]_block_invoke
+ ___65+[AKUIAvatarImageProvider fetchAvatarImageForContext:completion:]_block_invoke
+ ___65+[AKUIAvatarImageProvider fetchAvatarImageForContext:completion:]_block_invoke_2
+ ___block_descriptor_32_e18_v16?0"UIButton"8l
+ ___block_descriptor_40_e8_32bs_e29_v24?0"UIImage"8"NSError"16ls32l8
+ ___getAAUIProfilePictureStoreClass_block_invoke
+ ___swift_project_boxed_opaque_existential_0
+ ___swift_project_boxed_opaque_existential_0Tm
+ __swift_stdlib_reportUnimplementedInitializer
+ _associated conformance 9AuthKitUI25AKUIUserAvatarViewContent33_7DBAB36D1581C9B87813BB1CC248727DLLV05SwiftC00F0AA4BodyAeFP_AeF
+ _associated conformance So12CACornerMaskVs10SetAlgebraSCSQ
+ _associated conformance So12CACornerMaskVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So12CACornerMaskVs9OptionSetSCSY
+ _associated conformance So12CACornerMaskVs9OptionSetSCs0D7Algebra
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _flat unique So33AKApprovalFlowCodeRequestDelegate_p
+ _getAAUIProfilePictureStoreClass
+ _getAAUIProfilePictureStoreClass.softClass
+ _get_witness_table qd__7SwiftUI4ViewHD2_AaBPAAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQOyAA15ModifiedContentVyAKyAKyAA6HStackVyAA05TupleJ0VyAKyAKyAA5GroupVyAA012_ConditionalJ0VyAKyAA5ImageVAA18_AspectRatioLayoutVGAKyAuA24_ForegroundStyleModifierVyAA5ColorVGGGGAA06_FrameR0VGAA11_ClipEffectVyAA6CircleVGG_AA6VStackVyAOyAA4TextVSg_A18_QPGGAA6SpacerVQPGGAA08_PaddingR0VGA26_GAA011_BackgroundU0VyAA06_ShapeC0VyAA22UnevenRoundedRectangleVA0_GGG_Qo_HO
+ _kCBBrightnessBoostEnd
+ _kCBBrightnessBoostFull
+ _kCBBrightnessBoostFullEnd
+ _kCBBrightnessBoostScaler
+ _kCBBrightnessBoostStart
+ _objc_allocWithZone
+ _objc_release_x22
+ _objc_release_x8
+ _objc_retain_x19
+ _objc_retain_x2
+ _objc_retain_x20
+ _objc_retain_x22
+ _objc_retain_x8
+ _swift_allocError
+ _swift_beginAccess
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_continuation_resume
+ _swift_continuation_throwingResume
+ _swift_continuation_throwingResumeWithError
+ _swift_dynamicCastClass
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassMetadata
+ _swift_release_x21
+ _swift_release_x27
+ _swift_release_x28
+ _swift_retain
+ _symbolic $ss10SetAlgebraP
+ _symbolic $ss25ExpressibleByArrayLiteralP
+ _symbolic $ss9OptionSetP
+ _symbolic SSSg
+ _symbolic SccySS______pG s5ErrorP
+ _symbolic SccySo7UIImageCSg_____G s5NeverO
+ _symbolic So30AKAppleIDAuthenticationContextC
+ _symbolic So7UIColorCSg
+ _symbolic So7UIImageCSg
+ _symbolic Su
+ _symbolic _____ 12CoreGraphics7CGFloatV
+ _symbolic _____ 9AuthKitUI25AKUIUserAvatarViewContent33_7DBAB36D1581C9B87813BB1CC248727DLLV
+ _symbolic _____ So12CACornerMaskV
+ _symbolic ______p So33AKApprovalFlowCodeRequestDelegateP
+ _symbolic ______p s5ErrorP
+ _symbolic ______pSg So33AKApprovalFlowCodeRequestDelegateP
+ _symbolic _____yAAyAAyAAy_____y_____yAAyAAy_____y_____yAAy__________GAAyAF_____y_____GGGG_____G_____y_____GG______yACy_____Sg_AWQPGG_____QPGG_____GA1_G_____y_____y_____AJGGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5GroupV AA012_ConditionalD0V AA5ImageV AA18_AspectRatioLayoutV AA24_ForegroundStyleModifierV AA5ColorV AA06_FrameL0V AA11_ClipEffectV AA6CircleV AA6VStackV AA4TextV AA6SpacerV AA08_PaddingL0V AA011_BackgroundO0V AA10_ShapeViewV AA22UnevenRoundedRectangleV AA14_TaskModifier2V
+ _symbolic _____yAAyAAy_____y_____yAAyAAy_____y_____yAAy__________GAAyAF_____y_____GGGG_____G_____y_____GG______yACy_____Sg_AWQPGG_____QPGG_____GA1_G_____y_____y_____AJGGG 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5GroupV AA012_ConditionalD0V AA5ImageV AA18_AspectRatioLayoutV AA24_ForegroundStyleModifierV AA5ColorV AA06_FrameL0V AA11_ClipEffectV AA6CircleV AA6VStackV AA4TextV AA6SpacerV AA08_PaddingL0V AA011_BackgroundO0V AA10_ShapeViewV AA22UnevenRoundedRectangleV
+ _symbolic _____yAAy_____y_____yAAyAAy_____y_____yAAy__________GAAyAF_____y_____GGGG_____G_____y_____GG______yACy_____Sg_AWQPGG_____QPGG_____GA1_G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5GroupV AA012_ConditionalD0V AA5ImageV AA18_AspectRatioLayoutV AA24_ForegroundStyleModifierV AA5ColorV AA06_FrameL0V AA11_ClipEffectV AA6CircleV AA6VStackV AA4TextV AA6SpacerV AA08_PaddingL0V
+ _symbolic _____yAAy_____y_____yAAy__________GAAyAD_____y_____GGGG_____G_____y_____GG 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V AA5ImageV AA18_AspectRatioLayoutV AA24_ForegroundStyleModifierV AA5ColorV AA06_FrameJ0V AA11_ClipEffectV AA6CircleV
+ _symbolic _____ySo7UIImageCSgG 7SwiftUI9LazyStateV
+ _symbolic _____ySo7UIImageCSg_G 7SwiftUI9LazyStateV7StorageO
+ _symbolic _____ySo7UIImageCSg_G_yXlSgt 7SwiftUI9LazyStateV7StorageO
+ _symbolic _____y_____G 7SwiftUI14_UIHostingViewC 07AuthKitB0014AKUIUserAvatarD7Content33_7DBAB36D1581C9B87813BB1CC248727DLLV
+ _symbolic _____y__________G 7SwiftUI10_ShapeViewV AA22UnevenRoundedRectangleV AA5ColorV
+ _symbolic _____y_____yAAyAAy_____y_____yAAyAAy_____y_____yAAy__________GAAyAF_____y_____GGGG_____G_____y_____GG______yACy_____Sg_AWQPGG_____QPGG_____GA1_G_____y_____y_____AJGGG_Qo_ 7SwiftUI4ViewPAAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQO AA15ModifiedContentV AA6HStackV AA05TupleJ0V AA5GroupV AA012_ConditionalJ0V AA5ImageV AA18_AspectRatioLayoutV AA24_ForegroundStyleModifierV AA5ColorV AA06_FrameR0V AA11_ClipEffectV AA6CircleV AA6VStackV AA4TextV AA6SpacerV AA08_PaddingR0V AA011_BackgroundU0V AA06_ShapeC0V AA22UnevenRoundedRectangleV
+ _symbolic _____y_____y_____Sg_ADQPGG 7SwiftUI6VStackV AA12TupleContentV AA4TextV
+ _symbolic _____y_____y__________GG 7SwiftUI19_BackgroundModifierV AA10_ShapeViewV AA22UnevenRoundedRectangleV AA5ColorV
+ _symbolic _____y_____y_____yAAyAAy_____y_____yAAy__________GAAyAF_____y_____GGGG_____G_____y_____GG______yACy_____Sg_AWQPGG_____QPGG_____G 7SwiftUI15ModifiedContentV AA6HStackV AA05TupleD0V AA5GroupV AA012_ConditionalD0V AA5ImageV AA18_AspectRatioLayoutV AA24_ForegroundStyleModifierV AA5ColorV AA06_FrameL0V AA11_ClipEffectV AA6CircleV AA6VStackV AA4TextV AA6SpacerV AA08_PaddingL0V
+ _symbolic _____y_____y_____yAAy__________GAAyAD_____y_____GGGG_____G 7SwiftUI15ModifiedContentV AA5GroupV AA012_ConditionalD0V AA5ImageV AA18_AspectRatioLayoutV AA24_ForegroundStyleModifierV AA5ColorV AA06_FrameJ0V
+ _symbolic _____y_____y_____yACy_____y_____yACy__________GACyAF_____y_____GGGG_____G_____y_____GG______yABy_____Sg_AWQPGG_____QPGG 7SwiftUI6HStackV AA12TupleContentV AA08ModifiedE0V AA5GroupV AA012_ConditionalE0V AA5ImageV AA18_AspectRatioLayoutV AA24_ForegroundStyleModifierV AA5ColorV AA06_FrameL0V AA11_ClipEffectV AA6CircleV AA6VStackV AA4TextV AA6SpacerV
+ _symbolic _____yyXlG s23_ContiguousArrayStorageC
+ _type_layout_string So12CACornerMaskV
- -[AKModalSignInViewController _setupUsernameField]
- -[AKModalSignInViewController _shouldHideUsernameField]
- -[AKModalSignInViewController isSolariumEnabled]
- -[AKModalSignInViewController setIsSolariumEnabled:]
- -[AKModalSignInViewController setUsernameField:]
- -[AKModalSignInViewController usernameField]
- GCC_except_table88
- GCC_except_table99
- _OBJC_IVAR_$_AKModalSignInViewController._isSolariumEnabled
- _OBJC_IVAR_$_AKModalSignInViewController._usernameField
- _swift_coroFrameAlloc
- _symbolic $s9AuthKitUI33AKApprovalFlowCodeRequestDelegateP
- _symbolic ______p 9AuthKitUI33AKApprovalFlowCodeRequestDelegateP
- _symbolic ______pSg 9AuthKitUI33AKApprovalFlowCodeRequestDelegateP
CStrings:
+ "AAUIProfilePictureStore"
+ "AuthKitUI/AKUIUserAvatarView.swift"
+ "AuthKitUI_Internal.AKUIAccountAvatarConfiguration"
+ "AuthKitUI_Internal.AKUIUserAvatarView"
+ "Avatar fetch skipped — AIDA account unavailable: %{mask.hash}@"
+ "Avatar fetch skipped — iCloud account unavailable: %{mask.hash}@"
+ "Fatal error"
+ "SignInAppleLogo"
+ "View.task @ AuthKitUI/AKUIUserAvatarView.swift:"
+ "boostEnd"
+ "boostFull"
+ "boostFullEnd"
+ "boostScaler"
+ "boostStart"
+ "init()"
+ "init(coder:) not supported"
+ "init(frame:)"
+ "person.circle.fill"
```
