## PrintKitUI

> `/System/Library/PrivateFrameworks/PrintKitUI.framework/PrintKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6590c` | `0x64aa8` | **`-0xe64`** |
| `__AUTH_CONST.__objc_const` | `0xa750` | `0xa560` | **`-0x1f0`** |
| `__TEXT.__objc_methlist` | `0x7184` | `0x70a4` | **`-0xe0`** |
| `__AUTH.__objc_data` | `0x1630` | `0x15e0` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x1ba8` | `0x1bf4` | **`+0x4c`** |
| `__DATA_CONST.__objc_selrefs` | `0x4988` | `0x4948` | **`-0x40`** |
| `__DATA.__objc_ivar` | `0x7d0` | `0x7b4` | **`-0x1c`** |
| `__TEXT.__const` | `0x310` | `0x300` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x918` | `0x910` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x288` | `0x280` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x240` | `0x238` | **`-0x8`** |
| `__TEXT.__cstring` | `0x2a97` | `0x2a95` | **`-0x2`** |

### Other Changes

```diff

-97.0.0.0.0
+97.2.0.0.0

-  Functions: 2303
-  Symbols:   4285
+  Functions: 2285
+  Symbols:   4253
Symbols:
+ -[UIPrintInteractionController updatePageCountWithRanges:]
+ -[UIPrintPanelViewController compactPreviewController]
+ -[UIPrintPanelViewController setCompactPreviewController:]
+ -[UIPrintPanelViewController setSidebarPreviewController:]
+ -[UIPrintPanelViewController sidebarPreviewController]
+ -[UIPrintPreviewViewController initWithPrintPanelViewController:usingSideBar:withContainerView:]
+ -[UIPrintPreviewViewController layoutGlassButtonInset]
+ -[UIPrintPreviewViewController layoutGlassButtonLeadingConstraint]
+ -[UIPrintPreviewViewController layoutGlassButtonVerticalConstraint]
+ -[UIPrintPreviewViewController setLayoutGlassButtonLeadingConstraint:]
+ -[UIPrintPreviewViewController setLayoutGlassButtonVerticalConstraint:]
+ -[UIPrintPreviewViewController setUsingGlassLayoutButton:]
+ -[UIPrintPreviewViewController setUsingSideBar:]
+ -[UIPrintPreviewViewController usingGlassLayoutButton]
+ -[UIPrintPreviewViewController usingSideBar]
+ -[UIPrintPreviewViewController viewDidLayoutSubviews]
+ GCC_except_table110
+ GCC_except_table114
+ GCC_except_table123
+ GCC_except_table132
+ GCC_except_table139
+ GCC_except_table143
+ GCC_except_table148
+ GCC_except_table157
+ GCC_except_table18
+ GCC_except_table21
+ GCC_except_table272
+ GCC_except_table273
+ GCC_except_table277
+ GCC_except_table37
+ GCC_except_table38
+ GCC_except_table40
+ GCC_except_table56
+ GCC_except_table59
+ GCC_except_table63
+ GCC_except_table68
+ GCC_except_table74
+ GCC_except_table84
+ GCC_except_table90
+ GCC_except_table94
+ _OBJC_IVAR_$_UIPrintPanelViewController._compactPreviewController
+ _OBJC_IVAR_$_UIPrintPanelViewController._sidebarPreviewController
+ _OBJC_IVAR_$_UIPrintPreviewViewController._layoutGlassButtonLeadingConstraint
+ _OBJC_IVAR_$_UIPrintPreviewViewController._layoutGlassButtonVerticalConstraint
+ _OBJC_IVAR_$_UIPrintPreviewViewController._usingGlassLayoutButton
+ _OBJC_IVAR_$_UIPrintPreviewViewController._usingSideBar
+ ___block_descriptor_64_e8_32s40s48s56w_e8_v16?0q8lw56l8s32l8s40l8s48l8
- -[UIPrintInteractionController _currentPrintInfo]
- -[UIPrintInteractionController pageRanges]
- -[UIPrintInteractionController setPageRanges:]
- -[UIPrintPanelViewController compactPreviewViewController]
- -[UIPrintPanelViewController horizScrollPrintPanelConstraints]
- -[UIPrintPanelViewController previewVertSeparatorView]
- -[UIPrintPanelViewController setCompactPreviewViewController:]
- -[UIPrintPanelViewController setHorizScrollPrintPanelConstraints:]
- -[UIPrintPanelViewController setPreviewVertSeparatorView:]
- -[UIPrintPanelViewController setSidebarPreviewViewController:]
- -[UIPrintPanelViewController setVertScrollPrintPanelConstraints:]
- -[UIPrintPanelViewController sidebarPreviewViewController]
- -[UIPrintPanelViewController splitViewController:willHideColumn:]
- -[UIPrintPanelViewController splitViewController:willShowColumn:]
- -[UIPrintPanelViewController vertScrollPrintPanelConstraints]
- -[UIPrintPanelViewController viewWillAppear:]
- -[UIPrintPreviewContainerView .cxx_destruct]
- -[UIPrintPreviewContainerView layoutGlassButtonLeadingConstraint]
- -[UIPrintPreviewContainerView layoutGlassButtonVerticalConstraint]
- -[UIPrintPreviewContainerView layoutGlassButton]
- -[UIPrintPreviewContainerView layoutSubviews]
- -[UIPrintPreviewContainerView setLayoutGlassButton:]
- -[UIPrintPreviewContainerView setLayoutGlassButtonLeadingConstraint:]
- -[UIPrintPreviewContainerView setLayoutGlassButtonVerticalConstraint:]
- -[UIPrintPreviewContainerView setUsingCompactPreview:]
- -[UIPrintPreviewContainerView usingCompactPreview]
- -[UIPrintPreviewViewController initWithPrintPanelViewController:useCompactPreview:withContainerView:]
- -[UIPrintPreviewViewController layoutBarButton]
- -[UIPrintPreviewViewController positionForBar:]
- -[UIPrintPreviewViewController setLayoutBarButton:]
- -[UIPrintPreviewViewController setSolariumEnabled:]
- -[UIPrintPreviewViewController setUsingCompactPreview:]
- -[UIPrintPreviewViewController solariumEnabled]
- -[UIPrintPreviewViewController usingCompactPreview]
- GCC_except_table112
- GCC_except_table118
- GCC_except_table12
- GCC_except_table125
- GCC_except_table134
- GCC_except_table147
- GCC_except_table150
- GCC_except_table159
- GCC_except_table274
- GCC_except_table275
- GCC_except_table279
- GCC_except_table30
- GCC_except_table46
- GCC_except_table47
- GCC_except_table48
- GCC_except_table49
- GCC_except_table58
- GCC_except_table61
- GCC_except_table79
- GCC_except_table87
- GCC_except_table88
- GCC_except_table92
- GCC_except_table96
- GCC_except_table99
- _OBJC_CLASS_$_UIPrintPreviewContainerView
- _OBJC_IVAR_$_UIPrintInteractionController._pageRanges
- _OBJC_IVAR_$_UIPrintPanelViewController._compactPreviewViewController
- _OBJC_IVAR_$_UIPrintPanelViewController._horizScrollPrintPanelConstraints
- _OBJC_IVAR_$_UIPrintPanelViewController._previewVertSeparatorView
- _OBJC_IVAR_$_UIPrintPanelViewController._sidebarPreviewViewController
- _OBJC_IVAR_$_UIPrintPanelViewController._vertScrollPrintPanelConstraints
- _OBJC_IVAR_$_UIPrintPreviewContainerView._layoutGlassButton
- _OBJC_IVAR_$_UIPrintPreviewContainerView._layoutGlassButtonLeadingConstraint
- _OBJC_IVAR_$_UIPrintPreviewContainerView._layoutGlassButtonVerticalConstraint
- _OBJC_IVAR_$_UIPrintPreviewContainerView._usingCompactPreview
- _OBJC_IVAR_$_UIPrintPreviewViewController._layoutBarButton
- _OBJC_IVAR_$_UIPrintPreviewViewController._solariumEnabled
- _OBJC_IVAR_$_UIPrintPreviewViewController._usingCompactPreview
- _OBJC_METACLASS_$_UIPrintPreviewContainerView
- __OBJC_$_INSTANCE_METHODS_UIPrintPreviewContainerView
- __OBJC_$_INSTANCE_VARIABLES_UIPrintPreviewContainerView
- __OBJC_$_PROP_LIST_UIPrintPreviewContainerView
- __OBJC_CLASS_RO_$_UIPrintPreviewContainerView
- __OBJC_METACLASS_RO_$_UIPrintPreviewContainerView
- ___block_descriptor_64_e8_32s40s48s56s_e8_v16?0q8ls32l8s40l8s48l8s56l8
CStrings:
+ "q\xf0\xe1"
+ "\xf0\xf0\""
- "a"
- "\x81\xf0\xe1"
```
