## PowerlogHelperdOperators

> `/System/Library/PrivateFrameworks/PowerlogHelperdOperators.framework/PowerlogHelperdOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d5360` | `0x1d6d48` | **`+0x19e8`** |
| `__AUTH_CONST.__cfstring` | `0x330e0` | `0x33480` | **`+0x3a0`** |
| `__TEXT.__cstring` | `0x25f10` | `0x26160` | **`+0x250`** |
| `__TEXT.__oslogstring` | `0x148f6` | `0x14a6b` | **`+0x175`** |
| `__AUTH.__objc_data` | `0xbe0` | `0xaa0` | **`-0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x1720` | `0x1860` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x106c0` | `0x10738` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0xaac0` | `0xab28` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x15748` | `0x157a8` | **`+0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x15940` | `0x15990` | **`+0x50`** |
| `__AUTH_CONST.__objc_dictobj` | `0x39f8` | `0x3a20` | **`+0x28`** |
| `__DATA_DIRTY.__bss` | `0x390` | `0x3b8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x3a78` | `0x3aa0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x1a00` | `0x1a20` | **`+0x20`** |
| `__DATA.__bss` | `0x20c8` | `0x20b0` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x1590` | `0x1598` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x4420` | `0x4428` | **`+0x8`** |

### Other Changes

```diff

-3486.0.21.502.1
+3486.0.46.502.1

-  Functions: 8495
-  Symbols:   11551
-  CStrings:  8872
+  Functions: 8520
+  Symbols:   11569
+  CStrings:  8908
Symbols:
+ +[PLBatteryAgent entryEventBackwardDefinitionPowerDistribution]
+ +[PLDisplayAgent hasAppleARMBacklightPublisher]
+ +[PLUrsaUtilities getActionURLForAction:radarId:]
+ +[PLUrsaUtilities isRadarInstalled]
+ -[PLBatteryAgent lastPowerDistribution]
+ -[PLBatteryAgent logInputPowerDistribution:]
+ -[PLBatteryAgent logInputPowerDistributionToCA:]
+ -[PLBatteryAgent setLastPowerDistribution:]
+ -[PLXPCAgent clientDroppedEventsXPCListener]
+ -[PLXPCAgent logEventBackwardClientDroppedEvents:]
+ -[PLXPCAgent setClientDroppedEventsXPCListener:]
+ GCC_except_table134
+ GCC_except_table138
+ GCC_except_table157
+ GCC_except_table174
+ GCC_except_table186
+ GCC_except_table191
+ GCC_except_table247
+ GCC_except_table257
+ GCC_except_table259
+ GCC_except_table268
+ GCC_except_table275
+ GCC_except_table282
+ GCC_except_table321
+ GCC_except_table324
+ GCC_except_table328
+ GCC_except_table433
+ _OBJC_IVAR_$_PLBatteryAgent._lastPowerDistribution
+ _OBJC_IVAR_$_PLXPCAgent._clientDroppedEventsXPCListener
+ ___47+[PLDisplayAgent hasAppleARMBacklightPublisher]_block_invoke
+ ___48-[PLBatteryAgent logInputPowerDistributionToCA:]_block_invoke
+ ___block_descriptor_120_e8_32s40s_e19_"NSDictionary"8?0ls32l8s40l8
+ _hasAppleARMBacklightPublisher.onceToken
+ _hasAppleARMBacklightPublisher.result
+ _kPLBatteryAgentEventBackwardNamePowerDistribution
- GCC_except_table133
- GCC_except_table137
- GCC_except_table156
- GCC_except_table185
- GCC_except_table190
- GCC_except_table244
- GCC_except_table253
- GCC_except_table258
- GCC_except_table266
- GCC_except_table272
- GCC_except_table278
- GCC_except_table3
- GCC_except_table320
- GCC_except_table323
- GCC_except_table327
- GCC_except_table431
- ___block_descriptor_108_e8_32s40s_e19_"NSDictionary"8?0ls32l8s40l8
CStrings:
+ "ChargerAccumEfficiencyCount"
+ "ChargerAccumulatedEfficiency"
+ "ChargerCount"
+ "ChargerEfficiency"
+ "ChargerHwIlimBackoffReason"
+ "ChargerIBUS"
+ "ChargerPower"
+ "ChargerVBUS"
+ "ClientDroppedEvents"
+ "ClientDroppedEvents payload: %@"
+ "IPDChargingAllowed"
+ "IPDInputCurrent"
+ "IPDInputPower"
+ "IPDInputVoltage"
+ "IPDRatioOverride"
+ "IPDWattageOverride"
+ "InstantBootAdapterReady"
+ "InstantBootCount"
+ "InstantBootFailure"
+ "InstantBootGGReady"
+ "OPDDualChargerState"
+ "PLUrsaUtilities: generated action URL: %{public}@"
+ "PLUrsaUtilities: invalid action: %{public}@"
+ "PowerDistribution"
+ "Pushing InputPowerDistribution to CA: %@"
+ "SystemCapability100ms_Battery0"
+ "SystemCapability100ms_Battery1"
+ "SystemCapability1sec_Battery0"
+ "SystemCapability1sec_Battery1"
+ "SystemCapabilityInsta_Battery0"
+ "SystemCapabilityInsta_Battery1"
+ "XPCMetrics::ClientDroppedEvents"
+ "[OnDeviceACAMSBC] Skipping offset %@: payload entry is %{public}@, expected NSDictionary"
+ "[OnDeviceACAMSBC] Skipping offset %@: timeSinceLastSBC is %{public}@, expected NSNumber/NSString"
+ "com.apple.power.battery.InputPowerDistribution"
+ "nil action URL returned for action: %@"
+ "rdar://"
- "invalid action: %@"
```
