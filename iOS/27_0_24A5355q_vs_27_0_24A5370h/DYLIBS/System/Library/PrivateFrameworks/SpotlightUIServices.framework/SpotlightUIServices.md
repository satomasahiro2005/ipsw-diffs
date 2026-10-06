## SpotlightUIServices

> `/System/Library/PrivateFrameworks/SpotlightUIServices.framework/SpotlightUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x52de8` | `0x52f1c` | **`+0x134`** |
| `__AUTH_CONST.__objc_const` | `0x71f0` | `0x7220` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4ce8` | `0x4d00` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xb30` | `0xb40` | **`+0x10`** |
| `__TEXT.__const` | `0xbe4` | `0xbf4` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x318` | `0x324` | **`+0xc`** |
| `__DATA.__data` | `0x210` | `0x218` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x14d0` | `0x14d8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e30` | `0x2e38` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x478` | `0x480` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1400` | `0x13f8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x4bc` | `0x4c0` | **`+0x4`** |

### Other Changes

```diff

-228.102.0.0.0
+235.3.100.0.0

-  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels

-  Functions: 2169
-  Symbols:   3552
+  Functions: 2171
+  Symbols:   3558
Symbols:
+ +[SPUISActionSuggestionResultBuilder buildResultWithTitle:subtitle:thumbnail:actionIdentifier:canonicalIdentifier:commandDetail:]
+ -[SPUISActionSuggestionResultBuilder commandDetail]
+ -[SPUISActionSuggestionResultBuilder setCommandDetail:]
+ _OBJC_CLASS_$_GMAvailabilityWrapper
+ _OBJC_IVAR_$_SPUISActionSuggestionResultBuilder._commandDetail
+ _swift_release_x24
+ _swift_retain_x24
+ _symbolic _____Sg 32AssistantActionSuggestionSupport16SemanticIdentityO
- +[SPUISActionSuggestionResultBuilder buildResultWithTitle:subtitle:thumbnail:actionIdentifier:canonicalIdentifier:]
- _AFIsLinwoodEnabledAndAvailable
```
