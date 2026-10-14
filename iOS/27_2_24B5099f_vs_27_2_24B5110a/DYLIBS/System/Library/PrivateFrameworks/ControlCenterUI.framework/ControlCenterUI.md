## ControlCenterUI

> `/System/Library/PrivateFrameworks/ControlCenterUI.framework/ControlCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb550` | `0xbbec8` | **`+0x978`** |
| `__AUTH_CONST.__objc_const` | `0x11200` | `0x11260` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x446b` | `0x44cb` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x6960` | `0x69b0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x13f0` | `0x1438` | **`+0x48`** |
| `__DATA.__data` | `0x3a50` | `0x3a80` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x82c` | `0x85c` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xb578` | `0xb5a8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xd40` | `0xd68` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2d70` | `0x2d98` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x4511` | `0x4531` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4824` | `0x4834` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x744` | `0x750` | **`+0xc`** |

### Other Changes

```diff

-704.2.3.0.0
+704.2.4.100.0

-  Functions: 5057
-  Symbols:   5625
-  CStrings:  852
+  Functions: 5070
+  Symbols:   5640
+  CStrings:  856
Symbols:
+ -[CCUIBluetoothModuleViewController _startDiscoveringConnectedDevices]
+ -[CCUIBluetoothModuleViewController _stopDiscoveringConnectedDevices]
+ -[CCUIBluetoothModuleViewController _updateHiddenDeviceNames]
+ -[CCUIBluetoothModuleViewController _visibleConnectedDeviceNames]
+ GCC_except_table43
+ GCC_except_table58
+ GCC_except_table60
+ _OBJC_CLASS_$_CBDiscovery
+ _OBJC_IVAR_$_CCUIBluetoothModuleViewController._discoveredDevices
+ _OBJC_IVAR_$_CCUIBluetoothModuleViewController._discovery
+ _OBJC_IVAR_$_CCUIBluetoothModuleViewController._hiddenDeviceNames
+ ___70-[CCUIBluetoothModuleViewController _startDiscoveringConnectedDevices]_block_invoke
+ ___70-[CCUIBluetoothModuleViewController _startDiscoveringConnectedDevices]_block_invoke_2
+ ___70-[CCUIBluetoothModuleViewController _startDiscoveringConnectedDevices]_block_invoke_3
+ ___block_descriptor_32_e17_v16?0"NSError"8l
+ ___block_descriptor_40_e8_32w_e18_v16?0"CBDevice"8lw32l8
- GCC_except_table53
CStrings:
+ "[Bluetooth Module] CBDiscovery activation failed: %{public}@"
+ "[Bluetooth Module] Hidden connected devices: %@"
+ "v16@?0@\"CBDevice\"8"
+ "\xb1"
```
