## ScreenTimeSettingsUI

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsUI.framework/ScreenTimeSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12730c` | `0x1270a8` | **`-0x264`** |
| `__DATA_CONST.__objc_selrefs` | `0x6f68` | `0x6f90` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xc61c` | `0xc63c` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x138` | `0x150` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1848` | `0x1858` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x318` | `0x328` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3d20` | `0x3d30` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x43dc` | `0x43ce` | **`-0xe`** |
| `__DATA_CONST.__got` | `0x1498` | `0x14a0` | **`+0x8`** |

### Other Changes

```diff

-645.1.100.0.0
+649.0.0.0.0

-  Functions: 6272
-  Symbols:   8450
+  Functions: 6277
+  Symbols:   8453
Symbols:
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _extensionsSpecifier]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _getExtensionsSpecifierValue:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _setExtensionsSpecifierValue:specifier:]
+ GCC_except_table20
+ ___swift_closure_destructor.9Tm
+ _get_witness_table SHRz7SwiftUI4ViewR_AaBR0_r1_l018ScreenTimeSettingsB021ContentRestrictionRowVyAA012_ConditionalG0VyAA07LabeledG0VyAA08ModifiedG0VyAaBPAAE10labelStyleyQrqd__AA05LabelN0Rd__lFQOyAA0O0VyAA6VStackVyAA05TupleG0VyAKyAA4TextVAA30_EnvironmentKeyWritingModifierVySiSgGG_AKyA_AXyAA5ColorVSgGGSgQPGGAKyAKyAKyq_AA12_FrameLayoutVGAA011_BackgroundV0Vyq0_GGAA11_ClipEffectVyAA16RoundedRectangleVGGG_AC013CenterAlignedoN0VQo_A3_GAKyAA6PickerVyAA05EmptyC0VAC0gH5ValueVyxGSgAA13PickerBuilderV0G0VyA33__AA7ForEachVySayA32_GxAA12PickerOptionVyA33_A_GGGGA3_GGAA6HStackVyATyA25__AA6SpacerVAVQPGGGGAaBHPyHC
+ _symbolic _____y_____y_____y_____y_____y_____y_____y_____yADy__________ySiSgGG_ADyAlIy_____SgGGSgQPGGADyADyADyq______G_____yq0_GG_____y_____GGG______Qo_AOGADy_____y__________yxGSg_____yA9_______ySayA8_Gx_____yA9_ALGGGGAOGG_____yAGyA4_______AHQPGGGG 20ScreenTimeSettingsUI21ContentRestrictionRowV 05SwiftD0012_ConditionalE0V AD07LabeledE0V AD08ModifiedE0V AD4ViewPADE10labelStyleyQrqd__AD05LabelN0Rd__lFQO AD0O0V AD6VStackV AD05TupleE0V AD4TextV AD30_EnvironmentKeyWritingModifierV AD5ColorV AD12_FrameLayoutV AD011_BackgroundV0V AD11_ClipEffectV AD16RoundedRectangleV AA013CenterAlignedoN0V AD6PickerV AD05EmptyL0V AA0eF5ValueV AD13PickerBuilderV0E0V AD7ForEachV AD12PickerOptionV AD6HStackV AD6SpacerV
- GCC_except_table18
- ___swift_closure_destructor.5Tm
- _get_witness_table SHRz7SwiftUI4ViewR_AaBR0_r1_l018ScreenTimeSettingsB021ContentRestrictionRowVyAA012_ConditionalG0VyAA6HStackVyAA05TupleG0VyAA08ModifiedG0VyAaBPAAE10labelStyleyQrqd__AA05LabelO0Rd__lFQOyAA0P0VyAA6VStackVyAKyAMyAA4TextVAA30_EnvironmentKeyWritingModifierVySiSgGG_AMyA_AXyAA5ColorVSgGGSgQPGGAMyAMyAMyq_AA12_FrameLayoutVGAA011_BackgroundV0Vyq0_GGAA11_ClipEffectVyAA16RoundedRectangleVGGG_AC013CenterAlignedpO0VQo_A3_G_AA6SpacerVAMyAA6PickerVyAA05EmptyC0VAC0gH5ValueVyxGSgAA13PickerBuilderV0G0VyA35__AA7ForEachVySayA34_GxAA12PickerOptionVyA35_A_GGGGA3_GQPGGAIyAKyA25__A27_AVQPGGGGAaBHPyHC
- _symbolic _____y_____y_____y_____y_____y_____y_____y_____yADyAEy__________ySiSgGG_AEyAlIy_____SgGGSgQPGGAEyAEyAEyq______G_____yq0_GG_____y_____GGG______Qo_AOG______AEy_____y__________yxGSg_____yA10_______ySayA9_Gx_____yA10_ALGGGGAOGQPGGACyADyA4__A5_AHQPGGGG 20ScreenTimeSettingsUI21ContentRestrictionRowV 05SwiftD0012_ConditionalE0V AD6HStackV AD05TupleE0V AD08ModifiedE0V AD4ViewPADE10labelStyleyQrqd__AD05LabelO0Rd__lFQO AD0P0V AD6VStackV AD4TextV AD30_EnvironmentKeyWritingModifierV AD5ColorV AD12_FrameLayoutV AD011_BackgroundV0V AD11_ClipEffectV AD16RoundedRectangleV AA013CenterAlignedpO0V AD6SpacerV AD6PickerV AD05EmptyM0V AA0eF5ValueV AD13PickerBuilderV0E0V AD7ForEachV AD12PickerOptionV
```
