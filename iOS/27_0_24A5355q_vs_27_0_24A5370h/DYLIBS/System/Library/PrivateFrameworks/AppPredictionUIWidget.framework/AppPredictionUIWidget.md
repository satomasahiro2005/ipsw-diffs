## AppPredictionUIWidget

> `/System/Library/PrivateFrameworks/AppPredictionUIWidget.framework/AppPredictionUIWidget`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x150e0` | `0x159f0` | **`+0x910`** |
| `__AUTH_CONST.__objc_const` | `0x4110` | `0x41c0` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x17f0` | `0x1890` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x1ef8` | `0x1f60` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x488` | `0x4d8` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x20af` | `0x20f7` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x510` | `0x540` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x340` | `0x358` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1f8` | `0x20c` | **`+0x14`** |
| `__TEXT.__cstring` | `0x12de` | `0x12eb` | **`+0xd`** |
| `__DATA.__objc_ivar` | `0x15c` | `0x168` | **`+0xc`** |
| `__DATA.__data` | `0x9d0` | `0x9d8` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__const` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-658.0.9.0.0
+661.0.7.0.0

+  - /System/Library/PrivateFrameworks/ProactiveSupport.framework/ProactiveSupport

-  Functions: 597
-  Symbols:   1167
-  CStrings:  294
+  Functions: 607
+  Symbols:   1193
+  CStrings:  298
Symbols:
+ -[APUISuggestionIconView _layoutRedactedPlaceholder]
+ -[APUISuggestionIconView redactedForLockScreen]
+ -[APUISuggestionIconView setRedactedForLockScreen:]
+ -[APUISuggestionsWidgetView _rebuildForLockStateChange]
+ -[APUISuggestionsWidgetView dealloc]
+ -[APUISuggestionsWidgetView didMoveToWindow]
+ -[UILabel(LockScreenSupport) updateLabelBasedOnLockScreenState:]
+ GCC_except_table2
+ GCC_except_table6
+ GCC_except_table7
+ _OBJC_CLASS_$__PASDeviceState
+ _OBJC_IVAR_$_APUISuggestionIconView._redactedForLockScreen
+ _OBJC_IVAR_$_APUISuggestionIconView._redactedPlaceholderView
+ _OBJC_IVAR_$_APUISuggestionsWidgetView._lockStateRegistration
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_UILabel_$_LockScreenSupport
+ __OBJC_$_CATEGORY_UILabel_$_LockScreenSupport
+ ___44-[APUISuggestionsWidgetView didMoveToWindow]_block_invoke
+ ___44-[APUISuggestionsWidgetView didMoveToWindow]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_40_e8_32w_e8_v12?0i8lw32l8
+ _atx_SBHDefaultIconImageContinuousCornerRadiusForIconSize
+ _dispatch_assert_queue$V2
+ _kCACornerCurveCircular
+ _kCACornerCurveContinuous
+ _kPlaceholderConstraintsKey
+ _objc_copyWeak
+ _objc_initWeak
- GCC_except_table4
CStrings:
+ "A"
+ "Q"
+ "SuggestionsWidget: rebuilding for lock-state change (unlocked=%{BOOL}d)"
+ "v12@?0i8"
```
