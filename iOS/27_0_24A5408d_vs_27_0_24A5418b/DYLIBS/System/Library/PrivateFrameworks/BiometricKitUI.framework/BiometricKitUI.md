## BiometricKitUI

> `/System/Library/PrivateFrameworks/BiometricKitUI.framework/BiometricKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x10700` | `0x10720` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x9fc` | `0xa00` | **`+0x4`** |
| `__TEXT.__text` | `0x70538` | `0x70534` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-684.0.0.0.0
+684.100.0.0.0

-  Symbols:   4578
+  Symbols:   4579
Symbols:
+ _OBJC_IVAR_$_BKUIPearlEnrollView._currentRawPitch
+ _OBJC_IVAR_$_BKUIPearlEnrollView._lastLoggedCenterBinPitch
- _OBJC_IVAR_$_BKUIPearlEnrollView._lastLoggedCenterBinCorrectedPitch
Functions:
~ -[BKUIPearlEnrollView initWithFrame:videoCaptureSession:inSheet:positioningGuideView:squareNeedsPositionLayout:] : 2144 -> 2160
~ -[BKUIPearlEnrollView resetPitchCorrection] : 404 -> 420
~ -[BKUIPearlEnrollView setPitch:yaw:] : 1156 -> 1132
~ -[BKUIPearlEnrollView _updateRaiseLowerGuidanceLabelIfNeededForPitch:] : 464 -> 452
CStrings:
+ "centerBin rawPitch %0.2f, window [%0.2f, %0.2f] (pitchCorrection %0.2f deliberately not applied)"
+ "pitch %0.2f vs window [%0.2f, %0.2f] -> %s (pitchCorrection %0.2f not applied to guidance)"
+ "\xf0\xf0\x92"
- "centerBin correctedPitch %0.2f (rawPitch %0.2f - pitchCorrection %0.2f), window [%0.2f, %0.2f]"
- "correctedPitch %0.2f (rawPitch %0.2f - pitchCorrection %0.2f) vs window [%0.2f, %0.2f] -> %s"
- "\xf0\xf0\x82"
```
