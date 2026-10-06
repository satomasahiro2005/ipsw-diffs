## com.apple.driver.AppleT8140MCC

> `com.apple.driver.AppleT8140MCC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x16f88` | `0x170ac` | **`+0x124`** |
| `__TEXT.__cstring` | `0x5ba5` | `0x5c11` | **`+0x6c`** |
| `__TEXT.__os_log` | `0x266f` | `0x26cb` | **`+0x5c`** |

### Other Changes

```diff

-127.40.4.0.0
+127.40.5.0.0

-  CStrings:  926
+  CStrings:  930
Functions:
~ sub_fffffff0098db8f8 -> sub_fffffff0098dd328 : 304 -> 340
~ ____ZN25AppleMemCacheControllerV230getDataCollectionMemDescriptorEv_block_invoke : 248 -> 404
~ __ZN20AppleMCCUserClientV219clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 600 -> 700
CStrings:
+ "%s:%d: Failed to create mem descriptor for shared data queue\n\n"
+ "%s:%d: No data collection buffer available\n\n"
+ "Failed to create mem descriptor for shared data queue\n"
+ "No data collection buffer available\n"
```
