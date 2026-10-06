## WebSheet

> `/System/Library/PrivateFrameworks/WebSheet.framework/WebSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f10` | `0x858c` | **`+0x67c`** |
| `__TEXT.__cstring` | `0x1586` | `0x165b` | **`+0xd5`** |
| `__AUTH_CONST.__objc_const` | `0x14e8` | `0x15a0` | **`+0xb8`** |
| `__DATA_CONST.__const` | `0x2d0` | `0x348` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `0xb00` | `0xb60` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x230` | `0x280` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xc90` | `0xcd8` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xe48` | `0xe70` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2a0` | `0x2c8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x250` | `0x258` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xe8` | `0xec` | **`+0x4`** |

### Other Changes

```diff

-335.0.0.0.0
+337.0.0.0.0

-  Functions: 194
-  Symbols:   533
-  CStrings:  153
+  Functions: 205
+  Symbols:   555
+  CStrings:  157
Symbols:
+ -[WSSchemeApprovalCompletion .cxx_destruct]
+ -[WSSchemeApprovalCompletion completeWithApproval:]
+ -[WSSchemeApprovalCompletion dealloc]
+ -[WSSchemeApprovalCompletion initWithHandler:]
+ -[WSWebSheetView _openInBrowserTabForNavigationAction:webView:decisionHandler:]
+ -[WSWebSheetView _requestUserApprovalToOpenInApp:completion:]
+ GCC_except_table130
+ _OBJC_CLASS_$_WSSchemeApprovalCompletion
+ _OBJC_IVAR_$_WSSchemeApprovalCompletion._handler
+ _OBJC_METACLASS_$_WSSchemeApprovalCompletion
+ __OBJC_$_INSTANCE_METHODS_WSSchemeApprovalCompletion
+ __OBJC_$_INSTANCE_VARIABLES_WSSchemeApprovalCompletion
+ __OBJC_CLASS_RO_$_WSSchemeApprovalCompletion
+ __OBJC_METACLASS_RO_$_WSSchemeApprovalCompletion
+ ___61-[WSWebSheetView _requestUserApprovalToOpenInApp:completion:]_block_invoke
+ ___61-[WSWebSheetView _requestUserApprovalToOpenInApp:completion:]_block_invoke_2
+ ___61-[WSWebSheetView _requestUserApprovalToOpenInApp:completion:]_block_invoke_3
+ ___74-[WSWebSheetView webView:decidePolicyForNavigationAction:decisionHandler:]_block_invoke_3
+ ___79-[WSWebSheetView _openInBrowserTabForNavigationAction:webView:decisionHandler:]_block_invoke
+ ___79-[WSWebSheetView _openInBrowserTabForNavigationAction:webView:decisionHandler:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40bs_e8_v12?0B8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e8_v12?0B8ls48l8s32l8s40l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e8_v12?0B8ls64l8s32l8s40l8s48l8s56l8
+ _objc_retainBlock
+ _objc_retain_x28
- -[WSWebSheetView isUserAprroved:]
- GCC_except_table119
- _CFUserNotificationDisplayAlert
CStrings:
+ "openURL approval alert went away without a choice, treating as not approved"
+ "presented UIAlertController asking for approval to open in \"%@\""
+ "unable to prompt for openURL approval, treating as not approved"
+ "v12@?0B8"
```
