## IOKit

> `/System/Library/Frameworks/IOKit.framework/Versions/A/IOKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa3474` | `0xa352c` | **`+0xb8`** |
| `__TEXT.__cstring` | `0xbe60` | `0xbea3` | **`+0x43`** |

### Other Changes

```diff

-  CStrings:  2596
+  CStrings:  2601
Functions:
~ ___IOHIDEventTypeDescriptorAmbientLightSensor : 256 -> 440
CStrings:
+ "ColorComponent0:"
+ "ColorComponent1:"
+ "ColorComponent2:"
+ "ColorSpace:"
+ "OSKEXT_BUILD_DATE 15:35:00 Oct  3 2026"
+ "XYZ"
- "OSKEXT_BUILD_DATE 20:49:23 Oct  3 2026"
```
