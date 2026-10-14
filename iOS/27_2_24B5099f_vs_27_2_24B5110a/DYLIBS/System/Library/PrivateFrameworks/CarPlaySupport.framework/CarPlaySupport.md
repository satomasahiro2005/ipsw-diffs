## CarPlaySupport

> `/System/Library/PrivateFrameworks/CarPlaySupport.framework/CarPlaySupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17ab68` | `0x17b7e4` | **`+0xc7c`** |
| `__DATA.__data` | `0x4490` | `0x4510` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x31d8` | `0x3218` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x1290` | `0x12c8` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0xc1a4` | `0xc1dc` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x235b0` | `0x235e0` | **`+0x30`** |
| `__AUTH.__objc_data` | `0x5328` | `0x5350` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x1184` | `0x11a8` | **`+0x24`** |
| `__TEXT.__constg_swiftt` | `0x1d90` | `0x1db0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x7328` | `0x7340` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x3bb8` | `0x3bc8` | **`+0x10`** |
| `__TEXT.__const` | `0x3f24` | `0x3f14` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0xd8c` | `0xd9c` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x19b0` | `0x19b8` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x36c` | `0x374` | **`+0x8`** |

### Other Changes

```diff

-552.6.2.0.0
+552.7.1.0.0

-  Functions: 6339
-  Symbols:   12875
+  Functions: 6369
+  Symbols:   12926
Symbols:
+ -[CPSGridTemplateViewController viewDidLayoutSubviews]
+ -[CPSMapTemplateViewController(Panel) _dismissPanelAnimated:panels:]
+ _$s14CarPlaySupport23GridTemplateHostingViewC08makeRootG033_D13C162E7E65F016B27B4910C0BDA168LLAA07CPSGrideG0VyF
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvM
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvM.resume
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvMTj
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvMTq
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvW
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvg
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvgTj
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvgTo
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvgTq
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvpACTk
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvpMV
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvpWvd
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvs
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvsTj
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvsTo
+ _$s14CarPlaySupport23GridTemplateHostingViewC12templateSizeSo6CGSizeVvsTq
+ _$s14CarPlaySupport24GridButtonActionHandling_pSgMR
+ _$s14CarPlaySupport24GridButtonActionHandling_pSgMd
+ _$s14CarPlaySupport24GridButtonActionHandling_pSgWOcTm
+ _$s7SwiftUI12_FrameLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI12_FrameLayoutVAcA12ViewModifierAAWL
+ _$s7SwiftUI12_FrameLayoutVAcA12ViewModifierAAWl
+ _$s7SwiftUI12_FrameLayoutVN
+ _$s7SwiftUI14_OpacityEffectVAA12ViewModifierAAMc
+ _$s7SwiftUI14_OpacityEffectVAcA12ViewModifierAAWL
+ _$s7SwiftUI14_OpacityEffectVAcA12ViewModifierAAWl
+ _$s7SwiftUI14_OpacityEffectVN
+ _$s7SwiftUI14_PaddingLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI14_PaddingLayoutVAcA12ViewModifierAAWL
+ _$s7SwiftUI14_PaddingLayoutVAcA12ViewModifierAAWl
+ _$s7SwiftUI14_PaddingLayoutVN
+ _$s7SwiftUI15ModifiedContentVy14CarPlaySupport18AdditionalInfoView33_9EBDA4763611E3AED5BD15069ADB5F53LLVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGACyxq_GAA0J0A2aPRzAA0jT0R_rlWlTm
+ _$s7SwiftUI15ModifiedContentVyAA5ImageVAA14_PaddingLayoutVGACyxq_GAA4ViewA2aJRzAA0H8ModifierR_rlWlTm
+ _$s7SwiftUI15ModifiedContentVyACyAA4ViewPAAE11buttonStyleyQrqd__AA06ButtonG0Rd__lFQOyAA0H0VyACyAA6VStackVyAA012_ConditionalD0VyAMyACyACyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA12_FrameLayoutVGAE07CarPlayB0E20cpuiPrimaryTextColor13isHighlighted0Y7EnabledQrSb_SbtFQOyAY_Qo_GACyACyAoA012_AspectRatioR0VGAXGGSgGAA08_PaddingR0VGG_AZ30CPUISwiftUIButtonConfigurationO09GridPanelhG0VQo_AA05_FlexqR0VGAXGACyxq_GAad2aDRzAA0eO0R_rlWl
+ _$s7SwiftUI15ModifiedContentVyACyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA12_FrameLayoutVGACyxq_GAA4ViewA2aQRzAA0mI0R_rlWl
+ _$s7SwiftUI16_FlexFrameLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI16_FlexFrameLayoutVAcA12ViewModifierAAWL
+ _$s7SwiftUI16_FlexFrameLayoutVAcA12ViewModifierAAWl
+ _$s7SwiftUI16_FlexFrameLayoutVN
+ _$s7SwiftUI18_AspectRatioLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI18_AspectRatioLayoutVAcA12ViewModifierAAWL
+ _$s7SwiftUI18_AspectRatioLayoutVAcA12ViewModifierAAWl
+ _$s7SwiftUI18_AspectRatioLayoutVN
+ _$s7SwiftUI4TextVAA4ViewAAMc
+ _$s7SwiftUI4TextVAcA4ViewAAWL
+ _$s7SwiftUI4TextVAcA4ViewAAWl
+ _$s7SwiftUI5ColorVAA10ShapeStyleAAMc
+ _$s7SwiftUI5ColorVAA4ViewAAMc
+ _$s7SwiftUI5ColorVAcA10ShapeStyleAAWL
+ _$s7SwiftUI5ColorVAcA10ShapeStyleAAWl
+ _$s7SwiftUI5ColorVAcA4ViewAAWL
+ _$s7SwiftUI5ColorVAcA4ViewAAWl
+ _$s7SwiftUI5ImageVAA4ViewAAMc
+ _$s7SwiftUI5ImageVAcA4ViewAAWL
+ _$s7SwiftUI5ImageVAcA4ViewAAWl
+ _$s7SwiftUI9EmptyViewVAA0D0AAMc
+ _$s7SwiftUI9EmptyViewVAcA0D0AAWL
+ _$s7SwiftUI9EmptyViewVAcA0D0AAWl
+ _$s7SwiftUI9EmptyViewVN
+ _$s9CarPlayUI30CPUISwiftUIButtonConfigurationO23GridTemplateButtonStyleV5title8subtitle11strokeWidth19fillsAvailableSpace9isCompactAESSSg_AK12CoreGraphics7CGFloatVS2btcfC
+ _$s9CarPlayUI30CPUISwiftUIButtonConfigurationO23GridTemplateButtonStyleV9isCompact7forSizeSbSo6CGSizeV_tFZ
+ _$sS2i7SwiftUI18_FormatSpecifiableAAWL
+ _$sS2i7SwiftUI18_FormatSpecifiableAAWl
+ _$sSi7SwiftUI18_FormatSpecifiableAAMc
+ _$ss5NeverO7SwiftUI4ViewACMc
+ _$ss5NeverOAB7SwiftUI4ViewACWL
+ _$ss5NeverOAB7SwiftUI4ViewACWl
+ _$ss5NeverON
+ ___68-[CPSMapTemplateViewController(Panel) _dismissPanelAnimated:panels:]_block_invoke
+ ___68-[CPSMapTemplateViewController(Panel) _dismissPanelAnimated:panels:]_block_invoke_2
+ ___68-[CPSMapTemplateViewController(Panel) _dismissPanelAnimated:panels:]_block_invoke_3
+ ___swift_memcpy48_8
- GCC_except_table5
- _$s14CarPlaySupport19CPSGridTemplateViewV4bodyQrvg7SwiftUI0F0PAEE5frame5width6height9alignmentQr12CoreGraphics7CGFloatVSg_AoE9AlignmentVtFQOyAE6VStackVyAE7ForEachVySaySi6offset_SayAA24GridButtonRepresentationCG7elementtGSiAE6HStackVyAE12TupleContentVyAUyAY10Foundation4UUIDVAA0vw4ItemF033_D13C162E7E65F016B27B4910C0BDA168LLVG_AUySnySiGSiAgEEAhijKQrAO_AoQtFQOyAE5ColorV_Qo_GQPGGGG_Qo_AE13GeometryProxyVcfU_A18_yXEfU_
- _$s7SwiftUI12_FrameLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI14_OpacityEffectVAA12ViewModifierAAWP
- _$s7SwiftUI14_PaddingLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI15ModifiedContentVy14CarPlaySupport16LabeledValueView33_9EBDA4763611E3AED5BD15069ADB5F53LLVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGACyxq_GAA0J0A2aPRzAA0jT0R_rlWlTm
- _$s7SwiftUI15ModifiedContentVyAA5ImageVAA12_FrameLayoutVGACyxq_GAA4ViewA2aJRzAA0H8ModifierR_rlWlTm
- _$s7SwiftUI15ModifiedContentVyACyAA5ImageVAA30_EnvironmentKeyWritingModifierVyAA4FontVSgGGAA12_FrameLayoutVGACyxq_GAA4ViewA2aQRzAA0mI0R_rlWlTm
- _$s7SwiftUI16_FlexFrameLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI18_AspectRatioLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI4TextVAA4ViewAAWP
- _$s7SwiftUI5ColorVAA10ShapeStyleAAWP
- _$s7SwiftUI5ColorVAA4ViewAAWP
- _$s7SwiftUI5ImageVAA4ViewAAWP
- _$s7SwiftUI6ZStackVyAA12TupleContentVyAA012_ConditionalE0VyAA08ModifiedE0VyAIyAIyAA5ImageVAA18_AspectRatioLayoutVGAA30_EnvironmentKeyWritingModifierVyAA5ColorVSgGGAA010_FlexFrameK0VGAIyAnWGGSg_AIyAIyAA10_ShapeViewVyAA6CircleVARGAA01_rK0VGAA13_OffsetEffectVGSgQPGGWOcTm
- _$s7SwiftUI9EmptyViewVAA0D0AAWP
- _$s9CarPlayUI30CPUISwiftUIButtonConfigurationO23GridTemplateButtonStyleV5title8subtitle11strokeWidth19fillsAvailableSpaceAESSSg_AJ12CoreGraphics7CGFloatVSbtcfC
- _$sSi7SwiftUI18_FormatSpecifiableAAWP
- _$ss5NeverO7SwiftUI4ViewACWP
- ___67-[CPSMapTemplateViewController(Panel) _dismissPanelAnimated:panel:]_block_invoke
- ___67-[CPSMapTemplateViewController(Panel) _dismissPanelAnimated:panel:]_block_invoke_2
- ___67-[CPSMapTemplateViewController(Panel) _dismissPanelAnimated:panel:]_block_invoke_3
- ___swift_memcpy32_8
- _swift_unknownObjectRetain_n
```
