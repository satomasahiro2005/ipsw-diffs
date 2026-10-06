## PhotosUIFoundation

> `/System/Library/PrivateFrameworks/PhotosUIFoundation.framework/PhotosUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf108c` | `0xf298c` | **`+0x1900`** |
| `__TEXT.__swift5_typeref` | `0x2ad4` | `0x2c74` | **`+0x1a0`** |
| `__DATA.__bss` | `0x65c0` | `0x6750` | **`+0x190`** |
| `__TEXT.__const` | `0x6c00` | `0x6d80` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0x5b40` | `0x5c90` | **`+0x150`** |
| `__AUTH_CONST.__objc_const` | `0x1ef00` | `0x1efb8` | **`+0xb8`** |
| `__TEXT.__constg_swiftt` | `0x37dc` | `0x387c` | **`+0xa0`** |
| `__DATA.__data` | `0x45c8` | `0x4658` | **`+0x90`** |
| `__TEXT.__cstring` | `0xb947` | `0xb9d6` | **`+0x8f`** |
| `__AUTH_CONST.__cfstring` | `0x7d40` | `0x7dc0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0xfaf4` | `0xfb64` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x55a0` | `0x5610` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0xcbc` | `0xd28` | **`+0x6c`** |
| `__DATA_CONST.__objc_selrefs` | `0x7758` | `0x77b0` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0x18f0` | `0x1930` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x196a` | `0x1936` | **`-0x34`** |
| `__DATA_CONST.__got` | `0xe40` | `0xe70` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x928` | `0x958` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x1a7c` | `0x1a98` | **`+0x1c`** |
| `__TEXT.__swift5_reflstr` | `0x16e7` | `0x16f7` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x388` | `0x394` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x10d8` | `0x10e0` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x3ee0` | `0x3ee8` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x50` | `0x48` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x24c` | `0x250` | **`+0x4`** |

### Other Changes

