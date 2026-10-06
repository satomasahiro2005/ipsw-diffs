## SpringBoard

> `/System/Library/AccessibilityBundles/SpringBoard.axbundle/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38610` | `0x3a764` | **`+0x2154`** |
| `__AUTH_CONST.__cfstring` | `0xb940` | `0xbc20` | **`+0x2e0`** |
| `__TEXT.__oslogstring` | `0x72a` | `0x9fb` | **`+0x2d1`** |
| `__TEXT.__cstring` | `0xa401` | `0xa66e` | **`+0x26d`** |
| `__AUTH_CONST.__objc_const` | `0xb270` | `0xb390` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0xa60` | `0xb50` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x4c34` | `0x4d04` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2568` | `0x2628` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0xcd0` | `0xd70` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x12f0` | `0x1360` | **`+0x70`** |
| `__DATA_CONST.__const` | `0xdf0` | `0xe18` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x770` | `0x790` | **`+0x20`** |
| `__DATA.__bss` | `0xd0` | `0xe8` | **`+0x18`** |
| `__TEXT.__const` | `0xd0` | `0xe8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5c0` | `0x5d0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x960` | `0x970` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x3d0` | `0x3d8` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 1589
-  Symbols:   3804
-  CStrings:  1632
+  Functions: 1619
+  Symbols:   3855
+  CStrings:  1666
Symbols:
+ +[SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility _accessibilityPerformValidations:]
+ +[SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[SBAppSwitcherAppAccessibilityElement _accessibilityHintIsInstructional]
+ -[SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility _accessibilitySetRemoteElementIfNecessaryForScene:]
+ -[SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility _axActivePreflightScene]
+ -[SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility _axContextLayersForScene:]
+ -[SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility accessibilityElements]
+ -[SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility dealloc]
+ -[SBFluidSwitcherItemContainerAccessibility _accessibilityCloseAppFromCustomAction:]
+ -[SBFluidSwitcherItemContainerAccessibility _accessibilityHintIsInstructional]
+ -[SBKeyboardFocusCoordinatorAccessibility _axDeferringGraphFocusLockForScene:]
+ -[SBKeyboardFocusCoordinatorAccessibility _axFocusRequesterDeathWatcher]
+ -[SBKeyboardFocusCoordinatorAccessibility _axFullKeyboardAccessDaemonPid]
+ -[SBKeyboardFocusCoordinatorAccessibility _axSceneForPid:sceneID:]
+ -[SBKeyboardFocusCoordinatorAccessibility _axSetFocusRequesterDeathWatcher:]
+ -[SBRecordingIndicatorViewControllerAccessibility _axLoadAccessibilityInformationForIndicator:]
+ -[SBRecordingIndicatorViewControllerAccessibility _axLoadAccessibilityInformationForIndicatorView:overridesInvisibility:]
+ -[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]
+ GCC_except_table105
+ GCC_except_table1119
+ GCC_except_table1139
+ GCC_except_table1146
+ GCC_except_table1150
+ GCC_except_table1154
+ GCC_except_table1157
+ GCC_except_table1161
+ GCC_except_table121
+ GCC_except_table1317
+ GCC_except_table1324
+ GCC_except_table1328
+ GCC_except_table1355
+ GCC_except_table1359
+ GCC_except_table1364
+ GCC_except_table1367
+ GCC_except_table1386
+ GCC_except_table1394
+ GCC_except_table1402
+ GCC_except_table1408
+ GCC_except_table1419
+ GCC_except_table1421
+ GCC_except_table1545
+ GCC_except_table1599
+ GCC_except_table210
+ GCC_except_table231
+ GCC_except_table259
+ GCC_except_table263
+ GCC_except_table289
+ GCC_except_table315
+ GCC_except_table320
+ GCC_except_table323
+ GCC_except_table385
+ GCC_except_table397
+ GCC_except_table440
+ GCC_except_table546
+ GCC_except_table581
+ GCC_except_table608
+ GCC_except_table615
+ GCC_except_table617
+ GCC_except_table717
+ GCC_except_table724
+ GCC_except_table726
+ GCC_except_table728
+ GCC_except_table73
+ GCC_except_table742
+ GCC_except_table751
+ GCC_except_table755
+ GCC_except_table757
+ GCC_except_table778
+ GCC_except_table780
+ GCC_except_table796
+ GCC_except_table814
+ GCC_except_table818
+ GCC_except_table825
+ GCC_except_table87
+ GCC_except_table93
+ GCC_except_table967
+ GCC_except_table969
+ _AXLogAppAccessibility
+ _AXRemoteElementConcatSceneUUIDAndContextId
+ _AXSpringBoardKeyboardFocusUsesDeferringGraph
+ _AXSpringBoardKeyboardFocusUsesDeferringGraph.onceToken
+ _AXSpringBoardKeyboardFocusUsesDeferringGraph.usesDeferringGraph
+ _OBJC_CLASS_$_FBSceneLayer
+ _OBJC_CLASS_$_NSThread
+ _OBJC_CLASS_$_SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility
+ _OBJC_CLASS_$___SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility_super
+ _OBJC_METACLASS_$_SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility
+ _OBJC_METACLASS_$___SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility_super
+ __OBJC_$_CLASS_METHODS_SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility
+ __OBJC_CLASS_RO_$_SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility
+ __OBJC_CLASS_RO_$___SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility_super
+ __OBJC_METACLASS_RO_$_SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility
+ __OBJC_METACLASS_RO_$___SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility_super
+ ___105-[SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility _accessibilityResetRemoteElementArray]_block_invoke
+ ___121-[SBRecordingIndicatorViewControllerAccessibility _axLoadAccessibilityInformationForIndicatorView:overridesInvisibility:]_block_invoke
+ ___66-[SBKeyboardFocusCoordinatorAccessibility _axSceneForPid:sceneID:]_block_invoke
+ ___66-[SBKeyboardFocusCoordinatorAccessibility _axSceneForPid:sceneID:]_block_invoke_2
+ ___73-[SBKeyboardFocusCoordinatorAccessibility _axFullKeyboardAccessDaemonPid]_block_invoke
+ ___73-[SBKeyboardFocusCoordinatorAccessibility _axFullKeyboardAccessDaemonPid]_block_invoke_2
+ ___78-[SBKeyboardFocusCoordinatorAccessibility _axDeferringGraphFocusLockForScene:]_block_invoke
+ ___78-[SBKeyboardFocusCoordinatorAccessibility _axDeferringGraphFocusLockForScene:]_block_invoke_2
+ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke
+ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_2
+ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_3
+ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_4
+ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_5
+ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_6
+ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_7
+ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_8
+ ___82-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]_block_invoke_9
+ ___93-[SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility _axContextLayersForScene:]_block_invoke
+ ___AXSpringBoardKeyboardFocusUsesDeferringGraph_block_invoke
+ ___SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility___accessibilityGetRemoteElementArray
+ ___SBKeyboardFocusCoordinatorAccessibility___axFocusRequesterDeathWatcher
+ ___block_descriptor_41_e27_q24?0"UIView"8"UIView"16lu32l8
+ ___block_descriptor_72_e8_32s40s48s56s64r_e5_v8?0lr64l8s32l8s40l8s48l8s56l8
+ __os_feature_enabled_impl
+ __os_log_fault_impl
- -[SBKeyboardFocusCoordinatorAccessibility _accessibilityTokenStringForPid:sceneID:]
- GCC_except_table103
- GCC_except_table1114
- GCC_except_table1134
- GCC_except_table1141
- GCC_except_table1145
- GCC_except_table1148
- GCC_except_table119
- GCC_except_table1300
- GCC_except_table1326
- GCC_except_table1330
- GCC_except_table1335
- GCC_except_table1338
- GCC_except_table1357
- GCC_except_table1363
- GCC_except_table1365
- GCC_except_table1373
- GCC_except_table1379
- GCC_except_table1390
- GCC_except_table1515
- GCC_except_table1569
- GCC_except_table208
- GCC_except_table229
- GCC_except_table257
- GCC_except_table261
- GCC_except_table287
- GCC_except_table313
- GCC_except_table318
- GCC_except_table321
- GCC_except_table382
- GCC_except_table394
- GCC_except_table437
- GCC_except_table543
- GCC_except_table578
- GCC_except_table605
- GCC_except_table611
- GCC_except_table612
- GCC_except_table71
- GCC_except_table714
- GCC_except_table720
- GCC_except_table721
- GCC_except_table725
- GCC_except_table738
- GCC_except_table745
- GCC_except_table746
- GCC_except_table752
- GCC_except_table773
- GCC_except_table775
- GCC_except_table791
- GCC_except_table809
- GCC_except_table813
- GCC_except_table820
- GCC_except_table85
- GCC_except_table91
- GCC_except_table962
- GCC_except_table964
- ___67-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:]_block_invoke
- ___67-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:]_block_invoke_2
- ___67-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:]_block_invoke_3
- ___67-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:]_block_invoke_4
- ___67-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:]_block_invoke_5
- ___67-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:]_block_invoke_6
- ___67-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:]_block_invoke_7
- ___67-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:]_block_invoke_8
- ___67-[SpringBoardAccessibility _accessibilityStatusBarElements:sorted:]_block_invoke_9
- ___83-[SBKeyboardFocusCoordinatorAccessibility _accessibilityTokenStringForPid:sceneID:]_block_invoke
- ___83-[SBKeyboardFocusCoordinatorAccessibility _accessibilityTokenStringForPid:sceneID:]_block_invoke_2
- ___93-[SBRecordingIndicatorViewControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
- ___block_descriptor_40_e27_q24?0"UIView"8"UIView"16lu32l8
CStrings:
+ "CSNotificationDispatcher"
+ "Cannot determine SpringBoard focus lock state under the deferring graph; assuming not locked."
+ "Cannot lock keyboard focus to scene %{public}@ under the deferring graph. hostWindowScene: %@, target: %@, reason: %@"
+ "DeferringGraph"
+ "FBSceneLayerManager"
+ "Found no accessibility daemon scene for pid: %@ sceneID: %@"
+ "KeyboardArbiter"
+ "Locked keyboard focus to scene %{public}@ via the deferring graph, assertion: %{public}@"
+ "No Full Keyboard Access daemon to bound the keyboard focus override for pid: %i"
+ "Preflight remote elements stale; cleared and scheduled rebuild for next tick"
+ "Preflight remote elements validation failed. Expected: %@, Existing: %@"
+ "RBSProcessHandle"
+ "RBSProcessIdentity"
+ "Reset keyboard focus override for pid: %i because Full Keyboard Access (pid: %i) exited while it was in effect"
+ "SBDeviceApplicationCounterRotatableSceneOverlayView"
+ "SBDeviceApplicationCounterRotatableSceneOverlayViewAccessibility"
+ "SBDeviceApplicationSceneView"
+ "SBKeyboardFocusLockReason"
+ "SBKeyboardFocusTarget"
+ "Should always update remote view AX properties on the main thread"
+ "accessibility:"
+ "com.apple.fullkeyboardaccess"
+ "deferFromSBWindowScene:toTarget:lockReason:"
+ "delegate.windowControlsViewController"
+ "handleForIdentifier:error:"
+ "highLevelView"
+ "identityForDaemonJobLabel:"
+ "isKeyboardLayer"
+ "isKeyboardProxyLayer"
+ "layerManager"
+ "layers"
+ "o^@"
+ "secondaryIndicator"
+ "statusBarEdgeInOrientation:"
+ "statusBarOrientation"
+ "targetForFBScene:"
- "Found nil tokenString for pid: %@ sceneID: %@"
- "SBNotificationDestination"
```
