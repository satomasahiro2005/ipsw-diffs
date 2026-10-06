## GameKitFramework

> `/System/Library/AccessibilityBundles/GameKitFramework.axbundle/GameKitFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x344` | `0xe84` | **`+0xb40`** |
| `__AUTH_CONST.__objc_const` | `0x90` | `0x380` | **`+0x2f0`** |
| `__DATA_CONST.__objc_selrefs` | `0x58` | `0x1f8` | **`+0x1a0`** |
| `__AUTH.__objc_data` | `—` | `0x140` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0x220` | `0x360` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x14` | `0x124` | **`+0x110`** |
| `__TEXT.__cstring` | `0x153` | `0x213` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0x0` | `0x70` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x78` | `0xc0` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x60` | `0x90` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0xa0` | `0xc0` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `0x28` | **`+0x20`** |
| `__DATA.__bss` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA.__objc_ivar` | `—` | `0xc` | **`+0xc`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__const` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

+  - /System/Library/PrivateFrameworks/AXRuntime.framework/AXRuntime

-  Functions: 7
-  Symbols:   39
-  CStrings:  23
+  Functions: 28
+  Symbols:   136
+  CStrings:  33
Symbols:
+ +[AXGameKitAccessPointBridge accessPointElementForWindow:]
+ +[AXGameKitAccessPointBridge sharedBridge]
+ +[UIWindowAccessibility__GameKit__UIKit(SafeCategory) safeCategoryBaseClass]
+ +[UIWindowAccessibility__GameKit__UIKit(SafeCategory) safeCategoryTargetClassName]
+ -[AXGameKitAccessPointBridge .cxx_destruct]
+ -[AXGameKitAccessPointBridge _accessibilityAccessPointChanged:]
+ -[AXGameKitAccessPointBridge _attachWithIdentifier:angelPid:]
+ -[AXGameKitAccessPointBridge _detach]
+ -[AXGameKitAccessPointBridge _foregroundSceneForIdentifier:]
+ -[AXGameKitAccessPointBridge _keyWindowForScene:]
+ -[AXGameKitAccessPointBridge attachedWindow]
+ -[AXGameKitAccessPointBridge clientElement]
+ -[AXGameKitAccessPointBridge setAttachedWindow:]
+ -[AXGameKitAccessPointBridge setClientElement:]
+ -[AXGameKitAccessPointElement _accessibilitySortPriority]
+ -[AXGameKitAccessPointElement accessibilityFrame]
+ -[AXGameKitAccessPointElement axOrderingFrame]
+ -[AXGameKitAccessPointElement setAxOrderingFrame:]
+ -[UIWindowAccessibility__GameKit__UIKit _accessibilityAdditionalElements]
+ _AXGameCenterAccessPointDidChangeNotification
+ _NSClassFromString
+ _OBJC_CLASS_$_AXGameKitAccessPointBridge
+ _OBJC_CLASS_$_AXGameKitAccessPointElement
+ _OBJC_CLASS_$_AXRemoteElement
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSNotificationCenter
+ _OBJC_CLASS_$_NSString
+ _OBJC_CLASS_$_UIAccessibilitySafeCategory
+ _OBJC_CLASS_$_UIApplication
+ _OBJC_CLASS_$_UIWindowAccessibility__GameKit__UIKit
+ _OBJC_CLASS_$_UIWindowScene
+ _OBJC_CLASS_$___UIWindowAccessibility__GameKit__UIKit_super
+ _OBJC_IVAR_$_AXGameKitAccessPointBridge._attachedWindow
+ _OBJC_IVAR_$_AXGameKitAccessPointBridge._clientElement
+ _OBJC_IVAR_$_AXGameKitAccessPointElement._axOrderingFrame
+ _OBJC_METACLASS_$_AXGameKitAccessPointBridge
+ _OBJC_METACLASS_$_AXGameKitAccessPointElement
+ _OBJC_METACLASS_$_AXRemoteElement
+ _OBJC_METACLASS_$_UIAccessibilitySafeCategory
+ _OBJC_METACLASS_$_UIWindowAccessibility__GameKit__UIKit
+ _OBJC_METACLASS_$___UIWindowAccessibility__GameKit__UIKit_super
+ _UIAccessibilityConvertFrameToScreenCoordinates
+ _UIAccessibilityLayoutChangedNotification
+ _UIAccessibilityPostNotification
+ __NSConcreteStackBlock
+ __OBJC_$_CLASS_METHODS_AXGameKitAccessPointBridge
+ __OBJC_$_CLASS_METHODS_UIWindowAccessibility__GameKit__UIKit(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_AXGameKitAccessPointBridge
+ __OBJC_$_INSTANCE_METHODS_AXGameKitAccessPointElement
+ __OBJC_$_INSTANCE_METHODS_UIWindowAccessibility__GameKit__UIKit
+ __OBJC_$_INSTANCE_VARIABLES_AXGameKitAccessPointBridge
+ __OBJC_$_INSTANCE_VARIABLES_AXGameKitAccessPointElement
+ __OBJC_$_PROP_LIST_AXGameKitAccessPointBridge
+ __OBJC_$_PROP_LIST_AXGameKitAccessPointElement
+ __OBJC_CLASS_RO_$_AXGameKitAccessPointBridge
+ __OBJC_CLASS_RO_$_AXGameKitAccessPointElement
+ __OBJC_CLASS_RO_$_UIWindowAccessibility__GameKit__UIKit
+ __OBJC_CLASS_RO_$___UIWindowAccessibility__GameKit__UIKit_super
+ __OBJC_METACLASS_RO_$_AXGameKitAccessPointBridge
+ __OBJC_METACLASS_RO_$_AXGameKitAccessPointElement
+ __OBJC_METACLASS_RO_$_UIWindowAccessibility__GameKit__UIKit
+ __OBJC_METACLASS_RO_$___UIWindowAccessibility__GameKit__UIKit_super
+ ___42+[AXGameKitAccessPointBridge sharedBridge]_block_invoke
+ ___63-[AXGameKitAccessPointBridge _accessibilityAccessPointChanged:]_block_invoke
+ ___block_descriptor_53_e8_32s40s_e5_v8?0ls32l8s40l8
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __dispatch_main_q
+ _dispatch_async
+ _objc_alloc
+ _objc_alloc_init
+ _objc_destroyWeak
+ _objc_enumerationMutation
+ _objc_loadWeakRetained
+ _objc_msgSendSuper2
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _objc_opt_respondsToSelector
+ _objc_release_x1
+ _objc_release_x21
+ _objc_release_x22
+ _objc_release_x23
+ _objc_release_x24
+ _objc_release_x25
+ _objc_release_x8
+ _objc_retainAutoreleaseReturnValue
+ _objc_retain_x19
+ _objc_retain_x2
+ _objc_retain_x21
+ _objc_retain_x22
+ _objc_retain_x23
+ _objc_retain_x8
+ _objc_storeStrong
+ _objc_storeWeak
+ _objc_unsafeClaimAutoreleasedReturnValue
+ _sharedBridge.bridge
+ _sharedBridge.onceToken
Functions:
~ ___55+[AXGameKitFrameworkGlue accessibilityInitializeBundle]_block_invoke : 100 -> 104
~ ___55+[AXGameKitFrameworkGlue accessibilityInitializeBundle]_block_invoke_4 : 4 -> 20
CStrings:
+ "AXGameCenterAccessPointDidChange"
+ "AXGameCenterAccessPointStateRequest"
+ "GKAccessPoint"
+ "UIWindow"
+ "UIWindowAccessibility__GameKit__UIKit"
+ "active"
+ "angelPid"
+ "gc-access-point:%@"
+ "sceneIdentifier"
+ "shared"
```
