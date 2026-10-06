## TVSettings

> `/System/Library/PreferenceBundles/TVSettings.bundle/TVSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf560` | `0xff28` | **`+0x9c8`** |
| `__TEXT.__objc_methname` | `0x3cb8` | `0x3e89` | **`+0x1d1`** |
| `__TEXT.__objc_stubs` | `0x2720` | `0x28e0` | **`+0x1c0`** |
| `__DATA_CONST.__cfstring` | `0x2040` | `0x21e0` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x1f26` | `0x2086` | **`+0x160`** |
| `__DATA.__objc_const` | `0x2228` | `0x2308` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x11ac` | `0x1234` | **`+0x88`** |
| `__DATA.__objc_selrefs` | `0xf88` | `0x1000` | **`+0x78`** |
| `__DATA.__objc_data` | `0x910` | `0x960` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x523` | `0x553` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x27c` | `0x2aa` | **`+0x2e`** |
| `__DATA_CONST.__got` | `0x310` | `0x328` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x438` | `0x448` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xf8` | `0x100` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x7e0` | `0x7e8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xf0` | `0xf8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xa8` | `0xb0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1145.10.22.0.1
+1145.10.26.0.0

-  Functions: 334
-  Symbols:   235
-  CStrings:  1027
+  Functions: 344
+  Symbols:   238
+  CStrings:  1060
Symbols:
+ _UIAccessibilityTraitSelected
+ _WLKSignLanguageCodeASL
+ _WLKSignLanguageCodeBSL
CStrings:
+ "Change Download Sign Language"
+ "Change Sign Language Setting"
+ "DOWNLOAD_SIGN_LANGUAGES_EXPLANATION"
+ "DOWNLOAD_SIGN_LANGUAGES_TITLE"
+ "DOWNLOAD_SIGN_LANGUAGE_OFF"
+ "PreferredSignLanguagesDidChangeNotification"
+ "SIGN_LANGUAGE_ASL"
+ "SIGN_LANGUAGE_BSL"
+ "SIGN_LANGUAGE_SELECTION_TITLE"
+ "Setting download sign language to %{public}@."
+ "SignLanguageNoneOption"
+ "SignLanguageOffOption"
+ "T@\"NSString\",&,N"
+ "TVSettingsSignLanguageListItemsController"
+ "UNDO_SIGN_LANGUAGE_OPERATION"
+ "_isSignLanguageChoiceSpecifier:"
+ "_selectSignLanguageChoice:"
+ "_selectedSignLanguageChoiceCode"
+ "_setDownloadSignLanguageCode:"
+ "_setSignLanguage:specifier:"
+ "_signLanguageChoiceSpecifiers"
+ "_signLanguagesGroupSpecifier"
+ "_specifierForSignLanguageChoice:"
+ "accessibilityTraits"
+ "bfi"
+ "com.apple.videos:SignLanguagesGroupSpecifier"
+ "deselectRowAtIndexPath:animated:"
+ "downloadSignLanguageCode"
+ "setAccessibilityTraits:"
+ "setAccessoryType:"
+ "setDownloadSignLanguageCode:"
+ "setSignLanguage:specifier:"
+ "setSignLanguageCode:"
+ "setSignLanguageCodeDownload:"
+ "showSignLanguage:"
+ "signLanguageCode"
+ "signLanguageCodeDownload"
+ "specifierAtIndexPath:"
+ "tableView:cellForRowAtIndexPath:"
- "Toggle Sign Language"
- "_setSignLanguageEnabled:specifier:"
- "setSignLanguageEnabled:"
- "setSignLanguageEnabled:specifier:"
- "signLanguageEnabled"
- "signLanguageEnabled:"
```
