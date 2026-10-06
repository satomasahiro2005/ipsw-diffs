## ScreenTimeUI

> `/System/Library/PrivateFrameworks/ScreenTimeUI.framework/ScreenTimeUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62d34` | `0x63a14` | **`+0xce0`** |
| `__DATA_CONST.__const` | `0xca0` | `0xd90` | **`+0xf0`** |
| `__TEXT.__swift5_typeref` | `0x5810` | `0x589a` | **`+0x8a`** |
| `__TEXT.__objc_methlist` | `0x18d8` | `0x1948` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1530` | `0x15a0` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x44c` | `0x4b8` | **`+0x6c`** |
| `__DATA_CONST.__objc_selrefs` | `0x1958` | `0x19a0` | **`+0x48`** |
| `__DATA.__data` | `0x13d8` | `0x1418` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x29a8` | `0x29c8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xad0` | `0xae8` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x360d` | `0x35fd` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x180` | `0x184` | **`+0x4`** |

### Other Changes

```diff

-640.0.100.0.0
+645.1.100.0.0

-  Functions: 1930
-  Symbols:   1900
+  Functions: 1953
+  Symbols:   1930
Symbols:
+ -[STBlockingViewController _presentAskForMoreTimeOptions:]
+ -[STBlockingViewController _presentIgnoreLimitOptionsWithoutPasscode]
+ -[STBlockingViewController _refreshShouldAllowOneMoreMinuteWithCompletion:]
+ -[STBlockingViewController _refreshShouldAllowOneMoreMinute]
+ -[STBlockingViewController resolvedShouldAllowOneMoreMinute]
+ -[STBlockingViewController setResolvedShouldAllowOneMoreMinute:]
+ -[STLockoutPolicyController shouldAllowOneMoreMinuteWithCompletionHandler:]
+ -[STLockoutViewController _preferredAlertControllerStyle]
+ -[STLockoutViewController _presentIgnoreLimitActionSheetAllowingOneMoreMinute:]
+ -[STLockoutViewController _presentUnlockedAskOrApproveActionSheetAllowingOneMoreMinute:]
+ GCC_except_table10
+ GCC_except_table123
+ GCC_except_table129
+ GCC_except_table135
+ GCC_except_table139
+ GCC_except_table141
+ GCC_except_table143
+ GCC_except_table145
+ GCC_except_table147
+ GCC_except_table149
+ GCC_except_table26
+ GCC_except_table27
+ GCC_except_table37
+ GCC_except_table49
+ GCC_except_table52
+ GCC_except_table56
+ GCC_except_table57
+ GCC_except_table64
+ GCC_except_table67
+ GCC_except_table69
+ GCC_except_table89
+ GCC_except_table99
+ _OBJC_IVAR_$_STBlockingViewController._resolvedShouldAllowOneMoreMinute
+ ___57-[STLockoutViewController _actionIgnoreLimitActionSheet:]_block_invoke_2
+ ___58-[STBlockingViewController _presentAskForMoreTimeOptions:]_block_invoke
+ ___58-[STBlockingViewController _presentAskForMoreTimeOptions:]_block_invoke_2
+ ___58-[STBlockingViewController _presentAskForMoreTimeOptions:]_block_invoke_3
+ ___58-[STBlockingViewController _presentAskForMoreTimeOptions:]_block_invoke_4
+ ___58-[STBlockingViewController _presentAskForMoreTimeOptions:]_block_invoke_5
+ ___65-[STLockoutViewController _actionUnlockedAskOrApproveActionSheet]_block_invoke_2
+ ___69-[STBlockingViewController _presentIgnoreLimitOptionsWithoutPasscode]_block_invoke
+ ___69-[STBlockingViewController _presentIgnoreLimitOptionsWithoutPasscode]_block_invoke_2
+ ___69-[STBlockingViewController _presentIgnoreLimitOptionsWithoutPasscode]_block_invoke_3
+ ___69-[STBlockingViewController _presentIgnoreLimitOptionsWithoutPasscode]_block_invoke_4
+ ___75-[STBlockingViewController _refreshShouldAllowOneMoreMinuteWithCompletion:]_block_invoke
+ ___75-[STLockoutPolicyController shouldAllowOneMoreMinuteWithCompletionHandler:]_block_invoke
+ ___79-[STLockoutViewController _presentIgnoreLimitActionSheetAllowingOneMoreMinute:]_block_invoke
+ ___88-[STLockoutViewController _presentUnlockedAskOrApproveActionSheetAllowingOneMoreMinute:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e30_v24?0"NSNumber"8"NSError"16ls32l8
+ ___block_descriptor_40_e8_32w_e8_v12?0B8lw32l8
+ ___block_descriptor_41_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_41_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_48_e8_32bs40w_e30_v24?0"NSNumber"8"NSError"16lw40l8s32l8
+ ___block_descriptor_49_e8_32bs40w_e5_v8?0lw40l8s32l8
+ _get_witness_table 7SwiftUI15ModifiedContentVyAA6VStackVyAA05TupleD0VyACyACyACyACyACyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA25_ForegroundStyleModifier2VyAA5ColorVAA14LinearGradientVGGAKyAA19SymbolRenderingModeVSgGGAA14_PaddingLayoutVGAA023AccessibilityAttachmentK0VG_ACyAA4TextVAKyAA0Z9AlignmentOGGACyA13_A3_GAA7ForEachVys18EnumeratedSequenceVySaySSGGSiA13_GSgQPGGA3_GAA4ViewHPA24_AAA26_HPyHC_A3_AA04ViewK0HPyHCHC
+ _symbolic _____yAAyAAyAAyAAy__________y_____SgGG_____y__________GGACy_____SgGG_____G_____G 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA25_ForegroundStyleModifier2V AA5ColorV AA14LinearGradientV AA19SymbolRenderingModeV AA14_PaddingLayoutV AA023AccessibilityAttachmentI0V
+ _symbolic _____yAAyAAyAAyAAy__________y_____SgGG_____y__________GGACy_____SgGG_____G_____G_AAy_____ACy_____GGAAyAxQG_____y_____ySaySSGGSiAXGSgt 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA25_ForegroundStyleModifier2V AA5ColorV AA14LinearGradientV AA19SymbolRenderingModeV AA14_PaddingLayoutV AA023AccessibilityAttachmentI0V AA4TextV AA0X9AlignmentO AA7ForEachV s18EnumeratedSequenceV
+ _symbolic _____y__________G 7SwiftUI25_ForegroundStyleModifier2V AA5ColorV AA14LinearGradientV
+ _symbolic _____y___________y_____yADyADyADyADy__________y_____SgGG_____y__________GGAFy_____SgGG_____G_____G_ADy_____AFy_____GGADyA_ATG_____y_____ySaySSGGSiA_GSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA08ModifiedI0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA25_ForegroundStyleModifier2V AA5ColorV AA14LinearGradientV AA19SymbolRenderingModeV AA08_PaddingG0V AA023AccessibilityAttachmentO0V AA4TextV AA13TextAlignmentO AA7ForEachV s18EnumeratedSequenceV
+ _symbolic _____y_____y_____yAAyAAyAAyAAyAAy__________y_____SgGG_____y__________GGAEy_____SgGG_____G_____G_AAy_____AEy_____GGAAyAzSG_____y_____ySaySSGGSiAZGSgQPGGASG 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA25_ForegroundStyleModifier2V AA5ColorV AA14LinearGradientV AA19SymbolRenderingModeV AA14_PaddingLayoutV AA023AccessibilityAttachmentK0V AA4TextV AA0Z9AlignmentO AA7ForEachV s18EnumeratedSequenceV
+ _symbolic _____y_____y_____yACyACyACyACy__________y_____SgGG_____y__________GGAEy_____SgGG_____G_____G_ACy_____AEy_____GGACyAzSG_____y_____ySaySSGGSiAZGSgQPGG 7SwiftUI6VStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA25_ForegroundStyleModifier2V AA5ColorV AA14LinearGradientV AA19SymbolRenderingModeV AA14_PaddingLayoutV AA023AccessibilityAttachmentK0V AA4TextV AA0Z9AlignmentO AA7ForEachV s18EnumeratedSequenceV
- -[STLockoutPolicyController shouldAllowOneMoreMinute]
- GCC_except_table116
- GCC_except_table122
- GCC_except_table125
- GCC_except_table128
- GCC_except_table134
- GCC_except_table136
- GCC_except_table138
- GCC_except_table140
- GCC_except_table142
- GCC_except_table21
- GCC_except_table22
- GCC_except_table34
- GCC_except_table38
- GCC_except_table46
- GCC_except_table47
- GCC_except_table61
- GCC_except_table93
- _OBJC_CLASS_$_UIDevice
- ___55-[STBlockingViewController _showAskForMoreTimeOptions:]_block_invoke_2
- ___55-[STBlockingViewController _showAskForMoreTimeOptions:]_block_invoke_3
- ___55-[STBlockingViewController _showAskForMoreTimeOptions:]_block_invoke_4
- ___55-[STBlockingViewController _showAskForMoreTimeOptions:]_block_invoke_5
- ___66-[STBlockingViewController _showIgnoreLimitOptionsWithoutPasscode]_block_invoke_2
- ___66-[STBlockingViewController _showIgnoreLimitOptionsWithoutPasscode]_block_invoke_3
- ___66-[STBlockingViewController _showIgnoreLimitOptionsWithoutPasscode]_block_invoke_4
- _get_witness_table 7SwiftUI15ModifiedContentVyAA6VStackVyAA05TupleD0VyACyACyACyACyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA25_ForegroundStyleModifier2VyAA5ColorVAA14LinearGradientVGGAKyAA19SymbolRenderingModeVSgGGAA14_PaddingLayoutVG_ACyAA4TextVAKyAA0X9AlignmentOGGACyA10_A3_GAA7ForEachVys18EnumeratedSequenceVySaySSGGSiA10_GSgQPGGA3_GAA4ViewHPA21_AAA23_HPyHC_A3_AA04ViewK0HPyHCHC
- _symbolic _____yAAyAAyAAy__________y_____SgGG_____y__________GGACy_____SgGG_____G_AAy_____ACy_____GGAAyAvQG_____y_____ySaySSGGSiAVGSgt 7SwiftUI15ModifiedContentV AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA25_ForegroundStyleModifier2V AA5ColorV AA14LinearGradientV AA19SymbolRenderingModeV AA14_PaddingLayoutV AA4TextV AA0V9AlignmentO AA7ForEachV s18EnumeratedSequenceV
- _symbolic _____y___________y_____yADyADyADy__________y_____SgGG_____y__________GGAFy_____SgGG_____G_ADy_____AFy_____GGADyAyTG_____y_____ySaySSGGSiAYGSgQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_VStackLayoutV AA12TupleContentV AA08ModifiedI0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA25_ForegroundStyleModifier2V AA5ColorV AA14LinearGradientV AA19SymbolRenderingModeV AA08_PaddingG0V AA4TextV AA13TextAlignmentO AA7ForEachV s18EnumeratedSequenceV
- _symbolic _____y_____y_____yAAyAAyAAyAAy__________y_____SgGG_____y__________GGAEy_____SgGG_____G_AAy_____AEy_____GGAAyAxSG_____y_____ySaySSGGSiAXGSgQPGGASG 7SwiftUI15ModifiedContentV AA6VStackV AA05TupleD0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA25_ForegroundStyleModifier2V AA5ColorV AA14LinearGradientV AA19SymbolRenderingModeV AA14_PaddingLayoutV AA4TextV AA0X9AlignmentO AA7ForEachV s18EnumeratedSequenceV
- _symbolic _____y_____y_____yACyACyACy__________y_____SgGG_____y__________GGAEy_____SgGG_____G_ACy_____AEy_____GGACyAxSG_____y_____ySaySSGGSiAXGSgQPGG 7SwiftUI6VStackV AA12TupleContentV AA08ModifiedE0V AA5ImageV AA30_EnvironmentKeyWritingModifierV AA4FontV AA25_ForegroundStyleModifier2V AA5ColorV AA14LinearGradientV AA19SymbolRenderingModeV AA14_PaddingLayoutV AA4TextV AA0X9AlignmentO AA7ForEachV s18EnumeratedSequenceV
CStrings:
+ "Failed to fetch One More Minute policy: %{public}@"
- "Failed to fetch One More Minute policy for %{public}@: %{public}@"
```
