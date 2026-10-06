## BridgePreferences

> `/System/Library/PrivateFrameworks/BridgePreferences.framework/BridgePreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x397c0` | `0x3bd30` | **`+0x2570`** |
| `__TEXT.__const` | `0x1954` | `0x1bb4` | **`+0x260`** |
| `__AUTH_CONST.__objc_const` | `0x4f80` | `0x5180` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0x2018` | `0x21c8` | **`+0x1b0`** |
| `__DATA.__bss` | `0x4e8` | `0x688` | **`+0x1a0`** |
| `__AUTH_CONST.__const` | `0xb40` | `0xc50` | **`+0x110`** |
| `__TEXT.__constg_swiftt` | `0x6bc` | `0x778` | **`+0xbc`** |
| `__AUTH_CONST.__auth_got` | `0xa48` | `0xb00` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0xdf0` | `0xea8` | **`+0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a88` | `0x2b30` | **`+0xa8`** |
| `__AUTH.__data` | `0x400` | `0x4a0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x32a8` | `0x3348` | **`+0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x374` | `0x410` | **`+0x9c`** |
| `__DATA.__data` | `0x640` | `0x6d0` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x2ee` | `0x37e` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x356` | `0x3d8` | **`+0x82`** |
| `__AUTH.__objc_data` | `0x1578` | `0x15e8` | **`+0x70`** |
| `__TEXT.__swift5_assocty` | `0x18` | `0x68` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x7d0` | `0x800` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xf00` | `0xf28` | **`+0x28`** |
| `__DATA.__common` | `0x30` | `0x48` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x1c0` | `0x1d0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x78` | `0x88` | **`+0x10`** |
| `__TEXT.__cstring` | `0x4782` | `0x4792` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x18` | `0x24` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x50` | `0x5c` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x2dc` | `0x2e4` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xc8` | `0xd0` | **`+0x8`** |

### Other Changes

```diff

-1359.9.0.0.0
+1370.0.0.0.0

