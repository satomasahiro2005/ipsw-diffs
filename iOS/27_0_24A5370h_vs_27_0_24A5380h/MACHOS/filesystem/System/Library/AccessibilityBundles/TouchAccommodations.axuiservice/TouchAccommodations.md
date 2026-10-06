## TouchAccommodations

> `/System/Library/AccessibilityBundles/TouchAccommodations.axuiservice/TouchAccommodations`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x73ec` | `0x7668` | **`+0x27c`** |
| `__TEXT.__objc_methname` | `0x24c6` | `0x25b0` | **`+0xea`** |
| `__TEXT.__objc_stubs` | `0x1d00` | `0x1dc0` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x7f4` | `0x854` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x6b3` | `0x709` | **`+0x56`** |
| `__DATA.__objc_selrefs` | `0x910` | `0x948` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x4d0` | `0x500` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2f0` | `0x318` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x278` | `0x290` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x270` | `0x288` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA.__objc_const` | `0xaa8` | `0xab0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-3232.3.0.0.0
+3234.5.0.0.0

-  Functions: 146
-  Symbols:   167
-  CStrings:  502
+  Functions: 153
+  Symbols:   171
+  CStrings:  510
Symbols:
+ _AXDeviceGetPixelBoundsForDisplayUUID
+ _AXDeviceGetScaleFactorForDisplayUUID
+ _CGRectIsEmpty
+ _OBJC_CLASS_$_NSArray
CStrings:
+ "_createProgressLayerWithColor:withFilterName:"
+ "_startProgressAnimationOnLayer:forHoldDuration:"
+ "arrayWithObjects:count:"
+ "eventProcessor:didUpdateTouchAccommodationsAtNormalizedPoint:displayIdentifier:"
+ "fixedCoordinateSpace"
+ "screen"
+ "setActiveSceneTrackingEnabled:forSceneClientIdentifier:"
+ "setStrokeEnd:"
+ "v48@0:8@\"AXTouchAccommodationsEventProcessor\"16{CGPoint=dd}24@\"NSString\"40"
+ "v48@0:8@16{CGPoint=dd}24@40"
- "@36@0:8@16@24B32"
- "_createProgressLayerWithColor:withFilterName:forHoldDuration:"
```
