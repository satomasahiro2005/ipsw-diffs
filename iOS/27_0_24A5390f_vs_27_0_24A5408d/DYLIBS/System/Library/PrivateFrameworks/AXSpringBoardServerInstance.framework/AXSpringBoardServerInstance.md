## AXSpringBoardServerInstance

> `/System/Library/PrivateFrameworks/AXSpringBoardServerInstance.framework/AXSpringBoardServerInstance`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d758` | `0x3e368` | **`+0xc10`** |
| `__TEXT.__oslogstring` | `0x1712` | `0x18b9` | **`+0x1a7`** |
| `__AUTH.__objc_data` | `0x3e0` | `0x520` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x3908` | `0x3a30` | **`+0x128`** |
| `__DATA_CONST.__const` | `0x1058` | `0x10f8` | **`+0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0xf50` | `0xeb0` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x3354` | `0x33d4` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0xafc` | `0xb6c` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x2910` | `0x2978` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x11e0` | `0x1248` | **`+0x68`** |
| `__TEXT.__cstring` | `0x6691` | `0x66a5` | **`+0x14`** |
| `__DATA.__bss` | `0x848` | `0x838` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x860` | `0x870` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1f0` | `0x200` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xbe0` | `0xbe8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xf8` | `0x100` | **`+0x8`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 1357
-  Symbols:   2670
-  CStrings:  1110
+  Functions: 1372
+  Symbols:   2704
+  CStrings:  1116
Symbols:
+ +[AXSBDeviceApplicationSceneStatusBarBreadcrumbProviderAccessibility _shouldAddBreadcrumbToActivatingSceneEntity:sceneHandle:withTransitionContext:applicationController:]
+ +[AXSB_SBAssistantIslandStageCoordinator _accessibilityPerformValidations:]
+ +[AXSB_SBAssistantIslandStageCoordinator(SafeCategory) safeCategoryBaseClass]
+ +[AXSB_SBAssistantIslandStageCoordinator(SafeCategory) safeCategoryTargetClassName]
+ +[AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory _accessibilityPerformValidations:]
+ +[AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory(SafeCategory) safeCategoryBaseClass]
+ +[AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory(SafeCategory) safeCategoryTargetClassName]
+ -[AXSB_SBAssistantIslandStageCoordinator stageControllerActiveStateDidChange:]
+ -[AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory userInterfaceStyleProvider:didUpdateStyle:preferredAnimationSettings:completion:]
+ -[AXSpringBoardServerHelper _axActiveRemoteTransientOverlayIsGameCenterAccessPointOnly]
+ -[AXSpringBoardServerHelper _handleRecognitionOptionsAlert:]
+ -[AXSpringBoardServerHelper reduceAmbientFullScreenLiveActivityWithServerInstance:]
+ -[_AXSpringBoardServerInstance _reduceAmbientFullScreenLiveActivity:]
+ GCC_except_table1050
+ GCC_except_table1054
+ GCC_except_table1060
+ GCC_except_table1062
+ GCC_except_table1076
+ GCC_except_table1087
+ GCC_except_table1095
+ GCC_except_table110
+ GCC_except_table1107
+ GCC_except_table1125
+ GCC_except_table116
+ GCC_except_table1163
+ GCC_except_table178
+ GCC_except_table272
+ GCC_except_table280
+ GCC_except_table282
+ GCC_except_table287
+ GCC_except_table300
+ GCC_except_table302
+ GCC_except_table310
+ GCC_except_table320
+ GCC_except_table330
+ GCC_except_table360
+ GCC_except_table368
+ GCC_except_table391
+ GCC_except_table421
+ GCC_except_table424
+ GCC_except_table427
+ GCC_except_table437
+ GCC_except_table463
+ GCC_except_table466
+ GCC_except_table468
+ GCC_except_table469
+ GCC_except_table471
+ GCC_except_table472
+ GCC_except_table474
+ GCC_except_table475
+ GCC_except_table492
+ GCC_except_table494
+ GCC_except_table499
+ GCC_except_table501
+ GCC_except_table503
+ GCC_except_table506
+ GCC_except_table517
+ GCC_except_table519
+ GCC_except_table521
+ GCC_except_table523
+ GCC_except_table525
+ GCC_except_table530
+ GCC_except_table534
+ GCC_except_table537
+ GCC_except_table539
+ GCC_except_table541
+ GCC_except_table543
+ GCC_except_table558
+ GCC_except_table562
+ GCC_except_table564
+ GCC_except_table566
+ GCC_except_table575
+ GCC_except_table580
+ GCC_except_table583
+ GCC_except_table587
+ GCC_except_table596
+ GCC_except_table612
+ GCC_except_table614
+ GCC_except_table62
+ GCC_except_table634
+ GCC_except_table636
+ GCC_except_table641
+ GCC_except_table643
+ GCC_except_table659
+ GCC_except_table729
+ GCC_except_table781
+ GCC_except_table800
+ GCC_except_table828
+ GCC_except_table92
+ GCC_except_table923
+ GCC_except_table927
+ GCC_except_table967
+ GCC_except_table972
+ GCC_except_table974
+ _AXAskShouldHideOptions
+ _AXVSRemoteAlertServiceClassNameKey
+ _OBJC_CLASS_$_AXSB_SBAssistantIslandStageCoordinator
+ _OBJC_CLASS_$_AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory
+ _OBJC_CLASS_$_NSNull
+ _OBJC_CLASS_$___AXSB_SBAssistantIslandStageCoordinator_super
+ _OBJC_CLASS_$___AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory_super
+ _OBJC_METACLASS_$_AXSB_SBAssistantIslandStageCoordinator
+ _OBJC_METACLASS_$_AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory
+ _OBJC_METACLASS_$___AXSB_SBAssistantIslandStageCoordinator_super
+ _OBJC_METACLASS_$___AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory_super
+ __OBJC_$_CLASS_METHODS_AXSB_SBAssistantIslandStageCoordinator(SafeCategory)
+ __OBJC_$_CLASS_METHODS_AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_AXSB_SBAssistantIslandStageCoordinator
+ __OBJC_$_INSTANCE_METHODS_AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory
+ __OBJC_CLASS_RO_$_AXSB_SBAssistantIslandStageCoordinator
+ __OBJC_CLASS_RO_$_AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory
+ __OBJC_CLASS_RO_$___AXSB_SBAssistantIslandStageCoordinator_super
+ __OBJC_CLASS_RO_$___AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory_super
+ __OBJC_METACLASS_RO_$_AXSB_SBAssistantIslandStageCoordinator
+ __OBJC_METACLASS_RO_$_AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory
+ __OBJC_METACLASS_RO_$___AXSB_SBAssistantIslandStageCoordinator_super
+ __OBJC_METACLASS_RO_$___AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory_super
+ ___170+[AXSBDeviceApplicationSceneStatusBarBreadcrumbProviderAccessibility _shouldAddBreadcrumbToActivatingSceneEntity:sceneHandle:withTransitionContext:applicationController:]_block_invoke
+ ___170+[AXSBDeviceApplicationSceneStatusBarBreadcrumbProviderAccessibility _shouldAddBreadcrumbToActivatingSceneEntity:sceneHandle:withTransitionContext:applicationController:]_block_invoke_2
+ ___60-[AXSpringBoardServerHelper _handleRecognitionOptionsAlert:]_block_invoke
+ ___60-[AXSpringBoardServerHelper _handleRecognitionOptionsAlert:]_block_invoke_2
+ ___60-[AXSpringBoardServerHelper _handleRecognitionOptionsAlert:]_block_invoke_3
+ ___66-[AXSpringBoardServerHelper isSpotlightVisibleWithServerInstance:]_block_invoke
+ ___78-[AXSB_SBAssistantIslandStageCoordinator stageControllerActiveStateDidChange:]_block_invoke
+ ___83-[AXSpringBoardServerHelper reduceAmbientFullScreenLiveActivityWithServerInstance:]_block_invoke
+ ___83-[AXSpringBoardServerHelper reduceAmbientFullScreenLiveActivityWithServerInstance:]_block_invoke_2
+ ___87-[AXSpringBoardServerHelper _axActiveRemoteTransientOverlayIsGameCenterAccessPointOnly]_block_invoke
+ ___87-[AXSpringBoardServerHelper _axActiveRemoteTransientOverlayIsGameCenterAccessPointOnly]_block_invoke_2
+ ___block_descriptor_48_e8_32r40r_e8_B16?08lr32l8r40l8
+ ___block_descriptor_48_e8_32s40s_e25_v32?0"NSString"8Q16^B24ls32l8s40l8
+ ___block_descriptor_56_e8_32s40r48r_e5_v8?0ls32l8r40l8r48l8
+ ___block_descriptor_56_e8_32s40r_e5_v8?0lr40l8u48l8s32l8
- +[AXSBDeviceApplicationSceneStatusBarBreadcrumbProviderAccessibility _shouldAddBreadcrumbToActivatingSceneEntity:sceneHandle:withTransitionContext:]
- +[AXSB_SBSceneManagerSafeCategory _accessibilityPerformValidations:]
- +[AXSB_SBSceneManagerSafeCategory(SafeCategory) safeCategoryBaseClass]
- +[AXSB_SBSceneManagerSafeCategory(SafeCategory) safeCategoryTargetClassName]
- +[AXSpringBoardServerHelper _uiController]
- -[AXSB_SBSceneManagerSafeCategory userInterfaceStyleProvider:didUpdateStyle:preferredAnimationSettings:completion:]
- GCC_except_table1030
- GCC_except_table1035
- GCC_except_table1039
- GCC_except_table1047
- GCC_except_table1061
- GCC_except_table1072
- GCC_except_table1080
- GCC_except_table1092
- GCC_except_table1110
- GCC_except_table114
- GCC_except_table1148
- GCC_except_table176
- GCC_except_table266
- GCC_except_table270
- GCC_except_table274
- GCC_except_table278
- GCC_except_table281
- GCC_except_table286
- GCC_except_table288
- GCC_except_table314
- GCC_except_table351
- GCC_except_table359
- GCC_except_table382
- GCC_except_table412
- GCC_except_table415
- GCC_except_table418
- GCC_except_table449
- GCC_except_table453
- GCC_except_table455
- GCC_except_table456
- GCC_except_table458
- GCC_except_table461
- GCC_except_table462
- GCC_except_table464
- GCC_except_table482
- GCC_except_table484
- GCC_except_table489
- GCC_except_table491
- GCC_except_table493
- GCC_except_table496
- GCC_except_table507
- GCC_except_table509
- GCC_except_table511
- GCC_except_table513
- GCC_except_table515
- GCC_except_table520
- GCC_except_table524
- GCC_except_table527
- GCC_except_table529
- GCC_except_table531
- GCC_except_table533
- GCC_except_table536
- GCC_except_table538
- GCC_except_table552
- GCC_except_table554
- GCC_except_table560
- GCC_except_table563
- GCC_except_table565
- GCC_except_table567
- GCC_except_table586
- GCC_except_table601
- GCC_except_table621
- GCC_except_table623
- GCC_except_table628
- GCC_except_table63
- GCC_except_table630
- GCC_except_table646
- GCC_except_table715
- GCC_except_table767
- GCC_except_table786
- GCC_except_table814
- GCC_except_table908
- GCC_except_table912
- GCC_except_table93
- GCC_except_table952
- GCC_except_table957
- GCC_except_table959
- _AXSBUIControllerSharedInstance
- _AXSBUIControllerSharedInstance.SharedInstance
- _OBJC_CLASS_$_AXSB_SBSceneManagerSafeCategory
- _OBJC_CLASS_$___AXSB_SBSceneManagerSafeCategory_super
- _OBJC_METACLASS_$_AXSB_SBSceneManagerSafeCategory
- _OBJC_METACLASS_$___AXSB_SBSceneManagerSafeCategory_super
- __OBJC_$_CLASS_METHODS_AXSB_SBSceneManagerSafeCategory(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_AXSB_SBSceneManagerSafeCategory
- __OBJC_CLASS_RO_$_AXSB_SBSceneManagerSafeCategory
- __OBJC_CLASS_RO_$___AXSB_SBSceneManagerSafeCategory_super
- __OBJC_METACLASS_RO_$_AXSB_SBSceneManagerSafeCategory
- __OBJC_METACLASS_RO_$___AXSB_SBSceneManagerSafeCategory_super
- ___148+[AXSBDeviceApplicationSceneStatusBarBreadcrumbProviderAccessibility _shouldAddBreadcrumbToActivatingSceneEntity:sceneHandle:withTransitionContext:]_block_invoke
- ___148+[AXSBDeviceApplicationSceneStatusBarBreadcrumbProviderAccessibility _shouldAddBreadcrumbToActivatingSceneEntity:sceneHandle:withTransitionContext:]_block_invoke_2
- __uiController.AX_SBUIController
CStrings:
+ "0@`"
+ "AXSBServer: ambient fullscreen Live Activity is presented but SBActivityAmbientViewController does not respond to transitionToCompactOverlayModeWithCompletion: (selector may have drifted on this train)"
+ "AXSBServer: reducing ambient fullscreen Live Activity to compact overlay for VoiceOver home gesture"
+ "AXSB_SBAssistantIslandStageCoordinator"
+ "AXSB_SBUserInterfaceStyleSceneUpdaterSafeCategory"
+ "B16@?0@8"
+ "SBAssistantIslandStageCoordinator"
+ "SBUserInterfaceStyleSceneUpdater"
+ "_shouldAddBreadcrumbToActivatingSceneEntity:sceneHandle:withTransitionContext:applicationController:"
+ "action:access-point-overlay"
+ "activityViewController"
+ "ambientPresentationController"
+ "configurationIdentifier"
+ "definition"
+ "fullOverlayViewController"
+ "homeButtonPressHandler"
+ "isAutomaticStageCreationEnabled"
+ "isDarkModeActive queried by client; answering: %d"
+ "isFlexibleWindowingEnabled"
+ "isShownWithinWindowScene:"
+ "items"
+ "remoteTransientOverlaySessionManager"
+ "stageControllerActiveStateDidChange:"
+ "supportsSceneResizing"
+ "toggleDarkMode requested by client; dark mode active before toggle: %d"
+ "transientOverlay"
+ "v32@?0@\"NSString\"8Q16^B24"
+ "voiceControlController"
- "<SBKeyboardFocusControlling>"
- "AXSB_SBSceneManagerSafeCategory"
- "SBApplicationSceneHandleProviding"
- "SBApplicationSceneIdentityProviding"
- "SBContinuitySessionManager"
- "SBInCallTransientOverlayManager"
- "SBMainDisplayRootWindowScenePresentationBinder"
- "SBMutableSwitcherTransitionRequest"
- "SBUIController"
- "UIScenePresentationBinder"
- "_keyboardFocusCoordinator"
- "_shouldAddBreadcrumbToActivatingSceneEntity:sceneHandle:withTransitionContext:"
- "addScene:"
- "focusLockSpringBoardWindowScene:forReason:"
- "isMedusaCapable"
- "lockOverrideEnabled"
- "newSceneIdentityForApplication:"
- "setAppLayout:"
- "setDisplayItemLayoutAttributesMap:"
- "setUnlockedEnvironmentState:"
- "sharedApplication"
- "sharedRemoteSearchViewController"
```
