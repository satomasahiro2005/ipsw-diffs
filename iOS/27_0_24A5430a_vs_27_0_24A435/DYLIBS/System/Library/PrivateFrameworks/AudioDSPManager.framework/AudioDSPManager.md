## AudioDSPManager

> `/System/Library/PrivateFrameworks/AudioDSPManager.framework/AudioDSPManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbe264` | `0xc008c` | **`+0x1e28`** |
| `__AUTH_CONST.__objc_const` | `0x1078` | `0x14c8` | **`+0x450`** |
| `__TEXT.__eh_frame` | `0x3618` | `0x37f8` | **`+0x1e0`** |
| `__TEXT.__gcc_except_tab` | `0x7158` | `0x7300` | **`+0x1a8`** |
| `__AUTH.__objc_data` | `0x4d8` | `0x618` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x7c8` | `0x8f0` | **`+0x128`** |
| `__AUTH_CONST.__const` | `0x7ed0` | `0x7fe0` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x3ba0` | `0x3ca8` | **`+0x108`** |
| `__TEXT.__cstring` | `0x6500` | `0x65f1` | **`+0xf1`** |
| `__TEXT.__oslogstring` | `0x3b89` | `0x3c59` | **`+0xd0`** |
| `__AUTH.__data` | `0x560` | `0x600` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x27f8` | `0x2898` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x578` | `0x608` | **`+0x90`** |
| `__TEXT.__const` | `0xef98` | `0xf008` | **`+0x70`** |
| `__DATA_CONST.__const` | `0xc48` | `0xc98` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x2cc` | `0x31c` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1540` | `0x1588` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0xfc0` | `0x1000` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x1d80` | `0x1dbc` | **`+0x3c`** |
| `__DATA.__data` | `0x1560` | `0x1590` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x88` | `0xb0` | **`+0x28`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x38` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x18fc` | `0x1918` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x5c0` | `0x5d8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x5c` | `0x70` | **`+0x14`** |
| `__DATA.__bss` | `0x8060` | `0x8070` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x149c` | `0x14ac` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x228` | `0x22c` | **`+0x4`** |

### Other Changes

