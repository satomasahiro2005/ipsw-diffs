## CoreCDPUI

> `/System/Library/PrivateFrameworks/CoreCDPUI.framework/CoreCDPUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8bf3c` | `0x8c030` | **`+0xf4`** |
| `__AUTH.__data` | `0x1620` | `0x1648` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x4a82` | `0x4aa2` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xc14` | `0xc28` | **`+0x14`** |
| `__DATA.__data` | `0x2928` | `0x2918` | **`-0x10`** |
| `__TEXT.__cstring` | `0x5d32` | `0x5d42` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x4a6c` | `0x4a7c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2158` | `0x2168` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3380` | `0x3388` | **`+0x8`** |

### Other Changes

```diff

-442.0.0.0.0
+444.0.0.0.0

-  Functions: 3322
-  Symbols:   3728
-  CStrings:  936
+  Functions: 3323
+  Symbols:   3729
+  CStrings:  937
Symbols:
+ -[CDPUIController _executeCustodianRecoveryEscapeActionWithSupportedEscapeOfferMask:replacingViewController:]
+ -[CDPUIController _startAAUICustodianRecoveryFlowWithSupportedEscapeOfferMask:replacingViewController:]
+ GCC_except_table166
+ GCC_except_table171
+ GCC_except_table173
+ GCC_except_table175
+ GCC_except_table180
+ GCC_except_table183
+ GCC_except_table187
+ GCC_except_table193
+ GCC_except_table196
+ GCC_except_table198
+ GCC_except_table200
+ GCC_except_table203
+ GCC_except_table208
+ GCC_except_table213
+ GCC_except_table218
+ GCC_except_table220
+ GCC_except_table226
+ GCC_except_table237
+ GCC_except_table241
+ GCC_except_table244
+ GCC_except_table246
+ GCC_except_table252
+ GCC_except_table261
+ GCC_except_table271
+ GCC_except_table301
+ GCC_except_table310
+ GCC_except_table88
+ ___103-[CDPUIController _startAAUICustodianRecoveryFlowWithSupportedEscapeOfferMask:replacingViewController:]_block_invoke
- -[CDPUIController _startAAUICustodianRecoveryFlowWithSupportedEscapeOfferMask:]
- GCC_except_table165
- GCC_except_table169
- GCC_except_table172
- GCC_except_table174
- GCC_except_table179
- GCC_except_table181
- GCC_except_table186
- GCC_except_table192
- GCC_except_table195
- GCC_except_table197
- GCC_except_table199
- GCC_except_table202
- GCC_except_table207
- GCC_except_table212
- GCC_except_table217
- GCC_except_table219
- GCC_except_table225
- GCC_except_table236
- GCC_except_table240
- GCC_except_table243
- GCC_except_table245
- GCC_except_table251
- GCC_except_table260
- GCC_except_table270
- GCC_except_table300
- GCC_except_table309
- ___44-[CDPUIController performCustodianRecovery:]_block_invoke_3
- ___79-[CDPUIController _startAAUICustodianRecoveryFlowWithSupportedEscapeOfferMask:]_block_invoke
CStrings:
+ "-[CDPUIController _executeCustodianRecoveryEscapeActionWithSupportedEscapeOfferMask:replacingViewController:]"
+ "User elected to start Custodian Flow"
- "-[CDPUIController _executeCustodianRecoveryEscapeActionWithSupportedEscapeOfferMask:]"
```
