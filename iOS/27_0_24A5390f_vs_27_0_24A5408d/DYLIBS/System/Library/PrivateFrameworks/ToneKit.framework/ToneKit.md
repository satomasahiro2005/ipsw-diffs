## ToneKit

> `/System/Library/PrivateFrameworks/ToneKit.framework/ToneKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26858` | `0x26b50` | **`+0x2f8`** |
| `__TEXT.__cstring` | `0x18c1` | `0x19ab` | **`+0xea`** |
| `__AUTH_CONST.__objc_const` | `0x5190` | `0x50c0` | **`-0xd0`** |
| `__DATA_CONST.__const` | `0x5b8` | `0x630` | **`+0x78`** |
| `__AUTH.__objc_data` | `0x960` | `0x910` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x1a8` | `0x1ec` | **`+0x44`** |
| `__TEXT.__oslogstring` | `0xaa4` | `0xae7` | **`+0x43`** |
| `__TEXT.__objc_methlist` | `0x33dc` | `0x33b4` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1220` | `0x1240` | **`+0x20`** |
| `__TEXT.__const` | `0x108` | `0xf8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xb10` | `0xb20` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x478` | `0x470` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x118` | `0x110` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2580` | `0x2588` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x100` | `0xf8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x42c` | `0x428` | **`-0x4`** |

### Other Changes

```diff

-672.0.0.0.0
+675.0.0.0.0

-  Functions: 1028
-  Symbols:   1927
-  CStrings:  240
+  Functions: 1030
+  Symbols:   1924
+  CStrings:  243
Symbols:
+ +[TKPickerTableViewCell checkmarkImage]
+ +[TKPickerTableViewCell checkmarkPlaceholderImage]
+ -[TKPickerTableViewCell indentedRowSeparatorLeftInset]
+ -[TKTonePickerItem _setWantsIndentedLayout:]
+ -[TKTonePickerItem wantsIndentedLayout]
+ -[TKTonePickerViewController _isAlarmWakeUp]
+ -[TKTonePickerViewController _shouldShowCheckmarkOnLeadingEdge]
+ GCC_except_table50
+ GCC_except_table60
+ GCC_except_table71
+ GCC_except_table74
+ _OBJC_IVAR_$_TKTonePickerItem._wantsIndentedLayout
+ _OBJC_IVAR_$_TKTonePickerViewController._checkmarkPlaceholderImage
+ _OBJC_IVAR_$_TKVibrationPickerViewController._isAnimatingCommittedRowDeletion
+ _OBJC_IVAR_$_TKVibrationPickerViewController._pendingSwipeToDeleteExitEditingModeAfterRowDeletionAnimation
+ __OBJC_$_CLASS_METHODS_TKPickerTableViewCell
+ ___82-[TKVibrationPickerViewController tableView:commitEditingStyle:forRowAtIndexPath:]_block_invoke
+ ___82-[TKVibrationPickerViewController tableView:commitEditingStyle:forRowAtIndexPath:]_block_invoke_2
+ ___82-[TKVibrationPickerViewController tableView:commitEditingStyle:forRowAtIndexPath:]_block_invoke_3
+ ___86-[TKVibrationPickerViewController _handleUserGeneratedVibrationsDidChangeNotification]_block_invoke
+ ___86-[TKVibrationPickerViewController _handleUserGeneratedVibrationsDidChangeNotification]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_40_e8_32w_e8_v12?0B8lw32l8
+ ___block_descriptor_48_e8_32s_e5_v8?0ls32l8
- +[TKTonePickerViewController _checkmarkImage]
- -[TKPickerRowItem _setWantsIndentedLayout:]
- -[TKPickerRowItem wantsIndentedLayout]
- -[TKTonePickerTableViewCellLayoutManager _adjustedTextFrameWithOriginalTextFrame:forCell:]
- -[TKTonePickerTableViewCellLayoutManager minimumTextIndentation]
- -[TKTonePickerTableViewCellLayoutManager setMinimumTextIndentation:]
- -[TKTonePickerTableViewCellLayoutManager textRectForCell:rowWidth:forSizing:]
- -[TKTonePickerViewController _minimumTextIndentationForTableView:withCheckmarkImage:]
- -[TKTonePickerViewController _shouldShowCheckmarkOnTrailingEdge]
- -[TKVibrationPickerTableViewCell _layoutRemovableTextField]
- -[TKVibrationPickerTableViewCell layoutSubviews]
- GCC_except_table61
- GCC_except_table75
- _OBJC_CLASS_$_TKTonePickerTableViewCellLayoutManager
- _OBJC_CLASS_$_UITableViewCellLayoutManagerValue1
- _OBJC_IVAR_$_TKPickerRowItem._wantsIndentedLayout
- _OBJC_IVAR_$_TKTonePickerTableViewCellLayoutManager._minimumTextIndentation
- _OBJC_IVAR_$_TKTonePickerViewController._tableViewCellLayoutManagerForIndentedRemixRows
- _OBJC_IVAR_$_TKTonePickerViewController._tableViewCellLayoutManagerForIndentedRows
- _OBJC_IVAR_$_TKTonePickerViewController._tableViewCellLayoutManagerForUnindentedRows
- _OBJC_METACLASS_$_TKTonePickerTableViewCellLayoutManager
- _OBJC_METACLASS_$_UITableViewCellLayoutManagerValue1
- __OBJC_$_INSTANCE_METHODS_TKTonePickerTableViewCellLayoutManager
- __OBJC_$_INSTANCE_VARIABLES_TKTonePickerTableViewCellLayoutManager
- __OBJC_$_PROP_LIST_TKTonePickerTableViewCellLayoutManager
- __OBJC_CLASS_RO_$_TKTonePickerTableViewCellLayoutManager
- __OBJC_METACLASS_RO_$_TKTonePickerTableViewCellLayoutManager
CStrings:
+ "-[TKTonePickerItem wantsIndentedLayout]"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/ToneLibraryUI/Kit/Tones/TKTonePickerItem.m"
+ "A nested row must be able to show a leading checkmark: %{public}@."
+ "_TLVibrationPickerViewTableCellEditableIdentifier"
+ "\xf1B"
- "\xe1B"
- "\xf01"
```
