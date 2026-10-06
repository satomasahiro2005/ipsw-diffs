## MobileSafari

> `/System/Library/PrivateFrameworks/MobileSafari.framework/MobileSafari`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4eaedc` | `0x4fbc74` | **`+0x10d98`** |
| `__TEXT.__eh_frame` | `0x8e74` | `0x9654` | **`+0x7e0`** |
| `__AUTH_CONST.__const` | `0x20e98` | `0x21358` | **`+0x4c0`** |
| `__TEXT.__cstring` | `0x13529` | `0x13939` | **`+0x410`** |
| `__AUTH_CONST.__objc_const` | `0x3b328` | `0x3b638` | **`+0x310`** |
| `__TEXT.__swift5_typeref` | `0xd10e` | `0xd3e6` | **`+0x2d8`** |
| `__DATA.__data` | `0xe278` | `0xe518` | **`+0x2a0`** |
| `__TEXT.__unwind_info` | `0x12448` | `0x126c8` | **`+0x280`** |
| `__TEXT.__const` | `0x1cd24` | `0x1cf34` | **`+0x210`** |
| `__TEXT.__swift5_reflstr` | `0xc721` | `0xc911` | **`+0x1f0`** |
| `__TEXT.__constg_swiftt` | `0x11e54` | `0x1201c` | **`+0x1c8`** |
| `__TEXT.__objc_methlist` | `0x1cb90` | `0x1cd58` | **`+0x1c8`** |
| `__TEXT.__swift5_capture` | `0x7224` | `0x7384` | **`+0x160`** |
| `__DATA_CONST.__got` | `0x29a8` | `0x2af0` | **`+0x148`** |
| `__TEXT.__swift5_fieldmd` | `0x9b44` | `0x9c58` | **`+0x114`** |
| `__AUTH.__objc_data` | `0x10dd0` | `0x10ee0` | **`+0x110`** |
| `__AUTH_CONST.__auth_got` | `0x3998` | `0x3aa0` | **`+0x108`** |
| `__DATA_CONST.__objc_selrefs` | `0x10400` | `0x104a8` | **`+0xa8`** |
| `__DATA_CONST.__const` | `0x65c8` | `0x6648` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x4849` | `0x48b9` | **`+0x70`** |
| `__TEXT.__swift_as_cont` | `0x4e4` | `0x554` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0x7840` | `0x77dc` | **`-0x64`** |
| `__AUTH.__data` | `0x7fb8` | `0x8018` | **`+0x60`** |
| `__DATA_CONST.__objc_protolist` | `0x788` | `0x7b8` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x388` | `0x3ac` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0xab60` | `0xab80` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x260` | `0x278` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x44c` | `0x460` | **`+0x14`** |
| `__DATA.__bss` | `0x20e80` | `0x20e90` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x1840` | `0x1830` | **`-0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x4a88` | `0x4a98` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x968` | `0x974` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x4c0` | `0x4cc` | **`+0xc`** |
| `__DATA.__common` | `0xcc9` | `0xcd1` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x180` | `0x178` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x10b0` | `0x10b8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x11c0` | `0x11c4` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0xd8` | `0xdc` | **`+0x4`** |

### Other Changes

```diff

-625.1.24.10.1
+625.1.29.10.3

+  - /System/Library/Frameworks/Network.framework/Network

