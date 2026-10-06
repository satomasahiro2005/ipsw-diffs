## Reminders

> `/private/var/staged_system_apps/Reminders.app/Reminders`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x575674` | `0x577978` | **`+0x2304`** |
| `__TEXT.__objc_methname` | `0x18cb5` | `0x19295` | **`+0x5e0`** |
| `__TEXT.__objc_methtype` | `0x5dd7` | `0x6027` | **`+0x250`** |
| `__TEXT.__objc_methlist` | `0x6684` | `0x67dc` | **`+0x158`** |
| `__DATA.__objc_const` | `0x1a3c8` | `0x1a508` | **`+0x140`** |
| `__TEXT.__objc_stubs` | `0xa400` | `0xa500` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x21010` | `0x21108` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0xc2b0` | `0xc3a0` | **`+0xf0`** |
| `__DATA.__objc_data` | `0xc068` | `0xc138` | **`+0xd0`** |
| `__DATA.__objc_selrefs` | `0x4480` | `0x4548` | **`+0xc8`** |
| `__DATA.__data` | `0x2acc8` | `0x2ad88` | **`+0xc0`** |
| `__TEXT.__objc_classname` | `0x66b8` | `0x6718` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xd3c8` | `0xd420` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0xe7a9` | `0xe7f9` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x12478` | `0x124b8` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0xc3e4` | `0xc418` | **`+0x34`** |
| `__TEXT.__swift5_capture` | `0xa054` | `0xa084` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x4d30` | `0x4d48` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x3e8` | `0x3f8` | **`+0x10`** |
| `__DATA.__common` | `0x560` | `0x568` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3ff8` | `0x4000` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xba8` | `0xbb0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x124f6` | `0x124fc` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0xbe8` | `0xbec` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4077.0.0.0.0
+4079.0.0.0.0

-  Functions: 19103
-  Symbols:   8429
-  CStrings:  6276
+  Functions: 19135
+  Symbols:   8432
+  CStrings:  6322
Symbols:
+ _$s15RemindersUICore44TTRIRemindersListReminderCell_collectionViewC52requiredHorizontalMarginsForInsetSelectionBackground12CoreGraphics7CGFloatVvgZ
+ _$s15RemindersUICore52TTRIRemindersListReminderCellDelegate_collectionViewP09remindersdF19DidExpandForEditingyyAA0cdef1_hI0CFTq
+ _$s15RemindersUICore52TTRIRemindersListReminderCellDelegate_collectionViewP09remindersdF20WillExpandForEditingyyAA0cdef1_hI0CFTq
+ _OBJC_CLASS_$_UICollectionViewLayoutInvalidationContext
- _$s15RemindersUICore46TTRICollectionViewTreeBackedDiffableDataSourceC59isBatchedIncrementalUpdatesDisabled_workaroundRdar145323570SbvsTj
CStrings:
+ "@\"<UIViewControllerAnimatedTransitioning>\"40@0:8@\"UISplitViewController\"16q24q32"
+ "@\"UIView\"32@0:8@\"UISplitViewController\"16q24"
+ "B24@0:8@\"UISplitViewController\"16"
+ "B40@0:8@\"UISplitViewController\"16@\"UIGestureRecognizer\"24q32"
+ "B40@0:8@\"UISplitViewController\"16q24Q32"
+ "B40@0:8@16q24Q32"
+ "B44@0:8@\"UISplitViewController\"16@\"UIViewController\"24@\"UIViewController\"32B40"
+ "B44@0:8@16@24@32B40"
+ "Not performing state restoration because disabled by internal setting"
+ "Not saving stateRestorationActivity because disabled by internal setting {scene: %s}"
+ "SidebarRecoveryDebug: revealing primary column { width: %ld }"
+ "UISplitViewControllerDelegatePrivate"
+ "_TtC9Reminders34TTRIRemindersListElevatedRowLayout"
+ "_preferredSearchColumnForSplitViewController:"
+ "_splitViewController:allowInteractivePresentationGesture:inContentsOfColumn:"
+ "_splitViewController:animationControllerForTransitionFromDisplayMode:toDisplayMode:"
+ "_splitViewController:collapseSecondaryViewController:ontoPrimaryViewController:forRestorationOfCollapsedWhileSuspendedWithPrimaryVisible:"
+ "_splitViewController:constrainPrimaryColumnWidthForResizeWidth:"
+ "_splitViewController:constrainSupplementaryColumnWidthForResizeWidth:"
+ "_splitViewController:didChangeFromDisplayMode:toDisplayMode:"
+ "_splitViewController:didEndResizingColumn:"
+ "_splitViewController:didFinishExpandToDisplayMode:"
+ "_splitViewController:displayModeButtonViewInColumn:"
+ "_splitViewController:overrideProposedPermission:forInteractivePresentationGesture:inView:"
+ "_splitViewController:shouldDisplaySidebarWithReason:withHeading:"
+ "_splitViewController:willBeginResizingColumn:"
+ "_splitViewControllerInteractiveSidebarGestureDidEnd:"
+ "_splitViewControllerInteractiveSidebarGestureWillBegin:"
+ "_splitViewControllerIsPrimaryVisible:"
+ "_splitViewControllerShouldRestoreResponderAfterTraitCollectionTransition:"
+ "d32@0:8@\"UISplitViewController\"16d24"
+ "d32@0:8@16d24"
+ "didNavigateOnSceneConnection"
+ "disableWindowStateRestoration"
+ "elevatedIndexPath"
+ "elevatedItemID"
+ "indexPath"
+ "invalidateItemsAtIndexPaths:"
+ "invalidateLayoutWithContext:"
+ "q48@0:8@\"UISplitViewController\"16q24@\"UIGestureRecognizer\"32@\"UIView\"40"
+ "q48@0:8@16q24@32@40"
+ "representedElementCategory"
+ "setZIndex:"
+ "showColumn:"
+ "v40@0:8@\"UISplitViewController\"16q24q32"
+ "zIndex"
```
