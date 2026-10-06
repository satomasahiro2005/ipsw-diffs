## DisembarkUI

> `/System/Library/PrivateFrameworks/DisembarkUI.framework/DisembarkUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20790` | `0x20ac0` | **`+0x330`** |
| `__TEXT.__cstring` | `0x1df4` | `0x1ea4` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x1640` | `0x16c0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x109b` | `0x1101` | **`+0x66`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b10` | `0x1b20` | **`+0x10`** |

### Other Changes

```diff

-  CStrings:  378
+  CStrings:  384
Functions:
~ -[DKTelephonyProvider isPhysicalSIMModeActive] : 8 -> 628
~ +[DKEraseConfirmationAlertController alertControllerWithCellularPlans:physicalSIMModeActive:completion:] : 1580 -> 1776
CStrings:
+ "%@%@"
+ "ERASE_CONFIRMATION_ALERT_PHYSICAL_SIM_BACK_SIM_DEACTIVATION_MESSAGE_PLURAL"
+ "ERASE_CONFIRMATION_ALERT_PHYSICAL_SIM_BACK_SIM_DEACTIVATION_MESSAGE_SINGULAR"
+ "Failed to query isEuiccActive: %{public}@"
+ "Failed to query supportsDynamicSIMConfiguration: %{public}@"
+ "Localizable-V63"
```
