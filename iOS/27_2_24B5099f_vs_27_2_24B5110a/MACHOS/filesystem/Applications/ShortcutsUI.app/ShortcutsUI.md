## ShortcutsUI

> `/Applications/ShortcutsUI.app/ShortcutsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fe70` | `0x205bc` | **`+0x74c`** |
| `__TEXT.__objc_stubs` | `0x5b00` | `0x5ce0` | **`+0x1e0`** |
| `__TEXT.__objc_methname` | `0x87d5` | `0x8976` | **`+0x1a1`** |
| `__DATA.__objc_selrefs` | `0x1da0` | `0x1e28` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0x2654` | `0x26cc` | **`+0x78`** |
| `__TEXT.__cstring` | `0x24dc` | `0x2551` | **`+0x75`** |
| `__DATA.__objc_const` | `0x4188` | `0x41e8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xad0` | `0xb20` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x70c` | `0x744` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x7e8` | `0x820` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x1ab3` | `0x1acb` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x6e0` | `0x6f0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x284` | `0x28c` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x380` | `0x388` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x410` | `0x418` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-5113.0.1.1.1
+5114.0.8.3.0

-  Functions: 788
-  Symbols:   258
-  CStrings:  1895
+  Functions: 800
+  Symbols:   260
+  CStrings:  1919
Symbols:
+ _CGRectGetMinX
+ _OBJC_CLASS_$_UIHingeInteraction
CStrings:
+ "3"
+ "TB,N,V_hingeIsFullyOpen"
+ "TB,N,V_hingeIsOpen"
+ "_hingeIsFullyOpen"
+ "_hingeIsOpen"
+ "addInteraction:"
+ "animateAlongsideTransition:completion:"
+ "convertRect:toCoordinateSpace:"
+ "coordinateSpace"
+ "displayIsLandscape"
+ "foldIsActive"
+ "hinge"
+ "hingeIsFullyOpen"
+ "hingeIsOpen"
+ "initWithUpdateHandler:"
+ "platterOriginXInBannerMode"
+ "setHingeIsFullyOpen:"
+ "setHingeIsOpen:"
+ "status"
+ "updateForHinge:"
+ "v16@?0@\"<UIViewControllerTransitionCoordinatorContext>\"8"
+ "v24@?0@\"UIHingeInteraction\"8@\"UIHingeInteractionUpdate\"16"
+ "v40@0:8{CGSize=dd}16@32"
+ "viewDidLoad"
+ "viewWillTransitionToSize:withTransitionCoordinator:"
- "#"
```
