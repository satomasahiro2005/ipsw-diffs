## Translation

> `/System/Library/Frameworks/Translation.framework/Translation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5cccc` | `0x5cee0` | **`+0x214`** |
| `__AUTH_CONST.__objc_const` | `0xc0f8` | `0xc1a8` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x3e40` | `0x3ec0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x5e10` | `0x5e70` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1ed0` | `0x1f00` | **`+0x30`** |
| `__TEXT.__cstring` | `0x3464` | `0x3494` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x2898` | `0x28b8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1c80` | `0x1c98` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x8e0` | `0x8ec` | **`+0xc`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-389.1.0.0.0
+393.1.0.0.0

-  Functions: 2897
-  Symbols:   4409
-  CStrings:  952
+  Functions: 2907
+  Symbols:   4424
+  CStrings:  956
Symbols:
+ -[_LTLanguageDetectionConfiguration aiInferenceLocation]
+ -[_LTLanguageDetectionConfiguration setAiInferenceLocation:]
+ -[_LTLanguageStatusConfiguration isIndeterminate]
+ -[_LTLanguageStatusConfiguration wantsAIStatusUpdates]
+ -[_LTTranslationContext aiInferenceLocation]
+ -[_LTTranslationContext setAiInferenceLocation:]
+ -[_LTTranslationRequest aiInferenceLocation]
+ -[_LTTranslationRequest setAiInferenceLocation:]
+ GCC_except_table133
+ GCC_except_table67
+ GCC_except_table70
+ GCC_except_table74
+ GCC_except_table77
+ _OBJC_IVAR_$__LTLanguageDetectionConfiguration._aiInferenceLocation
+ _OBJC_IVAR_$__LTTranslationContext._aiInferenceLocation
+ _OBJC_IVAR_$__LTTranslationRequest._aiInferenceLocation
+ __LTAIInferenceLocationString
+ ___33-[_LTLanguageStatus cachedStatus]_block_invoke
+ ___block_descriptor_40_e8_32s_e14_"NSArray"8?0ls32l8
- GCC_except_table131
- GCC_except_table68
- GCC_except_table72
- GCC_except_table75
CStrings:
+ "@\"NSArray\"8@?0"
+ "Using single-paragraph sub-request"
+ "ai-mt-expert-server"
+ "aiInferenceLocation"
+ "any"
+ "on-device"
- "Fallback to text to speech translation"
- "ai_adapter_inference"
```
