## ProxCardKit

> `/System/Library/PrivateFrameworks/ProxCardKit.framework/ProxCardKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e120` | `0x1e39c` | **`+0x27c`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fe0` | `0x2008` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x8f50` | `0x8f70` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2dd8` | `0x2df0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x820` | `0x830` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3f8` | `0x400` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x390` | `0x394` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2131.10.1.2.11
+2131.20.65.2.1

-  Functions: 725
-  Symbols:   1750
+  Functions: 728
+  Symbols:   1754
Symbols:
+ -[PRXCardContainerView deactivateKeyboardSpecificConstraintsIfNeeded]
+ -[PRXCardContainerViewController _updateContainerPreferredContentSizeForContainerSize:]
+ -[PRXCardContentView layoutSubviews]
+ _OBJC_CLASS_$_UIViewLayoutRegion
+ _OBJC_IVAR_$_PRXCardContainerView._contentMaxHeight
- _CGRectContainsPoint
Functions:
~ -[PRXCardContainerViewController viewWillTransitionToSize:withTransitionCoordinator:] : 212 -> 220
~ -[PRXCardContainerViewController traitCollectionDidChange:] : 252 -> 336
~ -[PRXCardContainerViewController _updateContainerPreferredContentSize] : 216 -> 80
+ -[PRXCardContainerViewController _updateContainerPreferredContentSizeForContainerSize:]
~ -[PRXCardContainerViewController navigationController:willShowViewController:animated:] : 416 -> 424
+ -[PRXCardContentView layoutSubviews]
~ -[PRXCardContainerView initWithFrame:containerLayoutMargins:] : 2912 -> 2932
~ -[PRXCardContainerView setPreferredContentSize:] : 184 -> 204
~ -[PRXCardContainerView _updateKeyboardDeferred:] : 544 -> 744
+ -[PRXCardContainerView deactivateKeyboardSpecificConstraintsIfNeeded]
~ -[PRXCardContainerView gestureRecognizerShouldBegin:] : 276 -> 268
CStrings:
+ "\xf0\xe1"
- "\xf0\xd1"
```
