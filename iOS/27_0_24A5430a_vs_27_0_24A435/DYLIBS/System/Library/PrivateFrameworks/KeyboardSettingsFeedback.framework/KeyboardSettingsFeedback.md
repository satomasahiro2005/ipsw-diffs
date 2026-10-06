## KeyboardSettingsFeedback

> `/System/Library/PrivateFrameworks/KeyboardSettingsFeedback.framework/KeyboardSettingsFeedback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x150c` | `0x15b4` | **`+0xa8`** |
| `__AUTH_CONST.__cfstring` | `0x2e0` | `0x340` | **`+0x60`** |
| `__TEXT.__cstring` | `0x478` | `0x4b9` | **`+0x41`** |
| `__AUTH_CONST.__const` | `0x40` | `0x60` | **`+0x20`** |
| `__DATA.__bss` | `0x20` | `0x30` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x230` | `0x240` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x70` | `0x78` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 54
-  Symbols:   141
-  CStrings:  34
+  Functions: 56
+  Symbols:   146
+  CStrings:  37
Symbols:
+ _MGGetBoolAnswer
+ _OBJC_CLASS_$_NSUserDefaults
+ ___47-[TUIFeedbackController feedbackFeatureEnabled]_block_invoke
+ _feedbackFeatureEnabled.is_internal_install
+ _feedbackFeatureEnabled.once_token
Functions:
~ -[TUIFeedbackController feedbackFeatureEnabled] : 84 -> 184
+ ___47-[TUIFeedbackController feedbackFeatureEnabled]_block_invoke
~ _OUTLINED_FUNCTION_1 : 24 -> 20
~ _OUTLINED_FUNCTION_3 : 20 -> 24
~ -[TUIFeedbackController feedbackFeatureEnabled].cold.1 : 136 -> 20
+ -[TUIFeedbackController feedbackFeatureEnabled].cold.2
CStrings:
+ "%s Feedback %@: RC_SEED_BUILD: 0 enabled: %d"
+ "apple-internal-install"
+ "com.apple.keyboard"
+ "feedbackFeatureEnabled"
- "%s Feedback %@: RC_SEED_BUILD: 1 enabled: %d"
```
