## ClothPhysics

> `/System/Library/PrivateFrameworks/ClothPhysics.framework/ClothPhysics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x91b1` | `0x920d` | **`+0x5c`** |
| `__TEXT.__text` | `0xc1048` | `0xc0ff0` | **`-0x58`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x3610` | `0x3608` | **`-0x8`** |

### Other Changes

```diff

-21.0.2.0.0
+21.0.3.0.0

-  Functions: 3931
-  Symbols:   4396
-  CStrings:  1720
+  Functions: 3929
+  Symbols:   4395
+  CStrings:  1724
Symbols:
+ __ZN5cloth14PickingVolumes10encodeDragEPNS_14ComputeEncoderERKNS_16VolumeDragParamsERKNS_20SimulationParametersE
+ __ZN5cloth14PickingVolumes10encodePickEPNS_14ComputeEncoderERKNS_16VolumePickParamsEbNS_18GenericBufferSliceILb0EEE
- __ZN5cloth14PickingVolumes10encodeDragEPNS_14ComputeEncoderERKNS_16VolumeDragParamsERKNS_20SimulationParametersEf
- __ZN5cloth14PickingVolumes10encodePickEPNS_14ComputeEncoderERKNS_16VolumePickParamsENS_18GenericBufferSliceILb0EEE
- __ZN5cloth14PickingVolumes19computeFalloffRangeEj
CStrings:
+ "Volume pick depth range"
+ "volumePickReduceDepth"
+ "volumePickResetDepthRange"
+ "volumePick_falloff"
+ "volumePick_noFalloff"
- "computeFalloffRange"
```
