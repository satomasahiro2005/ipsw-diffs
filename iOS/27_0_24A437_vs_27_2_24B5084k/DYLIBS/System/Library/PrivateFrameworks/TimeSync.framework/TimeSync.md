## TimeSync

> `/System/Library/PrivateFrameworks/TimeSync.framework/TimeSync`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59b3c` | `0x5a174` | **`+0x638`** |
| `__TEXT.__oslogstring` | `0x4bd7` | `0x4ca2` | **`+0xcb`** |
| `__DATA_CONST.__const` | `0x1170` | `0x11e8` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0xfc0` | `0x1038` | **`+0x78`** |
| `__TEXT.__const` | `0x2b0` | `0x2a0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1af0` | `0x1b00` | **`+0x10`** |

### Other Changes

```diff

-1501.6.0.0.0
+1510.7.0.0.0

-  Functions: 2925
-  Symbols:   4473
-  CStrings:  1264
+  Functions: 2930
+  Symbols:   4475
+  CStrings:  1268
Symbols:
+ ___block_descriptor_48_e8_32s40r_e16_v16?0"NSUUID"8ls32l8r40l8
+ ___block_descriptor_48_e8_32s40r_e20_v20?0B8"NSError"12ls32l8r40l8
+ ___block_descriptor_48_e8_32s40r_e20_v20?0S8"NSError"12ls32l8r40l8
+ ___block_descriptor_48_e8_32s40r_e20_v20?0i8"NSError"12ls32l8r40l8
+ ___block_descriptor_48_e8_32s40r_e28_v24?0"NSUUID"8"NSError"16ls32l8r40l8
+ ___block_descriptor_48_e8_32s40r_e5_v8?0lr40l8s32l8
+ ___block_descriptor_56_e8_32r40r_e20_v20?0i8"NSError"12lr32l8r40l8
- ___32+[TSSyncEntity createWithProxy:]_block_invoke_3
- ___block_descriptor_40_e8_32r_e20_v20?0i8"NSError"12lr32l8
- ___block_descriptor_40_e8_32s_e20_v20?0S8"NSError"12ls32l8
- ___block_descriptor_40_e8_32s_e20_v20?0i8"NSError"12ls32l8
- ___block_descriptor_40_e8_32s_e28_v24?0"NSUUID"8"NSError"16ls32l8
CStrings:
+ "%@: %s error during call. UUID is nil."
+ "%@: %s failed to create sync entity (registered: %d, queriedSyncState: %d)."
+ "%@: %s failed to query sync entity type."
+ "%@: Failed to create sync entity for UUID: %@\n"
```
