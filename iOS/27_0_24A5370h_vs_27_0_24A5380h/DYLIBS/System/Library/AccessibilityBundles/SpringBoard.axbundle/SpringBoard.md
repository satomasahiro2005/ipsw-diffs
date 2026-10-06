## SpringBoard

> `/System/Library/AccessibilityBundles/SpringBoard.axbundle/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__objc_data` | `0x4c90` | `0x5550` | **`+0x8c0`** |
| `__AUTH.__objc_data` | `0x1450` | `0xc30` | **`-0x820`** |
| `__TEXT.__text` | `0x3a0b0` | `0x3a1f0` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0xb810` | `0xb930` | **`+0x120`** |
| `__TEXT.__cstring` | `0xa9b4` | `0xaa04` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x4e34` | `0x4e7c` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0xbee0` | `0xbf20` | **`+0x40`** |
| `__DATA_DIRTY.__bss` | `0x88` | `0xb8` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x7d0` | `0x7f0` | **`+0x20`** |
| `__DATA.__bss` | `0xf8` | `0xe0` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x9b0` | `0x9c0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1338` | `0x1348` | **`+0x10`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0

-  Functions: 1627
-  Symbols:   3895
-  CStrings:  1683
+  Functions: 1632
+  Symbols:   3912
+  CStrings:  1685
Symbols:
+ +[SBChargingAlertElementAccessibility _accessibilityPerformValidations:]
+ +[SBChargingAlertElementAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[SBChargingAlertElementAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[SBLowBatteryAlertElementAccessibility _accessibilityPerformValidations:]
+ +[SBLowBatteryAlertElementAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[SBLowBatteryAlertElementAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[SBChargingAlertElementAccessibility preferredAlertingDuration:]
+ -[SBLowBatteryAlertElementAccessibility preferredAlertingDuration:]
+ GCC_except_table1156
+ GCC_except_table1176
+ GCC_except_table1187
+ GCC_except_table1190
+ GCC_except_table1347
+ GCC_except_table1374
+ GCC_except_table1379
+ GCC_except_table1384
+ GCC_except_table1403
+ GCC_except_table1409
+ GCC_except_table1411
+ GCC_except_table1419
+ GCC_except_table1425
+ GCC_except_table1437
+ GCC_except_table1439
+ GCC_except_table1562
+ GCC_except_table1616
+ GCC_except_table972
+ GCC_except_table974
+ _OBJC_CLASS_$_SBChargingAlertElementAccessibility
+ _OBJC_CLASS_$_SBLowBatteryAlertElementAccessibility
+ _OBJC_CLASS_$___SBChargingAlertElementAccessibility_super
+ _OBJC_CLASS_$___SBLowBatteryAlertElementAccessibility_super
+ _OBJC_METACLASS_$_SBChargingAlertElementAccessibility
+ _OBJC_METACLASS_$_SBLowBatteryAlertElementAccessibility
+ _OBJC_METACLASS_$___SBChargingAlertElementAccessibility_super
+ _OBJC_METACLASS_$___SBLowBatteryAlertElementAccessibility_super
+ __OBJC_$_CLASS_METHODS_SBChargingAlertElementAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS_SBLowBatteryAlertElementAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_SBChargingAlertElementAccessibility
+ __OBJC_$_INSTANCE_METHODS_SBLowBatteryAlertElementAccessibility
+ __OBJC_CLASS_RO_$_SBChargingAlertElementAccessibility
+ __OBJC_CLASS_RO_$_SBLowBatteryAlertElementAccessibility
+ __OBJC_CLASS_RO_$___SBChargingAlertElementAccessibility_super
+ __OBJC_CLASS_RO_$___SBLowBatteryAlertElementAccessibility_super
+ __OBJC_METACLASS_RO_$_SBChargingAlertElementAccessibility
+ __OBJC_METACLASS_RO_$_SBLowBatteryAlertElementAccessibility
+ __OBJC_METACLASS_RO_$___SBChargingAlertElementAccessibility_super
+ __OBJC_METACLASS_RO_$___SBLowBatteryAlertElementAccessibility_super
+ ___63-[SpringBoardAccessibility _accessibilitySoftwareMimicKeyboard]_block_invoke_2
+ __accessibilitySoftwareMimicKeyboard.numberPadClass
+ __accessibilitySoftwareMimicKeyboard.onceToken
- +[SBPowerAlertElementAccessibility _accessibilityPerformValidations:]
- +[SBPowerAlertElementAccessibility(SafeCategory) safeCategoryBaseClass]
- +[SBPowerAlertElementAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[SBPowerAlertElementAccessibility preferredAlertingDuration:]
- GCC_except_table1152
- GCC_except_table1172
- GCC_except_table1179
- GCC_except_table1186
- GCC_except_table1343
- GCC_except_table1370
- GCC_except_table1375
- GCC_except_table1380
- GCC_except_table1399
- GCC_except_table1405
- GCC_except_table1407
- GCC_except_table1415
- GCC_except_table1421
- GCC_except_table1433
- GCC_except_table1435
- GCC_except_table1557
- GCC_except_table1611
- GCC_except_table968
- GCC_except_table970
- _OBJC_CLASS_$_SBPowerAlertElementAccessibility
- _OBJC_CLASS_$___SBPowerAlertElementAccessibility_super
- _OBJC_METACLASS_$_SBPowerAlertElementAccessibility
- _OBJC_METACLASS_$___SBPowerAlertElementAccessibility_super
- __OBJC_$_CLASS_METHODS_SBPowerAlertElementAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_SBPowerAlertElementAccessibility
- __OBJC_CLASS_RO_$_SBPowerAlertElementAccessibility
- __OBJC_CLASS_RO_$___SBPowerAlertElementAccessibility_super
- __OBJC_METACLASS_RO_$_SBPowerAlertElementAccessibility
- __OBJC_METACLASS_RO_$___SBPowerAlertElementAccessibility_super
CStrings:
+ "SBChargingAlertElement"
+ "SBChargingAlertElementAccessibility"
+ "SBLowBatteryAlertElement"
+ "SBLowBatteryAlertElementAccessibility"
+ "SBUIPasscodeLockNumberPad"
- "SBPowerAlertElement"
- "SBPowerAlertElementAccessibility"
- "viewController"
```
