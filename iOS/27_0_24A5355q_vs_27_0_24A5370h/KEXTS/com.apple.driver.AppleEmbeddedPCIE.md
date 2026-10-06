## com.apple.driver.AppleEmbeddedPCIE

> `com.apple.driver.AppleEmbeddedPCIE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x930` | **`+0x930`** |
| `__TEXT_EXEC.__text` | `0x338bc` | `0x33898` | **`-0x24`** |
| `__TEXT.__cstring` | `0x714e` | `0x7152` | **`+0x4`** |
| `__TEXT.__os_log` | `0x32d9` | `0x32dd` | **`+0x4`** |

### Other Changes

```diff

-1039.0.0.0.0
+1042.0.0.0.0
Functions:
~ __ZN17AppleEmbeddedPCIE15_handleAEREventEP16IOPCIEventSourcePK10IOPCIEvent : 2440 -> 2436
~ __ZN21AppleEmbeddedPCIEPort16_unmapRIDFromSIDEP11IOPCIDevice : 8120 -> 8104
~ sub_fffffff008b87a0c -> sub_fffffff008ba4848 : 348 -> 344
~ __ZN19ApplePCIEHostBridge13setPropertiesEP8OSObject : 324 -> 312
CStrings:
+ "[PCIe:%u %llu ns] AppleEmbeddedPCIEUserClient::%s Invalid error injection type %llu\n"
+ "[PCIe:%u %llu ns] AppleEmbeddedPCIEUserClient::%s Invalid timeout injection subtype %llu\n"
- "[PCIe:%u %llu ns] AppleEmbeddedPCIEUserClient::%s Invalid error injection type %u\n"
- "[PCIe:%u %llu ns] AppleEmbeddedPCIEUserClient::%s Invalid timeout injection subtype %u\n"
```
