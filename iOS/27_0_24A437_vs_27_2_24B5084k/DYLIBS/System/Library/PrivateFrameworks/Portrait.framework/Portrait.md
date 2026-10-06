## Portrait

> `/System/Library/PrivateFrameworks/Portrait.framework/Portrait`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x985a0` | `0x99318` | **`+0xd78`** |
| `__TEXT.__oslogstring` | `0x5e30` | `0x6133` | **`+0x303`** |
| `__TEXT.__objc_methlist` | `0xa0c4` | `0xa15c` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0x1e5a8` | `0x1e620` | **`+0x78`** |
| `__DATA_CONST.__objc_selrefs` | `0x5548` | `0x55a0` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x21a0` | `0x21b8` | **`+0x18`** |
| `__TEXT.__const` | `0x20b00` | `0x20b10` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1918` | `0x1920` | **`+0x8`** |
| `__TEXT.__cstring` | `0x52dd` | `0x52e3` | **`+0x6`** |

### Other Changes

```diff

-560.22.2.0.0
+560.40.3.0.0

-  Functions: 4109
-  Symbols:   7003
-  CStrings:  1518
+  Functions: 4122
+  Symbols:   7015
+  CStrings:  1528
Symbols:
+ -[PTCinematographyPostcaptureRefinement _advanceToInputFrameNearestTime:]
+ -[PTCinematographyPostcaptureRefinement _checkForInputStallAtTime:]
+ -[PTCinematographyPostcaptureRefinement _inputFrameSpacing]
+ -[PTCinematographyPostcaptureRefinement _lastProcessedInputFrame]
+ -[PTCinematographyPostcaptureRefinement didReportInputStall]
+ -[PTCinematographyPostcaptureRefinement firstInputTimeWithoutOutput]
+ -[PTCinematographyPostcaptureRefinement lastProcessedInputFrameIndex]
+ -[PTCinematographyPostcaptureRefinement processNextDisparityBuffer:atTime:]
+ -[PTCinematographyPostcaptureRefinement setDidReportInputStall:]
+ -[PTCinematographyPostcaptureRefinement setFirstInputTimeWithoutOutput:]
+ -[PTCinematographyPostcaptureRefinement setLastProcessedInputFrameIndex:]
+ -[PTPixelBufferCache removePixelBufferForTime:withinTolerance:]
+ _OBJC_IVAR_$_PTCinematographyPostcaptureRefinement._didReportInputStall
+ _OBJC_IVAR_$_PTCinematographyPostcaptureRefinement._firstInputTimeWithoutOutput
+ _OBJC_IVAR_$_PTCinematographyPostcaptureRefinement._lastProcessedInputFrameIndex
- -[PTCinematographyPostcaptureRefinement _priorInputFrame]
- _OBJC_IVAR_$_PTDisparityFilterDEMA_LKT._erodeMonocularDisparity
- _OUTLINED_FUNCTION_11
CStrings:
+ "Base decision filtering: %lu decisions in, %lu out"
+ "Cinematography: fast (per-frame metadata sampler, no decisions)"
+ "Cinematography: refined (generation %lu, %lu frames, %lu decisions)"
+ "Cinematography: snapshot (generation %lu, %lu frames, %lu decisions)"
+ "Input time %@ is not within half a frame of any script frame (nearest is %@); ignoring disparity buffer"
+ "Input time %@ precedes expected input time %@; ignoring disparity buffer"
+ "No frame near input time %@ to apply disparity buffer to"
+ "No output frame after inputs spanning %.2fs from %@; inputs may be too sparse (about 24 per second of source are needed)"
+ "No timestamp within tolerance %f seconds of the requested timestamp found in cache"
+ "Skipping %lu input frame(s) to reach input time %@"
+ "Tolerance passed to removePixelBufferForTime:withinTolerance: must be numeric, finite and non-negative"
+ "lastProcessedInputFrameIndex"
- "PTDisparityFilterDEMA_LKT enabling disparity erosion with strength: %.2f"
- "PortTypeFrontSuperWide"
```
