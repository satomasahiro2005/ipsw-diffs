## PassKitUIFoundation

> `/System/Library/PrivateFrameworks/PassKitUIFoundation.framework/PassKitUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26110` | `0x265c4` | **`+0x4b4`** |
| `__AUTH.__objc_data` | `0x8c0` | `0x4b0` | **`-0x410`** |
| `__DATA_DIRTY.__objc_data` | `0x140` | `0x550` | **`+0x410`** |
| `__AUTH_CONST.__cfstring` | `0xf80` | `0x1000` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x578` | `0x5c8` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x4650` | `0x4690` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1d24` | `0x1d0c` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x9f0` | `0xa08` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x7a8` | `0x794` | **`-0x14`** |
| `__TEXT.__cstring` | `0xe87` | `0xe9a` | **`+0x13`** |
| `__DATA.__bss` | `0xa5` | `0x95` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x18` | `0x28` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x650` | `0x658` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x490` | `0x498` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bf8` | `0x1bf0` | **`-0x8`** |

### Other Changes

```diff

-1682.1.0.0.0
+1686.3.0.0.0

-  Functions: 823
-  Symbols:   1906
-  CStrings:  251
+  Functions: 825
+  Symbols:   1923
+  CStrings:  254
Symbols:
+ -[PKAuthenticatorEvaluationContext populateAnalyticsEventForAuthentication:]
+ GCC_except_table162
+ GCC_except_table170
+ GCC_except_table174
+ GCC_except_table182
+ GCC_except_table184
+ GCC_except_table21
+ GCC_except_table28
+ GCC_except_table29
+ GCC_except_table34
+ GCC_except_table39
+ GCC_except_table8
+ GCC_except_table9
+ _OBJC_CLASS_$_PKPassLibrary
+ _OBJC_IVAR_$_PKFingerprintGlyphView._resolvedPrimaryColor
+ _OBJC_IVAR_$_PKFingerprintGlyphView._resolvedSecondaryColor
+ _PKAnalyticsReportNumberOfAvailableCardsKey
+ _PKAnalyticsReportPassIssuerNameKey
+ _PKAnalyticsReportPassProductSubtypeKey
+ _PKAnalyticsReportPassTokenSubTypeKey
+ _PKAnalyticsReportPassTokenTypeKey
+ _PKPaymentRequestClientAnalyticsParametersIssuerKey
+ _PKPaymentRequestClientAnalyticsParametersProductSubTypeKey
+ _PKPaymentRequestClientAnalyticsParametersTokenSubTypeKey
+ _PKPaymentRequestClientAnalyticsParametersTokenTypeKey
+ ___53-[PKFingerprintGlyphView _applyPrimaryColorAnimated:]_block_invoke
+ ___55-[PKFingerprintGlyphView _applySecondaryColorAnimated:]_block_invoke
+ _objc_retain_x9
- GCC_except_table161
- GCC_except_table169
- GCC_except_table173
- GCC_except_table181
- GCC_except_table183
- GCC_except_table24
- GCC_except_table27
- GCC_except_table30
- GCC_except_table37
- GCC_except_table49
- ___61-[PKFingerprintGlyphView _applyColor:toShapeLayers:animated:]_block_invoke
CStrings:
+ "0"
+ "2 or more"
+ "access"
+ "\xf0q"
- "\xf0Q"
```
