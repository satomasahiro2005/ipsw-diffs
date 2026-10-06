## ConnectivityModule

> `/System/Library/AccessibilityBundles/ConnectivityModule.axbundle/ConnectivityModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1544` | `0x10e4` | **`-0x460`** |
| `__AUTH_CONST.__cfstring` | `0x6a0` | `0x360` | **`-0x340`** |
| `__TEXT.__cstring` | `0x687` | `0x3aa` | **`-0x2dd`** |
| `__AUTH_CONST.__objc_const` | `0x3f0` | `0x2d0` | **`-0x120`** |
| `__AUTH.__objc_data` | `0xa0` | `—` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x160` | `0x100` | **`-0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f8` | `0x1b8` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0xf0` | `0xd8` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x28` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x80` | `0x78` | **`-0x8`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 32
-  Symbols:   144
-  CStrings:  63
+  Functions: 26
+  Symbols:   127
+  CStrings:  37
Symbols:
+ -[CCUIConnectivityAirplaneViewControllerAccessibility buttonTapped:forEvent:]
+ ___77-[CCUIConnectivityAirplaneViewControllerAccessibility buttonTapped:forEvent:]_block_invoke
+ ___77-[CCUIConnectivityAirplaneViewControllerAccessibility buttonTapped:forEvent:]_block_invoke_2
+ ___block_descriptor_56_e8_32s40s48s_e23_v16?0"UIAlertAction"8ls32l8s40l8s48l8
+ _objc_release_x26
+ _objc_retain_x20
- +[CCUIConnectivityButtonViewControllerAccessibility _accessibilityPerformValidations:]
- +[CCUIConnectivityButtonViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[CCUIConnectivityButtonViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[CCUIConnectivityAirplaneViewControllerAccessibility buttonTapped:]
- -[CCUIConnectivityButtonViewControllerAccessibility _accessibilityControlCenterButtonIdentifier]
- -[CCUIConnectivityButtonViewControllerAccessibility _accessibilityControlCenterButtonLabel]
- -[CCUIConnectivityButtonViewControllerAccessibility _accessibilityControlCenterGenericOnOff]
- _OBJC_CLASS_$_CCUIConnectivityButtonViewControllerAccessibility
- _OBJC_CLASS_$_NSDictionary
- _OBJC_CLASS_$___CCUIConnectivityButtonViewControllerAccessibility_super
- _OBJC_METACLASS_$_CCUIConnectivityButtonViewControllerAccessibility
- _OBJC_METACLASS_$___CCUIConnectivityButtonViewControllerAccessibility_super
- __OBJC_$_CLASS_METHODS_CCUIConnectivityButtonViewControllerAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_CCUIConnectivityButtonViewControllerAccessibility
- __OBJC_CLASS_RO_$_CCUIConnectivityButtonViewControllerAccessibility
- __OBJC_CLASS_RO_$___CCUIConnectivityButtonViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$_CCUIConnectivityButtonViewControllerAccessibility
- __OBJC_METACLASS_RO_$___CCUIConnectivityButtonViewControllerAccessibility_super
- ___68-[CCUIConnectivityAirplaneViewControllerAccessibility buttonTapped:]_block_invoke
- ___68-[CCUIConnectivityAirplaneViewControllerAccessibility buttonTapped:]_block_invoke_2
- ___UIAXStringForVariables
- ___block_descriptor_48_e8_32s40s_e23_v16?0"UIAlertAction"8ls32l8s40l8
- _objc_retain_x22
CStrings:
+ "buttonTapped:forEvent:"
- "CCUIConnectivityButtonViewControllerAccessibility"
- "CCUIConnectivityHotspotViewController"
- "CCUILabeledRoundButtonViewController"
- "CONTROL_CENTER_STATUS_AIRPLANE_MODE_OFF"
- "CONTROL_CENTER_STATUS_AIRPLANE_MODE_ON"
- "CONTROL_CENTER_STATUS_BLUETOOTH_OFF"
- "CONTROL_CENTER_STATUS_BLUETOOTH_ON"
- "CONTROL_CENTER_STATUS_CELLULAR_DATA_OFF"
- "CONTROL_CENTER_STATUS_CELLULAR_DATA_ON"
- "CONTROL_CENTER_STATUS_HOTSPOT_OFF"
- "CONTROL_CENTER_STATUS_HOTSPOT_ON"
- "CONTROL_CENTER_STATUS_VPN_OFF"
- "CONTROL_CENTER_STATUS_VPN_ON"
- "CONTROL_CENTER_STATUS_WIFI_OFF"
- "CONTROL_CENTER_STATUS_WIFI_ON"
- "__AXStringForVariablesSentinel"
- "airplane-mode-button"
- "buttonTapped:"
- "cellular-data-button"
- "com.apple.ControlCenter.Bluetooth"
- "com.apple.ControlCenter.VPN"
- "com.apple.ControlCenter.WiFi"
- "hotspot-button"
- "off"
- "on"
- "subtitle"
- "title"
```
