## libMobileGestalt.dylib

> `/usr/lib/libMobileGestalt.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6b438` | `0x6b1c0` | **`-0x278`** |
| `__TEXT.__cstring` | `0x176bd` | `0x1778d` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x3f54` | `0x3fb0` | **`+0x5c`** |
| `__AUTH_CONST.__cfstring` | `0x130e0` | `0x13120` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x22f8` | `0x22f0` | **`-0x8`** |

### Other Changes

```diff

-1622.0.0.0.0
+1622.0.4.0.0

-  Functions: 3603
+  Functions: 3605

-  CStrings:  3848
+  CStrings:  3850
CStrings:
+ "07622B10-6B5F-4A9D-848F-8D2A5DE1CF56"
+ "Failed to copyDeviceTreeProperty(IODeviceTree:/product side-button-location) on display %lu"
+ "IODeviceTree:/compute-module/compute-controller"
+ "IODeviceTree:/compute-module/compute-node"
+ "IODeviceTree:/compute-module/compute-packet-bridge"
+ "supports-apple-pencil"
- "1B36A68C-29DC-4699-9560-4BE0C4F06E5F"
- "compute-controller"
- "compute-node"
- "compute-packet-bridge"
```
