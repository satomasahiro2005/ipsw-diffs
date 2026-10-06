## TVSettings

> `/System/Library/PreferenceBundles/TVSettings.bundle/TVSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeee4` | `0xf560` | **`+0x67c`** |
| `__TEXT.__cstring` | `0x1d86` | `0x1f26` | **`+0x1a0`** |
| `__DATA_CONST.__cfstring` | `0x1ec0` | `0x2040` | **`+0x180`** |
| `__TEXT.__objc_methname` | `0x3b6e` | `0x3cb8` | **`+0x14a`** |
| `__TEXT.__objc_stubs` | `0x2640` | `0x2720` | **`+0xe0`** |
| `__DATA.__objc_selrefs` | `0xf28` | `0xf88` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x114c` | `0x11ac` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x241` | `0x27c` | **`+0x3b`** |
| `__DATA_CONST.__const` | `0x7c8` | `0x7e0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x420` | `0x438` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
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

-1145.1.3.0.0
+1145.10.20.0.0

-  Functions: 326
+  Functions: 334

-  CStrings:  999
+  CStrings:  1027
CStrings:
+ "ALWAYS_SHOW_PROFILE_SELECTION"
+ "Localizable-SimpleProfilesPersonal"
+ "PROFILE_SELECTION_GROUP_FOOTER"
+ "Settings Always Show Profile Selection value changed to %d"
+ "SignLanguage"
+ "Toggle Always Show Profile Selection"
+ "Toggle Sign Language"
+ "UNDO_ALWAYS_SHOW_PROFILE_SELECTION"
+ "UNDO_SIGN_LANGUAGE"
+ "_removeSignLanguageFromSpecifiers:"
+ "_setAlwaysShowProfileSelection:"
+ "_setSignLanguageEnabled:specifier:"
+ "alwaysShowProfileSelection"
+ "alwaysShowProfileSelection:"
+ "com.apple.videos:AlwaysShowProfileSelection"
+ "com.apple.videos:ProfileSelectionGroup"
+ "com.apple.videos:SignLanguage"
+ "com.apple.videos:SignLanguageGroup"
+ "default"
+ "eyesOfTheWorld"
+ "setAlwaysShowProfileSelection:"
+ "setIdentifier:"
+ "setSignLanguageEnabled:"
+ "setSignLanguageEnabled:specifier:"
+ "signLanguageEnabled"
+ "signLanguageEnabled:"
+ "sp_personal"
+ "videosSignLanguageSpecifier"
```
