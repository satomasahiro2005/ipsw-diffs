## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__eh_frame` | `0x20584` | `0x2052c` | **`-0x58`** |
| `__TEXT.__objc_methlist` | `0x2581c` | `0x25864` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x423a8` | `0x423d8` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x10820` | `0x10848` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x3d480` | `0x3d460` | **`-0x20`** |
| `__TEXT.__cstring` | `0x313c6` | `0x313b1` | **`-0x15`** |
| `__DATA.__data` | `0x93fc` | `0x93ec` | **`-0x10`** |
| `__TEXT.__text` | `0x8c53e0` | `0x8c53d0` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x1b24` | `0x1b1c` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1a70` | `0x1a74` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xde0` | `0xddc` | **`-0x4`** |

### Other Changes

```diff

-10.1.17.0.0
+10.1.18.2.1

-  Functions: 36161
-  Symbols:   27439
-  CStrings:  9886
+  Functions: 36162
+  Symbols:   27445
+  CStrings:  9885
Symbols:
+ +[AMSPurchaseRequestEncoder shouldCompressRequestBodyWithCallerDisabled:bag:]
+ -[AMSPurchaseRequestEncoder requestByEncodingRequestAndReturnSigningErrors:parameters:]
+ -[AMSPurchaseRequestEncoder shouldCompressRequestBodyForRequest:]
+ -[AMSURLRequestEncoder shouldCompressRequestBodyForRequest:]
+ -[AMSURLRequestProperties disableRequestBodyCompression]
+ -[AMSURLRequestProperties setDisableRequestBodyCompression:]
+ _OBJC_CLASS_$_DIDocUploadSession$lazyGOT$loadHelper_x8$for$_OUTLINED_FUNCTION_56+8
+ _OBJC_CLASS_$_DIUploadAsset$lazyGOT$loadHelper_x2$for$_OUTLINED_FUNCTION_39+12
+ _OBJC_IVAR_$_AMSURLRequestProperties._disableRequestBodyCompression
+ ___block_descriptor_56_e8_32s40s48s_e44_"AMSPromise"24?0"AMSBoolean"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_74_e8_32s40s48s56s64bs_e20_v20?0B8"NSError"12ls32l8s40l8s48l8s64l8s56l8
- _OBJC_CLASS_$_DIDocUploadSession$lazyGOT$loadHelper_x8$for$_OUTLINED_FUNCTION_65+8
- _OBJC_CLASS_$_DIUploadAsset$lazyGOT$loadHelper_x2$for$_OUTLINED_FUNCTION_42+12
- ___54-[AMSPurchaseRequestEncoder initWithPurchaseInfo:bag:]_block_invoke
- ___block_descriptor_40_e8_32s_e20_v16?0"AMSBoolean"8ls32l8
- ___block_descriptor_73_e8_32s40s48s56s64bs_e20_v20?0B8"NSError"12ls32l8s40l8s48l8s64l8s56l8
CStrings:
- "v16@?0@\"AMSBoolean\"8"
```
