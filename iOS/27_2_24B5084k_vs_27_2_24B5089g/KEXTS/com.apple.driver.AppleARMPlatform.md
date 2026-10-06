## com.apple.driver.AppleARMPlatform

> `com.apple.driver.AppleARMPlatform`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x56b0c` | `0x56c2c` | **`+0x120`** |
| `__TEXT.__cstring` | `0xd238` | `0xd2a4` | **`+0x6c`** |
| `__TEXT.__os_log` | `0x14f7` | `0x1553` | **`+0x5c`** |

### Other Changes

```diff

-1150.40.3.0.0
+1150.40.4.0.0

-  CStrings:  1747
+  CStrings:  1751
Functions:
~ __ZN18AppleMCCUserClient19clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 600 -> 700
~ sub_fffffff00864a650 -> sub_fffffff00864a6b4 : 308 -> 340
~ ____ZN23AppleMemCacheController30getDataCollectionMemDescriptorEv_block_invoke : 248 -> 404
CStrings:
+ "%s:%d: Failed to create mem descriptor for shared data queue\n\n"
+ "%s:%d: No data collection buffer available\n\n"
+ "Failed to create mem descriptor for shared data queue\n"
+ "No data collection buffer available\n"
```
