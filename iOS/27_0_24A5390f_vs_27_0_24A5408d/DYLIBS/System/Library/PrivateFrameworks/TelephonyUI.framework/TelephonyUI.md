## TelephonyUI

> `/System/Library/PrivateFrameworks/TelephonyUI.framework/TelephonyUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x67cac` | `0x69284` | **`+0x15d8`** |
| `__TEXT.__swift5_typeref` | `0x25fd` | `0x296d` | **`+0x370`** |
| `__AUTH_CONST.__const` | `0x1f08` | `0x1fa8` | **`+0xa0`** |
| `__DATA.__data` | `0xf20` | `0xf90` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x28a0` | `0x2900` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x3cc4` | `0x3d14` | **`+0x50`** |
| `__TEXT.__cstring` | `0x2d21` | `0x2d61` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3168` | `0x31a0` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x30` | `0x60` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x6f40` | `0x6f70` | **`+0x30`** |
| `__TEXT.__const` | `0x2b98` | `0x2bc8` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x4a8` | `0x4d8` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xc60` | `0xc88` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1c48` | `0x1c70` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x68` | `0x88` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x8f6` | `0x916` | **`+0x20`** |
| `__AUTH.__data` | `0x888` | `0x898` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xa24` | `0xa30` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x11d0` | `0x11d8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xa60` | `0xa68` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x338` | `0x33c` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x370` | `0x36c` | **`-0x4`** |

### Other Changes

