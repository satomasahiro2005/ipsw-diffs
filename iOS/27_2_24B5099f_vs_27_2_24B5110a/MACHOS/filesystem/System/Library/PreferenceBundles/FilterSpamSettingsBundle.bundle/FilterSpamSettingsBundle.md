## FilterSpamSettingsBundle

> `/System/Library/PreferenceBundles/FilterSpamSettingsBundle.bundle/FilterSpamSettingsBundle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x11e` | `0x153` | **`+0x35`** |
| `__TEXT.__text` | `0xaac` | `0xae0` | **`+0x34`** |
| `__DATA_CONST.__cfstring` | `0x100` | `0x120` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x6c5` | `0x6e5` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x460` | `0x480` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x218` | `0x220` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x78` | `0x80` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x90` | `0x98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3077.200.88.0.0
+3077.200.91.0.0

-  Symbols:   60
-  CStrings:  132
+  Symbols:   61
+  CStrings:  134
Symbols:
+ _OBJC_CLASS_$_TUFeatureFlags
Functions:
~ sub_13e0 : 272 -> 324
CStrings:
+ "FILTER_SPAM_EXPLANATION_FACETIME_ARBITRATION_ENABLED"
+ "voicemailSpamArbitrationEnabled"
```
