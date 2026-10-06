## IOKit

> `/System/Library/Frameworks/IOKit.framework/Versions/A/IOKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2880` | `0xa2dd0` | **`+0x550`** |
| `__TEXT.__cstring` | `0xbd7e` | `0xbe08` | **`+0x8a`** |
| `__AUTH_CONST.__const` | `0x1e50` | `0x1e58` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2298` | `0x22a0` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 3573
-  Symbols:   3958
-  CStrings:  2578
+  Functions: 3575
+  Symbols:   3960
+  CStrings:  2587
Symbols:
+ _IOHIDEventCreateHingeAngleEvent
+ ___IOHIDEventTypeDescriptorHingeAngleEvent
CStrings:
+ "AngleDegrees:"
+ "Closed"
+ "ColorComponent0:"
+ "ColorComponent1:"
+ "ColorComponent2:"
+ "ColorSpace:"
+ "MechanicalAngleDegrees:"
+ "OSKEXT_BUILD_DATE 14:15:26 Aug  8 2026"
+ "XYZ"
+ "velocityDegreesPerSecond:"
- "OSKEXT_BUILD_DATE 17:18:31 Aug  8 2026"
```
