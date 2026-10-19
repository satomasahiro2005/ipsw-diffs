## HealthKit

> `/System/Library/Frameworks/HealthKit.framework/HealthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42cc00` | `0x42cd68` | **`+0x168`** |
| `__AUTH_CONST.__objc_const` | `0x56918` | `0x56948` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x14cf1` | `0x14d11` | **`+0x20`** |
| `__TEXT.__cstring` | `0x38ba2` | `0x38bc2` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x4140` | `0x415c` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x33054` | `0x3306c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x14258` | `0x14270` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x12548` | `0x12558` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x316c` | `0x3170` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 30869
-  Symbols:   37051
-  CStrings:  9045
+  Functions: 30872
+  Symbols:   37057
+  CStrings:  9046
Symbols:
+ -[_HKFeatureFlags hearingAidOSEligibilityFallback]
+ -[_HKFeatureFlags setHearingAidOSEligibilityFallback:]
+ GCC_except_table124
+ GCC_except_table204
+ GCC_except_table209
+ _OBJC_IVAR_$__HKFeatureFlags._hearingAidOSEligibilityFallback
+ ___50-[_HKFeatureFlags hearingAidOSEligibilityFallback]_block_invoke
- GCC_except_table203
CStrings:
+ "hearingAidOSEligibilityFallback"
```
