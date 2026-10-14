## SiriLinkFlowPlugin

> `/System/Library/Assistant/FlowDelegatePlugins/SiriLinkFlowPlugin.bundle/SiriLinkFlowPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2196f4` | `0x21d548` | **`+0x3e54`** |
| `__TEXT.__oslogstring` | `0xd8ba` | `0xdcfa` | **`+0x440`** |
| `__TEXT.__eh_frame` | `0x1a294` | `0x1a65c` | **`+0x3c8`** |
| `__TEXT.__unwind_info` | `0xa558` | `0xa220` | **`-0x338`** |
| `__TEXT.__auth_stubs` | `0x5570` | `0x55c0` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x1734` | `0x1768` | **`+0x34`** |
| `__TEXT.__const` | `0x17aec` | `0x17b1c` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x5b92` | `0x5bbc` | **`+0x2a`** |
| `__DATA_CONST.__auth_got` | `0x2ac0` | `0x2ae8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x137e0` | `0x13808` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x11b4` | `0x11dc` | **`+0x28`** |
| `__DATA.__data` | `0xbd40` | `0xbd60` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x5345` | `0x5365` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x5440` | `0x5460` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1888` | `0x18a0` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x1058` | `0x1068` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1948` | `0x1950` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1728` | `0x1730` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xd70` | `0xd74` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 13611
-  Symbols:   29954
-  CStrings:  2877
+  Functions: 13671
+  Symbols:   30005
+  CStrings:  2891
Symbols:
+ _$s11SiriKitFlow11DeviceStateP15isHomeAccessorySbvgTj
+ _$s18SiriLinkFlowPlugin011WFShowAlertC0C11buildOutput33_0E609C7F55F99E1F092CF826B7D12744LL0a3KitC00H0_pyYaKFTQ9_
+ _$s18SiriLinkFlowPlugin011WFShowAlertC0C11buildOutput33_0E609C7F55F99E1F092CF826B7D12744LL0a3KitC00H0_pyYaKFTY10_
+ _$s18SiriLinkFlowPlugin011WFShowAlertC0C11buildOutput33_0E609C7F55F99E1F092CF826B7D12744LL0a3KitC00H0_pyYaKFTY11_
+ _$s18SiriLinkFlowPlugin016WFChooseFromListC0C7execute0a3KitC015ExecuteResponseVyYaFTQ3_
+ _$s18SiriLinkFlowPlugin016WFChooseFromListC0C7execute0a3KitC015ExecuteResponseVyYaFTY4_
+ _$s18SiriLinkFlowPlugin019CustomIntentConfirmF17ResponseGeneratorC25makePromptForConfirmation3app6intent0oH00a3KitC06Output_p0A13AppResolution0R0C_So8INIntentCSo0tH0CtYaKFTQ13_
+ _$s18SiriLinkFlowPlugin019CustomIntentConfirmF17ResponseGeneratorC25makePromptForConfirmation3app6intent0oH00a3KitC06Output_p0A13AppResolution0R0C_So8INIntentCSo0tH0CtYaKFTY14_
+ _$s18SiriLinkFlowPlugin020AutoShortcutFirstRunC0C16makePromptOutput7appName0a3KitC00K0_pSS_tYaKFTQ7_
+ _$s18SiriLinkFlowPlugin020AutoShortcutFirstRunC0C16makePromptOutput7appName0a3KitC00K0_pSS_tYaKFTY8_
+ _$s18SiriLinkFlowPlugin020WFConfirmInteractionC0C11buildOutput33_220071A64E3E8D776517CBE45A2C4B77LL0a3KitC00H0_pyYaKFTQ15_
+ _$s18SiriLinkFlowPlugin020WFConfirmInteractionC0C11buildOutput33_220071A64E3E8D776517CBE45A2C4B77LL0a3KitC00H0_pyYaKFTY16_
+ _$s18SiriLinkFlowPlugin020WFConfirmInteractionC0C11buildOutput33_220071A64E3E8D776517CBE45A2C4B77LL0a3KitC00H0_pyYaKFTY17_
+ _$s18SiriLinkFlowPlugin021WFExecuteCustomIntentC0C7execute0a3KitC015ExecuteResponseVyYaFTQ3_
+ _$s18SiriLinkFlowPlugin021WFExecuteCustomIntentC0C7execute0a3KitC015ExecuteResponseVyYaFTY4_
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFAN0Y0_pyYaYbcfU0_
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFAN0Y0_pyYaYbcfU0_TA
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFAN0Y0_pyYaYbcfU0_TATQ0_
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFAN0Y0_pyYaYbcfU0_TATu
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFAN0Y0_pyYaYbcfU0_TY0_
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFAN0Y0_pyYaYbcfU0_Tu
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFSbyXEfu_TA
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFTQ5_
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFTQ7_
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFTY6_
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFTY8_
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV03getC06config11deviceState15outputPublisher24linkActionDialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3KitC006DeviceK0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFTY9_
+ _$s18SiriLinkFlowPlugin07Defaultb8HandlingC7FactoryV17isSupportedAction11deviceState0H14OpenAppWhenRun20authenticationPolicySb0a3KitC006DeviceL0_p_SbyXKSo022LNActionAuthenticationR0VSgyXKtFZ04$s18abc17Plugin07Defaultb8f2C7g51V03getC06config11deviceState15outputPublisher24linkj67DialogTemplate0N17MetadataProvidingAA0bfC4TypeOAK03GetC6ConfigV_0a3s4C006t60K0_pAN06OutputM5Async_pAA0boP10TemplatingCAA0brS0_ptYaKFSo28uvR10VSgyXEfu0_So0U8MetadataCTf1nncn_n
+ _$s18SiriLinkFlowPlugin29ShortcutsUnlockDeviceStrategyC013makePromptForgF018dialogingTemplates11deviceState0a3KitC06Output_pAA29CustomIntentsDialogTemplatingC_AG0gO0_ptYaKFZTQ9_
+ _$s18SiriLinkFlowPlugin29ShortcutsUnlockDeviceStrategyC013makePromptForgF018dialogingTemplates11deviceState0a3KitC06Output_pAA29CustomIntentsDialogTemplatingC_AG0gO0_ptYaKFZTY10_
+ _$s18SiriLinkFlowPlugin29ShortcutsUnlockDeviceStrategyC013makePromptForgF018dialogingTemplates11deviceState0a3KitC06Output_pAA29CustomIntentsDialogTemplatingC_AG0gO0_ptYaKFZTY8_
+ _$s18SiriLinkFlowPlugin29ShortcutsUnlockDeviceStrategyC013makePromptForgF8_preRFv233_8F0899A5A2BE1D3C0D6839E453F4D424LL18dialogingTemplates11deviceState0a3KitC06Output_pAA29CustomIntentsDialogTemplatingC_AH0G5State_ptYaKFZTQ5_
+ _$s18SiriLinkFlowPlugin29ShortcutsUnlockDeviceStrategyC013makePromptForgF8_preRFv233_8F0899A5A2BE1D3C0D6839E453F4D424LL18dialogingTemplates11deviceState0a3KitC06Output_pAA29CustomIntentsDialogTemplatingC_AH0G5State_ptYaKFZTY7_
+ _$s18SiriLinkFlowPlugin29ShortcutsUnlockDeviceStrategyC013makePromptForgF8_preRFv233_8F0899A5A2BE1D3C0D6839E453F4D424LL18dialogingTemplates11deviceState0a3KitC06Output_pAA29CustomIntentsDialogTemplatingC_AH0G5State_ptYaKFZTY8_
+ _$s18SiriLinkFlowPlugin29ShortcutsUnlockDeviceStrategyC013makePromptForgF8_preRFv233_8F0899A5A2BE1D3C0D6839E453F4D424LL18dialogingTemplates11deviceState0a3KitC06Output_pAA29CustomIntentsDialogTemplatingC_AH0G5State_ptYaKFZTY9_
+ _$s19SiriFlowEnvironment14CurrentRequestC18overridePropertiesSDyAA0dE9OverridesO5FieldOypGSgvg
+ _$s19SiriFlowEnvironment23CurrentRequestOverridesO5FieldO12responseModeyA2EmFWC
+ _$s19SiriFlowEnvironment23CurrentRequestOverridesO5FieldOAESHAAWL
+ _$s19SiriFlowEnvironment23CurrentRequestOverridesO5FieldOMa
+ _$s19SiriFlowEnvironment23CurrentRequestOverridesO5FieldOSHAAMc
+ _$s19SiriFlowEnvironment23CurrentRequestOverridesO5FieldO_yptMR
+ _$s19SiriFlowEnvironment23CurrentRequestOverridesO5FieldO_yptMd
+ _$sSDy19SiriFlowEnvironment23CurrentRequestOverridesO5FieldOypGSgMR
+ _$sSDy19SiriFlowEnvironment23CurrentRequestOverridesO5FieldOypGSgMd
+ _$sSo13MGProductTypeaSQSCSQ2eeoiySbx_xtFZTW
+ _$sSo13MGProductTypeaSYSCSY8rawValue03RawD0QzvgTW
+ _$sSo28LNActionAuthenticationPolicyV12LinkMetadataE8nsNumberABSgSo8NSNumberCSg_tcfC
+ _$ss23_ContiguousArrayStorageCy19SiriFlowEnvironment23CurrentRequestOverridesO5FieldO_yptGMR
+ _$ss23_ContiguousArrayStorageCy19SiriFlowEnvironment23CurrentRequestOverridesO5FieldO_yptGMd
+ _$ss2eeoiySbx_xtSYRzSQ8RawValueRpzlFSo13MGProductTypea_Tgq5
+ _MGGetProductType
+ ___swift_allocate_boxed_opaque_existential_0Tm
+ _objc_msgSend$authenticationPolicyAllowingImplicit:
+ _symbolic SDy_____ypGSg 19SiriFlowEnvironment23CurrentRequestOverridesO5FieldO
+ _symbolic ______ypt 19SiriFlowEnvironment23CurrentRequestOverridesO5FieldO
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC 19SiriFlowEnvironment23CurrentRequestOverridesO5FieldO
- _$s11SiriKitFlow5ParseO16DirectInvocationVSgWOhTm
- _$s18SiriLinkFlowPlugin011WFShowAlertC0C11buildOutput33_0E609C7F55F99E1F092CF826B7D12744LL0a3KitC00H0_pyYaKFTY9_
- _$s18SiriLinkFlowPlugin020AutoShortcutFirstRunC0C16makePromptOutput7appName0a3KitC00K0_pSS_tYaKFTY7_
- _$s18SiriLinkFlowPlugin020WFConfirmInteractionC0C11buildOutput33_220071A64E3E8D776517CBE45A2C4B77LL0a3KitC00H0_pyYaKFTY15_
- _$s18SiriLinkFlowPlugin29ShortcutsUnlockDeviceStrategyC013makePromptForgF8_preRFv233_8F0899A5A2BE1D3C0D6839E453F4D424LL18dialogingTemplates11deviceState0a3KitC06Output_pAA29CustomIntentsDialogTemplatingC_AH0G5State_ptYaKFZTY5_
CStrings:
+ "#DefaultLinkHandlingFlowFactory isSupportedAction - NO support per authenticationPolicy"
+ "#DefaultLinkHandlingFlowFactory isSupportedAction - NO support per openAppWhenRun"
+ "#DefaultLinkHandlingFlowFactory isSupportedAction - NO support per unknown authenticationPolicy"
+ "#DefaultLinkHandlingFlowFactory isSupportedAction - supported per .alwaysAllowed"
+ "#DefaultLinkHandlingFlowFactory isSupportedAction - supported per NO authenticationPolicy"
+ "#SiriLinkFlowPlugin makeFlowFlowSearchResult - handoff per test device type"
+ "#SiriWorkflowRunner the request is happening on home accessory"
+ "#VoiceCommandParityFlow checkResponseModeOverride - CurrentRequest overrides: %s"
+ "#VoiceCommandParityFlow checkResponseModeOverride - can't set CurrentRequest override: %@"
+ "#VoiceCommandParityFlow checkResponseModeOverride - overriding to VOX; from %s"
+ "#WFOpenInteractionFlow handoff for Home Accessory"
+ "Executing on HomeAccessory. Returning nil for view snippet environment."
+ "The request is happening on home accessory"
+ "authenticationPolicyAllowingImplicit:"
```
