## AccessibilityPhysicalInteraction

> `/System/Library/PrivateFrameworks/AccessibilityPhysicalInteraction.framework/AccessibilityPhysicalInteraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c904` | `0x1e3ec` | **`+0x1ae8`** |
| `__DATA.__bss` | `0x280` | `0x6b0` | **`+0x430`** |
| `__TEXT.__const` | `0x4cd` | `0x6ed` | **`+0x220`** |
| `__AUTH_CONST.__const` | `0x530` | `0x660` | **`+0x130`** |
| `__DATA_CONST.__objc_selrefs` | `0x1828` | `0x18c8` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xa40` | `0xae0` | **`+0xa0`** |
| `__AUTH_CONST.__auth_got` | `0x800` | `0x880` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x1b0` | `0x230` | **`+0x80`** |
| `__TEXT.__cstring` | `0x8b4` | `0x931` | **`+0x7d`** |
| `__TEXT.__constg_swiftt` | `0x28` | `0x8c` | **`+0x64`** |
| `__DATA_CONST.__const` | `0x7a0` | `0x800` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x60` | `0xc0` | **`+0x60`** |
| `__TEXT.__dlopen_cstrs` | `0x5a` | `0xb6` | **`+0x5c`** |
| `__DATA.__data` | `0x2e0` | `0x338` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x61d` | `0x654` | **`+0x37`** |
| `__AUTH_CONST.__objc_const` | `0x2888` | `0x28b8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x20bc` | `0x20e4` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x7a0` | `0x7c0` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x10` | `0x30` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x10` | `0x30` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x578` | `0x588` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x4` | `0x10` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x1dc` | `0x1e0` | **`+0x4`** |

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

+  - /System/Library/PrivateFrameworks/AXRuntime.framework/AXRuntime

-  Functions: 927
-  Symbols:   1587
-  CStrings:  135
+  Functions: 969
+  Symbols:   1637
+  CStrings:  142
Symbols:
+ -[AXPIDragGesturePerformer isMultiStepGesture]
+ -[AXPIGesturePerformer isMultiStepGesture]
+ -[AXPISystemActionHelper _convertPointToPortraitUpOrientation:forDisplay:]
+ -[AXPISystemActionHelper performScrollAction:atPoint:onDisplay:]
+ GCC_except_table220
+ GCC_except_table222
+ GCC_except_table227
+ GCC_except_table245
+ GCC_except_table267
+ GCC_except_table326
+ GCC_except_table384
+ GCC_except_table713
+ GCC_except_table740
+ _AXUIFirstActiveScreen
+ _AXUIScreenForDisplayID
+ _MediaExperienceLibraryCore.frameworkLibrary
+ _OBJC_CLASS_$_AXElement
+ _OBJC_CLASS_$_AXEventData
+ _OBJC_IVAR_$_AXPISystemActionHelper._homeButtonIsPressed
+ __AXSHapticMusicEnabled
+ __AXShouldDispatchNonMainThreadCallbacksOnMainThreadPopReason
+ __AXShouldDispatchNonMainThreadCallbacksOnMainThreadPushReason
+ ___48-[AXPISystemActionHelper openVisualIntelligence]_block_invoke
+ ___64-[AXPISystemActionHelper performScrollAction:atPoint:onDisplay:]_block_invoke
+ ___64-[AXPISystemActionHelper performScrollAction:atPoint:onDisplay:]_block_invoke_2
+ ___64-[AXPISystemActionHelper performScrollAction:atPoint:onDisplay:]_block_invoke_3
+ ___MediaExperienceLibraryCore_block_invoke
+ ___block_descriptor_36_e19_B24?0{CGPoint=dd}8l
+ ___block_descriptor_72_e8_32s40bs48r_e5_v8?0lr48l8s40l8s32l8
+ ___block_descriptor_81_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
+ ___getAVSystemControllerClass_block_invoke
+ ___getAVSystemController_FullMuteAttributeSymbolLoc_block_invoke
+ _associated conformance 32AccessibilityPhysicalInteraction0A32DeviceActionHandlerResolvedStateV0A13SharedSupport0adE0O0gH0AaF11TripleClickVAG
+ _associated conformance 32AccessibilityPhysicalInteraction0A32DeviceActionHandlerResolvedStateV0A13SharedSupport0adE0O11TripleClickV0gH0AaD0agH0
+ _associated conformance 32AccessibilityPhysicalInteraction0A32SystemActionHandlerResolvedStateV0A13SharedSupport0adE0O0gH0AaF17DisplayAppearanceVAG
+ _associated conformance 32AccessibilityPhysicalInteraction0A32SystemActionHandlerResolvedStateV0A13SharedSupport0adE0O17DisplayAppearanceV0gH0AaD0agH0
+ _associated conformance 32AccessibilityPhysicalInteraction0A33FeatureActionHandlerResolvedStateV0A13SharedSupport0adE0O0gH0AaF10MotionCuesVAG
+ _associated conformance 32AccessibilityPhysicalInteraction0A33FeatureActionHandlerResolvedStateV0A13SharedSupport0adE0O0gH0AaF11HapticMusicVAG
+ _associated conformance 32AccessibilityPhysicalInteraction0A33FeatureActionHandlerResolvedStateV0A13SharedSupport0adE0O10MotionCuesV0gH0AaD0agH0
+ _associated conformance 32AccessibilityPhysicalInteraction0A33FeatureActionHandlerResolvedStateV0A13SharedSupport0adE0O11HapticMusicV0gH0AaD0agH0
+ _audit_stringMediaExperience
+ _dispatch_block_cancel
+ _dispatch_block_create
+ _dispatch_semaphore_create
+ _dispatch_semaphore_signal
+ _dispatch_semaphore_wait
+ _dlerror
+ _dlsym
+ _getAVSystemControllerClass
+ _getAVSystemControllerClass.softClass
+ _getAVSystemController_FullMuteAttributeSymbolLoc.ptr
+ _performScrollAction:atPoint:onDisplay:.AXPIScrollElementQueryQueue
+ _performScrollAction:atPoint:onDisplay:.onceToken
+ _swift_getForeignTypeMetadata
+ _symbolic _____ 32AccessibilityPhysicalInteraction0A32DeviceActionHandlerResolvedStateV
+ _symbolic _____ 32AccessibilityPhysicalInteraction0A33FeatureActionHandlerResolvedStateV
+ _symbolic _____ So30AXCAccessibilityShortcutOptionV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So30AXCAccessibilityShortcutOptionV
- GCC_except_table234
- GCC_except_table243
- GCC_except_table258
- GCC_except_table317
- GCC_except_table702
- GCC_except_table729
- ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
- _getSiriSimpleActivationSourceClass
CStrings:
+ "3"
+ "AVSystemController"
+ "AVSystemController_FullMuteAttribute"
+ "AXPIScrollElementQuery"
+ "Accessibility Mute action"
+ "B24@?0{CGPoint=dd}8"
+ "Could not perform scroll AXAction %d, timeout reached."
+ "softlink:o:path:/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience"
- "#"
```
