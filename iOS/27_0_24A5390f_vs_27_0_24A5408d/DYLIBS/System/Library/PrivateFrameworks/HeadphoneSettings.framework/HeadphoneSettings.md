## HeadphoneSettings

> `/System/Library/PrivateFrameworks/HeadphoneSettings.framework/HeadphoneSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xca58` | `0xd3b4` | **`+0x95c`** |
| `__AUTH_CONST.__auth_got` | `0x438` | `0x4b8` | **`+0x80`** |
| `__DATA.__data` | `0x238` | `0x278` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xc2` | `0xfa` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x220` | **`+0x30`** |
| `__TEXT.__const` | `0x334` | `0x364` | **`+0x30`** |
| `__TEXT.__cstring` | `0xbe9` | `0xc19` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x4f0` | `0x508` | **`+0x18`** |

### Other Changes

```diff

-2700.16.0.0.0
+2700.17.0.0.0

+  - /System/Library/PrivateFrameworks/Settings.framework/Settings

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

-  Functions: 488
-  Symbols:   680
-  CStrings:  211
+  Functions: 495
+  Symbols:   688
+  CStrings:  212
Symbols:
+ ___swift_destroy_boxed_opaque_existential_1
+ ___swift_project_boxed_opaque_existential_1
+ _symbolic _____Sg 19HeadphoneSettingsUI0aB13UIFeatureTypeO
+ _symbolic _____Sg_ABt 19HeadphoneSettingsUI0aB13UIFeatureTypeO
+ _symbolic ______p 16HeadphoneManager0A18FeatureContentTypeP
+ _symbolic ______p 19HeadphoneSettingsUI0aB17UIContentProviderP
+ _symbolic ______pSg 16HeadphoneManager0A18FeatureContentTypeP
+ _symbolic ______pSg 19HeadphoneSettingsUI0aB17UIContentProviderP
CStrings:
+ "HeadphoneSettingsController"
```
