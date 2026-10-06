## analyticsd

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x141b38` | `0x142538` | **`+0xa00`** |
| `__TEXT.__oslogstring` | `0x1ad69` | `0x1af29` | **`+0x1c0`** |
| `__TEXT.__objc_stubs` | `0x2c00` | `0x2cc0` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x17648` | `0x176e4` | **`+0x9c`** |
| `__TEXT.__cstring` | `0x16075` | `0x160d5` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x2f28` | `0x2f83` | **`+0x5b`** |
| `__DATA_CONST.__cfstring` | `0xd00` | `0xd40` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xe88` | `0xeb8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xad98` | `0xadc8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x8540` | `0x8568` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x630` | `0x638` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-  Functions: 6348
-  Symbols:   733
-  CStrings:  4115
+  Functions: 6354
+  Symbols:   734
+  CStrings:  4131
Symbols:
+ _OBJC_CLASS_$_CMDeviceStateManager
CStrings:
+ "DeviceStatePropertyQueue"
+ "[MotionStateResolver] Initializing CoreMotion Device State Properties"
+ "[MotionStateResolver] Starting updates for device state properties"
+ "[MotionStateResolver] WARNING: Device state manager instance not found."
+ "[MotionStateResolver] WARNING: Failed to get any CoreMotion classes for device state properties"
+ "[MotionStateResolver] WARNING: Operation queue instance not found for device state."
+ "[MotionStateResolver] property A: %ld, property B %ld"
+ "_"
+ "com.apple.analytics.motionstateresolver"
+ "initWithName:"
+ "isAvailable"
+ "propertyA"
+ "propertyB"
+ "startUpdatesToQueue:withHandler:"
+ "stopUpdates"
+ "v24@?0@\"CMDeviceStateEvent\"8@\"NSError\"16"
```
