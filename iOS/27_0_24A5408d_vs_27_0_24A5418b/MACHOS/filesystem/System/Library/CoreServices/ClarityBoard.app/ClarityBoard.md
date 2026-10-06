## ClarityBoard

> `/System/Library/CoreServices/ClarityBoard.app/ClarityBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2941d8` | `0x295a00` | **`+0x1828`** |
| `__TEXT.__objc_methname` | `0x129e5` | `0x12c75` | **`+0x290`** |
| `__TEXT.__objc_stubs` | `0xc160` | `0xc380` | **`+0x220`** |
| `__DATA.__objc_const` | `0xa5c8` | `0xa770` | **`+0x1a8`** |
| `__TEXT.__oslogstring` | `0x7623` | `0x7783` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x582c` | `0x591c` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x19520` | `0x19600` | **`+0xe0`** |
| `__TEXT.__objc_methtype` | `0x4253` | `0x42ff` | **`+0xac`** |
| `__DATA.__objc_selrefs` | `0x4140` | `0x41e0` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x4350` | `0x43b0` | **`+0x60`** |
| `__TEXT.__const` | `0x277f8` | `0x27858` | **`+0x60`** |
| `__DATA.__objc_data` | `0x4ae0` | `0x4b30` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x3e90` | `0x3ee0` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x21b8` | `0x21e8` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x2720` | `0x2748` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x3f14` | `0x3f38` | **`+0x24`** |
| `__TEXT.__swift5_reflstr` | `0x3393` | `0x33b3` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x15f0` | `0x1608` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x398` | `0x3ac` | **`+0x14`** |
| `__TEXT.__objc_classname` | `0x1854` | `0x1867` | **`+0x13`** |
| `__DATA.__bss` | `0x6380` | `0x6390` | **`+0x10`** |
| `__TEXT.__cstring` | `0x359d` | `0x358f` | **`-0xe`** |
| `__DATA.__common` | `0xc90` | `0xc98` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x390` | `0x398` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x100` | `0x108` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2f4` | `0x2f8` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x318` | `0x31c` | **`+0x4`** |
| `__TEXT.__swift5_typeref` | `0x104a2` | `0x104a0` | **`-0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-168.0.0.0.0
+168.2.0.0.0

+  - /System/Library/PrivateFrameworks/SensorAccess.framework/SensorAccess

-  Functions: 5723
-  Symbols:   2162
-  CStrings:  4331
+  Functions: 5748
+  Symbols:   2170
+  CStrings:  4366
Symbols:
+ _CACurrentMediaTime
+ _CGColorGetConstantColor
+ _CGRectApplyAffineTransform
+ _CGRectGetMaxX
+ _CGRectGetMaxY
+ _NSStringFromCGSize
+ _OBJC_CLASS_$_SensorAccessIndicator
+ _kCGColorBlack
CStrings:
+ "CLBIndicatorLayers"
+ "Display %u cleared %{public}@ indicator"
+ "Display %u has no usable size (native %{public}@, layer %{public}@); leaving indicator rect unconverted"
+ "Display %u holding %{public}@ indicator %.3fs to serve its minimum on time"
+ "Display %u placed %{public}@ indicator at %{public}@ (center %{public}@ within %{public}@ of %{public}@, orientation %ld)"
+ "Display %u published no usable indicator position (%{public}@); not declaring"
+ "Display %u removed %{public}@ indicator after its minimum on time"
+ "Secure indicators aren't enforced here, so the StatusBar view keeps drawing its own."
+ "T@\"CALayer\",R,N,V_outlineLayer"
+ "T@\"CASecureIndicatorLayer\",R,N,V_dotLayer"
+ "T@\"NSString\",R,N,V_type"
+ "Td,R,N,V_dotPresentationTime"
+ "Tq,N,V_interfaceOrientation"
+ "_configPixelSize"
+ "_convertNativeRectToLayerSpace:"
+ "_dotCenterWithinAcceptedRect:"
+ "_dotLayer"
+ "_dotPresentationTime"
+ "_indicatorsByType"
+ "_interfaceOrientation"
+ "_makeIndicatorForType:"
+ "_outlineLayer"
+ "_positionOutlineLayer:forDotFrame:"
+ "_preferredPositionFromPositions:"
+ "_removeIndicatorAfterMinimumOnTime:"
+ "_replaceIndicatorForOrientationIfNeeded:"
+ "_setIndicatorActive:forType:"
+ "_upperTrailingTargetInNativeSpace"
+ "didUpdateDeviceOrientation"
+ "dotLayer"
+ "dotPresentationTime"
+ "initWithType:dotLayer:outlineLayer:"
+ "insertSublayer:below:"
+ "outlineLayer"
+ "pixelSize"
+ "removeFromLayerTree"
+ "secureIndicatorDisplaysByProfileID"
+ "secureIndicatorPolicyEnforced"
+ "setAllowsGroupOpacity:"
+ "setDefaultContext:"
+ "setPosition:"
+ "setSupportAppSceneRequests:"
+ "{CGPoint=dd}16@0:8"
+ "{CGPoint=dd}48@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}48@0:8{CGRect={CGPoint=dd}{CGSize=dd}}16"
+ "{CGSize=\"width\"d\"height\"d}"
- "%{public}s camera secure indicator on display %u"
- "%{public}s microphone secure indicator on display %u"
- "Cleared"
- "Declared"
- "Display %u had no valid indicator positions; using center fallback %{public}@"
- "Display %u valid indicator positions: %{public}@"
- "_cameraLayer"
- "_makeIndicatorLayerWithType:"
- "_microphoneLayer"
- "_positionIndicatorLayer:"
- "secureCameraIndicatorContextsByProfileID"
```
