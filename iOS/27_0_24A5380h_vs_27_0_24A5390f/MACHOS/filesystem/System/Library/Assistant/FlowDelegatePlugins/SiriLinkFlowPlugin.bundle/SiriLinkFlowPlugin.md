## SiriLinkFlowPlugin

> `/System/Library/Assistant/FlowDelegatePlugins/SiriLinkFlowPlugin.bundle/SiriLinkFlowPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x5295` | `0x52d5` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0xcce` | `0xd0e` | **`+0x40`** |
| `__TEXT.__text` | `0x217264` | `0x217228` | **`-0x3c`** |
| `__TEXT.__objc_stubs` | `0x5320` | `0x5340` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x18f8` | `0x1908` | **`+0x10`** |
| `__DATA.__objc_const` | `0xe6a0` | `0xe6a8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xed4` | `0xedc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.8.4.0.0
+3600.8.7.0.0

-  Symbols:   29845
-  CStrings:  2862
+  Symbols:   29846
+  CStrings:  2865
Symbols:
+ _objc_msgSend$setConfirmationCondition:
Functions:
~ _$s18SiriLinkFlowPlugin09ShortcutsB15RCHFlowStrategyC16makeCustomOutput11appBundleId07successJ0014startedSessionM018isAudioStartAction11deviceState04linkT14DialogTemplate15responseFactory14serviceInvoker0a3KitC00J0_pSS_So08LNActionJ0CSSSgSbAM06DeviceV0_pAA0btX10TemplatingCAM18ResponseGenerating_pAM22AceServiceInvokerAsync_ptYaKFZTY6_ : 188 -> 184
~ _$s18SiriLinkFlowPlugin09ShortcutsB15RCHFlowStrategyC7flowFor5error0a3KitC003AnyC0Cs5Error_p_tFAF6Output_pyYaYbKcfU_TY4_ : 308 -> 304
~ _$s18SiriLinkFlowPlugin09ShortcutsB15RCHFlowStrategyC40makeOutputForFailureHandlingIntentDialog5error0a3KitC00I0_ps5Error_p_tYaKFTY2_ : 420 -> 416
~ _$s18SiriLinkFlowPlugin09ShortcutsB15RCHFlowStrategyC16makeCustomOutput11deviceState18isAudioStartAction15responseFactory12dialogResult8manifest8viewData11appBundleId07snippetP011environment0a3KitC00J0_pAN06DeviceL0_p_SbAN18ResponseGenerating_pSo015DialogExecutionT0CAN0J18GenerationManifestV10Foundation0W0VSgSSSo8LNActionCSgSo20LNSnippetEnvironmentCSgtYaFZTY0_ : 740 -> 680
~ _$s18SiriLinkFlowPlugin0B7RCHFlowC010initializeB10Connection33_A83A936DCCD3C7AD4B517ED3FBC5A826LL10connection15interactionModeyAA0bG0_p_So013LNInteractionS0VtYaFTY0_ : 1188 -> 1200
CStrings:
+ "executor:updateOpensIntentRequest:"
+ "setConfirmationCondition:"
+ "v32@0:8@\"LNActionExecutor\"16@\"LNUpdateOpensIntentRequest\"24"
```
