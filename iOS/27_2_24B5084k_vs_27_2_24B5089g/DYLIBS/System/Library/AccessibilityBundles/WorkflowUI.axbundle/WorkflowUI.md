## WorkflowUI

> `/System/Library/AccessibilityBundles/WorkflowUI.axbundle/WorkflowUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a0` | `0xb80` | **`-0x520`** |
| `__AUTH_CONST.__objc_const` | `0xcf0` | `0x870` | **`-0x480`** |
| `__DATA_DIRTY.__objc_data` | `0x5f0` | `0x370` | **`-0x280`** |
| `__AUTH_CONST.__cfstring` | `0x640` | `0x420` | **`-0x220`** |
| `__TEXT.__cstring` | `0x5a3` | `0x3ac` | **`-0x1f7`** |
| `__TEXT.__objc_methlist` | `0x3e4` | `0x28c` | **`-0x158`** |
| `__DATA_CONST.__objc_selrefs` | `0x190` | `0x140` | **`-0x50`** |
| `__DATA_CONST.__objc_classlist` | `0xb8` | `0x78` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x118` | `0xe0` | **`-0x38`** |
| `__AUTH_CONST.__const` | `0xc0` | `0xa0` | **`-0x20`** |
| `__DATA_CONST.__const` | `0xc8` | `0xa8` | **`-0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0x38` | `0x20` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x78` | `0x68` | **`-0x10`** |

### Other Changes

