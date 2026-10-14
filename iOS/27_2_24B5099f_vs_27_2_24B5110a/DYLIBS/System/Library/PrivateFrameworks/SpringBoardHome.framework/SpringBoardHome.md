## SpringBoardHome

> `/System/Library/PrivateFrameworks/SpringBoardHome.framework/SpringBoardHome`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x395728` | `0x396424` | **`+0xcfc`** |
| `__TEXT.__oslogstring` | `0xf840` | `0xfab0` | **`+0x270`** |
| `__TEXT.__objc_methlist` | `0x3ee5c` | `0x3eeac` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xfab8` | `0xfb00` | **`+0x48`** |
| `__DATA.__data` | `0x9798` | `0x97d8` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x2480` | `0x24b8` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cc58` | `0x1cc90` | **`+0x38`** |
| `__TEXT.__const` | `0x7fe4` | `0x7ff4` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1da8` | `0x1da0` | **`-0x8`** |

### Other Changes

```diff

-226.2.9.0.0
+226.2.11.201.0

-  Functions: 24877
-  Symbols:   33733
-  CStrings:  4601
+  Functions: 24895
+  Symbols:   33738
+  CStrings:  4606
Symbols:
+ +[SBHIconStateUnarchiver _todayListRepresentationFromRepresentation:]
+ -[SBFolderView _pageIndexForListInModelFolder:]
+ -[SBHWidgetContainerViewSnapshotResizeCoordinator _setResizableViewFrameIfPossible:]
+ -[SBIconView _insertCustomIconImageViewController:]
+ -[SBIconView _insertDelayedCustomImageViewIfPossible]
+ -[SBIconView _notifyObserversDidChangeCustomImageViewController:]
+ -[SBIconView insertCustomIconImageViewWhenPossible]
+ GCC_except_table171
+ GCC_except_table271
+ GCC_except_table274
+ GCC_except_table375
+ GCC_except_table387
+ GCC_except_table395
+ GCC_except_table423
+ GCC_except_table611
+ GCC_except_table668
+ GCC_except_table709
+ GCC_except_table99
+ _SBHScrollViewIsValidContentOffset
+ ___51-[SBIconView _insertCustomIconImageViewController:]_block_invoke
- GCC_except_table170
- GCC_except_table200
- GCC_except_table207
- GCC_except_table270
- GCC_except_table273
- GCC_except_table372
- GCC_except_table386
- GCC_except_table392
- GCC_except_table422
- GCC_except_table607
- GCC_except_table664
- GCC_except_table705
- GCC_except_table98
- ___61-[SBIconView setCustomIconImageViewController:clearingOwner:]_block_invoke
- _os_variant_has_internal_ui
CStrings:
+ "<%{public}@> Delaying insertion of custom icon image view controller %{public}@ until it's inside %{public}@"
+ "<%{public}@> Inserting delayed custom icon image view controller %{public}@"
+ "<%{public}@> Skipping widget view update; invalid widgetSize:%@"
+ "Custom icon image view controller %{public}@ has no superview; waiting for icon view %{public}@ to insert it"
+ "Ignoring invalid contentOffset %{public}@ for %{public}@; current contentOffset: %{public}@, bounds: %{public}@, contentSize: %{public}@, adjustedContentInset: %{public}@, pan state: %ld, pan translation: %{public}@, pan velocity: %{public}@"
+ "Skipping snapshot resize frame update; transform %{public}@ frame %{public}@ on %{public}@"
- "<SBHWidgetStackScrollView:%@> received invalid contentOffset:%@"
```
