## KeyboardSettings

> `/System/Library/PrivateFrameworks/KeyboardSettings.framework/KeyboardSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29fd0` | `0x29c20` | **`-0x3b0`** |
| `__AUTH_CONST.__cfstring` | `0x3260` | `0x3160` | **`-0x100`** |
| `__TEXT.__cstring` | `0x3728` | `0x3628` | **`-0x100`** |
| `__AUTH_CONST.__objc_const` | `0x3540` | `0x34e0` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x2af8` | `0x2ab0` | **`-0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x23c0` | `0x2390` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x5e0` | `0x5d8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1d4` | `0x1cc` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x768` | `0x770` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x960` | `0x958` | **`-0x8`** |

### Other Changes

```diff

-139.0.0.0.0
+142.0.0.0.0

-  Functions: 882
-  Symbols:   1805
-  CStrings:  534
+  Functions: 876
+  Symbols:   1796
+  CStrings:  526
Symbols:
- -[KSKeyboardController advancedDictation:]
- -[KSKeyboardController dictationAdvancedGroupSpecifier]
- -[KSKeyboardController dictationAdvancedSpecifier]
- -[KSKeyboardController setAdvancedDictation:specifier:]
- -[KSKeyboardController setDictationAdvancedGroupSpecifier:]
- -[KSKeyboardController setDictationAdvancedSpecifier:]
- _CFPreferencesAppSynchronize
- _OBJC_IVAR_$_KSKeyboardController._dictationAdvancedGroupSpecifier
- _OBJC_IVAR_$_KSKeyboardController._dictationAdvancedSpecifier
CStrings:
- "ADVANCED_DICTATION_PREVIEW_FOOTER_ENGLISH_ONLY"
- "ADVANCED_DICTATION_PREVIEW_FOOTER_MULTILINGUAL"
- "Advanced Dictation Preview"
- "AdvancedDictationGroup"
- "AdvancedDictationSetting"
- "DeviceSupportsInstructionFollowingPruningModels"
- "EnableFoundationModelDictation"
- "en"
```
