## SignpostSupport

> `/System/Library/PrivateFrameworks/SignpostSupport.framework/SignpostSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1db0` | `—` | **`-0x1db0`** |
| `__DATA_DIRTY.__objc_data` | `0x1630` | `0x3390` | **`+0x1d60`** |
| `__AUTH_CONST.__objc_const` | `0x16d58` | `0x16c08` | **`-0x150`** |
| `__TEXT.__objc_methlist` | `0xa0a4` | `0xa014` | **`-0x90`** |
| `__TEXT.__text` | `0x775a4` | `0x7753c` | **`-0x68`** |
| `__AUTH_CONST.__cfstring` | `0x1cac0` | `0x1ca60` | **`-0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x3bc8` | `0x3b68` | **`-0x60`** |
| `__TEXT.__cstring` | `0x1a775` | `0x1a737` | **`-0x3e`** |
| `__DATA_CONST.__const` | `0x1448` | `0x1430` | **`-0x18`** |
| `__TEXT.__const` | `0x1a08` | `0x19f8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2550` | `0x2540` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0xf38` | `0xf2c` | **`-0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x530` | `0x528` | **`-0x8`** |

### Other Changes

```diff

-201.0.0.0.0
+202.0.0.0.0

-  Functions: 4114
-  Symbols:   7306
-  CStrings:  3923
+  Functions: 4103
+  Symbols:   7282
+  CStrings:  3920
Symbols:
+ -[SignpostUpdateSequenceInterval setThreadID:]
+ -[SignpostUpdateSequenceInterval threadID]
+ _OBJC_IVAR_$_SignpostUpdateSequenceInterval._threadID
+ __timeRatioForTimeIntervalArray:applyPerceptionAdjustments:.concurrentAdjustment
- -[SignpostAnimationInterval animationType]
- -[SignpostAnimationInterval firstFrameGraceTimeMs]
- -[SignpostSupportAnimationGraceTimeController defaultGraceTimeMs]
- -[SignpostSupportAnimationGraceTimeController gracetimeMsForSubsystem:category:name:]
- -[SignpostSupportAnimationGraceTimeController init]
- -[SignpostSupportAnimationGraceTimeController setAnimationType:forSubsystem:category:name:]
- -[SignpostSupportAnimationGraceTimeController setDefaultGraceTimeMs:]
- -[SignpostSupportAnimationGraceTimeController setFirstFrameGraceTimeMs:forSubsystem:category:name:]
- -[SignpostSupportAnimationGraceTimeController setUserInitiatedGraceTimeMs:]
- -[SignpostSupportAnimationGraceTimeController setUserInteractiveGraceTimeMs:]
- -[SignpostSupportAnimationGraceTimeController userInitiatedGraceTimeMs]
- -[SignpostSupportAnimationGraceTimeController userInteractiveGraceTimeMs]
- -[SignpostSupportObjectExtractor animationFirstFrameGraceTimeController]
- _OBJC_CLASS_$_SignpostSupportAnimationGraceTimeController
- _OBJC_IVAR_$_SignpostSupportAnimationGraceTimeController._defaultGraceTimeMs
- _OBJC_IVAR_$_SignpostSupportAnimationGraceTimeController._userInitiatedGraceTimeMs
- _OBJC_IVAR_$_SignpostSupportAnimationGraceTimeController._userInteractiveGraceTimeMs
- _OBJC_IVAR_$_SignpostSupportObjectExtractor._animationFirstFrameGraceTimeController
- _OBJC_METACLASS_$_SignpostSupportAnimationGraceTimeController
- __OBJC_$_INSTANCE_METHODS_SignpostSupportAnimationGraceTimeController
- __OBJC_$_INSTANCE_VARIABLES_SignpostSupportAnimationGraceTimeController
- __OBJC_$_PROP_LIST_SignpostSupportAnimationGraceTimeController
- __OBJC_CLASS_RO_$_SignpostSupportAnimationGraceTimeController
- __OBJC_METACLASS_RO_$_SignpostSupportAnimationGraceTimeController
- __timeRatioForTimeIntervalArray:applyPerceptionAdjustments:.concurrentAdjustement
- _kSignpostSupportDefaultFirstFrameGraceTimeMs
- _kSignpostSupportDefaultUserInitiatedFirstFrameGraceTimeMs
- _kSignpostSupportDefaultUserInteractiveFirstFrameGraceTimeMs
CStrings:
+ "Animation Interval \"%@\" [%llu - %llu]\nDuration: %.4fs\nTelemetry:%@\n%@%@%@"
- "Animation Interval \"%@\" [%llu - %llu]\nDuration: %.4fs\nTelemetry:%@\nAnimation Type: %@\n%@%@%@"
- "User Initiated"
- "User Interactive"
- "overridden"
```
