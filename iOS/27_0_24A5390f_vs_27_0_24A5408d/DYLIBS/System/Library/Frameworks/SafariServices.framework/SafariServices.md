## SafariServices

> `/System/Library/Frameworks/SafariServices.framework/SafariServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1838e4` | `0x183a04` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x1bc9c` | `0x1bd2c` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x12290` | `0x12300` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x2c618` | `0x2c678` | **`+0x60`** |
| `__TEXT.__ustring` | `0x37d2` | `0x3774` | **`-0x5e`** |
| `__TEXT.__gcc_except_tab` | `0xfc30` | `0xfc6c` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x77d0` | `0x77f8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xc400` | `0xc3e0` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x91e8` | `0x9208` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2708` | `0x2710` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-625.1.24.10.1
+625.1.29.10.3

-  Functions: 9273
-  Symbols:   17504
-  CStrings:  2549
+  Functions: 9282
+  Symbols:   17519
+  CStrings:  2548
Symbols:
+ +[SFDialog(SafariServicesExtras) allowDownloadDialogWithDownload:accountableHost:navigatedWebView:allowViewAction:completionHandler:]
+ +[SFDialog(SafariServicesExtras) downloadBlockedDialogWithFileType:accountableHost:presentingURL:completionHandler:]
+ +[_SFFeatureAvailability _douyinSearchProviderIsAvailble]
+ -[_SFBrowserContentViewController navigationBarInsets]
+ -[_SFBrowserContentViewController oneTimeCodeProviderForAutomaticPasswordChangeController:]
+ -[_SFBrowserContentViewController prefersStatusBarHidden]
+ -[_SFBrowserView navigationBarInsets]
+ -[_SFDownload accountableHost]
+ -[_SFDownload setAccountableHost:]
+ -[_SFNavigationBar minimumContentInsets]
+ -[_SFNavigationBar setMinimumContentInsets:]
+ -[_SFNavigationBar setTabBarTheme:]
+ GCC_except_table141
+ GCC_except_table144
+ GCC_except_table158
+ GCC_except_table163
+ GCC_except_table167
+ GCC_except_table176
+ GCC_except_table206
+ GCC_except_table237
+ GCC_except_table238
+ GCC_except_table244
+ GCC_except_table248
+ GCC_except_table262
+ GCC_except_table263
+ GCC_except_table277
+ GCC_except_table278
+ GCC_except_table281
+ GCC_except_table670
+ _OBJC_CLASS_$_SFUnifiedBarTheme
+ _OBJC_IVAR_$__SFDownload._accountableHost
+ _OBJC_IVAR_$__SFNavigationBar._minimumContentInsets
+ _WBSSearchProviderShortNameDouyin
+ _WBSTabClusteringPolicyKey
+ ___133+[SFDialog(SafariServicesExtras) allowDownloadDialogWithDownload:accountableHost:navigatedWebView:allowViewAction:completionHandler:]_block_invoke
+ ___133+[SFDialog(SafariServicesExtras) allowDownloadDialogWithDownload:accountableHost:navigatedWebView:allowViewAction:completionHandler:]_block_invoke_2
+ ___block_descriptor_48_ea8_32s40bs_e8_v12?0B8ls32l8s40l8
+ _areEssentiallyPixelEqual
- +[SFDialog(SafariServicesExtras) allowDownloadDialogWithDownload:initiatingSecurityOrigin:navigatedWebView:allowViewAction:completionHandler:]
- +[SFDialog(SafariServicesExtras) downloadBlockedDialogWithFileType:initiatingSecurityOrigin:presentingURL:completionHandler:]
- -[_SFBrowserContentViewController _lockWebViewSafeAreaInsetTopForNavigationSnapshot]
- -[_SFBrowserContentViewController webViewController:willSnapshotBackForwardListItem:]
- GCC_except_table116
- GCC_except_table146
- GCC_except_table154
- GCC_except_table160
- GCC_except_table172
- GCC_except_table241
- GCC_except_table242
- GCC_except_table251
- GCC_except_table252
- GCC_except_table264
- GCC_except_table271
- GCC_except_table275
- GCC_except_table279
- _OBJC_IVAR_$_SFPasswordPickerServiceViewController._presentInPopover
- _OBJC_IVAR_$__SFBrowserContentViewController._isLockingTopSafeAreaInsetForNavigationSnapshot
- _WBSAutoTabClusteringEnabledKey
- _WBSEnableGraphicIconsInCompletionListKey
- ___142+[SFDialog(SafariServicesExtras) allowDownloadDialogWithDownload:initiatingSecurityOrigin:navigatedWebView:allowViewAction:completionHandler:]_block_invoke
- ___142+[SFDialog(SafariServicesExtras) allowDownloadDialogWithDownload:initiatingSecurityOrigin:navigatedWebView:allowViewAction:completionHandler:]_block_invoke_2
CStrings:
+ "&channel=41"
+ "a\xf0T"
- "&channel=42"
- "Do you want to download “%@” on “%@” and “%@”?"
- "a\xf0D"
```
