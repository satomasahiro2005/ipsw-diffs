## HealthSettingsUI

> `/System/Library/PrivateFrameworks/HealthSettingsUI.framework/HealthSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x166ec` | `0x1e62c` | **`+0x7f40`** |
| `__DATA.__bss` | `0xe88` | `0x388` | **`-0xb00`** |
| `__TEXT.__eh_frame` | `0x63c` | `0xb34` | **`+0x4f8`** |
| `__TEXT.__const` | `0xd58` | `0x8c8` | **`-0x490`** |
| `__AUTH_CONST.__const` | `0x598` | `0x800` | **`+0x268`** |
| `__TEXT.__swift5_capture` | `0xf8` | `0x328` | **`+0x230`** |
| `__AUTH_CONST.__objc_const` | `0x1030` | `0xe90` | **`-0x1a0`** |
| `__TEXT.__unwind_info` | `0x700` | `0x890` | **`+0x190`** |
| `__TEXT.__swift5_typeref` | `0x434` | `0x5b2` | **`+0x17e`** |
| `__AUTH_CONST.__auth_got` | `0x9a0` | `0xb18` | **`+0x178`** |
| `__DATA_DIRTY.__bss` | `0x290` | `0x180` | **`-0x110`** |
| `__TEXT.__cstring` | `0x7f4` | `0x8fa` | **`+0x106`** |
| `__DATA_CONST.__got` | `0x4a8` | `0x568` | **`+0xc0`** |
| `__DATA.__data` | `0x760` | `0x800` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x278` | `0x1e0` | **`-0x98`** |
| `__TEXT.__oslogstring` | `0x413` | `0x496` | **`+0x83`** |
| `__AUTH.__data` | `0x198` | `0x210` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x9c4` | `0x94c` | **`-0x78`** |
| `__TEXT.__swift5_proto` | `0x84` | `0x24` | **`-0x60`** |
| `__DATA_DIRTY.__objc_data` | `0x190` | `0x1e0` | **`+0x50`** |
| `__AUTH.__objc_data` | `0x2c0` | `0x308` | **`+0x48`** |
| `__TEXT.__swift_as_cont` | `0x48` | `0x8c` | **`+0x44`** |
| `__TEXT.__gcc_except_tab` | `0xc4` | `0xf4` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x198` | `0x1c0` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x48` | **`+0x24`** |
| `__TEXT.__swift_as_ret` | `0x24` | `0x48` | **`+0x24`** |
| `__DATA_CONST.__const` | `0x3a0` | `0x380` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x261` | `0x27d` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x48` | `0x60` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__objc_superrefs` | `0x30` | `0x20` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x38` | `0x28` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x54` | `0x48` | **`-0xc`** |
| `__TEXT.__constg_swiftt` | `0x368` | `0x374` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x58` | `0x50` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x750` | `0x748` | **`-0x8`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 605
-  Symbols:   687
-  CStrings:  80
+  Functions: 674
+  Symbols:   657
+  CStrings:  90
Symbols:
+ -[HKHealthSettingsController _updateTitle]
+ -[HKHealthSettingsController addPersonalizedSuggestionsSpecifier]
+ -[HKHealthSettingsController fetchPersonalizedSuggestionsAvailability]
+ -[HKHealthSettingsController personalizedSuggestionsSpecifier]
+ -[HKHealthSettingsController setPersonalizedSuggestionsSpecifier:]
+ GCC_except_table0
+ GCC_except_table21
+ GCC_except_table23
+ GCC_except_table25
+ GCC_except_table28
+ GCC_except_table36
+ GCC_except_table38
+ GCC_except_table6
+ _OBJC_CLASS_$_HKProfileIdentifier
+ _OBJC_IVAR_$_HKHealthSettingsController._personalizedSuggestionsAvailable
+ _OBJC_IVAR_$_HKHealthSettingsController._personalizedSuggestionsSpecifier
+ __CLASS_METHODS_HKHealthSettingsProfile
+ __DATA_HKHealthSettingsProfile
+ __INSTANCE_METHODS_HKHealthSettingsProfile
+ __IVARS_HKHealthSettingsProfile
+ __METACLASS_DATA_HKHealthSettingsProfile
+ __PROPERTIES_HKHealthSettingsProfile
+ ___42-[HKHealthSettingsController _updateTitle]_block_invoke
+ ___51-[HKHealthSettingsController fetchSharedHealthData]_block_invoke_3
+ ___51-[HKHealthSettingsOrganDonationViewController init]_block_invoke
+ ___70-[HKHealthSettingsController fetchPersonalizedSuggestionsAvailability]_block_invoke
+ ___70-[HKHealthSettingsController fetchPersonalizedSuggestionsAvailability]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e18_v16?0"NSString"8lw32l8
+ ___block_descriptor_40_e8_32w_e26_v16?0"_HKMedicalIDData"8lw32l8
+ ___block_descriptor_41_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_48_e8_32s40w_e5_v8?0ls32l8w40l8
+ ___swift_closure_destructor.32Tm
+ ___swift_closure_destructor.3Tm
+ ___swift_closure_destructor.42Tm
+ __swiftEmptyDictionarySingleton
+ __swift_implicitisolationactor_to_executor_cast
+ __swift_stdlib_reportUnimplementedInitializer
+ _bzero
+ _get_witness_table qd__7SwiftUI4ViewHD2_AaBPAAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQOyAcAE5alert_11isPresented7actions7messageQrqd___AA7BindingVySbGqd_0_yXEqd_1_yXEtSyRd__AaBRd_0_AaBRd_1_r1_lFQOyAcAE29navigationBarTitleDisplayModeyQrAA010NavigationP4ItemV0qrS0OFQOyAcAE0oQ0yQrqd__SyRd__lFQOyAA4ListVys5NeverOAA12TupleContentVyAA7SectionVyAA05EmptyC0VAA08ModifiedY0VyAA6VStackVyA0_yA6_yA6_yA6_yA6_yA6_yAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA24_ForegroundStyleModifierVyAA5ColorVGGAA12_FrameLayoutVGAA34_InsettableBackgroundShapeModifierVyA21_AA16RoundedRectangleVGGAA31AccessibilityAttachmentModifierVG_AA4TextVA37_QPGGAA14_PaddingLayoutVGA4_G_A2_yA37_A6_yAA6ToggleVyA37_GAA32_EnvironmentKeyTransformModifierVySbGGA37_GQPGG_SSQo__Qo__SSA0_yAA6ButtonVyA37_G_A58_QPGA37_Qo__Qo_HO
+ _objc_release_x1
+ _objc_retain_x27
+ _swift_arrayDestroy
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_deletedAsyncMethodErrorTu
+ _swift_getExistentialTypeMetadata
+ _swift_getForeignTypeMetadata
+ _swift_getTupleTypeMetadata3
+ _swift_isaMask
+ _swift_release_x26
+ _swift_retain_x20
+ _swift_retain_x25
+ _swift_retain_x26
+ _swift_retain_x8
+ _symbolic $sSY
+ _symbolic Iegh_
+ _symbolic IeyBh_
+ _symbolic SSIeAgHr_
+ _symbolic SSIeghg_
+ _symbolic SSSg
+ _symbolic SaySo19HKProfileIdentifierCG
+ _symbolic SaySo19HKProfileIdentifierCGSgIeghg_
+ _symbolic SbIeghy_
+ _symbolic SbSo13HKHealthStoreCYaYbc
+ _symbolic ScCySo16_HKMedicalIDDataCSg_____G s5NeverO
+ _symbolic ScCy__________G 10Foundation20PersonNameComponentsV s5NeverO
+ _symbolic ScTySS_____GSg s5NeverO
+ _symbolic Si
+ _symbolic So16_HKMedicalIDDataCSgIeghg_
+ _symbolic So16_HKMedicalIDDataCSgIeyBhy_
+ _symbolic So7NSArrayCSgIeyBhy_
+ _symbolic So8NSStringCIeyBhy_
+ _symbolic So9WDProfileC
+ _symbolic _____ 16HealthSettingsUI08HKHealthB7ProfileC
+ _symbolic _____ So13HKProfileTypeV
+ _symbolic _____7profile_t 16HealthSettingsUI08HKHealthB7ProfileC
+ _symbolic _____IeyBhy_ 10ObjectiveC8ObjCBoolV
+ _symbolic _____Sg 7SwiftUI4FontV
+ _symbolic _____XDXMT 16HealthSettingsUI08HKHealthB7ProfileC
+ _symbolic _____XMT 16HealthSettingsUI08HKHealthB7ProfileC
+ _symbolic _____y_____y_____y_____y_____y__________y_____y__________y_____yACyAFyAFyAFyAFyAFy__________y_____SgGG_____y_____GG_____G_____yAO_____GG_____G______AZQPGG_____GAEG_ADyAzFy_____yAZG_____ySbGGAZGQPGG_SSQo__Qo__SSACy_____yAZG_A15_QPGAZQo__Qo_ 7SwiftUI4ViewPAAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQO AcAE5alert_11isPresented7actions7messageQrqd___AA7BindingVySbGqd_0_yXEqd_1_yXEtSyRd__AaBRd_0_AaBRd_1_r1_lFQO AcAE29navigationBarTitleDisplayModeyQrAA010NavigationP4ItemV0qrS0OFQO AcAE0oQ0yQrqd__SyRd__lFQO AA4ListV s5NeverO AA12TupleContentV AA7SectionV AA05EmptyC0V AA08ModifiedY0V AA6VStackV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA24_ForegroundStyleModifierV AA5ColorV AA12_FrameLayoutV AA34_InsettableBackgroundShapeModifierV AA16RoundedRectangleV AA31AccessibilityAttachmentModifierV AA4TextV AA14_PaddingLayoutV AA6ToggleV AA32_EnvironmentKeyTransformModifierV AA6ButtonV
- +[HKHealthSettingsProfile sharedProfile]
- -[HKHealthSettingsProfile .cxx_destruct]
- -[HKHealthSettingsProfile fetchMedicalIDDataSynchronously]
- -[HKHealthSettingsProfile getNameComponents]
- -[HKHealthSettingsProfile getProfilesOfType:completion:]
- -[HKHealthSettingsProfile initWithProfileIdentifier:]
- -[HKHealthSettingsProfile localizedName]
- -[HKHealthSettingsProfile nameComponents]
- -[HKHealthSettingsProfile presentationContext]
- -[HKHealthSettingsProfile profileStore]
- -[HKHealthSettingsProfile setLocalizedName:]
- -[HKHealthSettingsProfile setNameComponents:]
- -[HKHealthSettingsProfileTableViewController .cxx_destruct]
- -[HKHealthSettingsProfileTableViewController canBeShownFromSuspendedState]
- -[HKHealthSettingsProfileTableViewController handleURL:withCompletion:]
- -[HKHealthSettingsProfileTableViewController init]
- -[HKHealthSettingsProfileTableViewController parentController]
- -[HKHealthSettingsProfileTableViewController readPreferenceValue:]
- -[HKHealthSettingsProfileTableViewController rootController]
- -[HKHealthSettingsProfileTableViewController setParentController:]
- -[HKHealthSettingsProfileTableViewController setPreferenceValue:specifier:]
- -[HKHealthSettingsProfileTableViewController setRootController:]
- -[HKHealthSettingsProfileTableViewController setSpecifier:]
- -[HKHealthSettingsProfileTableViewController showController:]
- -[HKHealthSettingsProfileTableViewController showController:animate:]
- -[HKHealthSettingsProfileTableViewController specifier]
- GCC_except_table10
- GCC_except_table19
- GCC_except_table22
- GCC_except_table29
- GCC_except_table31
- _HKLogQuery
- _OBJC_CLASS_$_HKHealthSettingsProfileTableViewController
- _OBJC_CLASS_$_NSPersonNameComponents
- _OBJC_CLASS_$_NSPredicate
- _OBJC_IVAR_$_HKHealthSettingsProfile._localizedName
- _OBJC_IVAR_$_HKHealthSettingsProfile._nameComponents
- _OBJC_IVAR_$_HKHealthSettingsProfileTableViewController._parentController
- _OBJC_IVAR_$_HKHealthSettingsProfileTableViewController._rootController
- _OBJC_IVAR_$_HKHealthSettingsProfileTableViewController._specifier
- _OBJC_METACLASS_$_HKHealthSettingsProfileTableViewController
- _OBJC_METACLASS_$_ProfileCharacteristicsViewController
- __Block_object_dispose
- __OBJC_$_CLASS_METHODS_HKHealthSettingsProfile
- __OBJC_$_INSTANCE_METHODS_HKHealthSettingsProfile
- __OBJC_$_INSTANCE_METHODS_HKHealthSettingsProfileTableViewController
- __OBJC_$_INSTANCE_VARIABLES_HKHealthSettingsProfile
- __OBJC_$_INSTANCE_VARIABLES_HKHealthSettingsProfileTableViewController
- __OBJC_$_PROP_LIST_HKHealthSettingsProfile
- __OBJC_$_PROP_LIST_HKHealthSettingsProfileTableViewController
- __OBJC_CLASS_PROTOCOLS_$_HKHealthSettingsProfileTableViewController
- __OBJC_CLASS_RO_$_HKHealthSettingsProfile
- __OBJC_CLASS_RO_$_HKHealthSettingsProfileTableViewController
- __OBJC_METACLASS_RO_$_HKHealthSettingsProfile
- __OBJC_METACLASS_RO_$_HKHealthSettingsProfileTableViewController
- ___40+[HKHealthSettingsProfile sharedProfile]_block_invoke
- ___44-[HKHealthSettingsProfile getNameComponents]_block_invoke
- ___56-[HKHealthSettingsProfile getProfilesOfType:completion:]_block_invoke
- ___58-[HKHealthSettingsProfile fetchMedicalIDDataSynchronously]_block_invoke
- ___Block_byref_object_copy_
- ___Block_byref_object_dispose_
- ___block_descriptor_40_e5_v8?0l
- ___block_descriptor_48_e8_32s40r_e38_v24?0"_HKMedicalIDData"8"NSError"16lr40l8s32l8
- ___block_descriptor_48_e8_32s40s_e5_v8?0ls32l8s40l8
- ___block_descriptor_56_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16ls40l8s32l8
- ___block_descriptor_56_e8_32s40s48r_e43_v32?0"NSString"8"NSString"16"NSError"24lr48l8s32l8s40l8
- ___swift_destroy_boxed_opaque_existential_1
- ___swift_memcpy0_1
- ___swift_memcpy16_8
- ___swift_memcpy1_1
- ___swift_noop_void_return
- ___swift_project_boxed_opaque_existential_1
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO0A17DetailsCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs0G3KeyAAs23CustomStringConvertible
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO0A17DetailsCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs0G3KeyAAs28CustomDebugStringConvertible
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO10CodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOSHAASQ
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO10CodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO10CodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs0F3KeyAAs28CustomDebugStringConvertible
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO17SourcesCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOSHAASQ
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO17SourcesCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs0G3KeyAAs23CustomStringConvertible
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO17SourcesCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs0G3KeyAAs28CustomDebugStringConvertible
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO19MedicalIDCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs9CodingKeyAAs23CustomStringConvertible
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO19MedicalIDCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs9CodingKeyAAs28CustomDebugStringConvertible
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO31PreferencesControllerCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOSHAASQ
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO31PreferencesControllerCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO31PreferencesControllerCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs0H3KeyAAs28CustomDebugStringConvertible
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO33PersonalizedSuggestionsCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 16HealthSettingsUI0aB21NavigationDestinationO33PersonalizedSuggestionsCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLOs0H3KeyAAs28CustomDebugStringConvertible
- _dispatch_group_create
- _dispatch_group_enter
- _dispatch_group_leave
- _dispatch_group_wait
- _dispatch_once
- _dispatch_semaphore_create
- _dispatch_semaphore_signal
- _dispatch_semaphore_wait
- _dispatch_time
- _get_witness_table qd__7SwiftUI4ViewHD2_AaBPAAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQOyAcAE29navigationBarTitleDisplayModeyQrAA010NavigationJ4ItemV0klM0OFQOyAcAE0iK0yQrqd__SyRd__lFQOyAA4ListVys5NeverOAA7SectionVyAA05EmptyC0VAA15ModifiedContentVyAA6ToggleVyAA4TextVGAA32_EnvironmentKeyTransformModifierVySbGGA1_GG_SSQo__Qo__Qo_HO
- _sharedProfile.onceToken
- _sharedProfile.sharedProfile
- _swift_allocError
- _swift_getExistentialMetatypeMetadata
- _swift_willThrow
- _symbolic SbSo13HKHealthStoreCYbc
- _symbolic _____ 16HealthSettingsUI0aB21NavigationDestinationO0A17DetailsCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLO
- _symbolic _____ 16HealthSettingsUI0aB21NavigationDestinationO10CodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLO
- _symbolic _____ 16HealthSettingsUI0aB21NavigationDestinationO17SourcesCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLO
- _symbolic _____ 16HealthSettingsUI0aB21NavigationDestinationO19MedicalIDCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLO
- _symbolic _____ 16HealthSettingsUI0aB21NavigationDestinationO31PreferencesControllerCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLO
- _symbolic _____ 16HealthSettingsUI0aB21NavigationDestinationO33PersonalizedSuggestionsCodingKeys33_C9333E6DE88A552246E4591CFDEBD840LLO
- _symbolic _____y_____y_____y_____y__________y__________y_____y_____G_____ySbGGAGGG_SSQo__Qo__Qo_ 7SwiftUI4ViewPAAE4task4name8priority4file4line_QrSSSg_ScPSSSiyyYaYAcntFQO AcAE29navigationBarTitleDisplayModeyQrAA010NavigationJ4ItemV0klM0OFQO AcAE0iK0yQrqd__SyRd__lFQO AA4ListV s5NeverO AA7SectionV AA05EmptyC0V AA15ModifiedContentV AA6ToggleV AA4TextV AA32_EnvironmentKeyTransformModifierV
- _type_layout_string 16HealthSettingsUI08HKHealthB27PersonalizedSuggestionsViewV
CStrings:
+ "ACTION_SUGGESTIONS_DISABLE_ALERT_CANCEL"
+ "ACTION_SUGGESTIONS_DISABLE_ALERT_CONFIRM"
+ "ACTION_SUGGESTIONS_DISABLE_ALERT_MESSAGE"
+ "ACTION_SUGGESTIONS_DISABLE_ALERT_TITLE"
+ "ACTION_SUGGESTIONS_LABEL"
+ "HKHealthSettingsController found no row to insert PERSONALIZED_SUGGESTIONS_ITEM after. Have: %{public}@"
+ "HealthSettingsUI.HKHealthSettingsProfile"
+ "HealthSettingsUI/HKHealthSettingsProfile.swift"
+ "PERSONALIZATION_DESCRIPTION"
+ "PERSONALIZATION_FEATURES_HEADER"
+ "PERSONALIZATION_FOOTER"
+ "PERSONALIZATION_ITEM"
+ "PERSONALIZATION_TITLE"
+ "[%s] Failed to fetch Medical ID data: %@"
+ "[%s] Failed to fetch name for profile: %@"
+ "[%s] Failed to fetch profiles from HKProfileStore: %s"
+ "fetchMedicalIDData()"
+ "fetchNameComponents()"
+ "https://support.apple.com/"
+ "init()"
+ "init(healthStore:)"
+ "v16@?0@\"NSString\"8"
+ "v16@?0@\"_HKMedicalIDData\"8"
- "%{public}@ Failed to fetch name for profile, Error: %{public}@"
- "%{public}@ Failed to fetch profiles from HKProfileStore, Error: %{public}@"
- "Invalid number of keys found, expected one."
- "PERSONALIZED_SUGGESTIONS_FOOTER"
- "PERSONALIZED_SUGGESTIONS_LABEL"
- "PERSONALIZED_SUGGESTIONS_TITLE"
- "bundleIdentifier"
- "personalizedSuggestions"
- "preferencesController"
- "type = %d"
- "v24@?0@\"NSArray\"8@\"NSError\"16"
- "v24@?0@\"_HKMedicalIDData\"8@\"NSError\"16"
- "v32@?0@\"NSString\"8@\"NSString\"16@\"NSError\"24"
```
