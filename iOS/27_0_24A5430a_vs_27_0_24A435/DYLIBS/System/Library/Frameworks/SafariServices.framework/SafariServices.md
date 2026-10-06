## SafariServices

> `/System/Library/Frameworks/SafariServices.framework/SafariServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x183b40` | `0x183bc0` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x2200` | `0x2220` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x77f8` | `0x7818` | **`+0x20`** |
| `__TEXT.__cstring` | `0xd450` | `0xd470` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xfc6c` | `0xfc84` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x12318` | `0x12328` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x2c6a0` | `0x2c6a8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1bd44` | `0x1bd4c` | **`+0x8`** |

### Other Changes

```diff

-625.1.29.10.28
+625.1.29.10.29

-  Functions: 9283
-  Symbols:   17522
-  CStrings:  2548
+  Functions: 9284
+  Symbols:   17525
+  CStrings:  2549
Symbols:
+ -[SFWebViewController _webView:requestWebAuthenticationConditionalMediationRegistrationForUser:relatedOrigins:completionHandler:]
+ GCC_except_table116
+ ___129-[SFWebViewController _webView:requestWebAuthenticationConditionalMediationRegistrationForUser:relatedOrigins:completionHandler:]_block_invoke
+ ___129-[SFWebViewController _webView:requestWebAuthenticationConditionalMediationRegistrationForUser:relatedOrigins:completionHandler:]_block_invoke_2
+ ___block_descriptor_32_e36_"NSString"16?0"WKSecurityOrigin"8l
- -[SFWebViewController _webView:requestWebAuthenticationConditionalMediationRegistrationForUser:completionHandler:]
- ___114-[SFWebViewController _webView:requestWebAuthenticationConditionalMediationRegistrationForUser:completionHandler:]_block_invoke
CStrings:
+ "@\"NSString\"16@?0@\"WKSecurityOrigin\"8"
```
