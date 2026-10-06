## MailUI

> `/System/Library/PrivateFrameworks/MailUI.framework/MailUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x358924` | `0x35689c` | **`-0x2088`** |
| `__TEXT.__cstring` | `0xeaf9` | `0xef29` | **`+0x430`** |
| `__TEXT.__const` | `0x11484` | `0x11224` | **`-0x260`** |
| `__DATA_DIRTY.__bss` | `0x57f0` | `0x56f0` | **`-0x100`** |
| `__DATA.__bss` | `0x7e18` | `0x7d20` | **`-0xf8`** |
| `__TEXT.__swift5_reflstr` | `0x3e6b` | `0x3d73` | **`-0xf8`** |
| `__AUTH_CONST.__const` | `0x12a80` | `0x129b0` | **`-0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x3784` | `0x36c4` | **`-0xc0`** |
| `__AUTH.__objc_data` | `0x1da0` | `0x1cf0` | **`-0xb0`** |
| `__TEXT.__constg_swiftt` | `0x4934` | `0x48a0` | **`-0x94`** |
| `__TEXT.__unwind_info` | `0x6c30` | `0x6bb0` | **`-0x80`** |
| `__TEXT.__swift5_typeref` | `0x1939a` | `0x19352` | **`-0x48`** |
| `__AUTH_CONST.__cfstring` | `0x4860` | `0x48a0` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x3648` | `0x3608` | **`-0x40`** |
| `__TEXT.__swift5_capture` | `0x5778` | `0x57b8` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x32c4` | `0x328c` | **`-0x38`** |
| `__DATA_CONST.__const` | `0x2fd0` | `0x3000` | **`+0x30`** |
| `__DATA.__data` | `0x7288` | `0x7260` | **`-0x28`** |
| `__AUTH.__data` | `0x14b0` | `0x1490` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x9f1c` | `0x9efc` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0xe38` | `0xe4c` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x1fc8` | `0x1fd8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6680` | `0x6670` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x6a0` | `0x690` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x578` | `0x568` | **`-0x10`** |
| `__AUTH_CONST.__objc_const` | `0x144c8` | `0x144c0` | **`-0x8`** |
| `__DATA_CONST.__objc_catlist` | `0xc8` | `0xd0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x598` | `0x590` | **`-0x8`** |

### Other Changes

```diff

-3901.100.1.2.14
+3901.200.34.0.0

