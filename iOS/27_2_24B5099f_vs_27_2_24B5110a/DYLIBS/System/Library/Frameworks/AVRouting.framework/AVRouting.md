## AVRouting

> `/System/Library/Frameworks/AVRouting.framework/AVRouting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ce20` | `0x4cefc` | **`+0xdc`** |
| `__AUTH_CONST.__cfstring` | `0x47a0` | `0x47e0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0xc170` | `0xc1a0` | **`+0x30`** |
| `__TEXT.__cstring` | `0xa4da` | `0xa506` | **`+0x2c`** |
| `__TEXT.__objc_methlist` | `0x6770` | `0x6798` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2018` | `0x2030` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1108` | `0x1110` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x5a0` | `0x5a4` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 2497
-  Symbols:   4659
-  CStrings:  1202
+  Functions: 2500
+  Symbols:   4663
+  CStrings:  1204
Symbols:
+ -[AVOutputContext predictedOutputDeviceIDsForPebbleInitiatedAppBundleID:]
+ -[AVOutputContextPredictedDevicesOptions pebbleInitiatedAppBundleID]
+ -[AVOutputContextPredictedDevicesOptions setPebbleInitiatedAppBundleID:]
+ GCC_except_table114
+ GCC_except_table124
+ GCC_except_table126
+ GCC_except_table141
+ _OBJC_IVAR_$_AVOutputContextPredictedDevicesOptions._pebbleInitiatedAppBundleID
- GCC_except_table113
- GCC_except_table123
- GCC_except_table125
- GCC_except_table140
CStrings:
+ "EndpointSubType_HomeAccessory"
+ "HomeAccessory"
```