```diff

-3050.3.0.0.0
+3050.3.1.0.0

-  Functions: 70
-  Symbols:   241
-  CStrings:  62
+  Functions: 48
+  Symbols:   173
+  CStrings:  44
Symbols:
- +[WFAutomationEmptyStateCellAccessibility _accessibilityPerformValidations:]
- +[WFAutomationEmptyStateCellAccessibility(SafeCategory) safeCategoryBaseClass]
- +[WFAutomationEmptyStateCellAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[WFAutomationListViewControllerAccessibility _accessibilityPerformValidations:]
- +[WFAutomationListViewControllerAccessibility(SafeCategory) safeCategoryBaseClass]
- +[WFAutomationListViewControllerAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[WFAutomationTypeExplanationPlatterViewAccessibility _accessibilityPerformValidations:]
- +[WFAutomationTypeExplanationPlatterViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[WFAutomationTypeExplanationPlatterViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- +[WFTriggerOptionSelectionViewAccessibility _accessibilityPerformValidations:]
- +[WFTriggerOptionSelectionViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[WFTriggerOptionSelectionViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[WFAutomationEmptyStateCellAccessibility _accessibilityChildren]
- -[WFAutomationListViewControllerAccessibility _accessibilityLoadAccessibilityInformation]
- -[WFAutomationTypeExplanationPlatterViewAccessibility accessibilityActivationPoint]
- -[WFAutomationTypeExplanationPlatterViewAccessibility accessibilityLabel]
- -[WFAutomationTypeExplanationPlatterViewAccessibility accessibilityTraits]
- -[WFAutomationTypeExplanationPlatterViewAccessibility isAccessibilityElement]
- -[WFTriggerOptionSelectionViewAccessibility accessibilityLabel]
- -[WFTriggerOptionSelectionViewAccessibility accessibilityTraits]
- -[WFTriggerOptionSelectionViewAccessibility isAccessibilityElement]
- _NSClassFromString
- _OBJC_CLASS_$_UIViewController
- _OBJC_CLASS_$_WFAutomationEmptyStateCellAccessibility
- _OBJC_CLASS_$_WFAutomationListViewControllerAccessibility
- _OBJC_CLASS_$_WFAutomationTypeExplanationPlatterViewAccessibility
- _OBJC_CLASS_$_WFTriggerOptionSelectionViewAccessibility
- _OBJC_CLASS_$___WFAutomationEmptyStateCellAccessibility_super
- _OBJC_CLASS_$___WFAutomationListViewControllerAccessibility_super
- _OBJC_CLASS_$___WFAutomationTypeExplanationPlatterViewAccessibility_super
- _OBJC_CLASS_$___WFTriggerOptionSelectionViewAccessibility_super
- _OBJC_METACLASS_$_WFAutomationEmptyStateCellAccessibility
- _OBJC_METACLASS_$_WFAutomationListViewControllerAccessibility
- _OBJC_METACLASS_$_WFAutomationTypeExplanationPlatterViewAccessibility
- _OBJC_METACLASS_$_WFTriggerOptionSelectionViewAccessibility
- _OBJC_METACLASS_$___WFAutomationEmptyStateCellAccessibility_super
- _OBJC_METACLASS_$___WFAutomationListViewControllerAccessibility_super
- _OBJC_METACLASS_$___WFAutomationTypeExplanationPlatterViewAccessibility_super
- _OBJC_METACLASS_$___WFTriggerOptionSelectionViewAccessibility_super
- _UIAXStringForAllChildren
- _UIAccessibilityTraitSelected
- __OBJC_$_CLASS_METHODS_WFAutomationEmptyStateCellAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_WFAutomationListViewControllerAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_WFAutomationTypeExplanationPlatterViewAccessibility(SafeCategory)
- __OBJC_$_CLASS_METHODS_WFTriggerOptionSelectionViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_WFAutomationEmptyStateCellAccessibility
- __OBJC_$_INSTANCE_METHODS_WFAutomationListViewControllerAccessibility
- __OBJC_$_INSTANCE_METHODS_WFAutomationTypeExplanationPlatterViewAccessibility
- __OBJC_$_INSTANCE_METHODS_WFTriggerOptionSelectionViewAccessibility
- __OBJC_CLASS_RO_$_WFAutomationEmptyStateCellAccessibility
- __OBJC_CLASS_RO_$_WFAutomationListViewControllerAccessibility
- __OBJC_CLASS_RO_$_WFAutomationTypeExplanationPlatterViewAccessibility
- __OBJC_CLASS_RO_$_WFTriggerOptionSelectionViewAccessibility
- __OBJC_CLASS_RO_$___WFAutomationEmptyStateCellAccessibility_super
- __OBJC_CLASS_RO_$___WFAutomationListViewControllerAccessibility_super
- __OBJC_CLASS_RO_$___WFAutomationTypeExplanationPlatterViewAccessibility_super
- __OBJC_CLASS_RO_$___WFTriggerOptionSelectionViewAccessibility_super
- __OBJC_METACLASS_RO_$_WFAutomationEmptyStateCellAccessibility
- __OBJC_METACLASS_RO_$_WFAutomationListViewControllerAccessibility
- __OBJC_METACLASS_RO_$_WFAutomationTypeExplanationPlatterViewAccessibility
- __OBJC_METACLASS_RO_$_WFTriggerOptionSelectionViewAccessibility
- __OBJC_METACLASS_RO_$___WFAutomationEmptyStateCellAccessibility_super
- __OBJC_METACLASS_RO_$___WFAutomationListViewControllerAccessibility_super
- __OBJC_METACLASS_RO_$___WFAutomationTypeExplanationPlatterViewAccessibility_super
- __OBJC_METACLASS_RO_$___WFTriggerOptionSelectionViewAccessibility_super
- ___65-[WFAutomationEmptyStateCellAccessibility _accessibilityChildren]_block_invoke
- ___AXStringForVariables
- ___block_descriptor_32_e15_B32?08Q16^B24l
CStrings:
- "B32@?0@8Q16^B24"
- "UITableTextAccessibilityElement"
- "WFAutomationEmptyStateCell"
- "WFAutomationEmptyStateCellAccessibility"
- "WFAutomationListViewController"
- "WFAutomationListViewControllerAccessibility"
- "WFAutomationTypeExplanationPlatterView"
- "WFAutomationTypeExplanationPlatterViewAccessibility"
- "WFTriggerOptionSelectionView"
- "WFTriggerOptionSelectionViewAccessibility"
- "__AXStringForVariablesSentinel"
- "_explanationTextLabel"
- "_explanationTextLabel.text"
- "button"
- "button.configuration.title"
- "create.automation"
- "selected"
- "textField"
```
