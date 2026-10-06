## libTelephonyUtilDynamic.dylib

> `/usr/lib/libTelephonyUtilDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x856b8` | `0x857e0` | **`+0x128`** |
| `__AUTH_CONST.__const` | `0x6d80` | `0x6da8` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x8b38` | `0x8b58` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3673` | `0x368f` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0x44c8` | `0x44d8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x368` | `0x370` | **`+0x8`** |

### Other Changes

```diff

-6562.0.0.0.0
+6565.0.0.0.0

-  Functions: 3363
-  Symbols:   5236
-  CStrings:  729
+  Functions: 3366
+  Symbols:   5241
+  CStrings:  730
Symbols:
+ GCC_except_table107
+ GCC_except_table114
+ GCC_except_table126
+ GCC_except_table139
+ GCC_except_table148
+ __ZN15MockHttpRequest27setCompanionProxyPreferenceEb
+ __ZN3ctu4Http16HttpSession_impl27setCompanionProxyPreferenceEb
+ __ZN3ctu4Http18HttpSessionRequest27setCompanionProxyPreferenceEb
- GCC_except_table120
- GCC_except_table124
- GCC_except_table151
Functions:
+ __ZN3ctu4Http16HttpSession_impl27setCompanionProxyPreferenceEb
~ ____ZN3ctu4Http18HttpSessionRequest5startENSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE_block_invoke : 2980 -> 3020
+ __ZN3ctu4Http18HttpSessionRequest27setCompanionProxyPreferenceEb
~ __ZN15MockHttpRequestC2EN3ctu4Http11RequestTypeEONSt3__112basic_stringIcNS3_11char_traitsIcEENS3_9allocatorIcEEEEONS3_3mapIS9_S9_NS1_29case_insensitive_key_comparerENS7_INS3_4pairIKS9_S9_EEEEEE : 1044 -> 1068
+ __ZN15MockHttpRequest27setCompanionProxyPreferenceEb
~ __ZN15MockHttpRequestD2Ev : 696 -> 716
CStrings:
+ "setCompanionProxyPreference"
```
