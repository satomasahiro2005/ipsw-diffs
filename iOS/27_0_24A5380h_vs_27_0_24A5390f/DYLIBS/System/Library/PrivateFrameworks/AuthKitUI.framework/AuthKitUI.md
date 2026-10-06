## AuthKitUI

> `/System/Library/PrivateFrameworks/AuthKitUI.framework/AuthKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc3dc` | `0xddc04` | **`+0x1828`** |
| `__DATA.__bss` | `0x1998` | `0x1ca8` | **`+0x310`** |
| `__TEXT.__const` | `0x12e4` | `0x1514` | **`+0x230`** |
| `__AUTH_CONST.__const` | `0x758` | `0x898` | **`+0x140`** |
| `__AUTH.__objc_data` | `0x2320` | `0x23d0` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0xd1a` | `0xdc2` | **`+0xa8`** |
| `__AUTH_CONST.__auth_got` | `0xd28` | `0xdc0` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x37c` | `0x3f4` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0x18670` | `0x186d8` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x1c20` | `0x1c88` | **`+0x68`** |
| `__DATA.__data` | `0x1fb8` | `0x2018` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x8814` | `0x886c` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x220` | `0x274` | **`+0x54`** |
| `__TEXT.__oslogstring` | `0x58f9` | `0x5949` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x5fc0` | `0x6008` | **`+0x48`** |
| `__TEXT.__swift5_assocty` | `0x198` | `0x1c8` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1aa` | `0x1da` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x88` | `0xb4` | **`+0x2c`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x78` | **`+0x28`** |
| `__AUTH.__data` | `0x250` | `0x270` | **`+0x20`** |
| `__AUTH_CONST.__cfstring` | `0x50c0` | `0x50e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x57bd` | `0x57dd` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0xbc` | `0xd4` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xeb0` | `0xec0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x40` | `0x4c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x764` | `0x768` | **`+0x4`** |

### Other Changes

```diff

-554.0.0.0.0
+555.0.0.0.0

-  Functions: 3324
-  Symbols:   5776
-  CStrings:  1309
+  Functions: 3368
+  Symbols:   5815
+  CStrings:  1311
Symbols:
+ +[AKIcon monogramWithAppName:size:]
+ -[AKAuthorizationInputPaneViewController _handleRequestedAuthorization:error:completionHandler:]
+ -[AKIcon _initWithSynthesizedImage:]
+ GCC_except_table169
+ _AKBasicLoginShouldEnablePasswordAutoFill
+ _AKBasicLoginShouldEnablePasswordAutoFill.onceToken
+ _AKBasicLoginShouldEnablePasswordAutoFill.shouldEnable
+ _OBJC_CLASS_$_AKMonogramRenderer
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_IVAR_$_AKIcon._synthesizedImage
+ _OBJC_METACLASS_$_AKMonogramRenderer
+ _UIFontDescriptorSystemDesignRounded
+ __CLASS_METHODS_AKMonogramRenderer
+ __DATA_AKMonogramRenderer
+ __INSTANCE_METHODS_AKMonogramRenderer
+ __METACLASS_DATA_AKMonogramRenderer
+ ___96-[AKAuthorizationInputPaneViewController _handleRequestedAuthorization:error:completionHandler:]_block_invoke
+ ___96-[AKAuthorizationInputPaneViewController _handleRequestedAuthorization:error:completionHandler:]_block_invoke_2
+ ___AKBasicLoginShouldEnablePasswordAutoFill_block_invoke
+ _associated conformance So21NSAttributedStringKeyaSHSCSQ
+ _associated conformance So21NSAttributedStringKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So21NSAttributedStringKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _objc_retain_x1
+ _objc_retain_x24
+ _objc_retain_x27
+ _objc_retain_x28
+ _swift_initStackObject
+ _swift_isEscapingClosureAtFileLocation
+ _swift_retain_x2
+ _swift_retain_x22
+ _swift_setDeallocating
+ _symbolic $ss21_ObjectiveCBridgeableP
+ _symbolic So30UIGraphicsImageRendererContextCIgg_
+ _symbolic So8NSStringC
+ _symbolic _____ 9AuthKitUI18AKMonogramRendererC
+ _symbolic _____ So21NSAttributedStringKeya
+ _symbolic _____ So6CGSizeV
+ _symbolic ______ypt So21NSAttributedStringKeya
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC So21NSAttributedStringKeya
+ _symbolic _____y_____ypG s18_DictionaryStorageC So21NSAttributedStringKeya
+ _type_layout_string So21NSAttributedStringKeya
+ _type_layout_string So6CGSizeV
- GCC_except_table168
- ___97-[AKAuthorizationInputPaneViewController _performAuthorizationWithRawPassword:completionHandler:]_block_invoke_2
- ___97-[AKAuthorizationInputPaneViewController _performAuthorizationWithRawPassword:completionHandler:]_block_invoke_3
CStrings:
+ "6"
+ "ServicesPaymentAngel"
+ "performPasswordAuthenticationForPaneViewController: allocated password VC"
- "5"
```
