## MobileSafariUI

> `/System/Library/PrivateFrameworks/MobileSafariUI.framework/MobileSafariUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ee368` | `0x2ee578` | **`+0x210`** |
| `__TEXT.__gcc_except_tab` | `0x1f4c8` | `0x1f4f4` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0x88c0` | `0x88e0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x98a0` | `0x98c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x10a64` | `0x10a84` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x186e0` | `0x186f0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x10288` | `0x10298` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x33450` | `0x33458` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x24d54` | `0x24d5c` | **`+0x8`** |

### Other Changes

```diff

-625.1.29.10.28
+625.1.29.10.29

-  Functions: 16267
-  Symbols:   23016
-  CStrings:  3282
+  Functions: 16270
+  Symbols:   23028
+  CStrings:  3283
Symbols:
+ -[TabDocument _webView:requestWebAuthenticationConditionalMediationRegistrationForUser:relatedOrigins:completionHandler:]
+ GCC_except_table1225
+ GCC_except_table368
+ GCC_except_table708
+ GCC_except_table749
+ GCC_except_table759
+ GCC_except_table761
+ GCC_except_table776
+ GCC_except_table783
+ GCC_except_table791
+ GCC_except_table809
+ GCC_except_table816
+ GCC_except_table833
+ GCC_except_table851
+ GCC_except_table868
+ GCC_except_table871
+ GCC_except_table889
+ GCC_except_table909
+ GCC_except_table921
+ GCC_except_table928
+ GCC_except_table944
+ GCC_except_table963
+ GCC_except_table971
+ GCC_except_table979
+ GCC_except_table981
+ ___121-[TabDocument _webView:requestWebAuthenticationConditionalMediationRegistrationForUser:relatedOrigins:completionHandler:]_block_invoke
+ ___121-[TabDocument _webView:requestWebAuthenticationConditionalMediationRegistrationForUser:relatedOrigins:completionHandler:]_block_invoke_2
+ ___45-[StartPageController _resumeBrowsingSection]_block_invoke_10
+ ___75+[TabMenuProvider menuForClusterWithID:title:tabCount:location:dataSource:]_block_invoke_9
+ ___block_descriptor_32_e36_"NSString"16?0"WKSecurityOrigin"8l
- -[TabDocument _webView:requestWebAuthenticationConditionalMediationRegistrationForUser:completionHandler:]
- GCC_except_table718
- GCC_except_table762
- GCC_except_table784
- GCC_except_table808
- GCC_except_table817
- GCC_except_table827
- GCC_except_table830
- GCC_except_table840
- GCC_except_table850
- GCC_except_table852
- GCC_except_table887
- GCC_except_table897
- GCC_except_table927
- GCC_except_table952
- GCC_except_table954
- GCC_except_table962
- ___106-[TabDocument _webView:requestWebAuthenticationConditionalMediationRegistrationForUser:completionHandler:]_block_invoke
CStrings:
+ "@\"NSString\"16@?0@\"WKSecurityOrigin\"8"
```
