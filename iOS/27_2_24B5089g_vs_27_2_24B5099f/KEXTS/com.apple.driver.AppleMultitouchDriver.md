## com.apple.driver.AppleMultitouchDriver

> `com.apple.driver.AppleMultitouchDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1d240` | `0x1d350` | **`+0x110`** |
| `__TEXT.__os_log` | `0x3a70` | `0x3acf` | **`+0x5f`** |
| `__TEXT_EXEC.__auth_stubs` | `0x6a0` | `0x680` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x350` | `0x340` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x128` | `0x130` | **`+0x8`** |
| `__TEXT.__cstring` | `0x22d5` | `0x22d4` | **`-0x1`** |

### Other Changes

```diff

-10100.44.0.0.0
+10110.3.0.0.0

-  CStrings:  542
+  CStrings:  543
Functions:
~ sub_fffffff009309e28 -> sub_fffffff00928edb8 : 204 -> 244
~ sub_fffffff009309ef4 -> sub_fffffff00928eeac : 204 -> 244
~ sub_fffffff00930a07c -> sub_fffffff00928f05c : 120 -> 56
~ sub_fffffff00930a108 -> sub_fffffff00928f0a8 : 104 -> 8
~ __ZN31AppleMultitouchDeviceUserClient11injectFrameEi : 372 -> 456
~ __ZN31AppleMultitouchDeviceUserClient12initWithTaskEP4taskPvjP12OSDictionary : 704 -> 740
~ sub_fffffff00930bfcc -> sub_fffffff009290f84 : 232 -> 252
~ __ZN31AppleMultitouchDeviceUserClient19clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 448 -> 660
CStrings:
+ "12111112122212121111111111111222222222111111122"
+ "[HID] [%s] [Error] %s::%s [0x%llx] Could not allocate _injectionMemory in clientMemoryForType\n"
- "121111121222121211111111111112222222221111112122"
```