```diff

-910.14.107.0.0
+910.21.101.0.0

-  Functions: 9385
-  Symbols:   11050
-  CStrings:  1577
+  Functions: 9427
+  Symbols:   11079
+  CStrings:  1579
Symbols:
+ +[PXAssetActionMenuBuilder _submenuWithTitle:systemImageName:actionTypes:actionManager:topRowActionTypesSet:titleOverrides:]
+ +[PXBadgeHelper commentsBadgeImageMini]
+ +[PXBadgeHelper commentsBadgeImage]
+ -[PXAlertConfiguration copyFrom:]
+ -[PXUserDefaults setSharedAlbumShowCommentBadges:]
+ -[PXUserDefaults sharedAlbumShowCommentBadges]
+ -[UIColor(PhotosUIFoundation) px_grayscaleColor]
+ -[UIScrollView(PhotosUICore) px_setPocketPreferredUserInterfaceStyleForVerticalEdges:]
+ -[UIScrollView(PhotosUICore) px_setSoftPocketStyleForTopEdge]
+ GCC_except_table1129
+ GCC_except_table1133
+ GCC_except_table1136
+ GCC_except_table1139
+ GCC_except_table1147
+ GCC_except_table1151
+ GCC_except_table1170
+ GCC_except_table1176
+ GCC_except_table1238
+ GCC_except_table1303
+ GCC_except_table1565
+ GCC_except_table1575
+ GCC_except_table1600
+ GCC_except_table1626
+ GCC_except_table2147
+ GCC_except_table2235
+ GCC_except_table2399
+ GCC_except_table2615
+ GCC_except_table2650
+ GCC_except_table2677
+ GCC_except_table2945
+ GCC_except_table3043
+ GCC_except_table3045
+ GCC_except_table3098
+ GCC_except_table3112
+ GCC_except_table3116
+ GCC_except_table3123
+ GCC_except_table3130
+ GCC_except_table3145
+ GCC_except_table3152
+ GCC_except_table316
+ GCC_except_table3166
+ GCC_except_table3435
+ GCC_except_table3470
+ GCC_except_table3491
+ GCC_except_table3573
+ GCC_except_table3608
+ GCC_except_table3639
+ GCC_except_table3643
+ GCC_except_table3659
+ GCC_except_table3706
+ GCC_except_table3722
+ GCC_except_table4019
+ GCC_except_table4029
+ GCC_except_table4092
+ GCC_except_table411
+ GCC_except_table412
+ GCC_except_table4246
+ GCC_except_table431
+ GCC_except_table4357
+ GCC_except_table4383
+ GCC_except_table4534
+ GCC_except_table464
+ GCC_except_table4653
+ GCC_except_table4932
+ GCC_except_table4934
+ GCC_except_table4945
+ GCC_except_table4948
+ GCC_except_table4972
+ GCC_except_table4980
+ GCC_except_table4984
+ GCC_except_table4988
+ GCC_except_table5021
+ GCC_except_table5080
+ GCC_except_table5106
+ GCC_except_table5147
+ _OBJC_IVAR_$_PXEventCoalescer._observersLock
+ _OBJC_IVAR_$_PXUserDefaults._sharedAlbumShowCommentBadges
+ _OUTLINED_FUNCTION_33
+ _OUTLINED_FUNCTION_34
+ _PXAssetActionTypeInternalFileRadar
+ _PXSharedAlbumCommentSFSymbolName
+ _PXUserDefaultsSharedAlbumShowCommentBadges
+ _UIAccessibilityTraitSelected
+ _associated conformance 18PhotosUIFoundation15PXAlertModifier33_560F926B1A7EF4E97A61120783104EB7LLV7SwiftUI04ViewD0AA4BodyAeFP_AE0N0
+ _get_witness_table 7SwiftUI4ViewRzlAA15ModifiedContentVyx18PhotosUIFoundation15PXAlertModifier33_560F926B1A7EF4E97A61120783104EB7LLVGAaBHPxAaBHD1__AhA0cI0HPyHCHC
+ _get_witness_table qd0__7SwiftUI4ViewHD5_AaBPAAE5alert_11isPresented7actions7messageQrqd___AA7BindingVySbGqd_0_yXEqd_1_yXEtSyRd__AaBRd_0_AaBRd_1_r1_lFQOyAA01_C16Modifier_ContentVy18PhotosUIFoundation07PXAlertJ033_560F926B1A7EF4E97A61120783104EB7LLVG_SSAA7ForEachVySaySo0N6ActionCGAucAE16keyboardShortcutyQrAA08KeyboardZ0VSgFQOyAA6ButtonVyAA4TextVG_Qo_GSgA2_SgQo_HO
+ _symbolic SaySo13PXAlertActionCG
+ _symbolic Sbz_Xx
+ _symbolic So13PXAlertActionC
+ _symbolic So13PXAlertActionCSg
+ _symbolic _____ 18PhotosUIFoundation15PXAlertModifier33_560F926B1A7EF4E97A61120783104EB7LLV
+ _symbolic _____Sg 7SwiftUI10ButtonRoleV
+ _symbolic _____Sg 7SwiftUI16KeyboardShortcutV
+ _symbolic _____Sg 7SwiftUI4TextV
+ _symbolic _____ySaySo13PXAlertActionCGAC_____y_____y_____G_Qo_G 7SwiftUI7ForEachV AA4ViewPAAE16keyboardShortcutyQrAA08KeyboardG0VSgFQO AA6ButtonV AA4TextV
+ _symbolic _____ySaySo13PXAlertActionCGAC_____y_____y_____G_Qo_GSg 7SwiftUI7ForEachV AA4ViewPAAE16keyboardShortcutyQrAA08KeyboardG0VSgFQO AA6ButtonV AA4TextV
+ _symbolic _____ySo20PXAlertConfigurationCSgG 7SwiftUI7BindingV
+ _symbolic _____y_____G 7SwiftUI21_ViewModifier_ContentV 18PhotosUIFoundation07PXAlertD033_560F926B1A7EF4E97A61120783104EB7LLV
+ _symbolic _____y_____G 7SwiftUI6ButtonV AA4TextV
+ _symbolic _____y_____y_____G_Qo_ 7SwiftUI4ViewPAAE16keyboardShortcutyQrAA08KeyboardE0VSgFQO AA6ButtonV AA4TextV
+ _symbolic _____y_____y_____G_SS_____ySaySo13PXAlertActionCGAF_____y_____y_____G_Qo_GSgAISgQo_ 7SwiftUI4ViewPAAE5alert_11isPresented7actions7messageQrqd___AA7BindingVySbGqd_0_yXEqd_1_yXEtSyRd__AaBRd_0_AaBRd_1_r1_lFQO AA01_C16Modifier_ContentV 18PhotosUIFoundation07PXAlertJ033_560F926B1A7EF4E97A61120783104EB7LLV AA7ForEachV AcAE16keyboardShortcutyQrAA08KeyboardY0VSgFQO AA6ButtonV AA4TextV
+ _symbolic _____yx_____G 7SwiftUI15ModifiedContentV 18PhotosUIFoundation15PXAlertModifier33_560F926B1A7EF4E97A61120783104EB7LLV
+ _type_layout_string 18PhotosUIFoundation15PXAlertModifier33_560F926B1A7EF4E97A61120783104EB7LLV
- -[UIScrollView(PhotosUICore) px_setPhotosPocketStyleForAllEdges]
- -[UIScrollView(PhotosUICore) px_setPocketPreferredUserInterfaceStyleForAllEdges:]
- GCC_except_table1127
- GCC_except_table1131
- GCC_except_table1134
- GCC_except_table1137
- GCC_except_table1145
- GCC_except_table1149
- GCC_except_table1156
- GCC_except_table1174
- GCC_except_table1236
- GCC_except_table1301
- GCC_except_table1563
- GCC_except_table1573
- GCC_except_table1598
- GCC_except_table1624
- GCC_except_table2146
- GCC_except_table2234
- GCC_except_table2398
- GCC_except_table2614
- GCC_except_table2648
- GCC_except_table2676
- GCC_except_table2944
- GCC_except_table3042
- GCC_except_table3044
- GCC_except_table3096
- GCC_except_table3110
- GCC_except_table3114
- GCC_except_table3121
- GCC_except_table3128
- GCC_except_table314
- GCC_except_table3143
- GCC_except_table3150
- GCC_except_table3164
- GCC_except_table3433
- GCC_except_table3468
- GCC_except_table3489
- GCC_except_table3569
- GCC_except_table3606
- GCC_except_table3637
- GCC_except_table3641
- GCC_except_table3657
- GCC_except_table3704
- GCC_except_table3720
- GCC_except_table4015
- GCC_except_table4025
- GCC_except_table4088
- GCC_except_table409
- GCC_except_table410
- GCC_except_table4242
- GCC_except_table429
- GCC_except_table4352
- GCC_except_table4373
- GCC_except_table4529
- GCC_except_table462
- GCC_except_table4648
- GCC_except_table4927
- GCC_except_table4929
- GCC_except_table4940
- GCC_except_table4943
- GCC_except_table4962
- GCC_except_table4975
- GCC_except_table4979
- GCC_except_table4983
- GCC_except_table5016
- GCC_except_table5075
- GCC_except_table5101
- GCC_except_table5142
- _PXAssetActionTypeInternalFileRadarForSharedLibrary
- _PXBarItemIdentifierToggleSidebar
- _PXSolariumMetricsEnabled
- _PXSolariumMetricsEnabled.isEnabled
- _PXSolariumMetricsEnabled.once
- ___PXSolariumMetricsEnabled_block_invoke
CStrings:
+ "CONTEXT_MENU_MOVE_TO_PERSONAL_LIBRARY_TITLE"
+ "CONTEXT_MENU_MOVE_TO_SHARED_LIBRARY_TITLE"
+ "CONTEXT_MENU_MOVE_TO_SUBMENU_TITLE"
+ "PXAssetActionTypeInternalFileRadar"
+ "PhotosUIFoundation/PXAlert+SwiftUI.swift"
+ "sharedAlbumShowCommentBadges"
+ "text.bubble"
+ "\xf0\x91"
- "Calistoga"
- "PXAssetActionTypeInternalFileRadarForSharedLibrary"
- "PXBarItemIdentifierToggleSidebar"
- "SwiftUI"
- "UIScrollEdgeEffectStyle._photosStyle is unavailable"
- "\xf0\x81"
```
