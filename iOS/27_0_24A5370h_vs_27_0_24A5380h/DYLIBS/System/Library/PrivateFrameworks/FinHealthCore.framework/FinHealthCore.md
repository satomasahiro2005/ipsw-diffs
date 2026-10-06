## FinHealthCore

> `/System/Library/PrivateFrameworks/FinHealthCore.framework/FinHealthCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf508c` | `0xf781c` | **`+0x2790`** |
| `__AUTH.__objc_data` | `0xa38` | `0x1b0` | **`-0x888`** |
| `__DATA_DIRTY.__objc_data` | `0xe00` | `0x1688` | **`+0x888`** |
| `__DATA_DIRTY.__data` | `0x2a0` | `0xaf0` | **`+0x850`** |
| `__AUTH.__data` | `0xc28` | `0x4d8` | **`-0x750`** |
| `__DATA_DIRTY.__bss` | `0x290` | `0x440` | **`+0x1b0`** |
| `__DATA.__bss` | `0x3c10` | `0x3b20` | **`-0xf0`** |
| `__DATA.__data` | `0xe50` | `0xd70` | **`-0xe0`** |
| `__AUTH_CONST.__const` | `0x2b10` | `0x2bb0` | **`+0xa0`** |
| `__TEXT.__const` | `0x3c48` | `0x3ce8` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x3ece` | `0x3f6e` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0xe94` | `0xeec` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0x6820` | `0x6860` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2a20` | `0x2a60` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0xc23` | `0xc53` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1540` | `0x1568` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x1a04` | `0x1a2a` | **`+0x26`** |
| `__TEXT.__constg_swiftt` | `0xf7c` | `0xfa0` | **`+0x24`** |
| `__DATA_CONST.__const` | `0x1aa0` | `0x1ab8` | **`+0x18`** |
| `__TEXT.__cstring` | `0xa31a` | `0xa32a` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xae0` | `0xae8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x20f8` | `0x2100` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x35d4` | `0x35dc` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1d8` | `0x1dc` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x110` | `0x114` | **`+0x4`** |

### Other Changes

```diff

-1.9.1.24.0
+1.9.1.27.0

-  Functions: 3383
-  Symbols:   3429
-  CStrings:  1270
+  Functions: 3420
+  Symbols:   3436
+  CStrings:  1275
Symbols:
+ -[FHDatabaseManager _executeFeatureQuery:argument:aggregatedFeatures:]
+ GCC_except_table108
+ GCC_except_table115
+ GCC_except_table123
+ GCC_except_table155
+ GCC_except_table157
+ GCC_except_table163
+ GCC_except_table165
+ GCC_except_table167
+ GCC_except_table169
+ GCC_except_table175
+ GCC_except_table181
+ GCC_except_table183
+ GCC_except_table185
+ GCC_except_table197
+ GCC_except_table203
+ GCC_except_table208
+ GCC_except_table210
+ _FHBankHolidaysDirectoryName
+ _FHBankHolidaysRolloutFactorName
+ _symbolic Sd8previous_Sd7currentt
+ _symbolic _____ 13FinHealthCore14AmountBehaviorO
+ _symbolic _____Sg s5Int16V
- GCC_except_table107
- GCC_except_table122
- GCC_except_table154
- GCC_except_table156
- GCC_except_table162
- GCC_except_table164
- GCC_except_table166
- GCC_except_table168
- GCC_except_table174
- GCC_except_table180
- GCC_except_table182
- GCC_except_table184
- GCC_except_table195
- GCC_except_table202
- GCC_except_table207
- GCC_except_table209
CStrings:
+ "BankHolidayProvider: %s.json not found in bundle at FeaturesResources/%s/"
+ "BankHolidayProvider: Loading %s holidays from Trial"
+ "BankHolidayProvider: Loading %s holidays from bundle"
+ "BankHolidayProvider: Trial %s/%s.json missing"
+ "FH_BANK_HOLIDAYS_ROLLOUT"
+ "FeaturesResources/"
+ "bank_holidays"
+ "select t_identifier, '%@,%lu,%lu' FHSmartFeatureAggregateType from transactions where m_displayname == %%@"
- "BankHolidayProvider: %s.json not found in bundle at FeaturesResources/bank_holidays/"
- "FeaturesResources/bank_holidays/"
- "select t_identifier, '%@,%lu,%lu' FHSmartFeatureAggregateType from transactions where m_displayname == \"%@\""
```
