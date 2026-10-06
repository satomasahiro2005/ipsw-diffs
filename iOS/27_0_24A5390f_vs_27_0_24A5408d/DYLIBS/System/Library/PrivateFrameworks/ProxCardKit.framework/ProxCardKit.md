## ProxCardKit

> `/System/Library/PrivateFrameworks/ProxCardKit.framework/ProxCardKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1dcf4` | `0x1e40c` | **`+0x718`** |
| `__TEXT.__dlopen_cstrs` | `0x101` | `0x1a1` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x308` | `0x338` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fc0` | `0x1ff0` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0xd0` | `0xf8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x810` | `0x838` | **`+0x28`** |
| `__DATA.__bss` | `0x60` | `0x80` | **`+0x20`** |
| `__TEXT.__cstring` | `0x734` | `0x74d` | **`+0x19`** |
| `__TEXT.__objc_methlist` | `0x2dc0` | `0x2dd8` | **`+0x18`** |
| `__TEXT.__const` | `0x228` | `0x230` | **`+0x8`** |

### Other Changes

```diff

-2126.10.4.0.0
+2131.10.1.2.7

-  Functions: 720
-  Symbols:   1742
-  CStrings:  92
+  Functions: 728
+  Symbols:   1752
+  CStrings:  94
Symbols:
+ -[PRXCardContainerView _effectiveSheetInsets]
+ -[PRXCardContainerView _updateSheetInsets]
+ GCC_except_table14
+ _CGRectContainsPoint
+ _PRXShouldFreezeSafeArea
+ _SharingUILibraryCore.frameworkLibrary
+ ___SharingUILibraryCore_block_invoke
+ ___getSFUIProxCardConfiguratorClass_block_invoke
+ _audit_stringSharingUI
+ _getSFUIProxCardConfiguratorClass.softClass
CStrings:
+ "SFUIProxCardConfigurator"
+ "softlink:r:path:/System/Library/PrivateFrameworks/SharingUI.framework/SharingUI"
```
