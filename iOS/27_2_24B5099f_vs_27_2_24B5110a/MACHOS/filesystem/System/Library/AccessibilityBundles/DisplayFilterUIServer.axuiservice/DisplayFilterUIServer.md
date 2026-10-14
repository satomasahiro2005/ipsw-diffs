## DisplayFilterUIServer

> `/System/Library/AccessibilityBundles/DisplayFilterUIServer.axuiservice/DisplayFilterUIServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2198` | `0x2a44` | **`+0x8ac`** |
| `__TEXT.__objc_stubs` | `0xac0` | `0xd20` | **`+0x260`** |
| `__TEXT.__objc_methname` | `0xf74` | `0x1178` | **`+0x204`** |
| `__TEXT.__cstring` | `0x172` | `0x284` | **`+0x112`** |
| `__DATA_CONST.__cfstring` | `0x1a0` | `0x260` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x330` | `0x3f0` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x450` | `0x4e8` | **`+0x98`** |
| `__DATA.__objc_const` | `0x640` | `0x6a0` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x1a0` | `0x200` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x484` | `0x4d4` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x110` | `0x138` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x4b6` | `0x4d7` | **`+0x21`** |
| `__DATA_CONST.__got` | `0xd0` | `0xe8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x118` | `0x128` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x24` | `0x2c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-3245.8.4.2.0
+3245.8.9.0.0

-  Functions: 51
-  Symbols:   93
-  CStrings:  233
+  Functions: 57
+  Symbols:   108
+  CStrings:  265
Symbols:
+ _AXInvertColorsSettingsEventFeatureClassicInvert
+ _AXInvertColorsSettingsEventFeatureSmartInvert
+ _CFAbsoluteTimeGetCurrent
+ _CGPathGetBoundingBox
+ _CGRectIsNull
+ _CGRectNull
+ _NSStringFromCGRect
+ _NSStringFromClass
+ __AXSInvertColorsSetEnabled
+ _objc_opt_class
+ _objc_opt_new
+ _objc_release_x27
+ _objc_release_x28
+ _objc_retain_x21
+ _objc_retain_x22
+ _objc_retain_x4
- _objc_retain
CStrings:
+ "@\"NSMutableArray\""
+ "B"
+ "Mask fully opaque; applying invert colors change"
+ "System aperture frames %@ -> exclusion %@"
+ "T@\"NSMutableArray\",&,N,V__pendingInvertColorsChanges"
+ "TB,N,V__invertColorsChangeInFlight"
+ "Transition mask state: rootView=%@ maskView=%@ alpha=%.2f hidden=%d aperture=%@ maskPathBounds=%@ window=%@ windowHidden=%d windowAlpha=%.2f windowLevel=%f"
+ "__invertColorsChangeInFlight"
+ "__pendingInvertColorsChanges"
+ "_applyInvertColorsChangeIsSmart:value:source:"
+ "_invertColorsChangeInFlight"
+ "_logMaskState"
+ "_pendingInvertColorsChanges"
+ "_processNextInvertColorsChangeIfNeeded"
+ "alpha"
+ "firstObject"
+ "frame"
+ "isHidden"
+ "isSmartInvert"
+ "layoutIfNeeded"
+ "mask"
+ "path"
+ "registerInvertColorsSettingsEventWithFeature:state:source:"
+ "removeObjectAtIndex:"
+ "setClassicInvertColors:"
+ "setLastSmartInvertColorsEnablement:"
+ "set_invertColorsChangeInFlight:"
+ "set_pendingInvertColorsChanges:"
+ "source"
+ "v20@0:8B16"
+ "v32@0:8B16B20@24"
+ "value"
+ "window"
+ "windowLevel"
- "_fadeDisplayForSmartInvertStartWithDuration:maskOpaqueCompletion:"
- "v32@0:8d16@?24"
```
