## SymptomEvaluator

> `/System/Library/PrivateFrameworks/Symptoms.framework/Frameworks/SymptomEvaluator.framework/SymptomEvaluator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a0bd0` | `0x2a1080` | **`+0x4b0`** |
| `__AUTH_CONST.__cfstring` | `0x1f400` | `0x1f560` | **`+0x160`** |
| `__AUTH_CONST.__objc_const` | `0x41ae0` | `0x41b80` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x278d0` | `0x27970` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x6fe8` | `0x7058` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x47e45` | `0x47eb5` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x18cb0` | `0x18cf8` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xd508` | `0xd548` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x31a8` | `0x31b8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7aa0` | `0x7ab0` | **`+0x10`** |
| `__DATA.__bss` | `0xee0` | `0xee8` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 12233
-  Symbols:   20030
-  CStrings:  12219
+  Functions: 12241
+  Symbols:   20044
+  CStrings:  12231
Symbols:
+ -[MotionStateRelay deviceStatePropertyB]
+ -[MotionStateRelay setDeviceStatePropertyB:]
+ -[MotionStateRelay startDeviceStatePropertyBMonitoring]
+ -[MotionStateRelay stopDeviceStatePropertyBMonitoring]
+ -[SFDeviceReport deviceStatePropertyB]
+ -[SFDeviceReport setDeviceStatePropertyB:]
+ _OBJC_IVAR_$_MotionStateRelay._deviceStateManager
+ _OBJC_IVAR_$_MotionStateRelay._deviceStateOperationQueue
+ _OBJC_IVAR_$_MotionStateRelay._deviceStatePropertyB
+ _OBJC_IVAR_$_SFDeviceReport._deviceStatePropertyB
+ ___55-[MotionStateRelay startDeviceStatePropertyBMonitoring]_block_invoke
+ ___block_descriptor_40_e8_32s_e40_v24?0"CMDeviceStateEvent"8"NSError"16ls32l8
+ _cmDeviceStateManagerClass
+ _isDeviceStateAvailable
CStrings:
+ "<NWDeviceReport:\n\tTimestamp Bucket:\t\t%u\n\tBattery Percentage:\t\t\t%u\n\tBattery Current Capacity:\t\t%u\n\tBattery Maximum Capacity:\t\t%u\n\tBattery Design Capacity:\t\t%u\n\tBattery Absolute Capacity:\t\t%u\n\tBattery Voltage:\t\t\t%u\n\tBattery Time Remaining:\t\t\t%u\n\tBattery Temperature:\t\t\t%u\n\tBattery External Power Is Connected:\t%u\n\tBattery Fully Charged:\t\t\t%u\n\tBattery At Warn Level:\t\t\t%u\n\tBattery At Critical Level:\t\t%u\n\tRNF Enabled:\t\t\t\t%u\n\tDevice Plugged In:\t\t\t%u\n\tDevice Screen On:\t\t\t%u\n\tDevice Screen Brightness:\t\t%u\n\tMotion State:\t\t\t\t%u\n\tDevice Orientation:\t\t\t%u\n\tDevice State Property B:\t\t\t%u\n\tThermal Pressure:\t\t\t%u\n\tQUIC Experimentally Enabled:\t\t%u\n\tUnified HTTP Stack Experimentally Enabled:\t\t%u\n\tPrivacy Proxy Service Status:\t\t%u\n\tPrivacy Proxy User Tier:\t\t%u\n\tPrivacy Proxy Networks:\t\t%@\n\tPrivacy Proxy Traffic:\t\t%@\n>"
+ "Ambiguous"
+ "CMDeviceStateManager"
+ "D"
+ "E"
+ "F"
+ "G"
+ "H"
+ "MotionDeviceStateQueue"
+ "MotionStateRelay: Device state changed to %ld"
+ "MotionStateRelay: motion activity class for device state is %@available."
+ "deviceStatePropertyB"
+ "v24@?0@\"CMDeviceStateEvent\"8@\"NSError\"16"
+ "\xb6"
- "<NWDeviceReport:\n\tTimestamp Bucket:\t\t%u\n\tBattery Percentage:\t\t\t%u\n\tBattery Current Capacity:\t\t%u\n\tBattery Maximum Capacity:\t\t%u\n\tBattery Design Capacity:\t\t%u\n\tBattery Absolute Capacity:\t\t%u\n\tBattery Voltage:\t\t\t%u\n\tBattery Time Remaining:\t\t\t%u\n\tBattery Temperature:\t\t\t%u\n\tBattery External Power Is Connected:\t%u\n\tBattery Fully Charged:\t\t\t%u\n\tBattery At Warn Level:\t\t\t%u\n\tBattery At Critical Level:\t\t%u\n\tRNF Enabled:\t\t\t\t%u\n\tDevice Plugged In:\t\t\t%u\n\tDevice Screen On:\t\t\t%u\n\tDevice Screen Brightness:\t\t%u\n\tMotion State:\t\t\t\t%u\n\tDevice Orientation:\t\t\t%u\n\tThermal Pressure:\t\t\t%u\n\tQUIC Experimentally Enabled:\t\t%u\n\tUnified HTTP Stack Experimentally Enabled:\t\t%u\n\tPrivacy Proxy Service Status:\t\t%u\n\tPrivacy Proxy User Tier:\t\t%u\n\tPrivacy Proxy Networks:\t\t%@\n\tPrivacy Proxy Traffic:\t\t%@\n>"
- "\xa6"
```
