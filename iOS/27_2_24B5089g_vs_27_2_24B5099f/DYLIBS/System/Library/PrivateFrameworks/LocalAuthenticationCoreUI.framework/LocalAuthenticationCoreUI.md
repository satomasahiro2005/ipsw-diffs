## LocalAuthenticationCoreUI

> `/System/Library/PrivateFrameworks/LocalAuthenticationCoreUI.framework/LocalAuthenticationCoreUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9e1e4` | `0x9edb8` | **`+0xbd4`** |
| `__AUTH_CONST.__objc_const` | `0xc320` | `0xc7b8` | **`+0x498`** |
| `__TEXT.__oslogstring` | `0xf8d` | `0x108d` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x30bc` | `0x317c` | **`+0xc0`** |
| `__DATA.__data` | `0x23c0` | `0x2430` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x738` | `0x788` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d48` | `0x1d98` | **`+0x50`** |
| `__TEXT.__cstring` | `0x2fd6` | `0x3026` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x4250` | `0x4280` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2890` | `0x28c0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x9f8` | `0xa20` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x1648` | `0x1670` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xe20` | `0xe40` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x2180` | `0x21a0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x14c` | `0x16c` | **`+0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x1fa8` | `0x1fc0` | **`+0x18`** |
| `__AUTH.__data` | `0x1d0` | `0x1c0` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x16c8` | `0x16d8` | **`+0x10`** |
| `__TEXT.__const` | `0x6f54` | `0x6f64` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x22b8` | `0x22c8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x210` | `0x21c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x2c0` | `0x2c8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x138` | `0x140` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x19c` | `0x1a0` | **`+0x4`** |

### Other Changes

```diff

-2319.40.35.0.1
+2319.40.43.0.0

+  - /System/Library/Frameworks/CoreMotion.framework/CoreMotion

