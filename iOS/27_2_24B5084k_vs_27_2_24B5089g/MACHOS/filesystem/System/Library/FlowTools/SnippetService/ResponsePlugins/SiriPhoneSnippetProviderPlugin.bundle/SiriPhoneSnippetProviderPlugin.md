## SiriPhoneSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/SiriPhoneSnippetProviderPlugin.bundle/SiriPhoneSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfba14` | `0xfc310` | **`+0x8fc`** |
| `__TEXT.__eh_frame` | `0x80a4` | `0x80fc` | **`+0x58`** |
| `__DATA_CONST.__const` | `0xa0c0` | `0xa110` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x12e4` | `0x1308` | **`+0x24`** |
| `__TEXT.__swift5_typeref` | `0x2c1a` | `0x2c3a` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x34a0` | `0x3490` | **`-0x10`** |
| `__TEXT.__const` | `0xbd94` | `0xbda4` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x7a2e` | `0x7a3e` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1a58` | `0x1a50` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xdd0` | `0xdd8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3605.17.1.1.1
+3605.20.1.0.0

-  Functions: 7136
-  Symbols:   15366
-  CStrings:  1031
+  Functions: 7140
+  Symbols:   15372
+  CStrings:  1032
Symbols:
+ _$s13FlowToolTypes0B5QueryV10identifierSSSgvs
+ _$s13FlowToolTypes0B7StoringP09SiriPhoneA5ToolsE010answerCallB06toolID2on0B3Kit0B10DefinitionVSgSS_AH09ContainerN0V6DeviceOSgtKF
+ _$s13FlowToolTypes0B7StoringP09SiriPhoneA5ToolsE010answerCallB06toolID2on0B3Kit0B10DefinitionVSgSS_AH09ContainerN0V6DeviceOSgtKFyAA0B5QueryVzcfU0_
+ _$s13FlowToolTypes0B7StoringP09SiriPhoneA5ToolsE010answerCallB06toolID2on0B3Kit0B10DefinitionVSgSS_AH09ContainerN0V6DeviceOSgtKFyAA0B5QueryVzcfU0_TA
+ _$s13FlowToolTypes0B7StoringP09SiriPhoneA5ToolsE010answerCallB06toolID2on0B3Kit0B10DefinitionVSgSS_AH09ContainerN0V6DeviceOSgtKFyAA0B5QueryVzcfU_
+ _$s13FlowToolTypes0B7StoringP09SiriPhoneA5ToolsE010answerCallB06toolID2on0B3Kit0B10DefinitionVSgSS_AH09ContainerN0V6DeviceOSgtKFyAA0B5QueryVzcfU_TA
+ _$s14PhoneSnippetUI18DisplayableContactV13consolidating4withA2C_tF
+ _$sSi6offset_16IntelligenceFlow14SystemResponseV0E4TypeO11DisplayItemO7elementtMR
+ _$sSi6offset_16IntelligenceFlow14SystemResponseV0E4TypeO11DisplayItemO7elementtMd
+ __swift_closure_destructor.29Tm
+ _symbolic Si6offset______7elementt 16IntelligenceFlow14SystemResponseV0D4TypeO11DisplayItemO
+ _symbolic _____ 7ToolKit19ContainerDefinitionV6DeviceO
- _$s10Foundation20PersonNameComponentsVSgWOb
- _$s14PhoneSnippetUI18DisplayableContactV4nameSSvg
- _$s14PhoneSnippetUI18DisplayableContactV7handlesSayAA0D6HandleVGvg
- _$s14PhoneSnippetUI18DisplayableContactV9contactIdSSvg
- _$sSa20_reserveCapacityImpl07minimumB013growForAppendySi_SbtF14PhoneSnippetUI17DisplayableHandleV_Tg5
- _$sSa6append10contentsOfyqd__n_t7ElementQyd__RszSTRd__lF14PhoneSnippetUI17DisplayableHandleV_SayAGGTg5
CStrings:
+ "#AnswerCallFlowTool could not find tool with id: %s"
+ "#AnswerCallFlowTool no %s on %s; trying local"
- "#FaceTimeAccountSetupProvider no local FaceTime container; app is uninstalled on the companion"
```
