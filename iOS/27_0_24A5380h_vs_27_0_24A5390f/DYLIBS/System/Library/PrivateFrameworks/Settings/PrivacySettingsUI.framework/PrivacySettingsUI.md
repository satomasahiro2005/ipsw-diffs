## PrivacySettingsUI

> `/System/Library/PrivateFrameworks/Settings/PrivacySettingsUI.framework/PrivacySettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x64694` | `0x6773c` | **`+0x30a8`** |
| `__TEXT.__swift5_typeref` | `0x1b8` | `0x53a` | **`+0x382`** |
| `__AUTH_CONST.__objc_const` | `0x6410` | `0x65e8` | **`+0x1d8`** |
| `__TEXT.__const` | `0x374` | `0x524` | **`+0x1b0`** |
| `__DATA.__data` | `0x478` | `0x5f8` | **`+0x180`** |
| `__AUTH_CONST.__auth_got` | `0x950` | `0xac8` | **`+0x178`** |
| `__TEXT.__cstring` | `0x8244` | `0x8344` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x4174` | `0x4274` | **`+0x100`** |
| `__AUTH.__objc_data` | `0x16c8` | `0x1780` | **`+0xb8`** |
| `__AUTH.__data` | `0x1a8` | `0x250` | **`+0xa8`** |
| `__DATA_CONST.__got` | `0x9e8` | `0xa78` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x32c0` | `0x3350` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x1798` | `0x1828` | **`+0x90`** |
| `__DATA.__bss` | `0x568` | `0x5f0` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0x1e8` | `0x26c` | **`+0x84`** |
| `__AUTH_CONST.__cfstring` | `0x6f60` | `0x6fc0` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0xbc` | `0x110` | **`+0x54`** |
| `__TEXT.__swift5_reflstr` | `0xb9` | `0xe3` | **`+0x2a`** |
| `__AUTH_CONST.__const` | `0xa48` | `0xa70` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1b00` | `0x1b28` | **`+0x28`** |
| `__AUTH_CONST.__objc_intobj` | `0x348` | `0x360` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x50` | `0x68` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_protorefs` | `0x8` | `0x18` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x19c` | `0x1ac` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x468` | `0x470` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x238` | `0x240` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x12a0` | `0x12a8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x14` | `0x1c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-2027.0.2.0.0
+2027.0.4.0.0

-  Functions: 2056
-  Symbols:   3607
-  CStrings:  1401
+  Functions: 2126
+  Symbols:   3696
+  CStrings:  1409
Symbols:
+ +[PUILockdownModeUtilities threatNotificationDate]
+ -[PUILockdownModeController dealloc]
+ -[PUILockdownModeController openSupportPageWithURL:]
+ -[PUILockdownModeController registerThreatNotificationObserver]
+ -[PUILockdownModeController reloadSpecifiersForThreatNotificationChange]
+ -[PUILockdownModeController setThreatNotificationObserverRegistered:]
+ -[PUILockdownModeController setThreatNotificationSpecifier:]
+ -[PUILockdownModeController threatNotificationObserverRegistered]
+ -[PUILockdownModeController threatNotificationSpecifier]
+ -[PUILockdownModeController unregisterThreatNotificationObserver]
+ -[PUILockdownModeController viewWillDisappear:]
+ GCC_except_table107
+ GCC_except_table114
+ GCC_except_table121
+ GCC_except_table124
+ GCC_except_table126
+ GCC_except_table130
+ GCC_except_table138
+ GCC_except_table142
+ GCC_except_table144
+ GCC_except_table148
+ GCC_except_table163
+ GCC_except_table22
+ GCC_except_table24
+ GCC_except_table25
+ GCC_except_table40
+ GCC_except_table89
+ GCC_except_table94
+ _CFNotificationCenterRemoveEveryObserver
+ _OBJC_CLASS_$_PUILockdownModeThreatNotificationCell
+ _OBJC_IVAR_$_PUILockdownModeController._threatNotificationObserverRegistered
+ _OBJC_IVAR_$_PUILockdownModeController._threatNotificationSpecifier
+ _OBJC_METACLASS_$_PUILockdownModeThreatNotificationCell
+ _OUTLINED_FUNCTION_31
+ _OUTLINED_FUNCTION_36
+ __CLASS_METHODS_PUILockdownModeThreatNotificationCell
+ __CLASS_PROPERTIES_PUILockdownModeThreatNotificationCell
+ __DATA_PUILockdownModeThreatNotificationCell
+ __INSTANCE_METHODS_PUILockdownModeThreatNotificationCell
+ __IVARS_PUILockdownModeThreatNotificationCell
+ __METACLASS_DATA_PUILockdownModeThreatNotificationCell
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_PUILockdownModeLearnMoreActionTarget
+ __OBJC_$_PROTOCOL_METHOD_TYPES_PUILockdownModeLearnMoreActionTarget
+ __OBJC_$_PROTOCOL_REFS_PUILockdownModeLearnMoreActionTarget
+ __OBJC_CLASS_PROTOCOLS_$_PUILockdownModeController
+ __OBJC_LABEL_PROTOCOL_$_PUILockdownModeLearnMoreActionTarget
+ __OBJC_PROTOCOL_$_PUILockdownModeLearnMoreActionTarget
+ __PROTOCOL_INSTANCE_METHODS_PUILockdownModeLearnMoreActionTarget
+ __PROTOCOL_METHOD_TYPES_PUILockdownModeLearnMoreActionTarget
+ __PROTOCOL_PROTOCOLS_PUILockdownModeLearnMoreActionTarget
+ __PROTOCOL_PUILockdownModeLearnMoreActionTarget
+ ___73-[PUIProblemReportingController setShouldShareiCloudAnalytics:specifier:]_block_invoke_2
+ ___block_descriptor_57_e8_32s40s48w_e5_v8?0lw48l8s32l8s40l8
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ ___threatNotificationDidChangeCallback_block_invoke
+ _associated conformance 17PrivacySettingsUI22ThreatNotificationCard33_90078785C6D9B5A5851A578C83C225F4LLV05SwiftC04ViewAA4BodyAeFP_AeF
+ _flat unique So36PUILockdownModeLearnMoreActionTarget_p
+ _get_witness_table 7SwiftUI15ModifiedContentVyACyACyACyACyACyAA6VStackVyAA05TupleD0VyAA4TextV_AIQPGGAA14_PaddingLayoutVGAA010_FlexFrameI0VGAA24_BackgroundStyleModifierVyAA017HierarchicalShapemN0VyAA5ColorVGGGAA11_ClipEffectVyAA16RoundedRectangleVGGAMGAA022_EnvironmentKeyWritingN0VyAA13OpenURLActionVGGSgAA4ViewHpA11_AAA13_HPA5_AAA13_HPA4_AAA13_HPAzAA13_HPAqAA13_HPAnAA13_HPAkAA13_HPyHC_AmA04ViewN0HPyHCHC_ApAA14_HPyHCHC_AyAA14_HPyHCHC_A3_AAA14_HPyHCHC_AmAA14_HPyHCHC_A10_AAA14_HPyHCHC_HC
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_dynamicCastObjCClass
+ _swift_dynamicCastObjCProtocolConditional
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getKeyPath
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassMetadata
+ _swift_getOpaqueTypeConformance2
+ _swift_getSingletonMetadata
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_release_x23
+ _swift_release_x26
+ _swift_release_x27
+ _swift_storeEnumTagSinglePayloadGeneric
+ _symbolic $s17PrivacySettingsUI36PUILockdownModeLearnMoreActionTargetP
+ _symbolic $s7SwiftUI4ViewP
+ _symbolic So11PSTableCellC
+ _symbolic _____ 17PrivacySettingsUI22ThreatNotificationCard33_90078785C6D9B5A5851A578C83C225F4LLV
+ _symbolic _____ 17PrivacySettingsUI37PUILockdownModeThreatNotificationCellC
+ _symbolic _____ 7SwiftUI13OpenURLActionV
+ _symbolic _____ 7SwiftUI17EnvironmentValuesV
+ _symbolic _____Sg 10Foundation4DateV
+ _symbolic ______p 17PrivacySettingsUI36PUILockdownModeLearnMoreActionTargetP
+ _symbolic ______pSg 17PrivacySettingsUI36PUILockdownModeLearnMoreActionTargetP
+ _symbolic _____yAAyAAyAAyAAyAAy_____y_____y______ADQPGG_____G_____G_____y_____y_____GGG_____y_____GGAGG_____y_____GG 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV AA14_PaddingLayoutV AA010_FlexFrameI0V AA24_BackgroundStyleModifierV AA017HierarchicalShapemN0V AA5ColorV AA11_ClipEffectV AA16RoundedRectangleV AA022_EnvironmentKeyWritingN0V AA13OpenURLActionV
+ _symbolic _____yAAyAAyAAyAAyAAy_____y_____y______ADQPGG_____G_____G_____y_____y_____GGG_____y_____GGAGG_____y_____GGSg 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV AA14_PaddingLayoutV AA010_FlexFrameI0V AA24_BackgroundStyleModifierV AA017HierarchicalShapemN0V AA5ColorV AA11_ClipEffectV AA16RoundedRectangleV AA022_EnvironmentKeyWritingN0V AA13OpenURLActionV
+ _symbolic _____yAAyAAyAAyAAy_____y_____y______ADQPGG_____G_____G_____y_____y_____GGG_____y_____GGAGG 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV AA14_PaddingLayoutV AA010_FlexFrameI0V AA24_BackgroundStyleModifierV AA017HierarchicalShapemN0V AA5ColorV AA11_ClipEffectV AA16RoundedRectangleV
+ _symbolic _____yAAyAAyAAy_____y_____y______ADQPGG_____G_____G_____y_____y_____GGG_____y_____GG 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV AA14_PaddingLayoutV AA010_FlexFrameI0V AA24_BackgroundStyleModifierV AA017HierarchicalShapemN0V AA5ColorV AA11_ClipEffectV AA16RoundedRectangleV
+ _symbolic _____yAAyAAy_____y_____y______ADQPGG_____G_____G_____y_____y_____GGG 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV AA14_PaddingLayoutV AA010_FlexFrameI0V AA24_BackgroundStyleModifierV AA017HierarchicalShapemN0V AA5ColorV
+ _symbolic _____yAAy_____y_____y______ADQPGG_____G_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV AA14_PaddingLayoutV AA010_FlexFrameI0V
+ _symbolic _____y_____G 7SwiftUI11_ClipEffectV AA16RoundedRectangleV
+ _symbolic _____y_____G 7SwiftUI19UIHostingControllerC 015PrivacySettingsB022ThreatNotificationCard33_90078785C6D9B5A5851A578C83C225F4LLV
+ _symbolic _____y_____G 7SwiftUI30_EnvironmentKeyWritingModifierV AA13OpenURLActionV
+ _symbolic _____y_____GSg 7SwiftUI19UIHostingControllerC 015PrivacySettingsB022ThreatNotificationCard33_90078785C6D9B5A5851A578C83C225F4LLV
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _symbolic _____y_____y_____GG 7SwiftUI24_BackgroundStyleModifierV AA017HierarchicalShapedE0V AA5ColorV
+ _symbolic _____y_____y______ACQPGG 7SwiftUI6VStackV AA12TupleContentV AA4TextV
+ _symbolic _____y_____y_____y______ADQPGG_____G 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA4TextV AA14_PaddingLayoutV
+ _symbolic _____yyXlG s23_ContiguousArrayStorageC
+ _symbolic x
+ _symbolic ypSg
+ _threatNotificationDidChangeCallback
- -[PUILockdownModeWebController didTapHeaderLearnMoreLink:]
- -[PUILockdownModeWebController presentAboutController]
- GCC_except_table106
- GCC_except_table113
- GCC_except_table120
- GCC_except_table125
- GCC_except_table136
- GCC_except_table140
- GCC_except_table143
- GCC_except_table147
- GCC_except_table160
- GCC_except_table17
- GCC_except_table18
- GCC_except_table33
- _OUTLINED_FUNCTION_30
- _OUTLINED_FUNCTION_35
- ___54-[PUILockdownModeWebController presentAboutController]_block_invoke
CStrings:
+ "%@ [%@](%@)"
+ "CONFIRM_ALERT_DISABLE_THREAT_MESSAGE"
+ "CUSTOMIZE_CONTACTS"
+ "CUSTOMIZE_WEBSITES"
+ "LOCKDOWN_MODE_FEATURES_GROUP"
+ "PUIThreatNotificationDateKey"
+ "THREAT_NOTIFICATION_BODY"
+ "THREAT_NOTIFICATION_LINK"
+ "THREAT_NOTIFICATION_TITLE"
+ "com.apple.LockdownMode.threatNotificationDidChange"
+ "https://support.apple.com/102174"
+ "https://support.apple.com/105120"
- "%@ [%@](https://support.apple.com/kb/HT212650)"
- "CONFIGURE_MESSAGES"
- "WEB_CONTENT"
- "https://support.apple.com/kb/HT212650"
```
