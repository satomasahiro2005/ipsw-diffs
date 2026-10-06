## BannerKit

> `/System/Library/PrivateFrameworks/BannerKit.framework/BannerKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d4b4` | `0x2d77c` | **`+0x2c8`** |
| `__TEXT.__oslogstring` | `0x2022` | `0x208b` | **`+0x69`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f40` | `0x1f68` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x3d0c` | `0x3d2c` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0xd048` | `0xd050` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xfb8` | `0xfb0` | **`-0x8`** |

### Other Changes

```diff

-165.0.0.0.0
+167.0.0.0.0

-  Functions: 1138
-  Symbols:   2359
-  CStrings:  434
+  Functions: 1140
+  Symbols:   2362
+  CStrings:  435
Symbols:
+ -[BNContentViewController _updateFrameForChildContentContainer:minimumTopInsetUpdate:interactive:]
+ -[BNContentViewController preferredMinimumTopInsetDidInvalidateInteractive:]
+ -[BNContentViewController viewDidLayoutSubviews]
+ GCC_except_table101
+ GCC_except_table25
+ GCC_except_table82
+ _CGRectNull
+ _NSStringFromCGRect
+ ___98-[BNContentViewController _updateFrameForChildContentContainer:minimumTopInsetUpdate:interactive:]_block_invoke
- -[BNContentViewController _updateFrameForChildContentContainer:minimumTopInsetUpdate:]
- GCC_except_table24
- GCC_except_table32
- GCC_except_table80
- GCC_except_table99
- ___86-[BNContentViewController _updateFrameForChildContentContainer:minimumTopInsetUpdate:]_block_invoke
CStrings:
+ "Banner frame: natural=%{public}@ minInsets=%{public}@ -> final=%{public}@ (presented=%d orientation=%ld)"
```