-  Functions: 1422
-  Symbols:   2572
-  CStrings:  855
+  Functions: 1488
+  Symbols:   2626
+  CStrings:  861
Symbols:
+ +[BPSFollowUpController removeSkippedPaneClassNamed:forDevice:]
+ +[BPSFollowUpController removeSkippedPaneClassNamedForCurrentDevice:]
+ -[BPSSheetBackdrop .cxx_destruct]
+ -[BPSSheetBackdrop backdropView]
+ -[BPSSheetBackdrop hostViewController]
+ -[BPSSheetBackdrop initWithHostViewController:]
+ -[BPSSheetBackdrop setBackdropView:]
+ -[BPSSheetBackdrop setHostViewController:]
+ -[BPSSheetBackdrop tearDownIfHostIsBeingDismissed]
+ -[BPSSheetBackdrop update]
+ GCC_except_table59
+ _OBJC_CLASS_$_BPSSheetBackdrop
+ _OBJC_CLASS_$_CABasicAnimation
+ _OBJC_CLASS_$_CAPropertyAnimation
+ _OBJC_CLASS_$_CAState
+ _OBJC_CLASS_$_UISheetPresentationController
+ _OBJC_IVAR_$_BPSSheetBackdrop._backdropView
+ _OBJC_IVAR_$_BPSSheetBackdrop._hostViewController
+ _OBJC_METACLASS_$_BPSSheetBackdrop
+ __DATA__TtCV17BridgePreferencesP33_A443055DC2E2A0F3E9C0C39948F2499811PackageView11Coordinator
+ __IVARS__TtCV17BridgePreferencesP33_A443055DC2E2A0F3E9C0C39948F2499811PackageView11Coordinator
+ __METACLASS_DATA__TtCV17BridgePreferencesP33_A443055DC2E2A0F3E9C0C39948F2499811PackageView11Coordinator
+ __OBJC_$_INSTANCE_METHODS_BPSSheetBackdrop
+ __OBJC_$_INSTANCE_METHODS__TtC17BridgePreferences20AnimationHostingView(BridgePreferences)
+ __OBJC_$_INSTANCE_VARIABLES_BPSSheetBackdrop
+ __OBJC_$_PROP_LIST_BPSSheetBackdrop
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CAStateControllerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CAStateControllerDelegate
+ __OBJC_CLASS_PROTOCOLS_$__TtC17BridgePreferences20AnimationHostingView(BridgePreferences)
+ __OBJC_CLASS_RO_$_BPSSheetBackdrop
+ __OBJC_LABEL_PROTOCOL_$_CAStateControllerDelegate
+ __OBJC_METACLASS_RO_$_BPSSheetBackdrop
+ __OBJC_PROTOCOL_$_CAStateControllerDelegate
+ ___26-[BPSSheetBackdrop update]_block_invoke
+ ___50-[BPSSheetBackdrop tearDownIfHostIsBeingDismissed]_block_invoke
+ ___50-[BPSSheetBackdrop tearDownIfHostIsBeingDismissed]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e56_v16?0"<UIViewControllerTransitionCoordinatorContext>"8ls32l8
+ ___swift_memcpy88_8
+ _associated conformance 17BridgePreferences11PackageView33_A443055DC2E2A0F3E9C0C39948F24998LLV7SwiftUI0D0AA4BodyAeFP_AeF
+ _associated conformance 17BridgePreferences11PackageView33_A443055DC2E2A0F3E9C0C39948F24998LLV7SwiftUI19UIViewRepresentableAaE0D0
+ _associated conformance 17BridgePreferences21StatefulAnimationViewV7SwiftUI0E0AA4BodyAdEP_AdE
+ _get_enum_tag_for_layout_string SSSgIegg_Sg
+ _get_witness_table 17BridgePreferences11PackageView33_A443055DC2E2A0F3E9C0C39948F24998LLV7SwiftUI0D0HPyHC
+ _swift_bridgeObjectRelease_n
+ _swift_dynamicCastObjCClass
+ _swift_release_x1
+ _swift_retain_x1
+ _symbolic $s7SwiftUI19UIViewRepresentableP
+ _symbolic SSSg
+ _symbolic _____ 17BridgePreferences11PackageView33_A443055DC2E2A0F3E9C0C39948F24998LLV
+ _symbolic _____ 17BridgePreferences11PackageView33_A443055DC2E2A0F3E9C0C39948F24998LLV11CoordinatorC
+ _symbolic _____ 17BridgePreferences21StatefulAnimationViewV
+ _symbolic _____ s5NeverO
+ _symbolic _____ySSG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G 7SwiftUI26UIViewRepresentableContextV 17BridgePreferences11PackageView33_A443055DC2E2A0F3E9C0C39948F24998LLV
+ _symbolic ySSSgcSg
+ _type_layout_string 17BridgePreferences11PackageView33_A443055DC2E2A0F3E9C0C39948F24998LLV
+ _type_layout_string 17BridgePreferences21StatefulAnimationViewV
- -[BPSWelcomeOptinViewController revalidateColumnLayoutIfNeeded]
- -[BPSWelcomeOptinViewController viewIsAppearing:]
- GCC_except_table61
- __INSTANCE_METHODS__TtC17BridgePreferences20AnimationHostingView
CStrings:
+ "+[BPSFollowUpController removeSkippedPaneClassNamed:forDevice:]"
+ "Could not load animation archive '%{public}s'"
+ "Dropped %{public}ld stale animations attached to the loaded package"
+ "Dropping stale animation '%{public}s' on '%{public}s' keyPath=%{public}s beginTime=%{public}f"
+ "Error: tried to remove a skipped pane with no class name"
+ "Loaded animation package: bounds=%{public}s sublayers=%{public}ld states=%{public}s"
+ "No animation state named '%{public}s' in the loaded package"
- "+[BPSFollowUpController removeSkippedPaneClass:forDevice:]"
```
