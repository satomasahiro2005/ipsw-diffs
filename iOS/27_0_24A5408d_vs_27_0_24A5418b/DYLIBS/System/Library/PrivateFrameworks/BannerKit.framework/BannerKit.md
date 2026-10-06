## BannerKit

> `/System/Library/PrivateFrameworks/BannerKit.framework/BannerKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2dc24` | `0x2d8c8` | **`-0x35c`** |
| `__AUTH_CONST.__objc_const` | `0xd0b0` | `0xd050` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x3d8c` | `0x3d44` | **`-0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fa8` | `0x1f90` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0xfb0` | `0xfb8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2bc` | `0x2b8` | **`-0x4`** |

### Other Changes

```diff

-169.0.1.0.0
+169.0.2.0.0

-  Functions: 1144
-  Symbols:   2373
+  Functions: 1142
+  Symbols:   2366
Symbols:
+ +[BNBannerLayoutManager _dismissedFrameForContentWithPreferredSize:inUseableContainerFrame:containerBounds:layoutInfo:overshoot:scale:]
+ +[BNBannerLayoutManager _presentedFrameForContentWithPreferredSize:inUseableContainerFrame:containerBounds:layoutInfo:scale:]
+ -[BNContentViewController viewDidLayoutSubviews]
+ GCC_except_table101
+ GCC_except_table25
+ GCC_except_table82
- +[BNBannerLayoutManager _dismissedFrameForContentWithPreferredSize:inUseableContainerFrame:containerBounds:layoutInfo:alignment:overshoot:scale:]
- +[BNBannerLayoutManager _presentedFrameForContentWithPreferredSize:inUseableContainerFrame:containerBounds:layoutInfo:alignment:scale:]
- -[BNBannerLayoutManager alignment]
- -[BNBannerLayoutManager idealContentWidth]
- -[BNBannerLayoutManager setAlignment:]
- GCC_except_table100
- GCC_except_table24
- GCC_except_table32
- GCC_except_table81
- _CGRectIsNull
- _OBJC_IVAR_$_BNBannerLayoutManager._alignment
- __OBJC_$_PROP_LIST_BNLayoutManagingPrivate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_BNLayoutManagingPrivate
```