```diff

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  - /usr/lib/swift/libswift_StringProcessing.dylib

-  Functions: 3598
-  Symbols:   4317
-  CStrings:  1233
+  Functions: 3643
+  Symbols:   4412
+  CStrings:  1245
Symbols:
+ +[CMAngleManagerShim isAvailable]
+ +[CMAngleManagerShim isClassAvailable]
+ +[CMDeviceStateManagerShim isAvailable]
+ +[CMDeviceStateManagerShim isClassAvailable]
+ +[CMDeviceStateManagerShim shared]
+ -[CMAngleManagerShim .cxx_destruct]
+ -[CMAngleManagerShim angleUpdateInterval]
+ -[CMAngleManagerShim init]
+ -[CMAngleManagerShim setAngleUpdateInterval:]
+ -[CMAngleManagerShim startAngleUpdatesToQueue:handler:]
+ -[CMAngleManagerShim stopAngleUpdates]
+ -[CMAngleShim angleDegrees]
+ -[CMAngleShim initWithAngle:]
+ -[CMAngleShim isAngleValid]
+ -[CMDeviceStateEventShim initWithEvent:]
+ -[CMDeviceStateEventShim propertyA]
+ -[CMDeviceStateManagerShim .cxx_destruct]
+ -[CMDeviceStateManagerShim init]
+ -[CMDeviceStateManagerShim startUpdatesToQueue:handler:]
+ -[CMDeviceStateManagerShim stopUpdates]
+ GCC_except_table14
+ GCC_except_table1753
+ GCC_except_table1756
+ GCC_except_table1757
+ GCC_except_table1760
+ GCC_except_table1764
+ GCC_except_table1767
+ GCC_except_table1768
+ GCC_except_table1769
+ GCC_except_table24
+ _NSClassFromString
+ _OBJC_CLASS_$_CMAngleManagerShim
+ _OBJC_CLASS_$_CMAngleShim
+ _OBJC_CLASS_$_CMDeviceStateEventShim
+ _OBJC_CLASS_$_CMDeviceStateManagerShim
+ _OBJC_CLASS_$_NSOperationQueue
+ _OBJC_IVAR_$_CMAngleManagerShim._manager
+ _OBJC_IVAR_$_CMAngleShim._angleDegrees
+ _OBJC_IVAR_$_CMAngleShim._angleValid
+ _OBJC_IVAR_$_CMDeviceStateEventShim._propertyA
+ _OBJC_IVAR_$_CMDeviceStateManagerShim._manager
+ _OBJC_METACLASS_$_CMAngleManagerShim
+ _OBJC_METACLASS_$_CMAngleShim
+ _OBJC_METACLASS_$_CMDeviceStateEventShim
+ _OBJC_METACLASS_$_CMDeviceStateManagerShim
+ __DATA__TtC20AudioDSPManagerSwift16CancellationFlag
+ __IVARS__TtC20AudioDSPManagerSwift16CancellationFlag
+ __METACLASS_DATA__TtC20AudioDSPManagerSwift16CancellationFlag
+ __OBJC_$_CLASS_METHODS_CMAngleManagerShim
+ __OBJC_$_CLASS_METHODS_CMDeviceStateManagerShim
+ __OBJC_$_CLASS_PROP_LIST_CMAngleManagerShim
+ __OBJC_$_CLASS_PROP_LIST_CMDeviceStateManagerShim
+ __OBJC_$_INSTANCE_METHODS_CMAngleManagerShim
+ __OBJC_$_INSTANCE_METHODS_CMAngleShim
+ __OBJC_$_INSTANCE_METHODS_CMDeviceStateEventShim
+ __OBJC_$_INSTANCE_METHODS_CMDeviceStateManagerShim
+ __OBJC_$_INSTANCE_VARIABLES_CMAngleManagerShim
+ __OBJC_$_INSTANCE_VARIABLES_CMAngleShim
+ __OBJC_$_INSTANCE_VARIABLES_CMDeviceStateEventShim
+ __OBJC_$_INSTANCE_VARIABLES_CMDeviceStateManagerShim
+ __OBJC_$_PROP_LIST_CMAngleManagerShim
+ __OBJC_$_PROP_LIST_CMAngleShim
+ __OBJC_$_PROP_LIST_CMDeviceStateEventShim
+ __OBJC_CLASS_RO_$_CMAngleManagerShim
+ __OBJC_CLASS_RO_$_CMAngleShim
+ __OBJC_CLASS_RO_$_CMDeviceStateEventShim
+ __OBJC_CLASS_RO_$_CMDeviceStateManagerShim
+ __OBJC_METACLASS_RO_$_CMAngleManagerShim
+ __OBJC_METACLASS_RO_$_CMAngleShim
+ __OBJC_METACLASS_RO_$_CMDeviceStateEventShim
+ __OBJC_METACLASS_RO_$_CMDeviceStateManagerShim
+ __ZZ34+[CMDeviceStateManagerShim shared]E8instance
+ __ZZ34+[CMDeviceStateManagerShim shared]E9onceToken
+ ___34+[CMDeviceStateManagerShim shared]_block_invoke
+ ___55-[CMAngleManagerShim startAngleUpdatesToQueue:handler:]_block_invoke
+ ___56-[CMDeviceStateManagerShim startUpdatesToQueue:handler:]_block_invoke
+ ___block_descriptor_40_ea8_32bs_e17_v16?0"CMAngle"8ls32l8
+ ___block_descriptor_40_ea8_32bs_e40_v24?0"CMDeviceStateEvent"8"NSError"16ls32l8
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _objc_release_x1
+ _objc_retainBlock
+ _objc_retain_x3
+ _swift_retain_x2
+ _symbolic So18CMAngleManagerShimC
+ _symbolic So24CMDeviceStateManagerShimC
+ _symbolic _____ 20AudioDSPManagerSwift16CancellationFlagC
+ _symbolic _____ySbG 15Synchronization6AtomicV
+ _symbolic _____ySf_G ScS12ContinuationV
+ _symbolic _____ySf__G ScS12ContinuationV11YieldResultO
+ _symbolic _____ySf__G ScS12ContinuationV15BufferingPolicyO
+ _symbolic _____y______G ScS12ContinuationV s5Int32V
+ _symbolic _____y_______G ScS12ContinuationV11YieldResultO s5Int32V
+ _symbolic _____y_______G ScS12ContinuationV15BufferingPolicyO s5Int32V
CStrings:
+ "Angle manager reports itself as unavailable"
+ "CMAngleManager"
+ "CMDeviceStateManager"
+ "Device angle update dropped (cancelled)"
+ "Device angle update error: invalid angle"
+ "Device pose update dropped (cancelled)"
+ "Device pose update error: %@"
+ "Device pose update: no event"
+ "State manager reports itself as unavailable"
+ "com.apple.AudioDSPManager.deviceAngle"
+ "com.apple.AudioDSPManager.devicePose"
+ "v16@?0@\"CMAngle\"8"
+ "v24@?0@\"CMDeviceStateEvent\"8@\"NSError\"16"
- "Feature not built in this configuration"
```
