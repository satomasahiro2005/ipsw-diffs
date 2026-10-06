## CoreBluetooth

> `/System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd855c` | `0xd8624` | **`+0xc8`** |
| `__AUTH_CONST.__objc_const` | `0x1c630` | `0x1c6d0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0xd734` | `0xd78c` | **`+0x58`** |
| `__TEXT.__cstring` | `0x1af0c` | `0x1af54` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x11260` | `0x112a0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5cf8` | `0x5d20` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x1380` | `0x138c` | **`+0xc`** |
| `__TEXT.__const` | `0x2d59` | `0x2d65` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x29f8` | `0x2a00` | **`+0x8`** |

### Other Changes

```diff

-2701.3.0.0.0
+2701.7.0.0.0

-  Functions: 5546
-  Symbols:   8448
-  CStrings:  5126
+  Functions: 5553
+  Symbols:   8458
+  CStrings:  5132
Symbols:
+ -[CBChannelSoundingProcedureTonesData phyDebugData]
+ -[CBChannelSoundingProcedureTonesData phyDebugNumSteps]
+ -[CBDevice _clearProximityServiceProductKitBackoffTicks]
+ -[CBDevice proximityServiceProductKitBackoffTicks]
+ -[CBDevice setProximityServiceProductKitBackoffTicks:]
+ -[CBDeviceDataProximityService proximityServiceProductKitBackoffTicks]
+ -[CBDeviceDataProximityService setProximityServiceProductKitBackoffTicks:]
+ GCC_except_table536
+ GCC_except_table541
+ GCC_except_table556
+ GCC_except_table619
+ _OBJC_IVAR_$_CBChannelSoundingProcedureTonesData._phyDebugData
+ _OBJC_IVAR_$_CBChannelSoundingProcedureTonesData._phyDebugNumSteps
+ _OBJC_IVAR_$_CBDeviceDataProximityService._proximityServiceProductKitBackoffTicks
- GCC_except_table533
- GCC_except_table538
- GCC_except_table553
- GCC_except_table616
CStrings:
+ "\v"
+ ", %s %llu"
+ "5!"
+ "MobileBluetooth-2701.7"
+ "MusicHandoffScan"
+ "kCBCSPhyDebugData"
+ "kCBCSPhyDebugNumSteps"
+ "psBT"
- "\t"
- "MobileBluetooth-2701.3"
```
