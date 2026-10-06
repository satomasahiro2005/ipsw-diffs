## TSUtility

> `/System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSUtility.framework/TSUtility`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf68f0` | `0xe4f90` | **`-0x11960`** |
| `__TEXT.__cstring` | `0x16ed2` | `0x153f2` | **`-0x1ae0`** |
| `__TEXT.__objc_methlist` | `0xb5bc` | `0xabc4` | **`-0x9f8`** |
| `__AUTH_CONST.__objc_const` | `0x12dc8` | `0x123f0` | **`-0x9d8`** |
| `__TEXT.__unwind_info` | `0x5028` | `0x49c0` | **`-0x668`** |
| `__DATA_CONST.__objc_selrefs` | `0x5bd0` | `0x56c0` | **`-0x510`** |
| `__AUTH_CONST.__cfstring` | `0xca80` | `0xc640` | **`-0x440`** |
| `__AUTH.__objc_data` | `0x3c10` | `0x3a30` | **`-0x1e0`** |
| `__TEXT.__const` | `0x171e2` | `0x17022` | **`-0x1c0`** |
| `__AUTH_CONST.__auth_got` | `0x1710` | `0x1568` | **`-0x1a8`** |
| `__AUTH_CONST.__const` | `0x28d0` | `0x2770` | **`-0x160`** |
| `__DATA_CONST.__const` | `0x2478` | `0x23b8` | **`-0xc0`** |
| `__DATA.__bss` | `0x2430` | `0x2390` | **`-0xa0`** |
| `__DATA.__objc_ivar` | `0xd14` | `0xc9c` | **`-0x78`** |
| `__DATA_DIRTY.__objc_data` | `0x6e0` | `0x690` | **`-0x50`** |
| `__TEXT.__eh_frame` | `0x474` | `0x42c` | **`-0x48`** |
| `__TEXT.__gcc_except_tab` | `0x4d54` | `0x4d0c` | **`-0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x6b8` | `0x680` | **`-0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x600` | `0x5d0` | **`-0x30`** |
| `__DATA_CONST.__objc_superrefs` | `0x580` | `0x558` | **`-0x28`** |
| `__DATA_CONST.__got` | `0xc30` | `0xc48` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x1980` | `0x1968` | **`-0x18`** |
| `__DATA.__common` | `0x4c8` | `0x4b8` | **`-0x10`** |
| `__DATA.__data` | `0x9478` | `0x9468` | **`-0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x150` | `0x140` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x502` | `0x50a` | **`+0x8`** |

### Other Changes

```diff

-487.0.0.0.0
+488.0.0.0.0

+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSFeatureFlags.framework/TSFeatureFlags
+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSFundamentals.framework/TSFundamentals
+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSGeometry.framework/TSGeometry

