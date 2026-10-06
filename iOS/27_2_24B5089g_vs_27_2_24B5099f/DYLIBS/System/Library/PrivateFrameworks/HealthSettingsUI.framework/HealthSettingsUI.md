## HealthSettingsUI

> `/System/Library/PrivateFrameworks/HealthSettingsUI.framework/HealthSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e62c` | `0x1ee10` | **`+0x7e4`** |
| `__TEXT.__eh_frame` | `0xb34` | `0xc14` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0x800` | `0x8c0` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x308` | `0x398` | **`+0x90`** |
| `__TEXT.__const` | `0x8c8` | `0x938` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x328` | `0x378` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x890` | `0x8d8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x94c` | `0x98c` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x496` | `0x4d6` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x27d` | `0x23d` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0x374` | `0x3b0` | **`+0x3c`** |
| `__AUTH.__data` | `0x210` | `0x240` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x380` | `0x3a8` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xb18` | `0xb38` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0xe90` | `0xe70` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x568` | `0x588` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x5b2` | `0x5ce` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x748` | `0x740` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift5_fieldmd` | `0x1e0` | `0x1e4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

+  - /System/Library/PrivateFrameworks/HealthHistory.framework/HealthHistory

-  Functions: 674
-  Symbols:   657
-  CStrings:  90
+  Functions: 688
+  Symbols:   670
+  CStrings:  92
Symbols:
+ -[HKHealthSettingsController _finishFetchingHealthRecordsData:completion:]
+ GCC_except_table30
+ GCC_except_table40
+ _OBJC_CLASS_$_HKActionSuggestionAvailability
+ _OBJC_CLASS_$__TtC16HealthSettingsUI34ManuallyEnteredRecordsAvailability
+ _OBJC_METACLASS_$_HKActionSuggestionAvailability
+ _OBJC_METACLASS_$__TtC16HealthSettingsUI34ManuallyEnteredRecordsAvailability
+ __CLASS_METHODS_HKActionSuggestionAvailability
+ __CLASS_METHODS__TtC16HealthSettingsUI34ManuallyEnteredRecordsAvailability
+ __DATA_HKActionSuggestionAvailability
+ __DATA__TtC16HealthSettingsUI34ManuallyEnteredRecordsAvailability
+ __INSTANCE_METHODS_HKActionSuggestionAvailability
+ __INSTANCE_METHODS__TtC16HealthSettingsUI34ManuallyEnteredRecordsAvailability
+ __METACLASS_DATA_HKActionSuggestionAvailability
+ __METACLASS_DATA__TtC16HealthSettingsUI34ManuallyEnteredRecordsAvailability
+ ___74-[HKHealthSettingsController _finishFetchingHealthRecordsData:completion:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e8_v16?0q8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40bs_e5_v8?0ls32l8s40l8
+ _symbolic _____ 16HealthSettingsUI32ActionSuggestionAvailabilityObjCC
+ _symbolic _____ 16HealthSettingsUI34ManuallyEnteredRecordsAvailabilityC
+ _symbolic _____ So23HKFailableBooleanResultV
+ _symbolic _____Ieghy_ So23HKFailableBooleanResultV
+ _symbolic _____IeyBhy_ So23HKFailableBooleanResultV
+ _symbolic _____XMT 16HealthSettingsUI34ManuallyEnteredRecordsAvailabilityC
+ _symbolic _____y_____G 7SwiftUI12ScaledMetricV 12CoreGraphics7CGFloatV
- GCC_except_table28
- GCC_except_table36
- _OBJC_CLASS_$__TtC16HealthSettingsUI35PersonalizedSuggestionsAvailability
- _OBJC_METACLASS_$__TtC16HealthSettingsUI35PersonalizedSuggestionsAvailability
- __DATA__TtC16HealthSettingsUI35PersonalizedSuggestionsAvailability
- __INSTANCE_METHODS__TtC16HealthSettingsUI35PersonalizedSuggestionsAvailability
- __IVARS__TtC16HealthSettingsUI35PersonalizedSuggestionsAvailability
- __METACLASS_DATA__TtC16HealthSettingsUI35PersonalizedSuggestionsAvailability
- ___block_descriptor_49_e8_32s40bs_e5_v8?0ls32l8s40l8
- _symbolic SbSo13HKHealthStoreCYaYbc
- _symbolic SbyYbc
- _symbolic _____ 16HealthSettingsUI35PersonalizedSuggestionsAvailabilityC
CStrings:
+ "Failed to check for manually entered records: %{public}@"
+ "v16@?0q8"
```
