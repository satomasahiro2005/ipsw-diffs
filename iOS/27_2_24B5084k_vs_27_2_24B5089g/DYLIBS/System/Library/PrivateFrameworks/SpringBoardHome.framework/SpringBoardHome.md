## SpringBoardHome

> `/System/Library/PrivateFrameworks/SpringBoardHome.framework/SpringBoardHome`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x393358` | `0x393d78` | **`+0xa20`** |
| `__AUTH.__objc_data` | `0xb990` | `0xb670` | **`-0x320`** |
| `__DATA_DIRTY.__objc_data` | `0x1590` | `0x18b0` | **`+0x320`** |
| `__TEXT.__oslogstring` | `0xf560` | `0xf710` | **`+0x1b0`** |
| `__AUTH_CONST.__cfstring` | `0x16f00` | `0x16f60` | **`+0x60`** |
| `__TEXT.__cstring` | `0x18c93` | `0x18cd3` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x4364` | `0x43a4` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3edbc` | `0x3edfc` | **`+0x40`** |
| `__AUTH.__data` | `0xcb0` | `0xc80` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x7940` | `0x7960` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x59100` | `0x59120` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cc18` | `0x1cc38` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x60` | `0x80` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xfa40` | `0xfa60` | **`+0x20`** |
| `__DATA.__data` | `0x9790` | `0x9788` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x9ed8` | `0x9ed0` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x3dc4` | `0x3dc8` | **`+0x4`** |

### Other Changes

```diff

-226.2.5.0.0
+226.2.7.201.0

-  Functions: 24832
-  Symbols:   33708
-  CStrings:  4590
+  Functions: 24840
+  Symbols:   33718
+  CStrings:  4598
Symbols:
+ -[SBIconDragContext addIconHiddenForDropAnimation:]
+ -[SBIconDragContext isIconHiddenForDropAnimation:]
+ -[SBIconDragManager _sourceIconViewForDragItem:inDragContext:primaryIconView:]
+ -[SBIconDragManager configureIconView:forIcon:]
+ -[SBIconView _updateAttributedApp]
+ -[SBIconView leafIcon:didChangeActiveDataSource:]
+ GCC_except_table199
+ GCC_except_table210
+ GCC_except_table255
+ GCC_except_table344
+ GCC_except_table362
+ GCC_except_table366
+ GCC_except_table372
+ GCC_except_table392
+ GCC_except_table607
+ GCC_except_table664
+ GCC_except_table705
+ _OBJC_IVAR_$_SBIconDragContext._iconsHiddenForDropAnimation
+ ___47-[SBIconDragManager configureIconView:forIcon:]_block_invoke
+ ___47-[SBIconDragManager configureIconView:forIcon:]_block_invoke_2
+ ___49-[SBHIconManager _dumpRootFolderForStateCapture:]_block_invoke_3
+ ___69-[SBIconDragManager iconView:item:willAnimateDragCancelWithAnimator:]_block_invoke_7
+ ___78-[SBIconDragManager _sourceIconViewForDragItem:inDragContext:primaryIconView:]_block_invoke
+ ___block_descriptor_32_e25_16?0"SBIconListModel"8l
- -[SBIconDragManager configureIconView:]
- GCC_except_table227
- GCC_except_table292
- GCC_except_table330
- GCC_except_table359
- GCC_except_table363
- GCC_except_table371
- GCC_except_table391
- GCC_except_table606
- GCC_except_table663
- GCC_except_table704
- ___39-[SBIconDragManager configureIconView:]_block_invoke
- ___51-[SBIconDragManager iconViewWillBeginDrag:session:]_block_invoke_3
- ___block_descriptor_56_e8_32s40s48s_e33_v24?0"<SBIconDragPreview>"8^B16ls32l8s40l8s48l8
CStrings:
+ "@16@?0@\"SBIconListModel\"8"
+ "Page visibility changing: list %{public}@ hidden %{public}d -> %{public}d, byUser: %{public}d, hiddenDate: %{public}@"
+ "PlatterCancelAnimation"
+ "PlatterDropAnimation"
+ "[%@] Focus %{public}@ does not require feature introduction"
+ "[%@] skipping donated focus mode %{public}@; it was superseded by %{public}@ before scrolling ended"
+ "[%@] updating page visibility for focus mode %{public}@ across %{public}lu lists; customizedHomeScreenPagesEnabled: %{public}d"
+ "lists"
+ "reapplying dropping state to recycled icon view %p for icon %{public}@"
+ "\xf0\xf0\xf0A"
- "[%@] Focus does not require feature introduction"
- "\xf0\xf0\xf01"
```
