## SettingsCellularUI

> `/System/Library/PrivateFrameworks/SettingsCellularUI.framework/SettingsCellularUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93904` | `0x94480` | **`+0xb7c`** |
| `__TEXT.__oslogstring` | `0x6c4b` | `0x6d3e` | **`+0xf3`** |
| `__AUTH_CONST.__cfstring` | `0x86c0` | `0x87a0` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x9141` | `0x91b0` | **`+0x6f`** |
| `__TEXT.__gcc_except_tab` | `0x186c` | `0x18d0` | **`+0x64`** |
| `__DATA_CONST.__const` | `0x1398` | `0x13d8` | **`+0x40`** |
| `__AUTH_CONST.__objc_intobj` | `0x378` | `0x3a8` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x5680` | `0x56a8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x9c9c` | `0x9cbc` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2370` | `0x2388` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xac8` | `0xad8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x678` | `0x670` | **`-0x8`** |
| `__AUTH_CONST.__objc_const` | `0x103d0` | `0x103d8` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 3357
-  Symbols:   5619
-  CStrings:  2059
+  Functions: 3363
+  Symbols:   5626
+  CStrings:  2070
Symbols:
+ +[SettingsCellularUtils simTypePrefixForLocation:]
+ -[PSUICellularController launchSIMConfigFlowFromURL:]
+ -[PSUITurnOnThisLineSpecifier simSetupFlowCompleted:]
+ GCC_except_table137
+ _TSUserInfoSIMConfigSwitchToEuiccKey
+ ___53-[PSUITurnOnThisLineSpecifier simSetupFlowCompleted:]_block_invoke
+ ___53-[PSUITurnOnThisLineSpecifier simSetupFlowCompleted:]_block_invoke_2
+ ___56-[PSUITurnOnThisLineSpecifier setPlanEnabled:specifier:]_block_invoke
+ ___block_descriptor_56_e8_32s40s_e5_v8?0ls32l8s40l8
- GCC_except_table136
- _objc_retain_x7
CStrings:
+ "Back SIM"
+ "DELETE_ESIM_CONFIRMATION_PP_MODE"
+ "Gemini-V63"
+ "Plan is no longer selectable — popping back to the Cellular page"
+ "Plan no longer exists — popping back to the Cellular page"
+ "Presenting SIM config switch flow for %@ plan"
+ "SIM config switch flow did not finish (type %lu) — reverting toggle"
+ "SIM_TYPE_BACK_SIM"
+ "SIM_TYPE_ESIM"
+ "SIM_TYPE_FRONT_SIM"
+ "action"
```
