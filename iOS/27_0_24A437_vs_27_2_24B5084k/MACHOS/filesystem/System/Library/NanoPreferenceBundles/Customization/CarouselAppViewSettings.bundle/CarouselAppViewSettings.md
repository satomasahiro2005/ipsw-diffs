## CarouselAppViewSettings

> `/System/Library/NanoPreferenceBundles/Customization/CarouselAppViewSettings.bundle/CarouselAppViewSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22cd4` | `0x22ec8` | **`+0x1f4`** |
| `__TEXT.__objc_stubs` | `0x4120` | `0x4220` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x4826` | `0x4915` | **`+0xef`** |
| `__TEXT.__objc_methtype` | `0x210d` | `0x217f` | **`+0x72`** |
| `__DATA.__objc_const` | `0x4148` | `0x41b0` | **`+0x68`** |
| `__DATA.__data` | `0x540` | `0x5a0` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x7c0` | `0x810` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x1a7c` | `0x1acc` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x1470` | `0x14b0` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x3f8` | `0x420` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x361` | `0x385` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0xfb8` | `0xfd8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x498` | `0x4a8` | **`+0x10`** |
| `__TEXT.__const` | `0x3a8` | `0x398` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2ab4` | `0x2ac4` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x29c` | `0x2a4` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__cstring` | `0xa54` | `0xa56` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1115.0.105.0.0
+1115.1.4.0.0

-  Functions: 764
-  Symbols:   352
-  CStrings:  1323
+  Functions: 769
+  Symbols:   359
+  CStrings:  1337
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
