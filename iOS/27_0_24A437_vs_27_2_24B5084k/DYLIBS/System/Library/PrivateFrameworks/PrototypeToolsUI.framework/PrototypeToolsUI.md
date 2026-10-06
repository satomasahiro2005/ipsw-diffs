## PrototypeToolsUI

> `/System/Library/PrivateFrameworks/PrototypeToolsUI.framework/PrototypeToolsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93fc` | `0xa620` | **`+0x1224`** |
| `__TEXT.__objc_methlist` | `0x1250` | `0x13a0` | **`+0x150`** |
| `__DATA_CONST.__objc_selrefs` | `0xf08` | `0x1038` | **`+0x130`** |
| `__AUTH_CONST.__objc_const` | `0x2bd0` | `0x2cc8` | **`+0xf8`** |
| `__DATA.__data` | `0x540` | `0x5a0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x3e8` | `0x430` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x220` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x320` | `0x340` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xb0` | `0xc8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x32a` | `0x33c` | **`+0x12`** |
| `__DATA_CONST.__objc_protolist` | `0x70` | `0x78` | **`+0x8`** |

### Other Changes

```diff

-164.0.0.0.0
+165.0.0.0.0

-  Functions: 266
-  Symbols:   714
-  CStrings:  44
+  Functions: 291
+  Symbols:   761
+  CStrings:  46
Symbols:
+ +[PTUIRowTableViewCell _infoHeightForText:font:width:]
+ +[PTUIRowTableViewCell infoExpandedHeightForRow:width:]
+ +[PTUIRowTableViewCell infoTextFont]
+ +[PTUIRowTableViewCell rowTitleFont]
+ +[PTUISliderRowTableViewCell infoExpandedHeightForRow:width:]
+ -[PTUIButtonRowTableViewCell canExpandInfo]
+ -[PTUIChoiceRowTableViewCell canExpandInfo]
+ -[PTUIDrillDownRowTableViewCell canExpandInfo]
+ -[PTUIModuleController rowTableViewCellDidToggleInfo:]
+ -[PTUIRowTableViewCell _clampToTopBand:band:]
+ -[PTUIRowTableViewCell _infoChevronTapped:]
+ -[PTUIRowTableViewCell _infoDoubleTapped:]
+ -[PTUIRowTableViewCell _toggleInfo]
+ -[PTUIRowTableViewCell canExpandInfo]
+ -[PTUIRowTableViewCell delegate]
+ -[PTUIRowTableViewCell infoBar]
+ -[PTUIRowTableViewCell infoLabel]
+ -[PTUIRowTableViewCell initWithStyle:reuseIdentifier:]
+ -[PTUIRowTableViewCell layoutSubviews]
+ -[PTUIRowTableViewCell managesOwnLayout]
+ -[PTUIRowTableViewCell setDelegate:]
+ -[PTUIRowTableViewCell setInfoExpanded:]
+ -[PTUISliderRowTableViewCell canExpandInfo]
+ -[PTUISliderRowTableViewCell layoutSubviews]
+ -[PTUISliderRowTableViewCell managesOwnLayout]
+ _CGRectGetHeight
+ _CGRectGetMaxY
+ _CGRectGetWidth
+ _NSFontAttributeName
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSHashTable
+ _OBJC_CLASS_$_UIImage
+ _OBJC_CLASS_$_UIImageSymbolConfiguration
+ _OBJC_CLASS_$_UIImageView
+ _OBJC_IVAR_$_PTUIModuleController._expandedRows
+ _OBJC_IVAR_$_PTUIRowTableViewCell._delegate
+ _OBJC_IVAR_$_PTUIRowTableViewCell._infoBar
+ _OBJC_IVAR_$_PTUIRowTableViewCell._infoChevron
+ _OBJC_IVAR_$_PTUIRowTableViewCell._infoLabel
+ _OBJC_IVAR_$_PTUISliderRowTableViewCell._sliderStack
+ __OBJC_$_CLASS_METHODS_PTUISliderRowTableViewCell
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_PTUIRowTableViewCellDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_PTUIRowTableViewCellDelegate
+ __OBJC_$_PROTOCOL_REFS_PTUIRowTableViewCellDelegate
+ __OBJC_LABEL_PROTOCOL_$_PTUIRowTableViewCellDelegate
+ __OBJC_PROTOCOL_$_PTUIRowTableViewCellDelegate
+ _objc_opt_respondsToSelector
CStrings:
+ "A"
+ "chevron.right"
```
