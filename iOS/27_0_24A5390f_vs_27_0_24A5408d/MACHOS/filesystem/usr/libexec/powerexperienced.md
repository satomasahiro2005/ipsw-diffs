## powerexperienced

> `/usr/libexec/powerexperienced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ad74` | `0x1b58c` | **`+0x818`** |
| `__TEXT.__oslogstring` | `0x31b3` | `0x32fc` | **`+0x149`** |
| `__DATA.__objc_const` | `0x5710` | `0x5840` | **`+0x130`** |
| `__TEXT.__objc_stubs` | `0x39c0` | `0x3ac0` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x41f5` | `0x42e7` | **`+0xf2`** |
| `__TEXT.__objc_methlist` | `0x23bc` | `0x2484` | **`+0xc8`** |
| `__DATA.__objc_data` | `0x8c0` | `0x910` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x1180` | `0x11c0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x758` | `0x780` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x8f8` | `0x918` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1341` | `0x1361` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x400` | `0x420` | **`+0x20`** |
| `__DATA.__bss` | `0x268` | `0x280` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x26c` | `0x278` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0xe0` | `0xe8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xd0` | `0xd8` | **`+0x8`** |
| `__TEXT.__const` | `0x148` | `0x150` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-173.0.0.0.0
+176.0.0.0.0

-  Functions: 843
+  Functions: 860

-  CStrings:  1440
+  CStrings:  1457
CStrings:
+ "DeviceExperienceState changing from %@ to %@ (secondaryDisplayActive=%d)"
+ "DeviceExperienceStateController"
+ "Failed to update CLPC with device orientation mode %@ (state %@). Error: %@"
+ "Failed to update CLPC with device thermal mode %@ (state %@). Error: %@"
+ "TC,V_currentState"
+ "Updated CLPC with device orientation mode %@ (state %@)"
+ "Updated CLPC with device thermal mode %@ (state %@)"
+ "_currentState"
+ "currentState"
+ "deviceexperiencestatecontroller"
+ "evaluateDeviceExperienceState"
+ "setCurrentState:"
+ "setDeviceExperienceState:"
+ "setDeviceOrientationMode:error:"
+ "setDeviceThermalMode:error:"
+ "setDeviceThermalState:"
+ "significantBackgroundTaskBacklogPresent:"
```
