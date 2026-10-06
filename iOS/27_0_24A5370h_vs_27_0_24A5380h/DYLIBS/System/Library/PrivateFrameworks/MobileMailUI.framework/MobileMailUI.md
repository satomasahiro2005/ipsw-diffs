## MobileMailUI

> `/System/Library/PrivateFrameworks/MobileMailUI.framework/MobileMailUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4de70` | `0x4e440` | **`+0x5d0`** |
| `__TEXT.__oslogstring` | `0x2277` | `0x2397` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0x977c` | `0x983c` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x7cf0` | `0x7d48` | **`+0x58`** |
| `__DATA.__data` | `0x1110` | `0x1158` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x5134` | `0x517c` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x29e0` | `0x2a08` | **`+0x28`** |
| `__DATA.__bss` | `0x60` | `0x48` | **`-0x18`** |
| `__DATA_DIRTY.__bss` | `0x1a0` | `0x1b8` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x68` | `0x80` | **`+0x18`** |
| `__TEXT.__const` | `0x8524` | `0x8534` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb40` | `0xb48` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x158` | `0x160` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4198` | `0x41a0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x4b8` | `0x4bc` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3893.100.7.0.0
+3895.100.17.2.1

-  Functions: 1732
-  Symbols:   3523
-  CStrings:  678
+  Functions: 1737
+  Symbols:   3536
+  CStrings:  682
Symbols:
+ -[MFMessageContentView webViewLoadingController:willIssueLoadForURL:]
+ -[MFWebViewLoadingController clearContent]
+ -[MFWebViewLoadingController delegate]
+ -[MFWebViewLoadingController setDelegate:]
+ GCC_except_table120
+ GCC_except_table126
+ GCC_except_table133
+ GCC_except_table141
+ GCC_except_table144
+ GCC_except_table147
+ GCC_except_table150
+ GCC_except_table156
+ GCC_except_table162
+ GCC_except_table163
+ GCC_except_table176
+ GCC_except_table186
+ GCC_except_table190
+ GCC_except_table199
+ GCC_except_table202
+ GCC_except_table203
+ GCC_except_table206
+ GCC_except_table210
+ GCC_except_table215
+ GCC_except_table220
+ GCC_except_table224
+ GCC_except_table225
+ GCC_except_table228
+ GCC_except_table233
+ GCC_except_table234
+ GCC_except_table241
+ GCC_except_table251
+ GCC_except_table264
+ GCC_except_table267
+ GCC_except_table272
+ GCC_except_table276
+ GCC_except_table279
+ GCC_except_table284
+ GCC_except_table356
+ GCC_except_table357
+ GCC_except_table367
+ GCC_except_table370
+ _OBJC_IVAR_$_MFWebViewLoadingController._delegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MFWebViewLoadingControllerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MFWebViewLoadingControllerDelegate
+ __OBJC_$_PROTOCOL_REFS_MFWebViewLoadingControllerDelegate
+ __OBJC_LABEL_PROTOCOL_$_MFWebViewLoadingControllerDelegate
+ __OBJC_PROTOCOL_$_MFWebViewLoadingControllerDelegate
+ ___64-[MFMessageContentView _webViewWebProcessDidBecomeUnresponsive:]_block_invoke
- GCC_except_table121
- GCC_except_table127
- GCC_except_table136
- GCC_except_table142
- GCC_except_table146
- GCC_except_table148
- GCC_except_table152
- GCC_except_table160
- GCC_except_table164
- GCC_except_table167
- GCC_except_table178
- GCC_except_table188
- GCC_except_table192
- GCC_except_table201
- GCC_except_table204
- GCC_except_table205
- GCC_except_table208
- GCC_except_table217
- GCC_except_table218
- GCC_except_table222
- GCC_except_table226
- GCC_except_table230
- GCC_except_table231
- GCC_except_table235
- GCC_except_table238
- GCC_except_table243
- GCC_except_table259
- GCC_except_table268
- GCC_except_table269
- GCC_except_table274
- GCC_except_table278
- GCC_except_table354
- GCC_except_table355
- GCC_except_table362
- GCC_except_table363
Functions:
~ -[MFMessageContentView _commonInit] : 2916 -> 2928
~ -[MFMessageContentView setContentRequest:] : 1764 -> 1800
~ -[MFWebViewLoadingController _doIssueLoadRequest] : 844 -> 1004
~ -[MFMessageContentView webProcessDidFinishLoadForURL:] : 504 -> 700
~ -[MFMessageContentView _webView:renderingProgressDidChange:] : 1372 -> 1460
~ -[MFMessageContentView dealloc] : 184 -> 196
~ ___42-[MFMessageContentView setContentRequest:]_block_invoke.236 : 952 -> 900
+ -[MFMessageContentView webViewLoadingController:willIssueLoadForURL:]
~ -[MFMessageContentView _webViewWebProcessDidBecomeUnresponsive:] : 352 -> 408
+ ___64-[MFMessageContentView _webViewWebProcessDidBecomeUnresponsive:]_block_invoke
~ -[MFMessageContentView _webView:webContentProcessDidTerminateWithReason:] : 1444 -> 1496
~ -[MFMessageContentView prepareForReuse] : 176 -> 208
+ -[MFWebViewLoadingController clearContent]
+ -[MFWebViewLoadingController delegate]
+ -[MFWebViewLoadingController setRemoteObjectInterface:]
~ -[MFWebViewLoadingController .cxx_destruct] : 124 -> 132
CStrings:
+ "2"
+ "<%{public}@: %p> Web process did finish load for content request: %{public}@ message: %{public}@ finishedURL=%{public}@ webView.URL=%{public}@ webProcessPID=%d"
+ "<%{public}@: %p>: %{public}@ %@ (pid: %d) — recovering via slapWebView"
+ "<%{public}@: %p>: Clearing webview content: %@"
+ "<%{public}@: %p>: Sending request to load webview with content representation: %{public}@ webView=%p webProcessPID=%d"
+ "<%{public}@: %p>: rendering progress did first paint, removing loading indicator. webView.URL=%{public}@ webView=%p webProcessPID=%d"
+ "MFWebViewLoadingController.clearContent"
+ "WebView=%{public}p"
- "<%{public}@: %p> Web process did finish load for content request: %{public}@ message: %{public}@"
- "<%{public}@: %p>: %{public}@ %@ (pid: %d)"
- "<%{public}@: %p>: Sending request to load webview with content representation: %{public}@"
- "<%{public}@: %p>: rendering progress did first paint, removing loading indicator"
```
