## SPOwner

> `/System/Library/PrivateFrameworks/SPOwner.framework/SPOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77958` | `0x77b44` | **`+0x1ec`** |
| `__TEXT.__oslogstring` | `0x7fa8` | `0x8078` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x2760` | `0x2770` | **`+0x10`** |

### Other Changes

```diff

-449.30.6.14.26
+449.31.6.16.16

-  Functions: 4411
-  Symbols:   7356
-  CStrings:  1577
+  Functions: 4414
+  Symbols:   7357
+  CStrings:  1580
Symbols:
+ -[SPBeaconManager submitDeviceEvent:source:timestamp:attachedTo:completion:]
+ _OUTLINED_FUNCTION_4
+ ___76-[SPBeaconManager submitDeviceEvent:source:timestamp:attachedTo:completion:]_block_invoke
+ ___block_descriptor_76_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- -[SPBeaconManager submitDeviceEvent:source:attachedTo:completion:]
- ___66-[SPBeaconManager submitDeviceEvent:source:attachedTo:completion:]_block_invoke
- ___block_descriptor_68_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
CStrings:
+ "NVRAM data (length %lu) failed to deserialize as a property list: %@"
+ "NVRAM data deserialized to %@ instead of NSDictionary (data length %lu) - treating as absent"
+ "No NVRAM data present for fm-spkeys"
```
