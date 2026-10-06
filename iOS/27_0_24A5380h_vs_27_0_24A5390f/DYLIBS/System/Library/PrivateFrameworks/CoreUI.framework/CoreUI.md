## CoreUI

> `/System/Library/PrivateFrameworks/CoreUI.framework/CoreUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe6310` | `0xe6000` | **`-0x310`** |
| `__TEXT.__cstring` | `0x25cb7` | `0x25cf7` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x4fa0` | `0x4f88` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0xa438` | `0xa420` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x43e0` | `0x43d8` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x2c78` | `0x2c7c` | **`+0x4`** |

### Other Changes

```diff

-1007.0.0.0.0
+1009.0.0.0.0

-  Functions: 5831
-  Symbols:   9211
-  CStrings:  5501
+  Functions: 5828
+  Symbols:   9208
+  CStrings:  5502
Symbols:
+ ___block_descriptor_72_e8_32o40o48o56r64r_e29_v16?0"NSMutableDictionary"8ls32l8r56l8s40l8s48l8r64l8
- +[CUIThemeFacet themeNamed:forBundle:error:]
- -[CUICommonAssetStorage _swapHeader]
- _RunTimeThemeRefForBundleIdentifierAndName
- ___block_descriptor_80_e8_32o40o48o56o64r72r_e29_v16?0"NSMutableDictionary"8ls32l8r64l8s40l8s48l8s56l8r72l8
CStrings:
+ "CoreUI: Car file '%s' couldn't read swapped header block."
```
