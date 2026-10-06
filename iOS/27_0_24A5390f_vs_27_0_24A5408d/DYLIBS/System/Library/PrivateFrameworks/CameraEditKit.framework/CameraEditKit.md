## CameraEditKit

> `/System/Library/PrivateFrameworks/CameraEditKit.framework/CameraEditKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41f50` | `0x422d8` | **`+0x388`** |
| `__AUTH_CONST.__objc_intobj` | `0x558` | `0x588` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1740` | `0x1760` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x518` | `0x528` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3490` | `0x34a0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x142e` | `0x143e` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x13c0` | `0x13c8` | **`+0x8`** |

### Other Changes

```diff

-4174.0.0.0.0
+4177.22.3.0.0

-  Functions: 2058
-  Symbols:   3384
-  CStrings:  266
+  Functions: 2059
+  Symbols:   3387
+  CStrings:  267
Symbols:
+ +[CEKFluidBehaviorUtilities animatablePropertyWithView:functionalCompletion:]
+ +[CEKFluidBehaviorUtilities animatablePropertyWithView:milestonePassingTest:passedBlock:]
+ +[CEKFluidBehaviorUtilities animatablePropertyWithView:progressMilestones:block:]
+ +[CEKFluidBehaviorUtilities floatAnimatablePropertyWithView:initialValue:cancelableFrameCallback:]
+ +[CEKFluidBehaviorUtilities rectAnimatablePropertyWithView:initialValue:cancelableFrameCallback:]
+ +[CEKFluidBehaviorUtilities vector2DAnimatablePropertyWithView:initialValue:cancelableFrameCallback:]
+ GCC_except_table46
+ _CEKStylisticNumeralFontOfSizeWeight
+ ___101+[CEKFluidBehaviorUtilities vector2DAnimatablePropertyWithView:initialValue:cancelableFrameCallback:]_block_invoke
+ ___77+[CEKFluidBehaviorUtilities animatablePropertyWithView:functionalCompletion:]_block_invoke
+ ___81+[CEKFluidBehaviorUtilities animatablePropertyWithView:progressMilestones:block:]_block_invoke
+ ___89+[CEKFluidBehaviorUtilities animatablePropertyWithView:milestonePassingTest:passedBlock:]_block_invoke
+ ___97+[CEKFluidBehaviorUtilities rectAnimatablePropertyWithView:initialValue:cancelableFrameCallback:]_block_invoke
+ _kCTFontOpenTypeFeatureTag
+ _kCTFontOpenTypeFeatureValue
- +[CEKFluidBehaviorUtilities animatablePropertyWithFunctionalCompletion:]
- +[CEKFluidBehaviorUtilities animatablePropertyWithMilestonePassingTest:passedBlock:]
- +[CEKFluidBehaviorUtilities animatablePropertyWithProgressMilestones:block:]
- +[CEKFluidBehaviorUtilities floatAnimatablePropertyWithInitialValue:cancelableFrameCallback:]
- +[CEKFluidBehaviorUtilities rectAnimatablePropertyWithInitialValue:cancelableFrameCallback:]
- +[CEKFluidBehaviorUtilities vector2DAnimatablePropertyWithInitialValue:cancelableFrameCallback:]
- GCC_except_table45
- ___72+[CEKFluidBehaviorUtilities animatablePropertyWithFunctionalCompletion:]_block_invoke
- ___76+[CEKFluidBehaviorUtilities animatablePropertyWithProgressMilestones:block:]_block_invoke
- ___84+[CEKFluidBehaviorUtilities animatablePropertyWithMilestonePassingTest:passedBlock:]_block_invoke
- ___92+[CEKFluidBehaviorUtilities rectAnimatablePropertyWithInitialValue:cancelableFrameCallback:]_block_invoke
- ___96+[CEKFluidBehaviorUtilities vector2DAnimatablePropertyWithInitialValue:cancelableFrameCallback:]_block_invoke
CStrings:
+ "cv08"
```
