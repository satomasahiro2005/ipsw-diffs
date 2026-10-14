## HealthKit

> `/System/Library/Frameworks/HealthKit.framework/HealthKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42cd8c` | `0x42cc00` | **`-0x18c`** |
| `__TEXT.__cstring` | `0x38b52` | `0x38ba2` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x34720` | `0x34760` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x56948` | `0x56918` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x14d11` | `0x14cf1` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x4158` | `0x4140` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x3306c` | `0x33054` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x14270` | `0x14258` | **`-0x18`** |
| `__DATA_CONST.__const` | `0xfff0` | `0x10000` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x12558` | `0x12548` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x3170` | `0x316c` | **`-0x4`** |

### Other Changes

```diff

-7027.1.54.2.3
+7027.1.56.2.9

-  Functions: 30872
-  Symbols:   37055
-  CStrings:  9043
+  Functions: 30869
+  Symbols:   37051
+  CStrings:  9045
Symbols:
+ GCC_except_table203
+ _kHKMedicalIDFollowUpExtensionIdentifier
+ _kHKMedicalIDFollowUpReviewCompletedDateKey
- -[_HKFeatureFlags hearingAidOSEligibilityFallback]
- -[_HKFeatureFlags setHearingAidOSEligibilityFallback:]
- GCC_except_table124
- GCC_except_table204
- GCC_except_table209
- _OBJC_IVAR_$__HKFeatureFlags._hearingAidOSEligibilityFallback
- ___50-[_HKFeatureFlags hearingAidOSEligibilityFallback]_block_invoke
CStrings:
+ "ATVRemote1,5"
+ "com.apple.health.HealthAppSupport.MedicalIDFollowUpExtension"
+ "reviewFollowUpItemCompletedDate"
- "hearingAidOSEligibilityFallback"
```
