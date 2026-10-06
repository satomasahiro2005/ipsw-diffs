## PerfPowerMetricMonitor

> `/System/Library/PrivateFrameworks/PerfPowerMetricMonitor.framework/PerfPowerMetricMonitor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19d90` | `0x1a974` | **`+0xbe4`** |
| `__TEXT.__oslogstring` | `0x1c3b` | `0x1e7f` | **`+0x244`** |
| `__AUTH_CONST.__objc_const` | `0x2898` | `0x2a48` | **`+0x1b0`** |
| `__TEXT.__cstring` | `0x1308` | `0x1444` | **`+0x13c`** |
| `__AUTH_CONST.__cfstring` | `0x1640` | `0x1740` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x187c` | `0x1954` | **`+0xd8`** |
| `__DATA_CONST.__objc_selrefs` | `0xf40` | `0xfd0` | **`+0x90`** |
| `__DATA_CONST.__objc_arraydata` | `0x2e8` | `0x328` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x280` | `0x2a4` | **`+0x24`** |
| `__TEXT.__gcc_except_tab` | `0x998` | `0x9a8` | **`+0x10`** |
| `__TEXT.__const` | `0xf8` | `0x100` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 674
-  Symbols:   1095
-  CStrings:  334
+  Functions: 693
+  Symbols:   1122
+  CStrings:  343
Symbols:
+ -[PPSMetricCollection brightnessX]
+ -[PPSMetricCollection displayAPLX]
+ -[PPSMetricCollection displayCostX]
+ -[PPSMetricCollection displayEnergyX]
+ -[PPSMetricCollection displayFPSX]
+ -[PPSMetricCollection displayPowerX]
+ -[PPSMetricCollection scanoutFPSX]
+ -[PPSMetricCollection setBrightnessX:]
+ -[PPSMetricCollection setDisplayAPLX:]
+ -[PPSMetricCollection setDisplayCostX:]
+ -[PPSMetricCollection setDisplayEnergyX:]
+ -[PPSMetricCollection setDisplayFPSX:]
+ -[PPSMetricCollection setDisplayPowerX:]
+ -[PPSMetricCollection setScanoutFPSX:]
+ -[PPSProcessMetricCollection displayPowerX]
+ -[PPSProcessMetricCollection setDisplayPowerX:]
+ -[PPSProcessMetricCollection setWeightOnScreenX:]
+ -[PPSProcessMetricCollection weightOnScreenX]
+ _OBJC_IVAR_$_PPSMetricCollection._brightnessX
+ _OBJC_IVAR_$_PPSMetricCollection._displayAPLX
+ _OBJC_IVAR_$_PPSMetricCollection._displayCostX
+ _OBJC_IVAR_$_PPSMetricCollection._displayEnergyX
+ _OBJC_IVAR_$_PPSMetricCollection._displayFPSX
+ _OBJC_IVAR_$_PPSMetricCollection._displayPowerX
+ _OBJC_IVAR_$_PPSMetricCollection._scanoutFPSX
+ _OBJC_IVAR_$_PPSProcessMetricCollection._displayPowerX
+ _OBJC_IVAR_$_PPSProcessMetricCollection._weightOnScreenX
CStrings:
+ "\nDisplay X Power    %8.3f W   %@\nDisplay X APL      %8.3f     %@\nDisplay X Cost     %8.3f     %@\nDisplay X Avg FPS  %8.3f     %@\nScanout X Avg FPS  %8.3f     %@\nDisplay X Energy   %8.3f J   %@\nBrightness X       %8.3f nits %@"
+ "%{public, signpost.description:begin_time}llu\n%{public, signpost.description:end_time}llu\nSystem Power Usage (sampled power) = %{public, name=System_Power_Usage, units=%/hr}.2f %%/hr\nThermal State = %{public, name=Thermal_State}ld \nCharging Status = %{public, name=Charging_State}d \nDisplay APL = %{public, name=Display_APL}.2f \nFrame Rate = %{public, name=Frame_Rate, units =fps}.2f FPS \nDisplay Brightness Percentage = %{public, name=Display_Brightness_Percentage, units=%}.2f %%\nDisplay Brightness Percentage X = %{public, name=Display_Brightness_Percentage_X, units=%}.2f %%\n"
+ "brightnessX"
+ "displayAPLX"
+ "displayCostX"
+ "displayEnergyX"
+ "displayFPSX"
+ "displayPowerX"
+ "scanoutFPSX"
```
