## SequoiaTranslator

> `/private/var/staged_system_apps/SequoiaTranslator.app/SequoiaTranslator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x306f78` | `0x3084b8` | **`+0x1540`** |
| `__DATA.__data` | `0x15d10` | `0x15de0` | **`+0xd0`** |
| `__DATA_CONST.__got` | `0x2068` | `0x20d0` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x8cb0` | `0x8d08` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x8130` | `0x8170` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x40a0` | `0x40c0` | **`+0x20`** |
| `__TEXT.__const` | `0x20124` | `0x20134` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-396.0.0.0.0
+396.1.0.0.0

-  Functions: 13199
-  Symbols:   3847
+  Functions: 13227
+  Symbols:   3863
Symbols:
+ _$s7SwiftUI12_FrameLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI12_ScaleEffectVAA12ViewModifierAAMc
+ _$s7SwiftUI12_ScaleEffectVN
+ _$s7SwiftUI14_OpacityEffectVAA12ViewModifierAAMc
+ _$s7SwiftUI14_OpacityEffectVN
+ _$s7SwiftUI14_PaddingLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI14_PaddingLayoutVN
+ _$s7SwiftUI15_RotationEffectVAA12ViewModifierAAMc
+ _$s7SwiftUI15_RotationEffectVN
+ _$s7SwiftUI16_FixedSizeLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI16_FixedSizeLayoutVN
+ _$s7SwiftUI16_FlexFrameLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI17_Rotation3DEffectVAA12ViewModifierAAMc
+ _$s7SwiftUI17_Rotation3DEffectVN
+ _$s7SwiftUI18_AspectRatioLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI18_AspectRatioLayoutVN
+ _$s7SwiftUI20_GeometryGroupEffectVAA12ViewModifierAAMc
+ _$s7SwiftUI20_GeometryGroupEffectVN
+ _$s7SwiftUI22HierarchicalShapeStyleVAA0dE0AAMc
+ _$s7SwiftUI25_AlignmentWritingModifierVAA04ViewE0AAMc
+ _$s7SwiftUI25_AlignmentWritingModifierVN
+ _$s7SwiftUI25_AllowsHitTestingModifierVAA04ViewF0AAMc
+ _$s7SwiftUI25_AllowsHitTestingModifierVN
+ _$s7SwiftUI25_AppearanceActionModifierVAA04ViewE0AAMc
+ _$s7SwiftUI25_AppearanceActionModifierVN
+ _$s7SwiftUI30_SafeAreaRegionsIgnoringLayoutVAA12ViewModifierAAMc
+ _$s7SwiftUI30_SafeAreaRegionsIgnoringLayoutVN
+ _$s7SwiftUI4TextVAA4ViewAAMc
+ _$s7SwiftUI5ColorVAA10ShapeStyleAAMc
+ _$s7SwiftUI5ColorVAA4ViewAAMc
+ _$s7SwiftUI5ImageVAA4ViewAAMc
+ _$s7SwiftUI8MaterialVAA10ShapeStyleAAMc
+ _$s7SwiftUI9EmptyViewVAA0D0AAMc
+ _$sSS18_uncheckedFromUTF8ySSSRys5UInt8VGFZ
+ _$sSS8UTF8ViewV13_foreignIndex5afterSS0D0VAF_tF
+ _$sSS8UTF8ViewV17_foreignSubscript8positions5UInt8VSS5IndexV_tF
+ _$sSd7SwiftUI16VectorArithmeticAAMc
+ _$sSf7SwiftUI16VectorArithmeticAAMc
+ _$sSs8UTF8ViewV8distance4from2toSiSS5IndexV_AGtF
+ _$ss5NeverO7SwiftUI4ViewACMc
- _$s7SwiftUI12_FrameLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI12_ScaleEffectVAA12ViewModifierAAWP
- _$s7SwiftUI14_OpacityEffectVAA12ViewModifierAAWP
- _$s7SwiftUI14_PaddingLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI15_RotationEffectVAA12ViewModifierAAWP
- _$s7SwiftUI16_FixedSizeLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI16_FlexFrameLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI17_Rotation3DEffectVAA12ViewModifierAAWP
- _$s7SwiftUI18_AspectRatioLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI20_GeometryGroupEffectVAA12ViewModifierAAWP
- _$s7SwiftUI22HierarchicalShapeStyleVAA0dE0AAWP
- _$s7SwiftUI25_AlignmentWritingModifierVAA04ViewE0AAWP
- _$s7SwiftUI25_AllowsHitTestingModifierVAA04ViewF0AAWP
- _$s7SwiftUI25_AppearanceActionModifierVAA04ViewE0AAWP
- _$s7SwiftUI30_SafeAreaRegionsIgnoringLayoutVAA12ViewModifierAAWP
- _$s7SwiftUI4TextVAA4ViewAAWP
- _$s7SwiftUI5ColorVAA10ShapeStyleAAWP
- _$s7SwiftUI5ColorVAA4ViewAAWP
- _$s7SwiftUI5ImageVAA4ViewAAWP
- _$s7SwiftUI8MaterialVAA10ShapeStyleAAWP
- _$s7SwiftUI9EmptyViewVAA0D0AAWP
- _$sSd7SwiftUI16VectorArithmeticAAWP
- _$sSf7SwiftUI16VectorArithmeticAAWP
- _$ss5NeverO7SwiftUI4ViewACWP
CStrings:
+ "2026-10-04 03:28:32"
+ "B515d-Translate-CL19"
- "2026-09-28 01:40:15"
- "B515d-Translate-CL18"
```
