## CarPlay

> `/System/Library/Frameworks/CarPlay.framework/CarPlay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f144` | `0x6f68c` | **`+0x548`** |
| `__TEXT.__oslogstring` | `0x3436` | `0x34d6` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x59b6` | `0x5a26` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x5640` | `0x5680` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1f18` | `0x1f50` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x9a40` | `0x9a78` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x214e0` | `0x21510` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x4350` | `0x4368` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1f78` | `0x1f70` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xa34` | `0xa38` | **`+0x4`** |

### Other Changes

```diff

-537.3.0.0.0
+540.1.0.0.0

-  Functions: 3374
-  Symbols:   6322
-  CStrings:  1090
+  Functions: 3382
+  Symbols:   6332
+  CStrings:  1094
Symbols:
+ +[CPRouteDetail routeDetailWithInfo:]
+ +[CPRouteDetail routeDetailWithParking:]
+ -[CPInterfaceController _setupTemplateVersionAndSupportedSelectorsWithCompletion:]
+ -[CPInterfaceController lastOverlaidTemplate]
+ -[CPInterfaceController setLastOverlaidTemplate:]
+ -[CPMapPanel setSections:]
+ -[CPNavigationAlert setShowsCloseButton:]
+ -[CPNavigationAlert showsCloseButton]
+ -[CPTemplateApplicationDashboardScene _updateSceneTraitsAndPushTraitsToScreen:callParentWillTransitionToTraitCollection:]
+ -[CPTemplateApplicationInstrumentClusterScene _updateSceneTraitsAndPushTraitsToScreen:callParentWillTransitionToTraitCollection:]
+ -[CPTemplateApplicationScene _updateSceneTraitsAndPushTraitsToScreen:callParentWillTransitionToTraitCollection:]
+ GCC_except_table132
+ GCC_except_table23
+ GCC_except_table29
+ GCC_except_table60
+ GCC_except_table77
+ _CPRouteDetailStringForType
+ _OBJC_IVAR_$_CPInterfaceController._lastOverlaidTemplate
+ _OBJC_IVAR_$_CPNavigationAlert._showsCloseButton
+ ___64-[CPInterfaceController hideOverlayTemplateAnimated:completion:]_block_invoke_2
+ ___65-[CPInterfaceController showOverlayTemplate:animated:completion:]_block_invoke_2
+ ___82-[CPInterfaceController _setupTemplateVersionAndSupportedSelectorsWithCompletion:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e18_v24?0Q8"NSSet"16ls32l8s40l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
- -[CPInterfaceController _completeSetupWithCompletion:]
- -[CPRouteDetail labelTintColor]
- -[CPRouteDetail setLabelTintColor:]
- -[CPTemplateApplicationDashboardScene _updateSceneTraitsAndPushTraitsToScreen:]
- -[CPTemplateApplicationInstrumentClusterScene _updateSceneTraitsAndPushTraitsToScreen:]
- -[CPTemplateApplicationScene _updateSceneTraitsAndPushTraitsToScreen:]
- GCC_except_table130
- GCC_except_table25
- GCC_except_table58
- GCC_except_table75
- _OBJC_IVAR_$_CPRouteDetail._labelTintColor
- ___54-[CPInterfaceController _completeSetupWithCompletion:]_block_invoke
- ___54-[CPInterfaceController templateIdentifierDidDismiss:]_block_invoke_2
- ___block_descriptor_48_e8_32s40bs_e18_v24?0Q8"NSSet"16ls32l8s40l8
CStrings:
+ "A navigation alert is currently showing. Call dismissNavigationAlertAnimated:completion: first."
+ "CPMapTemplate did not push because remote does not support"
+ "Finished setting up template version and supported selectors."
+ "Info"
+ "No panel matching id %@ found, must be an options panel"
+ "Parking"
+ "kCPNavigationAlertShowsCloseButtonKey"
- ", labelTintColor=%@"
- "No panel matching id %@ found"
- "labelTintColor"
```
