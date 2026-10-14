## QuickLookUICore

> `/System/Library/PrivateFrameworks/QuickLookUICore.framework/QuickLookUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21588` | `0x21654` | **`+0xcc`** |
| `__AUTH_CONST.__objc_const` | `0x7688` | `0x76e8` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2011` | `0x2056` | **`+0x45`** |
| `__AUTH_CONST.__cfstring` | `0x2040` | `0x2080` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x317c` | `0x31a4` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2110` | `0x2128` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x3b0` | `0x3b8` | **`+0x8`** |

### Other Changes

```diff

-1034.1.4.0.0
+1034.1.5.100.0

-  Functions: 1034
-  Symbols:   2155
-  CStrings:  410
+  Functions: 1037
+  Symbols:   2160
+  CStrings:  412
Symbols:
+ -[QLAppearance initWithTopInset:bottomInset:opaqueBottomBarHeight:presentationMode:peripheryInsets:]
+ -[QLAppearance opaqueBottomBarHeight]
+ -[QLItem canShowDocumentMenu]
+ -[QLItem setCanShowDocumentMenu:]
+ _OBJC_IVAR_$_QLAppearance._opaqueBottomBarHeight
+ _OBJC_IVAR_$_QLItem._canShowDocumentMenu
- -[QLAppearance initWithTopInset:bottomInset:presentationMode:peripheryInsets:]
CStrings:
+ "%@ - topInset: %f; bottomInset: %f; opaqueBottomBarHeight: %f; presentationMode: %lu"
+ "canShowDocumentMenu"
+ "opaqueBottomBarHeight"
- "%@ - topInset: %f; bottomInset: %f; presentationMode: %lu"
```
