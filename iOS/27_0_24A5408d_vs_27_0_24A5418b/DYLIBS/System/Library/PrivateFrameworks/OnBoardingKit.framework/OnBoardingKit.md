## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48b18` | `0x48988` | **`-0x190`** |
| `__AUTH_CONST.__cfstring` | `0x20e0` | `0x2080` | **`-0x60`** |
| `__TEXT.__cstring` | `0x1969` | `0x1939` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x4a8` | `0x488` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x61d4` | `0x61bc` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3fc0` | `0x3fb0` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x1361` | `0x136c` | **`+0xb`** |
| `__TEXT.__unwind_info` | `0x1008` | `0x1000` | **`-0x8`** |

### Other Changes

```diff

-3977.0.22.0.0
+3977.0.23.0.0

-  Functions: 1876
-  Symbols:   3454
-  CStrings:  380
+  Functions: 1874
+  Symbols:   3448
+  CStrings:  376
Symbols:
+ GCC_except_table13
- -[OBCapabilities _eligibilityContextHasCountryPolicyChina:]
- -[OBCapabilities _eligibilityCountryPolicyStringIsChina:]
- GCC_except_table15
- _xpc_array_get_count
- _xpc_array_get_string
- _xpc_dictionary_get_array
- _xpc_dictionary_get_string
CStrings:
+ "Failed to get Bembidion (China privacy) eligibility with error %d"
- "CHN"
- "CN"
- "Failed to get eligibility for greymatter with error %d"
- "OS_ELIGIBILITY_CONTEXT_COUNTRY_POLICY"
- "_"
```
