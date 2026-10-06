## AXSpringBoardServerInstance

> `/System/Library/PrivateFrameworks/AXSpringBoardServerInstance.framework/AXSpringBoardServerInstance`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bf14` | `0x3d758` | **`+0x1844`** |
| `__TEXT.__cstring` | `0x63e4` | `0x6691` | **`+0x2ad`** |
| `__TEXT.__oslogstring` | `0x14d1` | `0x1712` | **`+0x241`** |
| `__AUTH_CONST.__cfstring` | `0x6880` | `0x6ac0` | **`+0x240`** |
| `__DATA_CONST.__const` | `0xfa8` | `0x1058` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2890` | `0x2910` | **`+0x80`** |
| `__TEXT.__dlopen_cstrs` | `0x34a` | `0x3ae` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0x38a8` | `0x3908` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x32f4` | `0x3354` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1190` | `0x11e0` | **`+0x50`** |
| `__AUTH_CONST.__objc_intobj` | `0x4e0` | `0x528` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0xc80` | `0xcc0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xac4` | `0xafc` | **`+0x38`** |
| `__DATA.__bss` | `0x828` | `0x848` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x840` | `0x860` | **`+0x20`** |
| `__TEXT.__const` | `0x5a0` | `0x5b0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x104` | `0x10c` | **`+0x8`** |

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

-  Functions: 1338
-  Symbols:   2636
-  CStrings:  1073
+  Functions: 1357
+  Symbols:   2670
+  CStrings:  1110
Symbols:
+ -[AXSpringBoardServerHelper _configureActionButtonToDescribeScene]
+ -[AXSpringBoardServerHelper _handleActionButtonDescribeScenePromo]
+ -[AXSpringBoardServerHelper _handleSystemOverlayDisplayLayoutChange:]
+ -[AXSpringBoardServerHelper _monitorSystemOverlayVisibilityChanges]
+ -[AXSpringBoardServerHelper setSystemOverlayVisibilityMonitor:]
+ -[AXSpringBoardServerHelper setVisibleSystemOverlayIdentifiers:]
+ -[AXSpringBoardServerHelper systemOverlayVisibilityMonitor]
+ -[AXSpringBoardServerHelper visibleSystemOverlayIdentifiers]
+ GCC_except_table1030
+ GCC_except_table1035
+ GCC_except_table1039
+ GCC_except_table1045
+ GCC_except_table1047
+ GCC_except_table1072
+ GCC_except_table1080
+ GCC_except_table1092
+ GCC_except_table1110
+ GCC_except_table1148
+ GCC_except_table176
+ GCC_except_table266
+ GCC_except_table270
+ GCC_except_table274
+ GCC_except_table276
+ GCC_except_table278
+ GCC_except_table284
+ GCC_except_table286
+ GCC_except_table288
+ GCC_except_table290
+ GCC_except_table292
+ GCC_except_table294
+ GCC_except_table296
+ GCC_except_table298
+ GCC_except_table304
+ GCC_except_table314
+ GCC_except_table351
+ GCC_except_table359
+ GCC_except_table382
+ GCC_except_table412
+ GCC_except_table415
+ GCC_except_table418
+ GCC_except_table453
+ GCC_except_table455
+ GCC_except_table456
+ GCC_except_table458
+ GCC_except_table459
+ GCC_except_table461
+ GCC_except_table462
+ GCC_except_table464
+ GCC_except_table465
+ GCC_except_table482
+ GCC_except_table484
+ GCC_except_table489
+ GCC_except_table491
+ GCC_except_table493
+ GCC_except_table507
+ GCC_except_table520
+ GCC_except_table524
+ GCC_except_table529
+ GCC_except_table536
+ GCC_except_table538
+ GCC_except_table548
+ GCC_except_table554
+ GCC_except_table556
+ GCC_except_table560
+ GCC_except_table563
+ GCC_except_table565
+ GCC_except_table570
+ GCC_except_table573
+ GCC_except_table577
+ GCC_except_table586
+ GCC_except_table599
+ GCC_except_table601
+ GCC_except_table621
+ GCC_except_table623
+ GCC_except_table628
+ GCC_except_table630
+ GCC_except_table646
+ GCC_except_table715
+ GCC_except_table786
+ GCC_except_table814
+ GCC_except_table908
+ GCC_except_table912
+ GCC_except_table952
+ GCC_except_table957
+ GCC_except_table959
+ _AXZoomLensEffectLowLight
+ _FBSDisplayLayoutElementControlCenterIdentifier
+ _FBSDisplayLayoutElementNotificationCenterIdentifier
+ _OBJC_IVAR_$_AXSpringBoardServerHelper._systemOverlayVisibilityMonitor
+ _OBJC_IVAR_$_AXSpringBoardServerHelper._visibleSystemOverlayIdentifiers
+ _SBSDisplayLayoutElementAppSwitcherIdentifier
+ _VoiceShortcutClientLibraryCore.frameworkLibrary
+ ___66-[AXSpringBoardServerHelper _configureActionButtonToDescribeScene]_block_invoke
+ ___66-[AXSpringBoardServerHelper _handleActionButtonDescribeScenePromo]_block_invoke
+ ___66-[AXSpringBoardServerHelper _handleActionButtonDescribeScenePromo]_block_invoke_2
+ ___67-[AXSpringBoardServerHelper _monitorSystemOverlayVisibilityChanges]_block_invoke
+ ___69-[AXSpringBoardServerHelper _handleSystemOverlayDisplayLayoutChange:]_block_invoke
+ ___VoiceShortcutClientLibraryCore_block_invoke
+ ___block_descriptor_32_e20_v24?08"NSError"16l
+ ___block_descriptor_40_e8_32w_e92_v32?0"FBSDisplayLayoutMonitor"8"FBSDisplayLayout"16"FBSDisplayLayoutTransitionContext"24lw32l8
+ ___block_descriptor_48_e8_32s40s_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_e8_32s40s_e35_v32?0"NSString"8"NSNumber"16^B24ls32l8s40l8
+ ___getVCVoiceShortcutClientClass_block_invoke
+ __handleSystemOverlayDisplayLayoutChange:.actionTypesByLayoutIdentifier
+ __handleSystemOverlayDisplayLayoutChange:.onceToken
+ _audit_stringVoiceShortcutClient
+ _getVCVoiceShortcutClientClass.softClass
+ _weak_AFIsLinwoodEnabledAndWasEverAvailable
- GCC_except_table1011
- GCC_except_table1016
- GCC_except_table1020
- GCC_except_table1026
- GCC_except_table1028
- GCC_except_table1042
- GCC_except_table1053
- GCC_except_table1073
- GCC_except_table1091
- GCC_except_table1129
- GCC_except_table253
- GCC_except_table257
- GCC_except_table261
- GCC_except_table263
- GCC_except_table265
- GCC_except_table268
- GCC_except_table271
- GCC_except_table273
- GCC_except_table275
- GCC_except_table277
- GCC_except_table279
- GCC_except_table283
- GCC_except_table285
- GCC_except_table291
- GCC_except_table301
- GCC_except_table338
- GCC_except_table346
- GCC_except_table369
- GCC_except_table399
- GCC_except_table402
- GCC_except_table405
- GCC_except_table436
- GCC_except_table440
- GCC_except_table442
- GCC_except_table443
- GCC_except_table445
- GCC_except_table446
- GCC_except_table448
- GCC_except_table451
- GCC_except_table452
- GCC_except_table469
- GCC_except_table471
- GCC_except_table476
- GCC_except_table478
- GCC_except_table480
- GCC_except_table483
- GCC_except_table494
- GCC_except_table498
- GCC_except_table500
- GCC_except_table502
- GCC_except_table506
- GCC_except_table518
- GCC_except_table525
- GCC_except_table535
- GCC_except_table539
- GCC_except_table542
- GCC_except_table544
- GCC_except_table549
- GCC_except_table558
- GCC_except_table580
- GCC_except_table582
- GCC_except_table602
- GCC_except_table604
- GCC_except_table609
- GCC_except_table611
- GCC_except_table627
- GCC_except_table696
- GCC_except_table748
- GCC_except_table795
- GCC_except_table889
- GCC_except_table893
- GCC_except_table933
- GCC_except_table938
- GCC_except_table940
CStrings:
+ "9000"
+ "APPEARED"
+ "AXOverlayMonitor: %{public}@ %{public}@ — firing AXSpringBoardActionType %ld"
+ "AXOverlayMonitor: installed system overlay visibility monitor"
+ "AXOverlayMonitor: layout transition; elements = %{public}@"
+ "Accessibility template has no parameters"
+ "Class getVCVoiceShortcutClientClass(void)_block_invoke"
+ "Could not find Accessibility action template"
+ "Could not find Describe Scene parameter value"
+ "DISMISSED"
+ "Failed to archive configured action: %@"
+ "Failed to create configured action: %@"
+ "Failed to fetch parameter values: %@"
+ "Failed to fetch staccato actions: %@"
+ "SBSystemActionConfiguredActionArchive"
+ "Successfully configured Action Button to Describe Scene"
+ "VCVoiceShortcutClient"
+ "VCVoiceShortcutClient not available"
+ "action.button.describe.scene.promo.dismiss"
+ "action.button.describe.scene.promo.message"
+ "action.button.describe.scene.promo.set"
+ "action.button.describe.scene.promo.title"
+ "actionIdentifier"
+ "com.apple.AccessibilityUIServer.ToggleAccessibilityFeatureIntent"
+ "com.apple.Siri"
+ "com.apple.coremedia.cameraviewfinder"
+ "com.apple.lock-screen"
+ "com.apple.springboard.systemActionConfigurationChanged"
+ "conferenceManager"
+ "feature"
+ "interactiveScreenshotGestureManager"
+ "parameters"
+ "softlink:r:path:/System/Library/PrivateFrameworks/VoiceShortcutClient.framework/VoiceShortcutClient"
+ "v24@?0@\"NSArray\"8@\"NSError\"16"
+ "v24@?0@8@\"NSError\"16"
+ "v32@?0@\"NSString\"8@\"NSNumber\"16^B24"
+ "values"
+ "void *VoiceShortcutClientLibrary(void)"
- "_interactiveScreenshotGestureManager"
```
