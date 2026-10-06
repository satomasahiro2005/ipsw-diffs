## CellularPlanManager

> `/System/Library/PrivateFrameworks/CellularPlanManager.framework/CellularPlanManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1296c` | `0x121f8` | **`-0x774`** |
| `__DATA_CONST.__const` | `0xd88` | `0xcc0` | **`-0xc8`** |
| `__TEXT.__oslogstring` | `0x5fc` | `0x573` | **`-0x89`** |
| `__AUTH_CONST.__const` | `0x440` | `0x3e0` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x860` | `0x838` | **`-0x28`** |
| `__TEXT.__cstring` | `0x2284` | `0x226c` | **`-0x18`** |

### Other Changes

```diff

-13487.3.0.0.0
+13487.6.0.0.0

-  Functions: 695
-  Symbols:   1120
-  CStrings:  326
+  Functions: 683
+  Symbols:   1107
+  CStrings:  320
Symbols:
+ GCC_except_table134
+ GCC_except_table143
+ GCC_except_table149
+ GCC_except_table173
+ GCC_except_table182
+ GCC_except_table197
+ GCC_except_table206
+ GCC_except_table212
+ GCC_except_table215
+ GCC_except_table389
+ GCC_except_table404
- GCC_except_table155
- GCC_except_table161
- GCC_except_table170
- GCC_except_table185
- GCC_except_table194
- GCC_except_table218
- GCC_except_table221
- GCC_except_table227
- GCC_except_table236
- GCC_except_table413
- GCC_except_table416
- ___39-[CTCellularPlanManager setMcc:andMnc:]_block_invoke
- ___39-[CTCellularPlanManager setMcc:andMnc:]_block_invoke_2
- ___40-[CTCellularPlanManager mccMncOverride:]_block_invoke_3
- ___50-[CTCellularPlanManager setLatitude:andLongitude:]_block_invoke
- ___50-[CTCellularPlanManager setLatitude:andLongitude:]_block_invoke_2
- ___51-[CTCellularPlanManager latitudeLongitudeOverride:]_block_invoke_3
- ___55-[CTCellularPlanManager showUiIgnoringActivationFlags:]_block_invoke
- ___55-[CTCellularPlanManager showUiIgnoringActivationFlags:]_block_invoke_2
- ___block_descriptor_40_e8_32b_e11_v24?0d8d16ls32l8
- ___block_descriptor_40_e8_32b_e11_v24?0q8q16ls32l8
- ___block_descriptor_56_e8_32b_e5_v8?0ls32l8
- ___block_descriptor_56_e8_32o40o48o_e5_v8?0ls32l8s40l8s48l8
- ___block_descriptor_56_e8_32o_e5_v8?0ls32l8
CStrings:
- "unable to get mcc/mnc overrides %@"
- "unable to set lat/long %@"
- "unable to set mcc/mnc %@"
- "unable to set show Ui ignoring activation flags %@"
- "v24@?0d8d16"
- "v24@?0q8q16"
```
