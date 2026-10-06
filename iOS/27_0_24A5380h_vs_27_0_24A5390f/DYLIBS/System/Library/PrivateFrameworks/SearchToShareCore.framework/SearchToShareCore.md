## SearchToShareCore

> `/System/Library/PrivateFrameworks/SearchToShareCore.framework/SearchToShareCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9399c` | `0x93d58` | **`+0x3bc`** |
| `__AUTH_CONST.__cfstring` | `0x1c20` | `0x1b40` | **`-0xe0`** |
| `__TEXT.__cstring` | `0x23a1` | `0x22e1` | **`-0xc0`** |
| `__TEXT.__objc_methlist` | `0x49ac` | `0x4a1c` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f88` | `0x2fd8` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xc968` | `0xc9a8` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2ae8` | `0x2b08` | **`+0x20`** |
| `__DATA_CONST.__objc_catlist` | `0x88` | `0x90` | **`+0x8`** |

### Other Changes

```diff

-3400.1.6.28.0
+3400.1.6.30.0

-  Functions: 4007
-  Symbols:   3453
-  CStrings:  408
+  Functions: 4015
+  Symbols:   3464
+  CStrings:  401
Symbols:
+ +[UITraitCollection(STSVerticalBar) sts_isVerticalBarPresent:]
+ +[UITraitCollection(STSVerticalBar) sts_systemTraitsAffectingVerticalBar]
+ -[STSSearchBrowserHeaderView updateCancelButtonForVerticalBarPresent:]
+ -[STSSearchBrowserRootViewController _sts_closeBarButtonItemTapped:]
+ -[STSSearchBrowserRootViewController _sts_makeCloseBarButtonItem]
+ -[STSSearchBrowserRootViewController _sts_registerForVerticalBarTraitChanges]
+ -[STSSearchBrowserRootViewController _sts_syncCancelAffordanceForCurrentTraits]
+ -[STSSearchBrowserRootViewController viewDidLoad]
+ GCC_except_table31
+ _OBJC_CLASS_$_UITraitCollection
+ __OBJC_$_CATEGORY_CLASS_METHODS_UITraitCollection_$_STSVerticalBar
+ __OBJC_$_CATEGORY_UITraitCollection_$_STSVerticalBar
- GCC_except_table26
CStrings:
- "H:|-(contentInsetsLeft)-[_label]-(contentInsetsRight)-|"
- "V:|-(contentInsetsTop)-[_label]-(contentInsetsBottom)-|"
- "_label"
- "contentInsetsBottom"
- "contentInsetsLeft"
- "contentInsetsRight"
- "contentInsetsTop"
```