-  Functions: 15629
-  Symbols:   8739
-  CStrings:  2075
+  Functions: 15571
+  Symbols:   8737
+  CStrings:  2092
Symbols:
+ -[MUIMessageListViewController reportEngagementAction:onItemID:atIndexPath:]
+ -[MessageListPositionHelper actuallyVisibleIndexPaths]
+ -[UILabel(MailUI) mui_updateAccessibilityIdentifierHasHighlighted]
+ GCC_except_table78
+ _NSBackgroundColorAttributeName
+ _OBJC_CLASS_$_ACAccount
+ _ShouldUpdateAccessibilityIdentifier
+ _ShouldUpdateAccessibilityIdentifier.onceToken
+ _ShouldUpdateAccessibilityIdentifier.shouldUpdateAccessibilityIdentifier
+ _UpdateAccessibilityIdentifierIfNeeded
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UILabel_$_MailUI
+ __OBJC_$_CATEGORY_UILabel_$_MailUI
+ ___54-[MessageListPositionHelper actuallyVisibleIndexPaths]_block_invoke
+ ___66-[UILabel(MailUI) mui_updateAccessibilityIdentifierHasHighlighted]_block_invoke
+ ___ShouldUpdateAccessibilityIdentifier_block_invoke
+ ___block_descriptor_40_e8_32r_e36_v40?0"UIColor"8{_NSRange=QQ}16^B32lr32l8
+ ___block_descriptor_72_e8_32s_e21_B16?0"NSIndexPath"8ls32l8
+ _kMUIShouldShowHasHighlightedInAccessibilityIdentifierKey
+ _symbolic SDy_____ypG_____Spy_____GIggyy_ So21NSAttributedStringKeya So8_NSRangeV 10ObjectiveC8ObjCBoolV
- -[MessageListPositionHelper actuallyVisibleItemIDs]
- GCC_except_table108
- GCC_except_table77
- GCC_except_table79
- _OBJC_CLASS_$__TtC6MailUI25CircularPlatformImageView
- _OBJC_METACLASS_$_UIImageView
- _OBJC_METACLASS_$__TtC6MailUI25CircularPlatformImageView
- __DATA__TtC6MailUI25CircularPlatformImageView
- __INSTANCE_METHODS__TtC6MailUI25CircularPlatformImageView
- __METACLASS_DATA__TtC6MailUI25CircularPlatformImageView
- ___51-[MessageListPositionHelper actuallyVisibleItemIDs]_block_invoke
- ___block_descriptor_72_e8_32s_e21_16?0"NSIndexPath"8ls32l8
- _associated conformance 6MailUI16PlatformLocationVSHAASQ
- _associated conformance 6MailUI31MUIBackgroundConfigurationStyleOSHAASQ
- _symbolic SaySo15MUIGradientStopCG
- _symbolic So15CAGradientLayerC
- _symbolic So6UIFontCSg
- _symbolic _____ 6MailUI16PlatformLocationV
- _symbolic _____ 6MailUI25CircularPlatformImageViewC
- _symbolic _____ 6MailUI31MUIBackgroundConfigurationStyleO
- _type_layout_string 6MailUI16PlatformLocationV
CStrings:
+ "\r"
+ "\r\n"
+ "&amp;"
+ "&gt;"
+ "&lt;"
+ ".hasHighlighted"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/System/Library/PrivateFrameworks/Email.framework/Headers/EMContentRequestOptions.h"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Mail/MailUI/MailUI/iOS/Buckets/Cell/BucketCellContentView.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Mail/MailUI/MailUI/iOS/Buckets/ViewController/BucketsViewControllerDropSessionHelper.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Mail/MailUI/MailUI/iOS/Message List/CatchUp/MUIPriorityMessageListBackgroundDecorationView.swift"
+ "<"
+ "</body></html>"
+ "<br>"
+ "<html><body dir=\"auto\">"
+ ">"
+ "ShouldShowHasHighlightedInAccessibilityIdentifier"
+ "aa_primaryAppleAccount"
+ "const body = document.body;\n// The `Apple-mail-*` class strings and bare `attachment` tag are how MessageUI renders\n// inline photos/PDFs/files; we hardcode them because the ObjC constants aren't in scope here.\nconst preservedSelector = 'blockquote[type=\"cite\"], div#AppleMailSignature, attachment, ' +\n    '.Apple-mail-imageattach, .Apple-mail-pdf, .Apple-mail-fileattach';\n// Use querySelector + walk up so we find the body-level ancestor of a preserved\n// node even when MessageUI wraps it in a div (e.g., a blockquote nested inside\n// a `<div>` wrapper in a user-pasted reply). Iterating `body.children` and\n// matching directly would miss those.\nlet firstPreserved = body.querySelector(preservedSelector);\nwhile (firstPreserved && firstPreserved.parentNode !== body) {\n    firstPreserved = firstPreserved.parentNode;\n}\nif (firstPreserved === null) {\n    body.innerHTML = newHTML;\n    return;\n}\nwhile (body.firstChild && body.firstChild !== firstPreserved) {\n    body.removeChild(body.firstChild);\n}\nif (newHTML.length > 0) {\n    // Insert the parsed nodes directly via a <template> so we don't introduce an\n    // extra wrapper <div> — keeping the same DOM shape as the no-preserved-node\n    // path above (which assigns to `body.innerHTML` without a wrapper).\n    const template = document.createElement('template');\n    template.innerHTML = newHTML;\n    body.insertBefore(template.content, firstPreserved);\n}"
+ "hand.raised.fill"
+ "v40@?0@\"UIColor\"8{_NSRange=QQ}16^B32"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/System/Library/PrivateFrameworks/Email.framework/Headers/EMContentRequestOptions.h"
- "const body = document.body;\nconst preservedSelector = 'blockquote[type=\"cite\"], div#AppleMailSignature';\n// Use querySelector + walk up so we find the body-level ancestor of a preserved\n// node even when MessageUI wraps it in a div (e.g., a blockquote nested inside\n// a `<div>` wrapper in a user-pasted reply). Iterating `body.children` and\n// matching directly would miss those.\nlet firstPreserved = body.querySelector(preservedSelector);\nwhile (firstPreserved && firstPreserved.parentNode !== body) {\n    firstPreserved = firstPreserved.parentNode;\n}\nif (firstPreserved === null) {\n    body.innerHTML = newHTML;\n    return;\n}\nwhile (body.firstChild && body.firstChild !== firstPreserved) {\n    body.removeChild(body.firstChild);\n}\nif (newHTML.length > 0) {\n    // Insert the parsed nodes directly via a <template> so we don't introduce an\n    // extra wrapper <div> — keeping the same DOM shape as the no-preserved-node\n    // path above (which assigns to `body.innerHTML` without a wrapper).\n    const template = document.createElement('template');\n    template.innerHTML = newHTML;\n    body.insertBefore(template.content, firstPreserved);\n}"
- "hand.slash"
```
