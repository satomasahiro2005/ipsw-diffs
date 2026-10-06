## GameControllerUI

> `/System/Library/PrivateFrameworks/GameControllerUI.framework/GameControllerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6638` | `0x770c` | **`+0x10d4`** |
| `__AUTH_CONST.__objc_const` | `0x23a0` | `0x2970` | **`+0x5d0`** |
| `__TEXT.__oslogstring` | `0x218` | `0x418` | **`+0x200`** |
| `__DATA.__data` | `0x520` | `0x6a0` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0x7fc` | `0x964` | **`+0x168`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e0` | `0x6b0` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0x2a8` | `0x370` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0x2f0` | `0x378` | **`+0x88`** |
| `__TEXT.__gcc_except_tab` | `0xdc` | `0x14c` | **`+0x70`** |
| `__AUTH.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x120` | `0x160` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x170` | `0x1b0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x196` | `0x1c8` | **`+0x32`** |
| `__AUTH_CONST.__auth_got` | `0x380` | `0x3a8` | **`+0x28`** |
| `__DATA_CONST.__objc_catlist` | `0x38` | `0x60` | **`+0x28`** |
| `__DATA.__bss` | `0x1b0` | `0x1d0` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x78` | `0x98` | **`+0x20`** |
| `__TEXT.__const` | `0x186` | `0x196` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x5c` | `0x60` | **`+0x4`** |

### Other Changes

```diff

-14.0.19.0.0
+14.0.21.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

+  - /System/Library/PrivateFrameworks/GamePolicy.framework/GamePolicy

+  - /System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices

