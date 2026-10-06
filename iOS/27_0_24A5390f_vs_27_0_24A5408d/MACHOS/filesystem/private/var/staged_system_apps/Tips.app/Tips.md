## Tips

> `/private/var/staged_system_apps/Tips.app/Tips`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8cb9c` | `0x8e0ec` | **`+0x1550`** |
| `__TEXT.__swift5_typeref` | `0x1135e` | `0x11a6e` | **`+0x710`** |
| `__DATA_CONST.__const` | `0x2418` | `0x2688` | **`+0x270`** |
| `__TEXT.__objc_methname` | `0xd69b` | `0xd8cb` | **`+0x230`** |
| `__DATA.__data` | `0x3df0` | `0x3ce0` | **`-0x110`** |
| `__TEXT.__objc_stubs` | `0x8880` | `0x8960` | **`+0xe0`** |
| `__TEXT.__auth_stubs` | `0x3480` | `0x3540` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x5ed0` | `0x5f88` | **`+0xb8`** |
| `__TEXT.__const` | `0x55b4` | `0x5664` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x402c` | `0x40bc` | **`+0x90`** |
| `__DATA.__objc_data` | `0x2820` | `0x28a8` | **`+0x88`** |
| `__TEXT.__cstring` | `0x1dfb` | `0x1e7b` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1eb0` | `0x1f18` | **`+0x68`** |
| `__DATA.__objc_selrefs` | `0x3018` | `0x3078` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x1a50` | `0x1ab0` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x854` | `0x8b4` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x1f68` | `0x1fc0` | **`+0x58`** |
| `__DATA_CONST.__auth_ptr` | `0xf70` | `0xfa0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xf60` | `0xf90` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x355d` | `0x358d` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x244` | `0x260` | **`+0x1c`** |
| `__DATA.__bss` | `0x2ba8` | `0x2bb8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xfb4` | `0xfa4` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xdbc` | `0xdb0` | **`-0xc`** |
| `__DATA.__objc_ivar` | `0x2ec` | `0x2f4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-857.0.0.0.0
+866.0.0.0.0

-  Functions: 3040
-  Symbols:   1684
-  CStrings:  2628
+  Functions: 3089
+  Symbols:   1703
+  CStrings:  2649
Symbols:
+ _$s6TipsUI0A12ContentModelC10collection23forCollectionIdentifierSo13TPSCollectionCSgSSSg_tFTj
+ _$s6TipsUI0A12ContentModelC14overrideWidget4withySo11TPSDocumentC_tF
+ _$s6TipsUI0A12ContentModelC3tip13forIdentifierSo6TPSTipCSgSSSg_tFTj
+ _$s6TipsUI0A12ContentModelCMn
+ _$s7SwiftUI17EnvironmentValuesV31accessibilityReduceTransparencySbvg
+ _$s7SwiftUI17EnvironmentValuesV31accessibilityReduceTransparencySbvpMV
+ _$s7SwiftUI17EnvironmentValuesV9isEnabledSbvg
+ _$s7SwiftUI17EnvironmentValuesV9isEnabledSbvpMV
+ _$s7SwiftUI17EnvironmentValuesV9isEnabledSbvs
+ _$s7SwiftUI32_EnvironmentKeyTransformModifierVMn
+ _$s7SwiftUI32_EnvironmentKeyTransformModifierVyxGAA04ViewF0AAMc
+ _$s7SwiftUI4ViewPAAE22scrollEdgeEffectHidden_3forQrSb_AA0E0O3SetVtF
+ _$s7SwiftUI4ViewPAAE22scrollEdgeEffectHidden_3forQrSb_AA0E0O3SetVtFQOMQ
+ _$s7SwiftUI5LabelV5title4iconACyxq_GxyXE_q_yXEtcfC
+ _$s7SwiftUI5LabelVMn
+ _$s9TipsTryIt0bC14ViewControllerC13logEndSessionyyFTj
+ _$sSS6TipsUIE13tipSaveButtonSSvgZ
+ _$sSS6TipsUIE14tipShareButtonSSvgZ
+ _swift_dynamicCastClass
CStrings:
+ "''"
+ "@\"NSArray\"16@?0@\"NSString\"8"
+ "Set this Collection to Widget"
+ "Set this Tip to Widget"
+ "T@\"NSString\",C,N,V_pendingSearchResultCollectionID"
+ "T@\"NSString\",C,N,V_pendingSearchResultTipID"
+ "Tips.DevModeViewModel"
+ "_pendingSearchResultCollectionID"
+ "_pendingSearchResultTipID"
+ "canSetCollectionAsWidgetForID:"
+ "canSetTipAsWidgetForID:"
+ "checklistTipsProvider"
+ "clearPendingSearchResult"
+ "contentModel"
+ "hasWidgetContent"
+ "initWithContentModel:"
+ "logTryItEndSessionIfNeeded"
+ "pendingSearchResultCollectionID"
+ "pendingSearchResultTipID"
+ "selectDefaultCollectionIfNeeded"
+ "setAccessibilityIdentifier:"
+ "setChecklistTipsProvider:"
+ "setCollectionAsWidgetForID:"
+ "setDebugMenuHandler:"
+ "setPendingSearchResultCollectionID:"
+ "setPendingSearchResultTipID:"
+ "setTipAsWidgetForID:"
+ "statusBarManager"
- "%'"
- "handleGestureForDevMode"
- "handleTripleTapInternalGesture:"
- "overrideWidgetWithTip:"
- "setNumberOfTapsRequired:"
- "setupGestureForDevMode"
- "tipCollectionViewCellHandleTripleTapInternalGesture:"
```
