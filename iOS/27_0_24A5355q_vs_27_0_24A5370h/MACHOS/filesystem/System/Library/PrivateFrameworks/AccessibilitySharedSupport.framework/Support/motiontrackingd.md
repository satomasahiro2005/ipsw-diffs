## motiontrackingd

> `/System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/Support/motiontrackingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29834` | `0x2a924` | **`+0x10f0`** |
| `__TEXT.__objc_methname` | `0x9244` | `0x9609` | **`+0x3c5`** |
| `__TEXT.__objc_stubs` | `0x6ec0` | `0x71e0` | **`+0x320`** |
| `__TEXT.__oslogstring` | `0x21b9` | `0x2455` | **`+0x29c`** |
| `__TEXT.__cstring` | `0x217a` | `0x2268` | **`+0xee`** |
| `__DATA.__objc_selrefs` | `0x2050` | `0x2120` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x2ebc` | `0x2f84` | **`+0xc8`** |
| `__DATA.__objc_const` | `0x4aa0` | `0x4b58` | **`+0xb8`** |
| `__TEXT.__objc_methtype` | `0x1dd0` | `0x1e4c` | **`+0x7c`** |
| `__DATA.__data` | `0x7f0` | `0x850` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x800` | `0x7a0` | **`-0x60`** |
| `__DATA_CONST.__got` | `0x3f0` | `0x418` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x9c8` | `0x9f0` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x549` | `0x56c` | **`+0x23`** |
| `__TEXT.__auth_stubs` | `0x9f0` | `0xa00` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x3cc` | `0x3d8` | **`+0xc`** |
| `__TEXT.__gcc_except_tab` | `0xa68` | `0xa5c` | **`-0xc`** |
| `__DATA_CONST.__auth_got` | `0x508` | `0x510` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xa8` | `0xb0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-576.1.0.0.0
+579.1.0.0.0

-  Functions: 1037
-  Symbols:   299
-  CStrings:  2173
+  Functions: 1053
+  Symbols:   305
+  CStrings:  2221
Symbols:
+ _CGRectGetMidY
+ _OBJC_CLASS_$_CADisplay
+ _OBJC_CLASS_$_FBSActiveInterfaceOrientationObserver
+ _kCADisplayOrientationRotation0
+ _kCADisplayOrientationRotation180
+ _kCADisplayOrientationRotation270
+ _kCADisplayOrientationRotation90
- _OBJC_CLASS_$_FBSOrientationObserver
CStrings:
+ "%s display id=%u name=%{public}@ uniqueId=%{public}@; physicalSize: %f x %f in; bounds: %f x %f px; pointScale: %f; pitch: %f dpi; screen size: %f x %f cm; camera offset: %f, %f cm; displayRotation=%d"
+ "%s: CADisplay physicalSize is invalid: %f x %f"
+ "%s: display is nil"
+ "%s: empty bounds from CADisplay %u"
+ "%s: failed to compute screen size from CADisplay; gaze coordinates will be incorrect"
+ "%s: invalid bounds in points for alt display: %f x %f"
+ "%s: no CADisplay available for identity %@"
+ "%s: no CADisplay matched displayID %u; falling back to mainDisplay"
+ "%s: unrecognized value %{public}@"
+ "%s: updating to new screen bounds: %@ (display %u, identity %@)"
+ "+[AXMTUtilities displayForDisplayIdentity:]"
+ "-[AXMTUtilities _updateScreenBoundsForActiveDisplayIdentity:]"
+ "-[AXMTVisionKitEyeTracker _computeScreenAndCameraPositionsForDisplayIdentity:]"
+ "-[AXMTVisionKitEyeTracker _computeScreenSize:cameraOffset:forCADisplay:]"
+ "<nil>"
+ "@\"CADisplay\""
+ "@\"FBSActiveInterfaceOrientationObserver\""
+ "@\"FBSDisplayIdentity\""
+ "AXMTUtilities:_handleActiveInterfaceOrientationState: %ld"
+ "AXMTUtilities:registerActiveDisplayListener: %@"
+ "AXMTUtilities:unregisterActiveDisplayListener: %@"
+ "AXMTUtilitiesActiveDisplayListener"
+ "B40@0:8o^{CGSize=dd}16o^{CGVector=dd}24@32"
+ "F\""
+ "T@\"CADisplay\",&,V__activeDisplay"
+ "T@\"FBSActiveInterfaceOrientationObserver\",&,N,V__activeInterfaceOrientationObserver"
+ "T@\"FBSDisplayIdentity\",C,N,V_activeDisplayIdentity"
+ "T@\"NSPointerArray\",&,N,V__activeDisplayListeners"
+ "__activeDisplay"
+ "__activeDisplayListeners"
+ "__activeInterfaceOrientationObserver"
+ "_activateActiveInterfaceOrientationObserver"
+ "_activeDisplay"
+ "_activeDisplayIdentity"
+ "_activeDisplayListeners"
+ "_activeInterfaceOrientationObserver"
+ "_computeScreenAndCameraPositionsForDisplayIdentity:"
+ "_computeScreenSize:cameraOffset:forCADisplay:"
+ "_handleActiveInterfaceOrientationState:"
+ "_tearDownActiveInterfaceOrientationObserver"
+ "_updateScreenBoundsForActiveDisplayIdentity:"
+ "activateWithStateUpdateHandler:"
+ "activeDisplayIdentity"
+ "activeInterfaceOrientationState"
+ "axmtUtilities_activeDisplayDidChangeWithDisplayIdentity:"
+ "currentOrientation"
+ "displayForDisplayIdentity:"
+ "displayID"
+ "displayId"
+ "displayIdentity"
+ "displays"
+ "int _AXMTRotationDegreesFromCADisplayOrientationString(NSString * _Nullable __strong)"
+ "interfaceOrientation"
+ "mainDisplay"
+ "name"
+ "nativeOrientation"
+ "physicalSize"
+ "pointScale"
+ "registerActiveDisplayListener:"
+ "setActiveDisplayIdentity:"
+ "set_activeDisplay:"
+ "set_activeDisplayListeners:"
+ "set_activeInterfaceOrientationObserver:"
+ "totalRotationDegreesForActiveDisplay"
+ "uniqueId"
+ "unregisterActiveDisplayListener:"
+ "v16@?0@\"FBSActiveInterfaceOrientationStateUpdate\"8"
+ "v24@0:8@\"FBSDisplayIdentity\"16"
- "%s offset %f, %f; screen size: %f * %f"
- "%s pitch %d, width %d, height %d, scale %f --> %@"
- "-[AXMTVisionKitEyeTracker _computeScreenAndCameraPositions]"
- "@\"FBSOrientationObserver\""
- "AXMTUtilities:_interfaceOrientationChanged: %ld"
- "E"
- "T@\"FBSOrientationObserver\",&,N,V__orientationObserver"
- "__orientationObserver"
- "_computeScreenAndCameraPositions"
- "_interfaceOrientationChanged:"
- "_orientationObserver"
- "activeInterfaceOrientation"
- "main-screen-height"
- "main-screen-pitch"
- "main-screen-scale"
- "main-screen-width"
- "orientation"
- "setHandler:"
- "set_orientationObserver:"
- "v16@?0@\"FBSOrientationUpdate\"8"
```
