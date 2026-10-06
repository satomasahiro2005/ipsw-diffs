## ARKitCore

> `/System/Library/SubFrameworks/ARKitCore.framework/ARKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19ad54` | `0x19ae6c` | **`+0x118`** |
| `__TEXT.__gcc_except_tab` | `0x13490` | `0x134bc` | **`+0x2c`** |
| `__AUTH_CONST.__objc_const` | `0x3d0e0` | `0x3d100` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x20dc6` | `0x20dd9` | **`+0x13`** |
| `__TEXT.__const` | `0x25d78` | `0x25d88` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6ad0` | `0x6ad8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2038` | `0x203c` | **`+0x4`** |

### Other Changes

```diff

-781.0.7.0.0
+781.40.3.0.0

-  Functions: 8024
-  Symbols:   14602
+  Functions: 8025
+  Symbols:   14603
Symbols:
+ _OBJC_IVAR_$_ARCubemapCompletion._espressoLock
Functions:
+ sub_2c25f5808
~ ___34+[ARKitUserDefaults defaultValues]_block_invoke : 2264 -> 2280
~ -[ARCubemapCompletion init] : 4156 -> 4160
~ -[ARCubemapCompletion completeLatLongImage:] : 308 -> 388
~ __ZN5arkit10loadParamsE22ARNoiseModelIdentifierRNSt3__16vectorIfNS1_9allocatorIfEEEERNS2_IS5_NS3_IS5_EEEERNS2_IS8_NS3_IS8_EEEESC_S6_ : 24948 -> 25012
~ +[ARNoiseParameters modelIdentifierForDevicePosition:longEdgeImageResolution:] : 2368 -> 2416
~ -[ARViewRotationAngleProvider _deliverPreviewAngle:] : 472 -> 480
CStrings:
+ "%{public}@ <%p>: Delivering viewRotationAngle %f degrees (preview angle %.0f)"
- "%{public}@ <%p>: Delivering view rotation angle %f degrees"
```
