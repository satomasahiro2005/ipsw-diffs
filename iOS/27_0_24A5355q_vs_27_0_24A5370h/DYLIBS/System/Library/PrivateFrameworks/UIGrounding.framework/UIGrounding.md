## UIGrounding

> `/System/Library/PrivateFrameworks/UIGrounding.framework/UIGrounding`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49080` | `0x4acfc` | **`+0x1c7c`** |
| `__TEXT.__eh_frame` | `0x2c64` | `0x2f24` | **`+0x2c0`** |
| `__TEXT.__oslogstring` | `0x63d` | `0x6dd` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x1540` | `0x15d8` | **`+0x98`** |
| `__TEXT.__const` | `0x5b58` | `0x5be8` | **`+0x90`** |
| `__TEXT.__cstring` | `0xdd9` | `0xd79` | **`-0x60`** |
| `__AUTH_CONST.__auth_got` | `0xec8` | `0xf20` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x10b8` | `0x1110` | **`+0x58`** |
| `__AUTH.__data` | `0x1040` | `0x1090` | **`+0x50`** |
| `__AUTH.__objc_data` | `0x2d0` | `0x280` | **`-0x50`** |
| `__AUTH_CONST.__const` | `0x3920` | `0x3958` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x28` | `0x60` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x100` | `0x128` | **`+0x28`** |
| `__DATA.__data` | `0xf90` | `0xfb0` | **`+0x20`** |
| `__DATA.__common` | `0xe0` | `0xd0` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xa8` | `0xb8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xa26` | `0xa36` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x5c` | `0x6c` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x84` | `0x94` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x1508` | `0x14fc` | **`-0xc`** |
| `__AUTH_CONST.__objc_const` | `0xdc8` | `0xdd0` | **`+0x8`** |
| `__TEXT.__swift5_fieldmd` | `0x16dc` | `0x16e0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1c0` | `0x1c4` | **`+0x4`** |

### Other Changes

```diff

-34.0.0.0.0
+36.0.0.0.0

-  Functions: 1704
-  Symbols:   745
+  Functions: 1739
+  Symbols:   761
Symbols:
+ _OBJC_CLASS_$_NSProcessInfo
+ _objc_release_x28
+ _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
+ _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_singlePayloadEnumGeneric_getEnumTag
+ _swift_task_create
+ _symbolic Say_____G 29GenerativeFunctionsFoundation8ToolTypeV
+ _symbolic ScA_pSg
+ _symbolic ScPSg
+ _symbolic _____ 11UIGrounding20GMSGroundingModelVCIC29CombinedSafetyInferenceResult33_9D0A5062CC09B61BCEEA5DB1900F1948LLO
+ _symbolic _____ 15TokenGeneration16PromptCompletionV
+ _symbolic _____ 15TokenGeneration18SamplingParametersV
+ _symbolic _____ 9PromptKit012ChatMessagesA0V
+ _symbolic _____Sg 11UIGrounding20GMSGroundingModelVCIC29CombinedSafetyInferenceResult33_9D0A5062CC09B61BCEEA5DB1900F1948LLO
+ _symbolic _____Sg 15TokenGeneration16PromptCompletionV
+ _symbolic ______p s5ErrorP
+ _symbolic _____y___________p_G Scg8IteratorV 11UIGrounding20GMSGroundingModelVCIC29CombinedSafetyInferenceResult33_9D0A5062CC09B61BCEEA5DB1900F1948LLO s5ErrorP
- _symbolic _____ 9PromptKit011ChatMessageA0V
CStrings:
+ "UIGrounding: Failed to extract user text from chat for safety sanitization"
+ "UIGrounding: Safety sanitization text is empty after prefix stripping"
+ "com.apple.fm.language.instruct_300m.voice_control_ai_v2"
+ "d_CZPF4IRQsSAyupX9-aw8Dl-P4."
- "Sh1OhTRZ7oDJKtSghn7JhBDkPsA."
- "_OverrideConfigurationHelper.renderedPromptSanitizer(.dynamic(self.getVCISantizer()))"
- "com.apple.fm.language.instruct_300m.voice_control_ai"
- "system"
```
