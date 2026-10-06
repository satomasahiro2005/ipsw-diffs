## DisembarkUI

> `/System/Library/PrivateFrameworks/DisembarkUI.framework/DisembarkUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x228e0` | `0x22cc8` | **`+0x3e8`** |
| `__TEXT.__objc_methlist` | `0x2bd0` | `0x2dd0` | **`+0x200`** |
| `__AUTH_CONST.__objc_const` | `0x5408` | `0x55b8` | **`+0x1b0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c50` | `0x1df8` | **`+0x1a8`** |
| `__DATA.__data` | `0xb80` | `0xc40` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x2088` | `0x20d8` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x17e0` | `0x1820` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x508` | `0x548` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x10d0` | `0x10f8` | **`+0x28`** |
| `__DATA_CONST.__objc_protolist` | `0xf8` | `0x108` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x8e0` | `0x8e8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2f8` | `0x2f4` | **`-0x4`** |

### Other Changes

```diff

-285.1.3.0.0
+285.1.4.0.0

-  Symbols:   2006
-  CStrings:  403
+  Symbols:   2025
+  CStrings:  406
Symbols:
+ -[DKIntroViewController _createSanitizeStorageLearnMoreView]
+ -[DKIntroViewController textView:primaryActionForTextItem:defaultAction:]
+ _NSFontAttributeName
+ _NSForegroundColorAttributeName
+ _NSLinkAttributeName
+ _OBJC_CLASS_$_NSAttributedString
+ _OBJC_CLASS_$_NSMutableAttributedString
+ _OBJC_CLASS_$_UIAction
+ _OBJC_CLASS_$_UITextView
+ _UIEdgeInsetsZero
+ _UIFontTextStyleCaption2
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UIScrollViewDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UITextViewDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UIScrollViewDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UITextViewDelegate
+ __OBJC_$_PROTOCOL_REFS_UIScrollViewDelegate
+ __OBJC_$_PROTOCOL_REFS_UITextViewDelegate
+ __OBJC_CLASS_PROTOCOLS_$_DKIntroViewController
+ __OBJC_LABEL_PROTOCOL_$_UIScrollViewDelegate
+ __OBJC_LABEL_PROTOCOL_$_UITextViewDelegate
+ __OBJC_PROTOCOL_$_UIScrollViewDelegate
+ __OBJC_PROTOCOL_$_UITextViewDelegate
+ ___73-[DKIntroViewController textView:primaryActionForTextItem:defaultAction:]_block_invoke
+ ___block_descriptor_40_e8_32s_e18_v16?0"UIAction"8ls32l8
- -[DKIntroViewController _createSanitizeStorageLearnMoreController]
- -[DKIntroViewController sanitizeStorageLearnMoreController]
- -[DKIntroViewController setSanitizeStorageLearnMoreController:]
- _OBJC_CLASS_$_OBPrivacyLinkController
- _OBJC_IVAR_$_DKIntroViewController._sanitizeStorageLearnMoreController
CStrings:
+ " "
+ "SANITIZE_STORAGE_LEARN_MORE"
+ "SANITIZE_STORAGE_LEARN_MORE_BODY"
+ "SANITIZE_STORAGE_LEARN_MORE_URL"
+ "v16@?0@\"UIAction\"8"
- "OverwriteStorageLearnMore"
- "bundle"
```
