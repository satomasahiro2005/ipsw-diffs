## UARPKit

> `/System/Library/PrivateFrameworks/UARPKit.framework/UARPKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14480` | `0x14184` | **`-0x2fc`** |
| `__TEXT.__cstring` | `0x1e75` | `0x1dea` | **`-0x8b`** |
| `__TEXT.__gcc_except_tab` | `0x340` | `0x3bc` | **`+0x7c`** |
| `__TEXT.__oslogstring` | `0x7b1` | `0x742` | **`-0x6f`** |
| `__TEXT.__objc_methlist` | `0x1470` | `0x14d8` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x430` | `0x3e0` | **`-0x50`** |
| `__AUTH_CONST.__objc_const` | `0x1e80` | `0x1ea8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xd58` | `0xd78` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x420` | `0x418` | **`-0x8`** |

### Other Changes

```diff

-1576.0.0.0.0
+1587.0.3.0.3

-  Functions: 508
-  Symbols:   784
-  CStrings:  242
+  Functions: 512
+  Symbols:   777
+  CStrings:  240
Symbols:
+ -[UARPDeviceManager stageFirmwareAsset:deviceEndpoint:]
+ -[UARPDeviceManager tmapProcessMappedAnalyticsAsset:]
+ -[UARPDeviceManager tmapUpdateDatabaseWithPlist:]
+ -[UARPDeviceManager tmapUpdateDatabaseWithSuperBinary:]
+ GCC_except_table100
+ GCC_except_table103
+ GCC_except_table106
+ GCC_except_table109
+ GCC_except_table112
+ GCC_except_table115
+ GCC_except_table118
+ GCC_except_table121
+ GCC_except_table68
+ GCC_except_table83
+ GCC_except_table88
+ GCC_except_table91
+ GCC_except_table94
+ GCC_except_table97
+ ___49-[UARPDeviceManager tmapUpdateDatabaseWithPlist:]_block_invoke
+ ___53-[UARPDeviceManager cacheAsset:deviceEndpoint:error:]_block_invoke
+ ___53-[UARPDeviceManager cacheAsset:deviceEndpoint:error:]_block_invoke_2
+ ___53-[UARPDeviceManager tmapProcessMappedAnalyticsAsset:]_block_invoke
+ ___55-[UARPDeviceManager tmapUpdateDatabaseWithSuperBinary:]_block_invoke
+ ___73-[UARPDeviceManager exportSolicitedAsset:deviceEndpoint:dynamicAssetURL:]_block_invoke
+ ___73-[UARPDeviceManager exportSolicitedAsset:deviceEndpoint:dynamicAssetURL:]_block_invoke_2
+ ___block_descriptor_40_e8_32r_e15_v16?0"NSURL"8lr32l8
- GCC_except_table102
- GCC_except_table105
- GCC_except_table108
- GCC_except_table111
- GCC_except_table114
- GCC_except_table117
- GCC_except_table120
- GCC_except_table123
- GCC_except_table126
- GCC_except_table81
- GCC_except_table86
- GCC_except_table89
- GCC_except_table92
- GCC_except_table95
- GCC_except_table98
- _CC_SHA512_Final
- _CC_SHA512_Init
- _CC_SHA512_Update
- ___47-[UARPDeviceManager cacheAssetStart:assetUUID:]_block_invoke
- ___47-[UARPDeviceManager cacheAssetStart:assetUUID:]_block_invoke_2
- ___53-[UARPDeviceManager cacheAsset:assetUUID:appendData:]_block_invoke
- ___53-[UARPDeviceManager cacheAsset:assetUUID:appendData:]_block_invoke_2
- ___53-[UARPDeviceManager pullDynamicAssetStart:assetUUID:]_block_invoke
- ___53-[UARPDeviceManager pullDynamicAssetStart:assetUUID:]_block_invoke_2
- ___54-[UARPDeviceManager pullDynamicAsset:assetUUID:range:]_block_invoke
- ___54-[UARPDeviceManager pullDynamicAsset:assetUUID:range:]_block_invoke_2
- ___57-[UARPDeviceManager cacheAssetFinish:assetUUID:hashData:]_block_invoke
- ___57-[UARPDeviceManager cacheAssetFinish:assetUUID:hashData:]_block_invoke_2
- ___63-[UARPDeviceManager pullDynamicAssetFinish:assetUUID:hashData:]_block_invoke
- ___63-[UARPDeviceManager pullDynamicAssetFinish:assetUUID:hashData:]_block_invoke_2
- ___block_descriptor_48_e8_32r40r_e11_v20?0B8Q12lr32l8r40l8
- ___block_descriptor_48_e8_32r40r_e18_v20?0B8"NSURL"12lr32l8r40l8
- ___block_descriptor_48_e8_32r40r_e19_v20?0B8"NSData"12lr32l8r40l8
CStrings:
+ "%s: %lu entries"
+ "%s: %s"
+ "%s: could not close %@; %@"
+ "%s: could not open file handle for %@"
+ "%s: no XPC connection"
+ "-[UARPDeviceManager cacheAsset:deviceEndpoint:error:]"
+ "-[UARPDeviceManager tmapProcessMappedAnalyticsAsset:]"
+ "-[UARPDeviceManager tmapUpdateDatabaseWithPlist:]"
+ "-[UARPDeviceManager tmapUpdateDatabaseWithSuperBinary:]"
+ "failed"
+ "success"
+ "v16@?0@\"NSURL\"8"
- "%s: Create not close %@; %@"
- "%s: Create not verify hash for %@"
- "%s: pullDynamicAsset for %@ failed at offset %lu, length %lu"
- "%s: pullDynamicAssetStart for %@ failed"
- "%s: writeData for %@ failed at offset %lu, length %lu; %@"
- "-[UARPDeviceManager cacheAsset:assetUUID:appendData:]"
- "-[UARPDeviceManager cacheAssetFinish:assetUUID:hashData:]"
- "-[UARPDeviceManager cacheAssetStart:assetUUID:]"
- "-[UARPDeviceManager pullDynamicAsset:assetUUID:range:]"
- "-[UARPDeviceManager pullDynamicAssetFinish:assetUUID:hashData:]"
- "-[UARPDeviceManager pullDynamicAssetStart:assetUUID:]"
- "v20@?0B8@\"NSData\"12"
- "v20@?0B8@\"NSURL\"12"
- "v20@?0B8Q12"
```