-  Functions: 207
-  Symbols:   640
-  CStrings:  34
+  Functions: 247
+  Symbols:   737
+  CStrings:  54
Symbols:
+ +[GCGameIntentGamePolicyAction supportsSecureCoding]
+ +[GCGameIntentOpenPlatformGameLibraryAction homeScreenService]
+ -[GCGameIntentGamePolicyAction copyWithZone:]
+ -[GCGameIntentGamePolicyAction encodeWithCoder:]
+ -[GCGameIntentGamePolicyAction initWithCoder:]
+ -[GCGameIntentGamePolicyAction initWithOptions:]
+ -[GCGameIntentGamePolicyAction init]
+ -[GCGameIntentGamePolicyAction performAction]
+ -[GCGameIntentLaunchAppleGamesAction(GamePolicy) performAction]
+ -[GCGameIntentLaunchApplicationAction(UI) performAction]
+ -[GCGameIntentOpenPlatformGameLibraryAction tryPresentAppLibraryPod:]
+ -[GCGameIntentOpenPlatformGameLibraryAction(UI) performAction]
+ -[GCGameIntentShowAppleGameOverlayAction(GamePolicy) performAction]
+ -[GCGameIntentShowAppleGameOverlayAction(GamePolicy) tryMergeWithOther:]
+ -[_GCUserNotificationConfiguration(UI) _ui_configureNotificationDictionary:]
+ GCC_except_table0
+ GCC_except_table10
+ GCC_except_table6
+ GCC_except_table9
+ _OBJC_CLASS_$_GCGameIntentGamePolicyAction
+ _OBJC_CLASS_$_GCGameIntentLaunchAppleGamesAction
+ _OBJC_CLASS_$_GCGameIntentLaunchApplicationAction
+ _OBJC_CLASS_$_GCGameIntentOpenPlatformGameLibraryAction
+ _OBJC_CLASS_$_GCGameIntentShowAppleGameOverlayAction
+ _OBJC_CLASS_$_GPUserExperienceProxy
+ _OBJC_CLASS_$_LSApplicationWorkspace
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSString
+ _OBJC_CLASS_$_SBSHomeScreenService
+ _OBJC_CLASS_$__GCUserNotificationConfiguration
+ _OBJC_IVAR_$_GCGameIntentGamePolicyAction._options
+ _OBJC_METACLASS_$_GCGameIntentGamePolicyAction
+ _SBSSuspendFrontmostApplication
+ __OBJC_$_CATEGORY_GCGameIntentLaunchAppleGamesAction_$_GamePolicy
+ __OBJC_$_CATEGORY_GCGameIntentLaunchApplicationAction_$_UI
+ __OBJC_$_CATEGORY_GCGameIntentOpenPlatformGameLibraryAction_$_UI
+ __OBJC_$_CATEGORY_GCGameIntentShowAppleGameOverlayAction_$_GamePolicy
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_GCGameIntentLaunchAppleGamesAction_$_GamePolicy
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_GCGameIntentLaunchApplicationAction_$_UI
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_GCGameIntentOpenPlatformGameLibraryAction_$_UI
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_GCGameIntentShowAppleGameOverlayAction_$_GamePolicy
+ __OBJC_$_CATEGORY_INSTANCE_METHODS__GCUserNotificationConfiguration_$_UI
+ __OBJC_$_CATEGORY__GCUserNotificationConfiguration_$_UI
+ __OBJC_$_CLASS_METHODS_GCGameIntentGamePolicyAction
+ __OBJC_$_CLASS_PROP_LIST_GCGameIntentGamePolicyAction
+ __OBJC_$_CLASS_PROP_LIST_NSSecureCoding
+ __OBJC_$_INSTANCE_METHODS_GCGameIntentGamePolicyAction
+ __OBJC_$_INSTANCE_VARIABLES_GCGameIntentGamePolicyAction
+ __OBJC_$_PROP_LIST_GCGameIntentGamePolicyAction
+ __OBJC_$_PROTOCOL_CLASS_METHODS_NSSecureCoding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_GCGameIntentAction
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCoding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCopying
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_GCGameIntentAction
+ __OBJC_$_PROTOCOL_METHOD_TYPES_GCGameIntentAction
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCoding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCopying
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSSecureCoding
+ __OBJC_$_PROTOCOL_REFS_GCGameIntentAction
+ __OBJC_$_PROTOCOL_REFS_NSSecureCoding
+ __OBJC_CLASS_PROTOCOLS_$_GCGameIntentGamePolicyAction
+ __OBJC_CLASS_RO_$_GCGameIntentGamePolicyAction
+ __OBJC_LABEL_PROTOCOL_$_GCGameIntentAction
+ __OBJC_LABEL_PROTOCOL_$_NSCoding
+ __OBJC_LABEL_PROTOCOL_$_NSCopying
+ __OBJC_LABEL_PROTOCOL_$_NSSecureCoding
+ __OBJC_METACLASS_RO_$_GCGameIntentGamePolicyAction
+ __OBJC_PROTOCOL_$_GCGameIntentAction
+ __OBJC_PROTOCOL_$_NSCoding
+ __OBJC_PROTOCOL_$_NSCopying
+ __OBJC_PROTOCOL_$_NSSecureCoding
+ ___45-[GCGameIntentGamePolicyAction performAction]_block_invoke
+ ___45-[GCGameIntentGamePolicyAction performAction]_block_invoke_2
+ ___62-[GCGameIntentOpenPlatformGameLibraryAction(UI) performAction]_block_invoke
+ ___62-[GCGameIntentOpenPlatformGameLibraryAction(UI) performAction]_block_invoke_2
+ ___66+[GCGameIntentOpenPlatformGameLibraryAction(UI) homeScreenService]_block_invoke
+ ___67-[GCGameIntentShowAppleGameOverlayAction(GamePolicy) performAction]_block_invoke
+ ___67-[GCGameIntentShowAppleGameOverlayAction(GamePolicy) performAction]_block_invoke_2
+ ___73-[GCGameIntentOpenPlatformGameLibraryAction(UI) tryPresentAppLibraryPod:]_block_invoke
+ ____gc_log_game_intent_block_invoke
+ ___block_descriptor_40_e8_32s_e17_v16?0"NSError"8ls32l8
+ ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e19_v16?0"GCPromise"8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e8_v16?0Q8ls32l8s40l8
+ ___block_descriptor_48_e8_32s_e19_v16?0"GCPromise"8ls32l8
+ ___kCFBooleanFalse
+ ___kCFBooleanTrue
+ __gc_log_game_intent
+ __gc_log_game_intent.Log
+ __gc_log_game_intent.onceToken
+ __os_activity_create
+ __os_activity_current
+ __os_log_error_impl
+ _homeScreenService.Service
+ _homeScreenService.onceToken
+ _os_activity_scope_enter
+ _os_activity_scope_leave
CStrings:
+ "%lu"
+ "Dismiss app library fails: %@"
+ "Dismiss app library success."
+ "Dismiss app library: already dismissed"
+ "GameIntent"
+ "Launch Application"
+ "Launch Game Overlay: Handled by game policy (%zu)"
+ "Launch Game Overlay: Not handled (timeout)."
+ "Launch Game Overlay: Not handled."
+ "Launch Games Application"
+ "Open Game Layer"
+ "Present app library fails: %@"
+ "Present app library success."
+ "Present app library: Not on the home screen! Dismissing frontmost application..."
+ "Present app library: already presented"
+ "Show Game Overlay"
+ "Toggle Platform Game Library"
+ "options"
+ "v16@?0@\"NSError\"8"
+ "v16@?0Q8"
```