-  Functions: 26894
-  Symbols:   20258
-  CStrings:  2694
+  Functions: 27078
+  Symbols:   20320
+  CStrings:  2709
Symbols:
+ -[SFTipsCoordinator presentClusterOnboardingTipFrom:in:]
+ -[SFTipsCoordinator userDidOpenRelatedTabsViewWithCompletion:]
+ -[SFUnifiedTabBarItemView _postClusteringAccessoryButtonDidBecomeVisibleNotificationIfNeeded]
+ -[SFUnifiedTabBarMetrics maximumPinnedItemCount]
+ -[UIApplication(MobileSafariFrameworkExtras) safari_supportsOpenInNewWindow]
+ GCC_except_table179
+ GCC_except_table203
+ GCC_except_table207
+ GCC_except_table211
+ GCC_except_table223
+ _OBJC_CLASS_$_UISpringLoadedInteraction
+ _OBJC_CLASS_$__TtCC12MobileSafari35SFBookmarksCollectionViewController14ShrinkWrapCell
+ _OBJC_METACLASS_$__TtCC12MobileSafari35SFBookmarksCollectionViewController14ShrinkWrapCell
+ _SFClusteringAccessoryButtonDidBecomeVisibleNotification
+ _WBSStartPageSectionTrialRecentSearches
+ _WBSTabClusteringPolicyKey
+ __DATA__TtCC12MobileSafari35SFBookmarksCollectionViewController14ShrinkWrapCell
+ __INSTANCE_METHODS__TtCC12MobileSafari21SFFluidCollectionView21SpringLoadCoordinator
+ __INSTANCE_METHODS__TtCC12MobileSafari35SFBookmarksCollectionViewController14ShrinkWrapCell
+ __IVARS__TtCC12MobileSafari21SFFluidCollectionView21SpringLoadCoordinator
+ __IVARS__TtCC12MobileSafari35SFBookmarksCollectionViewController14ShrinkWrapCell
+ __METACLASS_DATA__TtCC12MobileSafari35SFBookmarksCollectionViewController14ShrinkWrapCell
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UISpringLoadedInteractionBehavior
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TabSnapshotMetadataStoring
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_UISpringLoadedInteractionBehavior
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_UISpringLoadedInteractionEffect
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TabSnapshotMetadataStoring
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UISpringLoadedInteractionBehavior
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UISpringLoadedInteractionEffect
+ __OBJC_$_PROTOCOL_REFS_TabSnapshotMetadataStoring
+ __OBJC_$_PROTOCOL_REFS_UISpringLoadedInteractionBehavior
+ __OBJC_$_PROTOCOL_REFS_UISpringLoadedInteractionEffect
+ __OBJC_LABEL_PROTOCOL_$_TabSnapshotMetadataStoring
+ __OBJC_LABEL_PROTOCOL_$_UISpringLoadedInteractionBehavior
+ __OBJC_LABEL_PROTOCOL_$_UISpringLoadedInteractionEffect
+ __OBJC_PROTOCOL_$_TabSnapshotMetadataStoring
+ __OBJC_PROTOCOL_$_UISpringLoadedInteractionBehavior
+ __OBJC_PROTOCOL_$_UISpringLoadedInteractionEffect
+ __PROTOCOLS__TtCC12MobileSafari21SFFluidCollectionView21SpringLoadCoordinator
+ ___62-[SFStartPageCollectionViewController reloadSection:animated:]_block_invoke
+ ___95-[SFUnifiedTabBarLayout _scrollSlowingLayoutInfoForItemAtIndex:withLayoutInfo:activeItemFrame:]_block_invoke
+ ___95-[SFUnifiedTabBarLayout _scrollSlowingLayoutInfoForItemAtIndex:withLayoutInfo:activeItemFrame:]_block_invoke_2
+ ___95-[SFUnifiedTabBarLayout _scrollSlowingLayoutInfoForItemAtIndex:withLayoutInfo:activeItemFrame:]_block_invoke_3
+ ___block_descriptor_32_e8_d16?0d8l
+ ___block_descriptor_40_e8_32s_e8_d16?0d8ls32l8
+ ___block_descriptor_48_e8_32bs40bs_e8_d16?0d8ls32l8s40l8
+ ___swift_closure_destructor.126Tm
+ ___swift_closure_destructor.339Tm
+ ___swift_closure_destructor.345Tm
+ ___swift_closure_destructor.404Tm
+ ___swift_closure_destructor.407Tm
+ ___swift_closure_destructor.88Tm
+ ___swift_memcpy216_8
+ ___unnamed_66
+ ___unnamed_68
+ _flat unique 12MobileSafari39SFFluidCollectionViewSpringLoadDelegate_pq_4ItemAA0cdE10SupportingPRts_x7SectionAERtsq0_13SupplementaryAERtsXP
+ _flat unique So31UISpringLoadedInteractionEffect_p
+ _flat unique So33UISpringLoadedInteractionBehavior_p
+ _symbolic $s12MobileSafari39SFFluidCollectionViewSpringLoadDelegateP
+ _symbolic So16UIViewControllerCIgg_
+ _symbolic So16UIViewControllerCSgXwz_Xx
+ _symbolic So24SFNotifyMeWhenControllerCXDXMT
+ _symbolic So25UISpringLoadedInteractionCSg
+ _symbolic So6UIViewCSgXwz_Xx
+ _symbolic _____ 12MobileSafari21SFFluidCollectionViewC21SpringLoadCoordinatorC
+ _symbolic _____ 12MobileSafari35SFBookmarksCollectionViewControllerC14ShrinkWrapCellC
+ _symbolic _____ 14SafariSharedUI30WBSClusterOnboardingTipManagerC
+ _symbolic _____ So22WBSTabClusteringPolicyV
+ _symbolic _____Sg 12MobileSafari34SFFluidCollectionViewDropPlacementO
+ _symbolic _____Sg 7Network6NWPathV
+ _symbolic _____Sg 7Network6NWPathV6StatusO
+ _symbolic _____Sg So22WBSTabClusteringPolicyV
+ _symbolic _____Sg_ABt 12MobileSafari11TabOverviewC7SectionV
+ _symbolic _____Sg_ABt 7Network6NWPathV6StatusO
+ _symbolic ______pSg So31UISpringLoadedInteractionEffectP
+ _symbolic ______pSg So33UISpringLoadedInteractionBehaviorP
+ _symbolic _____xq_q0_XjSgXw r1_l12MobileSafari39SFFluidCollectionViewSpringLoadDelegate_pq_4ItemRts_x7SectionRtsq0_13SupplementaryRtsXPXGMq
+ _symbolic _____y___________G So16UICollectionViewC5UIKitE16CellRegistrationV 12MobileSafari021SFBookmarksCollectionB10ControllerC010ShrinkWrapD0C AH4ItemV
+ _symbolic _____y________________G 12MobileSafari21SFFluidCollectionViewC21SpringLoadCoordinatorC AA11TabOverviewC7SectionV AG4ItemV AA0ciJ13SupplementaryO
+ _symbolic _____y_____yAAyAAy__________G_____GGAFG 7SwiftUI15ModifiedContentV AA6ZStackV AA5ImageV AA18_AspectRatioLayoutV AA06_FrameI0V
+ _symbolic _____y_____yABy__________G_____GG 7SwiftUI6ZStackV AA15ModifiedContentV AA5ImageV AA18_AspectRatioLayoutV AA06_FrameI0V
+ _symbolic _____y_____y_____yAByABy__________G_____GGAGGG 7SwiftUI13ImageRendererC AA15ModifiedContentV AA6ZStackV AA0C0V AA18_AspectRatioLayoutV AA06_FrameJ0V
+ _symbolic _____yxq_q0__G 12MobileSafari21SFFluidCollectionViewC15DropCoordinatorC
+ _symbolic _____yxq_q0__GSg 12MobileSafari21SFFluidCollectionViewC21SpringLoadCoordinatorC
- GCC_except_table178
- GCC_except_table202
- GCC_except_table206
- GCC_except_table210
- GCC_except_table222
- _OBJC_CLASS_$_UIScrollEdgeEffect
- _WBSAutoTabClusteringEnabledKey
- _WBSAutoTabClusteringImmediateModeEnabledKey
- _WBSStartPageSectionRecentSearches
- __CATEGORY_INSTANCE_METHODS_UIScrollEdgeEffect_$_MobileSafariFrameworkExtras_Swift
- __CATEGORY_PROPERTIES_UIScrollEdgeEffect_$_MobileSafariFrameworkExtras_Swift
- __CATEGORY_UIScrollEdgeEffect_$_MobileSafariFrameworkExtras_Swift
- ___swift_closure_destructor.338Tm
- ___swift_closure_destructor.344Tm
- ___swift_closure_destructor.403Tm
- ___swift_closure_destructor.406Tm
- ___swift_closure_destructor.69Tm
- ___swift_closure_destructor.84Tm
- ___swift_memcpy168_8
- ___swift_memcpy200_8
- ___unnamed_63
- ___unnamed_65
CStrings:
+ "Drop destination changed to %{public}s, placement: %{public}s"
+ "MobileSafari.SpringLoadCoordinator"
+ "MobileSafari/SFBookmarksCollectionViewController.ShrinkWrapCell.swift"
+ "SFClusteringAccessoryButtonDidBecomeVisibleNotification"
+ "Safari was unable to check for changes because the network connection was unavailable, but will try again %@."
+ "Safari was unable to check for changes because the page was blocked by Screen Time, but will try again %@."
+ "Safari was unable to check for changes because the page was not found, but will try again %@."
+ "Safari was unable to check for changes because the server returned an error, but will try again %@."
+ "Safari was unable to check for changes because this %1$@ needed to cool down, but will try again %2$@."
+ "Safari was unable to check for changes because this %1$@ was in Low Power Mode, but will try again %2$@."
+ "ShrinkWrapClusterTitle-"
+ "This update to Safari adds Notify Me, which requires approval from a parent or guardian."
+ "cornersAreConcentric"
+ "d16@?0d8"
+ "figure.teen.shield.fill"
+ "popoverPresentationController is nil. Cannot set its delegate and sourceRect."
+ "shortcutsAutomationUUID was nil when notifying for Notify Me failure."
+ "shrinkWrapTopicTile"
- " was visited on "
- "Drop destination changed to %{public}s"
- "UI may not appear because popoverPresentationController is nil."
```
