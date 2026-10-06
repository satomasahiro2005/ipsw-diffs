## libAppleTconUARPUpdater.dylib

> `/usr/lib/updaters/libAppleTconUARPUpdater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71230` | `0x71590` | **`+0x360`** |
| `__TEXT.__cstring` | `0x7771` | `0x77e0` | **`+0x6f`** |
| `__TEXT.__oslogstring` | `0x388a` | `0x38c7` | **`+0x3d`** |
| `__TEXT.__objc_methlist` | `0x6894` | `0x68cc` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fb0` | `0x1fd0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1ac0` | `0x1ad8` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0xd2d8` | `0xd2e0` | **`+0x8`** |

### Other Changes

```diff

-1587.2.3.0.0
+1587.40.26.502.1

-  Functions: 2950
-  Symbols:   4843
-  CStrings:  1305
+  Functions: 2958
+  Symbols:   4851
+  CStrings:  1309
Symbols:
+ -[UARPEndpointLayer3 noFirmwareAvailable]
+ -[UARPEndpointLayer3 notifyEndpointRemoteNotResponding]
+ -[UARPEndpointLayer3(Layer2EndpointCallbacks) layer2CallbackRemoteNotResponding:length:]
+ _OUTLINED_FUNCTION_19
+ _UARPEndpointLayer3RemoteNotResponding
+ _UARPLayer2RemoteNotResponding
+ ___41-[UARPEndpointLayer3 noFirmwareAvailable]_block_invoke
+ ___88-[UARPEndpointLayer3(Layer2EndpointCallbacks) layer2CallbackRemoteNotResponding:length:]_block_invoke
CStrings:
+ "%s: no firmware available"
+ "-[UARPEndpointLayer3 noFirmwareAvailable]_block_invoke"
+ "-[UARPEndpointLayer3 notifyEndpointRemoteNotResponding]"
+ "Endpoint %@: Remote Not Responding"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xc31"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xb31"
```
