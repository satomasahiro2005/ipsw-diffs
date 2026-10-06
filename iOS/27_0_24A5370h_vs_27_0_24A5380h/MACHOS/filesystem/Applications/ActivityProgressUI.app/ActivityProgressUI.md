## ActivityProgressUI

> `/Applications/ActivityProgressUI.app/ActivityProgressUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42310` | `0x44e7c` | **`+0x2b6c`** |
| `__TEXT.__eh_frame` | `0xac8` | `0xcf8` | **`+0x230`** |
| `__TEXT.__swift5_typeref` | `0x25dc` | `0x24d2` | **`-0x10a`** |
| `__TEXT.__oslogstring` | `0x13ec` | `0x14ec` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x2188` | `0x2250` | **`+0xc8`** |
| `__TEXT.__swift5_capture` | `0x780` | `0x81c` | **`+0x9c`** |
| `__TEXT.__unwind_info` | `0xf38` | `0xfb0` | **`+0x78`** |
| `__TEXT.__auth_stubs` | `0x1b20` | `0x1b90` | **`+0x70`** |
| `__TEXT.__const` | `0x3f74` | `0x3fe4` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x3935` | `0x39a5` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0xd98` | `0xdd0` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x3c` | `0x5c` | **`+0x20`** |
| `__DATA.__data` | `0x2680` | `0x2698` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x568` | `0x580` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x181c` | `0x1834` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x108c` | `0x10a4` | **`+0x18`** |
| `__DATA.__bss` | `0x2be0` | `0x2bf0` | **`+0x10`** |
| `__DATA.__objc_const` | `0x49f8` | `0x4a00` | **`+0x8`** |
| `__DATA.__objc_data` | `0xf10` | `0xf18` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xb28` | `0xb30` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xa38` | `0xa40` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x44` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x10` | `0x14` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-388.0.0.0.0
+390.0.0.0.0

-  Functions: 1577
-  Symbols:   895
-  CStrings:  807
+  Functions: 1605
+  Symbols:   906
+  CStrings:  812
Symbols:
+ _$s11ActivityKit0A0C0A12StateUpdatesV17makeAsyncIteratorAE0G0Vyx__GyF
+ _$s11ActivityKit0A0C0A12StateUpdatesV8IteratorVMn
+ _$s11ActivityKit0A0C0A12StateUpdatesV8IteratorVyx__GScIAAMc
+ _$s11ActivityKit0A0C0A12StateUpdatesVMn
+ _$s11ActivityKit0A0C20activityStateUpdatesAC0adE0Vyx_GvgTj
+ _$s11ActivityKit0A5StateO2eeoiySbAC_ACtFZ
+ _$s11ActivityKit0A5StateO9dismissedyA2CmFWC
+ _$s11ActivityKit0A5StateOMa
+ _$s11ActivityKit0A5StateOMn
+ _$s7SwiftUI5ColorV7opacityyACSdF
+ _$s7SwiftUI6HStackVyxGAA4ViewAAMc
+ _$sScI4next7ElementQzSgyYaKFTj
+ _$sScI4next7ElementQzSgyYaKFTjTu
+ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFyXl_Ts5
+ _$ss5ErrorMp
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
- _$s7SwiftUI13_HStackLayoutVMn
- _$s7SwiftUI21_ContentShapeModifierVMn
- _$s7SwiftUI21_ContentShapeModifierVyxGAA04ViewE0AAMc
- _$s7SwiftUI9RectangleVMn
- _swift_release_x9
CStrings:
+ "BackgroundActivitySessionsController: No session found when failing activity for task ID %s"
+ "Lockscreen activity %s dismissed by user; clearing failed tasks"
+ "Marking task %s as failed due to event: %s"
+ "Marking task identifier %s as failed by client"
+ "failActivityForIdentifier:"
```
