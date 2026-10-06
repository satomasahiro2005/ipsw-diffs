## FindMyDevice

> `/System/Library/PrivateFrameworks/FindMyDevice.framework/FindMyDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b07c` | `0x2aee0` | **`-0x19c`** |
| `__TEXT.__cstring` | `0x4797` | `0x4747` | **`-0x50`** |
| `__AUTH_CONST.__objc_const` | `0x7db8` | `0x7d78` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x2c4c` | `0x2c1c` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x13f0` | `0x13c8` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0xc58` | `0xc38` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x224` | `0x214` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x3f0` | `0x3e8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1458` | `0x1450` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x25c` | `0x258` | **`-0x4`** |

### Other Changes

```diff

-482.30.6.14.20
+482.30.6.14.19

-  Functions: 1493
-  Symbols:   2381
-  CStrings:  936
+  Functions: 1484
+  Symbols:   2370
+  CStrings:  934
Symbols:
+ -[FMDRepairDeviceLookupResult initWithSerialNumbers:thisDeviceSerialNumber:]
+ _OBJC_IVAR_$_FMDRepairDeviceLookupResult._devicesInRepairMode
- -[FMDRepairDeviceLookupResult addDevice:]
- -[FMDRepairDeviceLookupResult mutableDevicesInRepairMode]
- -[FMDRepairDeviceLookupResult serialQueue]
- -[FMDRepairDeviceLookupResult setMutableDevicesInRepairMode:]
- -[FMDRepairDeviceLookupResult setSerialQueue:]
- GCC_except_table7
- _OBJC_IVAR_$_FMDRepairDeviceLookupResult._mutableDevicesInRepairMode
- _OBJC_IVAR_$_FMDRepairDeviceLookupResult._serialQueue
- ___41-[FMDRepairDeviceLookupResult addDevice:]_block_invoke
- ___42-[FMDRepairDeviceLookupResult description]_block_invoke
- ___50-[FMDRepairDeviceLookupResult devicesInRepairMode]_block_invoke
- ___block_descriptor_40_e8_32s_e32_v32?0"FMDRepairDevice"8Q16^B24ls32l8
- _dispatch_queue_attr_make_with_autorelease_frequency
CStrings:
- "com.apple.icloud.FindMyDevice.FMDRepairDeviceLookupResult"
- "v32@?0@\"FMDRepairDevice\"8Q16^B24"
```
