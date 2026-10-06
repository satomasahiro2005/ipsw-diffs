## AppPredictionUIWidget

> `/System/Library/PrivateFrameworks/AppPredictionUIWidget.framework/AppPredictionUIWidget`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x159f0` | `0x15ef8` | **`+0x508`** |
| `__AUTH_CONST.__objc_const` | `0x41c0` | `0x42a0` | **`+0xe0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1890` | `0x18f0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1f60` | `0x1fc0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x540` | `0x568` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x168` | `0x180` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x20c` | `0x208` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-667.0.0.0.0
+671.0.2.0.0

-  Functions: 607
-  Symbols:   1193
+  Functions: 617
+  Symbols:   1210
Symbols:
+ -[APUIAppIconGridLayoutProvider hasExplicitScreenType]
+ -[APUIAppIconGridLayoutProvider screenType]
+ -[APUIAppIconGridLayoutProvider setHasExplicitScreenType:]
+ -[APUIAppIconGridLayoutProvider setScreenType:]
+ -[APUIAppIconGridView _currentInterfaceOrientation]
+ -[APUIAppIconGridView _fixedListWidthForOrientation:]
+ -[APUIAppIconGridView _makeLayoutProvider]
+ -[APUIAppIconGridView _updateLayoutForCurrentDisplay]
+ GCC_except_table11
+ GCC_except_table18
+ GCC_except_table21
+ GCC_except_table25
+ GCC_except_table3
+ GCC_except_table34
+ _OBJC_IVAR_$_APUIAppIconGridLayoutProvider._hasExplicitScreenType
+ _OBJC_IVAR_$_APUIAppIconGridLayoutProvider._screenType
+ _OBJC_IVAR_$_APUIAppIconGridView._appliedOrientation
+ _OBJC_IVAR_$_APUIAppIconGridView._appliedScreenType
+ _OBJC_IVAR_$_APUIAppIconGridView._fixedListWidth
+ _OBJC_IVAR_$_APUIAppIconGridView._hasAppliedScreenType
+ _getSBHDefaultIconListLayoutProviderClass
+ _getSBIconLocationRoot
- GCC_except_table12
- GCC_except_table15
- GCC_except_table19
- GCC_except_table28
- GCC_except_table5
```
