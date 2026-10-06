## SiriPhoneFlowTools

> `/System/Library/FlowTools/Tools/SiriPhoneFlowTools.flowtool/SiriPhoneFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb6084` | `0xb6b44` | **`+0xac0`** |
| `__DATA_CONST.__const` | `0x6910` | `0x6960` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x6060` | `0x6098` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0xfa0` | `0xfc4` | **`+0x24`** |
| `__TEXT.__auth_stubs` | `0x2870` | `0x2880` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x549e` | `0x54ae` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1440` | `0x1448` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xbf8` | `0xc00` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x33f0` | `0x33f8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x2528` | `0x252e` | **`+0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3605.17.1.1.1
+3605.20.1.0.0

-  Functions: 5506
-  Symbols:   11664
-  CStrings:  814
+  Functions: 5509
+  Symbols:   11672
+  CStrings:  815
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/SiriPhone/install/Symbols/BuiltProducts/libSiriPhoneFlowToolsImplementation.a(SPHCallCenter-ac1eace23f8230b104db8d9ab2f0c6d0.o)
+ _$s13FlowToolTypes0B5QueryV10identifierSSSgvs
+ _$s13FlowToolTypes0B7StoringP09SiriPhoneA5ToolsE010answerCallB06toolID2on0B3Kit0B10DefinitionVSgSS_AH09ContainerN0V6DeviceOSgtKF
+ _$s13FlowToolTypes0B7StoringP09SiriPhoneA5ToolsE010answerCallB06toolID2on0B3Kit0B10DefinitionVSgSS_AH09ContainerN0V6DeviceOSgtKFyAA0B5QueryVzcfU0_
+ _$s13FlowToolTypes0B7StoringP09SiriPhoneA5ToolsE010answerCallB06toolID2on0B3Kit0B10DefinitionVSgSS_AH09ContainerN0V6DeviceOSgtKFyAA0B5QueryVzcfU0_TA
+ _$s13FlowToolTypes0B7StoringP09SiriPhoneA5ToolsE010answerCallB06toolID2on0B3Kit0B10DefinitionVSgSS_AH09ContainerN0V6DeviceOSgtKFyAA0B5QueryVzcfU_
+ _$s13FlowToolTypes0B7StoringP09SiriPhoneA5ToolsE010answerCallB06toolID2on0B3Kit0B10DefinitionVSgSS_AH09ContainerN0V6DeviceOSgtKFyAA0B5QueryVzcfU_TA
+ __swift_closure_destructor.29Tm
+ _symbolic _____ 7ToolKit19ContainerDefinitionV6DeviceO
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/SiriPhone/install/Symbols/BuiltProducts/libSiriPhoneFlowToolsImplementation.a(SPHCallCenter-b14328fffe01c1b706a937f7b537e56c.o)
CStrings:
+ "#AnswerCallFlowTool could not find tool with id: %s"
+ "#AnswerCallFlowTool no %s on %s; trying local"
- "#FaceTimeAccountSetupProvider no local FaceTime container; app is uninstalled on the companion"
```
