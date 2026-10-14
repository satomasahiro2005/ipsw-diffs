## SpringBoardHome

> `/System/Library/AccessibilityBundles/SpringBoardHome.axbundle/SpringBoardHome`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2274c` | `0x22dc8` | **`+0x67c`** |
| `__TEXT.__gcc_except_tab` | `0xbac` | `0xae0` | **`-0xcc`** |
| `__TEXT.__cstring` | `0x521a` | `0x5250` | **`+0x36`** |
| `__DATA_CONST.__const` | `0x7e0` | `0x808` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x5f80` | `0x5fa0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1038` | `0x1050` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xba8` | `0xbc0` | **`+0x18`** |
| `__DATA.__bss` | `0x140` | `0x130` | **`-0x10`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  Functions: 855
-  Symbols:   1884
-  CStrings:  856
+  Functions: 861
+  Symbols:   1893
+  CStrings:  857
Symbols:
+ -[SBIconViewAccessibility _axDropPointForInsertionAtGridCellIndex:rootList:model:placeholderCell:fallback:]
+ GCC_except_table667
+ GCC_except_table668
+ GCC_except_table675
+ GCC_except_table693
+ GCC_except_table696
+ GCC_except_table706
+ GCC_except_table707
+ GCC_except_table723
+ GCC_except_table733
+ GCC_except_table740
+ GCC_except_table741
+ GCC_except_table757
+ GCC_except_table764
+ GCC_except_table773
+ GCC_except_table825
+ GCC_except_table838
+ GCC_except_table852
+ GCC_except_table855
+ _CGRectIsEmpty
+ _CGRectIsNull
+ ___107-[SBIconViewAccessibility _axDropPointForInsertionAtGridCellIndex:rootList:model:placeholderCell:fallback:]_block_invoke
+ ___107-[SBIconViewAccessibility _axDropPointForInsertionAtGridCellIndex:rootList:model:placeholderCell:fallback:]_block_invoke_2
+ ___107-[SBIconViewAccessibility _axDropPointForInsertionAtGridCellIndex:rootList:model:placeholderCell:fallback:]_block_invoke_3
+ ___107-[SBIconViewAccessibility _axDropPointForInsertionAtGridCellIndex:rootList:model:placeholderCell:fallback:]_block_invoke_4
+ ___107-[SBIconViewAccessibility _axDropPointForInsertionAtGridCellIndex:rootList:model:placeholderCell:fallback:]_block_invoke_5
+ ___107-[SBIconViewAccessibility _axDropPointForInsertionAtGridCellIndex:rootList:model:placeholderCell:fallback:]_block_invoke_6
+ ___block_descriptor_72_e8_32s40r_e5_v8?0lr40l8s32l8
+ ___block_descriptor_80_e8_32s40s48s56r_e5_v8?0ls32l8s40l8r56l8s48l8
- -[SBIconViewAccessibility accessibilityElementDidBecomeFocused]
- GCC_except_table669
- GCC_except_table687
- GCC_except_table690
- GCC_except_table700
- GCC_except_table701
- GCC_except_table717
- GCC_except_table727
- GCC_except_table734
- GCC_except_table735
- GCC_except_table745
- GCC_except_table758
- GCC_except_table767
- GCC_except_table819
- GCC_except_table832
- GCC_except_table846
- GCC_except_table849
- ___block_descriptor_80_e8_32s40s48s56r_e5_v8?0lr56l8s32l8s40l8s48l8
- _dropIndicies
- _dropIndiciesIconIdentifier
CStrings:
+ "gridCellIndex"
+ "gridPath"
+ "rectForDragHitRegion:forDefaultSizedCellAtCoordinate:"
- "afterIndex"
- "beforeIndex"
```
