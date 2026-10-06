## Stickers

> `/System/Library/PrivateFrameworks/Stickers.framework/Stickers`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x95218` | `0x95cd0` | **`+0xab8`** |
| `__TEXT.__swift5_reflstr` | `0x10cf` | `0x11af` | **`+0xe0`** |
| `__TEXT.__const` | `0x47c8` | `0x4838` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x1870` | `0x18c4` | **`+0x54`** |
| `__AUTH_CONST.__const` | `0x3210` | `0x3258` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x1388` | `0x13c8` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x4f68` | `0x4fa0` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x163f` | `0x1659` | **`+0x1a`** |
| `__TEXT.__cstring` | `0x1481` | `0x1491` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xb34` | `0xb44` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x23d0` | `0x23e0` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x32a0` | `0x32a8` | **`+0x8`** |
| `__DATA.__common` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA.__data` | `0x1238` | `0x1240` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x820` | `0x828` | **`+0x8`** |

### Other Changes

```diff

-88.0.0.0.0
+90.1.2.0.0

-  Functions: 2884
-  Symbols:   1143
+  Functions: 2893
+  Symbols:   1147
Symbols:
+ ___swift_allocate_boxed_opaque_existential_1Tm
+ _get_enum_tag_for_layout_string 8Stickers12RecencyErrorO
+ _symbolic SS11description_t
+ _symbolic _____ 8Stickers12RecencyErrorO
+ _symbolic _____Sg 14RecencyService0A13ResponseErrorO
+ _symbolic _____ySSG s11_SetStorageC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 9PromptKit0D0V
+ _type_layout_string 8Stickers12RecencyErrorO
- ___swift_allocate_boxed_opaque_existential_0
- _symbolic Say_____G 9PromptKit0A0V9ImageDataV
- _symbolic _____ 8Stickers12RecencyErrorV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 9PromptKit0D0V9ImageDataV
CStrings:
+ "_OverrideConfigurationHelper.samplingParameters(.dynamic(SamplingParameters(maximumTokens:Self.maximumTokens,stopSequences:Self.stopSequences)))"
+ "com.apple.EmojiKeywordExtraction"
- "_OverrideConfigurationHelper.samplingParameters(.dynamic(SamplingParameters(maximumTokens:Self.maximumTokens,)))"
- "com.apple.EmojiKeywordExtraction.prompt_template"
```
