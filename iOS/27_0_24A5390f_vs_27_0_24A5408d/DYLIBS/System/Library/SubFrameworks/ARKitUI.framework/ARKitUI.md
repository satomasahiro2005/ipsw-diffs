## ARKitUI

> `/System/Library/SubFrameworks/ARKitUI.framework/ARKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b150` | `0x2b478` | **`+0x328`** |
| `__TEXT.__oslogstring` | `0x18d2` | `0x1830` | **`-0xa2`** |
| `__DATA_CONST.__objc_selrefs` | `0x2248` | `0x2288` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x2910` | `0x2950` | **`+0x40`** |
| `__TEXT.__const` | `0x948` | `0x938` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xc10` | `0xc18` | **`+0x8`** |

### Other Changes

```diff

-781.0.4.0.0
+781.0.7.0.0

-  Functions: 972
-  Symbols:   2135
-  CStrings:  234
+  Functions: 979
+  Symbols:   2143
+  CStrings:  230
Symbols:
+ -[ARCoachingAnimationView buildRendererForGoal:glyph:]
+ -[ARCoachingAnimationView startCoachingAnimation:camera:]
+ -[ARCoachingAnimationView teardownRenderer]
+ -[ARSCNView _abandonStuckRotationGateIfNeeded]
+ -[ARSCNView _removeRotationSnapshot]
+ -[ARSCNView _windowDidRotate:]
+ _ARCoachingLoadDeviceGlyphWithName
+ _ARDeviceName
+ ___46-[ARSCNView _abandonStuckRotationGateIfNeeded]_block_invoke
+ ___54-[ARCoachingAnimationView buildRendererForGoal:glyph:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
- -[ARCoachingAnimationView startCoachingAnimation:]
- ___50-[ARCoachingAnimationView startCoachingAnimation:]_block_invoke
- ___block_descriptor_40_e8_32s_e17_v16?0"NSError"8ls32l8
CStrings:
+ "%{public}@ <%p>: Loading coaching glyph %@ for %@"
- "Loading glyph for iPad with home button"
- "Loading glyph for iPad without home button"
- "Loading glyph for iPhone device with home button"
- "Loading glyph for iPhone device with notch"
- "Loading glyph for iPhone with island"
```
