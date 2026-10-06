## SOSBuddy

> `/Applications/SOSBuddy.app/SOSBuddy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c2bcc` | `0x2c37c0` | **`+0xbf4`** |
| `__TEXT.__objc_methname` | `0xc3f5` | `0xc5e5` | **`+0x1f0`** |
| `__TEXT.__oslogstring` | `0xde33` | `0xdf03` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x4960` | `0x4a00` | **`+0xa0`** |
| `__DATA.__objc_const` | `0xf030` | `0xf088` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x1b418` | `0x1b468` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x2088` | `0x20c8` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x3d37` | `0x3d67` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x2c404` | `0x2c42a` | **`+0x26`** |
| `__DATA.__data` | `0x19210` | `0x19230` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xf568` | `0xf588` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2314` | `0x2334` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xbec1` | `0xbee1` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6558` | `0x6570` | **`+0x18`** |
| `__TEXT.__const` | `0x1ea44` | `0x1ea54` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x357c` | `0x358c` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xb9b0` | `0xb9bc` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x11b0` | `0x11b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 10922
-  Symbols:   2099
-  CStrings:  4308
+  Functions: 10930
+  Symbols:   2100
+  CStrings:  4324
Symbols:
+ _OBJC_CLASS_$_CMDeviceStateManager
CStrings:
+ "CMDeviceStateManager is not available on this device"
+ "Device state update error: %{public}s"
+ "Device state update received: %{public}@"
+ "Failed to create CMDeviceStateManager instance"
+ "Tf,R"
+ "_deviceStateManager"
+ "f16@0:8"
+ "forwardProgressUsage"
+ "initWithName:"
+ "isAvailable"
+ "minLOD"
+ "propertyB"
+ "recommendedPersistentThreadgroupsPerGridForThreadsPerThreadgroup:"
+ "startUpdatesToQueue:withHandler:"
+ "stopUpdates"
+ "v24@?0@\"CMDeviceStateEvent\"8@\"NSError\"16"
```