```diff

-147.100.5.2.1
+153.100.1.2.7

-  Functions: 3034
-  Symbols:   3195
-  CStrings:  534
+  Functions: 3052
+  Symbols:   3205
+  CStrings:  537
Symbols:
+ +[TPNumberPadButton containerLayoutHeight]
+ +[TPNumberPadButton effectiveScreenSizeCategory]
+ +[UIAlertController(TelephonyUI) confirmedCarrierOutageAlertControllerWithWiFiCallingNotEnabled:]
+ -[TPCoreTelephonyClient carrierOutageStatusResourceUrl:]
+ -[TPCoreTelephonyClient ctClient]
+ -[TPCoreTelephonyClient showConfirmedOutageAlert:]
+ GCC_except_table28
+ _OBJC_IVAR_$_TPCoreTelephonyClient._ctClient
+ ___block_descriptor_56_e8_32s40s48w_e23_v16?0"UIAlertAction"8lw48l8s32l8s40l8
+ _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE15sensoryFeedback_7trigger9conditionQrAA07SensoryE0V_qd__Sbqd___qd__tctSQRd__lFQOyAA15ModifiedContentVyAA012_ConditionalJ0VyAJyAJyAcAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQOyAJyAJyAA6ZStackVyAA05TupleJ0VyAJyAJyAJyAJyAJyAA06_ShapeC0VyAA7CapsuleVAA5ColorVGAA12_FrameLayoutVGAA12_ScaleEffectVGAA08_PaddingX0VGAA07_OffsetZ0VGAA0O18AttachmentModifierVGSg_AJy09TelephonyB017GlassActionSliderV5TrackVA4_GAJyAJyA18_5ThumbVA10_GAA16_OverlayModifierVyAJyA16_010ThumbInputC033_771A05A3184784DD17FD6AEB15A3A0E0LLVA13_GGGQPGGAA18_AnimationModifierVySbGGAA23_GeometryActionModifierVySo6CGSizeVA42_SQ12CoreGraphicsyHCg_GG_Qo_A13_GA13_GA47_GA13_G_A18_9DragPhaseOQo_HO
+ _symbolic _____yAAy_____yAAyAAy_____y_____yAAyAAyAAyAAyAAy_____y__________G_____G_____G_____G_____G_____GSg_AAy_____AJGAAyAAy_____ANG_____yAAy_____APGGGQPGG_____ySbGG_____y_____A6_SQ12CoreGraphicsyHCg_GG_Qo_APGAPG 7SwiftUI15ModifiedContentV AA4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6ZStackV AA05TupleD0V AA06_ShapeE0V AA7CapsuleV AA5ColorV AA12_FrameLayoutV AA12_ScaleEffectV AA08_PaddingR0V AA07_OffsetT0V AA0I18AttachmentModifierV 09TelephonyB017GlassActionSliderV5TrackV A4_5ThumbV AA08_OverlayX0V A2_010ThumbInputE033_771A05A3184784DD17FD6AEB15A3A0E0LLV AA010_AnimationX0V AA015_GeometryActionX0V So6CGSizeV
+ _symbolic _____y_____yAAyAAy_____yAAyAAy_____y_____yAAyAAyAAyAAyAAy_____y__________G_____G_____G_____G_____G_____GSg_AAy_____AKGAAyAAy_____AOG_____yAAy_____AQGGGQPGG_____ySbGG_____y_____A7_SQ12CoreGraphicsyHCg_GG_Qo_AQGAQGA12_GAQG 7SwiftUI15ModifiedContentV AA012_ConditionalD0V AA4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6ZStackV AA05TupleD0V AA06_ShapeF0V AA7CapsuleV AA5ColorV AA12_FrameLayoutV AA12_ScaleEffectV AA08_PaddingS0V AA07_OffsetU0V AA0J18AttachmentModifierV 09TelephonyB017GlassActionSliderV5TrackV A6_5ThumbV AA08_OverlayY0V A4_010ThumbInputF033_771A05A3184784DD17FD6AEB15A3A0E0LLV AA010_AnimationY0V AA015_GeometryActionY0V So6CGSizeV
+ _symbolic _____y_____yABy_____yAByABy_____y_____yAByAByAByAByABy_____y__________G_____G_____G_____G_____G_____GSg_ABy_____AKGAByABy_____AOG_____yABy_____AQGGGQPGG_____ySbGG_____y_____A7_SQ12CoreGraphicsyHCg_GG_Qo_AQGAQGA12_G 7SwiftUI19_ConditionalContentV AA08ModifiedD0V AA4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6ZStackV AA05TupleD0V AA06_ShapeF0V AA7CapsuleV AA5ColorV AA12_FrameLayoutV AA12_ScaleEffectV AA08_PaddingS0V AA07_OffsetU0V AA0J18AttachmentModifierV 09TelephonyB017GlassActionSliderV5TrackV A6_5ThumbV AA08_OverlayY0V A4_010ThumbInputF033_771A05A3184784DD17FD6AEB15A3A0E0LLV AA010_AnimationY0V AA015_GeometryActionY0V So6CGSizeV
+ _symbolic _____y_____yABy_____yAByABy_____y_____yAByAByAByAByABy_____y__________G_____G_____G_____G_____G_____GSg_ABy_____AKGAByABy_____AOG_____yABy_____AQGGGQPGG_____ySbGG_____y_____A7_SQ12CoreGraphicsyHCg_GG_Qo_AQGAQGA12__G 7SwiftUI19_ConditionalContentV7StorageO AA08ModifiedD0V AA4ViewPAAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6ZStackV AA05TupleD0V AA06_ShapeG0V AA7CapsuleV AA5ColorV AA12_FrameLayoutV AA12_ScaleEffectV AA08_PaddingT0V AA07_OffsetV0V AA0K18AttachmentModifierV 09TelephonyB017GlassActionSliderV5TrackV A8_5ThumbV AA08_OverlayZ0V A6_010ThumbInputG033_771A05A3184784DD17FD6AEB15A3A0E0LLV AA010_AnimationZ0V AA015_GeometryActionZ0V So6CGSizeV
+ _symbolic _____y_____y_____yAAyAAy_____yAAyAAy_____y_____yAAyAAyAAyAAyAAy_____y__________G_____G_____G_____G_____G_____GSg_AAy_____AKGAAyAAy_____AOG_____yAAy_____AQGGGQPGG_____ySbGG_____y_____A7_SQ12CoreGraphicsyHCg_GG_Qo_AQGAQGA12_GAQG______Qo_ 7SwiftUI4ViewPAAE15sensoryFeedback_7trigger9conditionQrAA07SensoryE0V_qd__Sbqd___qd__tctSQRd__lFQO AA15ModifiedContentV AA012_ConditionalJ0V AcAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6ZStackV AA05TupleJ0V AA06_ShapeC0V AA7CapsuleV AA5ColorV AA12_FrameLayoutV AA12_ScaleEffectV AA08_PaddingX0V AA07_OffsetZ0V AA0O18AttachmentModifierV 09TelephonyB017GlassActionSliderV5TrackV A11_5ThumbV AA16_OverlayModifierV A9_010ThumbInputC033_771A05A3184784DD17FD6AEB15A3A0E0LLV AA18_AnimationModifierV AA23_GeometryActionModifierV So6CGSizeV A11_9DragPhaseO
- +[UIAlertController(TelephonyUI) confirmedCarrierOutageAlertControllerWithWiFiCallingNotEnabled]
- GCC_except_table22
- GCC_except_table26
- _get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE15sensoryFeedback_7trigger9conditionQrAA07SensoryE0V_qd__Sbqd___qd__tctSQRd__lFQOyAA15ModifiedContentVyAcAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQOyAJyAJyAA6ZStackVyAA05TupleJ0VyAJyAJyAJyAJyAJyAA06_ShapeC0VyAA7CapsuleVAA5ColorVGAA12_FrameLayoutVGAA12_ScaleEffectVGAA08_PaddingW0VGAA07_OffsetY0VGAA0N18AttachmentModifierVGSg_AJy09TelephonyB017GlassActionSliderV5TrackVA2_GAJyAJyA16_5ThumbVA8_GAA16_OverlayModifierVyAJyA14_010ThumbInputC033_771A05A3184784DD17FD6AEB15A3A0E0LLVA11_GGGQPGGAA18_AnimationModifierVySbGGAA23_GeometryActionModifierVySo6CGSizeVA40_SQ12CoreGraphicsyHCg_GG_Qo_A11_G_A16_9DragPhaseOQo_HO
- _symbolic _____y_____y_____yAAyAAy_____y_____yAAyAAyAAyAAyAAy_____y__________G_____G_____G_____G_____G_____GSg_AAy_____AJGAAyAAy_____ANG_____yAAy_____APGGGQPGG_____ySbGG_____y_____A6_SQ12CoreGraphicsyHCg_GG_Qo_APG______Qo_ 7SwiftUI4ViewPAAE15sensoryFeedback_7trigger9conditionQrAA07SensoryE0V_qd__Sbqd___qd__tctSQRd__lFQO AA15ModifiedContentV AcAE20accessibilityElement8childrenQrAA26AccessibilityChildBehaviorV_tFQO AA6ZStackV AA05TupleJ0V AA06_ShapeC0V AA7CapsuleV AA5ColorV AA12_FrameLayoutV AA12_ScaleEffectV AA08_PaddingW0V AA07_OffsetY0V AA0N18AttachmentModifierV 09TelephonyB017GlassActionSliderV5TrackV A9_5ThumbV AA16_OverlayModifierV A7_010ThumbInputC033_771A05A3184784DD17FD6AEB15A3A0E0LLV AA18_AnimationModifierV AA23_GeometryActionModifierV So6CGSizeV A9_9DragPhaseO
CStrings:
+ "CarrierOutageAwareness"
+ "CarrierOutageStatusResourceUrl"
+ "ShowConfirmedOutageInCallAlertUI"
+ "https://"
- "https://www.att.com/outages"
```
