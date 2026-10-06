## Gestures

> `/System/Library/PrivateFrameworks/Gestures.framework/Gestures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42bbc0` | `0x435cb0` | **`+0xa0f0`** |
| `__TEXT.__eh_frame` | `0x302f4` | `0x30930` | **`+0x63c`** |
| `__DATA.__bss` | `0x2e8d0` | `0x2ebd0` | **`+0x300`** |
| `__TEXT.__const` | `0x1e580` | `0x1e7b0` | **`+0x230`** |
| `__TEXT.__swift5_typeref` | `0x1f487` | `0x1f62f` | **`+0x1a8`** |
| `__AUTH_CONST.__const` | `0x19d30` | `0x19c10` | **`-0x120`** |
| `__TEXT.__unwind_info` | `0xeed0` | `0xefb8` | **`+0xe8`** |
| `__TEXT.__cstring` | `0xf13d` | `0xf0ad` | **`-0x90`** |
| `__AUTH_CONST.__objc_const` | `0x35c0` | `0x3600` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x4854` | `0x4894` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x6794` | `0x67c8` | **`+0x34`** |
| `__DATA.__data` | `0x97c8` | `0x9798` | **`-0x30`** |
| `__TEXT.__swift5_proto` | `0x27a4` | `0x27c8` | **`+0x24`** |
| `__AUTH.__data` | `0x4c78` | `0x4c58` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x8e0c` | `0x8e28` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x2540` | `0x2528` | **`-0x18`** |
| `__TEXT.__swift5_capture` | `0x18cc` | `0x18e0` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x1600` | `0x15f0` | **`-0x10`** |
| `__DATA_DIRTY.__common` | `0x4c` | `0x44` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x904` | `0x908` | **`+0x4`** |

### Other Changes

```diff

-9127.0.75.0.0
+9127.0.79.0.0

-  Functions: 17105
-  Symbols:   3857
-  CStrings:  535
+  Functions: 17089
+  Symbols:   3882
+  CStrings:  532
Symbols:
+ ___swift_closure_destructor.29Tm
+ ___swift_exist.box.addr_destructor.25Tm
+ ___swift_project_boxed_opaque_existential_0
+ ___unnamed_18
+ ___unnamed_26
+ _associated conformance 8Gestures15ReferenceLengthVSLAASQ
+ _symbolic SDy_____Say_____GG 8Gestures13GestureNodeIDV AA21ServerSystemGateGroupC
+ _symbolic _____ 8Gestures15ReferenceLengthV
+ _symbolic _____ 8Gestures17MotionAccumulatorV0B8Mismatch33_3FF98EDE6DE80FA5EF0C522909068082LLV
+ _symbolic _____ 8Gestures21ServerSystemGateGroupC25handleFailureOfDependency33_E5E40AF1AA442A0DF24C64E3F7EA79BALL4withyAA13GestureNodeIDV_tF03AllcA6FailedL_V
+ _symbolic _____SgXw 8Gestures23ServerSystemGateManagerC
+ _symbolic _____y$4______y_____GG 8Gestures10RingBufferV AA12GesturePhaseO AA17PanComponentValueV
+ _symbolic _____y$4______y_____GG 8Gestures10RingBufferV AA12GesturePhaseO AA17TapComponentValueV
+ _symbolic _____y$4______y_____GG 8Gestures10RingBufferV AA12GesturePhaseO AA23LongPressComponentValueV
+ _symbolic _____y$4______y_____GG 8Gestures10RingBufferV AA12GesturePhaseO AA23TransformComponentValueV
+ _symbolic _____y$4______y_____GG 8Gestures18RingBufferIteratorV AA12GesturePhaseO AA17PanComponentValueV
+ _symbolic _____y$4______y_____GG 8Gestures18RingBufferIteratorV AA12GesturePhaseO AA17TapComponentValueV
+ _symbolic _____y$4______y_____GG 8Gestures18RingBufferIteratorV AA12GesturePhaseO AA23LongPressComponentValueV
+ _symbolic _____y$4______y_____GG 8Gestures18RingBufferIteratorV AA12GesturePhaseO AA23TransformComponentValueV
+ _symbolic _____y_____G 8Gestures12GesturePhaseO AA17PanComponentValueV
+ _symbolic _____y_____G 8Gestures12GesturePhaseO AA17TapComponentValueV
+ _symbolic _____y_____G 8Gestures12GesturePhaseO AA23LongPressComponentValueV
+ _symbolic _____y_____G 8Gestures12GesturePhaseO AA23TransformComponentValueV
+ _symbolic _____y_____G 8Gestures22ConcreteDecodingBridge33_4748A3B59C3C63F4B2F5F0DC897D5A36LLV AA15ReferenceLengthV
+ _symbolic _____y_____G 8Gestures22ConcreteEncodingBridge33_31140E8441B47DC8189D099795089180LLV AA15ReferenceLengthV
+ _symbolic _____y_____G_ACt 8Gestures12GesturePhaseO AA17PanComponentValueV
+ _symbolic _____y_____G_ACt 8Gestures12GesturePhaseO AA23TransformComponentValueV
+ _symbolic _____y_____Say_____GG s18_DictionaryStorageC 8Gestures13GestureNodeIDV AC21ServerSystemGateGroupC
+ _symbolic _____y______G 8Gestures17GesturePhaseQueueV17InvalidTransition33_6A4A816C1A2ABE239E994BF101BBC632LLV AA17PanComponentValueV
+ _symbolic _____y______G 8Gestures17GesturePhaseQueueV17InvalidTransition33_6A4A816C1A2ABE239E994BF101BBC632LLV AA17TapComponentValueV
+ _symbolic _____y______G 8Gestures17GesturePhaseQueueV17InvalidTransition33_6A4A816C1A2ABE239E994BF101BBC632LLV AA23LongPressComponentValueV
+ _symbolic _____y______G 8Gestures17GesturePhaseQueueV17InvalidTransition33_6A4A816C1A2ABE239E994BF101BBC632LLV AA23TransformComponentValueV
+ _symbolic y_____cSg 8Gestures14AnyGestureNodeC
- ___swift_closure_destructor.32Tm
- ___swift_exist.box.addr_destructor.24Tm
- ___unnamed_16
- ___unnamed_27
- _symbolic _____ 8Gestures17MotionAccumulatorV18adjustForThreshold_5deltaAA0B5DeltaVSgAC0F0V_AGtKF0B8MismatchL_V
- _symbolic _____ 8Gestures21ServerSystemGateGroupC27processDependencyNodeUpdate33_E5E40AF1AA442A0DF24C64E3F7EA79BALLyyAA07GestureH0CyytGF03AllcA6FailedL_V
- _symbolic _____ySdG 8Gestures22ConcreteDecodingBridge33_4748A3B59C3C63F4B2F5F0DC897D5A36LLV
- _symbolic _____ySdG 8Gestures22ConcreteEncodingBridge33_31140E8441B47DC8189D099795089180LLV
CStrings:
- "Gestures/ServerSystemGateGroup.swift"
- "com.apple.Gestures.systemGateDepsTracker ("
- "failEarlyOnDependencyRecognition"
```
