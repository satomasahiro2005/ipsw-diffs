## ScreenshotServices

> `/System/Library/PrivateFrameworks/ScreenshotServices.framework/ScreenshotServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e680` | `0x1e764` | **`+0xe4`** |
| `__TEXT.__oslogstring` | `0x17cc` | `0x1802` | **`+0x36`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c88` | `0x1c98` | **`+0x10`** |

### Other Changes

```diff

-  Symbols:   2122
-  CStrings:  487
+  Symbols:   2123
+  CStrings:  488
Symbols:
+ _MGGetProductType
Functions:
~ __SSVisualIntelligenceV2Enabled : 84 -> 112
~ __SSVisualIntelligenceV2EnabledForContext : 72 -> 268
~ -[UIView(SSPreferences) _ss_vi2Enabled] : 268 -> 272
CStrings:
+ "VIV2 disabled due to regular-compact landscape layout"
```
