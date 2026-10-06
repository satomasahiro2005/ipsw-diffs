## HealthUI

> `/System/Library/PrivateFrameworks/HealthUI.framework/HealthUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44b090` | `0x44e804` | **`+0x3774`** |
| `__TEXT.__eh_frame` | `0x3388` | `0x34e8` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0xf368` | `0xf420` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x2330f` | `0x233af` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x7455` | `0x74e5` | **`+0x90`** |
| `__DATA.__bss` | `0x70b0` | `0x7030` | **`-0x80`** |
| `__TEXT.__swift5_capture` | `0x14a4` | `0x1510` | **`+0x6c`** |
| `__AUTH_CONST.__const` | `0x8bf0` | `0x8c58` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x3b3c4` | `0x3b41c` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x66280` | `0x662d0` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x30d8` | `0x3120` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x18aa0` | `0x18ae0` | **`+0x40`** |
| `__TEXT.__const` | `0x8db4` | `0x8d74` | **`-0x40`** |
| `__DATA.__data` | `0x82d8` | `0x8308` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x3516` | `0x3542` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x7990` | `0x79b8` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x3100` | `0x30d8` | **`-0x28`** |
| `__TEXT.__constg_swiftt` | `0x4ec8` | `0x4eac` | **`-0x1c`** |
| `__TEXT.__swift_as_cont` | `0x158` | `0x164` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x90` | `0x9c` | **`+0xc`** |
| `__AUTH.__objc_data` | `0x183e0` | `0x183e8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3850` | `0x3858` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x84` | `0x8c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x405c` | `0x4060` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x39c` | `0x398` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x3f4` | `0x3f0` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-7027.0.64.0.0
+7027.0.67.2.1

-  Functions: 26351
-  Symbols:   35635
-  CStrings:  5314
+  Functions: 26382
+  Symbols:   35651
+  CStrings:  5320
Symbols:
+ +[HKSourceListDataSource fetchUsageDescriptionsForSource:completion:]
+ -[HKElectrocardiogramInfoView setBodyPreferredMaxLayoutWidth:]
+ -[HKElectrocardiogramMetadataView infoView]
+ -[HKElectrocardiogramMetadataView setBodyPreferredMaxLayoutWidth:]
+ -[HKElectrocardiogramMetadataView setInfoView:]
+ -[HKInteractiveChartAnnotationView _contentInkOverflow]
+ -[HKInteractiveChartAnnotationViewKeyValueLabel _keyToValueOverlap]
+ -[HKUnitPreferenceController _safeObjectTypeForDisplayType:]
+ GCC_except_table57
+ GCC_except_table89
+ _CTLineCreateWithAttributedString
+ _CTLineGetBoundsWithOptions
+ _OBJC_IVAR_$_HKElectrocardiogramMetadataView._infoView
+ __UITableViewDefaultSectionCornerRadiusForTraitCollection
+ ___69+[HKSourceListDataSource fetchUsageDescriptionsForSource:completion:]_block_invoke
+ ___69+[HKSourceListDataSource fetchUsageDescriptionsForSource:completion:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40bs_e27_v16?0"HKSourceDataModel"8ls32l8s40l8
+ ___swift_closure_destructor.113Tm
+ ___swift_closure_destructor.66Tm
+ ___swift_closure_destructor.73Tm
+ _symbolic ScCySSSg_A2At_____G s5NeverO
+ _symbolic So11UIStackViewC
+ _symbolic ytSgIeAgHr_
- GCC_except_table88
- ___swift_closure_destructor.67Tm
- ___swift_closure_destructor.74Tm
- _displayRangeForDisplayType:.__displayRanges
- _displayRangeForDisplayType:.onceToken
- _symbolic _____ 8HealthUI20GlyphTightTextLayoutC0E7MetricsV
- _type_layout_string 8HealthUI20GlyphTightTextLayoutC0E7MetricsV
CStrings:
+ "ActionButtonsCell"
+ "ENABLE_ALL_%ld_CATEGORIES"
+ "HealthUI/GlyphTightTextLayout.swift"
+ "Inverted histogram dates: start=%{public}@ end=%{public}@"
+ "No HealthKit usage descriptions resolved for source %@; App Explanation will be empty"
+ "refreshUsageDescriptionsIfNeeded()"
```
