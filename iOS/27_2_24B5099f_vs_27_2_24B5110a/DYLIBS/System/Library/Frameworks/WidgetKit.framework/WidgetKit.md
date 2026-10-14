## WidgetKit

> `/System/Library/Frameworks/WidgetKit.framework/WidgetKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2148a0` | `0x215eb8` | **`+0x1618`** |
| `__DATA.__bss` | `0x14630` | `0x147a0` | **`+0x170`** |
| `__TEXT.__const` | `0x21970` | `0x21ad0` | **`+0x160`** |
| `__AUTH.__data` | `0x5e00` | `0x5ed0` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x50e6` | `0x51b6` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x14530` | `0x145f0` | **`+0xc0`** |
| `__DATA.__data` | `0x6388` | `0x6448` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0xcd16` | `0xcc76` | **`-0xa0`** |
| `__TEXT.__unwind_info` | `0x8ec0` | `0x8f48` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0x7480` | `0x74e0` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x1af0` | `0x1b48` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0xc1a8` | `0xc1fc` | **`+0x54`** |
| `__TEXT.__swift5_reflstr` | `0x573f` | `0x578f` | **`+0x50`** |
| `__DATA.__common` | `0x280` | `0x2c0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x850` | `0x880` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1888` | `0x18b0` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x2d24` | `0x2d10` | **`-0x14`** |
| `__DATA_DIRTY.__data` | `0x62c0` | `0x62d0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x15e8` | `0x15f4` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0xa1c` | `0xa28` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2a10` | `0x2a18` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0xe664` | `0xe65c` | **`-0x8`** |

### Other Changes

```diff

-749.2.12.0.0
+749.2.13.0.0

