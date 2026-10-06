## PowerlogCore

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/PowerlogCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x666e0` | `0x67280` | **`+0xba0`** |
| `__TEXT.__cstring` | `0x3f5fd` | `0x3ff65` | **`+0x968`** |
| `__DATA_CONST.__objc_arraydata` | `0x41040` | `0x41680` | **`+0x640`** |
| `__TEXT.__text` | `0xe6808` | `0xe6d4c` | **`+0x544`** |
| `__TEXT.__oslogstring` | `0x884a` | `0x88f8` | **`+0xae`** |
| `__AUTH.__objc_data` | `0x500` | `0x460` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x1db0` | `0x1e50` | **`+0xa0`** |
| `__DATA.__bss` | `0x1739` | `0x16b1` | **`-0x88`** |
| `__DATA_DIRTY.__bss` | `0x1138` | `0x11c0` | **`+0x88`** |
| `__AUTH_CONST.__objc_dictobj` | `0xf618` | `0xf690` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0xa9a0` | `0xaa00` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x96e0` | `0x9728` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x24a0` | `0x24e0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5920` | `0x5950` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2580` | `0x25a0` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x4a58` | `0x4a70` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x7c4` | `0x7cc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3098` | `0x30a0` | **`+0x8`** |

### Other Changes

```diff

-3486.0.21.502.1
+3486.0.46.502.1

-  Functions: 4920
-  Symbols:   7227
-  CStrings:  14419
+  Functions: 4929
+  Symbols:   7237
+  CStrings:  14518
Symbols:
+ -[PLArchiveManager fireArchiveListener]
+ -[PLArchiveManager setFireArchiveListener:]
+ -[PLIOKitOperatorComposition initWithOperator:forDynamicServiceClass:forNotificationType:forAFKRole:withMatchBlock:]
+ -[PowerlogCore fireSBCListener]
+ -[PowerlogCore fireSignificantBatteryChangeNotification]
+ -[PowerlogCore setFireSBCListener:]
+ _OBJC_IVAR_$_PLArchiveManager._fireArchiveListener
+ _OBJC_IVAR_$_PowerlogCore._fireSBCListener
+ ___116-[PLIOKitOperatorComposition initWithOperator:forDynamicServiceClass:forNotificationType:forAFKRole:withMatchBlock:]_block_invoke
+ ___20-[PowerlogCore init]_block_invoke_2
+ ___24-[PLArchiveManager init]_block_invoke_2
+ ___block_descriptor_32_e38_v32?0"NSDictionary"8"NSString"1624l
- GCC_except_table42
- ___105-[PLIOKitOperatorComposition initWithOperator:forDynamicServiceClass:forNotificationType:withMatchBlock:]_block_invoke
CStrings:
+ "1006035"
+ "ANE1"
+ "BatteryShippingChargeLimit"
+ "CPU_Energy"
+ "CSIDualAntennaDuration"
+ "CSIEnabledDuration"
+ "CSIMacActiveDuration"
+ "Dormancy"
+ "ECPU_CORE0_NRG"
+ "ECPU_CORE0_SRM_NRG"
+ "ECPU_CORE1_NRG"
+ "ECPU_CORE1_SRM_NRG"
+ "ECPU_CORE2_NRG"
+ "ECPU_CORE2_SRM_NRG"
+ "ECPU_CORE3_NRG"
+ "ECPU_CORE3_SRM_NRG"
+ "ECPU_CPM_NRG"
+ "ECPU_CPM_SRM_NRG"
+ "ECPU_NRG"
+ "Features"
+ "FirstPartyApps"
+ "Manually firing SBC"
+ "Manually firing archive activity"
+ "PCPU0_CORE0_NRG"
+ "PCPU0_CORE0_SRM_NRG"
+ "PCPU0_CORE1_NRG"
+ "PCPU0_CORE1_SRM_NRG"
+ "PCPU0_CPM_NRG"
+ "PCPU0_CPM_SRM_NRG"
+ "PCPU_NRG"
+ "PLBatteryAgent_EventBackward_Battery.filtered.Level_0_1.Level_7_1800.Level_8_300"
+ "ShipChargeLimitCompliant"
+ "ShipChargeLimitEnabled"
+ "ShipChargeLimitSupported"
+ "ShippingChargeLimitSystemStatus"
+ "Skipping manual archive: archive manager is not enabled"
+ "Skipping manual archive: storage is locked"
+ "SystemCapability100ms_Battery0"
+ "SystemCapability100ms_Battery0_0"
+ "SystemCapability100ms_Battery0_1"
+ "SystemCapability100ms_Battery0_2"
+ "SystemCapability100ms_Battery0_3"
+ "SystemCapability100ms_Battery0_4"
+ "SystemCapability100ms_Battery0_5"
+ "SystemCapability100ms_Battery0_6"
+ "SystemCapability100ms_Battery0_7"
+ "SystemCapability100ms_Battery1"
+ "SystemCapability100ms_Battery1_0"
+ "SystemCapability100ms_Battery1_1"
+ "SystemCapability100ms_Battery1_2"
+ "SystemCapability100ms_Battery1_3"
+ "SystemCapability100ms_Battery1_4"
+ "SystemCapability100ms_Battery1_5"
+ "SystemCapability100ms_Battery1_6"
+ "SystemCapability100ms_Battery1_7"
+ "SystemCapability1sec_Battery0"
+ "SystemCapability1sec_Battery0_0"
+ "SystemCapability1sec_Battery0_1"
+ "SystemCapability1sec_Battery0_2"
+ "SystemCapability1sec_Battery0_3"
+ "SystemCapability1sec_Battery0_4"
+ "SystemCapability1sec_Battery0_5"
+ "SystemCapability1sec_Battery0_6"
+ "SystemCapability1sec_Battery0_7"
+ "SystemCapability1sec_Battery1"
+ "SystemCapability1sec_Battery1_0"
+ "SystemCapability1sec_Battery1_1"
+ "SystemCapability1sec_Battery1_2"
+ "SystemCapability1sec_Battery1_3"
+ "SystemCapability1sec_Battery1_4"
+ "SystemCapability1sec_Battery1_5"
+ "SystemCapability1sec_Battery1_6"
+ "SystemCapability1sec_Battery1_7"
+ "SystemCapabilityInsta_Battery0"
+ "SystemCapabilityInsta_Battery0_0"
+ "SystemCapabilityInsta_Battery0_1"
+ "SystemCapabilityInsta_Battery0_2"
+ "SystemCapabilityInsta_Battery0_3"
+ "SystemCapabilityInsta_Battery0_4"
+ "SystemCapabilityInsta_Battery0_5"
+ "SystemCapabilityInsta_Battery0_6"
+ "SystemCapabilityInsta_Battery0_7"
+ "SystemCapabilityInsta_Battery1"
+ "SystemCapabilityInsta_Battery1_0"
+ "SystemCapabilityInsta_Battery1_1"
+ "SystemCapabilityInsta_Battery1_2"
+ "SystemCapabilityInsta_Battery1_3"
+ "SystemCapabilityInsta_Battery1_4"
+ "SystemCapabilityInsta_Battery1_5"
+ "SystemCapabilityInsta_Battery1_6"
+ "SystemCapabilityInsta_Battery1_7"
+ "UISoc"
+ "candidate"
+ "com.apple.powerlogd.archive"
+ "com.apple.powerlogd.fireSBC"
+ "effectiveIdleSeconds"
+ "eventTimestamp"
+ "excluded"
+ "inactive"
+ "\xa3"
- "\xa2"
```
