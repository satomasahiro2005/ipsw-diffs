## SilexWeb

> `/System/Library/PrivateFrameworks/SilexWeb.framework/SilexWeb`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18e04` | `0x194c8` | **`+0x6c4`** |
| `__AUTH_CONST.__objc_const` | `0x9e40` | `0x9fa0` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x35cc` | `0x36c4` | **`+0xf8`** |
| `__DATA_CONST.__objc_selrefs` | `0x16c0` | `0x1730` | **`+0x70`** |
| `__DATA_CONST.__const` | `0xa40` | `0xa68` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x898` | `0x8c0` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x484` | `0x49c` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x4a8` | `0x4b0` | **`+0x8`** |

### Other Changes

```diff

-5926.0.0.0.0
+5934.2.0.0.0

-  Functions: 938
-  Symbols:   2577
+  Functions: 957
+  Symbols:   2604
Symbols:
+ -[SWContainerViewController pocketInsetsForSafeArea]
+ -[SWContainerViewController setPocketInsetsForSafeArea:]
+ -[SWContentRuleManager removeAllContentRuleLists]
+ -[SWContentRuleManager ruleListIdentifiers]
+ -[SWLocation canBecomeFirstResponder]
+ -[SWLocation initWithContext:URL:canBecomeFocused:canBecomeFirstResponder:]
+ -[SWViewController pocketInsetsForSafeArea]
+ -[SWViewController setPocketInsetsForSafeArea:]
+ -[SWViewController setWebViewCanBecomeFirstResponder:]
+ -[SWViewController webViewCanBecomeFirstResponder]
+ -[SWWebView canBecomeFirstResponder]
+ -[SWWebView canBecomeFocused]
+ -[SWWebView pocketInsetsForSafeArea]
+ -[SWWebView safeAreaInsetsDidChange]
+ -[SWWebView setPocketInsetsForSafeArea:]
+ -[SWWebView setWebViewCanBecomeFirstResponder:]
+ -[SWWebView setWebViewCanBecomeFocused:]
+ -[SWWebView updatePocketInsetsForSafeArea]
+ -[SWWebView webViewCanBecomeFirstResponder]
+ -[SWWebView webViewCanBecomeFocused]
+ _OBJC_IVAR_$_SWContentRuleManager._ruleListIdentifiers
+ _OBJC_IVAR_$_SWLocation._canBecomeFirstResponder
+ _OBJC_IVAR_$_SWViewController._webViewCanBecomeFirstResponder
+ _OBJC_IVAR_$_SWWebView._pocketInsetsForSafeArea
+ _OBJC_IVAR_$_SWWebView._webViewCanBecomeFirstResponder
+ _OBJC_IVAR_$_SWWebView._webViewCanBecomeFocused
+ _UIEdgeInsetsZero
+ ___block_descriptor_48_e8_32s40s_e39_v24?0"WKContentRuleList"8"NSError"16ls32l8s40l8
- -[SWLocation initWithContext:URL:canBecomeFocused:]
```
