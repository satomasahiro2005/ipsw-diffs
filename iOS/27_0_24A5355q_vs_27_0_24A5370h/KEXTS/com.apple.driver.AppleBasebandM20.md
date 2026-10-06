## com.apple.driver.AppleBasebandM20

> `com.apple.driver.AppleBasebandM20`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x580` | **`+0x580`** |
| `__TEXT_EXEC.__text` | `0x49784` | `0x49cb0` | **`+0x52c`** |
| `__TEXT.__cstring` | `0xa534` | `0xa6b4` | **`+0x180`** |
| `__TEXT.__os_log` | `0x9998` | `0x9aeb` | **`+0x153`** |
| `__DATA.__data` | `0x1d8` | `0x1f0` | **`+0x18`** |

### Other Changes

```diff

-1114.0.0.0.0
-  Functions: 843
+1115.0.0.0.0
+  Functions: 844

-  CStrings:  1012
+  CStrings:  1018
CStrings:
+ "%06ld.%06d %s::%s: device is target coalesced? %d\n"
+ "%06ld.%06d %s::%s: failed first port enable -- assume baseband is missing and populate baseband node with unknown values\n"
+ "%06ld.%06d %s::%s: invalid baseband device ID = %u, populating baseband with unknown values\n"
+ "%06ld.%06d %s::%s: set chipset unknown property? %d\n"
+ "%06ld.%06d %s::%s: setProperty success? RadioType: %d | ChipID: %d\n"
+ "%s: deviceID %x did not match any entry in static map; setting unknown properties\n\n"
+ "466"
+ "562"
+ "577"
+ "643"
+ "651"
+ "674"
+ "multi-cellular-platform"
+ "setUnknownProperties"
- "%06ld.%06d %s::%s: failed first port enable -- will assume baseband is missing\n"
- "%06ld.%06d %s::%s: invalid baseband device ID = %u\n"
- "454"
- "549"
- "564"
- "630"
- "638"
- "661"
```
