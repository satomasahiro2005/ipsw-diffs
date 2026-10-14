## libMobileGestalt.dylib

> `/usr/lib/libMobileGestalt.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__const` | `0x26268` | `0x25c28` | **`-0x640`** |
| `__TEXT.__text` | `0x6c1f8` | `0x6c72c` | **`+0x534`** |
| `__AUTH_CONST.__cfstring` | `0x133c0` | `0x134c0` | **`+0x100`** |
| `__TEXT.__const` | `0xa798` | `0xa878` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x1794d` | `0x17a1d` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x22e0` | `0x2338` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x1620` | `0x15d0` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x4039` | `0x4076` | **`+0x3d`** |

### Other Changes

```diff

-  Functions: 3620
-  Symbols:   1512
-  CStrings:  3874
+  Functions: 3629
+  Symbols:   1514
+  CStrings:  3885
Symbols:
+ _MobileGestalt_get_deviceSupportsFaceprint
+ _MobileGestalt_get_pumpkinMode
CStrings:
+ "27613242-AC70-4024-A204-58E9C509FC57"
+ "Accessory"
+ "BreadBoard"
+ "DeviceSupportsFaceprint"
+ "Failed to convert NVRAM number"
+ "HomeAccessory"
+ "PumpkinMode"
+ "TestMode2"
+ "Unknown NVRAM value type: %ld"
+ "WnCqFWpQgAFLfacM07K0RA"
+ "jSCETdfJtije3kkxEwspEQ"
+ "supports-faceprint"
- "1CC7D4EA-4D31-4423-B97E-6D2D944D3F64"
```
