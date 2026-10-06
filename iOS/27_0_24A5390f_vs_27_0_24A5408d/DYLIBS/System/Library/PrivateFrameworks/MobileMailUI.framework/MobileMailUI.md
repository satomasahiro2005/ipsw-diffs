## MobileMailUI

> `/System/Library/PrivateFrameworks/MobileMailUI.framework/MobileMailUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e444` | `0x4ec5c` | **`+0x818`** |
| `__AUTH_CONST.__objc_const` | `0x7d48` | `0x8028` | **`+0x2e0`** |
| `__TEXT.__objc_methlist` | `0x517c` | `0x5314` | **`+0x198`** |
| `__TEXT.__gcc_except_tab` | `0x983c` | `0x9938` | **`+0xfc`** |
| `__DATA_CONST.__objc_selrefs` | `0x41a0` | `0x4250` | **`+0xb0`** |
| `__AUTH.__objc_data` | `0x9c0` | `0xa60` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x2a08` | `0x2a80` | **`+0x78`** |
| `__DATA.__objc_ivar` | `0x4bc` | `0x4dc` | **`+0x20`** |
| `__TEXT.__const` | `0x84f4` | `0x8514` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x1f0` | `0x200` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x140` | `0x150` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb48` | `0xb50` | **`+0x8`** |

### Other Changes

```diff

-3897.100.8.2.5
+3901.100.1.2.7

-  Functions: 1737
-  Symbols:   3536
+  Functions: 1767
+  Symbols:   3590
Symbols:
+ +[MFPopoverConfiguration new]
+ +[MFPopoverConfigurationRequest new]
+ -[MFMessageDisplayMetrics mailActionCardPreferredHeightForRegularOnlyEnvironment]
+ -[MFMessageDisplayMetrics mailCardMinimumPopoverLayoutMargin]
+ -[MFMessageDisplayMetrics popoverConfigurationForRequest:]
+ -[MFPopoverConfiguration applyToViewController:]
+ -[MFPopoverConfiguration initWithCoder:]
+ -[MFPopoverConfiguration initWithPreferredContentSize:popoverLayoutMargins:]
+ -[MFPopoverConfiguration init]
+ -[MFPopoverConfiguration popoverLayoutMargins]
+ -[MFPopoverConfiguration preferredContentSize]
+ -[MFPopoverConfiguration setPopoverLayoutMargins:]
+ -[MFPopoverConfiguration setPreferredContentSize:]
+ -[MFPopoverConfigurationRequest .cxx_destruct]
+ -[MFPopoverConfigurationRequest approximateMinimumHeightNeededForAccessibilityContentSizeCategory]
+ -[MFPopoverConfigurationRequest containerSize]
+ -[MFPopoverConfigurationRequest initWithCoder:]
+ -[MFPopoverConfigurationRequest initWithContainerSize:presentingViewSize:popoverLayoutMargins:approximateMinimumHeightNeededForAccessibilityContentSizeCategory:sourceItem:containerTraitCollection:]
+ -[MFPopoverConfigurationRequest initWithContainerSize:presentingViewSize:popoverLayoutMargins:approximateMinimumHeightNeededForAccessibilityContentSizeCategory:sourceItem:isInRegularOnlyEnvironment:]
+ -[MFPopoverConfigurationRequest init]
+ -[MFPopoverConfigurationRequest isInRegularOnlyEnvironment]
+ -[MFPopoverConfigurationRequest popoverLayoutMargins]
+ -[MFPopoverConfigurationRequest presentingViewSize]
+ -[MFPopoverConfigurationRequest setApproximateMinimumHeightNeededForAccessibilityContentSizeCategory:]
+ -[MFPopoverConfigurationRequest setContainerSize:]
+ -[MFPopoverConfigurationRequest setIsInRegularOnlyEnvironment:]
+ -[MFPopoverConfigurationRequest setPopoverLayoutMargins:]
+ -[MFPopoverConfigurationRequest setPresentingViewSize:]
+ -[MFPopoverConfigurationRequest setSourceItem:]
+ -[MFPopoverConfigurationRequest sourceItem]
+ _OBJC_CLASS_$_MFPopoverConfiguration
+ _OBJC_CLASS_$_MFPopoverConfigurationRequest
+ _OBJC_IVAR_$_MFPopoverConfiguration._popoverLayoutMargins
+ _OBJC_IVAR_$_MFPopoverConfiguration._preferredContentSize
+ _OBJC_IVAR_$_MFPopoverConfigurationRequest._approximateMinimumHeightNeededForAccessibilityContentSizeCategory
+ _OBJC_IVAR_$_MFPopoverConfigurationRequest._containerSize
+ _OBJC_IVAR_$_MFPopoverConfigurationRequest._isInRegularOnlyEnvironment
+ _OBJC_IVAR_$_MFPopoverConfigurationRequest._popoverLayoutMargins
+ _OBJC_IVAR_$_MFPopoverConfigurationRequest._presentingViewSize
+ _OBJC_IVAR_$_MFPopoverConfigurationRequest._sourceItem
+ _OBJC_METACLASS_$_MFPopoverConfiguration
+ _OBJC_METACLASS_$_MFPopoverConfigurationRequest
+ __OBJC_$_CLASS_METHODS_MFPopoverConfiguration
+ __OBJC_$_CLASS_METHODS_MFPopoverConfigurationRequest
+ __OBJC_$_INSTANCE_METHODS_MFPopoverConfiguration
+ __OBJC_$_INSTANCE_METHODS_MFPopoverConfigurationRequest
+ __OBJC_$_INSTANCE_VARIABLES_MFPopoverConfiguration
+ __OBJC_$_INSTANCE_VARIABLES_MFPopoverConfigurationRequest
+ __OBJC_$_PROP_LIST_MFPopoverConfiguration
+ __OBJC_$_PROP_LIST_MFPopoverConfigurationRequest
+ __OBJC_CLASS_RO_$_MFPopoverConfiguration
+ __OBJC_CLASS_RO_$_MFPopoverConfigurationRequest
+ __OBJC_METACLASS_RO_$_MFPopoverConfiguration
+ __OBJC_METACLASS_RO_$_MFPopoverConfigurationRequest
```
