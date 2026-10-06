## SiriCrossDeviceArbitration

> `/System/Library/PrivateFrameworks/SiriCrossDeviceArbitration.framework/SiriCrossDeviceArbitration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x50` | `0xaf0` | **`+0xaa0`** |
| `__DATA_DIRTY.__objc_data` | `0xc80` | `0x1e0` | **`-0xaa0`** |
| `__TEXT.__text` | `0x2f498` | `0x2f744` | **`+0x2ac`** |
| `__TEXT.__oslogstring` | `0x545a` | `0x54d8` | **`+0x7e`** |
| `__TEXT.__objc_methlist` | `0x30d4` | `0x30fc` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x2e80` | `0x2ea0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x5318` | `0x5338` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5db4` | `0x5dd1` | **`+0x1d`** |
| `__DATA_CONST.__objc_selrefs` | `0x1df0` | `0x1e08` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x4f8` | `0x4fc` | **`+0x4`** |

### Other Changes

```diff

-3600.49.5.1.1
+3600.49.8.0.0

-  Functions: 1236
-  Symbols:   2308
-  CStrings:  1048
+  Functions: 1240
+  Symbols:   2313
+  CStrings:  1051
Symbols:
+ -[SCDAAssistantPreferences myriadForceInstrumentationEnabled]
+ -[SCDAPreferences forceInstrumentationEnabled]
+ -[SCDARecord isAnOutgoing]
+ GCC_except_table1013
+ GCC_except_table1034
+ GCC_except_table1098
+ GCC_except_table1129
+ GCC_except_table1141
+ GCC_except_table1216
+ GCC_except_table1217
+ GCC_except_table1223
+ GCC_except_table241
+ GCC_except_table247
+ GCC_except_table505
+ GCC_except_table734
+ GCC_except_table780
+ GCC_except_table849
+ GCC_except_table864
+ GCC_except_table915
+ GCC_except_table922
+ GCC_except_table949
+ GCC_except_table993
+ _OBJC_IVAR_$_SCDACoordinator._forceInstrumentationEnabled
+ ___61-[SCDAAssistantPreferences myriadForceInstrumentationEnabled]_block_invoke
- GCC_except_table1010
- GCC_except_table1031
- GCC_except_table1095
- GCC_except_table1123
- GCC_except_table1138
- GCC_except_table1212
- GCC_except_table1213
- GCC_except_table1219
- GCC_except_table240
- GCC_except_table246
- GCC_except_table502
- GCC_except_table731
- GCC_except_table777
- GCC_except_table846
- GCC_except_table861
- GCC_except_table909
- GCC_except_table919
- GCC_except_table946
- GCC_except_table990
Functions:
~ -[SCDACoordinator instrumentationUpdateBoost:value:] : 128 -> 136
~ -[SCDACoordinator _enterState:] : 3600 -> 3688
~ -[SCDACoordinator _readDefaults] : 744 -> 800
+ -[SCDARecord isAnEmergencyHandled]
+ -[SCDAAssistantPreferences myriadForceInstrumentationEnabled]
+ ___52-[SCDAAssistantPreferences disableMyriadBLEActivity]_block_invoke
~ -[SCDACoordinator initWithDelegate:] : 2824 -> 2788
~ ___68-[SCDACoordinator startWatchAdvertisingFromVoiceTriggerWithContext:]_block_invoke : 744 -> 756
~ ___51-[SCDACoordinator startAdvertisingFromInEarTrigger]_block_invoke : 316 -> 456
+ -[SCDAPreferences recencyBoostDecayInterval]
CStrings:
+ "%s #scda Not attempting / applying watch threshold boost because rebalance is enabled. rawAudioGoodnessScore: %u"
+ "%s BTLE trumping from in ear voice trigger"
+ "%s Skipping continuation loop: trigger was outgoing/self"
+ "%s Unexpectedly lowering goodness score %du for in ear trigger"
+ "Myriad Force Instrumentation"
- "%s #scda Not attempting / applying watch threshold boost because rebalance is enabled."
- "%s BTLE in-ear trigger entering election with default goodness"
```
