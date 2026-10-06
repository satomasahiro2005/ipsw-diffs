## MessageUI

> `/System/Library/Frameworks/MessageUI.framework/MessageUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14f114` | `0x14f7f0` | **`+0x6dc`** |
| `__TEXT.__gcc_except_tab` | `0x25148` | `0x25208` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x129f4` | `0x12aac` | **`+0xb8`** |
| `__TEXT.__oslogstring` | `0x5d6e` | `0x5e0e` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x1a778` | `0x1a810` | **`+0x98`** |
| `__DATA_CONST.__objc_selrefs` | `0xc200` | `0xc278` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0xa588` | `0xa5c8` | **`+0x40`** |
| `__AUTH_CONST.__objc_dictobj` | `0x578` | `0x5a0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x8e40` | `0x8e60` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x628` | `0x648` | **`+0x20`** |
| `__DATA.__bss` | `0x1d50` | `0x1d60` | **`+0x10`** |
| `__TEXT.__cstring` | `0xa0d6` | `0xa0e6` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1ee0` | `0x1ee8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1144` | `0x1148` | **`+0x4`** |

### Other Changes

```diff

-3895.100.17.2.1
+3897.100.8.2.5

-  Functions: 6860
-  Symbols:   11641
-  CStrings:  2048
+  Functions: 6870
+  Symbols:   11652
+  CStrings:  2051
Symbols:
+ -[MFComposeWebView _composeToolbarShouldProvideWritingToolsButton]
+ -[MFComposeWebView _writingToolsBarButtonItem]
+ -[MFComposeWebView placeCaretBeforeSignature]
+ -[MFMailComposeView _horizontallySafeAreaAdjustedBounds]
+ -[MFMailComposeView _updateHeaderViewLayoutMargins]
+ -[MFMessageComposeViewController insertCompositionText:]
+ -[MFMessageComposeViewController setSuppressesShelfStaging:]
+ -[MFMessageComposeViewController supportsCompositionTextInsertion]
+ -[_MFMailCompositionContext setSuppressAppIntentDonation:]
+ -[_MFMailCompositionContext suppressAppIntentDonation]
+ GCC_except_table229
+ GCC_except_table265
+ _OBJC_IVAR_$__MFMailCompositionContext._suppressAppIntentDonation
+ _UIFontWeightRegular
- GCC_except_table242
- GCC_except_table252
- GCC_except_table268
CStrings:
+ ".MailOutline"
+ "<%p> Skipping attachment with no contentID-derived URL for fileName: %{public}@"
+ "<%p> Skipping attachment with no contentID-derived URL for identifier: %{public}@"
```
