## PassKitUIFoundation

> `/System/Library/PrivateFrameworks/PassKitUIFoundation.framework/PassKitUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x265c4` | `0x266f4` | **`+0x130`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bf0` | `0x1c10` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x5c8` | `0x5e0` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x4690` | `0x46a0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1d0c` | `0x1d1c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa08` | `0xa18` | **`+0x10`** |

### Other Changes

```diff

-1689.3.0.0.0
+1695.1.2.0.0

-  Functions: 825
-  Symbols:   1923
+  Functions: 827
+  Symbols:   1928
Symbols:
+ -[PKAuthenticatorEvaluationContext successfulAuthenticationMethod]
+ GCC_except_table163
+ GCC_except_table171
+ GCC_except_table175
+ GCC_except_table183
+ GCC_except_table185
+ _PKAnalyticsReportEventTypeSuccessfulFaceID
+ _PKAnalyticsReportEventTypeSuccessfulPasscode
+ _PKAnalyticsReportEventTypeSuccessfulTouchID
+ _PKMapsDisplayNameForMerchant
- GCC_except_table162
- GCC_except_table170
- GCC_except_table174
- GCC_except_table182
- GCC_except_table184
Functions:
+ _PKMapsDisplayNameForMerchant
+ -[PKAuthenticatorEvaluationContext successfulAuthenticationMethod]
~ ___46-[PKAuthenticator _evaluateEvaluationContext:]_block_invoke : 700 -> 732
```
