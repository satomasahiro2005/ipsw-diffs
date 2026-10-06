## DeviceConfigurationAgent

> `/System/Library/PrivateFrameworks/DeviceConfiguration.framework/DeviceConfigurationAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c` | `0x5b0` | **`+0x574`** |
| `__TEXT.__auth_stubs` | `0x50` | `0x230` | **`+0x1e0`** |
| `__DATA_CONST.__auth_got` | `0x28` | `0x118` | **`+0xf0`** |
| `__DATA_CONST.__got` | `—` | `0x38` | **`+0x38`** |
| `__DATA.__data` | `—` | `0x28` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x38` | `0x60` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x58` | `0x80` | **`+0x28`** |
| `__TEXT.__cstring` | `—` | `0x24` | **`+0x24`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `—` | `0xa` | **`+0xa`** |
| `__DATA.__common` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__const` | `0x52` | `0x5a` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `—` | `0x6` | **`+0x6`** |

### Same-size Content Changes

- `__TEXT.__swift5_entry`

### Other Changes

```diff

-27.0.0.0.0
+29.2.6.0.0

+  - /usr/lib/swift/libswiftCore.dylib

+  - /usr/lib/swift/libswift_Concurrency.dylib
+  - /usr/lib/swift/libswift_DarwinFoundation3.dylib

-  Functions: 1
-  Symbols:   14
-  CStrings:  0
+  Functions: 11
+  Symbols:   53
+  CStrings:  2
Symbols:
+ _$s19DeviceConfiguration11UserManagerV014registerAsANewC8IfNeededyyFZ
+ _$s19DeviceConfiguration7ServiceC4stopyyF
+ _$s6Darwin7SIG_IGNyys5Int32VXCvg
+ _$s8Dispatch0A13WorkItemFlagsVMa
+ _$s8Dispatch0A13WorkItemFlagsVMn
+ _$s8Dispatch0A13WorkItemFlagsVs10SetAlgebraAAMc
+ _$s8Dispatch0A3QoSV11unspecifiedACvgZ
+ _$s8Dispatch0A3QoSVMa
+ _$sSayxGSTsMc
+ _$sScA15unownedExecutorScevgTj
+ _$sScM6sharedScMvgZ
+ _$sScMMa
+ _$sScMScAsWP
+ _$sSo17OS_dispatch_queueC8DispatchE4mainABvgZ
+ _$sSo18OS_dispatch_sourceC8DispatchE16makeSignalSource6signal5queueSo0a1_b1_c1_H0_ps5Int32V_So0a1_b1_I0CSgtFZ
+ _$sSo18OS_dispatch_sourceP8DispatchE15setEventHandler3qos5flags7handleryAC0D3QoSV_AC0D13WorkItemFlagsVyyXBSgtF
+ _$sSo18OS_dispatch_sourceP8DispatchE6resumeyyF
+ _$ss10SetAlgebraPyxqd__ncSTRd__7ElementQyd__ACRtzlufCTj
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _OBJC_CLASS_$_OS_dispatch_source
+ __Block_copy
+ __Block_release
+ __NSConcreteStackBlock
+ ___chkstk_darwin
+ __swiftEmptyArrayStorage
+ _exit
+ _objc_opt_self
+ _objc_release_x27
+ _signal
+ _swift_getObjCClassMetadata
+ _swift_getObjectType
+ _swift_getTypeByMangledNameInContext2
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_getWitnessTable
+ _swift_release
+ _swift_retain
+ _swift_retain_x2
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
CStrings:
+ "DeviceConfigurationAgent/main.swift"
+ "v8@?0"
```
