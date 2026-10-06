## SpringBoard

> `/System/Library/AccessibilityBundles/SpringBoard.axbundle/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39c9c` | `0x3a0b0` | **`+0x414`** |
| `__AUTH_CONST.__cfstring` | `0xbe00` | `0xbee0` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x98c` | `0xa34` | **`+0xa8`** |
| `__TEXT.__cstring` | `0xa92b` | `0xa9b4` | **`+0x89`** |
| `__DATA_CONST.__objc_selrefs` | `0x25c8` | `0x25d8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1328` | `0x1338` | **`+0x10`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 1623
-  Symbols:   3891
-  CStrings:  1676
+  Functions: 1627
+  Symbols:   3895
+  CStrings:  1683
Symbols:
+ -[SBSystemApertureViewControllerAccessibility _axHasHiddenElementToReveal]
+ GCC_except_table1152
+ GCC_except_table1172
+ GCC_except_table1183
+ GCC_except_table1186
+ GCC_except_table1343
+ GCC_except_table1370
+ GCC_except_table1375
+ GCC_except_table1380
+ GCC_except_table1399
+ GCC_except_table1405
+ GCC_except_table1407
+ GCC_except_table1415
+ GCC_except_table1421
+ GCC_except_table1433
+ GCC_except_table1435
+ GCC_except_table1557
+ GCC_except_table1611
+ GCC_except_table629
+ GCC_except_table630
+ GCC_except_table634
+ GCC_except_table737
+ GCC_except_table738
+ GCC_except_table740
+ GCC_except_table742
+ GCC_except_table755
+ GCC_except_table762
+ GCC_except_table767
+ GCC_except_table769
+ GCC_except_table790
+ GCC_except_table792
+ GCC_except_table808
+ GCC_except_table833
+ GCC_except_table968
+ GCC_except_table970
+ ___73-[SBSystemApertureViewControllerAccessibility accessibilityCustomActions]_block_invoke_3
+ ___73-[SBSystemApertureViewControllerAccessibility accessibilityCustomActions]_block_invoke_4
+ ___74-[SBSystemApertureViewControllerAccessibility _axHasHiddenElementToReveal]_block_invoke
- -[SBHomeScreenWindowAccessibility _accessibilityIsIsolatedWindow]
- GCC_except_table1148
- GCC_except_table1168
- GCC_except_table1175
- GCC_except_table1182
- GCC_except_table1339
- GCC_except_table1366
- GCC_except_table1371
- GCC_except_table1376
- GCC_except_table1395
- GCC_except_table1401
- GCC_except_table1403
- GCC_except_table1411
- GCC_except_table1417
- GCC_except_table1429
- GCC_except_table1431
- GCC_except_table1553
- GCC_except_table1607
- GCC_except_table725
- GCC_except_table732
- GCC_except_table734
- GCC_except_table736
- GCC_except_table749
- GCC_except_table756
- GCC_except_table757
- GCC_except_table761
- GCC_except_table784
- GCC_except_table786
- GCC_except_table802
- GCC_except_table827
- GCC_except_table863
- GCC_except_table964
- GCC_except_table966
- ___65-[SBHomeScreenWindowAccessibility _accessibilityIsIsolatedWindow]_block_invoke
CStrings:
+ "SAUILayoutSpecifyingOverriding"
+ "SAUIPreferredLayoutModeAssertion"
+ "_axRevealHiddenElementIfPossible"
+ "_layoutSpecifyingOverriderForElement:"
+ "layoutModeChangeReason"
+ "layoutStateApplicationSceneHandles"
+ "preferredLayoutMode"
+ "preferredLayoutModeAssertion"
+ "registeredElements"
+ "window.expand"
- "externalForegroundApplicationSceneHandles"
- "homeScreenViewController.iconManager.rootFolderController"
- "isDisplayingWidgetIntroductionOnPage:"
```
