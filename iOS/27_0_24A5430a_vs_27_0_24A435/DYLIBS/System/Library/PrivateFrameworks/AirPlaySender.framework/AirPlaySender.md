## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/AirPlaySender`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x243cd8` | `0x244090` | **`+0x3b8`** |
| `__TEXT.__cstring` | `0x8eacd` | `0x8ec83` | **`+0x1b6`** |
| `__AUTH_CONST.__cfstring` | `0x14880` | `0x148e0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xab8` | `0xb08` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x7740` | `0x7780` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x7668` | `0x76a8` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x2378` | `0x2388` | **`+0x10`** |
| `__TEXT.__const` | `0x61e0` | `0x61f0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x58b8` | `0x58c0` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 11437
-  Symbols:   8658
-  CStrings:  11571
+  Functions: 11443
+  Symbols:   8664
+  CStrings:  11583
Symbols:
+ _OBJC_CLASS_$_CMAngleManager
+ _OBJC_CLASS_$_CMDeviceStateManager
+ ___block_descriptor_32_e17_v16?0"CMAngle"8l
+ ___block_descriptor_32_e40_v24?0"CMDeviceStateEvent"8"NSError"16l
+ ___demoHIDClientInit_block_invoke_2
+ ___demoHIDClientInit_block_invoke_3
CStrings:
+ "Capturing motion angle data for demo data channel"
+ "Capturing motion device state for demo data channel"
+ "Error getting device state: %@"
+ "MotionDataAngle"
+ "MotionDataPropertyA"
+ "Unable to create NSData from demo angle: %@"
+ "Unable to create NSData from demo device state: %@"
+ "demoCaptureDeviceStateData"
+ "v16@?0@\"CMAngle\"8"
+ "v24@?0@\"CMDeviceStateEvent\"8@\"NSError\"16"
+ "void demoHIDClientInit(void)_block_invoke_2"
+ "void demoHIDClientInit(void)_block_invoke_3"
```