-  Functions: 12597
-  Symbols:   4307
-  CStrings:  751
+  Functions: 12658
+  Symbols:   4316
+  CStrings:  758
Symbols:
+ _associated conformance 9WidgetKit020IsActivityFullscreenA14EnvironmentKeyVAA01_afG0AA11CodingValueAaDP_SE
+ _associated conformance 9WidgetKit020IsActivityFullscreenA14EnvironmentKeyVAA01_afG0AA11CodingValueAaDP_SL
+ _associated conformance 9WidgetKit020IsActivityFullscreenA14EnvironmentKeyVAA01_afG0AA11CodingValueAaDP_Se
+ _associated conformance 9WidgetKit023ShowsActivityBackgroundA14EnvironmentKeyVAA01_afG0AA11CodingValueAaDP_SE
+ _associated conformance 9WidgetKit023ShowsActivityBackgroundA14EnvironmentKeyVAA01_afG0AA11CodingValueAaDP_SL
+ _associated conformance 9WidgetKit023ShowsActivityBackgroundA14EnvironmentKeyVAA01_afG0AA11CodingValueAaDP_Se
+ _get_witness_table 7SwiftUI19WidgetConfigurationRzlqd0__AaBHD3_AaBPAAE19transformPreferenceyQrqd__m_y5ValueQyd__zctAA0F3KeyRd__lFQOyx_0C3Kit0c10DescriptorH0VQo_HOTm
+ _get_witness_table 7SwiftUI19_ConditionalContentVyAA08ModifiedD0VyAEyAEyAEyAA4ViewPAAE15_containerShapeyQrqd__AA010InsettableH0Rd__lFQOyAA01_f9Modifier_D0Vy9WidgetKit32CommonActivityArchivingModifiersVG_AA16RoundedRectangleVQo_AL0n10BackgroundJ0VGAA022_EnvironmentKeyWritingJ0VyAA14FontDefinition_pXpGGAL0k5IdiomJ0VGAWyAA19WatchDisplayVariantOGGA1_GAaFHPA5_AaFHPA1_AaFHPAzaFHPAuaFHPqd0__AaFHD3_ARHO_AtA0fJ0HPyHCHC_AyAA7_HPyHCHC_A0_AAA7_HPyHCHC_A4_AAA7_HPyHCHC_A1_AaFHPAzaFHPAuaFHPqd0__AaFHD3_ARHO_AtAA7_HPyHCHC_AyAA7_HPyHCHC_A0_AAA7_HPyHCHCHC
+ _symbolic _____ 7SwiftUI17EnvironmentValuesV9WidgetKitE26ShowsActivityBackgroundKeyV
+ _symbolic _____ 9WidgetKit020IsActivityFullscreenA14EnvironmentKeyV
+ _symbolic _____ 9WidgetKit023ShowsActivityBackgroundA14EnvironmentKeyV
+ _symbolic _____yAAyAAyAAy_____y_____y_____G______Qo______G_____y______pXpGG_____GAIy_____GG 7SwiftUI15ModifiedContentV AA4ViewPAAE15_containerShapeyQrqd__AA010InsettableG0Rd__lFQO AA01_e9Modifier_D0V 9WidgetKit32CommonActivityArchivingModifiersV AA16RoundedRectangleV AJ0m10BackgroundI0V AA022_EnvironmentKeyWritingI0V AA14FontDefinitionP AJ0j5IdiomI0V AA19WatchDisplayVariantO
+ _symbolic _____yAAyAAy_____y_____y_____G______Qo______G_____y______pXpGG_____G 7SwiftUI15ModifiedContentV AA4ViewPAAE15_containerShapeyQrqd__AA010InsettableG0Rd__lFQO AA01_e9Modifier_D0V 9WidgetKit32CommonActivityArchivingModifiersV AA16RoundedRectangleV AJ0m10BackgroundI0V AA022_EnvironmentKeyWritingI0V AA14FontDefinitionP AJ0j5IdiomI0V
+ _symbolic _____y_______G 9WidgetKit0A11EnvironmentV6AnyKeyC7Storage33_78669324E9282AD527DC22F3259D9FF4LLC AA020IsActivityFullscreenacE0V
+ _symbolic _____y_______G 9WidgetKit0A11EnvironmentV6AnyKeyC7Storage33_78669324E9282AD527DC22F3259D9FF4LLC AA023ShowsActivityBackgroundacE0V
+ _symbolic _____y__________G 7SwiftUI15ModifiedContentV AA7AnyViewV AA14_PaddingLayoutV
+ _symbolic _____y__________G 7SwiftUI15ModifiedContentV AA7AnyViewV AA20_LayoutScaleModifierV
+ _symbolic _____y_____yAByAByABy_____y_____y_____G______Qo______G_____y______pXpGG_____GAJy_____GGAOG 7SwiftUI19_ConditionalContentV AA08ModifiedD0V AA4ViewPAAE15_containerShapeyQrqd__AA010InsettableH0Rd__lFQO AA01_f9Modifier_D0V 9WidgetKit32CommonActivityArchivingModifiersV AA16RoundedRectangleV AL0n10BackgroundJ0V AA022_EnvironmentKeyWritingJ0V AA14FontDefinitionP AL0k5IdiomJ0V AA19WatchDisplayVariantO
+ _symbolic _____y_____yAByAByABy_____y_____y_____G______Qo______G_____y______pXpGG_____GAJy_____GGAO_G 7SwiftUI19_ConditionalContentV7StorageO AA08ModifiedD0V AA4ViewPAAE15_containerShapeyQrqd__AA010InsettableI0Rd__lFQO AA01_g9Modifier_D0V 9WidgetKit32CommonActivityArchivingModifiersV AA16RoundedRectangleV AN0o10BackgroundK0V AA022_EnvironmentKeyWritingK0V AA14FontDefinitionP AN0l5IdiomK0V AA19WatchDisplayVariantO
- _get_witness_table 7SwiftUI19_ConditionalContentVyAA08ModifiedD0VyAEyAEyAEyAEyAEyAA4ViewPAAE15_containerShapeyQrqd__AA010InsettableH0Rd__lFQOyAA01_f9Modifier_D0Vy9WidgetKit32CommonActivityArchivingModifiersVG_AA16RoundedRectangleVQo_AL0n10BackgroundJ0VGAA022_EnvironmentKeyWritingJ0VyAA14FontDefinition_pXpGGAWySbGGAL0k5IdiomJ0VGAA01_tu9TransformJ0VySbGGAWyAA19WatchDisplayVariantOGGA7_GAaFHPA11_AaFHPA7_AaFHPA3_AaFHPA0_AaFHPAzaFHPAuaFHPqd0__AaFHD3_ARHO_AtA0fJ0HPyHCHC_AyAA13_HPyHCHC_A_AAA13_HPyHCHC_A2_AAA13_HPyHCHC_A6_AAA13_HPyHCHC_A10_AAA13_HPyHCHC_A7_AaFHPA3_AaFHPA0_AaFHPAzaFHPAuaFHPqd0__AaFHD3_ARHO_AtAA13_HPyHCHC_AyAA13_HPyHCHC_A_AAA13_HPyHCHC_A2_AAA13_HPyHCHC_A6_AAA13_HPyHCHCHC
- _get_witness_table 7SwiftUI4ViewRzAA14LinearGradientVRsd__r__lqd0__AaBHD3_AaBPAAE19containerBackground_3forQrqd___AA09ContainerG9PlacementVtAA10ShapeStyleRd__lFQOyx_ADQo_HOTm
- _symbolic _____yAAyAAyAAyAAyAAy_____y_____y_____G______Qo______G_____y______pXpGGAIySbGG_____G_____ySbGGAIy_____GG 7SwiftUI15ModifiedContentV AA4ViewPAAE15_containerShapeyQrqd__AA010InsettableG0Rd__lFQO AA01_e9Modifier_D0V 9WidgetKit32CommonActivityArchivingModifiersV AA16RoundedRectangleV AJ0m10BackgroundI0V AA022_EnvironmentKeyWritingI0V AA14FontDefinitionP AJ0j5IdiomI0V AA01_st9TransformI0V AA19WatchDisplayVariantO
- _symbolic _____yAAyAAyAAyAAy_____y_____y_____G______Qo______G_____y______pXpGGAIySbGG_____G_____ySbGG 7SwiftUI15ModifiedContentV AA4ViewPAAE15_containerShapeyQrqd__AA010InsettableG0Rd__lFQO AA01_e9Modifier_D0V 9WidgetKit32CommonActivityArchivingModifiersV AA16RoundedRectangleV AJ0m10BackgroundI0V AA022_EnvironmentKeyWritingI0V AA14FontDefinitionP AJ0j5IdiomI0V AA01_st9TransformI0V
- _symbolic _____yAAyAAyAAy_____y_____y_____G______Qo______G_____y______pXpGGAIySbGG_____G 7SwiftUI15ModifiedContentV AA4ViewPAAE15_containerShapeyQrqd__AA010InsettableG0Rd__lFQO AA01_e9Modifier_D0V 9WidgetKit32CommonActivityArchivingModifiersV AA16RoundedRectangleV AJ0m10BackgroundI0V AA022_EnvironmentKeyWritingI0V AA14FontDefinitionP AJ0j5IdiomI0V
- _symbolic _____yAAyAAy__________G_____G_____G 7SwiftUI15ModifiedContentV AA7AnyViewV AA16_FlexFrameLayoutV 9WidgetKit32CommonActivityArchivingModifiersV AA08_PaddingI0V
- _symbolic _____yAAyAAy_____y_____y_____G______Qo______G_____y______pXpGGAIySbGG 7SwiftUI15ModifiedContentV AA4ViewPAAE15_containerShapeyQrqd__AA010InsettableG0Rd__lFQO AA01_e9Modifier_D0V 9WidgetKit32CommonActivityArchivingModifiersV AA16RoundedRectangleV AJ0m10BackgroundI0V AA022_EnvironmentKeyWritingI0V AA14FontDefinitionP
- _symbolic _____ySbG 7SwiftUI32_EnvironmentKeyTransformModifierV
- _symbolic _____y_____yAByAByAByAByABy_____y_____y_____G______Qo______G_____y______pXpGGAJySbGG_____G_____ySbGGAJy_____GGATG 7SwiftUI19_ConditionalContentV AA08ModifiedD0V AA4ViewPAAE15_containerShapeyQrqd__AA010InsettableH0Rd__lFQO AA01_f9Modifier_D0V 9WidgetKit32CommonActivityArchivingModifiersV AA16RoundedRectangleV AL0n10BackgroundJ0V AA022_EnvironmentKeyWritingJ0V AA14FontDefinitionP AL0k5IdiomJ0V AA01_tu9TransformJ0V AA19WatchDisplayVariantO
- _symbolic _____y_____yAByAByAByAByABy_____y_____y_____G______Qo______G_____y______pXpGGAJySbGG_____G_____ySbGGAJy_____GGAT_G 7SwiftUI19_ConditionalContentV7StorageO AA08ModifiedD0V AA4ViewPAAE15_containerShapeyQrqd__AA010InsettableI0Rd__lFQO AA01_g9Modifier_D0V 9WidgetKit32CommonActivityArchivingModifiersV AA16RoundedRectangleV AN0o10BackgroundK0V AA022_EnvironmentKeyWritingK0V AA14FontDefinitionP AN0l5IdiomK0V AA01_uv9TransformK0V AA19WatchDisplayVariantO
CStrings:
+ ", shouldShowBackground="
+ "_isActivityFullscreen"
+ "_showsActivityBackground"
+ "isActivityFullscreen"
+ "isFullScreen"
+ "shouldShowBackground"
+ "showsActivityBackground"
```
