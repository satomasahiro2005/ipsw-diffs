## UnityPoster

> `/private/var/staged_system_apps/UnityPosterApp.app/Extensions/UnityPoster.appex/UnityPoster`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f14` | `0x3764` | **`+0x850`** |
| `__DATA.__objc_const` | `0x658` | `0x8a0` | **`+0x248`** |
| `__TEXT.__objc_stubs` | `0xdc0` | `0xf20` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0x159a` | `0x16ae` | **`+0x114`** |
| `__TEXT.__objc_methlist` | `0x5c4` | `0x6a8` | **`+0xe4`** |
| `__TEXT.__objc_methtype` | `0xaac` | `0xb42` | **`+0x96`** |
| `__DATA.__data` | `0x2b8` | `0x318` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x5c8` | `0x628` | **`+0x60`** |
| `__DATA.__objc_data` | `0x50` | `0xa0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x1f0` | `0x240` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x390` | `0x3d0` | **`+0x40`** |
| `__TEXT.__cstring` | `0xf2` | `0x12c` | **`+0x3a`** |
| `__TEXT.__objc_classname` | `0xbb` | `0xeb` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x130` | `0x160` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1d0` | `0x1f0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-2483.512.0.0.0
+2483.523.0.4.0

+  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

-  Functions: 73
-  Symbols:   105
-  CStrings:  307
+  Functions: 86
+  Symbols:   111
+  CStrings:  333
Symbols:
+ _CGRectEqualToRect
+ _OBJC_CLASS_$__UPContainerStateProxy
+ _OBJC_METACLASS_$__UPContainerStateProxy
+ _objc_msgSendSuper2
+ _objc_retainBlock
+ _objc_retain_x4
CStrings:
+ "@32@0:8{CGSize=dd}16"
+ "Td,R,N"
+ "Tq,R,N"
+ "T{CGSize=dd},R,N"
+ "WFWSPosterContainerStateSource"
+ "_UPContainerStateProxy"
+ "_cleanupAllQuiltViews"
+ "_lastPadBounds"
+ "_recreatePadQuiltViewInParentView:"
+ "_size"
+ "animateAlongsideTransition:completion:"
+ "d16@0:8"
+ "deviceSizeTarget"
+ "initWithSize:"
+ "interfaceOrientation"
+ "layoutDirection"
+ "orientation"
+ "pixelNativeScale"
+ "pixelScale"
+ "q16@0:8"
+ "setFromSource:"
+ "size"
+ "v16@?0@\"<UIViewControllerTransitionCoordinatorContext>\"8"
+ "{CGRect=\"origin\"{CGPoint=\"x\"d\"y\"d}\"size\"{CGSize=\"width\"d\"height\"d}}"
+ "{CGSize=\"width\"d\"height\"d}"
+ "{CGSize=dd}16@0:8"
```