-  Functions: 6211
-  Symbols:   2235
-  CStrings:  2830
+  Functions: 5675
+  Symbols:   1982
+  CStrings:  2692
Symbols:
+ _TSUAppEditInCat
+ _TSUAppEditInCat_init_token
+ _TSUAppEditInCat_log_t
+ _TSUFeatureFlagsCat
+ _TSUFeatureFlagsCat_init_token
+ _TSUFeatureFlagsCat_log_t
+ _TSUPXDBinary
+ _TSUPXDPackage
+ _TSUShapeGenerationCat
+ _TSUShapeGenerationCat_init_token
+ _TSUShapeGenerationCat_log_t
+ _swift_allocBox
+ _swift_allocError
+ _swift_dynamicCastMetatype
+ _swift_errorRelease
+ _swift_getDynamicType
+ _swift_getMetatypeMetadata
+ _swift_getObjectType
+ _swift_unknownObjectRetain
- _CGAffineTransformEqualToTransform
- _CGAffineTransformInvert
- _CGAffineTransformMakeRotation
- _CGContextAddCurveToPoint
- _CGContextAddLineToPoint
- _CGContextAddPath
- _CGContextBeginPath
- _CGContextClip
- _CGContextClipToRect
- _CGContextClipToRectSafe
- _CGContextClosePath
- _CGContextEOClip
- _CGContextEOFillPath
- _CGContextGetCTM
- _CGContextMoveToPoint
- _CGContextSetFlatness
- _CGContextSetLineCap
- _CGContextSetLineDash
- _CGContextSetLineJoin
- _CGContextSetLineWidth
- _CGContextSetMiterLimit
- _CGContextStrokePath
- _CGLineCapToTSULineCap
- _CGLineJoinToTSULineJoinStyle
- _CGPathAddArc
- _CGPathAddArcSafe
- _CGPathAddArcToPoint
- _CGPathAddArcToPointSafe
- _CGPathAddCurveToPoint
- _CGPathAddCurveToPointSafe
- _CGPathAddEllipseInRect
- _CGPathAddEllipseInRectSafe
- _CGPathAddLineToPoint
- _CGPathAddLineToPointSafe
- _CGPathAddPath
- _CGPathAddPathSafe
- _CGPathAddQuadCurveToPoint
- _CGPathAddQuadCurveToPointSafe
- _CGPathAddRect
- _CGPathAddRectSafe
- _CGPathAddRects
- _CGPathAddRectsSafe
- _CGPathAddRelativeArc
- _CGPathAddRelativeArcSafe
- _CGPathAddRoundedRect
- _CGPathAddRoundedRectSafe
- _CGPathApply
- _CGPathCloseSubpath
- _CGPathContainsPoint
- _CGPathContainsPointSafe
- _CGPathCreateCopy
- _CGPathCreateCopyByStrokingPath
- _CGPathCreateCopyByStrokingPathSafe
- _CGPathCreateCopyByTransformingPath
- _CGPathCreateCopyByTransformingPathSafe
- _CGPathCreateMutable
- _CGPathCreateMutableCopyByTransformingPath
- _CGPathCreateMutableCopyByTransformingPathSafe
- _CGPathCreateWithEllipseInRect
- _CGPathCreateWithEllipseInRectSafe
- _CGPathCreateWithRect
- _CGPathCreateWithRectSafe
- _CGPathGetPathBoundingBox
- _CGPathMoveToPoint
- _CGPathMoveToPointSafe
- _CGPathRetain
- _CGRectContainsRect
- _CGRectGetHeight
- _CGRectGetMaxX
- _CGRectGetMinX
- _CGRectGetWidth
- _CGRectInset
- _CGRectIntegral
- _CGRectIsInfinite
- _CGRectOffset
- _CGRectStandardize
- _NSStringFromCGRect
- _NSStringFromProtocol
- _NSZoneRealloc
- _OBJC_CLASS_$_TSUBezierPath
- _OBJC_METACLASS_$_TSUAssertionHandler
- _OBJC_METACLASS_$_TSUBezierPath
- _TSUAddPoints
- _TSUAddSizes
- _TSUAffineTransformForFlips
- _TSUAffineTransformIsRectilinear
- _TSUAliasRound
- _TSUAliasRoundedPoint
- _TSUAngleFromDelta
- _TSUAssertCat
- _TSUAssertCat_init_token
- _TSUAssertCat_log_t
- _TSUAveragePoints
- _TSUAxisAnglesToEulerAngles
- _TSUCFTypeCast
- _TSUCGAffineTransformIsValid
- _TSUCGFloatIsValid
- _TSUCeilSize
- _TSUCenterOfRect
- _TSUCenterRectOverRect
- _TSUCheckedClassAndProtocolCast
- _TSUCheckedProtocolCast
- _TSUCheckedStaticCast
- _TSUCheckedStaticProtocolCast
- _TSUClamp
- _TSUClampPointInRect
- _TSUClampPointOnLineToRect
- _TSUClassAndProtocolCast
- _TSUCrossPoints
- _TSUDefaultCat
- _TSUDeltaApplyAffineTransform
- _TSUDeltaFromAngle
- _TSUDistance
- _TSUDistanceSquared
- _TSUDistanceToRect
- _TSUDistanceToRectSquared
- _TSUDotPoints
- _TSUEdgeInsetsZero
- _TSUEqualPointsWithThreshold
- _TSUEqualRectsWithThreshold
- _TSUEqualSizesWithThreshold
- _TSUErrorCat
- _TSUEulerAnglesToAxisAngles
- _TSUFitOrFillSizeInRect
- _TSUFitOrFillSizeInSize
- _TSUFitSizeOfLineInSize
- _TSUFloorForScale
- _TSUFlooredPoint
- _TSUFlooredSize
- _TSUGetLowerLeft
- _TSUGetLowerRight
- _TSUGetUpperLeft
- _TSUGetUpperRight
- _TSUGrowRectToPoint
- _TSUIntegralRectForScale
- _TSUIntersectsRect
- _TSUIsTransformAxisAligned
- _TSUIsTransformAxisAlignedUnflipped
- _TSUIsTransformAxisAlignedWithObjectSize
- _TSUIsTransformAxisAlignedWithThreshold
- _TSUIsTransformFlipped
- _TSULineCapToCGLineCap
- _TSULineIntersectsRect
- _TSULineJoinToCGLineJoin
- _TSULogBacktrace
- _TSULogCat_IsCategoryEnabled
- _TSUMixAnglesInDegrees
- _TSUMixAnglesInRadians
- _TSUMixBOOLs
- _TSUMixFloats
- _TSUMixPoints
- _TSUMixRects
- _TSUMixSizes
- _TSUMultiplyPointBySize
- _TSUMultiplyPointScalar
- _TSUMultiplyRectScalar
- _TSUMultiplySizeByPoint
- _TSUMultiplySizeScalar
- _TSUNearlyCollinearPoints
- _TSUNearlyContainsRect
- _TSUNearlyEqualPoints
- _TSUNearlyEqualRects
- _TSUNearlyEqualSizes
- _TSUNearlyEqualTransforms
- _TSUNonNegativeSize
- _TSUNormalize3DRotationInRadians
- _TSUNormalizeAngleAboutZeroInRadians
- _TSUNormalizeAngleInDegrees
- _TSUNormalizeAngleInRadians
- _TSUNormalizeAngleInRadiansProvidingRange
- _TSUNormalizePoint
- _TSUNormalizedPointInRect
- _TSUNormalizedSubrectInRect
- _TSUOriginRotate
- _TSUPercentRectInsideRect
- _TSUPointFromNormalizedRect
- _TSUPointHasNaNComponents
- _TSUPointInRectInclusive
- _TSUPointInfinity
- _TSUPointIsFinite
- _TSUPointIsNull
- _TSUPointLength
- _TSUPointNull
- _TSUPointOnCurve
- _TSUPointOne
- _TSUPointSquaredLength
- _TSUPointsAlmostEqual
- _TSUProtocolHasInstanceMethod
- _TSURandomBetween
- _TSURectByExpandingBoundingRectToContentRect
- _TSURectFromNormalizedSubrect
- _TSURectGetMaxPoint
- _TSURectGetMinPoint
- _TSURectHasNaNComponents
- _TSURectIsFinite
- _TSURectUnit
- _TSURectWithCenterAndSize
- _TSURectWithInverseNormalizedRect
- _TSURectWithOriginAndSize
- _TSURectWithPoints
- _TSURectWithSize
- _TSURectWithSizeAlignedToRect
- _TSURotatePoint
- _TSURotatePoint90Degrees
- _TSURound
- _TSURoundForScale
- _TSURoundedMaxY
- _TSURoundedPoint
- _TSURoundedPointForScale
- _TSURoundedRect
- _TSURoundedRectForScale
- _TSURoundedSize
- _TSUScaleRectAroundPoint
- _TSUScaleSizeWithinSize
- _TSUSetCrashReporterInfov
- _TSUShiftConstrainDelta
- _TSUShrinkSizeToFitInArea
- _TSUShrinkSizeToFitInSize
- _TSUSizeHasNaNComponents
- _TSUSizeInfinity
- _TSUSizeIsEmpty
- _TSUSizeIsFinite
- _TSUSizeMax
- _TSUSizeMin
- _TSUSizeUnit
- _TSUSubtractPoints
- _TSUSubtractSizes
- _TSUTransform3DNearlyEqualToTransform
- _TSUTransform3DNearlyEqualToTransformWithTolerance
- _TSUTransformAngleInDegrees
- _TSUTransformAngleInRadians
- _TSUTransformConvertForNewOrigin
- _TSUTransformConvertingRectToRect
- _TSUTransformConvertingRectToRectAtPercent
- _TSUTransformFromTransformSpace
- _TSUTransformHasNaNComponents
- _TSUTransformMakeFree
- _TSUTransformMixAffineTransforms
- _TSUTransformMixDouble4x4s
- _TSUTransformMixTransform3Ds
- _TSUTransformScale
- _TSUTransformXYScale
- _TSUTransformedCornersOfRect
- _TSUTransformsDifferOnlyByTranslation
- _TSUTranslatedRectMaximizingOverlapWithRect
- _TSUUnionRect
- _TSUWarningCat
- _TSUWarningCat_init_token
- _TSUWarningCat_log_t
- _UIGraphicsGetCurrentContext
- ___invert_d4
- ___sincos_stret
- ___sincosf_stret
- ___snprintf_chk
- _asin
- _asprintf
- _atan2
- _atan2f
- _backtrace
- _backtrace_symbols
- _cos
- _dladdr
- _fflush
- _fmod
- _getsegmentdata
- _matrix_identity_double4x4
- _objc_setProperty_atomic
- _os_log_create
- _protocol_getMethodDescription
- _random
- _sin
- _swift_dynamicCast
CStrings:
+ "-[TSUAssetColorMap addEntriesFromDictionary:transformKeyBlock:]"
+ "-[TSUAssetColorMap addEntriesFromDictionary:transformKeyBlock:]_block_invoke"
+ "Did not expect nil NSUIApplication!"
+ "TSUAppEditInCat"
+ "TSUFeatureFlagsCat"
+ "TSUShapeGenerationCat"
+ "com.pixelmatorteam.pixelmator.document.binary"
+ "com.pixelmatorteam.pixelmator.document.package"
- "\t%s\n"
- "\n    %f %f %f %f %f %f curveto"
- "\n    %f %f lineto"
- "\n    %f %f moveto"
- "\n    closepath"
- "\n  Bounds: %@"
- "\n  Control point bounds: %@"
- "#%@"
- "%"
- "%@ %@[%d] %@ %@ %s:%d %@"
- "%{public}"
- "(%s @ %p)"
- "+[TSUAssert logBacktrace]"
- "+[TSUBezierPath bezierPathWithCGPath:]"
- "-[TSUAssetColorMap addEntriesFromPlistBasename:transformKeyBlock:]_block_invoke"
- "-[TSUBezierPath appendBezierPathWithArcWithCenter:radius:startAngle:endAngle:clockwise:]"
- "-[TSUBezierPath cString]"
- "-[TSUBezierPath calculateLengthOfElement:]"
- "-[TSUBezierPath controlPointBounds]"
- "-[TSUBezierPath copyWithZone:]"
- "-[TSUBezierPath currentPoint]"
- "-[TSUBezierPath curveToPoint:controlPoint1:controlPoint2:]"
- "-[TSUBezierPath curveToPoint:controlPoint:]"
- "-[TSUBezierPath elementAtIndex:allPoints:]"
- "-[TSUBezierPath elementAtIndex:associatedPoints:]"
- "-[TSUBezierPath initWithCString:]"
- "-[TSUBezierPath isClockwise]"
- "-[TSUBezierPath lengthOfElement:]"
- "-[TSUBezierPath lengthToElement:]"
- "-[TSUBezierPath lineToPoint:]"
- "-[TSUBezierPath p_appendPointsInRange:fromBezierPath:countingSubpaths:]"
- "-[TSUBezierPath setAssociatedPoints:atIndex:]"
- "-[TSUBezierPath(TSUAdditions) appendBezierPathWithArcWithEllipseBounds:startAngle:swingAngle:angleType:startNewPath:]"
- "-[TSUBezierPath(TSUAdditions) appendBezierPathWithArcWithEllipseBounds:startRadialVector:endRadialVector:angleSign:startNewPath:]"
- "-[TSUBezierPath(TSUBezierPathDevicePrimitives) _addPathSegment:point:]"
- "-[TSUBezierPath(TSUBezierPathDevicePrimitives) _deviceClosePath]"
- "-[TSUBezierPath(TSUBezierPathDevicePrimitives) _deviceCurveToPoint:controlPoint1:controlPoint2:elementLength:]"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/iWorkImport/shared/utility/TSUBezierPath.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/iWorkImport/shared/utility/TSUBezierPathAdditions.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/iWorkImport/shared/utility/TSUCast.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/iWorkImport/shared/utility/TSUGeometry.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/iWorkImport/shared/utility/TSUMath.m"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/iWorkImport/shared/utility/TSUSafeCGWrappers.m"
- "<REDACT %@ REDACT>"
- "<REDACT %s REDACT>"
- "<REDACT .*? REDACT>"
- "<callStacksSymbols repeated on same thread>"
- "<redacted>"
- "A CG call was elided because of an invalid parameter."
- "Angle out of range"
- "Backtrace:\n"
- "Bezier path string contained unknown elmt."
- "C %f %f %f %f %f %f"
- "CGFloat TSUClamp(CGFloat, CGFloat, CGFloat)"
- "CGFloat TSUEllipseParametricAngleWithPolarAngle(CGFloat, CGFloat, CGFloat)"
- "CGPoint p_TSUIntersectionPointOfLineWithRect(CGPoint, CGPoint, CGRect)"
- "CGRect TSURoundedRectForScale(CGRect, CGFloat)"
- "Can not determine control point bounds for an empty path."
- "Can not get the current point of an empty path."
- "ChartFillAssetColors"
- "Defaults"
- "Did not expect nil UIApplication!"
- "Extra index (%zd) must be within extra segment bounds [0, %zd)."
- "Fatal Assertion failure: %{public}s %{public}s:%d Can not determine control point bounds for an empty path."
- "Fatal Assertion failure: %{public}s %{public}s:%d Can not get the current point of an empty path."
- "Fatal Assertion failure: %{public}s %{public}s:%d Extra index (%zd) must be within extra segment bounds [0, %zd)."
- "Fatal Assertion failure: %{public}s %{public}s:%d Given index (%zd) must be within bounds [0, %zd)."
- "Fatal Assertion failure: %{public}s %{public}s:%d Given index (%zd) must not be negative."
- "Fatal Assertion failure: %{public}s %{public}s:%d Invalid Base64 encoded string at %tu: %d"
- "Fatal Assertion failure: %{public}s %{public}s:%d Missing extra segments."
- "Fatal Assertion failure: %{public}s %{public}s:%d Unable to add a curve when there is no current point."
- "Fatal Assertion failure: %{public}s %{public}s:%d Unable to add a line when there is no current point."
- "Fatal Assertion failure: %{public}s %{public}s:%d angle1 should not be infinte or NaN (%f)"
- "Fatal Assertion failure: %{public}s %{public}s:%d angle2 should not be infinte or NaN (%f)"
- "Fatal Assertion failure: %{public}s %{public}s:%d sfr_extraSegments could not NSZoneRealloc. No memory"
- "Fatal Assertion failure: %{public}s %{public}s:%d sfr_head could not NSZoneRealloc. No memory (when reallocing sfr_elementLength)"
- "Fatal Assertion failure: %{public}s %{public}s:%d sfr_head could not NSZoneRealloc. No memory (when reallocing sfr_head)"
- "Given index (%zd) must be within bounds [0, %zd)."
- "Given index (%zd) must not be greater than or equal to max element (%zd)"
- "Given index (%zd) must not be negative."
- "Invalid Base64 encoded string at %tu: %d"
- "L %f %f"
- "M %f %f"
- "Missing extra segments."
- "Only the first element of the arc should be a moveto"
- "Path should be flat. Illegal TSUCurveToBezierPathElement."
- "Point append range is out of range of available points."
- "Something is wrong with this bezier path!"
- "TSUAssertCat"
- "TSUBezierPath <%p>"
- "TSUCrash"
- "TSULogCatQueue"
- "TSULogCatYES"
- "TSUSetCrashReporterInfo: unknown reason"
- "TSUStdioLogSinkQueue"
- "TSUWarningCat"
- "Terminating application due to %@"
- "The arc shouldn't contain close_subpath elements"
- "The arc shouldn't contain lineto elements"
- "Unable to add a curve when there is no current point."
- "Unable to add a line when there is no current point."
- "Unexpected angle sign"
- "Unexpected object type %{public}@ in checked cast to multiple protocols"
- "Unexpected object type %{public}@ in checked cast to protocol %{public}@. This is a serious problem and could lead to a crash, or worse."
- "Unexpected object type %{public}@ in checked dynamic cast to %{public}@"
- "Unexpected object type %{public}@ in checked dynamic cast to class %{public}@ and 1 or more protocols"
- "Unexpected object type %{public}@ in checked static cast to %{public}@.  This is a serious problem and could lead to a crash, or worse."
- "Unhandled intersection scenario"
- "Unhandled path element type"
- "[Debug]"
- "[Error]"
- "[Fault]"
- "[Info]"
- "[Notice]"
- "__TEXT"
- "angle1 should not be infinte or NaN (%f)"
- "angle2 should not be infinte or NaN (%f)"
- "buffer too small for path element string"
- "cannot give scale = 0 for TSURoundedRectForScale!"
- "com.apple.iwork"
- "copiedPath->sfr_elementLength"
- "copiedPath->sfr_extraSegments"
- "copiedPath->sfr_head"
- "copiedPath->sfr_path"
- "id TSUCheckedClassAndProtocolCast(id<NSObject>, Class, NSUInteger, ...)"
- "id TSUCheckedDynamicCast(Class, id<NSObject>)"
- "id TSUCheckedProtocolCast(id<NSObject>, NSUInteger, ...)"
- "id TSUCheckedStaticCast(Class, id<NSObject>)"
- "id TSUCheckedStaticProtocolCast(Protocol *, id<NSObject>)"
- "lineWidth (%f) should be greater than zero."
- "loadaddr"
- "logBacktrace_lastStackAddress"
- "max > min!"
- "result->sfr_path"
- "sfr_extraSegments could not NSZoneRealloc. No memory"
- "sfr_head could not NSZoneRealloc. No memory (when reallocing sfr_elementLength)"
- "sfr_head could not NSZoneRealloc. No memory (when reallocing sfr_head)"
- "sfr_lastSubpathIndex >= 0"
- "uint8_t decodeBase64CharAndShiftOffset(const char, NSUInteger &)"
- "uuid"
- "v20@?0@\"NSString\"8B16"
- "v32@?0{CGPoint=dd}8d24"
- "v40@?0i8@\"NSString\"12r*20i28@\"NSString\"32"
- "void TSUNotifyCGAssertionAvoided()"
- "void _SFRSetLineWidth(CGContextRef, CGFloat)"
- "yyyy-MM-dd HH:mm:ss.SSS"
```
