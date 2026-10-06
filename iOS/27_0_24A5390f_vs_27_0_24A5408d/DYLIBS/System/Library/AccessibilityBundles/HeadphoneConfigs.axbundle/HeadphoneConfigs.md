## HeadphoneConfigs

> `/System/Library/AccessibilityBundles/HeadphoneConfigs.axbundle/HeadphoneConfigs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25fc` | `0x2c58` | **`+0x65c`** |
| `__AUTH_CONST.__cfstring` | `0x7e0` | `0x9e0` | **`+0x200`** |
| `__TEXT.__cstring` | `0x558` | `0x734` | **`+0x1dc`** |
| `__AUTH_CONST.__objc_const` | `0x9a0` | `0xac0` | **`+0x120`** |
| `__TEXT.__oslogstring` | `—` | `0xe1` | **`+0xe1`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x150` | `0x1d0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x7bc` | `0x80c` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x5b8` | `0x600` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x98` | `0xd8` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x120` | `0x138` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x58` | **`+0x10`** |
| `__TEXT.__const` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA.__bss` | `0x10` | `0x11` | **`+0x1`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 52
-  Symbols:   191
-  CStrings:  81
+  Functions: 60
+  Symbols:   227
+  CStrings:  100
Symbols:
+ +[HPSSpatialProfileSingeStepEnrollmentControllerAccessibility _accessibilityPerformValidations:]
+ +[HPSSpatialProfileSingeStepEnrollmentControllerAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[HPSSpatialProfileSingeStepEnrollmentControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[HPSSpatialProfileSingeStepEnrollmentControllerAccessibility moveToStep:]
+ -[HPSSpatialProfileSingeStepEnrollmentControllerAccessibility triggerFaceInFrameHandlerTimeout]
+ _AXLogCommon
+ _AXSpatialProfileAnnounce
+ _AXSpatialProfileString
+ _NSLocaleUsesMetricSystem
+ _OBJC_CLASS_$_HPSSpatialProfileSingeStepEnrollmentControllerAccessibility
+ _OBJC_CLASS_$_NSAttributedString
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSLocale
+ _OBJC_CLASS_$___HPSSpatialProfileSingeStepEnrollmentControllerAccessibility_super
+ _OBJC_METACLASS_$_HPSSpatialProfileSingeStepEnrollmentControllerAccessibility
+ _OBJC_METACLASS_$___HPSSpatialProfileSingeStepEnrollmentControllerAccessibility_super
+ _UIAccessibilityAnnouncementNotification
+ _UIAccessibilitySpeechAttributeQueueAnnouncement
+ __OBJC_$_CLASS_METHODS_HPSSpatialProfileSingeStepEnrollmentControllerAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_HPSSpatialProfileSingeStepEnrollmentControllerAccessibility
+ __OBJC_CLASS_RO_$_HPSSpatialProfileSingeStepEnrollmentControllerAccessibility
+ __OBJC_CLASS_RO_$___HPSSpatialProfileSingeStepEnrollmentControllerAccessibility_super
+ __OBJC_METACLASS_RO_$_HPSSpatialProfileSingeStepEnrollmentControllerAccessibility
+ __OBJC_METACLASS_RO_$___HPSSpatialProfileSingeStepEnrollmentControllerAccessibility_super
+ ___AXSpatialProfileAnnounce_block_invoke
+ ___block_descriptor_48_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___kCFBooleanTrue
+ __dispatch_main_q
+ __os_log_debug_impl
+ _dispatch_async
+ _kAXLastAnnouncementKey
+ _objc_getAssociatedObject
+ _objc_retain_x19
+ _objc_retain_x20
+ _objc_setAssociatedObject
+ _os_log_type_enabled
Functions:
~ ___55+[AXHeadphoneConfigsGlue accessibilityInitializeBundle]_block_invoke_3 : 132 -> 152
CStrings:
+ "FACE_TOO_CLOSE_DETAIL_IMPERIAL"
+ "FACE_TOO_CLOSE_DETAIL_METRICS"
+ "GENERAL_FAILURE_DETAIL"
+ "HPSSpatialProfileSingeStepEnrollmentController"
+ "HPSSpatialProfileSingeStepEnrollmentControllerAccessibility"
+ "SINGLE_STEP_FRONT_VIEW_CAPTURE_DETAIL"
+ "SINGLE_STEP_FRONT_VIEW_POSITION_YOUR_FACE"
+ "SINGLE_STEP_OCCLUSION_EAR_DETAIL"
+ "SPATIAL_AUDIO_PROFILE_COMPLETE"
+ "SpatialAudioProfile"
+ "[AX SpatialEnroll] announcing: %{public}@"
+ "[AX SpatialEnroll] moveToStep %d (HPSSpatialProfileSingeStepEnrollmentController)"
+ "[AX SpatialEnroll] triggerFaceInFrameHandlerTimeout (HPSSpatialProfileSingeStepEnrollmentController)"
+ "_currentStep"
+ "_faceBoundingBoxStatus"
+ "_faceCaptured"
+ "_faceTooCloseErrorShowing"
+ "moveToStep:"
+ "triggerFaceInFrameHandlerTimeout"
```
