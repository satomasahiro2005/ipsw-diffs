## CarouselLayoutSettings

> `/System/Library/NanoPreferenceBundles/Customization/CarouselLayoutSettings.bundle/CarouselLayoutSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21894` | `0x21a88` | **`+0x1f4`** |
| `__TEXT.__objc_stubs` | `0x3d40` | `0x3e40` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x430a` | `0x43f9` | **`+0xef`** |
| `__TEXT.__objc_methtype` | `0x20cb` | `0x213d` | **`+0x72`** |
| `__DATA.__objc_const` | `0x3560` | `0x35c8` | **`+0x68`** |
| `__DATA.__data` | `0x4e0` | `0x540` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x780` | `0x7d0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x1844` | `0x1894` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x1308` | `0x1348` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xf38` | `0xf68` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x3d8` | `0x400` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x2f0` | `0x314` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x450` | `0x460` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2ab4` | `0x2ac4` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x274` | `0x27c` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x68` | `0x70` | **`+0x8`** |
| `__TEXT.__cstring` | `0x972` | `0x974` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-1115.0.105.0.0
+1115.1.4.0.0

-  Functions: 709
-  Symbols:   327
-  CStrings:  1244
+  Functions: 714
+  Symbols:   334
+  CStrings:  1258
Symbols:
+ _CGRectGetMaxY
+ _CGRectGetMinX
+ _CGRectGetMinY
+ _CGRectGetWidth
+ _CGRectNull
+ _CGSizeZero
+ _CSLPRFNear
+ _OBJC_CLASS_$__UIScrollEdgeEffectViewInteraction
- _OBJC_CLASS_$_UINavigationBarAppearance
CStrings:
+ "\"!"
+ "@\"_UIScrollEdgeEffectViewInteraction\""
+ "CSLUIFieldOfIconsViewScrollDelegate"
+ "_fieldOfIconsViewOptions"
+ "_scrollEdgeEffectInteraction"
+ "addInteraction:"
+ "captureView"
+ "effectView"
+ "scrollEdgeEffectContentRect"
+ "update"
+ "updateFieldOfIconsLayoutIfNeeded"
+ "updateScrollEdgeEffect"
+ "updateWithContentRect:shouldAnimateVisibility:"
+ "v28@0:8@\"CSLUIFieldOfIconsView\"16B24"
+ "viewDidLayoutSubviews"
+ "{CGRect={CGPoint=dd}{CGSize=dd}}16@0:8"
- "#"
- "navigationBar"
```
