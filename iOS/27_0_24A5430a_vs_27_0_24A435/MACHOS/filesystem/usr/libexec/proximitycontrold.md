## proximitycontrold

> `/usr/libexec/proximitycontrold`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x260cdc` | `0x261cfc` | **`+0x1020`** |
| `__TEXT.__oslogstring` | `0x7c0e` | `0x7d4e` | **`+0x140`** |
| `__DATA.__objc_const` | `0x187f8` | `0x18930` | **`+0x138`** |
| `__TEXT.__objc_methname` | `0xde49` | `0xdf59` | **`+0x110`** |
| `__TEXT.__objc_stubs` | `0x41a0` | `0x4280` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x153e8` | `0x154b0` | **`+0xc8`** |
| `__DATA.__data` | `0x179c8` | `0x17a88` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x7d19` | `0x7d99` | **`+0x80`** |
| `__TEXT.__const` | `0x21168` | `0x211d8` | **`+0x70`** |
| `__TEXT.__objc_classname` | `0x23c7` | `0x2427` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x9943` | `0x99a3` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0xf184` | `0xf1e4` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x92cc` | `0x9318` | **`+0x4c`** |
| `__TEXT.__constg_swiftt` | `0xd6b0` | `0xd6f4` | **`+0x44`** |
| `__DATA.__objc_selrefs` | `0x1d98` | `0x1dd0` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x345c` | `0x3494` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x6b90` | `0x6bb8` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x36db` | `0x36fb` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xea0` | `0xea8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x470` | `0x478` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x8b0` | `0x8b4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 10273
-  Symbols:   1632
-  CStrings:  4156
+  Functions: 10290
+  Symbols:   1633
+  CStrings:  4175
Symbols:
+ _OBJC_CLASS_$_CMDeviceStateManager
CStrings:
+ "[DeviceState] ### Unable to create CMDeviceStateManager; DeviceState source unavailable"
+ "[DeviceState] ### Update error: %{public}s"
+ "[DeviceState] %{public}s: propertyB=%{public}ld -> isDeviceStateSupported=%{bool,public}d"
+ "[DeviceState] Starting; CMDeviceStateManager.isAvailable=%{bool,public}d"
+ "_TtC17proximitycontroldP33_6EE8370B87DB0A53F8CEB2E558CDC55E19DeviceStateObserver"
+ "com.apple.ProximityControl.FrontBoardMonitor"
+ "com.apple.ProximityControl.FrontBoardMonitor.DeviceStateObserver"
+ "deliveryQueue"
+ "deviceStateObserver"
+ "didReceiveInitialEvent"
+ "initWithName:"
+ "isAvailable"
+ "onUpdate"
+ "propertyB"
+ "setMaxConcurrentOperationCount:"
+ "setName:"
+ "startUpdatesToQueue:withHandler:"
+ "stopUpdates"
+ "v24@?0@\"CMDeviceStateEvent\"8@\"NSError\"16"
```
