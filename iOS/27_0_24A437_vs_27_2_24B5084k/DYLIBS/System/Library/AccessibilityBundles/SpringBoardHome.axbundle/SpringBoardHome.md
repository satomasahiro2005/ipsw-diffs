## SpringBoardHome

> `/System/Library/AccessibilityBundles/SpringBoardHome.axbundle/SpringBoardHome`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21bbc` | `0x21da4` | **`+0x1e8`** |
| `__TEXT.__unwind_info` | `0xb58` | `0xb68` | **`+0x10`** |
| `__DATA.__data` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1000` | `0x1008` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x21e4` | `0x21ec` | **`+0x8`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 843
-  Symbols:   1867
+  Functions: 844
+  Symbols:   1869
Symbols:
+ -[SBIconViewAccessibility _accessibilityHintIsInstructional]
+ GCC_except_table736
+ GCC_except_table742
+ GCC_except_table749
+ GCC_except_table808
+ GCC_except_table821
+ GCC_except_table835
+ GCC_except_table838
+ _SBAXLastAnnouncedIconDragPage
- GCC_except_table735
- GCC_except_table741
- GCC_except_table748
- GCC_except_table807
- GCC_except_table820
- GCC_except_table834
- GCC_except_table837
Functions:
~ _AXSBScrollDescriptionForCurrentPage : 484 -> 512
~ -[SBDockIconListViewAccessibility accessibilityHint] : 664 -> 672
~ -[SBFolderControllerAccessibility folderViewDidEndScrolling:] : 260 -> 296
~ -[SBIconScrollViewAccessibility _accessibilityScrollStatus:] : 300 -> 304
~ -[SBIconScrollViewAccessibility _accessibilityScrollStatus] : 148 -> 152
~ ___60-[SBIconScrollViewAccessibility _accessibilityScrollToPage:]_block_invoke_2 : 192 -> 196
+ -[SBIconViewAccessibility _accessibilityHintIsInstructional]
~ -[SBIconViewAccessibility accessibilityDropPointDescriptors] : 4796 -> 5080
~ +[SBRootFolderViewAccessibility _accessibilityPerformValidations:] : 756 -> 768
```
