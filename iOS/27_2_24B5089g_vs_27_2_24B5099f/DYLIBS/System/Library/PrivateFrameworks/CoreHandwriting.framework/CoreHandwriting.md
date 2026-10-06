## CoreHandwriting

> `/System/Library/PrivateFrameworks/CoreHandwriting.framework/CoreHandwriting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3514d0` | `0x352518` | **`+0x1048`** |
| `__TEXT.__gcc_except_tab` | `0x51734` | `0x5197c` | **`+0x248`** |
| `__TEXT.__oslogstring` | `0x1740c` | `0x17585` | **`+0x179`** |
| `__AUTH_CONST.__cfstring` | `0xf120` | `0xf180` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x5400` | `0x5450` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xdf4c` | `0xdf9c` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xbbb0` | `0xbc00` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x6628` | `0x6660` | **`+0x38`** |
| `__TEXT.__cstring` | `0x8941` | `0x896f` | **`+0x2e`** |
| `__AUTH_CONST.__objc_const` | `0x1cbd0` | `0x1cbf0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x151c` | `0x1520` | **`+0x4`** |

### Other Changes

```diff

-587.2.102.0.0
+587.2.104.0.0

-  Functions: 7481
+  Functions: 7490

-  CStrings:  3610
+  CStrings:  3621
CStrings:
+ "%@ render input drawing to %@/%@.png, "
+ "%@ render style drawing to %@/%@.png, "
+ "%@ render synthesis result to %@/%@.png, "
+ "%@ serialize input drawing to %@/%@.json, "
+ "%@ serialize style drawing to %@/%@.json, "
+ "%@ serialize synthesis result to %@/%@.json, "
+ "%@_%@_input_drawing"
+ "%@_%@_result"
+ "%@_%@_style_drawing"
+ "@\"NSArray\"8@?0"
+ "CHLogAllSynthesisRequestImages"
+ "Drawing writeImageToFile saving image at URL %@"
+ "Drawing writeImageToFile unable to create image destination at URL %@"
+ "Drawing writeImageToFile unable to render drawing with %lu strokes"
+ "Drawing writeImageToFile unable to write image at URL %@"
+ "png"
+ "public.png"
- "%@ serialize input drawing to %@/%@, "
- "%@ serialize style drawing to %@/%@, "
- "%@ serialize synthesis result to %@/%@, "
- "%@_%@_input_drawing.json"
- "%@_%@_result.json"
- "%@_%@_style_drawing.json"
```
