## MobileMailUI

> `/System/Library/PrivateFrameworks/MobileMailUI.framework/MobileMailUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x2367` | `0x24b7` | **`+0x150`** |
| `__TEXT.__text` | `0x4e92c` | `0x4e9a4` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x98c0` | `0x9890` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x7fd8` | `0x7ff8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xb48` | `0xb60` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x4258` | `0x4270` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x5304` | `0x531c` | **`+0x18`** |
| `__TEXT.__const` | `0x8514` | `0x8504` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2a58` | `0x2a60` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x4dc` | `0x4e0` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3901.200.34.0.0
+3901.200.41.0.0

-  Functions: 1764
-  Symbols:   3583
-  CStrings:  678
+  Functions: 1766
+  Symbols:   3591
+  CStrings:  679
Symbols:
+ -[MFMessageContentView _committedDocumentMatchesContentURL:]
+ -[MFMessageContentView _discardFirstPaintGateState]
+ -[MFMessageContentView _handleNavigationFailure:]
+ -[MFMessageContentView webView:didFailProvisionalNavigation:withError:]
+ -[MFWebViewLoadingController cancelPendingContent]
+ GCC_except_table158
+ GCC_except_table160
+ GCC_except_table165
+ GCC_except_table167
+ GCC_except_table178
+ GCC_except_table188
+ GCC_except_table201
+ GCC_except_table204
+ GCC_except_table214
+ GCC_except_table217
+ GCC_except_table227
+ GCC_except_table229
+ GCC_except_table236
+ GCC_except_table238
+ GCC_except_table243
+ GCC_except_table253
+ GCC_except_table255
+ GCC_except_table266
+ GCC_except_table268
+ GCC_except_table269
+ GCC_except_table274
+ GCC_except_table281
+ GCC_except_table283
+ GCC_except_table286
+ GCC_except_table288
+ GCC_except_table360
+ GCC_except_table361
+ GCC_except_table369
+ GCC_except_table371
+ GCC_except_table372
+ GCC_except_table374
+ _EMErrorDomain
+ _NSURLErrorDomain
+ _OBJC_IVAR_$_MFMessageContentView._committedDocumentURL
+ _WKErrorDomain
- -[MFWebViewLoadingController clearContent]
- -[VIPManager allVIPEmailAddressesCriterion]
- -[VIPManager criterionForEmailAddresses:]
- GCC_except_table151
- GCC_except_table156
- GCC_except_table162
- GCC_except_table168
- GCC_except_table169
- GCC_except_table171
- GCC_except_table182
- GCC_except_table196
- GCC_except_table209
- GCC_except_table220
- GCC_except_table221
- GCC_except_table233
- GCC_except_table234
- GCC_except_table239
- GCC_except_table240
- GCC_except_table242
- GCC_except_table247
- GCC_except_table261
- GCC_except_table263
- GCC_except_table270
- GCC_except_table272
- GCC_except_table273
- GCC_except_table282
- GCC_except_table356
- GCC_except_table357
- GCC_except_table364
- GCC_except_table365
- GCC_except_table366
- GCC_except_table367
CStrings:
+ "<%{public}@: %p>: Canceling pending content: %@"
+ "<%{public}@: %p>: Message Content View did fail navigation, substituting error content: %{public}@"
+ "<%{public}@: %p>: honoring first paint for error markup, skipping the content URL match. committed=%{public}@"
+ "<%{public}@: %p>: superseded navigation, not treating as a failure: %{public}@"
+ "<%{public}@: %p>: webView first paint precedes the commit of the expected document, disregarding this event. committed=%{public}@ expected=%{public}@ loading indicator visible: %@"
+ "\xf0\xf0R"
- "<%{public}@: %p>: Clearing webview content: %@"
- "<%{public}@: %p>: Message Content View did fail navigation: %{public}@"
- "MFWebViewLoadingController.clearContent"
- "WebView=%{public}p"
- "\xf0\xf0B"
```
