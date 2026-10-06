## libAppleTconUARPUpdater.dylib

> `/usr/lib/updaters/libAppleTconUARPUpdater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x702e4` | `0x70778` | **`+0x494`** |
| `__TEXT.__oslogstring` | `0x377b` | `0x3847` | **`+0xcc`** |
| `__TEXT.__cstring` | `0x7675` | `0x76ff` | **`+0x8a`** |
| `__AUTH_CONST.__cfstring` | `0x54c0` | `0x5520` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1a50` | `0x1a70` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xdb8` | `0xdc8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x67fc` | `0x6804` | **`+0x8`** |

### Other Changes

```diff

-1587.0.21.0.0
+1587.0.27.0.0

-  Functions: 2921
-  Symbols:   4806
-  CStrings:  1294
+  Functions: 2928
+  Symbols:   4812
+  CStrings:  1300
Symbols:
+ -[UARPSuperBinaryLayer3 processSuperBinaryPropertyList:]
+ _UARPLayer3DateAsString
+ _UARPLayer3DateTimeAsString
+ _UARPLayer3TimestampAsString
+ _kUARPCommonPayloadPLST
+ _kUARPCommonPayloadPMAP
CStrings:
+ "%02ld-%02ld-%02ld"
+ "%04ld-%02ld-%02ld"
+ "%s: Failed to instantiate UARPSuperBinaryPayloadLayer3 at index %lu for %@"
+ "%s: could not instantiate UARPSuperBinaryLayer3 for tag %@ on endpoint %@"
+ "%s: could not instantiate UARPSuperBinaryPayloadLayer3 for asset %@ on endpoint %@"
+ "%s: processSuperBinaryPropertyList: failed to process"
+ "-"
+ "-[UARPEndpointLayer3(Layer2EndpointCallbacks) layer2CallbackUnsolicitedDynamicAssetOffered:assetTag:]_block_invoke"
+ "PLST"
- "%s: Error creating payload at index %lu"
- "%s: Failed to create payload at index %lu"
- "yyyy-MM-dd-HH-mm-ss"
```
