## PrivacyDisclosureUI

> `/System/Library/PrivateFrameworks/PrivacyDisclosureUI.framework/PrivacyDisclosureUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fd0` | `0x4f54` | **`-0x7c`** |
| `__TEXT.__oslogstring` | `0x94` | `0xf9` | **`+0x65`** |
| `__DATA_CONST.__got` | `0x198` | `0x1b8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x990` | `0x998` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x840` | `0x848` | **`+0x8`** |
| `__TEXT.__cstring` | `0x490` | `0x491` | **`+0x1`** |

### Other Changes

```diff

-49.0.0.0.0
+49.0.1.0.0

-  Functions: 105
-  Symbols:   340
-  CStrings:  81
+  Functions: 106
+  Symbols:   347
+  CStrings:  82
Symbols:
+ -[PDUDisclosureReviewViewController_iOS privacyLinkTitle]
+ _NSParagraphStyleAttributeName
+ _OBJC_CLASS_$_NSMutableParagraphStyle
+ _OBJC_CLASS_$_OBHeaderAccessoryButton
+ _OBJC_CLASS_$_OBPrivacyLinkController
+ __os_log_impl
+ _objc_retain_x25
CStrings:
+ "PDUDisclosureReviewViewController_iOS privacyLinkTitle obkBundleID: %@ falling back to ABOUT_PRIVACY"
+ "defaultAppearance"
- "info.circle.fill"
```