-  Functions: 4555
-  Symbols:   10523
-  CStrings:  403
+  Functions: 4569
+  Symbols:   10562
+  CStrings:  409
Symbols:
+ -[LACUITouchIDSensorReachabilityMonitor .cxx_destruct]
+ -[LACUITouchIDSensorReachabilityMonitor _applyDeviceStateEvent:]
+ -[LACUITouchIDSensorReachabilityMonitor _sensorOutOfReachInDeviceStateEvent:]
+ -[LACUITouchIDSensorReachabilityMonitor dealloc]
+ -[LACUITouchIDSensorReachabilityMonitor isSensorOutOfReach]
+ -[LACUITouchIDSensorReachabilityMonitor sensorReachabilityDidChangeHandler]
+ -[LACUITouchIDSensorReachabilityMonitor setSensorReachabilityDidChangeHandler:]
+ -[LACUITouchIDSensorReachabilityMonitor start]
+ -[LACUITouchIDSensorReachabilityMonitor stop]
+ _$s25LocalAuthenticationCoreUI30LACUIPasscodeHostingController33_9C68DDE9F839077839CBDD25F7AE3B54LLC21viewDidLayoutSubviewsyyFTo
+ _$s25LocalAuthenticationCoreUI30LACUIPasscodeHostingController33_9C68DDE9F839077839CBDD25F7AE3B54LLCAA0e4ViewG11ConfiguringA2aEP17configureMaxWidth10windowSizeySo6CGSizeV_tFTW
+ _$s25LocalAuthenticationCoreUI30LACUIPasscodeHostingController33_9C68DDE9F839077839CBDD25F7AE3B54LLCAA0e4ViewG11ConfiguringA2aEP20configureBodyPadding4withySo012UINavigationG0CSg_tFTW
+ _$s25LocalAuthenticationCoreUI30LACUIPasscodeHostingController33_9C68DDE9F839077839CBDD25F7AE3B54LLCAA0e4ViewG11ConfiguringA2aEP25pullDownGestureRecognizer3forSo09UIGestureT0CSgSo06UIViewG0CSg_tFTW
+ _$s25LocalAuthenticationCoreUI30LACUIPasscodeHostingController33_9C68DDE9F839077839CBDD25F7AE3B54LLCAA0e4ViewG11ConfiguringA2aEP29configurePreferredContentSize4withySo6CGSizeV_tFTW
+ _$s25LocalAuthenticationCoreUI30LACUIPasscodeHostingController33_9C68DDE9F839077839CBDD25F7AE3B54LLCAA0e4ViewG11ConfiguringA2aEP9viewModelAA0eoR0CvgTW
+ _$s25LocalAuthenticationCoreUI30LACUIPasscodeHostingController33_9C68DDE9F839077839CBDD25F7AE3B54LLCAA0e4ViewG11ConfiguringAAMc
+ _$s25LocalAuthenticationCoreUI30LACUIPasscodeHostingController33_9C68DDE9F839077839CBDD25F7AE3B54LLCAA0e4ViewG11ConfiguringAAWP
+ _$s25LocalAuthenticationCoreUI38LACUIPasscodeViewControllerConfiguringPAASo06UIViewG0CRbzrlE20configureBodyPadding4withySo012UINavigationG0CSg_tFAA0e7HostingG033_9C68DDE9F839077839CBDD25F7AE3B54LLC_Tg5
+ _$s25LocalAuthenticationCoreUI38LACUIPasscodeViewControllerConfiguringPAASo06UIViewG0CRbzrlE20configureBodyPadding4withySo012UINavigationG0CSg_tFSo0e7ServicefG0C_Tg5
+ _$s7SwiftUI19UIHostingControllerC8rootViewxvgTj
+ _OBJC_CLASS_$_CMDeviceStateManager
+ _OBJC_CLASS_$_LACUITouchIDSensorReachabilityMonitor
+ _OBJC_IVAR_$_LACUITouchIDSensorReachabilityMonitor._deviceStateManager
+ _OBJC_IVAR_$_LACUITouchIDSensorReachabilityMonitor._sensorOutOfReach
+ _OBJC_IVAR_$_LACUITouchIDSensorReachabilityMonitor._sensorReachabilityDidChangeHandler
+ _OBJC_METACLASS_$_LACUITouchIDSensorReachabilityMonitor
+ __OBJC_$_INSTANCE_METHODS_LACUITouchIDSensorReachabilityMonitor
+ __OBJC_$_INSTANCE_VARIABLES_LACUITouchIDSensorReachabilityMonitor
+ __OBJC_$_PROP_LIST_LACUITouchIDSensorReachabilityMonitor
+ __OBJC_$_PROP_LIST_LACUITouchIDSensorReachabilityMonitoring
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_LACUITouchIDSensorReachabilityMonitoring
+ __OBJC_$_PROTOCOL_METHOD_TYPES_LACUITouchIDSensorReachabilityMonitoring
+ __OBJC_$_PROTOCOL_REFS_LACUITouchIDSensorReachabilityMonitoring
+ __OBJC_CLASS_PROTOCOLS_$_LACUITouchIDSensorReachabilityMonitor
+ __OBJC_CLASS_RO_$_LACUITouchIDSensorReachabilityMonitor
+ __OBJC_LABEL_PROTOCOL_$_LACUITouchIDSensorReachabilityMonitoring
+ __OBJC_METACLASS_RO_$_LACUITouchIDSensorReachabilityMonitor
+ __OBJC_PROTOCOL_$_LACUITouchIDSensorReachabilityMonitoring
+ ___46-[LACUITouchIDSensorReachabilityMonitor start]_block_invoke
+ ___block_descriptor_40_e8_32w_e40_v24?0"CMDeviceStateEvent"8"NSError"16lw32l8
+ _dispatch_assert_queue$V2
- _$s25LocalAuthenticationCoreUI38LACUIPasscodeViewControllerConfiguringPAASo06UIViewG0CRbzrlE20configureBodyPadding4withySo012UINavigationG0CSg_tFSo0e7ServicefG0C_Tg5Tm
- _$s25LocalAuthenticationCoreUI38LACUIPasscodeViewControllerConfiguringPAASo06UIViewG0CRbzrlE20configureBodyPadding4withySo012UINavigationG0CSg_tFSo0efG0C_Tg5
CStrings:
+ "%{public}@ could not start tracking, the sensor is assumed to be within reach"
+ "%{public}@ has nothing to track, the sensor is assumed to be within reach"
+ "%{public}@ observed A:%ld B:%ld, sensor out of reach: %d"
+ "Failed to read the device state: %{public}@"
+ "LocalAuthenticationUIService"
+ "v24@?0@\"CMDeviceStateEvent\"8@\"NSError\"16"
```
