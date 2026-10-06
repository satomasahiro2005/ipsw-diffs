## UIKit

> `/System/Library/AccessibilityBundles/UIKit.axbundle/UIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x158cf4` | `0x15a29c` | **`+0x15a8`** |
| `__AUTH_CONST.__objc_const` | `0x203d8` | `0x205f0` | **`+0x218`** |
| `__AUTH.__objc_data` | `0x2260` | `0x23a0` | **`+0x140`** |
| `__TEXT.__gcc_except_tab` | `0x33bc` | `0x3480` | **`+0xc4`** |
| `__TEXT.__objc_methlist` | `0xfa0c` | `0xfab4` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x4240` | `0x4288` | **`+0x48`** |
| `__TEXT.__cstring` | `0x19278` | `0x192a5` | **`+0x2d`** |
| `__DATA_CONST.__const` | `0x1e90` | `0x1eb8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1dec0` | `0x1dee0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x1760` | `0x1780` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x1b28` | `0x1b48` | **`+0x20`** |
| `__DATA_CONST.__objc_superrefs` | `0xa68` | `0xa78` | **`+0x10`** |
| `__DATA.__data` | `0x690` | `0x698` | **`+0x8`** |
| `__TEXT.__const` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x128` | `0x124` | **`-0x4`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 5931
-  Symbols:   11794
-  CStrings:  4194
+  Functions: 5951
+  Symbols:   11837
+  CStrings:  4195
Symbols:
+ +[UIRefreshControlAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[UIRefreshControlAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[_UIContextMenuHeaderViewAccessibility _accessibilityPerformValidations:]
+ +[_UIContextMenuHeaderViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[_UIContextMenuHeaderViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[UIRefreshControlAccessibility accessibilityLabel]
+ -[UIRefreshControlAccessibility accessibilityRespondsToUserInteraction]
+ -[UIRefreshControlAccessibility accessibilityTraits]
+ -[UIRefreshControlAccessibility isAccessibilityElement]
+ -[UIScrollViewAccessibility _axObserveRefreshControlCompletion:elapsed:]
+ -[UITextViewAccessibility _axShouldExposeLinksForCommandClient]
+ -[UITextViewAccessibility _axTitleForLink:]
+ -[UITextViewAccessibility accessibilityCustomActions]
+ -[_UIContextMenuHeaderViewAccessibility _accessibilityLoadAccessibilityInformation]
+ GCC_except_table1762
+ GCC_except_table1773
+ GCC_except_table1774
+ GCC_except_table1781
+ GCC_except_table1783
+ GCC_except_table1790
+ GCC_except_table1812
+ GCC_except_table1844
+ GCC_except_table1893
+ GCC_except_table1899
+ GCC_except_table1919
+ GCC_except_table1932
+ GCC_except_table1942
+ GCC_except_table1988
+ GCC_except_table2081
+ GCC_except_table2129
+ GCC_except_table2151
+ GCC_except_table2235
+ GCC_except_table2254
+ GCC_except_table2259
+ GCC_except_table2267
+ GCC_except_table2286
+ GCC_except_table2303
+ GCC_except_table2358
+ GCC_except_table2385
+ GCC_except_table2395
+ GCC_except_table2402
+ GCC_except_table2418
+ GCC_except_table2436
+ GCC_except_table2529
+ GCC_except_table2613
+ GCC_except_table2669
+ GCC_except_table2737
+ GCC_except_table2741
+ GCC_except_table2759
+ GCC_except_table2778
+ GCC_except_table2895
+ GCC_except_table2928
+ GCC_except_table2979
+ GCC_except_table3002
+ GCC_except_table3054
+ GCC_except_table3138
+ GCC_except_table3144
+ GCC_except_table3197
+ GCC_except_table3210
+ GCC_except_table3333
+ GCC_except_table3334
+ GCC_except_table3390
+ GCC_except_table3450
+ GCC_except_table3587
+ GCC_except_table3658
+ GCC_except_table3677
+ GCC_except_table3696
+ GCC_except_table3812
+ GCC_except_table3843
+ GCC_except_table3880
+ GCC_except_table3882
+ GCC_except_table3915
+ GCC_except_table3917
+ GCC_except_table3931
+ GCC_except_table3939
+ GCC_except_table3953
+ GCC_except_table3954
+ GCC_except_table3980
+ GCC_except_table3985
+ GCC_except_table4006
+ GCC_except_table4015
+ GCC_except_table4035
+ GCC_except_table4048
+ GCC_except_table4050
+ GCC_except_table4066
+ GCC_except_table4080
+ GCC_except_table4119
+ GCC_except_table4137
+ GCC_except_table4143
+ GCC_except_table4155
+ GCC_except_table4177
+ GCC_except_table4184
+ GCC_except_table4322
+ GCC_except_table4438
+ GCC_except_table4627
+ GCC_except_table4630
+ GCC_except_table4631
+ GCC_except_table4653
+ GCC_except_table4687
+ GCC_except_table4692
+ GCC_except_table4701
+ GCC_except_table4705
+ GCC_except_table4706
+ GCC_except_table4714
+ GCC_except_table4717
+ GCC_except_table4723
+ GCC_except_table4739
+ GCC_except_table4754
+ GCC_except_table4771
+ GCC_except_table4841
+ GCC_except_table4899
+ GCC_except_table5012
+ GCC_except_table5023
+ GCC_except_table5039
+ GCC_except_table5064
+ GCC_except_table5066
+ GCC_except_table5071
+ GCC_except_table5238
+ GCC_except_table5362
+ GCC_except_table5455
+ GCC_except_table5551
+ GCC_except_table5579
+ GCC_except_table5637
+ GCC_except_table5743
+ GCC_except_table5749
+ GCC_except_table5764
+ GCC_except_table5780
+ GCC_except_table5801
+ GCC_except_table5813
+ GCC_except_table5830
+ _OBJC_CLASS_$_UIRefreshControlAccessibility
+ _OBJC_CLASS_$__UIContextMenuHeaderViewAccessibility
+ _OBJC_CLASS_$___UIRefreshControlAccessibility_super
+ _OBJC_CLASS_$____UIContextMenuHeaderViewAccessibility_super
+ _OBJC_METACLASS_$_UIRefreshControlAccessibility
+ _OBJC_METACLASS_$__UIContextMenuHeaderViewAccessibility
+ _OBJC_METACLASS_$___UIRefreshControlAccessibility_super
+ _OBJC_METACLASS_$____UIContextMenuHeaderViewAccessibility_super
+ __AXContextMenuTriggerElementStorage
+ __OBJC_$_CLASS_METHODS_UIRefreshControlAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS__UIContextMenuHeaderViewAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_UIRefreshControlAccessibility
+ __OBJC_$_INSTANCE_METHODS__UIContextMenuHeaderViewAccessibility
+ __OBJC_CLASS_RO_$_UIRefreshControlAccessibility
+ __OBJC_CLASS_RO_$__UIContextMenuHeaderViewAccessibility
+ __OBJC_CLASS_RO_$___UIRefreshControlAccessibility_super
+ __OBJC_CLASS_RO_$____UIContextMenuHeaderViewAccessibility_super
+ __OBJC_METACLASS_RO_$_UIRefreshControlAccessibility
+ __OBJC_METACLASS_RO_$__UIContextMenuHeaderViewAccessibility
+ __OBJC_METACLASS_RO_$___UIRefreshControlAccessibility_super
+ __OBJC_METACLASS_RO_$____UIContextMenuHeaderViewAccessibility_super
+ ___110-[_AXUITextViewParagraphElement initWithAccessibilityContainer:textRange:links:attributedText:paragraphIndex:]_block_invoke_3
+ ___53-[UITextViewAccessibility accessibilityCustomActions]_block_invoke
+ ___58-[UICollectionViewListCellAccessibility accessibilityPath]_block_invoke
+ ___58-[UICollectionViewListCellAccessibility accessibilityPath]_block_invoke_2
+ ___58-[UICollectionViewListCellAccessibility accessibilityPath]_block_invoke_3
+ ___72-[UIScrollViewAccessibility _axObserveRefreshControlCompletion:elapsed:]_block_invoke
+ ___83-[_UIContextMenuHeaderViewAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
+ ___UITableViewCellAccessibility__accessibilityIsFetchingChildren
+ ___block_descriptor_48_e8_32w40w_e37_B16?0"UIAccessibilityCustomAction"8lw32l8w40l8
- GCC_except_table1770
- GCC_except_table1771
- GCC_except_table1775
- GCC_except_table1780
- GCC_except_table1787
- GCC_except_table1809
- GCC_except_table1838
- GCC_except_table1890
- GCC_except_table1896
- GCC_except_table1916
- GCC_except_table1929
- GCC_except_table1939
- GCC_except_table1985
- GCC_except_table2075
- GCC_except_table2126
- GCC_except_table2148
- GCC_except_table2232
- GCC_except_table2251
- GCC_except_table2256
- GCC_except_table2264
- GCC_except_table2283
- GCC_except_table2300
- GCC_except_table2355
- GCC_except_table2382
- GCC_except_table2392
- GCC_except_table2399
- GCC_except_table2415
- GCC_except_table2433
- GCC_except_table2526
- GCC_except_table2610
- GCC_except_table2666
- GCC_except_table2734
- GCC_except_table2738
- GCC_except_table2756
- GCC_except_table2775
- GCC_except_table2892
- GCC_except_table2925
- GCC_except_table2976
- GCC_except_table2999
- GCC_except_table3051
- GCC_except_table3134
- GCC_except_table3140
- GCC_except_table3187
- GCC_except_table3200
- GCC_except_table3323
- GCC_except_table3324
- GCC_except_table3380
- GCC_except_table3440
- GCC_except_table3577
- GCC_except_table3648
- GCC_except_table3667
- GCC_except_table3686
- GCC_except_table3802
- GCC_except_table3833
- GCC_except_table3870
- GCC_except_table3872
- GCC_except_table3905
- GCC_except_table3907
- GCC_except_table3921
- GCC_except_table3929
- GCC_except_table3943
- GCC_except_table3944
- GCC_except_table3970
- GCC_except_table3975
- GCC_except_table3996
- GCC_except_table4005
- GCC_except_table4025
- GCC_except_table4030
- GCC_except_table4038
- GCC_except_table4056
- GCC_except_table4070
- GCC_except_table4109
- GCC_except_table4127
- GCC_except_table4133
- GCC_except_table4145
- GCC_except_table4167
- GCC_except_table4174
- GCC_except_table4312
- GCC_except_table4428
- GCC_except_table4617
- GCC_except_table4620
- GCC_except_table4621
- GCC_except_table4643
- GCC_except_table4672
- GCC_except_table4677
- GCC_except_table4691
- GCC_except_table4695
- GCC_except_table4696
- GCC_except_table4697
- GCC_except_table4703
- GCC_except_table4704
- GCC_except_table4728
- GCC_except_table4743
- GCC_except_table4826
- GCC_except_table4884
- GCC_except_table4997
- GCC_except_table5008
- GCC_except_table5024
- GCC_except_table5049
- GCC_except_table5051
- GCC_except_table5056
- GCC_except_table5223
- GCC_except_table5342
- GCC_except_table5435
- GCC_except_table5531
- GCC_except_table5559
- GCC_except_table5617
- GCC_except_table5723
- GCC_except_table5729
- GCC_except_table5744
- GCC_except_table5760
- GCC_except_table5781
- GCC_except_table5793
- GCC_except_table5810
- _OBJC_IVAR_$_UITableViewCellAccessibility._accessibilityIsFetchingChildren
- __OBJC_$_INSTANCE_VARIABLES_UITableViewCellAccessibility
- ___61-[UIScrollViewAccessibility _axManipulateWithRefreshControl:]_block_invoke
CStrings:
+ "AXHeadingLevel"
+ "UIRefreshControlAccessibility"
+ "_UIContextMenuHeaderView"
+ "_UIContextMenuHeaderViewAccessibility"
+ "isRefreshing"
+ "refreshed.content"
- "SkipConvertToLowercase"
- "_UIKeyboardShortcutView"
- "inputLabel"
- "keyShortcutInputView"
- "modifiersLabel"
```
